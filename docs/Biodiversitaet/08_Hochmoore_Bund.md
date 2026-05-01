
# Technische Anleitungen


# Geobasisdaten des


# Umweltrechts


# Bundesinventar der Hoch- und


# Übergangsmoore von nationaler Bedeutung


# Identifikator 20.1


# Version 1.1

Bern, 22. August 2017

### Bundesamt für Umwelt BAFU /AÖL

BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Hochmoore (GeoIV p. 20); Identifikator 20.1

**FIG**

Mitglieder AG gitKBNL
Catherine Guex, Frederic Aubert (VD) 2010
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
Peter Staubli, BAFU AÖL

**Leiter der FIG**

Helmut Recher, BAFU AÖL

**Datum**

22.08.2017

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
Technische Anpassungen der Modellstruktur: UML,
Objektklassen, INTERLIS
22.08.2017
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes

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
Hochmoore .............................................................................................. 5
3.2.
Datenbereitstellung und Qualitätssicherung ........................................... 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung ........................................................................... 6
4.2.
Objektklassenkatalog .............................................................................. 7
4.3.
Beschreibung mit INTERLIS 2.3 ...........................................................13

### 5.


### Darstellung der Daten der Hochmoore ............................... 14

5.1.
Darstellungsmodell Bund ......................................................................14

### Anhang

I
Datenmodell im Format INTERLIS 2.3
II
Darstellungsmodell
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
1

## 1. Einleitung

Die Hochmoore entstanden in den letzten 5-10‘000 Jahren auf nassen Böden und
entwickelten eine dicke Torfschicht aus Torfmoosen. Drainagen, Torfabbau und
Umnutzung in Landwirtschaftsfläche haben in den letzten 200 Jahren die
Hochmoore auf rund 5- 10% des ursprünglichen Bestandes dezimiert.
Hochmoore sind äusserst empfindliche Ökosysteme. So sind sie gefährdet durch:

Nährstoffeinträge erfolgen indirekt durch Düngerstoffe aus der Luft oder
direkt aus dem angrenzenden Landwirtschaftsland. Dies führt rasch zur
Zerstörung der Hochmoorvegetation und des Torfbodens.

Viehtritt oder menschliche Einflüsse wie zum Beispiel Loipen führen zu
mechanischen Schädigungen mit der Folge, dass der Boden erodiert.

Drainagen führen zur Austrocknung des Torfs und damit zu dessen
Mineralisierung (Zersetzung des organischen Materials unter Freiwerden
von CO 2 ). Die typischen Hochmoorpflanzen verschwinden und Gehölze
kommen auf.
Um ein Moor, dessen Wasserhaushalt durch frühere Eingriffe gestört ist, wieder
herzustellen, braucht es eine Regeneration. Die Regeneration stoppt den Abbau
des Moores und ermöglicht wieder dessen Wachstum. Langfristig sollen sie
nämlich wieder der Natur überlassen werden können. In den meisten Fällen ist
dies ein sehr langandauernder Prozess.
Die Ziele der Regeneration sind:

Wiederherstellung der ökologischen, besonders der hydrologischen
Bedingungen, welche für das Hochmoor existentiell sind.

Wiederherstellung der typischen Pflanzen- und Tierwelt durch gezielte
Schaffung von Habitaten oder die Verbesserung ihrer Struktur.

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
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
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
expliziten
Raumbezugs
ist
das
Hochmoor-Inventar
in
diesen
Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikator 20). Art. 9
GeoIV definiert die Aufgaben der zuständigen Fachstelle des Bundes. Im Anh. 1
der GeoIV wird für den Geobasisdatensatz 20 das BAFU als die zuständige
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
Darstellungsmodell/e (Art. 11 GeoIV) ist hingegen fakultativ. Das BAFU wird als
zuständige Stelle für die Daten bezeichnet. Diese Geobasisdaten sind gemäss
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
GeoIV
NHG
Rechtlicher Stellenwert
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
3

## 2. Ziel und Zweck

