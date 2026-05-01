BAFU 2012
Auengebiete Kant Inventar : Umsetzung des Geoinformationsgesetzes

# Technische Anleitungen


# Geobasisdaten des


# Umweltrechts


# Kantonales Inventar der Auengebiete von


# nationaler, regionaler und lokaler Bedeutung


# Identifikator 26.1


### Bundesamt für Umwelt BAFU / AÖL

BAFU 2012
Auengebiete Kant Inventar : Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Auengebiete
Kant.
Inventar
(GeoIV
p.
21);
Identifikator 26.1

**FIG**

Mitglieder der AG gitKBNL
Catherine Guex, Frederic Aubert  (VD)  2010
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
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes

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
Welche Objekte werden wie erfasst? ...................................................... 3
2.4.
Welche Informationen werden wie veröffentlicht? ................................... 4
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
Objektklassenkatalog .............................................................................. 8
4.3.
Beschreibung mit INTERLIS 2.3 ...........................................................11

### 5.


### Darstellung der Daten der Auengebiete ............................. 12

5.1.
Darstellungsmodell Bund ......................................................................12

### Anhang

I
Datenmodell im Format INTERLIS 2.3
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Auen finden sich dort, wo Wasser von Gletschern, Flüssen und Seen in flacheren
Bereichen mit Land intensiv in Berührung kommt. Typisch ist, dass der
Wasserspiegel schwankt. Unterschieden wird zwischen den Tieflandauen-
Flussauen, Deltas und Seeauen - sowie den alpinen Auen - Gletschervorfelder und
alpine Schwemmebenen. Da Auen eine Vielzahl verschiedener Lebensräume
aufweisen, finden sich sehr viele Tier- und Pflanzenarten in diesen Ökosystemen.
90% der Schweizer Auen sind in den letzten Jahrzehnten verschwunden und bei
den Tieflandauen von nationaler Bedeutung weist nur noch ein Drittel eine
natürliche
Dynamik
auf.
Gewässerverbauungen,
die
Entwässerung
der
Flussebenen, der Bau von Stauseen sowie von Wasserfassungen für die
Stromproduktion sind vor allem für das Verschwinden vieler Auen verantwortlich.
Dazu kommen der Bau von Infrastrukturanlagen wie Strassen, Deponien und
Kiesabbau, das Wachsen der Agglomerationen sowie die intensive Nutzung durch
Wald- und Landwirtschaft und Tourismus.
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
expliziten Raumbezugs ist das Kantonale Inventar der Auengebiete von nationaler
und regionaler Bedeutung in diesen Ausführungsbestimmungen aufgeführt (Anh. 1
GeoIV, Identifikator 26). Art. 9 GeoIV definiert die Aufgaben der zuständigen
Fachstelle des Bundes. Im Anh. 1 der GeoIV wird für den Geobasisdatensatz 26
das BAFU als die zuständige Fachstelle des Bundes bezeichnet. Diese muss somit
ein minimales Geodatenmodell vorgeben, das Definieren und Beschreiben eines
oder mehrerer Darstellungsmodell/e (Art. 11 GeoIV) ist hingegen fakultativ. Die
Kantone werden als zuständige Stelle für die Daten bezeichnet. Diese
Geobasisdaten sind gemäss GeoIV der Zugangsberechtigungsstufe A zugeteilt,
d.h. dass sie öffentlich zugänglich sind und ein Download-Dienst vorgesehen ist.
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
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
verpflichtet die Kantone die Daten in dieser Form zu pflegen und mit den im
Datenmodell definierten Relationen zur Verfügung zu stellen.
NHG
Rechtlicher Stellenwert
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu Auengebieten
Auen sind als natürliche Lebensräume im Überschwemmungsbereich von
Gewässern im Rückgang begriffen. Das wissenschaftliche Aueninventar wurde
vom EDI im Mai 1981 in Auftrag gegeben und an der eidgenössischen Anstalt für
das
forstliche
Versuchswesen
(heute
WSL)
in
der
Forschungsgruppe
Vegetationskunde erstellt. Gemäss Art 18a des Bundesgesetzes vom 1. Juli 1966
über den Natur- und Heimatschutz (NHG) - in Kraft seit dem 1. Februar 1988 - be-
zeichnet der Bundesrat die Biotope von nationaler Bedeutung, bestimmt ihre Lage
und legt die Schutzziele fest. Dies geschieht jedoch erst nach Anhören der
Kantone. Als zweites Bundesinventar gemäss Art. 18a NHG setzte der Bundesrat
1992 das Bundesinventar der Auengebiete mit 169 Objekten in Kraft, welches in
den Jahren 2001, 2003 und 2007 mittels dreier Ergänzungen komplettiert wurde.
Zwischen 1995 und 1997 wurde das Inventar der Gletschervorfelder und alpinen
Schwemmebenen (IGLES), als wissenschaftliches Inventar, die Grundlage der 1.
Ergänzung erarbeitet.
2.2.
Umsetzung
Mit der Auen-Verordnung (SR 451.31) werden die wertvollsten Auen unter Schutz
gestellt. Diese verpflichtet die Kantone den genauen Grenzverlauf festzulegen und
ökologisch ausreichende Pufferzonen auszuscheiden. Die Objekte sollen
ungeschmälert erhalten bleiben. Ein Abweichen vom Schutzziel ist nur zulässig für
unmittelbar standortgebundene Vorhaben, die dem Schutz des Menschen vor
schädlichen Auswirkungen des Wassers oder einem andern überwiegenden
öffentlichen Interesse von ebenfalls nationaler Bedeutung dienen. Weiter sorgen
die Kantone für Schutz und Unterhalt der Biotope von regionaler und lokaler
Bedeutung, die Bestimmung der Bedeutung ist in der Kompetenz der Kantone. Die
Kantonalen Inventare umfassen die Objekte von nationaler Bedeutung, für die der
Kanton den genauen Grenzverlauf festgelegt hat (SR451.31 Art. 3 Abs.1) sowie
die Objekte von regionaler und lokaler Bedeutung.
Der Datensatz ist Grundlage für die Öffentlichkeitsarbeit (international und
national) im Bereich Biodiversität (Berichte, Statistiken, Artikel in der Fachpresse,
Auskünfte auf Anfragen, usw.).
2.3.
Welche Objekte werden wie erfasst?
Ins Bundesinventar aufgenommen und im Massstab 1:25‘000 kartiert wurden
Auengebiete wenn sie auf der Minimalfläche typische Auenvegetation aufweisen,
sowie Gletschervorfelder und alpine Schwemmebenen mit einem glazifluvial oder
fluvial geprägten Auenbereich von mindestens 2500m2 Fläche.
Für die Umsetzung der Auenverordnung wurden von den Kantonen für viele dieser
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
unterschiedlich stark vom Bundesperimeter ab. Aus den Auenkartierungen
resultieren weitere Objekte nicht nationaler  Bedeutung, die ebenfalls im Massstab
1:25‘000 erfasst wurden. Diese werden ergänzt durch Kartierungen von Objekten
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Auenschutz
Langfristig geschützte
Biotope
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
4
von regionaler und lokaler Bedeutung in unterschiedlichen Massstäben. Da es sich
beim kantonalen Inventar um Vegetationskartierungen von Biotopen und nicht um
Schutzperimeter handelt, enthält es keine Pufferzonen.
2.4.
Welche Informationen werden wie veröffentlicht?
Die Geodaten werden zukünftig in der  NGDI zur Verfügung gestellt. Das Inventar
ist nicht Bestandteil des ÖREB-Katasters.
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
Veröffentlichung der Daten
Geodaten
Geobasisdaten
Georeferenzdaten
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Auengebiete
Auen wurden aufgrund ihrer Grösse und Vegetation, mindestens 2 ha an
natürlichen oder 5 ha an korrigierten Gewässern mit typischer Auenvegetation auf
der Minimalfläche, erfasst und im Massstab 1:25‘000 kartiert. Gletschervorfelder
und alpine Schwemmebenen müssen einen glazifluvial oder fluvial geprägten
Auenbereich von mindestens 2500 m2 aufweisen. Die kantonalen Kartierungen
wurden auf Basis unterschiedlicher Grundlagen erstellt. Fläche und Lage dieser
Objekte sind in den Feldkartierungen des Bundesinventars und den kantonalen
Kartierungen festgehalten. Die Perimeter wurden auf der Basis dieser Grundlagen
digitalisiert.
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
6

