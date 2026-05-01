BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes

# Technische Anleitungen


# Geobasisdaten des


# Umweltrechts


# Kantonales Inventar der Flachmoore von


# nationaler, regionaler und lokaler Bedeutung


# Identifikator 28.1


### Bundesamt für Umwelt BAFU /AÖL

BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Flachmoore
Kant.
Inventar
(GeoIV
p.
21);
Identifikator 28.1

**FIG**

Mitglieder der AG git KBNL
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
BAFU: Christian Schlatter
Ab 2010:
Kurt Spälti (IKGeo)
2011:
Peter Staub (GKG/KOGIS)

**Leiter der FIG**

Jürg Schenker, BAFU AÖL

**Datum**

06.11.2012

**Version**

1.0
.
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu Flachmooren .......... 3
2.2.
Umsetzung .............................................................................................. 3
2.3.
Welche Objekte werden wie erfasst? ...................................................... 3
2.4.
Welche Informationen werden wie veröffentlicht? ................................... 3
2.5.
Aufwand ................................................................................................... 4
2.6.
Begriffe aus dem GeoIG .......................................................................... 4

### 3.


### Modellbeschreibung ............................................................... 5

3.1.
Flachmoore .............................................................................................. 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung ........................................................................... 6
4.2.
Objektklassenkatalog .............................................................................. 7
4.3.
Beschreibung mit INTERLIS 2.3 ...........................................................10

### 5.


### Darstellung der Daten der Flachmoore .............................. 11

5.1.
Darstellungsmodell Bund ......................................................................11

### Anhang

I
Datenmodell im Format INTERLIS 2.3
II
Darstellungsmodell
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Flachmoore sind durch Rodungen oder Verlandungen und nachfolgende
landwirtschaftliche Nutzung auf nassen Böden entstanden. Wegen umfangreicher
Entwässerungen zur Gewinnung von Kulturland und Aufdüngung sind Flachmoore
und deren typische Arten in der Schweiz sehr selten geworden.
Flachmoore werden heute nicht mehr durch grossflächige Meliorationen zerstört,
wie dies früher der Fall war, jedoch oft durch unangepasste Nutzung, lokale
Drainagen oder Nährstoffeintrag aus benachbarten Flächen in ihrer Qualität
geschmälert. Werden abgelegene Parzellen nicht mehr bewirtschaftet, besteht die
Gefahr, dass diese mit Gehölze einwachsen.
Flachmoore werden heute auch nicht mehr grossflächig überbaut, jedoch stehen
sie oft im Interessenkonflikt mit neuen Erschliessungsstrassen und Infrastrukturen
für den Tourismus sowie dem Nutzungsdruck von Freizeitaktivitäten jeder Art.
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
expliziten Raumbezugs ist das kantonale Inventar der Flachmoore in diesen
Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikator 28). Art. 9
GeoIV definiert die Aufgaben der zuständigen Fachstelle des Bundes. Im Anh. 1
der GeoIV wird für den Geobasisdatensatz 28 das BAFU als die zuständige
Fachstelle
des
Bundes
bezeichnet.
Diese
muss
somit
ein
minimales
Geodatenmodell vorgeben, das Definieren und Beschreiben eines oder mehrerer
Darstellungsmodell/e (Art. 11 GeoIV) ist hingegen fakultativ. Die Kantone werden
als zuständige Stelle für die Daten bezeichnet. Diese Geobasisdaten sind gemäss
GeoIV der Zugangsberechtigungsstufe A zugeteilt, d.h. dass sie öffentlich
zugänglich sind und ein Download-Dienst vorgesehen ist.
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
2
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
verpflichtet die Kantone die Daten in dieser Form zu pflegen mit den im
Datenmodell definierten Relationen zur Verfügung zu stellen.
NHG
Rechtlicher Stellenwert
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu Flachmooren
Flachmoore sind Überreste der ursprünglichen Natur- und Kulturlandschaft und
sind
stark
im
Rückgang
begriffen.
Sie
beherbergen
hochangepasste
Lebensgemeinschaften von Pflanzen und Tieren mit einer grossen Zahl
gefährdeter Tier- und Pflanzenarten. Das wissenschaftliche Flachmoorinventar
wurde in den Jahren 1987 - 90 von einer Arbeitsgemeinschaft im Auftrag des EDI
erhoben. Weitere Objekte wurden von den Kantonen im Rahmen eigener
Kartierungen erfasst.
2.2.
Umsetzung
Mit der Flachmoor-Verordnung (SR 451.33) werden die wichtigsten Flachmoore
unter Schutz gestellt. Diese verpflichtet die Kantone den genauen Grenzverlauf
festzulegen und ökologisch ausreichende Pufferzonen auszuscheiden. Die Objekte
müssen ungeschmälert erhalten bleiben. Weiter sorgen die Kantone für Schutz
und Unterhalt der Biotope von regionaler und lokaler Bedeutung, die Bestimmung
der Bedeutung ist in der Kompetenz der Kantone. Die Kantonalen Inventare der
Objekte umfassen die Objekte von nationaler Bedeutung, für die der Kanton den
genauen Grenzverlauf festgelegt hat (SR 451.33 Art. 3 Abs.1) sowie die Objekte
von regionaler und lokaler Bedeutung.
Der Datensatz ist Grundlage für die Öffentlichkeitsarbeit (international und
national) im Bereich Biodiversität (Berichte, Statistiken, Artikel in der Fachpresse,
Auskünfte auf Anfragen, usw.).
2.3.
Welche Objekte werden wie erfasst?
Die nationalen Flachmoore wurden aufgrund der Merkmale Fläche und Vegetation
ins Bundesinventar aufgenommen und im Massstab 1:25‘000 kartiert. Für die
Umsetzung der Flachmoorverordnung wurden von den Kantonen für viele dieser
Objekte
Detailkartierungen
auf
Basis
unterschiedlicher
kartographischer
Grundlagen
durchgeführt.
Die
Perimeter
der
Detailkartierungen
weichen
unterschiedlich stark vom Bundesperimeter ab. Aus der Flachmoorkartierung
resultierten weitere Objekte nicht nationaler Bedeutung, die ebenfalls im Massstab
1:25‘000 erfasst wurden. Diese werden ergänzt durch Kartierungen von Objekten
von regionaler und lokaler Bedeutung in unterschiedlichen Massstäben. Da es sich
beim kantonalen Inventar um Vegetationskartierungen von Biotopen und nicht um
Schutzperimeter handelt, enthält es keine Pufferzonen.
2.4.
Welche Informationen werden wie veröffentlicht?
Die Geodaten werden zukünftig in der  NGDI zur Verfügung gestellt. Das Inventar
ist nicht Bestandteil des ÖREB-Katasters.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Flachmoorschutz
Langfristig geschützte
Flachmoore
Veröffentlichung der Daten
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
4
2.5.
Aufwand
Die Kantone sind für den Aufbau und die periodische Aktualisierung zuständig.
Das BAFU ist für die Auswertung des Datensatzes und die Erstellung der
Statistiken im nationalen Kontext zuständig.
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
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Flachmoore
Flachmoore wurden aufgrund von Fläche und Vegetation erfasst und im Massstab
1:25‘000 kartiert. Objekte wurden ins Bundesinventar aufgenommen, wenn sie
eine Mindestfläche von 1 Hektare und bei der Bewertung mindestens 15 Punkte
beim Bewertungsmass erreichten. Flachmoorflächen die mehr als 100 m
auseinanderliegen wurden als separate Objekte erfasst. Weiter wurden auf Antrag
der Kantone Objekte wegen Singularitäten (Besonderheiten) aufgenommen. Die
Objekte welche bei der Bewertung die notwendige Punktzahl nicht erreichten
werden beim Bund in einem Datensatz „Flachmore von regionaler Bedeutung“
geführt. Die kantonalen Kartierungen wurden auf Basis unterschiedlicher
Grundlagen erstellt, wobei die Bedingungen des Bundesinventars nicht
konsequent angewendet wurden. Fläche und Lage dieser Objekte sind in den
Feldkartierungen des Bundesinventars und den kantonalen Kartierungen
festgehalten. Die Perimeter wurden auf der Basis dieser Grundlagen digitalisiert.
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
6

