
# Bundesinventar der


# Amphibienlaichgebie


# te von nationaler


# Bedeutung


# Identifikatoren 22.1


# und 22.2


# Geobasisdaten des Umweltrechts


# Modelldokumentation


# Version 1.1

Bern, 10. August 2017

### Bundesamt für Umwelt BAFU /AÖL


**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes
Offiz. Bezeichner
Amphibienlaichgebiete (GeoIV p. 21);
Identifikatoren 22.1 und 22.2
FIG
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
Leiter der FIG
Helmut Recher, BAFU AÖL
Datum
10. August 2017
Version
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
Überarbeitung auf Grund technischer Anpassungen
und Erfordernisse
10.08.2017

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**1**


## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 2


### 2.


### Ziel und Zweck ........................................................................ 4

2.1.
Ausgangslage der Erhebung von Informationen zu
Amphibienlaichgebieten ...................................................................................... 4
2.2.
Umsetzung ........................................................................................... 4
2.3.
Welche Objekte werden erfasst? ......................................................... 4
2.4.
Welche Informationen werden wie veröffentlicht? ............................... 4
2.5.
Aufwand ............................................................................................... 4
2.6.
Begriffe aus dem GeoIG ...................................................................... 5

### 3.


### Modellbeschreibung ............................................................... 6

3.1.
Amphibienlaichgebiete (Ortsfeste Objekte) ......................................... 6
3.2.
Wanderobjekte ..................................................................................... 6

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 8

4.1.
Graphische Darstellung ....................................................................... 8
4.2.
Objektklassenkatalog ........................................................................... 9
4.3.
Beschreibung mit INTERLIS 2.3 ........................................................ 14

### 5.


### Darstellung der Daten der Amphibienlaichgebiete ............ 15

5.1.
Darstellungsmodell Bund ................................................................... 15

### Anhang

I
Datenmodell im Format INTERLIS 2.3
II
Darstellungsmodell

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**2**


## 1. Einleitung

Die Amphibien sind die am stärksten gefährdete Tiergruppe der Schweiz:
Insgesamt  70% der einheimischen Arten stehen auf der Roten Liste. Alle in der
Schweiz vorkommenden Arten sind mit Ausnahme des Alpensalamanders für ihre
Fortpflanzung auf Gewässer angewiesen. Um die gefährdeten Amphibien zu
schützen, setzte der Bund 2001 das Inventar der Amphibienlaichgebiete von
nationaler
Bedeutung
IANB in
Kraft.
Es
bezeichnet
die
wichtigsten
Fortpflanzungsgebiete und beauftragt die Kantone, für deren Schutz und Unterhalt zu
sorgen.
Das Inventar umfasst aktuell 824 Objekte mit einer Gesamtfläche von knapp
13'900 ha. Noch nicht in Kraft gesetzte, aber inventarisierte Objekte unterstehen
einem provisorischen Schutz. Die Flächen der einzelnen Objekte reichen von
einem Dutzend Quadratmetern bis zu einem Quadratkilometer. Vor allem für
seltenere und gefährdete Amphibienarten sind die inventarisierten Laichgebiete
überlebenswichtig. Einige Arten kommen markant häufiger in IANB-Objekten vor
als in übrigen Gebieten. Ausschliesslich in IANB-Gewässern findet sich der akut
gefährdete Italienische Springfrosch (Rana latastei).
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
expliziten Raumbezugs ist das Bundesinventar der Amphibienlaichgebiete in
diesen Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikatoren 22.1
und 22.2). Art. 9 GeoIV definiert die Aufgaben der zuständigen Fachstelle des
Bundes. Im Anh. 1 der GeoIV wird für den Geobasisdatensatz 22 das BAFU als die
zuständige Fachstelle des Bundes bezeichnet. Diese muss somit ein minimales
Geodatenmodell vorgeben, das Definieren und Beschreiben eines oder mehrerer
Darstellungsmodell/e (Art. 11 GeoIV) ist hingegen fakultativ. Das BAFU wird als
zuständige Stelle für die Daten bezeichnet. Diese Geobasisdaten sind gemäss
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**3**

GeoIV der Zugangsberechtigungsstufe A zugeteilt, d.h. dass sie öffentlich
zugänglich sind und ein Download-Dienst vorgesehen ist.
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
verpflichtet das Bundesamt die Daten in dieser Form zu pflegen und mit den im
Datenmodell definierten Relationen zur Verfügung zu stellen.
NHG
Rechtlicher Stellenwert

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**4**


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