## 4. Modell-Struktur: konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die Abbildung 1 zeigt das UML-Diagramm für das kantonale Inventar der
Auengebiete von nationaler, regionaler und lokaler Bedeutung.
Kartierungsgrundlage_CatRef
MultiSurface
MultilingualMText
kt_Auengebiet
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Obj_GISFlaeche[1] : Numerisch
Herkunft[1] : Zeichenkette
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Bedeutung_CatRef
AU_TYP_CatRef
kt_Auengebiet_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
Geo_Obj
+
1
1..*
Bedeutung
+
1
AU_TYP
+
0..1
Kartierungsgrundlage
+
1
Mutationgsgrund
+
0..1
Abbildung 1: Darstellung des kantonalen Inventares der  Auengebiete von nationaler, regionaler und lokaler Bedeutung  als UML-Diagramm
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
7
Kartierungsgrundlage_Catalogue
Code[1] : Zeichenkette
Kartierungsgrundlage_CatRef
Bedeutung_CatRef
MultilingualText
Bedeutung_Catalogue
Code[1] : Zeichenkette
Reference
+
Reference
+
Description
+
1
Description
+
1
AU_TYP_Catalogue
Code[1] : Zeichenkette
AU_TYP_CatRef
Description
+
1
Reference
+
Abbildung 2: Darstellung entsprechenden Codelisten als UML-Diagramm
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
8
4.2.
Objektklassenkatalog
Entität kt_Auengebiet
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
AG
Obligatorisch
A1.2
ObjNummer
Eindeutiger Code zur
Kennzeichnung des
Objekts
TEXT
11
Nummer kantonale Grundlage
Obligatorisch
A1.3
Name
Bezeichnung des
Objekts
TEXT
Beuggenboden
Falls vorhanden
Fakultativ
A1.4
Obj_GISFlaeche
GIS-Gesamtfläche des
Objekts in ha
DOUBLE
23.5124134 ha
Obligatorisch
A1.5
AU_TYP
Gewässertypen
AUFZÄHLUNG
AU_TYP2
Definition AU_TYP verwenden falls erhoben
oder weglassen
Fakultativ
A1.6
Herkunft
Ursprünglicher
Kantonaler
Datenbestand
TEXT
Kartierung der
Auengebiete
Kanton Aargau
1990
Hinweis aus welchem Inventar oder welcher
Kartierung diese Daten stammen
Obligatorisch
A1.7
Kartierungsgrundlage
Grundlage für die
Erfassung des
Perimeters
AUFZÄHLUNG
K2

