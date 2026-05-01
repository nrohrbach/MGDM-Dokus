# Waldreservate – Identifikator 160

**Geobasisdaten des Umweltrechts – Modelldokumentation**

**Version 2.0** | Bern, 23.01.2025

**Bundesamt für Umwelt BAFU / BnL**

---

## Metadaten

| Feld | Inhalt |
|---|---|
| Offiz. Bezeichner | Waldreservate; Identifikator 160 |
| FIG (Fachinformationsgemeinschaft) | Kantonale GIS-Zuständige im Bereich Wald: Catherine Guex, Anne-Mickaëlle Golay und Gilles Gachet (VD), Michael Opiasa (AG), Anja Bader (ZH), Romain Blanc (NE), Roman Meyer (BL), Simon Crameri (GR), BAFU: Thomas Bettler (Abt. Wald), Peter Staub (KGK), Pasquale Di Donato (KOGIS) |
| Leiter der FIG | Bruno Lauper, BAFU BnL (Fachinhalte); Dominik Angst, BAFU I&S (technisch) |
| Datum | 23.01.2025 |
| Version | In Bearbeitung |

### Änderungskontrolle

| Version | Beschreibung | Datum |
|---|---|---|
| 1.0 | Erstfassung des Modells | 24.04.2014 |
| 1.1 | Technische Anpassungen der Modellstruktur: UML, Objektklassen, INTERLIS | 09.05.2015 |
| 1.2 | Aufnahme von Attributen zur Sicherung des Informationsbedarfs sowie Angaben zur Sicherung der Datenqualität, Arbeitsversion für Pilotphase mit KGK. Ergänzungen für ÖREB gemäss ÖREB-Rahmenmodell (Stand 15.04.2021). LV03 gelöscht. | 12.12.2023 |
| 2.0 | Finale Version | 23.01.2025 |

---

## Inhaltsverzeichnis