Mit der Amphibienlaichgebiets-Verordnung werden die wichtigsten Lebensräume
der Amphibien unter Schutz gestellt. Als viertes Bundesinventar gemäss Art. 18a
NHG setzte der Bundesrat 2001 das Bundesinventar der Amphibienlaichgebiete
mit 701 Objekten in Kraft, welches in den Jahren 2003, 2007 und 2017  revidiert
wurde.
Es bezeichnet die wichtigsten Fortpflanzungsgebiete und beauftragt die Kantone,
für deren Schutz und Unterhalt zu sorgen. Das Ziel des IANB ist es, die
nachgewiesenen Amphibienbestände zu erhalten, zu fördern beziehungsweise
wiederherzustellen.

**2.3.**


**Welche Objekte werden erfasst?**

Die aus den kantonalen Inventaren bekannten Laichgebiete wurden auf Grund
ihrer Artenzusammensetzung, Seltenheit der Arten und Populationsgrösse
bewertet. Dafür wurde eine eigene Formel entwickelt.

**2.4.**


**Welche Informationen werden wie veröffentlicht?**

Das Bundesinventar bildet als Anhang 3 Bestandteil der Verordnung über den
Schutz der Amphibienlaichgebiete von nationaler Bedeutung. Im Internet werden
die Objektlisten und Objektblätter als pdf-Formate kantonsweise publiziert. Die
Geodaten werden in der BGDI dargestellt und sind auf der Homepage des BAFU
integriert, wo sie gemäss den Bestimmungen des Geoinformationsgesetzes
öffentlich zur Verfügung stehen.

**2.5.**


**Aufwand**

Das BAFU ist für den Aufbau, die periodische Aktualisierung und die Auswertung
des Datensatzes und die Erstellung der entsprechenden Statistiken zuständig.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Amphibienschutz
Langfristig geschützte
Biotope
Veröffentlichung der Daten

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**5**


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
Geodaten
Geobasisdaten
Georeferenzdaten

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**6**


## 3. Modellbeschreibung


**3.1.**


**Amphibienlaichgebiete (Ortsfeste Objekte)**

Amphibienlaichgebiete wurden auf Grund ihrer Artenzusammensetzung, Seltenheit
der Arten und Populationsgrösse bewertet. Dafür wurde eine eigene Formel
entwickelt (BAFU Schriftenreihe Umwelt Nr. 233). Ortsfeste Objekte umfassen das
Laichgewässer und angrenzende natürliche und naturnahe Flächen (Bereich A)
sowie weitere Landlebensräume und Wanderkorridore (Bereich B). Die Bereiche A
und B werden  in der Umschreibung der Objekte soweit  erforderlich festgehalten.
Fläche und Lage der Amphibienlaichgebiete  sind in den Feldkartierungen des
Bundesinventars festgehalten. Die Perimeter wurden auf der Basis dieser
Grundlagen digitalisiert.
Abbildung 1: Georeferenzierung des Objekts mittels PK25

**3.2.**


**Wanderobjekte**


**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**7**

Die Wanderobjekte umfassen Rohstoffabbaugebiete, insbesondere Kies- und
Tongruben sowie Steinbrüche, mit Laichgewässern, die im Laufe der Zeit
verschoben werden können. Sie werden deshalb im Bundesinventar nur als Punkt
dargestellt, wobei dieser der Schwerpunktskoordinate entspricht. Dieser Wert
wurde bei der Georeferenzierung für die Erfassung verwendet.
Abbildung 2: Georeferenzierung des Objekts mittels PK25

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**8**


## 4. Modell-Struktur: konzeptionelles Datenmodell


**4.1.**


**Graphische Darstellung**

