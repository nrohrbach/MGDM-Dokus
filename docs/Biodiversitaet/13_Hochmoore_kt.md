BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes

# Technische Anleitungen


# Geobasisdaten des


# Umweltrechts


# Kantonales Inventar der Hoch- und


# Übergangsmoore von nationaler, regionaler


# und lokaler Bedeutung


# Identifikator 27.1


### Bundesamt für Umwelt BAFU /AÖL

BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Hochmoore
Kant.
Inventar
(GeoIV
p.
21);
Identifikator 27.1

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
BAFU: Christian Schlatter
Ab 2010:
Kurt Spälti (IKGeo)
2011
Peter Staub (GKG/KOGIS)

**Leiter der FIG**

Jürg Schenker, BAFU AÖL

**Datum**

06.11.2012

**Version**

1.0
BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu Hochmooren .......... 3
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
Hochmoore .............................................................................................. 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung ........................................................................... 6
4.2.
Objektklassenkatalog .............................................................................. 8
4.3.
Beschreibung mit INTERLIS 2.3 ...........................................................13

### 5.


### Darstellung der Daten der Hochmoore ............................... 14

5.1.
Darstellungsmodell Bund ......................................................................14

### Anhang

I
Datenmodell im Format INTERLIS 2.3
BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Die Hochmoore entstanden in den letzten 5-10‘000 Jahren auf nassen Böden und
entwickelten eine dicke Torfschicht aus Torfmoosen. Drainagen, Torfabbau und
Umnutzung in Landwirtschaftsfläche haben in den letzten 200 Jahren die
Hochmoore auf rund 5- 10% des ursprünglichen Bestandes dezimiert.
Hochmoore sind äusserst empfindliche Ökosysteme. So sind sie gefährdet durch:
•
Nährstoffeinträge erfolgen indirekt durch Düngerstoffe aus der Luft oder
direkt aus dem angrenzenden Landwirtschaftsland. Dies führt rasch zur
Zerstörung der Hochmoorvegetation und des Torfbodens.
•
Viehtritt oder menschliche Einflüsse wie zum Beispiel Loipen führen zu
mechanischen Schädigungen mit der Folge, dass der Boden erodiert.
• Drainagen führen zur Austrocknung des Torfs und damit zu dessen
Mineralisierung (Zersetzung des organischen Materials unter Freiwerden
von CO2). Die typischen Hochmoorpflanzen verschwinden und Gehölze
kommen auf.
Um ein Moor, dessen Wasserhaushalt durch frühere Eingriffe gestört ist, wieder
herzustellen, braucht es eine Regeneration. Die Regeneration stoppt den Abbau
des Moores und ermöglicht wieder dessen Wachstum. Langfristig sollen sie
nämlich wieder der Natur überlassen werden können. In den meisten Fällen ist
dies ein sehr langandauernder Prozess.
Die Ziele der Regeneration sind:
•
Wiederherstellung der ökologischen, besonders der hydrologischen
Bedingungen, welche für das Hochmoor existentiell sind.
•
Wiederherstellung der typischen Pflanzen- und Tierwelt durch gezielte
Schaffung von Habitaten oder die Verbesserung ihrer Struktur.
•
Wiederherstellung der funktionellen Aspekte des Ökosystems, welche für
das Wachstum des Hochmoors verantwortlich sind.
Übergangsmoore
nehmen
eine
Zwischenstellung
zwischen
Hoch-
und
Flachmooren ein. Sie werden sowohl direkt vom Regenwasser wie auch von
Mineralbodenwasser beeinflusst. Standörtlich sind sie deshalb eher den
Flachmooren zuzurechnen. Ihre Vegetation, ihre naturkundliche Bedeutung wie
auch ihre Empfindlichkeit sind aber jenen der Hochmoore ähnlich, weshalb sie
unter dem Begriff Hochmoor aufgenommen wurden.
Seit dem 1. Juli 2008 ist das Bundesgesetz über Geoinformation (GeoIG) in Kraft.
Es hat zum Ziel, auf nationaler Ebene verbindliche bundesrechtliche Standards für
die Erfassung, Modellierung und den Austausch von Geodaten 1 des Bundes,
insbesondere von Geobasisdaten des Bundesrechts, festzulegen. Weiter regelt es
die Finanzierung, das Urheberrecht sowie den Datenschutz. Das Gesetz bildet
auch für das Datenmanagement der Kantone und Gemeinden neue, gesicherte
rechtliche Grundlagen. So wird sich der Zugang zu den mit grossem Aufwand
erhobenen und verwalteten Daten für Behörden, Wirtschaft und Bevölkerung
verbessern. Es wird eine Mehrfachnutzung der gleichen Daten in den
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
2
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
expliziten Raumbezugs ist das kantonale Inventar der Hoch- und Übergangsmoore
in diesen Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikator 27).
Art. 9 GeoIV definiert die Aufgaben der zuständigen Fachstelle des Bundes. Im
Anh. 1 der GeoIV wird für den Geobasisdatensatz 27 das BAFU als die zuständige
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
GeoIV
NHG
Rechtlicher Stellenwert
BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu Hochmooren
Hochmoore gehören zu den empfindlichsten Lebensräumen in der Schweiz und
sind stark im Rückgang begriffen. Heute existieren noch zwischen 5 und 10% des
ursprünglichen Bestandes. Das wissenschaftliche Hochmoorinventar wurde im
Auftrag der Pro Natura Helvetica in den Jahren 1978 bis 1984 von der Abteilung
Landschaft der WSL (Eidg. Forschungsanstalt für Wald, Schnee und Landschaft)
erhoben. Weitere Objekte wurden von den Kantonen im Rahmen eigener
Kartierungen erfasst.
2.2.
Umsetzung
Mit der Hochmoor-Verordnung (SR451.32) werden die noch verbliebenen
Hochmoore unter Schutz gestellt. Diese verpflichtet die Kantone den genauen
Grenzverlauf
festzulegen
und
ökologisch
ausreichende
Pufferzonen
auszuscheiden und insbesondere das Hochmoorumfeld und die angrenzenden
Flachmoore auszuscheiden. Die Objekte müssen ungeschmälert erhalten bleiben.
Weiter sorgen die Kantone für Schutz und Unterhalt der Biotope von regionaler
und lokaler Bedeutung, die Bestimmung der Bedeutung ist in der Kompetenz der
Kantone. Die Kantonalen Inventare umfassen die Objekte von nationaler
Bedeutung, für die der Kanton den genauen Grenzverlauf festgelegt hat (SR451.32
Art. 3 Abs.1) sowie die Objekte von regionaler und lokaler Bedeutung.
Der Datensatz ist Grundlage für die Öffentlichkeitsarbeit (international und
national) im Bereich Biodiversität (Berichte, Statistiken, Artikel in der Fachpresse,
Auskünfte auf Anfragen, usw.).
2.3.
Welche Objekte werden wie erfasst?
Die nationalen Hochmoore wurden im Massstab 1:25‘000 kartiert und allein
aufgrund ihres Pflanzenbestandes ins Bundesinventar aufgenommen. Für die
Umsetzung der Hochmoorverordnung wurden von den Kantonen für viele dieser
Objekte
Detailkartierungen
auf
Basis
unterschiedlicher
kartographischer
Grundlagen durchgeführt.  Die Perimeter der Detailkartierungen weichen
unterschiedlich stark vom Bundesperimeter ab. Diese werden ergänzt durch
Kartierungen von Objekten von regionaler und lokaler Bedeutung in ebenfalls
unterschiedlichen Massstäben. Da es sich beim kantonalen Inventar um
Vegetationskartierungen von Biotopen und nicht um Schutzperimeter handelt,
enthält es keine Pufferzonen.
2.4.
Welche Informationen werden wie veröffentlicht?
Die Geodaten werden zukünftig in der NGDI zur Verfügung gestellt. Das Inventar
ist nicht Bestandteil des ÖREB-Katasters.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Hochmoorschutz
Langfristig geschützte
Biotope
Veröffentlichung der Daten
BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
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
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Hochmoore
Hochmoore wurden aufgrund ihre Pflanzenbestandes erfasst und im Massstab
1:25‘000 kartiert. Objekte wurden ins Bundesinventar aufgenommen, wenn
Torfmoose, eine von vier klassischen Hochmoorzeigerarten oder 3 von weiteren 17
Hochmoorzeigerarten vorkommen und die zusammenhängende Hochmoorfläche
mindestens 625 m 2 umfasst. Die Kartierung richtet sich nach der dominanten
Vegetation,
welche
durch
20
Kategorien
festgehalten
wird.
Bei
der
Georeferenzierung wurden diese zu 26 Kategorien erweitert, damit primäre und
sekundäre
Hochmoore
unterschieden
werden
konnten.
Die
kantonalen
Kartierungen wurden auf Basis unterschiedlicher Grundlagen und oft ohne
Erfassung dieser Kategorien erstellt. Fläche und Lage dieser Objekte sind in den
Feldkartierungen des Bundesinventars und den kantonalen Kartierungen
festgehalten. Die Perimeter wurden auf der Basis dieser Grundlagen digitalisiert.
BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
6