2.1.
Ausgangslage der Erhebung von Informationen zu Hochmooren
Hochmoore gehören zu den empfindlichsten Lebensräumen in der Schweiz und
sind stark im Rückgang begriffen. Heute existieren noch zwischen 5 und 10% des
ursprünglichen Bestandes. Das wissenschaftliche Hochmoorinventar wurde im
Auftrag der Pro Natura Helvetica in den Jahren 1978 bis 1984 von der Abteilung
Landschaft der WSL (Eidg. Forschungsanstalt für Wald, Schnee und Landschaft)
erhoben.
2.2.
Umsetzung
Mit der Hochmoor-Verordnung werden die noch verbliebenen Hochmoore unter
Schutz gestellt. Gemäss Art. 18a des Bundesgesetzes vom 1. Juli 1966 über den
Natur-und Heimatschutz (NHG) - in Kraft seit dem 1. Februar 1988 -bezeichnet der
Bundesrat die Biotope von nationaler Bedeutung, bestimmt ihre Lage und legt die
Schutzziele fest. Dies geschieht jedoch erst nach Anhören der Kantone. A ls erstes
Bundesinventar gemäss Art. 18a NHG setzte der Bundesrat 1991 das
Bundesinventar der Hoch- und Übergangsmoore mit 514 Objekten in Kraft,
welches 2003 mit einer 2.Serie ergänzt sowie 2007 und 2017 revidiert wurde.
Abbau und Zerstörung der Hochmoore kann für immer sein und deshalb stehen sie
unter besonderem Schutz: Intakte Hochmoore müssen vor jeglichen schädigenden
Einwirkungen verschont werden. In degradierten Hochmooren muss der
Wasserhaushalt wieder so hergestellt werden (Regeneration), dass sie in Zukunft
wieder völlig der Natur überlassen werden können.
Die Schutzziele sind in der Hochmoorverordnung festgehalten:

Ungeschmälerte Erhaltung in Fläche und Qualität

Erhaltung und Förderung der standortheimischen Pflanzen und Tierwelt

Erhaltung der typischen Geländeform

Aufwerten und Wiederherstellen bereits geschädigter Moorflächen
Intakte Hochmoore benötigen keine Pflegemassnahmen. Da aber viele Hochmoore
von früheren Nutzungen gestört sind, erfordern sie Wiederaufwertungsmass-
nahmen in Form von Regeneration und anderen Pflegemassnahmen. Die
allermeisten Hochmoore sind heute Naturschutzgebiete.
2.3.
Welche Objekte werden erfasst?
Hochmoore wurden allein aufgrund ihres Pflanzenbestandes ins Hochmoorinventar
aufgenommen und kartographisch erfasst. Als Bedingungen dazu galten:
 Es müssen Torfmoose vorkommen.
 Zusätzlich müssen entweder mindestens eine der 4 klassischen
Hochmoorzeigenden Gefässpflanzen oder 3 von 17 weiteren Hochmoor
bewohnenden Arten vorkommen. Die entsprechende Artenliste wurde
einheitlich für die ganze Schweiz festgelegt.
 Die zusammenhängende Hochmoorfläche muss mindestens 625 m2
umfassen.
Die Kartierung richtet sich nach der dominanten Vegetation, welche durch 20
Kategorien festgehalten wird.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den
Hochmoorschutz
Langfristig geschützte Hoch-
und Übergangsmoore
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
4
2.4.
Welche Informationen werden veröffentlicht?
Das Bundesinventar bildet als Anhang 2 Bestandteil der Verordnung über den
Schutz der Hochmoore von nationaler Bedeutung. Im Internet werden die
Objektlisten und Objektblätter als pdf-Formate kantonsweise publiziert. Die
Geodaten werden in der BGDI dargestellt und sind auf der Homepage des BAFU
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
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
5

## 3. Modellbeschreibung

3.1.
Hochmoore
Hochmoore wurden aufgrund ihre Pflanzenbestandes erfasst und im Massstab
1:25‘000 kartiert. Objekte wurden ins Bundesinventar aufgenommen, wenn
Torfmoose, eine von vier klassischen Hochmoorzeigerarten oder 3 von weiteren 17
Hochmoorzeigerarten vorkommen und die zusammenhängende Hochmoorfläche
mindestens 625 m2 umfasst. Die Kartierung richtet sich nach der dominanten
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
sekundäre Hochmoore unterschieden werden konnten. Fläche und Lage dieser
Objekte sind in den Feldkartierungen des Bundesinventars festgehalten. Die
Perimeter wurden auf der Basis dieser Grundlagen digitalisiert.
Abbildung 1: Georeferenzierung des Objekts mittels PK25
3.2.
Datenbereitstellung und Qualitätssicherung
Im Zuge der Bereitstellung der Geodaten werden folgende Regeln erfüllt:
Objekte im Polygondatensatz dürfen sich innerhalb des Datensatzes nicht
überlappen (no self-overlap).
Angaben der Felder „Typ“ und „Einheit“ müssen inhaltlich zusammen passen.
Der Typ (1-2) passt zur Einheit (1-6). Der Typ 3 passt zur Einheit 7-11 und 14-20.
Der Typ 4 passt zur Einheit 12. Der Typ 5 passt zur Einheit 13.
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
6

