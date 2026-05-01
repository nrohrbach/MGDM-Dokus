
# Kantonales Inventar der


# Amphibienlaichgebiete


# von nationaler,


# regionaler und lokaler


# Bedeutung


# Identifikatoren 29.1 und


# 29.2


# Geobasisdaten des Umweltrechts


# Modelldokumentation


# Version 1.1

Bern, 18. Februar 2018

### Bundesamt für Umwelt BAFU /AÖL


**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Amphibienlaichgebiete Kant. Inventar (GeoIV p.
21); Identifikatoren 29.1 und 29.2

**FIG**

Mitglieder der AG mit KBNL
Catherine Guex, Frederic Aubert  (VD) 2010
Andreas Lienhard (ZH)
Stefan Meier (AG)
Markus Müller Egli (LU)
Remo Bianchi (SZ)
Matthias Künzler (TG) 2009
Rolf Niederer (TG) ab 2010
Norbert Danuser (GR)
Simone Serretti (TI)
Stefan Rey (ZG)
Peter Zopfi (GL), bis 2009
Mirjam Zehnder (KKGeo)
Rolf Zürcher(GKG/KOGIS)

**Leiter der FIG**

Helmut Recher, BAFU AÖL

**Datum**

18.02.2018

**Version**

Von der Direktion des BAFU verabschiedete
Version

**Änderungskontrolle**

Version
Beschreibung
Datum
1.0
Erstfassung des Modells
06.11.2012
1.1
Technische Anpassung INTERLIS-Beschreibung
18.02.2018

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu
Amphibienlaichgebieten ...................................................................................... 3
2.2.
Umsetzung ............................................................................................. 3
2.3.
Welche Objekte werden wie erfasst? ..................................................... 3
2.4.
Welche Informationen werden wie veröffentlicht? .................................. 4
2.5.
Aufwand .................................................................................................. 4
2.6.
Begriffe aus dem GeoIG ......................................................................... 4

### 3.


### Modellbeschreibung ............................................................... 5

3.1.
Amphibienlaichgebiete (Ortsfeste Objekte) ............................................ 5
3.2.
Wanderobjekte ....................................................................................... 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung .......................................................................... 6
4.2.
Objektklassenkatalog ............................................................................. 7
4.3.
Beschreibung mit INTERLIS 2.3 .......................................................... 12

### 5.


### Darstellung der Daten der Amphibienlaichgebiete ............ 13

5.1.
Darstellungsmodell Bund ..................................................................... 13

### Anhang

I
Datenmodell im Format INTERLIS 2.3

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**1**


## 1. Einleitung

Die Amphibien sind die am stärksten gefährdete Tiergruppe der Schweiz:
Insgesamt 70% der einheimischen Arten stehen auf der Roten Liste. Alle in der
Schweiz vorkommenden Arten sind mit Ausnahme des Alpensalamanders für ihre
Fortpflanzung auf Gewässer angewiesen. Um die gefährdeten Amphibien zu
schützen, setzte der Bund 2001 das Inventar der Amphibienlaichgebiete von
nationaler
Bedeutung
IANB
in
Kraft.
Es
bezeichnet
die
wichtigsten
Fortpflanzungsgebiete und beauftragt die Kantone, für deren Schutz und Unterhalt
zu sorgen.
Vor allem für seltenere und gefährdete Amphibienarten sind die inventarisierten
Laichgebiete überlebenswichtig. Einige Arten kommen markant häufiger in IANB-
Objekten vor als in übrigen Gebieten. Ausschliesslich in IANB-Gewässern findet
sich der akut gefährdete Italienische Springfrosch (Rana latastei).
Seit dem 1. Juli 2008 ist das Bundesgesetz über Geoinformation (GeoIG) in Kraft.
Es hat zum Ziel, auf nationaler Ebene verbindliche bundesrechtliche Standards für
die Erfassung, Modellierung und den Austausch von Geodaten 1 des Bundes,
insbesondere von Geobasisdaten des Bundesrechts, festzulegen. Weiter regelt es
die Finanzierung, das Urheberrecht sowie den Datenschutz. Das Gesetz bildet
auch für das Datenmanagement der Kantone und Gemeinden neue, gesicherte
rechtliche Grundlagen. So wird sich der Zugang zu den mit grossem Aufwand
erhobenen und verwalteten Daten für Behörden, Wirtschaft und Bevölkerung
verbessern. Es wird eine Mehrfachnutzung der gleichen Daten in den
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
Mit dem GeoIG ist auch die Verordnung über Geoinformationen (GeoIV) in Kraft
getreten. Sie präzisiert das GeoIG in fachlicher sowie technischer Hinsicht und
führt im Anhang 1 die „Geobasisdaten des Bundesrechts“ auf. Wegen des
expliziten Raumbezugs ist das kantonale Inventar der Amphibienlaichgebiete in
diesen Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikatoren 29.1
und 29.2). Art. 9 GeoIV definiert die Aufgaben der zuständigen Fachstelle des
Bundes. Im Anh. 1 der GeoIV wird für den Geobasisdatensatz 29 das BAFU als die
zuständige Fachstelle des Bundes bezeichnet. Diese muss somit ein minimales
Geodatenmodell vorgeben, das Definieren und Beschreiben eines oder mehrerer
Darstellungsmodell/e (Art. 11 GeoIV) ist hingegen fakultativ. Die Kantone werden
als zuständige Stelle für die Daten bezeichnet .Diese Geobasisdaten sind gemäss
GeoIV der Zugangsberechtigungsstufe A zugeteilt, d.h. dass sie öffentlich
zugänglich sind und ein Download-Dienst vorgesehen ist.
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV
NHG

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**2**

