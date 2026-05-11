# Abfallanlagen und Materialentnahmestellen
## Identifikatoren 114.1 und 114.3
### Geobasisdaten des Umweltrechts – Modelldokumentation
**Version 1.2 | Bern, 07.04.2021**
**Bundesamt für Umwelt BAFU / Abfall und Rohstoffe**

---

## Impressum

| | |
|---|---|
| **Offiz. Bezeichner** | Kehrichtverbrennungsanlagen und Deponien des Typs A; Identifikator 114.1 / Materialentnahmestellen; Identifikator 114.3 |
| **FIG** | Yves Degoumois, VS / Martin Eugster, TG / Ivo Lehmann, SZ / Dominik Angst, BAFU / David Bumann, BAFU / Mirjam Zehnder, KKGEO / Christine Najar, GKG/KOGIS |
| **Leiter der FIG** | André Laube, BAFU, Abteilung Abfall und Rohstoffe |
| **Datum** | 07.04.2021 |
| **Version** | 1.2 |

### Änderungskontrolle

| Version | Beschreibung | Datum |
|---|---|---|
| 1.0 | Erstfassung des Modells | 23.06.2015 |
| 1.1 | Aktualisierung aufgrund VVEA/Änderung GeoIV | 26.01.2017 |
| 1.2 | Beschreibung des Darstellungsmodells und Erweiterungsoption zum Darstellungsmodell (im Anhang) hinzugefügt. Anpassungen ILI-File, Hinweis auf Option Attribut «Status» | 07.04.2021 |

---

## Inhaltsverzeichnis

1. Einleitung
2. Konzeptionelles zum Datenmodell
   - 2.1 Überschneidung der Identifikatoren 114 und 116
   - 2.2 Ausgangslage der Erhebung von Informationen zum Identifikator 114.1 und 114.3
   - 2.3 Ziel und Zweck
   - 2.4 Welche Informationen werden wie veröffentlicht?
   - 2.5 NUS
   - 2.6 Umsetzung
3. Modellbeschreibung
4. Modell-Struktur: konzeptionelles Datenmodell
   - 4.1 UML-Klassendiagramm / Grafische Darstellung
   - 4.2 Objektkatalog
5. Darstellungsmodell

**Anhang**
- Anhang 1: Datenmodell im Format INTERLIS 2.3
- Anhang 2: Erweiterungsoption zum Darstellungsmodell (alle zur Entsorgung von Abfällen relevanten Anlagetypen)

---

## 1. Einleitung

**GeoIG** — Seit dem 1. Juli 2008 ist das Bundesgesetz über Geoinformation (GeoIG, SR 510.62) in Kraft. Es hat zum Ziel, auf nationaler Ebene verbindliche bundesrechtliche Standards für die Erfassung, Modellierung und den Austausch von Geodaten¹ des Bundes, insbesondere von Geobasisdaten des Bundesrechts, festzulegen. Weiter regelt es die Finanzierung, das Urheberrecht sowie den Datenschutz. Das Gesetz bildet auch für das Datenmanagement der Kantone und Gemeinden neue, gesicherte rechtliche Grundlagen. So wird sich der Zugang zu den mit grossem Aufwand erhobenen und verwalteten Daten für Behörden, Wirtschaft und Bevölkerung verbessern. Es wird eine Mehrfachnutzung der gleichen Daten in den verschiedensten Anwendungen ermöglichen. Mit der Harmonisierung werden auch Verknüpfungen von Datenbanken möglich, die einfache und neuartige Auswertungen ermöglichen. Die Werterhaltung und die Qualität der Geodaten soll über lange Zeitperioden sichergestellt werden.