## 4. Modell-Struktur: konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die Abbildung 1 zeigt das UML-Diagramm des kantonalen Inventar des Hoch- und
Übergangsmoore von nationaler, regionaler und lokaler Bedeutung.
kt_Hochmoor
Kanton[1] : CHCantonCode
ObjNummer[1] : Zeichenkette
Name[0..1] : Zeichenkette
Obj_GISFlaeche[1] : Numerisch
Herkunft[1] : Zeichenkette
Aufnahmedatum[0..1] : XMLDate
Mutationsdatum[0..1] : XMLDate
MultilingualMText
HM_KE_CatRef
HM_TYP_CatRef
HM_Kartierungsgrundlage_CatRef
kt_Hochmoor_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
HM_TO[0..1] : Numerisch
kt_Hochmoor_Geometrie
HM_Bedeutung_CatRef
MultiSurface
Geo_Obj
+
1
Kartierungsgrundlage
+
1
Bedeutung
+
1
Mutationsgrund
+
0..1
HM_TYP
+
0..1
HM_KE
+
0..1
1
1..*
1
1..*
Abbildung 1: Darstellung des kantonalen Inventar der Hoch- und Übergangsmoore von nationaler, regionaler und lokaler Bedeutung als
UML-Diagramm
BAFU 2012
Hochmoore Kant Inventar: Umsetzung des Geoinformationsgesetzes
7
HM_Kartierungsgrundlage_Catalogue
Code[1] : Zeichenkette
MultilingualText
HM_KE_CatRef
HM_Kartierungsgrundlage_CatRef
HM_Bedeutung_Catalogue
Code[1] : Zeichenkette
HM_KE_Catalogue
Code[1] : Zeichenkette
HM_Typ_Catalogue
Code[1] : Zeichenkette
HM_Bedeutung_CatRef
HM_TYP_CatRef
Description
+
1
Description
+
1
Reference
+
Description
+
1
Reference
+
Reference
+
Reference
+
Description
+
1
Abbildung 2: Darstellung entsprechenden Codelisten als UML-Diagramm
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
8
4.2.
Objektklassenkatalog
Entität kt_Hochmoor
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
347
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
Objekts in ha
DOUBLE
0.76 ha
Obligatorisch
A1.5
Herkunft
Ursprünglicher
Kantonaler
Datenbestand
TEXT
Vegetation der
Hochmoore des
Kantons Bern
Hinweis aus welchem Inventar oder welcher
Kartierung diese Daten stammen
Obligatorisch
A1.6
Kartierungsgrundlage
Grundlage für die
Erfassung des
Perimeters
AUFZÄHLUNG
K2
Definition Grundlage siehe unten
Obligatorisch
A1.7
Aufnahmedatum
Datum der Aufnahme
ins kantonale Inventar
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
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
9
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
B2
Definition Bedeutung siehe unten
Obligatorisch
Entität kt_Hochmoor_Teilobjekt
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
HM_TO
Teilobjektnummer
LONG
INTEGER
2
Falls vorhanden
Fakultativ
Entität kt_Hochmoor_Geometrie
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.13
HM_TYP
Hochmoortyp
AUFZÄHLUNG
HM_TYP4
Definition HM_TYP verwenden falls erhoben
oder weglassen
Fakultativ
A1.14
HM_KE
Kartiereinheiten
AUFZÄHLUNG
HM_KE10
Definition HM_KE verwenden falls erhoben
oder weglassen
Fakultativ
A1.15
Geo_Obj
Ausdehnung des
Objekts
POLYGON
Obligatorisch
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
10
Entität HM_TYP
Code
DE
FR
IT
HM_TYP1
HM_TYP2
HM_TYP3
HM_TYP4
HM_TYP5
Primäre Hochmoorfläche
Sekundäre Hochmoorfläche
Hochmoorumfeld
Offene Wasserfläche
Vegetationslose Torffelder
Tourbières primaires
Tourbières secondaires
Zone de contact
Plan d’eau
Tourbes nues exploitées
Torbiere primarie
Torbiere secondarie
Area adiacente
Superficie d’aqua
Torba scoperchiata
Entität HM_KE
Code
DE
FR
IT
HM_KE1
HM_KE2
HM_KE3
HM_KE4
HM_KE5
HM_KE6
HM_KE7
HM_KE8
HM_KE9
HM_KE10
HM_KE11
Bultgesellschaften
Schlenkengesellschaften
Bergföhrenhochmoor
Rüllengesellschaften
Birken- und Fichtenmoore
Hochmoormischvegetation
Wald
Waldweide
Weide
Gebüsch,Aufforstung
Niedermoor,Verlandung
Végétation des buttes
Végétation de gouilles
Pinède de tourbière
Végétation de combe d’écoulement
Boulaie et pessière de tourbière
Végétation mixte de tourbière
Forêt
Pâturages boisés
Pâturages
Buissons, reboisements
Bas-marais, atterrissement
Vegetazione dei cumuli torbosi
Vegetazione delle depressioni
Pineta di torbiera
Veg delle vallecoli di drenaggio nat.
Betulleti, peccete di torbiera
Vegetazione mista di torbiera
Bosco
Bosco pascolato
Pascolo
Cespugli, rimboschimento
Palude bassa, interramento
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
11
HM_KE12
HM_KE13
HM_KE14
HM_KE15
HM_KE16
HM_KE17
HM_KE18
HM_KE19
HM_KE20
HM_KE21
HM_KE22
HM_KE23
HM_KE24
HM_KE25
HM_KE26
Wasserflächen
Torffelder
Dauerwiese,Matte
Acker,Kunstwiese
Siedlung,Garten
Dolinen
Mischvegetation
Hochstaudenfluren
Deponie,Aufschüttung
Bultgesellschaften
Schlenkengesellschaften
Bergföhrenhochmoor
Rüllengesellschaften
Birken- und Fichtenmoore
Hochmoormischvegetation
Plans d’eau (bleu)
Surfaces raclées (brun)
Prairies, herbages
Cultures, prairies artificielles
Bâtiments, jardins
Emposieux
Végétation mixte
Mégaphorbiaies
Remblais, décharge
Végétation des buttes
Végétation de gouilles
Pinède de tourbière
Végétation de combe d’écoulement
Boulaie et pessière de tourbière
Végétation mixte de tourbière
Acque libere (blu)
Campi di torba nuda (bruno)
Prati permanenti
Campi arati, prati artificiali
Insediamento,giardini
Doline
Vegetazione mista
Megaforbie (erbe alte)
Depositi, ripiene
Vegetazione dei cumuli torbosi
Vegetazione delle depressioni
Pineta di torbiera
Veg delle vallecoli di drenaggio nat.
Betulleti, peccete di torbiera
Vegetazione mista di torbiera
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
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
Carte nationale 1:25’000
Autre carte nationale
Base cantonale de planification
Photographie aerienne, orthophoto
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
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
13
4.3.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
14