Seit dem 1. Januar 1967 ist das Bundesgesetz über den Natur und Heimatschutz
(NHG) in Kraft. Es hat u.a. zum Ziel, das heimatliche Landschafts- und Ortsbild, die
geschichtlichen  Stätten sowie die Natur- und Kulturdenkmäler des Landes zu
schonen und die einheimische Tier- und Pflanzenwelt sowie ihre biologische
Vielfalt und ihren natürlichen Lebensraum zu schützen. In den Artikeln 18a und
18b sind die Grundlagen für die Bezeichnung und den Schutz der Biotope von
nationaler, regionaler und lokaler Bedeutung festgehalten.
Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von
Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können
(Ebene Kanton oder Gemeinde), um die unterschiedlichen Bedürfnisse im Vollzug
abbilden zu können. Das nachfolgend vorgegebene minimale Geodatenmodell
verpflichtet die Kantone die Daten in dieser Form zu pflegen und mit den im
Datenmodell definierten Relationen zur Verfügung zu stellen.
Rechtlicher Stellenwert

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**3**


## 2. Ziel und Zweck


**2.1.**


**Ausgangslage der Erhebung von Informationen zu**


**Amphibienlaichgebieten**

In der Schweiz leben heute 19 Amphibienarten – fast alle befinden sich auf der
Roten Liste der gefährdeten Tierarten. Die Fläche der Feuchtgebiete als
Lebensraum der Amphibien schrumpfte in den letzten 100 Jahren auf weniger als
einen Zehntel zusammen. Die noch erhaltenen Lebensräume sollten deshalb
gesichert werden. Als Laichgewässer bevorzugen die meisten Arten stehende
Kleingewässer wie Tümpel und Weiher. Neben kleineren Tümpeln bis zu grossen
Feuchtgebietskomplexen bilden Kies- und Lehmgruben einen wichtigen Anteil
(rund ein Fünftel der Gesamtobjekte) des Inventars. Im Laufe der Nutzung haben
sie sich zu schützenswerten naturnahen Standorten entwickelt.

**2.2.**


**Umsetzung**