**GeoIV** — Mit dem GeoIG ist auch die Verordnung über Geoinformationen (GeoIV, SR 510.620) in Kraft getreten. Sie präzisiert das GeoIG in fachlicher sowie technischer Hinsicht und führt im Anhang 1 die «Geobasisdaten des Bundesrechts» auf. Unter anderem fordert Art. 9 GeoIV ein minimales Geodatenmodell zu einem Geobasisdatensatz (Anhang 1 GeoIV). In jedem Fall ist die entsprechende Bundesstelle in der Verantwortung, dieses Modell zu erstellen, in vielen Fällen in Zusammenarbeit mit den Kantonen. Das Definieren und Beschreiben eines oder mehrerer Darstellungsmodelle (Art. 11 GeoIV) ist hingegen fakultativ.

**VVEA** — Gemäss Art. 45 VVEA gibt das BAFU die minimalen Geodatenmodelle und Darstellungsmodelle für Geobasisdaten nach der Verordnung vor, für die es in Anhang 1 der GeoIV als Fachstelle des Bundes bezeichnet ist.

**Rechtlicher Stellenwert** — Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können (Ebene Kanton oder Gemeinde), um die unterschiedlichen Bedürfnisse im Vollzug abbilden zu können.

> ¹ Begriffe gemäss GeoIG, Art. 3

---

## 2. Konzeptionelles zum Datenmodell

### 2.1 Überschneidung der Identifikatoren 114 und 116

**ID 114: Abfallanlagen** — Nach Art. 31 Abs. 1 des Umweltschutzgesetzes (USG, SR 814.01) legen die Kantone entsprechend der Abfallplanung die Standorte der Abfallanlagen fest. Als wichtige Abfallanlagen gelten nach heutiger Praxis der kantonalen Abfallplanung die Kehrichtverbrennungsanlagen (KVA) und die Deponien. Diese Anlagen werden unter Identifikator 114 «Abfallanlagen» erfasst.

**ID 114.1: KVA und Deponien Typ A** — Nach Art. 35 der Abfallverordnung (VVEA, SR 814.600) dürfen die Kantone fünf Typen von Deponien bewilligen, nämlich die Typen A, B, C, D und E. Deponien des Typs A, in welchen ausschliesslich unverschmutzte Abfälle wie unverschmutztes Aushub- und Ausbruchmaterial zugelassen sind, gelten im Gegensatz zu den anderen Deponietypen nicht als belastete Standorte im Sinne von Art. 2 Abs. 1 der Verordnung über die Sanierung von Altlasten (AltlV, SR 814.680).

**ID 114.3: Materialentnahmestellen** — Materialentnahmestellen (Kiesgruben, Steinbrüche usw.), welche wiederaufgefüllt/rekultiviert werden, gelten nicht als Abfallanlagen, sondern als Standorte für die Verwertung von unverschmutztem Aushub- und Ausbruchmaterial. Aufgrund der Bedeutung dieses Anlagetyps für die kantonalen Abfallplanungen werden sie ergänzend ebenfalls im vorliegenden Modell erfasst.

**ID 114.2 und ID 116: Kataster belasteter Standorte** — Nach Art. 2 Abs. 1 Bst. a AltlV gelten stillgelegte oder noch in Betrieb stehende Deponien und andere Abfallablagerungen als belastete Standorte. Ausgenommen sind Standorte, auf die ausschliesslich unverschmutztes Aushub- oder Ausbruchmaterial gelangt ist (Deponien des Typs A). Daher müssen in Betrieb stehende sowie stillgelegte Deponien der Typen B, C, D und E im Kataster der belasteten Standorte aufgeführt werden. Sie werden deshalb auch durch den Identifikator 116 (Kataster der belasteten Standorte) im Geoinformationssystem erfasst.

Daraus resultiert eine Überlappung der Identifikatoren 114 und 116 (vgl. Abbildung 1).

Aufgrund der Schnittmenge der Identifikatoren 114 und 116 wird für die Modellierung folgende Abgrenzung vorgenommen. Gleichzeitig werden die Materialentnahmestellen als Ergänzung dem Identifikator 114 zugeordnet (vgl. Abbildung 2).