## 4. Modell-Struktur: konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die Abbildung 1 zeigt das UML-Diagramm des kantonalen Inventar der
Flachmoore von nationaler, regionaler und lokaler Bedeutung.
Kartierungsgrundlage_CatRef
kt_Flachmoor_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
MultilingualMText
kt_Flachmoor
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Obj_GISFlaeche[1] : Numerisch
Herkunft[1] : Zeichenkette
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
MultiSurface
Bedeutung_CatRef
Bedeutung
+
1
1..*
Mutationgsgrund
+
0..1
Kartierungsgrundlage
+
1
Geo_Obj
+
1
Abbildung 1: Darstellung des kantonalen Inventar der Flachmoore von nationaler, regionaler und lokaler Bedeutung.
Kartierungsgrundlage_Catalogue
Code[1] : Zeichenkette
Bedeutung_Catalogue
Code[1] : Zeichenkette
Kartierungsgrundlage_CatRef
Bedeutung_CatRef
MultilingualText
Reference
+
Description
+
1
Description
+
1
Reference
+
Abbildung 2: Darstellung entsprechenden Codelisten als UML-Diagramm
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
7
4.2.
Objektklassenkatalog
Entität kt_Flachmoor
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
Kantonskürzel
TEXT
BE
Obligatorisch
A1.2
ObjNummer
Eindeutiger Code zur
Kennzeichnung des
Objekts
TEXT
14532
Nummer kantonale Grundlage
Obligatorisch
A1.3
Name
Bezeichnung des
Objekts
TEXT
-
Falls vorhanden
Fakultativ
A1.4
Obj_GISFlaeche
GIS-Gesamtfläche des
Objektes in ha
DOUBLE
0.7326 ha
Obligatorisch
A1.5
Herkunft
Ursprünglicher
Kantonaler
Datenbestand
TEXT
Inventar der
Feuchtgebiete
des  Kanton
Bern 2000
Hinweis aus welchem Inventar oder welcher
Kartierung diese Daten stammen
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
01.02.2000
Fakultativ
A1.8
Mutationsdatum
Datum der Mutation
des Objekts
DATE
01.07.2007
Fakultativ
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
8
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
Bedeutung des Objekts
AUFZÄHLUNG
B1
Definition Bedeutung siehe unten
Obligatorisch
Entität kt_Flachmoor_Teilobjekt
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
Geo_Obj
Ausdehnung des
Objekts
POLYGON
Obligatorisch
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
9
Entität Kartierungsgrundlage
Code
DE
FR
IT
K1
K2
K3
K4
K5
K6
Landeskarte 1:25000
Andere Landeskarte
Kantonale Plangrundlage
Luftbild, Orthophoto
andere
unbekannt
Carte nationale 1 :25’000
Autre carte nationale
Base cantonale de planification
Photographie arienne, orthophoto
Autres
Inconnu
Carta nazionale 1:25’000
Altra carta nazionale
Base cartografica cantonale
Immagine aerea, orthophoto
Altri/e
Sconosciuto
Entität Bedeutung
Code
DE
FR
IT
B1
B2
B3
National
Regional
Lokal
National
Régional
Local
Nazionale
Regionale
Locale
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
10
4.3.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
11

