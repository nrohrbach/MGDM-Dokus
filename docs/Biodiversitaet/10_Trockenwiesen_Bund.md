Bern, 13. November 2023

### Bundesamt für Umwelt BAFU /AÖL


# Bundesinventar der


# Trockenwiesen und -


# weiden von nationaler


# Bedeutung


# Identifikator 186.1


# Geobasisdaten des Umweltrechts


# Modelldokumentation


# Version 1.2


**Offiz. Bezeichner**

Trockenwiesen (GeoIV p. 33); Identifikator 186.1

**FIG**

Mitglieder der AG gitKBNL
Catherine Guex
Andreas Lienhard (ZH)
Stefan Meier (AG)
Markus Müller Egli (LU)
Remo Bianchi (SZ)
Rolf Niederer (TG) ab 2010
Norbert Danuser (GR)
Simone Serretti (TI)
Stefan Rey (ZG)
Mirjam Zehnder (KKGEO)
Rolf Zürcher(GKG/KOGIS)
Dominik Angst (BAFU)

**Leiter der FIG**

Helmut Recher, BAFU AÖL

**Datum**

13.11.2023

**Version**

Von der Direktion des BAFU verabschiedete
Version
Änderungskontrolle
Version
Beschreibung
Datum
1.0
Erstfassung des Modells
24.02.2015
1.1
Überarbeitung auf Grund technischer Anpassungen
05.09.2017
1.1
Technische Anpassungen: Einführung Multipart-
Geometrien
09.12.2020
1.2
Ergänzung des Merkmals «Singularität»
13.11.2023
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu Trockenwiesen ....... 3
2.2.
Umsetzung .............................................................................................. 3
2.3.
Welche Objekte werden erfasst? ............................................................ 3
2.4.
Welche Informationen werden veröffentlicht? ......................................... 4
2.5.
Aufwand ................................................................................................... 4
2.6.
Begriffe aus dem GeoIG .......................................................................... 4

### 3.


### Modellbeschreibung ............................................................... 5

3.1.
Trockenwiesen ........................................................................................ 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung ........................................................................... 6
4.2.
Objektklassenkatalog .............................................................................. 7
4.3.
Beschreibung mit INTERLIS 2.3 ...........................................................11

### 5.


### Darstellung der Daten der Trockenwiesen ......................... 12

5.1.
Darstellungsmodell Bund ......................................................................12

### Anhang