Die in Betrieb stehenden, bzw. stillgelegten aber nach Abschluss noch zu überwachenden Deponien der Typen B, C, D und E erhalten den Identifikator 114.2 und werden gemeinsam mit dem „Kataster der belasteten Standorte" (ID 116) modelliert. Wird eine Deponie nach Ende deren Nachsorge gemäss VVEA nicht mehr überwachungsbedürftig sein, so ist diese Deponie im Datensatz mit Identifikator 114.2 zu löschen. Gleichzeitig ist sicherzustellen, dass ihr Identifikator 116 als belasteter, weder sanierungs- noch überwachungsbedürftiger Ablagerungsstandort im MGDM «Kataster der belasteten Standorte» verbleibt. Die in Betrieb stehenden oder stillgelegten Deponien des Typs A werden gemeinsam unter «Abfallanlagen» mit den Kehrichtverbrennungsanlagen (ID 114.1) modelliert. Ergänzt werden diese mit den Materialentnahmestellen (ID 114.3), welche potenzielle Stellen für die Verwertung von unverschmutztem Aushub- und Ausbruchmaterial (Wiederauffüllung/Rekultivierung) sind.

In diesem Dokument werden nur die Identifikatoren 114.1 «KVA und Deponien des Typs A» und ID 114.3 «Materialentnahmestellen» behandelt. Deponien der Typen B, C, D, und E (ID 114.2) werden gemeinsam mit dem Identifikator 116 modelliert.

---

### 2.2 Ausgangslage der Erhebung von Informationen zum Identifikator 114.1 und 114.3 «Abfallanlagen und Materialentnahmestellen»

«Abfallanlagen und Materialentnahmestellen» beinhalten:

- Kehrichtverbrennungsanlagen
- Deponien des Typs A
- Materialentnahmestellen als Stellen potenzieller Verwertung von unverschmutztem Aushub- und Ausbruchmaterial (Aufnahme aus abfallplanerischen Gründen)

Alle Kehrichtverbrennungsanlagen der Schweiz sind schon als bedeutende Punktquelle von Luftschadstoffen im Schadstoffregister SwissPRTR (www.prtr.ch) georeferenziert.

Deponien des Typs A sind auf Kantonsebene georeferenziert. Die erste nationale Erhebung der Standorte von «DepTypA» wurde abgeschlossen. Diese hat allerdings auch Lücken in den kantonalen Daten aufgezeigt. Jedoch sind die Standortkoordinaten zum grossen Teil vorhanden.

Materialentnahmestellen können Standorte für die Verwertung von unverschmutztem Aushub- und Ausbruchmaterial sein. Deren Standortkoordinaten liegen in einigen Fällen vor, teilweise auch als Polygonflächen.

---

### 2.3 Ziel und Zweck

In erster Linie soll der Identifikator «Abfallanlagen» eine Aussage zur Versorgung des Landes mit Entsorgungskapazität erlauben. Insbesondere bei der Entsorgung von Aushubmaterial ist die Transportdistanz der entscheidende Kostenfaktor. Damit ist die räumliche Verteilung einerseits der Deponien des Typs A zur Ablagerung und andererseits der Materialentnahmestellen zur Verwertung von unverschmutztem Aushub- und Ausbruchmaterial zwecks Wiederauffüllung/Rekultivierung von grossem Interesse. Da Aushubmaterial über Kantonsgrenzen hinweg transportiert wird, ist eine gesamtschweizerische Übersicht wichtig. Sie ergänzt die in den kantonalen Abfallplanungen vorhandenen Geodaten.

---

### 2.4 Welche Informationen werden wie veröffentlicht?

**Veröffentlichung der Daten** — Die Geodaten werden zukünftig der Nationalen Geodateninfrastruktur (NGDI) zur Verfügung gestellt.

---

### 2.5 NUS

**Netzwerk Umweltbeobachtung Schweiz (NUS)** — Aufgrund der Ablösung der NUS-Parameter durch BAFU-Indikatoren (noch im Aufbau) wird auf eine Zuordnung von NUS-Parametern zu den hier beschriebenen Modell-Elementen verzichtet.

---

### 2.6 Umsetzung

