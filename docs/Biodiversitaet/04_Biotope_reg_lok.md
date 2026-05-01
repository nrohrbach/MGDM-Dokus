BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes

# Technische Anleitungen


# Geobasisdaten des


# Umweltrechts


# Übrige Biotope von regionaler und lokaler


# Bedeutung


# Identifikatoren 23.1, 23.2 und 23.3


### Bundesamt für Umwelt BAFU /AÖL

BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Biotope regional/lokal (GeoIV p. 21); Identifikatoren
23.1, 23.2 und 23.3

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
BAFU: Christian Schlatter (Abt. Wald)
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
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu regionalen und
lokalen Biotopen ................................................................................................... 3
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
Biotope regionaler und lokaler Bedeutung .............................................. 5

### 4.


### Modell-Struktur; konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung ........................................................................... 6
4.2.
Objektklassenkatalog .............................................................................. 9
4.3.
Beschreibung mit INTERLIS 2.3 ...........................................................13

### 5.


### Darstellung der Daten der regionalen/lokalen Biotope ..... 14

5.1.
Darstellungsmodell Bund ......................................................................14
5.2.
Darstellungsmodell Kantone .................................................................14

### Anhang

I
Datenmodell im Format INTERLIS 2.3
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Die gesetzliche Grundlage für den Natur- und Landschaftsschutz beim Bund liefert
das 1966 von beiden Kammern des eidgenössischen Parlaments einstimmig
angenommene Bundesgesetz über den Natur- und Heimatschutz (NHG). Es
verpflichtet die Behörden und Amtsstellen des Bundes, bei der Erfüllung ihrer
Aufgaben dafür zu sorgen, dass das heimatliche Landschafts- und Ortsbild,
geschichtliche Stätten sowie Natur- und Kulturdenkmäler geschont und, wo das
allgemeine Interesse an ihnen überwiegt, ungeschmälert erhalten bleiben. Von
zentraler Bedeutung  ist Artikel 18. Er verpflichtet zum Schutz genügend grosser
Lebensräume für die einheimische Tier- und Pflanzenwelt. Zu schützen sind
namentlich Uferbereiche, Riedgebiete, Moore, seltene Waldgesellschaften,
Hecken, Feldgehölze, Trockenrasen. Der Bund bezeichnet die Biotope von
nationaler Bedeutung. Für den Schutz der Biotope von regionaler und lokaler
Bedeutung sind die Kantone zuständig, die zudem in intensiv genutzten Gebieten
für den ökologischen Ausgleich mit Feldgehölzen, Hecken, Uferbestockungen oder
mit anderer naturnaher und standortgemässer Vegetation zu sorgen haben.
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
expliziten Raumbezugs sind die übrigen Biotope von regionaler und lokaler
Bedeutung in diesen Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV,
Identifikatoren 23.1, 23.2 und 23.3). Art. 9 GeoIV definiert die Aufgaben der
zuständigen Fachstelle des Bundes. Im Anh. 1 der GeoIV wird für den
Geobasisdatensatz 23 das BAFU als die zuständige Fachstelle des Bundes
bezeichnet. Diese muss somit ein minimales Geodatenmodell vorgeben, das
Definieren und Beschreiben eines oder mehrerer Darstellungsmodell/e (Art. 11
GeoIV) ist hingegen fakultativ. Die Kantone werden als zuständige Stelle für die
Daten
bezeichnet.
Diese
Geobasisdaten
sind
gemäss
GeoIV
der
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
2
Zugangsberechtigungsstufe A zugeteilt, d.h. dass sie öffentlich zugänglich sind
und ein Download-Dienst vorgesehen ist.
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
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu regionalen und
lokalen Biotopen
Das NHG beinhaltet die Aufforderung dem Aussterben einheimischer Tier- und
Pflanzenarten durch die Erhaltung genügend grosser Lebensräume entgegen-
zuwirken. Als weiteren wichtigen Schritt hat das Parlament am 19 Juni 1987 die
Bestimmungen des NHG über den Biotopschutz, vor allem durch Einführung klarer
Verfahrensvorschriften, ergänzt. Demzufolge wird der Bundesrat, nach Anhören
der Kantone, in der ganzen Schweiz Biotope von nationaler Bedeutung
bezeichnen. Um die Abgrenzung von Biotopen regionaler und lokaler Bedeutung
kümmern sich die Kantone; ebenso um die biologische Anreicherung intensiv
genutzter Gebiete mit Feldgehölzen, Hecken, Uferbestockungen oder anderer
standortsgemässer Vegetation.
2.2.
Umsetzung
Mit dem Artikel 18 im NHG wird die Verantwortung für den Schutz der Biotope und
weiterer wichtigerer Elemente im intensiv genutzten Gebiet geregelt. Er beauftragt
die Kantone die Biotope von regionaler und lokaler Bedeutung zu erfassen und für
deren Schutz und Unterhalt zu sorgen. Die Bestimmung der Bedeutung ist in der
Kompetenz der Kantone. Biotope im Sinne des NHG sind „Lebensräume“ (Art. 18
Abs. 1), besonders zu schützen sind Uferbereiche, Riedgebiete und Moore,
seltene Waldgesellschaften, Hecken, Feldgehölze, Trockenrasen und weitere
Standorte, die eine ausgleichende Funktion im Naturhaushalt erfüllen. Ein
Lebensraum ist dann ein Biotop von  regionaler oder lokaler Bedeutung, wenn ihm
die Schutzwürdigkeit nach den Kriterien  von Art. 14 Abs. 3 der NHV zugesprochen
wird.
2.3.
Welche Objekte werden wie erfasst?
Verschiedene Biotoptypen wurden vom Bund mit entsprechenden Verordnungen
unter Schutz gestellt. Die zugehörigen Kantonalen Inventare der Objekte von
nationaler, regionaler und lokaler Bedeutung umfassen auch die Objekte von
regionaler und lokaler Bedeutung dieser Biotoptypen.
Alle übrigen aus kantonalen Inventaren und Kartierungen bekannten Objekte
regionaler und lokaler Bedeutung werden hier erfasst, wobei als Kategorien die
Hauptlebensräume der Liste der schützenswerten Lebensraumtypen gemäss
Anhang 1 der NHV (ohne die Lebensräume der Biotopinventare des Bundes)
verwendet werden. Da diese bei weitem nicht alle Biotoptypen beinhalten die in
den Kantonen erfasst werden, können diese unter der Kategorie „weitere
Biotoptypen“ aufgeführt und definiert werden.
Das kantonale Inventar enthält Biotop- und Lebensraumkartierungen und ist nicht
identisch mit Schutzverordnungen.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Biotopschutz
Langfristig geschützte
Biotope
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
4
2.4.
Welche Informationen werden wie veröffentlicht?
Die Geodaten werden zukünftig in der NGDI zur Verfügung gestellt. Das Inventar
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
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Biotope regionaler und lokaler Bedeutung
Biotope regionaler und lokaler Bedeutung sind Lebensräume für die einheimische
Tier- und Pflanzenwelt und Elemente in der intensiv genutzten Landschaft. Da
diese Biotoptypen in alleiniger Verantwortung der Kantone erfasst werden sind
Definitionen, Kategorien und Aufnahmekriterien sehr unterschiedlich und erfolgen
nicht nach einheitlichen Regeln. Die kantonalen Kartierungen wurden auf Basis
unterschiedlicher Grundlagen erstellt. Fläche und Lage dieser Objekte sind in den
kantonalen Kartierungen und Inventaren festgehalten. Die Objekte wurden auf der
Basis dieser Grundlagen digitalisiert. Aufgrund der unterschiedlichen Typen und
Definitionen können diese Objekte als Flächen, Linien oder Punkte dargestellt
werden, entsprechend sind für die übrigen Biotope von regionaler und lokaler
Bedeutung 3 Datensätze möglich.
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
6