I
Datenmodell im Format INTERLIS 2.3
II
Darstellungsmodell
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Trockenwiesen und -weiden sind von landwirtschaftlicher Nutzung geprägte,
artenreiche Lebensräume. Die Ausprägungen dieser Lebensräume sind aufgrund
unterschiedlicher naturräumlicher und kulturhistorischer Verhältnisse äusserst
vielfältig. Der Bund hat die wertvollsten Flächen in einem Inventar bezeichnet.
Unterhalb der Waldgrenze verdankt das Grünland seine Existenz zum grössten Teil
der Tätigkeit des Menschen. Seit Jahrtausenden hat der Mensch Wiesen und
Weiden landwirtschaftlich genutzt und dabei eine enorme Vielfalt hervorgebracht.
In Trockenwiesen und -weiden lebt eine Vielzahl an Pflanzen und Tieren.  Trockene
Wiesen und Weiden sind magere Standorte. Die Erträge sind vergleichsweise gering
und erlauben nur eine extensive Bewirtschaftung.
Da sich die traditionelle Bewirtschaftung von Trockenwiesen und -weiden heute nicht
mehr überall lohnt, geht der Bestand an Trockenwiesen in der Schweiz drastisch
zurück: In den vergangenen 60 Jahren sind rund 90 % der Trockenwiesen und -
weiden in der Schweiz verschwunden.  Die Hauptgründe für diesen massiven
Rückgang in der Schweiz sind:
•
Intensivierung der Landwirtschaft,
•
attraktive Wohnlagen an Südhängen,
•
Ersatzaufforstungen für Bauten und Anlagen und
•
seit kurzem auch die Nutzungsaufgabe in abgelegenen Gebieten.
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
im Anhang 1 die „Geobasisdaten des Bundesrechts“ auf. Unter anderem bestimmt
Art. 9 GeoIV, dass die zuständige Fachstelle des Bundes ein minimales
Geodatenmodell zu jedem Geobasisdatensatz vorgibt (Anhang 1 GeoIV). Für die
Geobasisdatensätze im Bereich der Umwelt ist die zuständige Fachstelle des
Bundes das BAFU. Soweit der Vollzug der jeweiligen Bestimmungen bei den
Kantonen liegt, erfolgt die Erarbeitung des Datenmodells in Zusammenarbeit mit den
1 Begriffe gemäss GeoIG, siehe Kap. 2.6
Grundlagen
GeoIG
GeoIV
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
2
Kantonen. Schliesslich sieht die GeoIV in Verbindung mit. der entsprechenden
Verordnung des Umweltrechts vor, dass das BAFU auch ein minimales
Darstellungsmodell vorgibt (Art. 11 GeoIV, Art. 27b NHV (SR 451.1). Soweit die
Kantone für den Vollzug zuständig sind, werden auch die Darstellungsmodelle von
BAFU und Kantone gemeinsam erarbeitet.
Seit dem 1. Januar 1967 ist das Bundesgesetz über den Natur- und Heimatschutz
(NHG) in Kraft. Es hat u.a. zum Ziel, das heimatliche Landschafts- und Ortsbild, die
geschichtlichen Stätten sowie die Natur- und Kulturdenkmäler des Landes zu
schonen und die einheimische Tier- und Pflanzenwelt sowie ihre biologische Vielfalt
und ihren natürlichen Lebensraum zu schützen. In den Artikeln 18a und 18b sind die
Grundlagen für die Bezeichnung und den Schutz der Biotope von nationaler,
regionaler und lokaler Bedeutung festgehalten.
Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von
Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können
(Ebene Kanton oder Gemeinde). Für die Kantone ist das nachfolgende minimale
Geodatenmodell verbindlich. Es ist ihnen freigestellt, in ihre Datenmodelle
zusätzliche Informationen zu integrieren.
NHG
Rechtlicher Stellenwert
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu Trockenwiesen
Mit bis zu 100 Pflanzenarten pro Are gehören Trockenwiesen und -weiden zu den
artenreichsten Pflanzengesellschaften der Schweiz. In Trockenwiesen und -weiden
können beinahe zwei Drittel sowohl der gesamten Schweizer Flora als auch der
seltenen und gefährdeten Pflanzenarten gefunden werden. Von den 3100
Pflanzenarten der Schweiz kommen über 400 (13%) vorwiegend in diesem
Lebensraum vor. 1981 unterbreitete der Bund den Kantonen einen Vorschlag zur
gesamtschweizerischen Kartierung der Halbtrocken- und Trockenrasen der
Schweiz, den er den Kantonen zur Anwendung empfahl (die so genannte ANL-
Methode). In den Jahren darauf wurde die Methode von einigen Kantonen teilweise
abgeändert und für die Erstellung kantonaler Inventare übernommen. Die darin
enthaltenen Ziele wurden in freiwilligen Vereinbarungen mit den einzelnen
Bewirtschafterinnen und Bewirtschaftern umgesetzt. Einzelne kantonale Modelle
konnten bald erfreuliche Erfolge aufweisen. Trotz der Bemühungen von Bund und
Kantonen im Bereich des Arten- und Biotopschutzes, sowie der Neuausrichtung der
Landwirtschaftspolitik konnte der Rückgang wertvoller TWW gesamtschweizerisch
nicht verhindert werden. Die vorliegenden Ergebnisse der Inventarisierungsarbeiten
durch den Bund bestätigen diese unerfreuliche Entwicklung in aller Deutlichkeit. Auf
Grund der Ergebnisse einer Umfrage sowie auf Grund der Analyse der
verschiedenen kantonalen Vorgehensweisen beschloss der Bund 1994, eine
selektive Neukartierung der TWW mit einer gesamtschweizerisch einheitlichen
Erhebungsmethode durchzuführen.
2.2.
Umsetzung
Mit der Trockenwiesen-Verordnung werden die wertvollsten Trockenwiesen der
Schweiz unter Schutz gestellt. Als letztes Bundesinventar gemäss Art. 18a NHG
setzte der Bundesrat 2010 das Bundesinventar der Trockenwiesen und -weiden mit
2934 Objekten in Kraft, welches 2012 und 2017 revidiert wurde.
Die Objekte sind ungeschmälert zu erhalten. Das Schutzziel umfasst insbesondere:
•
die Erhaltung und Förderung der spezifischen Pflanzen- und Tierwelt sowie ihrer
ökologischen Grundlagen;
•
die Erhaltung der für die Trockenwiesen typischen Eigenart, Struktur und
Dynamik
•
eine nachhaltig betriebene Land- und Waldwirtschaft.
In Vorranggebieten sind die ökologische Qualität der an die Objekte angrenzenden
natürlichen und naturnahen Lebensräume und Strukturelemente sowie deren
Vernetzung zu fördern, damit die spezifische Funktionsfähigkeit der Objekte
verbessert werden kann.
2.3.
Welche Objekte werden erfasst?
Die Trockenwiesen und –weiden wurden nach einer neu entwickelten
Kartiermethode, welche die Biodiversität des Lebensraumes Trockenwiesen in den
Grundzügen kartiert, aufgenommen. Sie lehnt sich an die Methode der früheren
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den Schutz
der Trockenwiesen
Langfristig geschützte
Biotope
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
4
Inventarisierungen der Kantone (ANL-Methode) an. Aufgenommen wurden die
wertvollsten 30% der Objekte der bestehenden kantonalen Inventare, welche nach
einer einheitlichen Bewertung ausgeschieden und für die Aufnahme ins neue
Inventar vorgeschlagen wurden. Bei Kantonen ohne Inventar wurden die
abzusuchenden Gebiete aufgrund von Expertenbefragungen ermittelt. Die
Kartierung beruht auf dem Prinzip der Einheitsflächenkartierung, wobei  die
Trockenwiesen aufgrund der Merkmale Minimalfläche und pflanzensoziologische
Verbände aufgenommen wurden.
2.4.
Welche Informationen werden veröffentlicht?
Das Bundesinventar bildet als Anhang 2 Bestandteil der Verordnung über den
Schutz der Trockenwiesen von nationaler Bedeutung. Im Internet werden die
Objektlisten und Objektblätter als pdf-Formate kantonsweise publiziert. Die
Geodaten werden auf der BGDI dargestellt und sind auf der Homepage des BAFU
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
Veröffentlichung der Daten
Geodaten
Geobasisdaten
Georeferenzdaten
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Trockenwiesen
Trockenwiesen und –weiden wurden aufgrund einer differenzierten und
luftbildgestützten
Vegetationskartierung
mit
einem
modular
aufgebauten
Vegetationsschlüssel erhoben und im Massstab 1:10‘000 kartiert. Parallel wurde
gestützt
auf
das
Modell
der
Nutzwertanalyse
ein
Bewertungs-
und
Klassierungsverfahren entwickelt. Fläche und Lage der Objekte sind in den
Feldkartierungen des Bundesinventars festgehalten. Die Perimeter wurden auf der
Basis dieser Grundlagen digitalisiert.
Abbildung 1: Georeferenzierung des Objekts mittels PK25
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
6

## 4. Modell-Struktur: konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die Abbildung 2 zeigt das UML-Diagramm für die Trockenwiesen.
Abbildung 2: Darstellung des Bundesinventar der Trockenwiesen und –weiden von nationaler Bedeutung als UML-Diagramm
Trockenwiese_Teilobjekt
TeilObjNummer[1] : Zeichenkette
Bewertungseinheit[1] : Numerisch
Singularitaet[1] : Boolean
Geo_Obj[1] : MultiPolygon
Trockenwiese
ObjNummer[1] : Zeichenkette
Name[1] : Zeichenkette
RefObjBlatt[0..1] : Zeichenkette
DesignatType[0..1] : DesignationType
IUCNCategory[1] : IUCNCategory
Inkraftsetzungsdatum[1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Mutationsgrund[0..1] : Zeichenkette
IUCNCategory
<<enumeration>>
Strict_Nature_Reserve_Ia
Wilderness_Area_Ib
National_Park_II
Natural_Monument_III
Habitat_or_Species_Management_Area_IV
Protected_Landscape_or_Seascape_V
Managed_Resource_Protected_Area_VI
DesignationType
<<enumeration>>
SAC
SPA
SCI
RAMSAR
NDA
BAFU 20203
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
7
4.2.
Objektklassenkatalog
Klasse Trockenwiese
Merkmal (Attribut)
Erklärung der
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
6154
Nummer Bundesinventar
Obligatorisch
A1.2
Name
Bezeichnung des
Objekts
TEXT
Petit Sauges
Name auf Objektblatt
Obligatorisch
A1.3
RefObjBlatt
URl
URI
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
Fakultativ
A1.5
IUCNCategory
Internationale
Schutzgebietskategori
e für die internationale
Berichterstattung.
Code wird vom BAFU
gemäss Kategorien
IUCNCategory:
AUFZÄHLUNG
IV
(Management
Area)
http://www.unep-
wcmc.org/protected_areas/categories/index.
html
Obligatorisch
BAFU 20203
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
8
MCPFE und der
Kategorien der IUCN
gemacht.
A1.6
Inkraftsetzungsdatum
Datum der
Inkraftsetzung des
Objekts
DATE
01.02.2010
Obligatorisch
A1.7
Mutationsdatum
Datum der Mutation
des Objekts
DATE
17.01.2012
Fakultativ
A1.8
Mutationsgrund
Grund der Mutation
des Objekts
TEXT
Vergrösserung
Objekt auf
Antrag Kt
Fakultativ
BAFU 20203
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
9
Klasse Trockenwiese_Teilobjekt
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
Identifikationsnummer
des Teilobjekts
TEXT
eindeutige Identifikationsnummer eines
Teilobjekts, zusammengesetzt aus:
Kantonskürzel (2-stellig),
persönliche Kartierer-ID (3-stellig) und
Laufnummer im Feld (4-stellig).
Z.B.  „BL3010002“ besteht aus
Kantonskürzel =BL
Kartierer-ID = 301
Laufnummer = 0002
Bedingung: Ein eindeutiger Schlüssel für jeden
Datensatz ist aus den zwei Merkmalen
ObjNummer + TeilObjNummer erstellbar.
Obligatorisch
A1.10
Bewertungseinheit
Nummer
Bewertungseinheit
NUMERISCH
6154
Flächen mit gleicher Bewertungseinheit sind
benachbart oder unter 100m entfernt. Ihre
Punktebewertung wird zusammengefasst
einem Objekt zugeordnet.
Obligatorisch
A1.11
Singularitaet
Besondere Eigenarten
BOOLEAN
Ja / Nein
Eine Singularität wird durch das
Vorhandensein eines oder mehrerer
Obligatorisch
BAFU 20203
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
10
besonders wertgebender Merkmale gemäss
Liste definiert 3 .
Default = Nein
A1.12
Geo_Obj
Ausdehnung des
Objekts
MULTIPOLYGO
N
Obligatorisch
3 Die Liste enthält folgende Einträge: a) enthält TWW-Zielarten, b) enthält geschützte oder gefährdete Arten, c) besondere Nutzungsform: traditionelle Nutzung in sehr schmalen Streifen
("Hosenträger"), d) bedeutendes Landschaftselement und e) grosse Vielfalt verschiedener Lebensraumtypen.
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
11
4.3.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang.
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
12