**Aufwand für die Umsetzung** — Die Daten für das vorliegende Datenmodell sind bei den Kantonen grösstenteils vorhanden. Es ist nicht davon auszugehen, dass noch viele Daten zusätzlich zu erfassen sind. Der Umsetzungsaufwand beschränkt sich daher auf die Implementierung des Datenmodells, damit der Datentransfer sichergestellt ist.

---

## 3. Modellbeschreibung

Folgende Anlagen sind im Modell abzubilden:

- **Kehrichtverbrennungsanlagen (KVA):** Kehrichtverbrennungsanlagen werden, wie schon im PRTR (www.prtr.ch), als Punkt dargestellt.

- **Deponien des Typs A:** Deponien, auf denen unverschmutzte Abfälle insbesondere unverschmutztes Aushub- und Ausbruchmaterial abgelagert werden. Der betriebliche Status der Deponie wird nicht differenziert². Ein stillgelegter Betrieb kann sich aufgrund des Attributs „nutzbares Ablagerungsvolumen" mit Wert „0" ergeben.

- **Materialentnahmestellen:** Standorte (z. B. Kiesgruben, Steinbrüche u. a. m.) potenzieller Verwertung von unverschmutztem Aushub- und Ausbruchmaterial zwecks Wiederauffüllung/Rekultivierung. Die Materialentnahmestellen werden unabhängig ihres betrieblichen Status' modelliert. Falls keine Wiederauffüllung oder eine Teilauffüllung am Standort besteht, z. B. wegen Biotop, wird dies über den Wert des Attributs „nutzbares Verwertungsvolumen" abgebildet.

Die Unterscheidung in die verschiedenen Anlagetypen geschieht über die Auswahlliste im Attribut «Anlagetyp». Weiter sind die geografische Lage (Geometrie), die Anlagebezeichnung (Name), die BFS-Nr. der Standortgemeinde sowie ein Weblink der zuständigen Bewilligungsbehörde zu erfassen. Bei den Deponien des Typs A und den Materialentnahmestellen ist zudem das gesamte nutzbare Ablagerungs-/Verwertungsvolumen (Kubatur) gemäss Errichtungs-, Abbau- respektive Rekultivierungsbewilligung in m³ Festmass anzugeben, sowie für die Planung die kurzfristig (innert 3 Jahren) und langfristig (innert 4–10 Jahren) verfügbaren Volumina.

Die geografische Lage wird bei den KVA wie auch bei den Deponien des Typs A und den Materialentnahmestellen als Punktkoordinate erfasst. Diese entspricht den Koordinaten (x/y) der Einfahrt, Waage oder Anmeldestelle der Anlage. Zusätzlich zum Punkt kann, falls erwünscht und bekannt, die Lage auch als Polygon erfasst werden.

> ² Bei Deponien Typ A wie auch bei Materialentnahmestellen kann es nach Bedarf nützlich sein ein optionales «Status»- oder «Nachnutzungs»-Attribut oder Ähnliches zu differenzieren, z. B. wenn Weiternutzungen als Ruderalstandorte, Biotope etc. unterschieden werden sollen. Allein aus abfallplanerischer Sicht ergibt sich hierin keine zwingende Notwendigkeit.

---

## 4. Modell-Struktur: konzeptionelles Datenmodell

### 4.1 UML-Klassendiagramm / Grafische Darstellung