Mit der Amphibienlaichgebiets-Verordnung (SR 451.34) werden die wichtigsten
Lebensräume der Amphibien unter Schutz gestellt. Diese verpflichtet die Kantone
den genauen Grenzverlauf der ortsfesten Objekte von nationaler Bedeutung
festzulegen.
Für
Wanderobjekte
vereinbaren
die
Kantone
mit
den
GrundeigentümerInnen, den Nutzungsberechtigten oder den betroffenen Branchen
einen Perimeter, in dem die Amphibienlaichgewässer an geeignete Standorte
verschoben werden können. Die ortsfesten Objekte müssen ungeschmälert und
die Wanderobjekte funktionsfähig erhalten bleiben. Weiter sorgen die Kantone für
Schutz und Unterhalt der Biotope von regionaler und lokaler Bedeutung, die
Bestimmung der Bedeutung ist in der Kompetenz der Kantone. Die kantonalen
Inventare umfassen Objekte von nationaler Bedeutung, für die der Kanton den
genauen Grenzverlauf festgelegt hat (SR451.34 Art. 4 Abs.1) sowie die Objekte
von regionaler und lokaler Bedeutung.
Der Datensatz ist Grundlage für die Öffentlichkeitsarbeit (international und
national) im Bereich Biodiversität (Berichte, Statistiken, Artikel in der Fachpresse,
Auskünfte auf Anfragen, usw.).

**2.3.**


**Welche Objekte werden wie erfasst?**

Die aus kantonalen Inventaren bekannten Laichgebiete wurden für die Aufnahme
ins Bundesinventar auf Grund ihrer Artenzusammensetzung, Seltenheit der Arten
und Populationsgrösse bewertet und im Massstab 1:10‘000 kartiert. Für die
Umsetzung der Amphibienlaichgebiets-Verordnung wurden von den Kantonen für
viele
dieser
Objekte
Detailkartierungen
auf
Basis
unterschiedlicher
kartographischer
Grundlagen
durchgeführt.
Diese
werden
ergänzt
durch
Kartierungen von Objekten von regionaler und lokaler Bedeutung in ebenfalls
unterschiedlichen Massstäben. Da es sich beim kantonalen Inventar um
Vegetationskartierungen von Biotopen und nicht um Schutzperimeter handelt,
enthält es keine Pufferzonen.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Amphibienschutz
Langfristig geschützte
Biotope

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**4**


**2.4.**


**Welche Informationen werden wie veröffentlicht?**

Die Geodaten werden zukünftig in der  NGDI zur Verfügung gestellt. Das Inventar
ist nicht Bestandteil des ÖREB-Katasters.

**2.5.**


**Aufwand**

Die Kantone sind für den Aufbau und die periodische Aktualisierung zuständig.
Das BAFU ist für die Auswertung des Datensatzes und die Erstellung der
Statistiken im nationalen Kontext zuständig.

**2.6.**


**Begriffe aus dem GeoIG**

