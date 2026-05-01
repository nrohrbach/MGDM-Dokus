
# Bundesinventar der


# Auengebiete von


# nationaler


# Bedeutung


# Identifikator 19.1


# Geobasisdaten des Umweltrechts


# Modelldokumentation


# Version 1.1

Bern, 11. November 2019

### Bundesamt für Umwelt BAFU /AÖL

BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
1

**Offiz. Bezeichner**

Auengebiete (GeoIV p. 20); Identifikator 19.1

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
Stefan Lussi, BAFU AÖL

**Leiter der FIG**

Helmut Recher, BAFU AÖL

**Datum**

11.11.2019

**Version**

Von der Direktion des BAFU verabschiedete
Version
Änderungskontrolle
Version
Beschreibung
Datum
1.0
Erstfassung des Modells
06.11.2012
1.1
Technische Anpassung INTERLIS-Beschreibung
Korrektur der Codeliste „Typ“ ; Technische
Anpassungen der Modellstruktur: UML, Objektklassen,
INTERLIS
16.01.2018
1.1
Ergänzung UNIQUE-Constraint im ILI, Korrektur des
italienischen Textes in Entität TYP 3
11.11.2019
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu Auengebieten ......... 3
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
Auengebiete ............................................................................................ 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung ........................................................................... 6
4.2.
Objektklassenkatalog .............................................................................. 7
4.3.
Beschreibung mit INTERLIS 2.3 ...........................................................10

### 5.


### Darstellung der Daten der Auengebiete ............................. 11

5.1.
Darstellungsmodell Bund ......................................................................11

### Anhang