```
┌─────────────────────────────────┐     ┌──────────────────────────────────┐
│ Anlage                          │     │ TypBeschreibung                  │
├─────────────────────────────────┤     ├──────────────────────────────────┤
│ Anlagetyp[1] : Typ              │     │ Typ[1] : Typ                     │
│ Geografische_Lage[1] : Geometrie│     │ Beschreibung[1] : MultilingualText│
│ Anlagebezeichnung[1] : Zeichen- │     └──────────────────────────────────┘
│   kette                         │
│ BFS_Nr[1..*] : BFSNummer        │     ┌──────────────────────────────────┐
│ URL_Behoerde[1] : Zeichenkette  │     │ Geometrie                        │
│ Kubatur_gesamt[0..1] : Numerisch│     ├──────────────────────────────────┤
│ Kubatur_kfr[0..1] : Numerisch   │     │ Polygon[0..1] : Polygon          │
│ Kubatur_lfr[0..1] : Numerisch   │     │ Punkt[1] : Coord2                │
│ Erfassungsjahr[0..1] : Numerisch│     └──────────────────────────────────┘
└─────────────────────────────────┘

Erfassungsjahr ist zu erfassen, falls Kubatur_kfr oder Kubatur_lfr erfasst ist.
Kubaturen (alle 3) sind zu erfassen, wenn Anlagetyp gleich Materialentnahmestelle oder DepTypA.
```

---

### 4.2 Objektkatalog

**Klasse Anlage**

| Attributname | Merkmal (Attribut) | Datentyp | Kardinalität | Erlaubte Einträge | Bemerkungen |
|---|---|---|---|---|---|
| Anlagetyp | Typ | Aufzählung | obligatorisch | Kehrichtverbrennungsanlage (KVA), Deponie des Typs A (DepTypA), Materialentnahmestelle (MatEntS) | Aufzählung als Strukturklasse modelliert (grau in UML-Diagramm), mehrsprachig |
| Geografische_Lage | Geometrie | — | obligatorisch | GIS-Polygone oder GIS-Punktkoordinaten des Standorts | Mindestens Punkt muss erfasst sein. Als Strukturklasse modelliert (grau in UML-Diagramm) |
| Anlagebezeichnung | Anlagebezeichnung | Text [50] | obligatorisch | Name der Anlage | z. B. KVA Weinfelden, Kiesgrube Moos |
| BFS_Nr | BFS-Nummer der Standortgemeinde(n) | Zahl [100..9999] | obligatorisch | — | Notwendig, um ohne GIS-Analyse über eine Gemeinde eine Abfrage betr. der Anlagen zu machen. Es können mehrere Gemeinden von einer Anlage betroffen sein. |
| URL_Behoerde | URL der Behörde | URI | obligatorisch | Webseite der zuständigen kommunalen Bewilligungsbehörde | Federführende Baubewilligungsbehörde auf kommunaler Ebene |
| Kubatur_gesamt | Gesamtes nutzbares Ablagerungs- resp. Verwertungsvolumen in m³ Festmass | Zahl | bedingt obligatorisch | — | Für Deponien des Typs A oder Materialentnahmestellen sind die Kubaturen gemäss Errichtungs-, Abbau- respektive Rekultivierungsbewilligung zwingend zu erheben. |
| Kubatur_kfr | Kurzfristig nutzbares Ablagerungs- resp. Verwertungsvolumen in m³ Festmass | Zahl | bedingt obligatorisch | — | Für Deponien des Typs A oder Materialentnahmestellen zwingend zu erheben. Kurzfristig bedeutet innerhalb der kommenden 3 Jahre. |
| Kubatur_lfr | Langfristig nutzbares Ablagerungs- resp. Verwertungsvolumen in m³ Festmass | Zahl | bedingt obligatorisch | — | Für Deponien des Typs A oder Materialentnahmestellen zwingend zu erheben. Langfristig bedeutet innerhalb der kommenden 4–10 Jahre. |
| Erfassungsjahr | Jahr der letzten Anpassung der kurzfristig und langfristig nutzbaren Kubaturen | Zahl | bedingt obligatorisch | — | Muss erfasst werden, falls kurzfristig und/oder langfristig nutzbare Kubaturen erfasst sind. |

---

## 5. Darstellungsmodell

Das Darstellungsmodell ist verbindlich für alle Webpublikationen auf dem Portal der NGDI. In allen anderen Zusammenhängen kann das Darstellungsmodell verwendet werden, muss aber nicht.

Als Hintergrundkarte sind vorzugsweise graustufige Karten in verschiedenen Massstäben zu benutzen.