Die nachfolgend verwendeten Begriffe aus dem GeoIG sind wie folgt definiert 2 :
Raumbezogene Daten, die mit einem bestimmten Zeitbezug die Ausdehnung und
Eigenschaften bestimmter Räume und Objekte beschreiben, insbesondere deren
Lage, Beschaffenheit, Nutzung und Rechtsverhältnisse. (Beispiel.: digitale
Strassenkarten, Adressverzeichnis von Routenplanern)
Geodaten, die auf einem rechtsetzenden Erlass des Bundes, eines Kantones oder
einer Gemeinde beruhen. (Beispiel: Amtliche Vermessung, Bauzonenplan,
Hochmoorinventar)
Geodaten, die im Anhang 1 der GeoIV als solche klassiert sind.
2 Art. 3 GeoIG [ http://www.admin.ch/ch/d/sr/510_62/a3.html ]
Veröffentlichung der Daten
Geodaten
Geobasisdaten
Georeferenzdaten

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**5**


## 3. Modellbeschreibung


**3.1.**


**Amphibienlaichgebiete (Ortsfeste Objekte)**

Amphibienlaichgebiete wurden auf Grund ihrer Artenzusammensetzung, Seltenheit
der Arten und Populationsgrösse bewertet. Dafür wurde eine eigene Formel
entwickelt (BAFU Schriftenreihe Umwelt Nr 233). Insgesamt fanden so 824 Objekte
(742 ortsfeste und 82 Wanderobjekte) Aufnahme ins Inventar. Die kantonalen
Kartierungen wurden auf Basis unterschiedlicher Grundlagen und meist ohne
Verwendung dieser Formel  erstellt. Fläche und Lage dieser Objekte sind in den
Feldkartierungen des Bundesinventars und den kantonalen Kartierungen
festgehalten. Die Perimeter wurden auf der Basis dieser Grundlagen digitalisiert.

**3.2.**


**Wanderobjekte**

Die Wanderobjekte umfassen Rohstoffabbaugebiete, insbesondere Kies- und
Tongruben sowie Steinbrüche, mit Laichgewässern, die im Laufe der Zeit
verschoben werden können. Sie werden deshalb im Bundesinventar nur als Punkt
dargestellt, wobei dieser der Schwerpunktskoordinate entspricht. Dieser Wert
wurde bei der Georeferenzierung für die Erfassung verwendet. Von den Kantonen
aufgenommene Wanderobjekte liegen teilweise ebenfalls nur in Punktform vor.

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**6**


## 4. Modell-Struktur: konzeptionelles Datenmodell


**4.1.**


**Graphische Darstellung**

Die Abbildung 1 zeigt das UML-Diagramm für das kantonale Inventar der
Amphibienlaichgebiete von nationaler, regionaler und lokaler Bedeutung.
kt_Amphibiengebiet
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Obj_GISFlaeche[1] : Numerisch
Herkunft[1] : Zeichenkette
Kartierungsgrundlage[1] : Kartierungsgrundlage_CatRef
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Mutationgsgrund[0..1] : MultilingualMText
Bedeutung[1] : Bedeutung_CatRef
kt_Amphibiengebiet_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
AM_L_Bereich[0..1] : AM_L_Bereich_CatRef
Geo_Obj[1] : MultiPolygon
1..*
AM_L_Bereich_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
AM_L_Bereich_CatRef
Bedeutung_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Bedeutung_CatRef
Kartierungsgrundlage_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Kartierungsgrundlage_CatRef
Reference
+
Reference
+
Reference
+
Abbildung 1: Darstellung des kantonalen Inventar der Amphibienlaichgebiete von nationaler, regionaler und lokaler Bedeutung als UML-
Diagramm
kt_Wanderobjekt
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Herkunft[1] : Zeichenkette
Kartierungsgrundlage[1] : Kartierungsgrundlage_CatRef
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Mutationgsgrund[0..1] : MultilingualMText
Bedeutung[1] : Bedeutung_CatRef
Geo_Obj[1] : Coord3
Bedeutung_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Bedeutung_CatRef
Kartierungsgrundlage_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Kartierungsgrundlage_CatRef
Reference
+
Reference
+
Abbildung 2: Darstellung der Amphibienwanderobjekte als UML- Diagramm

**BAFU 2018**

Amphibienlaichgebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes

**7**


**4.2.**


**Objektklassenkatalog**

Entität kt_Amphibienlaichgebiet
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.1
Kanton
Kantonszeichen
TEXT
ZH
Obligatorisch
A1.2
ObjNummer
Eindeutiger Code zur
Kennzeichnung des

**Objekts**


**TEXT**


**507**


**Nummer kantonale Grundlage**

Obligatorisch
A1.3
Name
Bezeichnung des

**Objekts**


**TEXT**

Torfstich

**Aegelsee**

Falls vorhanden
Fakultativ
A1.4
Obj_GISFlaeche
GIS-Gesamtfläche des

**Objektes in ha**


**DOUBLE**


**2.5234ha**

Obligatorisch
A1.5
Herkunft
Ursprünglicher
Kantonaler
Datenbestand
TEXT
Amphibieninven
tar des Kantons
ZH, 1984
Hinweis aus welchem Inventar oder welcher

**Kartierung diese Daten stammen**

Obligatorisch
A1.6
Kartierungsgrundlage
Grundlage für die
Erfassung des
Perimeters
AUFZÄHLUNG
K3

**Definition Grundlage siehe unten**

Obligatorisch
A1.7
Aufnahmedatum
Aufnahme ins
kantonale Inventar
oder Verzeichnis
DATE
01.02.1991
Fakultativ
A1.8
Mutationsdatum
Datum der Mutation
des Objekts
DATE
1.07.2007
Fakultativ

**BAFU 2018**

Amphibienlaichgebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes

**8**

A1.9
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Vergrösserung
Objekt
Fakultativ
A1.10
Bedeutung

**Bedeutung des Objekts**


**AUFZÄHLUNG**


**B1**


**Definition Bedeutung siehe unten**

Obligatorisch
Entität kt_Amphibien_Teilobjekt
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.11
Teilobj_Nr
Identifikationsnummer
des Teilobjekts
TEXT
Kantonsinterne Identifikationsnummer des
Teilobjekts
Obligatorisch
A1.12
AM_L_Bereich
Bereich des Polygons
AUFZÄHLUNG
A
Definition AM_L_Bereich siehe unten
Fakultativ
A1.13
Geo_Obj
Ausdehnung des
Objekts
POLYGON
Obligatorisch
Entität kt_Wanderobjekt

**Merkmal (Attribut)**

Erklärung
der

**Merkmale**


**Datentyp**


**Beispiel**


**Bemerkungen**


**Pflichtattribut**

A1.1
Kanton
Kantonszeichen
TEXT
ZH
Obligatorisch

**A1.2**


**ObjNummer**

Eindeutiger Code zur
Kennzeichnung des
Objekts
TEXT
ZH 384

**Nummer kantonale Grundlage**

Obligatorisch

**BAFU 2018**

Amphibienlaichgebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes

**9**


**A1.3**


**Name**

Bezeichnung des
Objekts
TEXT
Rüssmatte
Name auf Objektblatt
Fakultativ
A1.4
Herkunft
Ursprünglicher
Kantonaler
Datenbestand

**TEXT**

Amphibieninv
entar des
Kantons ZH,

**1984**

Hinweis aus welchem Inventar oder welcher

**Kartierung diese Daten stammen**

Obligatorisch
A1.5
Kartierungsgrundlage
Grundlage für die
Erfassung des
Perimeters
AUFZÄHLUNG
K1
Definition Grundlage siehe unten
Obligatorisch
A1.6
Aufnahmedatum
Aufnahme ins
kantonale Inventar
oder Verzeichnis
DATE
01.02.1991
Fakultativ
A1.7
Mutationsdatum
Datum der Mutation
des Objekts
DATE
Fakultativ
A1.8
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Fakultativ
A1.9
Bedeutung
Bedeutung des Objekts
AUFZÄHLUNG
B1

**Definition Bedeutung siehe unten**

Obligatorisch
A1.10
Geo_Obj
Ausdehnung des
Objekts
POINT
Obligatorisch

**BAFU 2018**

Amphibienlaichgebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes

**10**

Entität AM_L_Bereich
Code
DE
FR
IT

**A**


**B**

Bereich A (dient der Fortpflanzung der
Amphibien – alle Gewässer welche sicher

**oder potentiell der Fortpflanzung dienen)**

Bereich
B
(Nährstoffpufferzone
und
engerer Landlebensraum angrenzend an

**das Fortpflanzungsgewässer)**

secteur A (sert à la reproduction des
batraciens – tous les plans d'eau servant à la
reproduction
de
manière
effective
ou
potentielle)
secteur B (zone tampon et habitat terrestre
attenant au plan d'eau de reproduction)
Settore
A
(funge
da
luogo
per
la
riproduzione degli anfibi – tutti i corpi
d’acqua dove la riproduzione è accertata o
è potenziale)
Settore B (zona cuscinetto per i nutrienti e
superficie confinante con i corpi d’acqua

**idonei alla riproduzione)**

Entität Kartierungsgrundlage
Code
DE
FR
IT

**K1**


**K2**


**K3**


**K4**


**K5**

K6

**Landeskarte 1:25000**


**Andere Landeskarte**


**Kantonale Plangrundlage**

Luftbild, Orthophoto

**andere**


**unbekannt**

Carte nationale 1 :25’000
Autre carte nationale
Base cantonale de planification
Photographie arienne, orthophoto
Autres

**Inconnu**

Carta nazionale 1:25’000
Altra carta nazionale
Base cartografica cantonale
Immagine aerea, orthophoto
Altri/e

**Sconosciuto**


**BAFU 2018**

Amphibienlaichgebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes

**11**

Entitiät Bedeutung
Code
DE
FR
IT

**B1**

B2
B3

**National**

Regional

**Lokal**


**National**

Régional

**Local**

Nazionale
Regionale

**Locale**


**BAFU 2018**


**Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes 12**


**4.3.**


**Beschreibung mit INTERLIS 2.3**

Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**13**


## 5. Darstellung der Daten der Amphibienlaichgebiete


**5.1.**


**Darstellungsmodell Bund**

Für die regionalen Amphibienlaichgebiete besteht noch kein Darstellungsmodell.

**5.2**


**Darstellungsmodell Kantone**


**Für die kantonalen Objekte besteht noch kein Darstellungsmodell.**

Darstellungsmodell

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**14**


## Anhang


**I Datenmodell im Format INTERLIS 2.3**

Bei Abweichungen zw. Modelldokumentation und Model Repository gilt die ILI-Version im Model Repository.

**Amphibienlaichgebiete**

INTERLIS 2.3;
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=29.1
MODEL kt_Amphibien_Laichgebiete_Codelisten_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2018-02-07"  =
IMPORTS CatalogueObjects_V1,LocalisationCH_V1;
/* Modell für externe Codelisten, die anschliessend importiert werden in die Modelle *_LV03* und *_LV95" */
TOPIC Codelisten =
CLASS AM_L_Bereich_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*8;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END AM_L_Bereich_Catalogue;
CLASS Bedeutung_Catalogue

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**15**

EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Bedeutung_Catalogue;
CLASS Kartierungsgrundlage_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Kartierungsgrundlage_Catalogue;
STRUCTURE AM_L_Bereich_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) AM_L_Bereich_Catalogue;
END AM_L_Bereich_CatRef;
STRUCTURE Bedeutung_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) Bedeutung_Catalogue;
END Bedeutung_CatRef;
STRUCTURE Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) Kartierungsgrundlage_Catalogue;
END Kartierungsgrundlage_CatRef;
END Codelisten;
END kt_Amphibien_Laichgebiete_Codelisten_V1_1.

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**16**