## 4. Modell-Struktur; konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die folgenden Abbildungen zeigen die UML-Diagramme für die Biotope von
regionaler und lokaler Bedeutung (für Flächen, Linien und Punkte).
MultiSurface
Biotopflaeche
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Bio_Typ_KT[0..1] : Zeichenkette
Herkunft[1] : Zeichenkette
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
BIO_TYP_CatRef
BIO_Bedeutung_CatRef
Biotopflaeche_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
BIO_Kartierungsgrundlage_CatRef
MultilingualMText
Mutationgsgrund
+
0..1
Bedeutung
+
1
Kartierungsgrundlage
+
1
1..*
Geo_Obj
+
1
BIO_TYP
+
1
Abbildung 1: Darstellung der Biotopflächen von regionaler und lokaler Bedeutung als UML-Diagramm
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
7
MultilingualMText
BIO_Bedeutung_CatRef
Biotoplinie
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Bio_Typ_KT[0..1] : Zeichenkette
Herkunft[1] : Zeichenkette
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
MultiLine
Biotoplinie_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
BIO_Kartierungsgrundlage_CatRef
BIO_TYP_CatRef
Mutationgsgrund
+
0..1
Bedeutung
+
1
BIO_TYP
+
1
1..*
Kartierungsgrundlage
+
1
Geo_Obj
+
1
Abbildung 2: Darstellung der Biotoplinien von regionaler und lokaler Bedeutung als UML-Diagramm
BIO_Bedeutung_CatRef
Biotoppunkt_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
Geo_Obj[1] : Coord3
MultilingualMText
BIO_Kartierungsgrundlage_CatRef
BIO_TYP_CatRef
Biotoppunkt
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Bio_Typ_KT[0..1] : Zeichenkette
Herkunft[1] : Zeichenkette
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
BIO_TYP
+
1
1..*
Bedeutung
+
1
Mutationgsgrund
+
0..1
Kartierungsgrundlage
+
1
Abbildung 3: Darstellung der Biotoppunkte von regionaler und lokaler Bedeutung als UML-Diagramm
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
8
BIO_TYP_Catalogue
Code[1] : Zeichenkette
BIO_Kartierungsgrundlage_CatRef
BIO_Kartierungsgrundlage_Catalogue
Code[1] : Zeichenkette
BIO_Bedeutung_CatRef
MultilingualText
BIO_Bedeutung_Catalogue
Code[1] : Zeichenkette
BIO_TYP_CatRef
Description
+
1
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
Reference
+
Abbildung 4: Darstellung entsprechenden Codelisten als UML-Diagramm
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
9
4.2.
Objektklassenkatalog
Entitäten Biotopflaeche, Biotoplinie, Biotoppunkt
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
BS
Obligatorisch
A1.2
ObjNummer
Eindeutiger Code zur
Kennzeichnung des
Objekts
TEXT
394
Nummer kantonale Grundlage
Obligatorisch
A1.3
Name
Bezeichnung des
Objekts
TEXT
Park und
Böschung
unterhalb
Pfalz
Falls vorhanden
Fakultativ
A1.4
BIO_TYP
Biotop-Typ
AUFZÄHLUNG
Bio_Typ7
Definition BIO_TYP siehe unten
Obligatorisch
A1.5
Bio_TYP_KT
Kantonale
Bezeichnung des Typs
TEXT
Mauern
Felsen
Fakultativ
A1.6
Herkunft
Ursprünglicher
Kantonaler
Datenbestand
TEXT
Naturinventar
BS
Obligatorisch
A1.7
Kartierungsgrundlage
Grundlage für die
Erfassung des
Perimeters
AUFZÄHLUNG
K3