I
Datenmodell im Format INTERLIS 2.3
II
Darstellungsmodell
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Auen finden sich dort, wo Wasser von Gletschern, Flüssen und Seen in flacheren
Bereichen mit Land intensiv in Berührung kommt. Typisch ist, dass der
Wasserspiegel schwankt. Unterschieden wird zwischen den Tieflandauen -
Flussauen, Deltas und Seeauen - sowie den alpinen Auen - Gletschervorfelder und
alpine Schwemmebenen. Da Auen eine Vielzahl verschiedener Lebensräume
aufweisen, finden sich sehr viele Tier- und Pflanzenarten in diesen Ökosystemen.
90% der Schweizer Auen sind in den letzten Jahrzehnten verschwunden und bei
den Tieflandauen von nationaler Bedeutung weist nur noch ein Drittel eine natürliche
Dynamik auf. Gewässerverbauungen, die Entwässerung der Flussebenen, der Bau
von Stauseen sowie von Wasserfassungen für die Stromproduktion sind vor allem
für das Verschwinden vieler Auen verantwortlich. Dazu kommen der Bau von
Infrastrukturanlagen wie Strassen, Deponien und Kiesabbau, das Wachsen der
Agglomerationen sowie die intensive Nutzung durch Wald- und Landwirtschaft und
Tourismus.
Seit dem 1. Juli 2008 ist das Bundesgesetz über Geoinformation (GeoIG) in Kraft.
Es hat zum Ziel, auf nationaler Ebene verbindliche bundesrechtliche Standards für
die Erfassung, Modellierung und den Austausch von Geodaten 1 des Bundes,
insbesondere von Geobasisdaten des Bundesrechts, festzulegen. Weiter regelt es
die Finanzierung, das Urheberrecht sowie den Datenschutz. Das Gesetz bildet auch
für das Datenmanagement der Kantone und Gemeinden neue, gesicherte rechtliche
Grundlagen. So wird sich der Zugang zu den mit grossem Aufwand erhobenen und
verwalteten Daten für Behörden, Wirtschaft und Bevölkerung verbessern. Es wird
eine Mehrfachnutzung der gleichen Daten in den verschiedensten Anwendungen
ermöglichen. Mit der Harmonisierung werden auch
Verknüpfungen von
Datenbanken möglich, die einfache und neuartige Auswertungen ermöglichen. Die
Werterhaltung und die Qualität der Geodaten soll über lange Zeitperioden
sichergestellt werden.
Mit dem GeoIG ist auch die Verordnung über Geoinformationen (GeoIV) in Kraft
getreten. Sie präzisiert das GeoIG in fachlicher sowie technischer Hinsicht und führt
im Anhang 1 die „Geobasisdaten des Bundesrechts“ auf. Wegen des expliziten
Raumbezugs
ist
das
Bundesinventar
der
Auengebiete
in
diesen
Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikator 19). Art. 9 GeoIV
definiert die Aufgaben der zuständigen Fachstelle des Bundes. Im Anh. 1 der GeoIV
wird für den Geobasisdatensatz 19 das BAFU als die zuständige Fachstelle des
Bundes bezeichnet. Diese muss somit ein minimales Geodatenmodell vorgeben,
das Definieren und Beschreiben eines oder mehrerer Darstellungsmodell/e (Art. 11
GeoIV) ist hingegen fakultativ. Das BAFU wird als zuständige Stelle für die Daten
bezeichnet.
Diese
Geobasisdaten
sind
gemäss
GeoIV
der
Zugangsberechtigungsstufe A zugeteilt, d.h. dass sie öffentlich zugänglich sind und
ein Download-Dienst vorgesehen ist.
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
2
Seit dem 1. Januar 1967 ist das Bundesgesetz über den Natur und Heimatschutz
(NHG) in Kraft. Es hat u.a. zum Ziel, das heimatliche Landschafts- und Ortsbild, die
geschichtlichen  Stätten sowie die Natur- und Kulturdenkmäler des Landes zu
schonen und die einheimische Tier- und Pflanzenwelt sowie ihre biologische Vielfalt
und ihren natürlichen Lebensraum zu schützen. In den Artikeln 18a und 18b sind die
Grundlagen für die Bezeichnung und den Schutz der Biotope von nationaler,
regionaler und lokaler Bedeutung festgehalten.
Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von
Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können
(Ebene Kanton oder Gemeinde), um die unterschiedlichen Bedürfnisse im Vollzug
abbilden zu können. Das nachfolgend vorgegebene minimale Geodatenmodell
verpflichtet das Bundesamt die Daten in dieser Form zu pflegen und mit den im
Datenmodell definierten Relationen zur Verfügung zu stellen.
NHG
Rechtlicher Stellenwert
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu Auengebieten
Auen sind als natürliche Lebensräume im Überschwemmungsbereich von
Gewässern im Rückgang begriffen. Das wissenschaftliche Aueninventar wurde vom
EDI im Mai 1981 in Auftrag gegeben und an der eidgenössischen Anstalt für das
forstliche Versuchswesen (heute WSL) in der Forschungsgruppe Vegetationskunde
erstellt. Gemäss Art 18a des Bundesgesetzes vom 1. Juli 1966 über den Natur- und
Heimatschutz (NHG) - in Kraft seit dem 1. Februar 1988 - bezeichnet der Bundesrat
die Biotope von nationaler Bedeutung, bestimmt ihre Lage und legt die Schutzziele
fest. Dies geschieht jedoch erst nach Anhören der Kantone. Als zweites
Bundesinventar gemäss Art. 18a NHG setzte der Bundesrat 1992 das
Bundesinventar der Auengebiete mit 169 Objekten in Kraft, welches in den Jahren
2001, 2003, 2007 und 2017 ergänzt wurde.  Zwischen 1995 und 1997 wurde das
Inventar der Gletschervorfelder und alpinen Schwemmebenen (IGLES), als
wissenschaftliches Inventar, die Grundlage der 1. Ergänzung erarbeitet.
2.2.
Umsetzung
Mit der Auen-Verordnung werden die wertvollsten Auen der Schweiz unter Schutz
gestellt. Auf der Grundlage des Natur- und Heimatschutzgesetzes wurde 1992 das
Bundesinventar der Auen von nationaler Bedeutung in Kraft gesetzt. In zwei
Schritten wurde das Inventar vor allem mit den Gebirgsauen ergänzt. Die
Auenverordnung von 1992 verpflichtet die Kantone:

die Auen von nationaler Bedeutung zu schützen,

die Pflanzen und Tiere der Auen zu erhalten und zu fördern,

die Dynamik der Auen zu erhalten bzw. wiederherzustellen und

