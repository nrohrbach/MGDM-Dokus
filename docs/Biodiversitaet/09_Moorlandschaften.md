
**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetzes

# Technische Anleitungen


# Geobasisdaten des


# Umweltrechts


# Bundesinventar der Moorlandschaften von


# besonderer Schönheit und nationaler


# Bedeutung


# Identifikator 24.1


# Version 1. 1

Bern, 22. August 2017

### Bundesamt für Umwelt BAFU /AÖL


**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Moorlandschaften (GeoIV p. 29); Identifikator 24.1

**FIG**

Mitglieder der AG gitKBNL
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
Rolf Zürcher, KOGIS
Mirjam Zehner, KKGEO
Dominik Angst, BAFU
Helmut Recher, BAFU AÖL

**Leiter der FIG**

Helmut Recher, BAFU AÖL

**Datum**

22.08.2017

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
Technische Anpassungen der Modellstruktur: UML,
Objektklassen, INTERLIS
22.08.2017

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu Moorlandschaften . 3
2.2.
Umsetzung ............................................................................................. 3
2.3.
Welche Objekte werden erfasst? ........................................................... 3
2.4.
Welche Informationen werden wie veröffentlicht? .................................. 4
2.5.
Aufwand .................................................................................................. 4
2.6.
Begriffe aus dem GeoIG ......................................................................... 4

### 3.


### Modellbeschreibung ............................................................... 5

3.1.
Moorlandschaften ................................................................................... 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung .......................................................................... 6
4.2.
Objektklassenkatalog ............................................................................. 7
4.3.
Beschreibung mit INTERLIS 2.3 ............................................................ 9

### 5.


### Darstellung der Daten der Moorlandschaften .................... 10

5.1.
Darstellungsmodell Bund ..................................................................... 10

### Anhang ........................................................................................... 11


### Anhang

I
Datenmodell im Format INTERLIS 2.3
II
Darstellungsmodell

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**1**


## 1. Einleitung

Eine Moorlandschaft ist eine in besonderem Masse durch Moore geprägte,
naturnahe Landschaft. Ihr moorfreier Teil steht zu den Mooren in enger
ökologischer, visueller, kultureller oder geschichtlicher Beziehung.
Moorlandschaften sind in ihrer Schönheit gefährdet durch das Erstellen von
Infrastrukturen und in ihrer Funktion beeinträchtigt durch unangepasste Nutzung,
so besonders durch Freizeitaktivitäten (Naherholung, Sport, Tourismus).
Grundsätzlich gilt, dass Gestaltung und Nutzung der Moorlandschaften weiterhin
zulässig sind, soweit sie den Schutzzielen nicht widersprechen, also die
Moorbiotope nicht schmälern und die charakteristischen Elemente erhalten
bleiben. Somit stehen ausserhalb der Moorbiotope ästhetische, kulturelle und
ökologische Werte im Vordergrund.
Erhalt und Steigerung ökologischer Werte wiederum können durch naturnahen
Waldbau und ökologisch ausgerichtete Landwirtschaft erreicht werden. Am
häufigsten treten Konflikte auf, wenn es darum geht, neue Bauten oder Anlagen zu
erstellen bzw. diese zu verändern.
Der Landschaftsschutz ist weniger einschränkend als der Biotopschutz. Die
Kantone regeln den Schutz der Moorlandschaft ausserhalb der Biotope mittels
Landschaftsschutz oder speziellen Verordnungen.
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
expliziten Raumbezugs ist das Bundesinventar der Moorlandschaften in diesen
Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikatoren 160). Art. 9
GeoIV bezeichnet das BAFU als die zuständige Fachstelle des Bundes. Diese
muss somit ein minimales Geodatenmodell vorgeben, das Definieren und
Beschreiben eines oder mehrerer Darstellungsmodell/e (Art. 11 GeoIV) ist
hingegen fakultativ. Das BAFU wird als zuständige Stelle für die Daten bezeichnet.
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**2**