Die Abbildung 3 und 5 zeigen das UML-Diagramm für die Amphibienlaichgebiete
(AM_L) und Amphibienwanderobjekte (AM_G).
Amphibienlaichgebiet_Teilobjekt
TeilObjNummer[1] : Zeichenkette
Bereich[1] : Bereich_CatRef
Geo_Obj[1] : MultiPolygon
Amphibienlaichgebiet
ObjNummer[1] : Zeichenkette
Name[1] : Zeichenkette
RefObjBlatt[0..1] : Zeichenkette
DesignatType[0..1] : DesignationType
IUCNCategory[1] : IUCNCategory
Inkraftsetzungsdatum[1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Mutationsgrund[0..1] : MultilingualMText
1..*
Bereich_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Bereich_CatRef
DesignationType
<<enumeration>>
SAC
SPA
SCI
RAMSAR
NDA
IUCNCategory
<<enumeration>>
Strict_Nature_Reserve_Ia
Wilderness_Area_Ib
National_Park_II
Natural_Monument_III
Habitat_or_Species_Management_Area_IV
Protected_Landscape_or_Seascape_V
Managed_Resource_Protected_Area_VI
Reference
+
Abbildung 3: Darstellung der Amphibienlaichgebiete als UML-Diagramm
Wanderobjekt
ObjNummer[1] : Zeichenkette
Name[1] : Zeichenkette
RefObjBlatt[0..1] : Zeichenkette
DesignatType[0..1] : DesignationType
IUCNCategory[1] : IUCNCategory
Inkraftsetzungsdatum[1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Geo_Obj[1] : Coord3
Mutationsgrund[0..1] : MultilingualMText
DesignationType
<<enumeration>>
SAC
SPA
SCI
RAMSAR
NDA
IUCNCategory
<<enumeration>>
Strict_Nature_Reserve_Ia
Wilderness_Area_Ib
National_Park_II
Natural_Monument_III
Habitat_or_Species_Management_Area_IV
Protected_Landscape_or_Seascape_V
Managed_Resource_Protected_Area_VI
Abbildung 4: Darstellung der Amphibienwanderobjekte als UML- Diagramm

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**9**


**4.2.**


**Objektklassenkatalog**

Entität Amphibienlaichgebiet

**Merkmal (Attribut)**

Erklärung
der

**Merkmale**


**Datentyp**


**Beispiel**


**Bemerkungen**


**Pflichtattribut**


**A1.1**


**ObjNummer**

Eindeutiger Code zur
Kennzeichnung des
Objekts
TEXT
AG 384

**Nummer Bundesinventar**

Obligatorisch

**A1.2**


**Name**

Bezeichnung des
Objekts
TEXT
Rüssmatte
Name auf Objektblatt
Obligatorisch
A1.3
RefObjBlatt
URl

**(Persistenter) Link auf das Objektblatt**

Fakultativ

**A1.4**


**DesignatType**

Schutzgebietstyp für
die internationale
Berichterstattung.
Angabe wird vom
BAFU gemäss Liste
DesignationType (EU)
gemacht
DesignationType:
AUFZÄHLUNG
Ramsar
Vgl.
http://inspire.jrc.ec.europa.eu/documents/D
ata_Specifications/INSPIRE_DataSpecifica
tion_PS_v3.0.pdf
Fakultativ

**A1.5**


**IUCNCategory**

Internationale
Schutzgebietskategorie
für die internationale
Berichterstattung.
Code wird vom BAFU
gemäss Kategorien
IUCNCategory:
AUFZÄHLUNG
IV
(Management
Area)
http://www.unep-
wcmc.org/protected_areas/categories/inde
x.html
Obligatorisch

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**10**

MCPFE und der
Kategorien der IUCN
gemacht.
A1.6
Inkraftsetzungsdatum
Datum der
Inkraftsetzung des
Objekts
DATE
01.02.1991
Obligatorisch
A1.7
Mutationsdatum
Datum der Mutation
des Objekts
DATE
1.07.2007
Fakultativ
A1.8
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Vergrösserung
Objekt auf
Antrag Kt
Fakultativ

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**11**

Entität Amphibiengebiet-Teilobjekt
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.11
Teilobj_NrTeilObjNum
mer
Identifikationsnummer
des Teilobjekts
TEXT
Bundesinterne Identifikationsnummer des
Teilobjekts
Obligatorisch
A1.12
Bereich
Bereich des Polygons
AUFZÄHLUNG
A
Definition Bereich siehe unten
Obligatorisch
A1.13
Geo_Obj
Ausdehnung des

**Objekts**


**POLYGON**

Obligatorisch

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**12**

Entität Wanderobjekt

**Merkmal (Attribut)**

Erklärung
der

**Merkmale**


**Datentyp**


**Beispiel**


**Bemerkungen**


**Pflichtattribut**


**A1.1**


**ObjNummer**

Eindeutiger Code zur
Kennzeichnung des
Objekts
TEXT
AG 384

**Bundesinterne Identifikationsnummer**

Obligatorisch

**A1.2**


**Name**

Bezeichnung des
Objekts
TEXT
Rüssmatte
Name auf Objektblatt
Obligatorisch
A1.3
RefObjBlatt
URl

**(Persistenter) Link auf das Objektblatt**

Fakultativ

**A1.4**


**DesignatType**

Schutzgebietstyp für
die internationale
Berichterstattung.
Angabe wird vom
BAFU gemäss Liste
DesignationType (EU)
gemacht
DesignationType:
TEXT
ramsar
Vgl.
http://inspire.jrc.ec.europa.eu/documents/Da
ta_Specifications/INSPIRE_DataSpecificatio
n_PS_v3.0.pdf
Fakultativ

**A1.5**


**IUCNCategory**

Internationale
Schutzgebietskategorie
für die internationale
Berichterstattung.
Code wird vom BAFU
gemäss Kategorien
MCPFE und der
IUCNCategory:
TEXT
IV
(Management
Area)
http://www.unep-
wcmc.org/protected_areas/categories/index.
html
Obligatorisch

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**13**

Kategorien der IUCN
gemacht.
A1.6
Inkraftsetzungsdatum
Datum der
Inkraftsetzung des
Objekts
DATE
01.02.1991
Obligatorisch
A1.7
Mutationsdatum
Datum der Mutation
des Objekts
DATE
1.07.2007
Fakultativ
A1.8
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Vergrösserung
Objekt auf
Antrag Kt
Fakultativ
A1.9
Geo_Obj
Lage des Objekts
POINT
Obligatorisch
Entität Bereich

**Code**


**DE**


**FR**


**IT**

A
B
Bereich A (dient der Fortpflanzung der
Amphibien – alle Gewässer welche sicher
oder potentiell der Fortpflanzung dienen)
Bereich
B
(Nährstoffpufferzone
und
engerer Landlebensraum angrenzend an
das Fortpflanzungsgewässer)
secteur A (sert à la reproduction des
batraciens – tous les plans d'eau
servant à la reproduction de manière
effective ou potentielle)
secteur B (zone tampon et habitat
terrestre attenant au plan d'eau de
reproduction)
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


**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**14**


**4.3.**


**Beschreibung mit INTERLIS 2.3**

Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**15**


## 5. Darstellung der Daten der Amphibienlaichgebiete


**5.1.**


**Darstellungsmodell Bund**

Die Daten der Amphibienlaichgebiete werden vom BAFU für den Vollzug des
Arten- und Biotopschutzes verwendet. Die Darstellung erfolgt im Rahmen des
Erlasses resp. bei Revisionen der Amphibienlaichgebietsverordnung. Dabei
gelangen die folgenden geographischen Darstellungsarten zur Anwendung
(Abbildung 3).
Abbildung 7: Geographische Lage der Amphibienlaichgebiete
Legende:
Darstellungsmodell Bund

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**16**


## Anhang


**I Datenmodell im Format INTERLIS 2.3**

Bei Abweichungen zw. Modelldokumentation und Model Repository gilt die ILI-Version im Model Repository.

**Amphibienlaichgebiete**

INTERLIS 2.3;
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=22.1
MODEL Amphibien_Laichgebiete_Codelisten_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-04-05"  =
IMPORTS CatalogueObjects_V1,LocalisationCH_V1;
TOPIC Codelisten =
CLASS Bereich_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*1;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Bereich_Catalogue;
STRUCTURE Bereich_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) Bereich_Catalogue;

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**17**

END Bereich_CatRef;
END Codelisten;
END Amphibien_Laichgebiete_Codelisten_V1_1.
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=22.1
MODEL Amphibien_Laichgebiete_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-04-05"  =
IMPORTS GeometryCHLV03_V1,LocalisationCH_V1,Amphibien_Laichgebiete_Codelisten_V1_1;
TOPIC Amphibienlaichgebiete =
DEPENDS ON Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten;
DOMAIN
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV03_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/* Codelisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
);

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**18**

IUCNCategory = (
Strict_Nature_Reserve_Ia,
Wilderness_Area_Ib,
National_Park_II,
Natural_Monument_III,
Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
CLASS Amphibienlaichgebiet_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
Bereich : MANDATORY Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.Bereich_CatRef;
Geo_Obj : MANDATORY MultiPolygon;
END Amphibienlaichgebiet_Teilobjekt;
CLASS Amphibienlaichgebiet =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**19**

RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
END Amphibienlaichgebiet;
ASSOCIATION Amphibienlaichgebiet_TeilobjektAmphibienlaichgebiet =
Amphibienlaichgebiet_Teilobjekt -- {1..*} Amphibienlaichgebiet_Teilobjekt;
Amphibienlaichgebiet -<#> {1} Amphibienlaichgebiet;
END Amphibienlaichgebiet_TeilobjektAmphibienlaichgebiet;
END Amphibienlaichgebiete;
END Amphibien_Laichgebiete_LV03_V1_1.
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=22.1
MODEL Amphibien_Laichgebiete_LV95_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-04-05"  =
IMPORTS GeometryCHLV95_V1,LocalisationCH_V1,Amphibien_Laichgebiete_Codelisten_V1_1;
TOPIC Amphibienlaichgebiete =
DEPENDS ON Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten;

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**20**

DOMAIN
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/* Codelisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
);
IUCNCategory = (
Strict_Nature_Reserve_Ia,
Wilderness_Area_Ib,
National_Park_II,
Natural_Monument_III,
Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**21**

Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
CLASS Amphibienlaichgebiet_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
Bereich : MANDATORY Amphibien_Laichgebiete_Codelisten_V1_1.Codelisten.Bereich_CatRef;
Geo_Obj : MANDATORY MultiPolygon;
END Amphibienlaichgebiet_Teilobjekt;
CLASS Amphibienlaichgebiet =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
END Amphibienlaichgebiet;
ASSOCIATION Amphibienlaichgebiet_TeilobjektAmphibienlaichgebiet =
Amphibienlaichgebiet_Teilobjekt -- {1..*} Amphibienlaichgebiet_Teilobjekt;
Amphibienlaichgebiet -<#> {1} Amphibienlaichgebiet;
END Amphibienlaichgebiet_TeilobjektAmphibienlaichgebiet;
END Amphibienlaichgebiete;
END Amphibien_Laichgebiete_LV95_V1_1.

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**22**


**Wanderobjekte**

INTERLIS 2.3;
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=22.2
MODEL Amphibien_Wanderobjekte_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-04-05"  =
IMPORTS GeometryCHLV03_V1,LocalisationCH_V1;
TOPIC Wanderobjekte =
DOMAIN
/* Codelisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
);
IUCNCategory = (
Strict_Nature_Reserve_Ia,
Wilderness_Area_Ib,
National_Park_II,

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**23**

Natural_Monument_III,
Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
CLASS Wanderobjekt =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Geo_Obj : MANDATORY GeometryCHLV03_V1.Coord3;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
END Wanderobjekt;
END Wanderobjekte;
END Amphibien_Wanderobjekte_LV03_V1_1.
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=22.2
MODEL Amphibien_Wanderobjekte_LV95_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-04-05"  =

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**24**

IMPORTS GeometryCHLV95_V1,LocalisationCH_V1;
TOPIC Wanderobjekte =
DOMAIN
/* Codelisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
);
IUCNCategory = (
Strict_Nature_Reserve_Ia,
Wilderness_Area_Ib,
National_Park_II,
Natural_Monument_III,
Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
CLASS Wanderobjekt =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**25**

DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Geo_Obj : MANDATORY GeometryCHLV95_V1.Coord3;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
END Wanderobjekt;
END Wanderobjekte;
END Amphibien_Wanderobjekte_LV95_V1_1.

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**26**


# II Darstellungsmodell Bundesinventar der Amphibienlaichgebiete von nationaler Bedeutung


**( Amphibienlaichgebiete)**

Layer transparency: 50%
Fläche Kategorie A:
Type: Picture Fill,
Picture: ordered20.bmp
Farbname: -
RGB: 143,0,201
Outline:
Type: Line
Width: 1.5
Farbname: -
RGB: 143,0,201

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**27**

Fläche Kategorie B:
Typ: Line Fill
Farbname: -
RGB: 143,0,201
Separation: 15
Linetyp: Line
Linewidth: 1.0
Outline:
Type: Line
Width: 1.5
Farbname: -
RGB: 143,0,201

**BAFU 2017**

Amphibienlaichgebiete: Umsetzung des Geoinformationsgesetzes

**28**


**(Amphibien Wanderobjekte)**

Layer transparency: 50%
Punkt:
Typ: Character Marker Symbol
Charakter Marker: Dreieck
Size 10
Farbname: -
RGB: 143,0,201