Nutzungen im Einklang mit den Schutzzielen zu regeln.
Es ist die Aufgabe der Kantone, dafür zu sorgen, dass Pläne und Vorschriften für die
zulässige Nutzung des Gebietes der Verordnung entsprechen. Bestehende
Nutzungen dürfen den Schutzzielen nicht zuwider laufen. Seltene und gefährdete
Pflanzen- und Tierarten sind gezielt zu fördern .
2.3.
Welche Objekte werden erfasst?
Aufgenommen und kartiert wurden Auengebiete von mindestens 2 ha an natürlichen
oder naturnahen Gewässern, von mindestens 5 ha an korrigierten Gewässern, wenn
sie
auf
der
Minimalfläche
typische
Auenvegetation
aufweisen,
sowie
Gletschervorfelder und alpine Schwemmebenen mit einem glazifluvial oder fluvial
geprägten Auenbereich von mindestens 2500m2 Fläche.
2.4.
Welche Informationen werden wie veröffentlicht?
Das Bundesinventar bildet als Anhang 2 Bestandteil der Verordnung über den
Schutz der Auengebiete von nationaler Bedeutung. Im Internet werden die
Objektlisten und Objektblätter als pdf-Formate kantonsweise publiziert. Die
Geodaten werden auf der BGDI dargestellt und sind auf der Homepage des BAFU
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Auenschutz
Langfristig geschützte
Biotope
Veröffentlichung der Daten
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
4
integriert, wo sie gemäss den Bestimmungen des Geoinformationsgesetzes
öffentlich zur Verfügung stehen.
2.5.
Aufwand
Das BAFU ist für den Aufbau, die periodische Aktualisierung und die Auswertung
des Datensatzes und die Erstellung der entsprechenden Statistiken zuständig.
2.6.
Begriffe aus dem GeoIG
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
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Auengebiete
Auen wurden aufgrund ihrer Grösse und Vegetation, mindestens 2 ha an natürlichen
oder 5 ha an korrigierten Gewässern mit typischer Auenvegetation auf der
Minimalfläche, erfasst und im Massstab 1:25‘000 kartiert. Gletschervorfelder und
alpine Schwemmebenen müssen einen glazifluvial oder fluvial geprägten
Auenbereich von mindestens 2500 m2 aufweisen. Fläche und Lage dieser Objekte
sind auf den Originalkarten des Bundesinventars im Massstab 1:25‘000
festgehalten. Die Perimeter wurden auf der Basis dieser Grundlagen digitalisiert.
Abbildung 1: Georeferenzierung des Objekts mittels PK25
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
6

## 4. Modell-Struktur: konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die Abbildung 2 zeigt das UML-Diagramm für die Auengebiete.
Abbildung 2: Darstellung des Bundesinventar der Auengebiete von nationaler Bedeutung als UML-Diagramm
Auengebiet_Teilobjekt
Geo_Obj[1] : MultiPolygon
Auengebiet
ObjNummer[1] : Zeichenkette
Name[1] : Zeichenkette
RefObjBlatt[0..1] : Zeichenkette
DesignatType[0..1] : DesignationType
IUCNCategory[1] : IUCNCategory
Typ[1] : TYP_CatRef
Inkraftsetzungsdatum[1] : XMLDate
Mutationsdatum[0..1] : XMLDate
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
1..*
TYP_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
TYP_CatRef
Reference
+
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
7
4.2.
Objektklassenkatalog
Entität Auengebiet
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
Objekts
TEXT
321
Nummer Bundesinventar
Obligatorisch
A1.2
Name
Bezeichnung des
Objekts
TEXT
Harzisboden
Name auf Objektblatt
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
Berichterstattung.
Angabe wird vom
BAFU gemäss Liste
DesignationType (EU)
gemacht
DesignationType:
AUFZÄHLUNG
ramsar
Vgl.
http://inspire.jrc.ec.europa.eu/documents/Da
ta_Specifications/INSPIRE_DataSpecificatio
n_PS_v3.0.pdf
Obligatorisch
A1.5
IUCNCategory
Internationale
Schutzgebietskategori
e für die internationale
Berichterstattung.
Code wird vom BAFU
gemäss Kategorien
MCPFE und der
IUCNCategory:
AUFZÄHLUNG
IV
(Management
Area)
http://www.unep-
wcmc.org/protected_areas/categories/index.
html
Obligatorisch
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
8
Kategorien der IUCN
gemacht.
A1.6
Typ
Gewässertypen
AUFZÄHLUNG
2
Definition TYP siehe unten
Obligatorisch
A1.7
Inkraftsetzungsdatum
Datum der
Inkraftsetzung des
Objekts
DATE
01.02.1991
Obligatorisch
A1.8
Mutationsdatum
Datum der Mutation
des Objekts
DATE
1.07.2007
Fakultativ
A1.9
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Vergrösserung
Objekt auf
Antrag Kt
Fakultativ
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
9
Entität Auengebiet_Teilobjekt
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.10
Geo_Obj
Ausdehnung des
Objekts
POLYGON
Obligatorisch
Entität TYP
Code
DE
FR
IT
1
2
3
4
5
Gletschervorfeld
Alpine Schwemmebene
Fliessgewässer
Delta
Seeufer
Marge proglaciaire
Plaine alluviale alpine
Cours d'eau
Delta
Rive lacustre
Margine proglaciale
Pianura alluvionale alpina
Corso d'acqua
Delta
Riva del Lago
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
10
4.3.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
11