Standorte von Abfallanlagen und Materialentnahmestellen werden gemäss dem entsprechenden Anlagentyp, wie in der nachstehenden Tabelle aufgezeigt, dargestellt. Zur besseren Hervorhebung der Signaturen werden diese mit weisser Umrandung dargestellt.

Zur Unterscheidung der Anlagetypen werden 3 Signaturformen verwendet; Rechteck mit Kamin für KVA auf abgerundetem Quadrat, Kreis für Deponien und kopfstehendes Dreieck für Materialentnahmestellen.

Die Darstellungspriorität erfolgt folgendermassen (Vordergrund in den Hintergrund):

1. Entnahmestelle (ID 114.3)
2. Deponie Typ A (ID 114.1)
3. *Deponie Typ B (ID 114.2) (vgl. Anhang 2, fakultativ)*
4. *Deponie Typ C (ID 114.2) (vgl. Anhang 2, fakultativ)*
5. *Deponie Typ D (ID 114.2) (vgl. Anhang 2, fakultativ)*
6. *Deponie Typ E (ID 114.2) (vgl. Anhang 2, fakultativ)*
7. Kehrichtverbrennungsanlage (ID 114.1)

| Anlagetyp | Signatur | Grösse [Pixel] | RGB | Umrandung |
|---|---|---|---|---|
| Materialentnahmestelle | ▼ | 30 | 115/76/0 | weiss |
| Deponie Typ A | ○ | 41 | 76/230/0 | weiss |
| Kehrichtverbrennungsanlage | ▪ | 30 | 255/0/0 | weiss |
| Materialentnahmestelle und Deponie Typ A | ▼○ | — | — | weiss |

Die Darstellung der Abfallanlagen und Materialentnahmestellen erfolgt als Punkt. Dieser entspricht den Koordinaten (x/y, LV95 oder LV03) der Einfahrt, Waage oder Anmeldestelle der Anlage³.

Deponien des Typs A, welche – im Gegensatz zu den anderen Deponietypen – nicht zu belasteten Standorten zählen, sind in grüner Kreissignatur festgehalten. Die vorkommende Kombination von Materialentnahmestelle und gleichzeitiger Deponie des Typs A an einem Standort wird folglich durch eine kopfstehende Dreiecks- und eine Kreissignatur dargestellt. Aufgrund der Priorisierung überlagern sich die beiden einzeln erfassten Punkte zu einer Kombination, welche als abschliessende Darstellungsform verstanden werden kann.

**Weitere Angaben zu Anlagetypen:** Weitere Informationen zu den dargestellten Anlagesignaturen können durch deren Anklicken als Textfeld (tooltip) abgerufen werden:

- Anlagebezeichnung
- ggf. Deponietyp, ggf. Kategorie der Materialentnahmestelle (Kies, Steine, Ton/Lehm)
- Standortgemeinde
- URL der zuständigen Behörde
- Kubatur gesamt
- Andere optionale Angaben (kantonal)

> ³ In Anlehnung an BAFU (2019) Berichterstattung nach VVEA. Ein Modul der Vollzugshilfe zur Verordnung über die Vermeidung und Entsorgung von Abfällen. Bundesamt für Umwelt, Bern. Umwelt-Vollzug Nr. 1826: 65 S.

---

## Anhang 1: INTERLIS-Beschreibung

> Bei Abweichungen zwischen dem in dieser Modelldokumentation aufgelisteten Modell und dem im Model Repository gilt das Modell im Model Repository.