**Definition Grundlage siehe unten**

Obligatorisch
A1.8
Aufnahmedatum
Datum der Aufnahme
ins kantonale Inventar
DATE
01.03.1990
Fakultativ
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
9
oder Verzeichnis
A1.9
Mutationsdatum
Datum der Mutation
des Objekts
DATE
1.07.2007
Fakultativ
A1.10
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Vergrösserung
Objekt
Fakultativ
A1.11
Bedeutung
Bedeutung des Objekts
AUFZÄHLUNG
B2
Definition Bedeutung siehe unten
Obligatorisch
Entität kt_Auengebiet_Teilobjekt
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.12
Teilobj_Nr
Identifikationsnummer
des Teilobjekts
TEXT
Kantonsinterne Identifikationsnummer des
Teilobjekts
Obligatorisch
A1.13
Geo_Obj
Ausdehnung des
Objekts
POLYGON
Obligatorisch
Entität AU_TYP
Code
DE
FR
IT
AU_TYP1
AU_TYP2
AU_TYP3
AU_TYP4
AU_TYP5
Fliessgewässer
Delta
Seeufer
Alpine Schwemmebene
Gletschervorfeld
Cours d‘eau
Delta
Rive lacustre
Plaine alluviale alpine
Marge proglaciaire
Cors d’aqua
Delta
Riva del lago
Pianura alluvionale alpina
Margine proglaziale
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
10
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
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
11
4.3.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
12

## 5. Darstellung der Daten der Auengebiete

5.1.
Darstellungsmodell Bund
Für regionale Auen besteht noch kein Darstellungsmodell
5.2 Kantonale Darstellungsmodelle
Für kantonale Daten besteht noch kein Darstellungsmodell
Darstellungsmodell Bund
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
13

## Anhang

I Datenmodell im Format INTERLIS 2.3
INTERLIS 2.3;
!!@ technicalContact = gis@bafu.admin.ch;
!!@ IDGeoIV = "26.1";
!!@ furtherInformation = http://www.bafu.admin.ch/geodatenmodelle;
!! Repository: models.geo.admin.ch/bafu;
!! Version 1;
MODEL kt_Auen_V1 (en)
AT "http://www.bafu.admin.ch/geodatenmodelle"
VERSION "2012-11-06" =
IMPORTS
AdministrativeUnits_V1,WithLatestModification_V1,Localisation_V1,CatalogueObjects_V1,GeometryCHLV03_V1,CHAdminCodes_
V1,LocalisationCH_V1,Units;
TOPIC aCodelisten =
CLASS AU_TYP_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*8;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END AU_TYP_Catalogue;
CLASS Bedeutung_Catalogue
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
14
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Bedeutung_Catalogue;
CLASS Kartierungsgrundlage_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END Kartierungsgrundlage_Catalogue;
STRUCTURE AU_TYP_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO AU_TYP_Catalogue;
END AU_TYP_CatRef;
STRUCTURE Bedeutung_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO Bedeutung_Catalogue;
END Bedeutung_CatRef;
STRUCTURE Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO Kartierungsgrundlage_Catalogue;
END Kartierungsgrundlage_CatRef;
END aCodelisten;
TOPIC kt_Auengebiet =
BAFU 2012
Auengebiete Kant Inventar: Umsetzung des Geoinformationsgesetzes
15
OID AS INTERLIS.UUIDOID;
CLASS kt_Auengebiet =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT;
Name : TEXT;
Obj_GISFlaeche : MANDATORY 1.000 .. 999999999.000 [Units.ha];
AU_TYP : kt_Auen_V1.aCodelisten.AU_TYP_CatRef;
Herkunft : MANDATORY TEXT;
Kartierungsgrundlage : MANDATORY kt_Auen_V1.aCodelisten.Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY kt_Auen_V1.aCodelisten.Bedeutung_CatRef;
END kt_Auengebiet;
CLASS kt_Auengebiet_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT;
Geo_Obj : MANDATORY GeometryCHLV03_V1.MultiSurface;
END kt_Auengebiet_Teilobjekt;
ASSOCIATION Teilobjektkt_Auengebiet =
kt_Auengebiet_Teilobjekt -- {1..*} kt_Auengebiet_Teilobjekt;
kt_Auengebiet -<#> {1} kt_Auengebiet;
END Teilobjektkt_Auengebiet;
END kt_Auengebiet;
END kt_Auen_V1.