
### Bundesamt für Umwelt BAFU /AÖL


# Ruhezonen für


# Wildtiere (inkl.


# Routennetz)


# Identifikatoren 195.1


# und 195.2


# Geobasisdaten des Umweltrechts


# Modelldokumentation


# Version 2.1

Bern, 25.01.2021

**Offiz. Bezeichner**

Wildruhezonen (GeoIV p. 34); Identifikatoren 195.1
und 195.2

**FIG**

Roman Guidon, AREG Kt. SG
Mirjam Ballmer, KWL
Rolf Zürcher, KOGIS
Mirjam Zehnder, KKGEO
Dominik Angst, BAFU
Helmut Recher, BAFU AÖL (technische
Anforderungen)
Thomas Gerner, BAFU AÖL (Fachspezialist
Wildruhezonen)

**Leiter der FIG**

Helmut Recher, BAFU AÖL

**Datum**

10.12.2019

**Version**

Verabschiedete Version
Änderungskontrolle
Version
Beschreibung
Datum
1.0
Erstfassung des Modells
24.02.2015
1.1
Technische Anpassungen der Modellstruktur: UML,
Objektklassen, INTERLIS
17.05.2017
2.0
Anpassung gemäss abschliessender Rückmeldung
aus Pilotprojekt:
- Ergänzung Kap. 3.2 Datenbereitstellung und
Qualitätssicherung
- Ergänzung optionales Attribut «RefKanton» (Klasse
Wildruhezone_Teilobjekt) für einen Link zu weiteren
kantonalen Informationen
- Übernommene Anpassungen aus Anhörung (FIG,
Kantone)
10.12.2019
2.1
Multipolygone eingeführt und Datentyp
Wildruhezone_Teilobjekt.Geo_Obj als MultiPolygon
definiert
23.01.2020
2.1
Patch-Change ILI: Zweiter Constraint in CLASS
Wildruhezone_Teilobjekt angepasst
21.04.2020
2.1
Patch-Change Modelldokument: Ergänzung
Empfehlung in Darstellung für W2
25.08.2020
2.1
Korrektur: falscher Kapitelverweis
25.01.2021
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu den Wildruhezonen 3
2.2.
Umsetzung .............................................................................................. 3
2.3.
Welche Objekte werden erfasst? ............................................................ 3
2.4.
Welche Informationen werden wie veröffentlicht? ................................... 3
2.5.
Aufwand ................................................................................................... 4
2.6.
Begriffe aus dem GeoIG .......................................................................... 4

### 3.


### Modellbeschreibung ............................................................... 5

3.1.
Wildruhezonen......................................................................................... 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 5

4.1.
Graphische Darstellung ........................................................................... 5
4.2.
Objektklassenkatalog .............................................................................. 6
4.3.
Datenbereitstellung und Qualitätssicherung .........................................12
4.4.
Beschreibung mit INTERLIS 2.3 ...........................................................12

### 5.


### Darstellung der Daten der Wildruhezonen ......................... 13

5.1.
Darstellungsmodell Bund ......................................................................13

### Anhang