Diese Geobasisdaten sind gemäss GeoIV der Zugangsberechtigungsstufe A
zugeteilt, d.h. dass sie öffentlich zugänglich sind und ein Download-Dienst
vorgesehen ist.
Seit dem 1. Januar 1967 ist das Bundesgesetz über den Natur und Heimatschutz
(NHG) in Kraft. Es hat u.a. zum Ziel, das heimatliche Landschafts- und Ortsbild, die
geschichtlichen  Stätten sowie die Natur- und Kulturdenkmäler des Landes zu
schonen und die einheimische Tier- und Pflanzenwelt sowie ihre biologische
Vielfalt und ihren natürlichen Lebensraum zu schützen. In den Artikeln 23b, 23c
und 23d sind die Grundlagen für die Bezeichnung und den Schutz der
Moorlandschaften von besonderer Schönheit und von nationaler Bedeutung
festgehalten.
Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von
Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können
(Ebene Kanton oder Gemeinde), um die unterschiedlichen Bedürfnisse im Vollzug
abbilden zu können. Das nachfolgend vorgegebene minimale Geodatenmodell
verpflichtet das Bundesamt die Daten in dieser Form zu pflegen und mit den im
Datenmodell definierten Relationen zur Verfügung zu stellen.
NHG
Rechtlicher Stellenwert

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**3**


## 2. Ziel und Zweck


**2.1.**


**Ausgangslage der Erhebung von Informationen zu Moorlandschaften**

Moorlandschaften sind in besonderem Masse durch Moore geprägte naturnahe
Landschaften,
die
daneben
auch
andere
bemerkenswerte
Natur-
und
Kulturelemente beherbergen. Sie stellen für verschiedene Tier- und Pflanzenarten
die
letzten
verbliebenen
Lebensräume
dar.
Das
wissenschaftliche
Moorlandschaftsinventar wurde in den Jahren 1987 - 90 von der Hintermann &
Weber AG im Auftrag des EDI erhoben. Gemäss Art. 23b des Bundesgesetzes
vom 1. Juli 1966 über den Natur- und Heimatschutz (NHG) bezeichnet der
Bundesrat unter Berücksichtigung der bestehenden Besiedlung und Nutzung die
schützenswerten Moorlandschaften von besonderer Schönheit und von nationaler
Bedeutung und bestimmt deren Lage. Er arbeitet dabei eng mit den Kantonen
zusammen, welche ihrerseits die betroffenen Grundeigentümer anhören.

**2.2.**


**Umsetzung**

Mit
der
Moorlandschafts-Verordnung
werden
die
national
bedeutenden
Moorlandschaften unter Schutz gestellt. Der Bundesrat setzte diese 1996 mit dem
Bundesinventar mit 88 Objekten im Anhang in Kraft. Eine erste Revision erfolgte
2001 auf Antrag des Kantons VD, eine zweite mit der definitiven Aufnahme des
Objektes Grimsel im Jahre 2004 und weitere 2007 und 2017.
Die Regelungen zur Nutzung der Moorlandschaften ausserhalb der Moorbiotope
sind weniger rigoros als für die Moorbiotope selber. Für jede Moorlandschaft gelten
allgemeine sowie der Moorlandschaft eigene Schutzziele.
Die Schutzziele sind festgehalten in der Moorlandschaftsverordnung:

Erhaltung der Schönheit und Vielfalt der Landschaft, welche die nationale
Bedeutung ausmachen

Ungeschmälerte Erhaltung aller Moorbiotope

Erhaltung der charakteristischen Elemente einer Moorlandschaft

Besondere Rücksichtnahme auf seltene und gefährdete Pflanzen und
Tiere

Unterstützung der für die Moorlandschaft typische Nutzung
Für sämtliche Flach- und Hochmoore innerhalb der Moorlandschaften gelten
Schutzziele und Massnahmen entsprechend den jeweiligen Verordnungen.

**2.3.**


**Welche Objekte werden erfasst?**

Von besonderer Schönheit und von nationaler Bedeutung ist eine Moorlandschaft
dann, wenn sie in ihrer Art einmalig ist oder in einer Gruppe von vergleichbaren
Moorlandschaften zu den wertvollsten gehört. Dazu wurden die Moorlandschaften
sowohl gruppiert (14 Typen) als auch bewertet. Aus der Gegenüberstellung zur
naturräumlichen Gliederung der Schweiz ergaben sich die Einmaligen und die
Gruppenbesten.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Moorlandschaftsschutz
Langfristig geschützte
Biotope

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**4**


**2.4.**


**Welche Informationen werden wie veröffentlicht?**

Das Bundesinventar bildet als Anhang 2 Bestandteil der Verordnung über den
Schutz der Moorlandschaften von besonderer Schönheit und von nationaler
Bedeutung. Im Internet werden die Objektlisten und Objektblätter als pdf-Formate
publiziert. Die Geodaten werden in der BGDI dargestellt und sind auf der
Homepage des BAFU integriert, wo sie gemäss den Bestimmungen des
Geoinformationsgesetzes öffentlich zur Verfügung stehen.

**2.5.**


**Aufwand**

Das BAFU ist für den Aufbau, die periodische Aktualisierung und die Auswertung
des Datensatzes und die Erstellung der entsprechenden Statistiken zuständig.

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

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**5**