!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=29.1
MODEL kt_Amphibien_Laichgebiete_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2018-02-07"  =
IMPORTS CHAdminCodes_V1,Units,GeometryCHLV03_V1,LocalisationCH_V1,kt_Amphibien_Laichgebiete_Codelisten_V1_1;
TOPIC kt_Amphibiengebiet =
DEPENDS ON kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten;
DOMAIN
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV03_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für gesamtes Amphibiengebiet */
CLASS kt_Amphibiengebiet =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT*30;

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**17**

Name : TEXT*80;
Obj_GISFlaeche : MANDATORY 1.000 .. 999999999.000 [Units.ha];
Herkunft : MANDATORY TEXT*250;
Kartierungsgrundlage : MANDATORY
kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.Bedeutung_CatRef;
END kt_Amphibiengebiet;
/* Klasse für Amphibien-Teilgebiete */
CLASS kt_Amphibiengebiet_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT*20;
AM_L_Bereich : kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.AM_L_Bereich_CatRef;
Geo_Obj : MANDATORY MultiPolygon;
END kt_Amphibiengebiet_Teilobjekt;
ASSOCIATION Teilobjektkt_Auengebiet =
kt_Amphibiengebiet_Teilobjekt -- {1..*} kt_Amphibiengebiet_Teilobjekt;
kt_Amphibiengebiet -<#> {1} kt_Amphibiengebiet;
END Teilobjektkt_Auengebiet;
END kt_Amphibiengebiet;
END kt_Amphibien_Laichgebiete_LV03_V1_1.
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**18**