## 4. Modell-Struktur: konzeptionelles Datenmodell

4.1.
Graphische Darstellung
Die Abbildung 2 zeigt das UML-Diagramm der Bundesinventare der Hoch- und
Übergangsmoore von nationaler Bedeutung.
Hochmoor_Geometrie
HM_KE[1] : HM_KE_CatRef
Typ[1] : Typ_CatRef
Geo_Obj[1] : MultiSurface
Einheit[1] : Numerisch
Hochmoor
ObjNummer[1] : Zeichenkette
Name[1] : Zeichenkette
RefObjBlatt[0..1] : Zeichenkette
DesignatType[0..1] : DesignationType
IUCNCategory[1] : IUCNCategory
Inkraftsetzungsdatum[1] : XMLDate
Mutationsdatum[0..1] : XMLDate
Mutationsgrund[0..1] : Zeichenkette
Hochmoor_Teilobjekt
TelObjNummer[1] : Zeichenkette
HM_TO[1] : Numerisch
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
1..*
HM_KE_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
HM_KE_CatRef
Typ_Catalogue
Code[1] : Zeichenkette
Description[1] : MultilingualText
Typ_CatRef
Reference
+
Reference
+
Abbildung 2: Darstellung der Hoch- und Übergangsmoore von nationaler Bedeutung als UML-Diagramm
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
7
4.2.
Objektklassenkatalog
Entität Hochmoor
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
576
Nummer Bundesinventar
Obligatorisch
A1.2
Name
Bezeichnung des
Objekts
TEXT
Moore am
Schwyberg
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
Fakultativ
A1.5
IUCNCategory
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
wcmc.org/protected_areas/categories/index.
html
Obligatorisch
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
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
Entität Hochmoor_Teilobjekt
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
Text
Bundesinterne Identifikationsnummer des
Teilobjekts. Voreingestellter Wert für Objekte
ohne Teilobjekte = 1
Bedingung: Ein eindeutiger Schlüssel für
jeden Datensatz ist aus den vier Merkmalen
ObjNummer + TeilObjNummer + TYP +
Einheit erstellbar.
Obligatorisch
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
9
Entität Hochmoor_Geometrie
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.10
TYP
Hochmoortyp
AUFZÄHLUNG
4
Obligatorisch
A1.11
Einheit
Kartiereinheiten
AUFZÄHLUNG
10
20 Kartiereinheiten
Obligatorisch
A1.12
HM_KE
Kartiereinheiten
AUFZÄHLUNG
HM_KE10
[Nur interne Verwendung] 26 Kartiereinheiten,
6 Einheiten wurden eingefügt für den
Hochmoor-Typ = 2
Obligatorisch
A1.13
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
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
10
1
2
3
4
5
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
Superficie d’acqua
Torba scoperchiata
Entität Einheit
Code
DE
FR
IT
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
Bultgesellschaften
Schlenkengesellschaften
Bergföhrenhochmoor
Rüllengesellschaften
Birken- und Fichtenmoore
Hochmoormischvegetation
Wald
Waldweide
Weide
Gebüsch_Aufforstung
Niedermoor_Verlandung
Wasserflächen
Torffelder
Dauerwiese_Matte
Acker_Kunstwiese
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
Plans d’eau (bleu)
Surfaces raclées (brun)
Prairies, herbages
Cultures, prairies artificielles
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
Acque libere (blu)
Campi di torba nuda (bruno)
Prati permanenti
Campi arati, prati artificiali
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
11
16
17
18
19
20
Siedlung_Garten
Dolinen
Mischvegetation
Hochstaudenfluren
Deponie_Aufschüttung
Bâtiments, jardins
Emposieux
Végétation mixte
Mégaphorbiaies
Remblais, décharge
Insediamento,giardini
Doline
Vegetazione mista
Megaforbie (erbe alte)
Depositi, ripiene
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
HM_KE12
HM_KE13
HM_KE14
HM_KE15
Bultgesellschaften
Schlenkengesellschaften
Bergföhrenhochmoor
Rüllengesellschaften
Birken- und Fichtenmoore
Hochmoormischvegetation
Wald
Waldweide
Weide
Gebüsch_Aufforstung
Niedermoor_Verlandung
Wasserflächen
Torffelder
Dauerwiese_Matte
Acker_Kunstwiese
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
Plans d’eau (bleu)
Surfaces raclées (brun)
Prairies, herbages
Cultures, prairies artificielles
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
Acque libere (blu)
Campi di torba nuda (bruno)
Prati permanenti
Campi arati, prati artificiali
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
12
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
Siedlung_Garten
Dolinen
Mischvegetation
Hochstaudenfluren
Deponie_Aufschüttung
Bultgesellschaften
Schlenkengesellschaften
Bergföhrenhochmoor
Rüllengesellschaften
Birken- und Fichtenmoore
Hochmoormischvegetation
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
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
13
4.3.
Beschreibung mit INTERLIS 2.3
Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
14