```interlis
INTERLIS 2.3;

!!------------------------------------------------------------------------------
!! 2021-02-04 | BAFU | STRUCTURE TypBeschreibung zu CLASS umdefiniert; LV03 gelöscht;
!!              Korrekturen bei beschreibenden Texten
!! 2021-04-07 | BAFU | Korrektur bei Beschreibungen der Kubatur-Attribute
!!==============================================================================

!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ IDGeoIV="114.1, 114.3"

MODEL Abfallanlagen_MatEntnahmestellen_V1_2 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2021-04-07" =
  IMPORTS Units, GeometryCHLV95_V1, LocalisationCH_V1;

  TOPIC Anlagen =

    DOMAIN
      BFSNummer = 1000 .. 9999;
      Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord3 WITHOUT OVERLAPS > 0.001;

      /** Aufzaehlung des Anlagetyps, codiert */
      Typ = (
        KVA,
        DepTypA,
        MatEntS
      );

    STRUCTURE BFSNummer_ = value : MANDATORY BFSNummer; END BFSNummer_;

    /** Struktur Geometrie, zur Beschreibung der Lage der Anlage */
    STRUCTURE Geometrie =
      /** GIS-Polygone zu Beschreibung von Lage und Ausdehnung der Anlage */
      Polygon : Polygon;
      /** Punkt zur Beschreibung der geografischen Lage der Anlage */
      Punkt : MANDATORY GeometryCHLV95_V1.Coord2;
    END Geometrie;

    CLASS TypBeschreibung =
      /** Anlagetyp */
      Typ : MANDATORY Typ;
      /** Mehrsprachiger Name des Anlagetyps */
      Beschreibung : MANDATORY LocalisationCH_V1.MultilingualText;
    END TypBeschreibung;

    /** Beschreibung der Anlage */
    CLASS Anlage =
      /** Typ der Anlage: Kehrichtverbrennungsanlage, Deponie Typ A, Materialentnahmestelle (Auswahlliste)
       * Die Verbindung mit Indikator 116, wo die weiteren Deponietypen
       * (Reaktor-, Reststoff, und Inertstoffdeponien) modelliert sind, muss gewährleistet werden.
       */
      Anlagetyp : MANDATORY Typ;

      /** Geografische Lage der Anlage
       * (entweder Punkt oder Polygon, mindestens eines der beiden muss erfasst sein)
       */
      Geografische_Lage : MANDATORY Abfallanlagen_MatEntnahmestellen_V1_2.Anlagen.Geometrie;

      /** Name der Anlage */
      Anlagebezeichung : MANDATORY TEXT*50;

      /** BFS-Nummer der Standortgemeinde(n), es können mehrere Gemeinden angegeben werden. */
      BFS_Nr : BAG {1..*} OF BFSNummer_;

      /** URI der zuständigen kommunalen Bewilligungsbehörde */
      URL_Behoerde : MANDATORY INTERLIS.URI;

      /** Gesamtes nutzbares Ablagerungs- resp. Verwertungsvolumen in m3 Festmass,
       * für Deponien des Typs A oder Materialentnahmestellen sind die Kubaturen
       * gemäss Errichtungsbewilligung zwingend zu erheben.
       */
      Kubatur_gesamt : 0.000 .. 999999999.000 [Units.m3];

      /** Kurzfristig nutzbares Volumen in m3 Festmass,
       * für Deponien des Typs A oder Materialentnahmestellen sind die Kubaturen zwingend zu erheben.
       * Kurzfristig bedeutet innerhalb der kommenden 3 Jahre.
       */
      Kubatur_kfr : 0.000 .. 999999999.999 [Units.m3];

      /** Langfristig nutzbares Volumen in m3 Festmass,
       * für Deponien des Typs A oder Materialentnahmestellen sind die Kubaturen zwingend zu erheben.
       * Langfristig bedeutet innerhalb der kommenden 4 – 10 Jahre.
       */
      Kubatur_lfr : 0.000 .. 999999999.000 [Units.m3];

      /** Jahr der letzten Anpassung der kurzfristig und langfristig nutzbaren Kubaturen.
       * Muss erfasst werden, falls kurzfristig und/oder langfristig nutzbare Kubaturen erfasst sind.
       */
      Erfassungsjahr : 1900 .. 2999;

      MANDATORY CONSTRAINT ((Anlagetyp != #DepTypA) OR (DEFINED (Kubatur_gesamt)));
      MANDATORY CONSTRAINT ((Anlagetyp != #MatEntS) OR (DEFINED (Kubatur_gesamt)));
      MANDATORY CONSTRAINT ((Anlagetyp != #DepTypA) OR (DEFINED (Kubatur_kfr)));
      MANDATORY CONSTRAINT ((Anlagetyp != #MatEntS) OR (DEFINED (Kubatur_kfr)));
      MANDATORY CONSTRAINT ((Anlagetyp != #DepTypA) OR (DEFINED (Kubatur_lfr)));
      MANDATORY CONSTRAINT ((Anlagetyp != #MatEntS) OR (DEFINED (Kubatur_lfr)));
      MANDATORY CONSTRAINT (NOT (DEFINED (Kubatur_kfr)) OR (DEFINED (Erfassungsjahr)));
      MANDATORY CONSTRAINT (NOT (DEFINED (Kubatur_lfr)) OR (DEFINED (Erfassungsjahr)));

    END Anlage;

  END Anlagen;

END Abfallanlagen_MatEntnahmestellen_V1_2.
```