!!@ IDGeoIV=29.1
MODEL kt_Amphibien_Laichgebiete_LV95_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2018-02-07"  =
IMPORTS CHAdminCodes_V1,Units,GeometryCHLV95_V1,LocalisationCH_V1,kt_Amphibien_Laichgebiete_Codelisten_V1_1;
TOPIC kt_Amphibiengebiet =
DEPENDS ON kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten;
DOMAIN
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für gesamtes Amphibiengebiet */
CLASS kt_Amphibiengebiet =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT*30;
Name : TEXT*80;
Obj_GISFlaeche : MANDATORY 1.000 .. 999999999.000 [Units.ha];
Herkunft : MANDATORY TEXT*250;

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**19**

Kartierungsgrundlage : MANDATORY
kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.Bedeutung_CatRef;
END kt_Amphibiengebiet;
/* Klasse für Amphibien-Teilgebiete */
CLASS kt_Amphibiengebiet_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT*20;
AM_L_Bereich : kt_Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.AM_L_Bereich_CatRef;
Geo_Obj : MANDATORY MultiPolygon;
END kt_Amphibiengebiet_Teilobjekt;
ASSOCIATION Teilobjektkt_Auengebiet =
kt_Amphibiengebiet_Teilobjekt -- {1..*} kt_Amphibiengebiet_Teilobjekt;
kt_Amphibiengebiet -<#> {1} kt_Amphibiengebiet;
END Teilobjektkt_Auengebiet;
END kt_Amphibiengebiet;
END kt_Amphibien_Laichgebiete_LV95_V1_1.

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**20**