## 5. Darstellung der Daten der Hochmoore

5.1.
Darstellungsmodell Bund
Für die regionalen Hochmoore besteht noch kein Darstellungsmodell
5.2
Darstellungsmodell Kantone
Für die kantonalen Objekte besteht noch kein Darstellungsmodell
Darstellungsmodell
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
15

## Anhang

I Datenmodell im Format INTERLIS 2.3
INTERLIS 2.3;
!!@ technicalContact = gis@bafu.admin.ch;
!!@ IDGeoIV = "27.1";
!!@ furtherInformation = http://www.bafu.admin.ch/geodatenmodelle;
!! Repository: models.geo.admin.ch/bafu;
!! Version 1;
MODEL kt_Hochmoore_V1 (en)
AT "http://www.bafu.admin.ch/geodatenmodelle"
VERSION "2012-11-06" =
IMPORTS
WithLatestModification_V1,CHAdminCodes_V1,LocalisationCH_V1,Units,Localisation_V1,CatalogueObjects_V1,GeometryCHLV03
_V1;
TOPIC Codelisten =
CLASS HM_Bedeutung_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END HM_Bedeutung_Catalogue;
CLASS HM_Kartierungsgrundlage_Catalogue
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
16
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*3;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END HM_Kartierungsgrundlage_Catalogue;
CLASS HM_KE_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*7;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END HM_KE_Catalogue;
CLASS HM_Typ_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*8;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END HM_Typ_Catalogue;
STRUCTURE HM_Bedeutung_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO HM_Bedeutung_Catalogue;
END HM_Bedeutung_CatRef;
STRUCTURE HM_Kartierungsgrundlage_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO HM_Kartierungsgrundlage_Catalogue;
END HM_Kartierungsgrundlage_CatRef;
STRUCTURE HM_KE_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
17
Reference (EXTENDED) : REFERENCE TO HM_KE_Catalogue;
END HM_KE_CatRef;
STRUCTURE HM_TYP_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO HM_Typ_Catalogue;
END HM_TYP_CatRef;
END Codelisten;
TOPIC kt_Hochmoore =
CLASS kt_Hochmoor =
Kanton : MANDATORY CHAdminCodes_V1.CHCantonCode;
ObjNummer : MANDATORY TEXT;
Name : TEXT;
Obj_GISFlaeche : MANDATORY 1.0 .. 999999.0 [Units.m2];
Herkunft : MANDATORY TEXT;
Kartierungsgrundlage : MANDATORY kt_Hochmoore_V1.Codelisten.HM_Kartierungsgrundlage_CatRef;
Aufnahmedatum : INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : LocalisationCH_V1.MultilingualMText;
Bedeutung : MANDATORY kt_Hochmoore_V1.Codelisten.HM_Bedeutung_CatRef;
END kt_Hochmoor;
CLASS kt_Hochmoor_Geometrie =
HM_TYP : kt_Hochmoore_V1.Codelisten.HM_TYP_CatRef;
HM_KE : kt_Hochmoore_V1.Codelisten.HM_KE_CatRef;
Geo_Obj : MANDATORY GeometryCHLV03_V1.MultiSurface;
BAFU 2012
Hochmoore Kant Inventar : Umsetzung des Geoinformationsgesetzes
18
END kt_Hochmoor_Geometrie;
CLASS kt_Hochmoor_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT;
HM_TO : 0 .. 999999;
END kt_Hochmoor_Teilobjekt;
ASSOCIATION GeometrieTeilobjekt =
kt_Hochmoor_Geometrie -- {1..*} kt_Hochmoor_Geometrie;
kt_Hochmoor_Teilobjekt -<#> {1} kt_Hochmoor_Teilobjekt;
END GeometrieTeilobjekt;
ASSOCIATION TeilobjektHochmoor =
kt_Hochmoor_Teilobjekt -- {1..*} kt_Hochmoor_Teilobjekt;
kt_Hochmoor -<#> {1} kt_Hochmoor;
END TeilobjektHochmoor;
END kt_Hochmoore;
END kt_Hochmoore_V1.