1. [Einleitung](#1-einleitung)
2. [Ziel und Zweck](#2-ziel-und-zweck)
   - 2.1 Informationsbedarf
   - 2.2 Umsetzung
   - 2.3 Objekte – Definition
   - 2.4 Kommunikation
   - 2.5 Nachführung – Aktualisierung
   - 2.6 Begriffe aus dem GeoIG
3. [Modellbeschreibung](#3-modellbeschreibung)
4. [Modell-Struktur; konzeptionelles Datenmodell](#4-modell-struktur-konzeptionelles-datenmodell)
   - 4.1 Graphische Darstellung
   - 4.2 Objektklassenkatalog
5. [Darstellung der Daten der Waldreservate](#5-darstellung-der-daten-der-waldreservate)
   - 5.1 Darstellungsmodell Bund

**Anhang**

- I: Geschützte Waldflächen in Europa – Die internationale Klassifizierung der MCPFE
- II: Datenmodell im Format INTERLIS 2.3
- III: Darstellungsmodell der Waldreservate

---

## 1. Einleitung

**Grundlagen**

Waldreservate sind wichtige Instrumente zur Förderung der ökologischen und biologischen Vielfalt im Wald; sie stossen auf ein grosses Interesse in der Umweltpolitik, bei Naturschutzorganisationen und in der breiten Öffentlichkeit. Bund und Kantone haben sich verpflichtet, bis 2030 10 % der Waldfläche als Waldreservate auszuscheiden. Damit Bund und Kantone über die Fortschritte der Reservatspolitik umfassend informieren und diese steuern können, benötigen sie zuverlässige Daten zu den rechtskräftigen Waldreservaten, die im vorliegenden Dokument beschrieben werden.

Das vorliegende Minimale Geobasisdatenmodell (MGDM) erlaubt im Sinne der Harmonisierung auch die Erfassung anderer Waldreservate, z. B. nach kantonalem Recht. Jedoch dürfen gemäss diesem MGDM nur vertraglich oder durch eine Schutzanordnung gesicherte, rechtskräftige Waldreservate publiziert werden (NGDI, geodienste.ch, ÖREB-Kataster). Werden andere Waldreservate publiziert (z. B. im ÖREB-Kataster), sind sie entsprechend zu kennzeichnen.

**GeoIG**

Seit dem 1. Juli 2008 ist das Bundesgesetz über Geoinformation (GeoIG) in Kraft. Es hat zum Ziel, auf nationaler Ebene verbindliche bundesrechtliche Standards für die Erfassung, Modellierung und den Austausch von Geodaten des Bundes, insbesondere von Geobasisdaten des Bundesrechts, festzulegen. Weiter regelt es die Finanzierung, das Urheberrecht sowie den Datenschutz. Das Gesetz bildet auch für das Datenmanagement der Kantone und Gemeinden neue, gesicherte rechtliche Grundlagen.

**GeoIV**

Mit dem GeoIG ist auch die Verordnung über Geoinformationen (GeoIV) in Kraft getreten. Sie präzisiert das GeoIG in fachlicher sowie technischer Hinsicht und führt im Anhang 1 die „Geobasisdaten des Bundesrechts" auf. Unter anderem bestimmt Art. 9 GeoIV, dass die zuständige Fachstelle des Bundes ein minimales Geodatenmodell zu jedem Geobasisdatensatz vorgibt (Anhang 1 GeoIV). Für die Geobasisdatensätze im Bereich der Umwelt ist die zuständige Fachstelle des Bundes das BAFU. Soweit der Vollzug der jeweiligen Bestimmungen bei den Kantonen liegt, erfolgt die Erarbeitung des Datenmodells in Zusammenarbeit mit den Kantonen. Schliesslich sieht die GeoIV in Verbindung mit der entsprechenden Verordnung des Umweltrechts vor, dass das BAFU auch ein minimales Darstellungsmodell vorgibt (Art. 11 GeoIV, Art. 66a Waldverordnung).

**Waldgesetz und NFA-Programmvereinbarungen**

Das Bundesgesetz für den Wald („Waldgesetz" – WaG, SR 921.0) gibt in Art. 20 Abs. 4 den Kantonen die Möglichkeit, „zur Erhaltung der Artenvielfalt von Flora und Fauna angemessene Flächen als Waldreservate auszuscheiden". Gemäss Art. 38 Abs. 1a WaG unterstützt der Bund den Schutz und den Unterhalt von Waldreservaten mit Finanzhilfen.

**Rechtlicher Stellenwert**

Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können (Ebene Kanton oder Gemeinde). Für die Kantone ist das nachfolgende minimale Geodatenmodell verbindlich. Es ist ihnen freigestellt, in ihre Datenmodelle zusätzliche Informationen zu integrieren.

---

## 2. Ziel und Zweck

### 2.1 Informationsbedarf

**Bedeutung der Waldreservate für den Naturschutz**

Die biologische Vielfalt hängt vom ökologischen Zustand der ganzen Landschaft ab. Ein wesentliches Element darin ist bei uns der Wald, der 30 % der Landesfläche bedeckt und auf den mindestens 20 000 der auf über 50 000 Arten geschätzten Fauna und Flora als Lebensraum angewiesen sind. Obwohl der Wald zu den vergleichsweise naturnahen Ökosystemen gehört, weist er regional und lokal ökologische Defizite auf, die sich in den Roten Listen diverser waldgebundener Organismengruppen manifestieren.

Das nachhaltigste, in der Öffentlichkeit meistbeachtete und wissenschaftlich validierte Instrument zur Förderung der Biodiversität im Wald sind Waldreservate: Eine bestimmte Waldfläche wird endgültig aus der normalen Waldbewirtschaftung herausgenommen mit dem Ziel, die ökologische und biologische Vielfalt passiv oder aktiv zu fördern.

**Aktive Information Bund und Kantone**

Bund und Kantone wollen aktiv und umfassend über die Fortschritte in der Waldreservatspolitik informieren. Dafür und für die weitere Steuerung ihrer Politik brauchen sie zuverlässige und deshalb konsistent erhobene Daten, die mit dem vorliegenden Projekt bereitgestellt werden.

### 2.2 Umsetzung

Die Geodaten der Waldreservate liefern Bund und Kantonen eine verlässliche Grundlage für die Gestaltung und Kommunikation ihrer Waldreservatspolitik. Im Einzelnen dient die Statistik folgenden Zwecken:

- **a) Erfolgskontrolle und Politik-Steuerung:** Ermöglicht die Beurteilung der bisherigen Reservatspolitik (Zahl, Fläche, Verteilung, regionale und ökologische Repräsentativität usw.) und damit die Grundlage für die künftige Steuerung dieser Politik.
- **b) Planungsinstrument:** Dank der Einbindung in das NUS dient die Datenbank auch der Planung bzw. Beurteilung von verschiedenartigen Grossprojekten auf nationaler und kantonaler Ebene (z. B. neue Parkprojekte).
- **c) Berichterstattung national und international:** Der Datensatz ist Grundlage für die Öffentlichkeitsarbeit betreffend Waldreservate, sowie für die internationale Berichterstattung im Rahmen diverser biodiversitäts- und forstpolitischer Konventionen (CBD, MCPFE, SoFE).

### 2.3 Objekte – Definition

Es werden ausschliesslich vertraglich oder durch eine Schutzanordnung gesicherte Waldreservate im engeren Sinne erfasst, im Sinne des Waldgesetzes (SR 921.0):

Waldreservate sind auf Dauer angelegte Schutzflächen mit absolutem Vorrang Ökologie und biologische Vielfalt. Ihr Perimeter ist definiert. Ihr Schutzstatus ist behörden- und eigentümerverbindlich gesichert – i. d. R. auf mindestens 50 Jahre für Naturwaldreservate und 25 Jahre für Sonderwaldreservate, mit Verlängerungsoption.

### 2.4 Kommunikation

Die Geodaten werden zukünftig in der NGDI und im ÖREB-Kataster zur Verfügung gestellt. Es werden nur die vertraglich oder durch eine Schutzanordnung gesicherten, rechtskräftigen Flächen der Waldreservate gemäss diesem MGDM publiziert.

In nationalen und internationalen Berichten, auf der Webseite des BAFU, in Broschüren und Fachartikeln werden vorwiegend Statistiken publiziert, die von allgemeinem nationalem Interesse sind. Ausserdem ist eine internetbasierte Datenbank vorgesehen, welche themenbezogene oder regions- und kantonsspezifische Abfragen ermöglicht.

### 2.5 Nachführung – Aktualisierung

Die Geobasisdaten Waldreservate sollen alle 2 Jahre aktualisiert werden. Die entsprechenden Datenlieferungen der Kantone erfolgen jeweils zusammen mit den Jahresberichten NFA Waldbiodiversität.

### 2.6 Begriffe aus dem GeoIG

| Begriff | Definition |
|---|---|
| **Geodaten** | Raumbezogene Daten, die mit einem bestimmten Zeitbezug die Ausdehnung und Eigenschaften bestimmter Räume und Objekte beschreiben, insbesondere deren Lage, Beschaffenheit, Nutzung und Rechtsverhältnisse. (Beispiel: digitale Strassenkarten, Adressverzeichnis von Routenplanern) |
| **Geobasisdaten** | Geodaten, die auf einem rechtsetzenden Erlass des Bundes, eines Kantons oder einer Gemeinde beruhen. (Beispiel: Amtliche Vermessung, Bauzonenplan, Hochmoorinventar) |
| **Georeferenzdaten** | Informationen, die im Anhang 1 der GeoIV als Geodaten klassiert sind. |

---

## 3. Modellbeschreibung

### 3.1 Zu erfassende Daten

Es sind die Geodaten des gesamten Waldreservatsperimeters zu erfassen, der aus räumlich getrennten Perimetern besteht und auch Nichtwaldflächen einschliessen kann (Felsen, Schutthalden, Trockenrasen, subalpine Weiden und Rasen usw.), sofern diese Fläche noch als Waldareal im Sinne des WaG gelten und den geltenden kantonalen Vorgaben entsprechen.

Ausserdem werden die Geodaten der Teilobjekte gemäss internationaler Klassifizierung der MCPFE erfasst (siehe Anhang I):

1. keinerlei Eingriffe gestattet
2. minimale Eingriffe möglich
3. Eingriffe zu Naturschutzzwecken vorgesehen

Als Attribut zu den Geodaten ist für jedes Reservatsobjekt die offizielle, im Vertrag ausgewiesene Fläche (Attribut „Vertragsflaeche") anzugeben.

Die Zuordnung zu den IUCN-Kategorien ist nicht Bestandteil des Datenmodells, sie wird bei Bedarf durch das BAFU vorgenommen:

- MCPFE1.1 = IUCN Kat Ia und Ib
- MCPFE1.2 = IUCN Kat II
- MCPFE1.3 = IUCN Kat IV

Im Zuge der Bereitstellung der Geodaten werden folgende Regeln erfüllt:

- Objekte im Polygondatensatz dürfen sich innerhalb des Datensatzes nicht überlappen (no self-overlap).
- Objekte im Polygondatensatz müssen vollständig innerhalb einer Kantonsfläche aus den aktuellen swissBoundaries-Daten liegen (must be Covered by).

---

## 4. Modell-Struktur; konzeptionelles Datenmodell

### 4.1 Graphische Darstellung

Das UML-Diagramm zeigt folgende Klassen und Beziehungen:

```
Waldreservat
├── ObjNummer[1] : Zeichenkette
├── Name[1] : Zeichenkette
└── Vertragsflaeche[1] : Numerisch
    └── 1 ──< 1..* ──> Waldreservat_Teilobjekt
        ├── TeilObjNummer[1] : Zeichenkette
        ├── MCPFE_Class[1] : MCPFE_Class_CatRef
        ├── PrioGebiet[1] : Prioritaet
        ├── Schutzziele[1..*] : Schutzziele
        ├── NFA_Finanzierung[1] : Boolean
        ├── Geo_Obj[1] : Polygon
        ├── Rechtsstatus[1] : RechtsstatusArt
        ├── publiziertAb[1] : XMLDate
        └── publiziertBis[0..1] : XMLDate

Amt
├── Name[1] : MultilingualText
├── AmtImWeb[0..1] : MultilingualUri
├── UID[0..1] : Zeichenkette
├── Zeile1[0..1] : Zeichenkette
├── Zeile2[0..1] : Zeichenkette
├── Strasse[0..1] : Zeichenkette
├── Hausnr[0..1] : Zeichenkette
├── PLZ[0..1] : Zeichenkette
└── Ort[0..1] : Zeichenkette

Dokument
├── Typ[1] : DokumentTyp
├── Titel[1] : MultilingualText
├── Abkuerzung[0..1] : MultilingualText
├── OffizielleNr[0..1] : MultilingualText
├── NurInGemeinde[0..1] : CHMunicipalityCode
├── TextImWeb[0..1] : MultilingualUri
├── Dokument[0..1] : MultilingualBlob
├── AuszugIndex[1] : Numerisch
├── Rechtsstatus[1] : RechtsstatusArt
├── publiziertAb[1] : XMLDate
└── publiziertBis[0..1] : XMLDate

Schutzziele
├── Schutzziel[1] : Schutzziel_CatRef
└── SchutzzielBemerkung[0..1] : Zeichenkette

Prioritaet (Enumeration)
├── ja_hauptsaechlich
├── ja_teilweise
└── nein

RechtsstatusArt (Enumeration)
├── inKraft
├── AenderungMitVorwirkung
└── AenderungOhneVorwirkung

DokumentTyp (Enumeration)
├── Rechtsvorschrift
├── GesetzlicheGrundlage
└── Hinweis
```

### 4.2 Objektklassenkatalog

#### 4.2.1 Klasse Waldreservat: Objektblatt (Geodaten für jedes Reservat)

| Nr. | Merkmal (Attribut) | Erklärung | Datentyp | Beispiel | Bemerkungen | Pflichtattribut |
|---|---|---|---|---|---|---|
| A1.1 | ObjNummer | Eindeutiger Code zur Kennzeichnung des Objekts | TEXT | 160_ZH_306 | Aufbau: `[GeoIG_ID]_[Kantonskürzel]_[ObjNummer]`. GeoIG_ID für Waldreservate = 160. Kantonskürzel: 2-stellig. | Obligatorisch [1] |
| A1.2 | Name | Bezeichnung des Waldreservats | TEXT | Sihlwald | Offizielle kantonale Bezeichnung des Reservats (wie in der Vereinbarung/Vertrag enthalten) | Obligatorisch [1] |
| A1.3 | Vertragsflaeche | Vertragsfläche des Objektes in ha | NUMERISCH | 10.53 ha | Gesamtfläche des vertraglich oder durch eine Schutzanordnung festgelegten, rechtskräftigen Waldreservats, begrenzt auf die Waldfläche gemäss WaG und Definition des Kantons. | Obligatorisch [1] |

#### 4.2.2 Klasse Waldreservat_Teilobjekt: Obligatorische Geodaten für Waldreservatsobjekte

| Nr. | Merkmal (Attribut) | Erklärung | Datentyp | Beispiel | Bemerkungen | Pflichtattribut |
|---|---|---|---|---|---|---|
| A2.1 | TeilObjNummer | Identifikationsnummer des Teilobjekts | TEXT | – | Kantonsinterne Identifikationsnummer. Ein Teilobjekt ist notwendig, weil das Waldreservat aus mehreren geografisch getrennten Teilen bestehen kann oder verschiedene Schutzziele hat (z. B. verschiedene MCPFE-Codes). | Obligatorisch [1] |
| A2.2 | MCPFE_Class | Code zur Kennzeichnung der 3 internat. Schutzflächentypen 1, 2 und 3 gemäss Tabelle in Anhang I | AUFZÄHLUNG | MCPFE1.3 | Definition MCPFE-Class siehe unten | Obligatorisch [1] |
| A2.3 | PrioGebiet | Prioritäre Gebiete | JA hauptsächlich / JA teilweise / NEIN | JA hauptsächlich | > 65% der Fläche → ja überwiegend; 10–65% → ja teilweise; < 10% → nein | Obligatorisch [1] |
| A2.4 | Schutzziel | Schutzziel | AUFZÄHLUNG | Waldlebensräumen | Auswahl mehrerer Schutzziele möglich | Obligatorisch [1] |
| A2.4.1 | SchutzzielBemerkung | Freitext zur weiteren Beschreibung der Schutzziele | MTEXT | Freier, mehrzeiliger Text | Erlaubt Präzisierungen z. B. bei Aktionsplänen (Auerhuhn, Mittelspecht usw.), traditioneller Bewirtschaftung (Wytweiden, Selven, Niederwald usw.) oder Auenwald / seltenen Waldgesellschaften. | Nicht obligatorisch [0..1] |
| A2.5 | NFA_Finanzierung | Finanzierung mit Beteiligung Bundesträger | JA/NEIN (BOOLEAN) | JA | Finanzierung mit Beteiligung von Bundesmitteln des NFA (Nationaler Finanzausgleich) | Obligatorisch [1] |
| A2.6 | Geo_Obj | Ausdehnung des Objekts | POLYGON | – | Die Summe der Flächen der Teilobjekte soll gleich der Vertragsfläche des Waldreservats sein. Kleine Abweichungen können vorkommen. | Obligatorisch [1] |
| A2.7 | Rechtsstatus | Besagt, ob das Objekt in Kraft ist. | AUFZÄHLUNG | inKraft | Es sollen nur die rechtskräftigen Flächen publiziert werden. | Obligatorisch [1] |
| A2.8 | publiziertAb | Datum, ab dem das Objekt in Kraft ist. | INTERLIS.XMLDate | 2017-08-27 | Datum des Vertragsbeginns. | Obligatorisch [1] |
| A2.9 | publiziertBis | Datum, bis wann der Vertrag läuft. | INTERLIS.XMLDate | 2017-08-27 | Datum des Vertragsendes, sofern bekannt. | Nicht obligatorisch [0..1] |

#### 4.2.3 Klasse Dokument

| Nr. | Merkmal (Attribut) | Erklärung | Datentyp | Beispiel | Pflichtattribut |
|---|---|---|---|---|---|
| A3.1 | Typ | Typ des Dokuments | AUFZÄHLUNG | Rechtsvorschrift | Obligatorisch [1] |
| A3.2 | Titel | Titel des Dokuments | TEXT | Waldgesetz | Obligatorisch [1] |
| A3.3 | Abkuerzung | Abkürzung des Gesetzes | TEXT | WaG | Nicht obligatorisch [0..1] |
| A3.4 | OffizielleNr | Offizielle Nummer des Gesetzes | TEXT | SR 921.0 | Nicht obligatorisch [0..1] |
| A3.5 | NurInGemeinde | BFSNr falls eine Vorschrift der Gemeinde | AUFZÄHLUNG | 942 | Nicht obligatorisch [0..1] |
| A3.6 | TextImWeb | Verweis auf das Dokument im Web | MultilingualURI | http://www.admin.ch/ch/d/sr/c921_0.html | Nicht obligatorisch [0..1] |
| A3.7 | Dokument | Das Dokument als PDF-Datei | MultilingualBlob | – | Nicht obligatorisch [0..1] |
| A3.8 | AuszugIndex | Ordnungszahl für die Sortierung im Auszug | ZAHL | 1 | Bereich (-1000, 1000) | Obligatorisch [1] |
| A3.9 | Rechtsstatus | Unterscheidung ob eine Zone in Kraft oder in Änderung ist. | AUFZÄHLUNG | inKraft | Obligatorisch [1] |
| A3.10 | publiziertAb | Datum, ab dem dieses Element in Auszügen erscheint. | INTERLIS.XMLDate | 2017-08-27 | Obligatorisch [1] |
| A3.11 | publiziertBis | Datum, bis zu dem dieses Element in Auszügen erscheint. | INTERLIS.XMLDate | 2017-08-27 | Nicht obligatorisch [0..1] |

#### 4.2.4 Klasse Amt

| Nr. | Merkmal (Attribut) | Erklärung | Datentyp | Beispiel | Pflichtattribut |
|---|---|---|---|---|---|
| A4.1 | Name | Name des Amtes | TEXT | Amt für Wald und Naturgefahren des Kantons Graubünden | Obligatorisch [1] |
| A4.2 | AmtImWeb | Verweis auf die Website des Amtes | MultilingualURI | http://www.wald.gr.ch/ | Nicht obligatorisch [0..1] |
| A4.3 | UID | Unternehmens-Identifikationsnummer | TEXT | – | Nicht obligatorisch [0..1] |
| A4.4 | Zeile1 | – | TEXT | – | Nicht obligatorisch [0..1] |
| A4.5 | Zeile2 | – | TEXT | – | Nicht obligatorisch [0..1] |
| A4.6 | Strasse | Name der Strasse | TEXT | – | Nicht obligatorisch [0..1] |
| A4.7 | Hausnr | Nummer des Hauses | TEXT | – | Nicht obligatorisch [0..1] |
| A4.8 | PLZ | Postleitzahl | TEXT | – | Nicht obligatorisch [0..1] |
| A4.9 | Ort | Name des Ortes | TEXT | – | Nicht obligatorisch [0..1] |

#### 4.2.5 Entität MCPFE_Class

| Code | DE | FR | IT | EN |
|---|---|---|---|---|
| MCPFE1.1 | Keine aktiven Eingriffe | Pas d'interventions actives | Nessun intervento attivo | No active intervention |
| MCPFE1.2 | Minimale Eingriffe | Interventions minimales | Interventi minimi | Minimum Intervention |
| MCPFE1.3 | Biodiversitätsförderung durch gezielte Eingriffe | Promotion de la biodiversité par des interventions ciblées | Promozione delle biodiversità per mezzo di interventi specifici | Conservation through active management |

#### 4.2.6 Entität Schutzziel

| Code | DE | FR | IT | EN |
|---|---|---|---|---|
| Prozessschutz | Zulassen der natürlichen Waldentwicklung | Laisser libre cours au développement naturel de la forêt | Permettere lo sviluppo naturale della foresta | Allowing natural forest development |
| LichteWaelder | Lichte Wälder wiederherstellen und pflegen | Restaurer et entretenir les forêts claires | Mantenere e ripristinare i boschi radi | Restoring and maintaining open woodlands |
| FeuchteWaelder | Feuchte Wälder erhalten und wiederherstellen | Maintenir et restaurer les forêts humides | Mantenere e ripristinare le foreste umide | Maintaining and restoring wet forests |
| Bewirtschaftungsformen | Besondere Bewirtschaftungsformen erhalten | Maintenir les formes d'exploitation particulières | Mantenere forme tradizionali di sfruttamento | Maintaining traditional forms of exploitation |
| AndereNPA/NPLAufwertung | Erhaltung anderer seltener Waldgesellschaften oder national prioritärer Arten | Maintenir d'autres associations forestières rares ou espèces prioritaires au niveau national | Mantenere altre associazioni forestali rare o specie prioritarie a livello nazionale | Maintaining other rare forest associations or priority species at national level |
| GenDiv | Erhaltung der genetischen Vielfalt (Generhaltungsgebiete) | Préserver la diversité génétique (aires de conservation génétique) | Conservazione della diversità genetica (zone di conservazione genetica) | Conservation of genetic diversity (genetic conservation units) |

#### 4.2.7 Entität DokumentTyp

| Code | DE | FR | IT | EN |
|---|---|---|---|---|
| Rechtsvorschrift | Rechtsvorschrift | Norme juridique | Prescrizione legale | Legal provision |
| GesetzlicheGrundlage | Gesetzliche Grundlage | Base légale | Base legale | Legal basis |
| Hinweis | Hinweis | Mention | Indicazione | Note |

#### 4.2.8 Entität RechtsstatusArt

| Code | DE | FR | IT | EN |
|---|---|---|---|---|
| inKraft | In Kraft | En vigueur | In vigore | In force |
| AenderungMitVorwirkung | Änderung mit Vorwirkung | Modification avec effet anticipé | Modifica con effetto anticipato | Amendments with advance effect |
| AenderungOhneVorwirkung | Änderung ohne Vorwirkung | Modification sans effet anticipé | Modifica senza effetto anticipato | Amendments without advance effect |

---

## 5. Filterfunktion zur ÖREB-Transferstruktur

Dieses Kapitel definiert die Transformation der Daten entsprechend dem vorliegenden Datenmodell in die Transferstruktur des Rahmenmodells für den ÖREB-Kataster.

| Modell `Waldreservate_v1_2.ili` | Rahmenmodell ÖREB-Kataster (Transferstruktur) |
|---|---|
| Waldreservat_Teilobjekt.Rechtsstatus | Eigentumsbeschraenkung.Rechtsstatus |
| Waldreservat_Teilobjekt.publiziertAb | Eigentumsbeschraenkung.publiziertAb |
| Waldreservat_Teilobjekt.publiziertBis | Eigentumsbeschraenkung.publiziertBis |
| Waldreservat_Teilobjekt.Geo_Obj | Geometrie.Flaeche |
| Waldreservat_Teilobjekt.Rechtsstatus | Geometrie.Rechtsstatus |
| Waldreservat_Teilobjekt.publiziertAb | Geometrie.publiziertAb |
| Waldreservat_Teilobjekt.publiziertBis | Geometrie.publiziertBis |
| Dokument.Typ | Dokument.Typ |
| Dokument.Titel | Dokument.Titel |
| Dokument.Abkuerzung | Dokument.Abkuerzung |
| Dokument.OffizielleNr | Dokument.OffizielleNr |
| Dokument.NurInGemeinde | Dokument.NurInGemeinde |
| Dokument.TextImWeb | Dokument.TextImWeb |
| Dokument.Dokument | Dokument.Dokument |
| Dokument.AuszugIndex | Dokument.AuszugIndex |
| Dokument.Rechtsstatus | Dokument.Rechtsstatus |
| Dokument.publiziertAb | Dokument.publiziertAb |
| Dokument.publiziertBis | Dokument.publiziertBis |
| Amt.Name | Amt.Name |
| Amt.AmtImWeb | Amt.AmtImWeb |
| Amt.UID | Amt.UID |
| Amt.Zeile1 | Amt.Zeile1 |
| Amt.Zeile2 | Amt.Zeile2 |
| Amt.Strasse | Amt.Strasse |
| Amt.Hausnr | Amt.Hausnr |
| Amt.PLZ | Amt.PLZ |
| Amt.Ort | Amt.Ort |
| z. B. `https://wms.geo.admin.ch/?SERVICE=WMS&REQUEST=GetMap&VERSION=1.3.0&LAYERS=...` | DarstellungsDienst.VerweisWMS |

| Modell `Waldreservate_Codelisten_V1_2.ili` | Rahmenmodell ÖREB-Kataster (Transferstruktur) |
|---|---|
| MCPFE_Class_Catalogue.Symbol | LegendeEintrag.Symbol |
| MCPFE_Class_Catalogue.Description | LegendeEintrag.LegendeText |
| MCPFE_Class_Catalogue.Code | LegendeEintrag.ArtCode |
| https://models.geo.admin.ch/BAFU/Waldreservate_Catalogues_V1_2_20211202.xml | LegendeEintrag.ArtCodeliste |
| Konstanter Wert `ch.Waldreservate` | LegendeEintrag.Thema |

---

## 6. Darstellung der Daten der Waldreservate

### 6.1 Darstellungsmodell Bund

Die Daten über die vertraglich oder durch eine Schutzanordnung gesicherten, rechtskräftigen Waldreservate sind für das BAFU die Grundlage für die Erfolgskontrolle und die Steuerung der Waldreservatspolitik. Es werden daraus Statistiken für nationale und internationale Berichte generiert und in grafisch attraktiver Form dargestellt.

Die hier definierte Darstellung der Waldreservate gilt für die Publikationen von vertraglich oder durch eine Schutzanordnung gesicherten, rechtskräftigen Flächen durch den Bund (in der NGDI, inkl. geodienste.ch) und im ÖREB-Kataster.

---

## Anhang I – Geschützte Waldflächen in Europa: Die internationale Klassifizierung der MCPFE

Um einen internationalen Vergleich der verschiedenen in den europäischen Ländern gebräuchlichen Waldschutz-Typen zu ermöglichen, hat eine technische Arbeitsgruppe im Auftrag der „Ministerkonferenz zum Schutze der Wälder in Europa" (MCPFE) eine einheitliche Klassifizierung vorgeschlagen.

Das Originaldokument: http://www.ogm.gov.tr/yukle/protected.pdf

### Europäische Klassifizierung der Biodiv-Schutzflächen im Wald (MCPFE)

| Schutzflächen-Typ | Auflagen bzw. mögliche Eingriffe | Bemerkungen / Beispiele aus der Schweiz |
|---|---|---|
| **1.1 – No active intervention** | Zugang für Öffentlichkeit eingeschränkt; nicht-destruktive Forschung zugelassen | Jede direkte Beeinflussung durch den Menschen ist ausgeschlossen. Auch bei Borkenkäfer-Kalamitäten oder Waldbrand wird nicht eingegriffen; die Jagd ist untersagt. In der Schweiz die Ausnahme – im Mittelland praktisch nicht möglich. *Beispiele: Wald im Nationalpark GR; Kernzone des Bödmerenwaldes SZ; Fichtenurwald Scaté in Breil/Brigels GR.* |
| **1.2 – Minimum intervention** | Wildregulation (Jagd) möglich; Forstschutzmassnahmen (beschränkt); Waldbrandbekämpfung; nicht-destruktive Forschung; Sicherheitsschläge an Strassen; Subsistenz-Nutzung durch einheimische Bevölkerung | Der Normalfall eines Naturwaldreservates bzw. einer Altholzinsel in der Schweiz. Grundsätzlich wird die natürliche Waldentwicklung zugelassen, aber wenn Katastrophen drohen, kann eingegriffen werden. *Beispiele: Kernzone Sihlwald ZH; Combe Grède Chasseral BE.* |
| **1.3 – Conservation through active management** | Zusätzlich zu 1.2: gezielte Eingriffe zur Förderung der Biodiversität; Holznutzung möglich, sofern im Einklang mit dem Reservatsziel | Grosse Teile von sog. „Sonderwaldreservaten". *Beispiele: Erhaltung von Alteichen und Begründung neuer Eichenbestände in Mittelspechtgebieten; Entbuschung von Felsen und Geröllhalden mit Reptilienpopulationen; Auslichten von Balzplätzen des Auerhuhns in Bergwäldern.* |

---

## Anhang II – Datenmodell im Format INTERLIS 2.4

> Bei Abweichungen zwischen dem in dieser Modelldokumentation aufgelisteten Modell und dem im Model Repository gilt das Modell im Model Repository.

```interlis
INTERLIS 2.4;

!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ IDGeoIV=160.1

/*
Dieses MGDM gilt für vertraglich gesicherte, rechtskräftige Waldreservatsflächen
im Sinne des Waldgesetzes (SR 921.0).
Für Waldreservatsflächen mit Rechtsstatus "Änderung mit/ohne Vorwirkung" dürfen
die Kantone dieses Modell nutzen, diese Daten sind als kantonale Daten auszuweisen.
*/

MODEL Waldreservate_V2_0 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2025-01-23" =
  IMPORTS CatalogueObjects_V2, Units, GeometryCHLV95_V2, LocalisationCH_V2,
          CHAdminCodes_V2, InternationalCodes_V2;

  /* Topic für externe Codelisten */
  TOPIC Codelisten
  EXTENDS CatalogueObjects_V2.Catalogues =

    CLASS MCPFE_Class_Catalogue
    EXTENDS CatalogueObjects_V2.Catalogues.Item =
      Symbol : MANDATORY BLACKBOX BINARY;
      Code : MANDATORY TEXT*8;
      Description : MANDATORY LocalisationCH_V2.MultilingualText;
    END MCPFE_Class_Catalogue;

    CLASS Schutzziel_Catalogue
    EXTENDS CatalogueObjects_V2.Catalogues.Item =
      Code : MANDATORY TEXT*30;
      Description : MANDATORY LocalisationCH_V2.MultilingualText;
    END Schutzziel_Catalogue;

  END Codelisten;

  TOPIC Waldreservate =
  DEPENDS ON Waldreservate_V2_0.Codelisten;

    DOMAIN
      Prioritaet = (ja_hauptsaechlich, ja_teilweise, nein);
      DokumentTyp = (Rechtsvorschrift, GesetzlicheGrundlage, Hinweis);
      RechtsstatusArt = (inKraft, AenderungMitVorwirkung, AenderungOhneVorwirkung);

      /* Flächen ohne Kreisbogen */
      Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V2.Coord2
                WITHOUT OVERLAPS > 0.001;

    STRUCTURE LocalisedUri =
      Language : InternationalCodes_V2.LanguageCode_ISO639_1;
      Text : MANDATORY URI;
    END LocalisedUri;

    STRUCTURE MultilingualUri =
      LocalisedText : BAG {1..*} OF LocalisedUri;
      UNIQUE (LOCAL) LocalisedText:Language;
    END MultilingualUri;

    STRUCTURE LocalisedBlob =
      Language : InternationalCodes_V2.LanguageCode_ISO639_1;
      Blob : MANDATORY BLACKBOX BINARY;
    END LocalisedBlob;

    STRUCTURE MultilingualBlob =
      LocalisedBlob : BAG {1..*} OF LocalisedBlob;
      UNIQUE (LOCAL) LocalisedBlob:Language;
    END MultilingualBlob;

    STRUCTURE Schutzziele =
      Schutzziel : MANDATORY REFERENCE TO (EXTERNAL)
                   Waldreservate_V2_0.Codelisten.Schutzziel_Catalogue;
      SchutzzielBemerkung : MTEXT*255;
    END Schutzziele;

    /* Klasse für das gesamte Waldreservat */
    CLASS Waldreservat =
      ObjNummer : MANDATORY TEXT*30;
      Name : MANDATORY TEXT*80;
      Vertragsflaeche : MANDATORY 0.00 .. 999999.00 [Units.ha];
    END Waldreservat;

    /* Klasse für die Waldreservat-Teilgebiete */
    CLASS Waldreservat_Teilobjekt =
      TeilObjNummer : MANDATORY TEXT*30;
      MCPFE_Class : MANDATORY REFERENCE TO (EXTERNAL)
                    Waldreservate_V2_0.Codelisten.MCPFE_Class_Catalogue;
      PrioGebiet : MANDATORY Prioritaet;
      Schutzziele : BAG {1..*} OF Schutzziele;
      NFA_Finanzierung : MANDATORY BOOLEAN;
      Geo_Obj : MANDATORY Polygon;
      Rechtsstatus : MANDATORY RechtsstatusArt;
      publiziertAb : MANDATORY INTERLIS.XMLDate;
      publiziertBis : INTERLIS.XMLDate;
    END Waldreservat_Teilobjekt;

    CLASS Dokument =
      Typ : MANDATORY DokumentTyp;
      Titel : MANDATORY LocalisationCH_V2.MultilingualText;
      Abkuerzung : LocalisationCH_V2.MultilingualText;
      OffizielleNr : LocalisationCH_V2.MultilingualText;
      NurInGemeinde : CHAdminCodes_V2.CHMunicipalityCode;
      TextImWeb : MultilingualUri;
      Dokument : MultilingualBlob;
      AuszugIndex : MANDATORY -1000 .. 1000;
      Rechtsstatus : MANDATORY RechtsstatusArt;
      publiziertAb : MANDATORY INTERLIS.XMLDate;
      publiziertBis : INTERLIS.XMLDate;
      MANDATORY CONSTRAINT DEFINED (TextImWeb) OR DEFINED(Dokument);
    END Dokument;

    CLASS Amt =
      Name : MANDATORY LocalisationCH_V2.MultilingualText;
      AmtImWeb : MultilingualUri;
      UID : TEXT*12;
      Zeile1 : TEXT*80;
      Zeile2 : TEXT*80;
      Strasse : TEXT*100;
      Hausnr : TEXT*7;
      PLZ : TEXT*4;
      Ort : TEXT*40;
      UNIQUE UID;
    END Amt;

    ASSOCIATION WaldreservatWaldreservat_Teilobjekt =
      WR_Teilobjekt -- {1..*} Waldreservat_Teilobjekt;
      WR -<#> {1} Waldreservat;
    END WaldreservatWaldreservat_Teilobjekt;

    ASSOCIATION DokumentWaldreservat =
      Dokument -- {0..*} Dokument;
      Waldreservat_Teilobjekt -- {0..*} Waldreservat_Teilobjekt;
    END DokumentWaldreservat;

    ASSOCIATION AmtDokument =
      Amt -- {1} Amt;
      Dokument -<> {0..*} Dokument;
    END AmtDokument;

  END Waldreservate;

END Waldreservate_V2_0.
```

---

## Anhang III – Darstellungsmodell Waldreservate

Die hier definierte Darstellung gilt für die Publikationen von rechtskräftigen Flächen durch den Bund (in der NGDI, inkl. geodienste.ch) und im ÖREB-Kataster. Die Verwendung in den Kantonen wird empfohlen.

Als Hintergrund wird empfohlen, nur die graustufigen Karten gemäss Geobasisdatenkatalog (Anhang 1 GeoIV) in verschiedenen Massstäben zu benutzen (keine Farben).

**Layer Transparency:** 30%

**Outline (alle Kategorien):**
- Type: Line
- Width: 0.1
- Farbname: Leaf Green
- RGB: 56, 168, 0

### Symbolisierung – Rechtsstatus = in Kraft

| | MCPFE1.1 | MCPFE1.2 | MCPFE1.3 |
|---|---|---|---|
| Farbname | Tarragon Green | Macaw Green | Tzavorite Green |
| RGB | 112, 168, 0 | 152, 230, 0 | 211, 255, 190 |

Flächen vollständig ausgefüllt (simple fill).

### Symbolisierung – Rechtsstatus = Änderung mit/ohne Vorwirkung

| | MCPFE1.1 | MCPFE1.2 | MCPFE1.3 |
|---|---|---|---|
| Farbname | Tarragon Green | Macaw Green | Tzavorite Green |
| RGB | 112, 168, 0 | 152, 230, 0 | 211, 255, 190 |

Grüne, vertikale Schraffur gemäss MCPFE-Kategorie auf weissem Hintergrund.