## 5. Darstellung der Daten der Flachmoore

5.1.
Darstellungsmodell Bund
Die Daten der regionalen und lokalen Flachmoore werden vom BAFU als
Ergänzung zu den Bundesinventaren für den Vollzug des Arten- und
Biotopschutzes
verwendet.
Dabei
gelangt
die
folgende
geographische
Darstellungsart zur Anwendung (Abbildung 3).
Abbildung 3: Geographische Lage der regionalen Flachmoore
Legende:
5.2
Darstellungsmodell Kantone
Es wird vorgeschlagen für die kantonalen Daten die Darstellungsmodelle des
Bundes für nationale und regionale Flachmoore zu verwenden.
Darstellungsmodell Bund
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
12

## Anhang

I Datenmodell im Format INTERLIS 2.3
INTERLIS 2.3;
!!@ technicalContact = gis@bafu.admin.ch;
!!@ IDGeoIV = "28.1";
!!@ furtherInformation = http://www.bafu.admin.ch/geodatenmodelle;
!! Repository: models.geo.admin.ch/bafu;
!! Version 1;
MODEL kt_Flachmoore_V1 (en)
AT "http://www.bafu.admin.ch/geodatenmodelle"
VERSION "2012-11-06" =
IMPORTS
CatalogueObjects_V1,Units,Localisation_V1,CHAdminCodes_V1,WithLatestModification_V1,LocalisationCH_V1,Administrative
Units_V1,GeometryCHLV03_V1;
TOPIC Codelisten =
CLASS Bedeutung_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Bedeutung_Catalogue;
CLASS Kartierungsgrundlage_Catalogue
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
13
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Kartierungsgrundlage_Catalogue;
STRUCTURE Bedeutung_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO Bedeutung_Catalogue;
END Bedeutung_CatRef;
STRUCTURE Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO Kartierungsgrundlage_Catalogue;
END Kartierungsgrundlage_CatRef;
END Codelisten;
TOPIC kt_Flachmoor =
CLASS kt_Flachmoor =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT;
Name : TEXT;
Obj_GISFlaeche : MANDATORY 1.000 .. 999999999.000 [Units.ha];
Herkunft : MANDATORY TEXT;
Kartierungsgrundlage : MANDATORY kt_Flachmoore_V1.Codelisten.Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
14
Bedeutung : MANDATORY kt_Flachmoore_V1.Codelisten.Bedeutung_CatRef;
END kt_Flachmoor;
CLASS kt_Flachmoor_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT;
Geo_Obj : MANDATORY GeometryCHLV03_V1.MultiSurface;
END kt_Flachmoor_Teilobjekt;
ASSOCIATION Teilobjektkt_Flachmoor =
kt_Flachmoor_Teilobjekt -- {1..*} kt_Flachmoor_Teilobjekt;
kt_Flachmoor -<#> {1} kt_Flachmoor;
END Teilobjektkt_Flachmoor;
END kt_Flachmoor;
END kt_Flachmoore_V1.
BAFU 2012
Flachmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
15
II Darstellungsmodell Kantonales Inventar der Flachmoore nationaler und regionaler
Bedeutung
(Flachmoore Kant Inventar)
Layer transparency: 45%
Fläche:
Type: Simple Fill
Farbname: Peridot Green
RGB: 170, 255, 0
Outline:
Type: Line
Width: 0.4
Farbname: Macaw Green
RGB: 152, 230, 0