**Wanderobjekte**

INTERLIS 2.3;
!!@ IDGeoIV=29.2
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL kt_Amphibien_Wanderobjekte_Codelisten_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2018-02-07"  =
IMPORTS LocalisationCH_V1,CatalogueObjects_V1;
/* Modell für externe Codelisten, die anschliessend importiert werden in die Modelle *_LV03* und *_LV95" */
TOPIC Codelisten =
CLASS Bedeutung_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Bedeutung_Catalogue;
CLASS Kartierungsgrundlage_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Kartierungsgrundlage_Catalogue;
STRUCTURE Bedeutung_CatRef

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**21**

EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) Bedeutung_Catalogue;
END Bedeutung_CatRef;
STRUCTURE Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) Kartierungsgrundlage_Catalogue;
END Kartierungsgrundlage_CatRef;
END Codelisten;
END kt_Amphibien_Wanderobjekte_Codelisten_V1_1.
!!@ IDGeoIV=29.2
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL kt_Amphibien_Wanderobjekte_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2018-02-07"  =
IMPORTS LocalisationCH_V1,CHAdminCodes_V1,GeometryCHLV03_V1,kt_Amphibien_Wanderobjekte_Codelisten_V1_1;
TOPIC kt_Wanderobjekt =
DEPENDS ON kt_Amphibien_Wanderobjekte_Codelisten_V1_1.Codelisten;
/* Klasse für Amphibien-Wanderobjekte */
CLASS kt_Wanderobjekt =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT*30;
Name : TEXT*80;

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**22**

Herkunft : MANDATORY TEXT*250;
Kartierungsgrundlage : MANDATORY
kt_Amphibien_Wanderobjekte_Codelisten_V1_1.Codelisten.Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY kt_Amphibien_Wanderobjekte_Codelisten_V1_1.Codelisten.Bedeutung_CatRef;
Geo_Obj : MANDATORY GeometryCHLV03_V1.Coord3;
END kt_Wanderobjekt;
END kt_Wanderobjekt;
END kt_Amphibien_Wanderobjekte_LV03_V1_1.
!!@ IDGeoIV=29.2
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL kt_Amphibien_Wanderobjekte_LV95_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2018-02-07"  =
IMPORTS LocalisationCH_V1,CHAdminCodes_V1,GeometryCHLV95_V1,kt_Amphibien_Wanderobjekte_Codelisten_V1_1;
TOPIC kt_Wanderobjekt =
DEPENDS ON kt_Amphibien_Wanderobjekte_Codelisten_V1_1.Codelisten;
/* Klasse für Amphibien-Wanderobjekte */
CLASS kt_Wanderobjekt =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT*30;

**BAFU 2018**

Amphibienlaichgebiete Kant Inv: Umsetzung des Geoinformationsgesetzes

**23**

Name : TEXT*80;
Herkunft : MANDATORY TEXT*250;
Kartierungsgrundlage : MANDATORY
kt_Amphibien_Wanderobjekte_Codelisten_V1_1.Codelisten.Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY kt_Amphibien_Wanderobjekte_Codelisten_V1_1.Codelisten.Bedeutung_CatRef;
Geo_Obj : MANDATORY GeometryCHLV95_V1.Coord3;
END kt_Wanderobjekt;
END kt_Wanderobjekt;
END kt_Amphibien_Wanderobjekte_LV95_V1_1.