---

## Anhang 2: Optionale Erweiterung des Darstellungsmodells
*(alle für die Entsorgung von Abfällen relevanten Anlagetypen)*

Vorliegendes Modell beschränkt sich auf die Kehrichtverbrennungsanlagen, die Deponien Typ A sowie die Materialentnahmestellen. Es liegt jedoch nahe, dass insbesondere die Darstellung aller für die Entsorgung von Abfällen relevanten Anlagen von allgemeinem Interesse sein dürfte. Das bedingt die Mitberücksichtigung der Deponien der Typen B, C, D und E (ID 114.2). Letztere Abfallanlagen sind jedoch aufgrund ihrer Eigenschaft als belastete Standorte gemeinsam mit dem «Kataster der belasteten Standorte» (ID 116.1, 117.1, 118.1 und 119.1) modelliert.

Erst mittels Zusammenführung der drei erforderlichen Identifikatoren ID 114.1, ID 114.3 (Abfallanlagen und Materialentnahmestellen) sowie ID 114.2 (aus Kataster der belasteten Standorte) können alle für die Entsorgung von Abfällen relevanten Anlagetypen dargestellt werden. Die zusätzlichen Deponie-Typen können wie folgt dargestellt und gemäss Kapitel 5 kombiniert werden:

| Anlagetyp | Signatur | Grösse [Pixel] | RGB | Umrandung |
|---|---|---|---|---|
| Deponie Typ B | ◕ | 40 | 255/170/0 | weiss |
| Deponie Typ C | ◔ | 40 | 255/170/0 | weiss |
| Deponie Typ D | ◑ | 40 | 255/170/0 | weiss |
| Deponie Typ E | ◒ | 40 | 255/170/0 | weiss |
| Deponie mit Kombination Kompartimente Typen B und D | — | — | — | weiss |
| Deponie mit Kombination Kompartimente Typen A und B | — | — | — | weiss |
| Materialentnahmestelle und Deponie Typ B | ▼◕ | — | — | weiss |

Zur besseren Hervorhebung der Signaturen auf dem Kataster der belasteten Standorte, welcher alle Farbstufen nutzt, werden die Signaturen mit weisser äusserer Umrandung dargestellt.

Mit der Segmentierung des Kreises lassen sich die verschiedenen Deponie- respektive Kompartimentstypen unterscheiden. Deponien des Typs A, welche nicht zu den belasteten Standorten zählen, sind in grüner Kreissignatur festgehalten. Die anderen Deponie- respektive Kompartimentstypen werden mit orangefarbenen Viertelkreis-Segmenten dargestellt, wobei das im Uhrzeigersinn erste Segment Typ B, das zweite Typ C, das dritte Typ D und das vierte Segment Typ E bedeutet.

Die häufig vorkommende Kombination von Materialentnahmestelle und gleichzeitiger Deponie der Typen A oder B an einem Standort wird folglich durch eine kopfstehende Dreiecks- und eine darunterliegende Kreissignatur dargestellt.