## 5. Darstellung der Daten der Trockenwiesen

5.1.
Darstellungsmodell Bund
Die Daten der Trockenwiesen werden vom BAFU für den Vollzug des Arten- und
Biotopschutzes verwendet. Die Darstellung erfolgt im Rahmen des Erlasses resp.
bei Revisionen der Trockenwiesenverordnung. Dabei gelangt die folgende
geographische Darstellungsart zur Anwendung (Abbildung 3).
Abbildung 3: Geographische Lage der Trockenwiesen
Legende:
Darstellungsmodell Bund
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes

## Anhang

I Datenmodell im Format INTERLIS 2.3
Bei Abweichungen zwischen der INTERLIS-Modelldefinition in der Modelldokumentation und dem Model Repository gilt die Version m Model Repository.
INTERLIS 2.3;
!! Version    | Who   | Modification
!!------------------------------------------------------------------------------
!! 2022-06-02 | BAFU  | Korrektur Multipolygone (anstelle Polygone), VIEW durch CONSTRAINTS OF ersetzt, LV03 gelöscht
!! 2022-11-15 | BAFU  | Ergänzung Attribut "Singularitaet"
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ IDGeoIV=186.1
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL Trockenwiesen_V1_2 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2023-11-15"  =
IMPORTS GeometryCHLV95_V1;
TOPIC Trockenwiesen =
DOMAIN
DesignationType = (
SAC,
SPA,
SCI,
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
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
/** Flächen ohne Kreisbogen */
Polygon = SURFACE WITH (STRAIGHTS) VERTEX GeometryCHLV95_V1.Coord3 WITHOUT OVERLAPS > 0.001;
/** Definition von Multipolygonen, analog CHBase Geometry */
STRUCTURE PolygonStructure =
Polygon: Polygon;
END PolygonStructure;
STRUCTURE MultiPolygon =
Polygons: BAG {1..*} OF PolygonStructure;
END MultiPolygon;
CLASS Trockenwiese_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
Bewertungseinheit : MANDATORY 0 .. 999999;
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
Singularitaet : MANDATORY BOOLEAN;
Geo_Obj : MANDATORY MultiPolygon;
END Trockenwiese_Teilobjekt;
CLASS Trockenwiese =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : TEXT*255;
END Trockenwiese;
ASSOCIATION Teilobjekt =
Trockenwiese_Teilobjekt -- {1..*} Trockenwiese_Teilobjekt;
Trockenwiese -<#> {1} Trockenwiese;
END Teilobjekt;
/** Klassenübergreifender Constraint für Eindeutigkeit */
CONSTRAINTS OF Trockenwiese_Teilobjekt =
UNIQUE TeilObjNummer, Trockenwiese->ObjNummer;
END;
END Trockenwiesen;
END Trockenwiesen_V1_2.
BAFU 2023
Trockenwiesen: Umsetzung des Geoinformationsgesetzes
II Darstellungsmodell Bundesinventar der Trockenwiesen von nationaler Bedeutung
(Trockenwiesen)