## 3. Modellbeschreibung


**3.1.**


**Moorlandschaften**

Die potentiellen Moorlandschaften wurden aufgrund definierter  Abgrenzungsregeln
im Felde erfasst und kartiert. Für die Bewertung der Objekte wurden 9 Kriterien
herangezogen: Fläche, Anteil moortypische Fläche, Erschliessung, Moorbiotope,
geomorphologische Elemente, Biotopelemente, Kulturelemente, Besiedlung und
Beeinträchtigungen. Die definitive Aufnahme ins Inventar erfolgte durch eine
Expertengruppe.  Fläche und Lage dieser Objekte sind in den Feldkartierungen
des Bundesinventars im Massstab 1:25‘000 festgehalten. Die Perimeter wurden
auf der Basis dieser Grundlagen digitalisiert.
Abbildung 1: Georeferenzierung des Objekts mittels PK25

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**6**


## 4. Modell-Struktur: konzeptionelles Datenmodell


**4.1.**


**Graphische Darstellung**

Die Abbildung 2 zeigt das UML-Diagramm für das Bundesinventar der
Moorlandschaften von besonderer Schönheit und nationaler Bedeutung.
Moorlandschaft
ObjNummer[1] : Zeichenkette
Name[1] : Zeichenkette
RefObjBlatt[0..1] : Zeichenkette
DesignatType[0..1] : DesignationType
IUCNCategory[1] : IUCNCategory
Inkraftsetzungsdatum[1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Mutationsgrund[0..1] : Zeichenkette
Moorlandschaft_Teilobjekt
TelObjNummer[1] : Zeichenkette
Geo_Obj[1] : MultiPolygon
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
1..*
Abbildung 2: Darstellung des Bundesinventares der Moorlandschaften von besonderer Schönheit und nationaler Bedeutung als UML-
Diagramm

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**7**


**4.2.**


**Objektklassenkatalog**

A1 Entität I NVENTAR O BJEKT : Moorlandschaft
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.1
ObjNummer
Eindeutiger Code zur
Kennzeichnung des

**Objekts**


**TEXT**


**15**


**Nummer Bundesinventar**

Obligatorisch
A1.2
Name
Bezeichnung des

**Objekts**


**TEXT**


**Glaubenberg**


**Name auf Objektblatt**

Obligatorisch
A1.3
RefObjBlatt
URl
(Persistenter) Link auf das Objektblatt
Fakultativ
A1.4
DesignatType
Schutzgebietstyp für
die internationale

**Berichterstattung.**

Angabe wird vom
BAFU gemäss Liste
DesignationType (EU)

**gemacht**


**DesignationType:**


**AUFZÄHLUNG**


**Ramsar**

Vgl.
http://inspire.jrc.ec.europa.eu/documents/Da
ta_Specifications/INSPIRE_DataSpecificatio

**n_PS_v3.0.pdf**

Obligatorisch
A1.5
IUCNCategory
Internationale
Schutzgebietskategorie
für die internationale

**Berichterstattung.**

Code wird vom BAFU
gemäss Kategorien

**IUCNCategory:**


**AUFZÄHLUNG**

5
(Management

**Area)**

http://www.unep-
wcmc.org/protected_areas/categories/index.

**html**

Obligatorisch

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**8**

MCPFE und der
Kategorien der IUCN

**gemacht.**

A1.6
Inkraftsetzungsdatum
Datum der
Inkraftsetzung des
Objekts
DATE

**01.02.1991**

Obligatorisch
A1.7
Mutationsdatum
Datum der Mutation
des Objekts
DATE

**1.07.2007**

Fakultativ
A1.8
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT (255)
Vergrösserung
Objekt auf

**Antrag Kt**

Fakultativ
Entität Moorlandschaft_Teilobjekt
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.9
TeilObjNummer
Teilobjektnummer des
Teilobjekts
ZAHL
Bundesinterne Identifikationsnummer des
Teilobjekts. Voreingestellter Wert für Objekte
ohne Teilobjekte = 0
Bedingung: Ein eindeutiger Schlüssel für jeden
Datensatz ist aus den zwei Merkmalen
ObjNummer + TeilObjNummer erstellbar.
Obligatorisch
A1.10
Geo_Obj
Ausdehnung des
Objekts
POLYGON
Obligatorisch

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**9**


**4.3.**


**Beschreibung mit INTERLIS 2.3**

Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im
Anhang. Gegenüber INTERLIS 1 bietet INTERLIS 2 verschiedene Vorteile. So
können zum Beispiel Bedingungen (Constraints) formuliert werden. Weiter ist die
Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die
Version 2.3 von INTERLIS zu verwenden.

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**10**


## 5.


## Darstellung der Daten der Moorlandschaften


**5.1.**


**Darstellungsmodell Bund**

Die Daten der Moorlandschaften werden vom BAFU für den Vollzug des Arten-
und Biotopschutzes verwendet. Die Darstellung erfolgt im Rahmen des Erlasses
resp. bei Revisionen der Moorlandschaftsverordnung. Dabei gelangt die folgende
geographische Darstellungsart zur Anwendung (Abbildung 3).
Abbildung 3: Geographische Lage der Moorlandschaften
Legende:
Darstellungsmodell Bund

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**11**


## Anhang


**I Datenmodell im Format INTERLIS 2.3**

Bei Abweichungen zw. Modelldokumentation und Model Repository gilt die ILI-Version im Model Repository.
INTERLIS 2.3;
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=24.1
MODEL Moorlandschaften_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-03-27"  =
IMPORTS GeometryCHLV03_V1;
TOPIC Moorlandschaften =
DOMAIN
/* Aufzählungslisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
);

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**12**

IUCNCategory = (
Strict_Nature_Reserve_Ia,
Wilderness_Area_Ib,
National_Park_II,
Natural_Monument_III,
Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV03_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für Moorlandschaft-Teilobjekt */
CLASS Moorlandschaft_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
Geo_Obj : MANDATORY MultiPolygon;
END Moorlandschaft_Teilobjekt;

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**13**

/* Klasse für gesamtes Moorlandschaft-Objekt */
CLASS Moorlandschaft =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : TEXT*255;
END Moorlandschaft;
/* Klassenübergreifender Constraint für Eindeutigkeit */
VIEW vML
JOIN OF Moorlandschaft_Teilobjekt,Moorlandschaft; =
ATTRIBUTE
ALL OF Moorlandschaft_Teilobjekt;
ALL OF Moorlandschaft;
UNIQUE ObjNummer,TeilObjNummer;
END vML;
ASSOCIATION Moorlandschaft_TeilobjektFlachmoor =
Moorlandschaft_Teilobjekt -- {1..*} Moorlandschaft_Teilobjekt;
Moorlandschaft -<#> {1} Moorlandschaft;
END Moorlandschaft_TeilobjektFlachmoor;
END Moorlandschaften;
END Moorlandschaften_LV03_V1_1.

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**14**

!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=24.1
MODEL Moorlandschaften_LV95_V1_1 (en)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-03-27"  =
IMPORTS GeometryCHLV95_V1;
TOPIC Moorlandschaften =
DOMAIN
/* Aufzählungslisten */
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

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**15**

Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für Moorlandschaft-Teilobjekt */
CLASS Moorlandschaft_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
Geo_Obj : MANDATORY MultiPolygon;
END Moorlandschaft_Teilobjekt;
/* Klasse für gesamtes Moorlandschaft-Objekt */
CLASS Moorlandschaft =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**16**

IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : TEXT*255;
END Moorlandschaft;
/* Klassenübergreifender Constraint für Eindeutigkeit */
VIEW vML
JOIN OF Moorlandschaft_Teilobjekt,Moorlandschaft; =
ATTRIBUTE
ALL OF Moorlandschaft_Teilobjekt;
ALL OF Moorlandschaft;
UNIQUE ObjNummer,TeilObjNummer;
END vML;
ASSOCIATION Moorlandschaft_TeilobjektFlachmoor =
Moorlandschaft_Teilobjekt -- {1..*} Moorlandschaft_Teilobjekt;
Moorlandschaft -<#> {1} Moorlandschaft;
END Moorlandschaft_TeilobjektFlachmoor;
END Moorlandschaften;
END Moorlandschaften_LV95_V1_1.

**BAFU 2017**

Moorlandschaften: Umsetzung des Geoinformationsgesetztes

**17**


**II Darstellungsmodell Bundesinventare der Moorlandschaften von besonderer Schönheit und**


**nationaler Bedeutung**


**(Moorlandschaft)**

Layer transparency: 0%
Fläche:
Type: Line Fill
Farbname: Cantaloupe
RGB: 255,167,127
Separation: 15
Linetyp: Line
Linewidth: 1.0
Outline:
Type: Marker Line Symbol
Farbname: Cantaloupe
RGB: 255,167,127
Marker
Line
Symbol:
Circle1
Size:
3.0
Cartographic
Line
Width: 5.0
Line
Caps:
Butt
Line
Joins:
Mitter
Template