## 5. Darstellung der Daten der Auengebiete

5.1.
Darstellungsmodell Bund
Die Daten der Auengebiete werden vom BAFU für den Vollzug des Arten- und
Biotopschutzes verwendet. Die Darstellung erfolgt im Rahmen des Erlasses resp.
bei Revisionen der Auenverordnung. Dabei gelangt die folgende geographische
Darstellungsart zur Anwendung (Abbildung 3).
Abbildung 4: Geographische Lage der Auengebiete
Legende:
Darstellungsmodell Bund
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
12

## Anhang

I Datenmodell im Format INTERLIS 2.3
Bei Abweichungen zwischen der INTERLIS-Modelldefinition in der Modelldokumentation und dem Model Repository gilt die Version m Model Repository.
INTERLIS 2.3;
!! Version    | Who   | Modification
!!------------------------------------------------------------------------------
!! 2019-11-11 | BAFU  | UNIQUE-Constraint beim Attribut Auengebiet.ObjNummer eingfügt.
!!@ IDGeoIV=19.1
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL Auengebiete_Codelisten_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2019-11-11"  =
IMPORTS LocalisationCH_V1,CatalogueObjects_V1;
/* Modell für externe Codelisten, die anschliessend importiert werden in die Modelle *_LV03* und *_LV95" */
TOPIC Codelisten =
CLASS TYP_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*15;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END TYP_Catalogue;
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
13
STRUCTURE TYP_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) TYP_Catalogue;
END TYP_CatRef;
END Codelisten;
END Auengebiete_Codelisten_V1_1.
!!@ IDGeoIV=19.1
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL Auengebiete_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2019-11-11"  =
IMPORTS GeometryCHLV03_V1,LocalisationCH_V1,Auengebiete_Codelisten_V1_1;
TOPIC Auengebiete =
DEPENDS ON Auengebiete_Codelisten_V1_1.Codelisten;
DOMAIN
/* Aufzählungslisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
14
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
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV03_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für die Auen-Teilgebiete */
CLASS Auengebiet_Teilobjekt =
Geo_Obj : MANDATORY MultiPolygon;
END Auengebiet_Teilobjekt;
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
15
/* Klasse für das gesamte Auengebiet */
CLASS Auengebiet =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Typ : MANDATORY Auengebiete_Codelisten_V1_1.Codelisten.TYP_CatRef;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
UNIQUE ObjNummer;
END Auengebiet;
ASSOCIATION Auengebiet_TeilobjektAuengebiet =
Auengebiet_Teilobjekt -- {1..*} Auengebiet_Teilobjekt;
Auengebiet -<#> {1} Auengebiet;
END Auengebiet_TeilobjektAuengebiet;
END Auengebiete;
END Auengebiete_LV03_V1_1.
!!@ IDGeoIV=19.1
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL Auengebiete_LV95_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2019-11-11"  =
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
16
IMPORTS GeometryCHLV95_V1,LocalisationCH_V1,Auengebiete_Codelisten_V1_1;
TOPIC Auengebiete =
DEPENDS ON Auengebiete_Codelisten_V1_1.Codelisten;
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
Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
/* Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord3 WITHOUT OVERLAPS > 0.001;
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
17
/* Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
/* Klasse für die Auen-Teilgebiete */
CLASS Auengebiet_Teilobjekt =
Geo_Obj : MANDATORY MultiPolygon;
END Auengebiet_Teilobjekt;
/* Klasse für das gesamte Auengebiet */
CLASS Auengebiet =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Typ : MANDATORY Auengebiete_Codelisten_V1_1.Codelisten.TYP_CatRef;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
UNIQUE ObjNummer;
END Auengebiet;
ASSOCIATION Auengebiet_TeilobjektAuengebiet =
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
18
Auengebiet_Teilobjekt -- {1..*} Auengebiet_Teilobjekt;
Auengebiet -<#> {1} Auengebiet;
END Auengebiet_TeilobjektAuengebiet;
END Auengebiete;
END Auengebiete_LV95_V1_1.
BAFU 2019
Auengebiete: Umsetzung des Geoinformationsgesetzes
19
II Darstellungsmodell Bundesinventar der Auengebiete von nationaler Bedeutung
(Auengebiete)
Layer transparency: 55%
Fläche:
Type: Simple Fill
Farbname: -
RGB: 0,201,224
Outline:
Type: Line
Width: 0.2
Farbname: Larkspur Blue
RGB: 0,132,168