## 5. Darstellung der Daten der Hochmoore

5.1.
Darstellungsmodell Bund
Die Daten der Hochmoore werden vom BAFU für den Vollzug des Arten- und
Biotopschutzes verwendet.. Die Darstellung erfolgt im Rahmen des Erlasses resp.
bei
Revisionen
der
Hochmoorverordnung.
Dabei
gelangt
die
folgende
geographische Darstellungsart zur Anwendung (Abbildung 3).
Abbildung 4: Geographische Lage der Hochmoore
Legende:
Darstellungsmodell Bund
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
15

## Anhang

I Datenmodell im Format INTERLIS 2.3
Bei Abweichungen zw. Modelldokumentation und Model Repository gilt die ILI-Version im Model Repository.
INTERLIS 2.3;
!!@ IDGeoIV=20.1
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL Hochmoore_Codelisten_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-05-09"  =
IMPORTS CatalogueObjects_V1,LocalisationCH_V1;
/* Modell für externe Codelisten, die anschliessend importiert werden in die Modelle *_LV03* und *_LV95" */
TOPIC Codelisten =
CLASS HM_KE_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*7;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
END HM_KE_Catalogue;
CLASS Typ_Catalogue
EXTENDS CatalogueObjects_V1.Catalogues.Item =
Code : MANDATORY TEXT*8;
Description : MANDATORY LocalisationCH_V1.MultilingualText;
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
16
END Typ_Catalogue;
STRUCTURE HM_KE_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) HM_KE_Catalogue;
END HM_KE_CatRef;
STRUCTURE Typ_CatRef
EXTENDS CatalogueObjects_V1.Catalogues.CatalogueReference =
Reference (EXTENDED) : REFERENCE TO (EXTERNAL) Typ_Catalogue;
END Typ_CatRef;
END Codelisten;
END Hochmoore_Codelisten_V1_1.
!!@ IDGeoIV=20.1
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL Hochmoore_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-05-09"  =
IMPORTS GeometryCHLV03_V1,Hochmoore_Codelisten_V1_1;
TOPIC Hochmoore =
DEPENDS ON Hochmoore_Codelisten_V1_1.Codelisten;
DOMAIN
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
17
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
/* Klasse für Hochmoor-Geometrieobjekt */
CLASS Hochmoor_Geometrie =
HM_KE : MANDATORY Hochmoore_Codelisten_V1_1.Codelisten.HM_KE_CatRef;
Typ : MANDATORY Hochmoore_Codelisten_V1_1.Codelisten.Typ_CatRef;
Geo_Obj : MANDATORY GeometryCHLV03_V1.MultiSurface;
Einheit : MANDATORY 0..99;
END Hochmoor_Geometrie;
/* Klasse für Hochmoor-Teilobjekt */
CLASS Hochmoor_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
18
END Hochmoor_Teilobjekt;
/* Klasse für gesamtes Hochmoor-Objekt */
CLASS Hochmoor =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : TEXT*255;
END Hochmoor;
/* Klassenübergreifender Constraint für Eindeutigkeit */
VIEW vHM
JOIN OF Hochmoor_Teilobjekt,Hochmoor,Hochmoor_Geometrie; =
ATTRIBUTE
ALL OF Hochmoor_Teilobjekt;
ALL OF Hochmoor;
ALL OF Hochmoor_Geometrie;
UNIQUE ObjNummer,TeilObjNummer,Einheit;
END vHM;
ASSOCIATION AssociationDef194 =
Hochmoor_Geometrie -- {1..*} Hochmoor_Geometrie;
Hochmoor_Teilobjekt -<#> {1} Hochmoor_Teilobjekt;
END AssociationDef194;
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
19
ASSOCIATION AssociationDef180 =
Hochmoor_Teilobjekt -- {1..*} Hochmoor_Teilobjekt;
Hochmoor -<#> {1} Hochmoor;
END AssociationDef180;
END Hochmoore;
END Hochmoore_LV03_V1_1.
!!@ IDGeoIV=20.1
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
MODEL Hochmoore_LV95_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-05-09"  =
IMPORTS GeometryCHLV95_V1,Units,Hochmoore_Codelisten_V1_1;
TOPIC Hochmoore =
DEPENDS ON Hochmoore_Codelisten_V1_1.Codelisten;
DOMAIN
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
);
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
20
IUCNCategory = (
Strict_Nature_Reserve_Ia,
Wilderness_Area_Ib,
National_Park_II,
Natural_Monument_III,
Habitat_or_Species_Management_Area_IV,
Protected_Landscape_or_Seascape_V,
Managed_Resource_Protected_Area_VI
);
/* Klasse für Hochmoor-Geometrieobjekt */
CLASS Hochmoor_Geometrie =
HM_KE : MANDATORY Hochmoore_Codelisten_V1_1.Codelisten.HM_KE_CatRef;
Typ : MANDATORY Hochmoore_Codelisten_V1_1.Codelisten.Typ_CatRef;
Geo_Obj : MANDATORY GeometryCHLV95_V1.MultiSurface;
Einheit : MANDATORY 0..99;
END Hochmoor_Geometrie;
/* Klasse für Hochmoor-Teilobjekt */
CLASS Hochmoor_Teilobjekt =
TeilObjNummer : MANDATORY TEXT*30;
HM_TO : MANDATORY 0 .. 999999;
END Hochmoor_Teilobjekt;
/* Klasse für gesamtes Hochmoor-Objekt */
CLASS Hochmoor =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
21
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund : TEXT*255;
END Hochmoor;
/* Klassenübergreifender Constraint für Eindeutigkeit */
VIEW vHM
JOIN OF Hochmoor_Teilobjekt,Hochmoor,Hochmoor_Geometrie; =
ATTRIBUTE
ALL OF Hochmoor_Teilobjekt;
ALL OF Hochmoor;
ALL OF Hochmoor_Geometrie;
UNIQUE ObjNummer,TeilObjNummer,Einheit;
END vHM;
ASSOCIATION AssociationDef194 =
Hochmoor_Geometrie -- {1..*} Hochmoor_Geometrie;
Hochmoor_Teilobjekt -<#> {1} Hochmoor_Teilobjekt;
END AssociationDef194;
ASSOCIATION AssociationDef180 =
Hochmoor_Teilobjekt -- {1..*} Hochmoor_Teilobjekt;
Hochmoor -<#> {1} Hochmoor;
END AssociationDef180;
END Hochmoore;
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
22
END Hochmoore_LV95_V1_1.
BAFU 2017
Hoch- und Übergangsmoore: Umsetzung des Geoinformationsgesetzes
23
II Darstellungsmodell Bundesinventar der Hoch- und Übergangsmoore von nationaler
Bedeutung
(Hochmoore)
Layer transparency: 25%
Flächen:
Typ: Simple Fill
1: Mars Red, RGB: 255,0,0
2: Solar Yellow, RGB: 255,255,0
3: Medium Applle, RGB: 85,255,0
4: Apatite Blue, RGB: 115,223,255
5: Raw Umber, RGB: 168,112,0
Outline:
Type: Line
Width: 0.2
Farbname: Black
RGB: 0,0,0