**Definition Grundlage siehe unten**

Obligatorisch
A1.8
Aufnahmedatum
Datum der Aufnahme
ins kantonale Inventar
DATE
01.02.1991
Fakultativ
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
10
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
B1
Definition Bedeutung siehe unten
Obligatorisch
Entitäten Biotopflaeche_Teilobjekt, Biotoplinie_Teilobjekt, Biotoppunkt_Teilobjekt
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
A.1.13
Geo_Obj
Ausdehnung des
Objekts
POYLGON,
LINE oder
POINT
Obligatorisch
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
11
Entität BIO_TYP
Code
DE
FR
IT
BIO_TYP1
Quellfluren, Gewässer
Sources, suintements, milieux aquatiques
Sorgenti, risorgenze e ambienti
acquatici
BIO_TYP2
Uferbereiche, Verlandungsgesellschaften
Zones riveraines, Associations
d’atterissement
Rive, zone d’interramento
BIO_TYP3
Schluchtwälder, Wälder an Steilhängen und
Trockenwälder
Forêts de ravins, de pente, thermophiles
Boschi di gola,di pendio ripido,
termofili
BIO_TYP4
Saumgesellschaften, Gebüsche und Heiden
Lisières, brousailles et landes
Margini
di
bosco,
radure,
cespuglietti e brughiere
BIO_TYP5
Fels-, Felsgrus- und Karstfluren sowie
Schuttfluren
Rochers, éboulis et lapiez
Rocce, ghiaioni, tavolati e campi
solcati
BIO_TYP6
Ackerbegleitvegetation, Ruderalfluren
Végétation ségétale et rudérale
Vegetazione segetale e ruderale
BIO_TYP7
Anderer Biotoptyp
Autre type de biotope
Altri biotopi
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
12
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
Regional
Lokal
Régional
Local
Regionale
Locale
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
13
4.3.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
14