I
Datenmodell im Format INTERLIS 2.3
BAFU2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Sport und Erholung in der Natur liegen im Trend - sei es Wandern, Mountainbiking,
Hängegleiten im Sommer oder Tourenskifahren und Schneeschuhlaufen im
Winter. Bei all diesen Aktivitäten bewegt man sich im Lebensraum von Wildtieren
wie Rothirsch, Gämse, Steinbock oder Birkhuhn. Diese reagieren zu bestimmten
Zeiten sensibel auf Beunruhigungen durch Menschen. Gerade im Winter sind sie
wegen der Kälte und dem spärlichen Nahrungsangebot besonders auf Ruhe
angewiesen.
Als Wildruhezonen werden die Gebiete ausgeschieden, welche für Säugetiere und
Vögel als Rückzugsgebiete besonders wichtig sind (z.B. Wintereinstandsgebiete).
Wildruhezonen erlauben es, die Lebensraumnutzung von Mensch und Wildtier
zeitlich und räumlich zu entflechten, indem der Zutritt für Freizeitnutzer während
den sensiblen Zeiten eingeschränkt ist. Die Störungsvermeidung ist laut
Jagdgesetzgebung Aufgabe der Kantone. Die Ausscheidung und der Vollzug der
Wildruhezonen in den Kantonen erfolgt nach kantonalem oder kommunalem
Recht. Dies stellt sicher, dass die Wildruhezonen den Verhältnissen vor Ort
angepasst sind. Das BAFU unterstützt und berät die Kantone bei der
Ausscheidung von Wildruhezonen und setzt sich für eine Harmonisierung der
Kennzeichnung im Gelände ein.
Seit dem 1. Juli 2008 ist das Bundesgesetz über Geoinformation (GeoIG) in Kraft.
Es hat zum Ziel, auf nationaler Ebene verbindliche bundesrechtliche Standards für
die Erfassung, Modellierung und den Austausch von Geodaten 1 des Bundes,
insbesondere von Geobasisdaten des Bundesrechts, festzulegen. Weiter regelt es
die Finanzierung, das Urheberrecht sowie den Datenschutz. Das Gesetz bildet
auch für das Datenmanagement der Kantone und Gemeinden eine neue,
gesicherte rechtliche Grundlage. So wird sich der Zugang zu den mit grossem
Aufwand erhobenen und verwalteten Daten für Behörden, Wirtschaft und
Bevölkerung verbessern. Es wird eine Mehrfachnutzung der gleichen Daten in den
verschiedensten Anwendungen ermöglichen. Mit der Harmonisierung werden auch
Verknüpfungen
von
Datenbanken
möglich,
die
einfache
und
neuartige
Auswertungen ermöglichen. Die Werterhaltung und die Qualität der Geodaten soll
über lange Zeitperioden sichergestellt werden.
Mit dem GeoIG ist auch die Verordnung über Geoinformation (GeoIV) in Kraft
getreten. Sie präzisiert das GeoIG in fachlicher sowie technischer Hinsicht und
führt im Anhang 1 die „Geobasisdaten des Bundesrechts“ auf. Unter anderem
bestimmt Art. 9 GeoIV, dass die zuständige Fachstelle des Bundes ein minimales
Geodatenmodell zu jedem Geobasisdatensatz vorgibt (Anhang 1 GeoIV). Für die
Geobasisdatensätze im Bereich der Umwelt ist die zuständige Fachstelle des
Bundes das BAFU. Soweit der Vollzug der jeweiligen Bestimmungen bei den
Kantonen liegt, erfolgt die Erarbeitung des Datenmodells in Zusammenarbeit mit
1 Begriffe gemäss GeoIG, siehe Kap. 2.6
Grundlagen
GeoIG
GeoIV
BAFU2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
2
den Kantonen. Schliesslich sieht die GeoIV in Verbindung mit der entsprechenden
Verordnung des Umweltrechts vor, dass das BAFU auch ein minimales
Darstellungsmodell vorgibt (Art. 11 GeoIV, Art. 27b NHV (SR 451.1)). Soweit die
Kantone für den Vollzug zuständig sind, werden auch die Darstellungsmodelle von
BAFU und den Kantonen gemeinsam erarbeitet.
Seit dem 20. Juni 1986 ist das Bundesgesetz über die Jagd und den Schutz
wildlebender Säugetiere und Vögel (Jagdgesetz, JSG) in Kraft. Es hat u.a. zum
Ziel, die Artenvielfalt und die Lebensräume der einheimischen und ziehenden
wildlebenden Säugetiere und Vögel zu erhalten und bedrohte Tierarten zu
schützen. Die Störungsvermeidung ist laut Jagdgesetz Aufgabe der Kantone (Art.
7 Abs. 4 JSG). Die Ausscheidung und der Vollzug der Wildruhezonen in den
Kantonen erfolgt nach kantonalem oder kommunalem Recht.
Am 15. Juli 2012 wurde die Verordnung über die Jagd und den Schutz
wildlebender Säugetiere und Vögel (Jagdverordnung, JSV) revidiert. Im neuen Art.
4 ter werden die Bestimmungen des Jagdgesetzes (JSG) präzisiert, indem
festgehalten wird, dass zum Schutz vor Störung Wildruhezonen und die darin zur
Benutzung erlaubten Routen und Wege bezeichnet werden können.
Ausserdem besagt die Verordnung, dass das Bundesamt für Umwelt BAFU die
Kantone unter anderem bei der Bekanntmachung der Wildruhezonen unterstützt.
Die Störungsvermeidung ist laut Jagdgesetz Aufgabe der Kantone (Art. 7 Abs. 4
JSG). Die Ausscheidung und der Vollzug der Wildruhezonen in den Kantonen
erfolgt nach kantonalem oder kommunalem Recht.
Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von
Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können
(Ebene Kanton oder Gemeinde). Für die Kantone ist das nachfolgende minimale
Geodatenmodell gemäss GeoIG verbindlich. Es ist ihnen freigestellt, in ihre
Datenmodelle zusätzliche Informationen zu integrieren.
JSG
JSV
Rechtlicher Stellenwert
BAFU2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu den Wildruhezonen
Wildruhezonen sind für Säugetiere und Vögel wichtige Gebiete, in denen die
Bedürfnisse der Wildtiere im Vordergrund stehen. Sie dienen gemäss Jagdgesetz
(Art. 7 Abs. 4 JSG) der Vermeidung übermässiger Störung als Antwort auf die
zunehmende
Freizeitnutzung.
Wildruhezonen
dürfen
während
bestimmten
Jahreszeiten - oder in einzelnen Fällen während des ganzen Jahres - nicht oder
nur beschränkt für Freizeitaktivitäten genutzt werden.
2.2.
Umsetzung
Um die Sensibilisierung zu verbessern, unterstützt das Bundesamt für Umwelt
BAFU gestützt auf die JSV die Kantone unter anderem bei der Bekanntmachung
der Wildruhezonen.
Mit dem Geobasisdatensatz wird das Ziel verfolgt, die breite Zugänglichkeit zu
Informationen über Lage und geltende Bestimmungen der bestehenden
Wildruhezonen in der Schweiz zu gewährleisten.
Zur Publikation dieser - grundsätzlich in kantonaler Hoheit stehenden - Geodaten
zu den Wildruhezonen in den Landeskarten und im Internet, stellen die Kantone
allfällige Änderungen der Perimeter und der darin zur Benutzung erlaubten Routen
und der relevanten Attribute zu diesen Daten (so z.B. zeitliche Bestimmungen zur
Wildruhe) alljährlich bereit.
2.3.
Welche Objekte werden erfasst?
Wildruhezonen stützen sich auf den Auftrag, wie er im Jagdgesetz und der
Jagdverordnung festgehalten ist. Es gibt rechtsverbindliche und empfohlene
Wildruhezonen.
Rechtsverbindliche
Wildruhezonen
sind
über
den
Rechtssetzungsprozess ausgeschieden (z.B. kantonales Jagdrecht, kommunale
Zonenplanung) und Übertretungen in diesen Gebieten sind strafbar. Empfohlene
Wildruhezonen beruhen auf der Empfehlung einer Behörde oder einer
Vereinbarung zwischen Schutz- und Nutzorganisationen.
2.4.
Welche Informationen werden wie veröffentlicht?
Die kantonalen Daten werden von den Kantonen auf ihren Webseiten in
unterschiedlicher Form präsentiert, die gesamtschweizerische Übersicht ist auf
dem thematischen Fachportal „Wildruhezonen Schweiz“ ( www.wildruhezonen.ch )
verfügbar. Weiter werden die Wildruhezonen auf den Skitourenkarten der
Swisstopo
entsprechend
deren
Nachführungsrhythmus
veröffentlicht.
Die
Geodaten werden zukünftig in der NGDI zur Verfügung gestellt. Das Inventar ist
nicht Bestandteil des ÖREB-Katasters.
Schutz vor Störung
Information der Freizeitnutzer
Kantonale und
kommunale
Schutzbeschlüsse
Veröffentlichung der Daten
BAFU2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
4
2.5.
Aufwand
Die Kantone sind für den Aufbau und die periodische Aktualisierung der Geodaten
der Wildruhezonen zuständig. Das BAFU ist für die Auswertung des Datensatzes
und die Erstellung der Statistiken im nationalen Kontext zuständig.
2.6.
Begriffe aus dem GeoIG
Die nachfolgend verwendeten Begriffe aus dem GeoIG sind wie folgt definiert 2 :
Raumbezogene Daten, die mit einem bestimmten Zeitbezug die Ausdehnung und
Eigenschaften bestimmter Räume und Objekte beschreiben, insbesondere deren
Lage, Beschaffenheit, Nutzung und Rechtsverhältnisse. (Beispiel: digitale
Strassenkarten, Adressverzeichnis von Routenplanern)
Geodaten, die auf einem rechtsetzenden Erlass des Bundes, eines Kantons oder
einer Gemeinde beruhen. (Beispiel: Amtliche Vermessung, Nutzungsplanung,
Bundesinventar der Hoch- und Übergangsmoore von nationaler Bedeutung)
Geobasisdaten, die für weitere Geodaten als geometrische Grundlage dienen.
Diese sind im Anhang 1 der GeoIV als solche klassiert.
2 Art. 3 GeoIG [ http://www.admin.ch/ch/d/sr/510_62/a3.html ]
Geodaten
Geobasisdaten
Georeferenzdaten
BAFU2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Wildruhezonen
Wildruhezonen stützen sich auf den Auftrag, wie er im Jagdgesetz und der
Jagdverordnung festgehalten ist. Es gibt rechtsverbindliche und empfohlene
Wildruhezonen. Die Ausscheidung und Beschreibung der Wildruhezonen inkl. der
erlaubten und begehbaren Routen und Wege liegt in der Kompetenz der Kantone.
Für die Aufnahme in den Geobasisdatensatz ist die Erfassung der Perimeter im
Massstab 1:25‘000 vorgegeben. Für die Erstellung und Nachführung des
Datensatzes werden die Daten in digitaler Form unverändert von den Kantonen
übernommen.

## 4. Modell-Struktur: konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die Abbildung 1 zeigt das UML-Diagramm für die Wildruhezonen inklusive
Routennetz.
Wildruhezone_Teilobjekt
TeilObjNummer[1] : Zeichenkette
Bestimmungen[1] : Bestimmungen_CatRef
Bestimmungen_Kt[0..1] : MultilingualMText
Zusatzinformation[0..1] : Zeichenkette
RefKanton[0..1] : Zeichenkette
Schutzzeit[1] : Zeichenkette
Geo_Obj[1] : MultiPolygon
Routennetz
Geo_Obj[1] : Linie
Wegtyp[1] : Wegtyp_CatRef
Einschraenkung[0..1] : Zeichenkette
Wildruhezone
ObjNummer[1] : Numerisch
Kanton[1] : CHCantonCode
Name[1] : Zeichenkette
Schutzstatus[1] : Schutzstatus_CatRef
Grundlage[1] : Zeichenkette
Beschlussjahr[1] : GregorianYear
Mutationsdatum[0..1] : XMLDate
Mutationsgrund[0..1] : MultilingualMText
Bestimmungen_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Bestimmungen_CatRef
Schutzstatus_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Schutzstatus_CatRef
Wegtyp_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Wegtyp_CatRef
1
1..*
1
0..*
Reference
+
Reference
+
Reference
+
Falls Wegtxp mit Einschränkungen ist <<Einschraenkung>> auszufüllen
Abbildung 1: Darstellung der Wildruhezonen inkl. Routennetz als UML-Diagramm
Anmerkungen: Wildruhezone_Teilobjekt.Geo_Obj: Gültigkeit gemäss Kapitel 4.3
Routennetz.Geo_Obj: Einschränkungen gemäss Kapitel 4.3
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
6
4.2.
Objektklassenkatalog

### Klasse Wildruhezone

Merkmal (Attribut)
Erklärung der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.1
ObjNummer
Code zur
Kennzeichnung des
Objekts
NUMERISCH
0201
Kantonsinterne Identifikationsnummer, die
auf Kantonsebene eindeutig sein muss.
Obligatorisch
A1.2
Kanton
Kantonskürzel
AUFZÄHLUNG
GR
Kantonsliste plus „CH“ für
kantonsübergreifende Eidg.
Wildtierschutzgebiete
Obligatorisch
A1.3
Name
Bezeichnung des
Objekts
TEXT
Tschappina
Obligatorisch
A1.4
Schutzstatus
Schutzstatus
AUFZÄHLUNG
S10
Definition Schutzstatus siehe unten
Obligatorisch
A1.5
Grundlage
Grundlage für die
Schutzbestimmungen
TEXT
Nutzungsplanung
Obligatorisch
A1.6
Beschlussjahr
Jahr des Beschlusses
zur Schaffung der
Wildruhezone
“GregorianYear“
gemäss
INTERLIS
2005
Obligatorisch
A1.7
Mutationsdatum
Datum der Mutation
des Objekts
DATE
01.07.2007
Fakultativ
A1.8
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Vergrösserung
Objekt auf Antrag
Kt
Mehrsprachig
Fakultativ
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
7
Klasse Wildruhezone_Teilobjekt
Merkmal (Attribut)
Erklärung der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.9
TeilObjNummer
Identifikationsnummer
des Teilobjekts
TEXT
Kantonsinterne Identifikationsnummer des
Teilobjekts. Voreingestellter Wert für Objekte
ohne Teilobjekte = 0
Bedingung: Ein eindeutiger Schlüssel für
jeden Datensatz ist aus den drei Merkmalen
Kanton + ObjNummer + TeilObjNummer
erstellbar.
Obligatorisch
A1.10
Bestimmungen
Bestimmungen
AUFZÄHLUNG
R10
Definition Bestimmungen siehe unten
Obligatorisch
A1.11
Bestimmungen_Kt
Kantonale
Bezeichnung
Bestimmung
TEXT
Beschreibung einer im Attribut
„Bestimmungen“ erfassten „Andere
Bestimmung“ (R900, E900). Bei anderen
Bestimmungen bleibt das Feld leer.
Mehrsprachig
Fakultativ
A1.12
Zusatzinformation
Ergänzende
Bemerkungen
TEXT
Lebensraum
Kerngebiet
Besondere Bedingungen müssen im Attribut
Zusatzinformation präzisiert werden, z.B.
"Hunde sind an der Leine zu führen. Auflage
aus wildökologischem Konzept.".
Fakultativ 3
A1.13
RefKanton
Link zu
Detailinformationen,
z.B. Schutzverordnung,
TEXT
URL-Link
Beispiel einer Detailkarte für eine
Wildruhezone:
https://www.fr.ch/sites/default/files/contens/publ/_ww
w/files/jpg21/fr_div_carte_zone_tranquillite_berra_2
Fakultativ
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
8
Detailkarte
0171201.jpg
A1.14
Schutzzeit
Zeitraum der Gültigkeit
der
Schutzbestimmungen
TEXT
16.12 bis 31.03,
Ende Skisaison
Beginn mit gleicher Formatierung dd.mm. –
dd.mm , z.B.  „01.12. - 31.03.“, Zusatztext
jedoch möglich.
Obligatorisch
A1.15
Geo_Obj
Ausdehnung des
Objekts
MultiPolygon
Erfassung im Massstab 1:25‘000 als
Vorgabe, Kreisbogen sind nicht erlaubt.
Obligatorisch
Klasse Routennetz (Wildruhezonen Routennetz)
Merkmal (Attribut)
Erklärung der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.16
Geo_Obj
Ausdehnung des
Objekts
LINIE
Kreisbogen sind nicht erlaubt.
Obligatorisch
A1.17
Wegtyp
AUFZÄHLUNG
W1
Definition Wegtyp siehe unten.
Code zur Kennzeichnung der Weg-
/Routenkategorie
Obligatorisch
A1.18
Einschraenkung
Geltende
Einschränkungen
TEXT(254)
Wege / Routen mit Einschränkungen müssen
im Attribut  «Einschränkung» präzisiert
werden, z.B. "Erlaubt bei geschlossener
Schneedecke".
Fakultativ 4
4 Ein Wegtyp mit Einschränkung (W2) bedingt einen textlichen Eintrag der vorgesehenen Einschränkungen in das Feld Einschraenkung, z.B. «Erlaubt bei geschlossener Schneedecke».
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
9
Entität Wegtyp
Code
DE
FR
IT
W1
Erlaubter Weg / Route
Chemin / itinéraire autorisé
Sentiero / itinerario autorizzato
W2
Weg / Route mit Einschränkung
Chemin / itinéraire avec restriction
Sentiero / itinerario con restrizione
Entität Schutzstatus 5
Code
DE
FR
IT
S10
rechtsverbindlich
contraignant
vincolante
S20
empfohlen
recommandée
raccomandata
Entität Bestimmungen
Code
DE
FR
IT
Rechtsverbindliche Wildruhezonen
Zone de tranquillité contraignantes
Zona di tranquillità vincolante
R10
Zutrittsverbot
Interdiction d’accès
Divieto di accesso
R20
Zutrittsverbot (zu Fuss und Wintersportarten)
Interdiction d’accès (à pied ou pour les sports
d’hiver)
Divieto di accesso (a piedi o per la pratica di
sport invernali)
R30
Zutrittsverbot, durchqueren auf
eingezeichnetem Weg gestattet
Interdiction d‘accès, sauf sur le chemin
indiqué
Divieto di accesso, tranne sui sentieri
segnalati
R40
Zutrittsverbot, durchqueren auf
eingezeichneter Route gestattet
Interdiction d‘accès, sauf sur les itinéraires
indiqués
Divieto di accesso, tranne sui percorsi
segnalati
R50
Zutrittsverbot, durchqueren auf
Interdiction d’accès, sauf sur les itinéraires
indiqués, obligation de tenir les chiens en
Divieto di accesso, tranne sui percorsi
5 Einschränkungen in der Verwendung der Entität „Schutzstatus“ in Verbindung mit der Entität „Bestimmungen“: Ein rechtsverbindlicher Schutzstatus (S10) bedingt die Verwendung einer
rechtsverbindlichen Bestimmung (R10- R900), ein empfohlener Schutzstatus (S20) bedingt die Verwendung einer empfohlenen Bestimmung (E10- E900),
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
10
eingezeichneter Route gestattet, Leinenpflicht
laisse
segnalati; obbligo di tenere i cani al guinzaglio
R60
Zutrittsverbot abseits der eingezeichneten
Wege
Interdiction de quitter les chemins indiqués
Divieto di uscire dai sentieri segnalati
R70
Zutrittsverbot abseits der eingezeichneten
Wege, Leinenpflicht
Interdiction de quitter les chemins indiqués,
obligation de tenir les chiens en laisse
Divieto di uscire dai sentieri segnalati; obbligo
di tenere i cani al guinzaglio
R80
Wegegebot
Obligation de rester sur les chemins
Obbligo di rimanere sui sentieri segnalati
R90
Wegegebot, Leinenpflicht
Obligation de rester sur les chemins et de tenir
les chiens en laisse
Obbligo di rimanere sui sentieri segnalati e di
tenere i cani al guinzaglio
R100
Betreten oder befahren nur auf
eingezeichneten Wegen oder Routen gestattet
Accès autorisé uniquement sur les chemins ou
itinéraires indiqués
Accesso autorizzato solo sui sentieri e i
percorsi segnalati
R110
Betreten oder befahren nur auf Pisten, Loipen
und eingezeichneten Wegen oder Routen
Accès autorisé uniquement sur les pistes ou
les chemins et itinéraires indiqués
Accesso autorizzato solo sulle piste, i sentieri
e i percorsi segnalati.
R120
Betreten oder befahren nur auf Pisten, Loipen
und eingezeichneten Wegen oder Routen,
Leinenpflicht
Accès autorisés uniquement sur les pistes ou
les chemins et itinéraires indiqués, obligation
de tenir les chiens en laisse
Accesso autorizzato solo sulle piste, i sentieri
e i percorsi segnalati; obbligo di tenere i cani
al guinzaglio
R130
Zutrittsverbot, Abfahrt durch eingezeichneten
Korridor gestattet
Interdiction d’accès, descente dans le couloir
indiqué autorisée
Divieto di accesso, è autorizzata la discesa nei
corridoi segnalati
R140
Wintersportverbot
Interdiction de pratiquer des sports d‘hiver
Divieto di praticare sport invernali
R150
Wintersportverbot abseits eingezeichneter
Routen
Interdiction de pratiquer des sports d‘hiver
hors des itinéraires indiqués
Divieto di praticare sport invernali al di fuori
dei percorsi segnalati
R160
Wintersportverbot abseits gekennzeichneter
Pisten
Interdiction de pratiquer des sports d‘hiver
hors des pistes indiquées
Divieto di praticare sport invernali al di fuori
delle piste segnalate
R900
Andere Bestimmung
Autre disposition
Altre disposizioni
Empfohlene Wildruhezonen
Zones de tranquillité recommandées
Zone di tranquillità raccomandate
E10
Bitte nicht betreten
Merci de ne pas entrer dans cette zone
sensible
Si raccomanda di non entrare in questa zona
sensibile
E20
Bitte nicht betreten, durchqueren nur auf
eingezeichneter Route
Merci de ne pas traverser cette zone sensible,
sauf sur les itinéraires indiqués
Si raccomanda di non attraversare questa
zona sensibile, tranne sui percorsi segnalati.
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
11
E30
Bitte nicht betreten, durchqueren nur auf
eingezeichneter Route, Hunde an der Leine
führen
Merci de ne pas traverser cette zone sensible,
sauf sur les itinéraires indiqués, et de tenir les
chiens en laisse
Si raccomanda di non attraversare questa
zona sensibile, tranne sui percorsi segnalati;
obbligo di tenere i cani al guinzaglio.
E40
Bitte eingezeichnete Routen und Wege nicht
verlassen
Merci de ne pas quitter les itinéraires et les
chemins indiqués
Si raccomanda di non abbandonare i percorsi
e i sentieri segnalati.
E50
Bitte eingezeichnete Routen und Wege nicht
verlassen, Hunde an der Leine führen
Merci de ne pas quitter les itinéraires et les
chemins indiqués, tenir les chiens en laisse
Si raccomanda di non abbandonare i percorsi
e i sentieri segnalati; obbligo di tenere i cani al
guinzaglio.
E900
Andere Bestimmung
Autre disposition
Altre disposizioni
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
12
4.3.
Datenbereitstellung und Qualitätssicherung
Die von den Kantonen bereitgestellten Geodaten müssen folgende Anforderungen erfüllen:
Konsistenzbedingungen gemäss Datenmodell
Pflichtattribute vorhanden, Einhaltung der Aufzählungswerte der Kataloge, zusammengesetzter Schlüssel
ist eindeutig (s. A 1.9), keine Überlappung von Objekten im Polygondatensatz der Wildruhezonen, usw.
Inhaltliche Anforderungen
1. Objekte der Wildruhezonen müssen vollständig innerhalb einer
Kantonsfläche liegen 6 .
2. Überlappungen von Objekten der Wildruhezonen mit Objekten der
Jagdbanngebiete/Wildtierschutzgebiete (siehe
https://s.geo.admin.ch/7ccb155f1b) sind zulässig.
Voraussetzung ist, dass die Wildruhezonen zusätzliche Massnahmen zur
Besucherlenkung definieren, welche durch die Verordnung über die
eidgenössischen Jagdbanngebiete nicht bereits abgedeckt sind.
3. Die erlaubten Wege und Routen der Wildruhezonen liegen räumlich
innerhalb und bis maximal 50 Meter Entfernung ausserhalb der
Wildruhezonen.
Für diese inhaltlichen Anforderungen können keine Konsistenzbedingungen im INTERLIS-Modell
formuliert werden. Die Einhaltung der inhaltlichen Vorgaben und ein Abgleich der Geodaten der
Wildruhezonen mit externen Daten (z.B. Jagdbanngebiete) hat vor der Datenbereitstellung durch die
Kantone zu erfolgen.
4.4.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang.
6 Zum Beispiel bietet der swissboundaries-Datensatz der swisstopo hier eine frei verfügbare, harmonisierte Grundlage mit
ausreichender Genauigkeit.
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
13

## 5. Darstellung der Daten der Wildruhezonen

5.1.
Darstellungsmodell Bund
Die Daten der Wildruhezonen (inkl. Routennetz) werden vom BAFU für den Vollzug
des Arten- und Biotopschutzes verwendet. Die Darstellung erfolgt im Rahmen des
Erlasses resp. der jährlichen Updates. Dabei gelangt das folgende geographische
Darstellungsmodell zur Anwendung  für die Verwendung im Rahmen der NGDI
(Abbildungen 2 und 3).
Abbildung 2: Geographische Lage der Wildruhezonen
Legende:
Schutzstatus
Flächen
RGB
Transparenz /
Umrandung
S10
“Red”
RGB: 255,54,26
Transparency: 50%
Outline:
Type: Line
Width: 0.5
“Black”
RGB: 0,0,0
S20
“Yellow”
RGB: 255,204,0
Darstellungsmodell Bund
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
14
Abbildung 3: Routennetz in den Wildruhezonen
Legende:
Wegtyp
Linien / Signatur
RGB / Linientyp
Transparenz
W1
RGB: 56,168,0
Type: Line
Width: 2
Transparency:
0%
W2
RGB: 56,168,0
Type: Gestrichelte Line
mit Markierungssymbol
(Kreis mit
Ausrufezeichen)
Width: 2
Umsetzungsempfehlung:
Gestrichelte Linie:
PATTERN 12 12
Ausrufezeichen: SIZE 8,
CHARACTER !, FONT
NotoSansBold, COLOR
RGB 56 168 0
Kreisring:
Kreis, innen: POINTS 10
10,  FILLED false, COLOR
RGB 255 255 255
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
15
Kreis, aussen: POINTS 10
10,  FILLED true, COLOR
RGB 56 168 0
.
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
16

## Anhang

I Datenmodell im Format INTERLIS 2.3
Bei Abweichungen zw. Modelldokumentation und Model Repository gilt die ILI-Version im Model Repository.
INTERLIS 2.3;
!! Version    | Who  | Modification
!!----------------------------------------------------------------------------------------
!! 2019-10-30 | BAFU | Neue Version 2.0: Ergänzung optionales Attribut «RefKanton» (Klasse Wildruhezone_Teilobjekt)
für einen Link zu weiteren kantonalen Informationen
!!                     Übernommene Anpassungen aus Anhörung (FIG, Kantone)
!! 2020-01-23 | BAFU | Multipolygone eingeführt und Datentyp Wildruhezone_Teilobjekt.Geo_Obj als MultiPolygon
definiert
!! 2020-04-21 | BAFU | Second Constraint in CLASS Wildruhezone_Teilobjekt adapted
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV="195.1, 195.2"
MODEL Wildruhezonen_Codelisten_V2_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2020-01-23"  =
IMPORTS LocalisationCH_V1,CatalogueObjects_V1;
DOMAIN
TypID = OID TEXT*80;
/* Modell für externe Codelisten, die anschliessend importiert werden in die Modelle *_LV03* und *_LV95" */
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
17
TOPIC Codelisten =
BASKET OID AS TypID;
OID AS TypID;
CLASS Bestimmungen_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*5;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Bestimmungen_Catalogue;
CLASS Schutzstatus_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Schutzstatus_Catalogue;
CLASS Wegtyp_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Wegtyp_Catalogue;
STRUCTURE Bestimmungen_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.MandatoryCatalogueReference =
Reference (EXTENDED) : MANDATORY REFERENCE TO (EXTERNAL) Bestimmungen_Catalogue;
END Bestimmungen_CatRef;
STRUCTURE Schutzstatus_CatRef
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
18
EXTENDS CatalogueObjects_V1.Catalogues.MandatoryCatalogueReference =
Reference (EXTENDED) : MANDATORY REFERENCE TO (EXTERNAL) Schutzstatus_Catalogue;
END Schutzstatus_CatRef;
STRUCTURE Wegtyp_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.MandatoryCatalogueReference =
Reference (EXTENDED) : MANDATORY REFERENCE TO (EXTERNAL) Wegtyp_Catalogue;
END Wegtyp_CatRef;
END Codelisten;
END Wildruhezonen_Codelisten_V2_1.
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV="195.1, 195.2"
MODEL Wildruhezonen_LV03_V2_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2020-01-23"  =
IMPORTS GeometryCHLV03_V1,LocalisationCH_V1,CHAdminCodes_V1,Wildruhezonen_Codelisten_V2_1;
TOPIC Wildruhezonen =
DEPENDS ON Wildruhezonen_Codelisten_V2_1.Codelisten;
DOMAIN
/* Linien/Flächen ohne Kreisbogen */
Linie = POLYLINE WITH (STRAIGHTS) VERTEX GeometryCHLV03_V1.Coord2;
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
19
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV03_V1.Coord2 WITHOUT OVERLAPS > 0.001;
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für die gesamten Wildruhezonen */
CLASS Wildruhezone =
ObjNummer : MANDATORY 0 .. 9999;
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
Name : MANDATORY TEXT*80;
Schutzstatus : MANDATORY Wildruhezonen_Codelisten_V2_1.Codelisten.Schutzstatus_CatRef;
Grundlage : MANDATORY TEXT*250;
Beschlussjahr : MANDATORY INTERLIS.GregorianYear;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
END Wildruhezone;
/* Klasse für die Wildruhezonen-Routen */
CLASS Routennetz =
Geo_Obj : MANDATORY Linie;
Wegtyp : MANDATORY Wildruhezonen_Codelisten_V2_1.Codelisten.Wegtyp_CatRef;
Einschraenkung : TEXT*254;
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
20
/* Ein Wegtyp mit Einschränkungen (W2) bedingt einen textlichen Eintrag im Attribut Einschraenkung. Für einen
Wegtyp ohne Einschränkungen (W1) muss das Feld Einschraenkung leer sein. */
MANDATORY CONSTRAINT NOT (Wegtyp->Reference->Code == "W2") OR DEFINED (Einschraenkung);
MANDATORY CONSTRAINT NOT (Wegtyp->Reference->Code == "W1") OR NOT (DEFINED (Einschraenkung));
END Routennetz;
/* Klasse für Wildruhezonen-Teilflächen */
CLASS Wildruhezone_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
Bestimmungen : MANDATORY Wildruhezonen_Codelisten_V2_1.Codelisten.Bestimmungen_CatRef;
Bestimmungen_Kt : LocalisationCH_V1.MultilingualMText;
Zusatzinformation : TEXT*500;
RefKanton : INTERLIS.URI;
Schutzzeit : MANDATORY TEXT*250;
Geo_Obj : MANDATORY MultiPolygon;
/* Wenn Bestimmungen den Status "R900" oder "E900" haben, muss das Feld Bestimmungen_Kt gefüllt sein. Bei anderen
Bestimmungen muss das Feld Bestimmungen_Kt leer sein. */
MANDATORY CONSTRAINT NOT (Bestimmungen->Reference->Code == "R900" OR Bestimmungen->Reference->Code == "E900") OR
DEFINED (Bestimmungen_Kt);
MANDATORY CONSTRAINT (Bestimmungen->Reference->Code == "R900" OR Bestimmungen->Reference->Code == "E900") OR NOT
(DEFINED (Bestimmungen_Kt));
END Wildruhezone_Teilobjekt;
ASSOCIATION RoutennetzWildruhezone =
WRZ_Routennetz -- {0..*} Routennetz;
WRZ -<#> {1} Wildruhezone;
END RoutennetzWildruhezone;
ASSOCIATION Wildruhezone_TeilobjektWildruhezone =
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
21
WRZ_Teilobjekt -- {1..*} Wildruhezone_Teilobjekt;
WRZ -<#> {1} Wildruhezone;
UNIQUE WRZ->Kanton, WRZ->ObjNummer, WRZ_Teilobjekt->TeilObjNummer;
/* Wenn Schutzstatus = S10 "rechtsverbindlich", dann dürfen nur Bestimmungen für rechtsvebindliche Wildruhezonen
erfasst werden, also R*.
Wenn Schutzstatus = S20 "empfohlen", dann dürfen nur Bestimmungen für empfohlene Wildruhezonen erfasst werden,
also E*. */
MANDATORY CONSTRAINT NOT (WRZ->Schutzstatus->Reference->Code == "S10") OR
(WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R10" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R20" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R30" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R40" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R50" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R60" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R70" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R80" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R90" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R100" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R110" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R120" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R130" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R140" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R150" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R160" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R900");
MANDATORY CONSTRAINT NOT (WRZ->Schutzstatus->Reference->Code == "S20") OR
(WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E10" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E20" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E30" OR
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
22
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E40" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E50" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E900");
END Wildruhezone_TeilobjektWildruhezone;
END Wildruhezonen;
END Wildruhezonen_LV03_V2_1.
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV="195.1, 195.2"
MODEL Wildruhezonen_LV95_V2_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2020-01-23"  =
IMPORTS GeometryCHLV95_V1,LocalisationCH_V1,CHAdminCodes_V1,Wildruhezonen_Codelisten_V2_1;
TOPIC Wildruhezonen =
DEPENDS ON Wildruhezonen_Codelisten_V2_1.Codelisten;
DOMAIN
/* Linien/Flächen ohne Kreisbogen */
Linie = POLYLINE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord2;
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord2 WITHOUT OVERLAPS > 0.001;
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
23
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für die gesamten Wildruhezonen */
CLASS Wildruhezone =
ObjNummer : MANDATORY 0 .. 9999;
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
Name : MANDATORY TEXT*80;
Schutzstatus : MANDATORY Wildruhezonen_Codelisten_V2_1.Codelisten.Schutzstatus_CatRef;
Grundlage : MANDATORY TEXT*250;
Beschlussjahr : MANDATORY INTERLIS.GregorianYear;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
END Wildruhezone;
/* Klasse für die Wildruhezonen-Routen */
CLASS Routennetz =
Geo_Obj : MANDATORY Linie;
Wegtyp : MANDATORY Wildruhezonen_Codelisten_V2_1.Codelisten.Wegtyp_CatRef;
Einschraenkung : TEXT*254;
/* Ein Wegtyp mit Einschränkungen (W2) bedingt einen textlichen Eintrag im Attribut Einschraenkung. Für einen
Wegtyp ohne Einschränkungen (W1) muss das Feld Einschraenkung leer sein. */
MANDATORY CONSTRAINT NOT (Wegtyp->Reference->Code == "W2") OR DEFINED (Einschraenkung);
MANDATORY CONSTRAINT NOT (Wegtyp->Reference->Code == "W1") OR NOT (DEFINED (Einschraenkung));
END Routennetz;
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
24
/* Klasse für Wildruhezonen-Teilflächen */
CLASS Wildruhezone_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
Bestimmungen : MANDATORY Wildruhezonen_Codelisten_V2_1.Codelisten.Bestimmungen_CatRef;
Bestimmungen_Kt : LocalisationCH_V1.MultilingualMText;
Zusatzinformation : TEXT*500;
RefKanton : INTERLIS.URI;
Schutzzeit : MANDATORY TEXT*250;
Geo_Obj : MANDATORY MultiPolygon;
/* Wenn Bestimmungen den Status "R900" oder "E900" haben, muss das Feld Bestimmungen_Kt gefüllt sein. Bei anderen
Bestimmungen muss das Feld Bestimmungen_Kt leer sein. */
MANDATORY CONSTRAINT NOT (Bestimmungen->Reference->Code == "R900" OR Bestimmungen->Reference->Code == "E900") OR
DEFINED (Bestimmungen_Kt);
MANDATORY CONSTRAINT (Bestimmungen->Reference->Code == "R900" OR Bestimmungen->Reference->Code == "E900") OR NOT
(DEFINED (Bestimmungen_Kt));
END Wildruhezone_Teilobjekt;
ASSOCIATION RoutennetzWildruhezone =
WRZ_Routennetz -- {0..*} Routennetz;
WRZ -<#> {1} Wildruhezone;
END RoutennetzWildruhezone;
ASSOCIATION Wildruhezone_TeilobjektWildruhezone =
WRZ_Teilobjekt -- {1..*} Wildruhezone_Teilobjekt;
WRZ -<#> {1} Wildruhezone;
UNIQUE WRZ->Kanton, WRZ->ObjNummer, WRZ_Teilobjekt->TeilObjNummer;
/* Wenn Schutzstatus = S10 "rechtsverbindlich", dann dürfen nur Bestimmungen für rechtsvebindliche Wildruhezonen
erfasst werden, also R*.
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
25
Wenn Schutzstatus = S20 "empfohlen", dann dürfen nur Bestimmungen für empfohlene Wildruhezonen erfasst werden,
also E*. */
MANDATORY CONSTRAINT NOT (WRZ->Schutzstatus->Reference->Code == "S10") OR
(WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R10" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R20" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R30" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R40" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R50" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R60" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R70" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R80" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R90" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R100" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R110" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R120" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R130" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R140" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R150" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R160" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "R900");
MANDATORY CONSTRAINT NOT (WRZ->Schutzstatus->Reference->Code == "S20") OR
(WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E10" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E20" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E30" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E40" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E50" OR
WRZ_Teilobjekt->Bestimmungen->Reference->Code == "E900");
END Wildruhezone_TeilobjektWildruhezone;
BAFU 2020
Wildruhezonen: Umsetzung des Geoinformationsgesetzes
26
END Wildruhezonen;
END Wildruhezonen_LV95_V2_1.