## 5. Darstellung der Daten der regionalen/lokalen


## Biotope

5.1.
Darstellungsmodell Bund
Für die regionalen und lokalen Biotope besteht noch kein Darstellungsmodell.
5.2.
Darstellungsmodell Kantone
Für die regionalen und lokalen Biotope besteht noch kein Darstellungsmodell.
Darstellungsmodell
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
15

## Anhang

I Datenmodelle im Format INTERLIS 2.3
Biotopflächen
INTERLIS 2.3;
!!@ technicalContact = gis@bafu.admin.ch;
!!@ IDGeoIV = "23.1";
!!@ furtherInformation = http://www.bafu.admin.ch/geodatenmodelle;
!! Repository: models.geo.admin.ch/bafu;
!! Version 1;
MODEL Biotopflaechen_V1 (en)
AT "http://www.bafu.admin.ch/geodatenmodelle"
VERSION "2012-11-06" =
IMPORTS
WithLatestModification_V1,LocalisationCH_V1,CHAdminCodes_V1,AdministrativeUnits_V1,Units,CatalogueObjects_V1,Geometry
CHLV03_V1,Localisation_V1;
TOPIC aCodelisten =
CLASS BIO_Bedeutung_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_Bedeutung_Catalogue;
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
16
CLASS BIO_Kartierungsgrundlage_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_Kartierungsgrundlage_Catalogue;
CLASS BIO_TYP_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*9;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_TYP_Catalogue;
STRUCTURE BIO_Bedeutung_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_Bedeutung_Catalogue;
END BIO_Bedeutung_CatRef;
STRUCTURE BIO_Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_Kartierungsgrundlage_Catalogue;
END BIO_Kartierungsgrundlage_CatRef;
STRUCTURE BIO_TYP_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_TYP_Catalogue;
END BIO_TYP_CatRef;
END aCodelisten;
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
17
TOPIC Biotopflaechen =
CLASS Biotopflaeche =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT;
Name : TEXT;
BIO_TYP : MANDATORY Biotopflaechen_V1.aCodelisten.BIO_TYP_CatRef;
Bio_Typ_KT : TEXT;
Herkunft : MANDATORY TEXT;
Kartierungsgrundlage : MANDATORY Biotopflaechen_V1.aCodelisten.BIO_Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY Biotopflaechen_V1.aCodelisten.BIO_Bedeutung_CatRef;
END Biotopflaeche;
CLASS Biotopflaeche_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT;
Geo_Obj : MANDATORY GeometryCHLV03_V1.MultiSurface;
END Biotopflaeche_Teilobjekt;
ASSOCIATION TeilobjektBiotopflaeche =
Biotop_Teilobjekt -- {1..*} Biotopflaeche_Teilobjekt;
Biotop -<#> {1} Biotopflaeche;
END TeilobjektBiotopflaeche;
END Biotopflaechen;
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
18
END Biotopflaechen_V1.
Biotoplinien
INTERLIS 2.3;
!!@ technicalContact = gis@bafu.admin.ch;
!!@ IDGeoIV = "23.2";
!!@ furtherInformation = http://www.bafu.admin.ch/geodatenmodelle;
!! Repository: models.geo.admin.ch/bafu;
!! Version 1;
MODEL Biotoplinien_V1 (en)
AT "http://www.bafu.admin.ch/geodatenmodelle"
VERSION "2012-11-06" =
IMPORTS
Localisation_V1,Units,LocalisationCH_V1,WithLatestModification_V1,CHAdminCodes_V1,CatalogueObjects_V1,Administrative
Units_V1,GeometryCHLV03_V1;
TOPIC aCodelisten =
CLASS BIO_Bedeutung_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_Bedeutung_Catalogue;
CLASS BIO_Kartierungsgrundlage_Catalogue
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
19
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_Kartierungsgrundlage_Catalogue;
CLASS BIO_TYP_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*9;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_TYP_Catalogue;
STRUCTURE BIO_Bedeutung_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_Bedeutung_Catalogue;
END BIO_Bedeutung_CatRef;
STRUCTURE BIO_Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_Kartierungsgrundlage_Catalogue;
END BIO_Kartierungsgrundlage_CatRef;
STRUCTURE BIO_TYP_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_TYP_Catalogue;
END BIO_TYP_CatRef;
END aCodelisten;
TOPIC Biotoplinien =
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
20
CLASS Biotoplinie =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT;
Name : TEXT;
BIO_TYP : MANDATORY Biotoplinien_V1.aCodelisten.BIO_TYP_CatRef;
Bio_Typ_KT : TEXT;
Herkunft : MANDATORY TEXT;
Kartierungsgrundlage : MANDATORY Biotoplinien_V1.aCodelisten.BIO_Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY Biotoplinien_V1.aCodelisten.BIO_Bedeutung_CatRef;
END Biotoplinie;
CLASS Biotoplinie_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT;
Geo_Obj : MANDATORY GeometryCHLV03_V1.MultiLine;
END Biotoplinie_Teilobjekt;
ASSOCIATION TeilobjektBiotopflaeche =
Biotop_Teilobjekt -- {1..*} Biotoplinie_Teilobjekt;
Biotop -<#> {1} Biotoplinie;
END TeilobjektBiotopflaeche;
END Biotoplinien;
END Biotoplinien_V1.
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
21
Biotoppunkte
INTERLIS 2.3;
!!@ technicalContact = gis@bafu.admin.ch;
!!@ IDGeoIV = "23.3";
!!@ furtherInformation = http://www.bafu.admin.ch/geodatenmodelle;
!! Repository: models.geo.admin.ch/bafu;
!! Version 1;
MODEL Biotoppunkte_V1 (en)
AT "http://www.bafu.admin.ch/geodatenmodelle"
VERSION "2012-11-06" =
IMPORTS
GeometryCHLV03_V1,Localisation_V1,Units,LocalisationCH_V1,CatalogueObjects_V1,AdministrativeUnits_V1,CHAdminCodes_V1
,WithLatestModification_V1;
TOPIC aCodelisten =
CLASS BIO_Bedeutung_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_Bedeutung_Catalogue;
CLASS BIO_Kartierungsgrundlage_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
22
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_Kartierungsgrundlage_Catalogue;
CLASS BIO_TYP_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*9;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END BIO_TYP_Catalogue;
STRUCTURE BIO_Bedeutung_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_Bedeutung_Catalogue;
END BIO_Bedeutung_CatRef;
STRUCTURE BIO_Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_Kartierungsgrundlage_Catalogue;
END BIO_Kartierungsgrundlage_CatRef;
STRUCTURE BIO_TYP_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO BIO_TYP_Catalogue;
END BIO_TYP_CatRef;
END aCodelisten;
TOPIC Biotoppunkte =
CLASS Biotoppunkt =
BAFU 2012
Biotope regional/lokal: Umsetzung des Geoinformationsgesetzes
23
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT;
Name : TEXT;
BIO_TYP : MANDATORY Biotoppunkte_V1.aCodelisten.BIO_TYP_CatRef;
Bio_Typ_KT : TEXT;
Herkunft : MANDATORY TEXT;
Kartierungsgrundlage : MANDATORY Biotoppunkte_V1.aCodelisten.BIO_Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationgsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY Biotoppunkte_V1.aCodelisten.BIO_Bedeutung_CatRef;
END Biotoppunkt;
CLASS Biotoppunkt_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT;
Geo_Obj : MANDATORY GeometryCHLV03_V1.Coord3;
END Biotoppunkt_Teilobjekt;
ASSOCIATION TeilobjektBiotopflaeche =
Biotop_Teilobjekt -- {1..*} Biotoppunkt_Teilobjekt;
Biotop -<#> {1} Biotoppunkt;
END TeilobjektBiotopflaeche;
END Biotoppunkte;
END Biotoppunkte_V1.