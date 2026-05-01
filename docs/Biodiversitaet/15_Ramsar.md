
# Technische Anleitungen


# Geobasisdaten des


# Umweltrechts


# Übereinkommen über Feuchtgebiete,


# insbesondere als Lebensraum für Wasser-


# und Watvögel, von internationaler Bedeutung


# (Ramsar-Konvention)


# Identifikator 2.1

Bern, 17. April 2018

### Bundesamt für Umwelt BAFU /AÖL


**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**Offiz. Bezeichner**

Ramsar-Konvention (GeoIV p. 19); Identifikator 2.1

**FIG**

-

**Leiter der FIG**

Helmut Recher, BAFU AÖL

**Datum**

17.04.2018

**Version**

Von der BAFU-Direktion verabschiedete Version

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
17.04.2018

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

## Inhaltsverzeichnis


### 1.


### Einleitung ................................................................................ 1


### 2.


### Ziel und Zweck ........................................................................ 3

2.1.
Ausgangslage der Erhebung von Informationen zu Ramsar-Objekten .. 3
2.2.
Umsetzung ............................................................................................. 3
2.3.
Welche Objekte werden erfasst? ........................................................... 3
2.4.
Welche Informationen werden wie veröffentlicht? .................................. 3
2.5.
Aufwand .................................................................................................. 4
2.6.
Begriffe aus dem GeoIG ......................................................................... 4

### 3.


### Modellbeschreibung ............................................................... 5

3.1.
Ramsar- Konvention ............................................................................... 5

### 4.


### Modell-Struktur: konzeptionelles Datenmodell ................... 6

4.1.
Graphische Darstellung .......................................................................... 6
4.2.
Objektklassenkatalog ............................................................................. 7
4.3.
Beschreibung mit INTERLIS 2.3 ............................................................ 9

### 5.


### Darstellung der Daten der Ramsar-Objekte ....................... 10

5.1.
Darstellungsmodell Bund ..................................................................... 10

### Anhang

I
Datenmodell im Format INTERLIS 2.3
II
Darstellungsmodell

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**1**


## 1. Einleitung

Das Ramsar-Übereinkommen hat den Schutz von Feuchtgebieten insbesondere
als Lebensraum für Wasser- und Watvögel zum Ziel. Im Bereich von Seen,
Flussdelten, Auen, Mooren und Wattgebieten ist die Artenvielfalt besonders gross,
und für viele Vögel sind dies unersetzliche Lebensräume. Gleichzeitig gehören
diese Gebiete zu den empfindlichsten und gefährdetsten Biotopen. Bisher haben
die heute 160 Vertragsstaaten der Ramsar-Konvention, die vor 40 Jahren
abgeschlossen wurde, insgesamt 1950 Schutzobjekte in die Liste international
bedeutender Feuchtgebiete eintragen lassen. Die Liste umfasst damit eine Fläche
von über 1 901 360 km2, was etwa 46 mal der Fläche der Schweiz entspricht.
Von den Schweizer Feuchtgebieten wurden bisher 11 in die Ramsar-Liste
eingetragen: Die Bucht Fanel-Chablais (BE, VD, NE), das Delta Bolle di Magadino
(TI), der Klingnauer Stausee (AG), das Südufer des Neuenburgersees (FR, VD),
Les Grangettes (VD), die Bucht von Genf und der Rhonelauf unterhalb von Genf
(GE), das Kaltbrunner Riet (SG), der Stausee Niederried (BE), das Moorgebiet
Laubersmad-Salwidili (LU) und die alpinen Auen Rhonegletschervorfeld (VS) und
Vadret da Roseg (GR). Für die Umsetzung der Schutzmassnahmen sind die
Kantone verantwortlich. Für die meisten Schutzobjekte wurden entsprechende
Vorkehrungen getroffen.
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
expliziten
Raumbezugs
ist
die
Ramsar-Konvention
in
diesen
Ausführungsbestimmungen aufgeführt (Anh. 1 GeoIV, Identifikator 2). Art. 9 GeoIV
definiert die Aufgaben der zuständigen Fachstelle des Bundes. Im Anh. 1 der
GeoIV wird für den Geobasisdatensatz 2 das BAFU als die zuständige Fachstelle
des Bundes bezeichnet. Diese muss somit ein minimales Geodatenmodell
vorgeben,
das
Definieren
und
Beschreiben
eines
oder
mehrerer
1 Begriffe gemäss GeoIG, siehe Kap. 2.2
Grundlagen
GeoIG
GeoIV

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**2**

Darstellungsmodell/e (Art. 11 GeoIV) ist hingegen fakultativ. Das BAFU wird als
zuständige Stelle für die Daten bezeichnet. Diese Geobasisdaten sind gemäss
GeoIV der Zugangsberechtigungsstufe A zugeteilt, d.h. dass sie öffentlich
zugänglich sind und ein Download-Dienst vorgesehen ist.
Erstes weltweites Naturschutzabkommen, abgeschlossen in der iranischen Stadt
Ramsar. Völkerrechtlich verbindlicher Vertrag zum Schutz von Feuchtgebieten als
Lebensraum für Wasser- und Watvögel und als Rastplatz für Zugvögel. Als
internationales Abkommen ist die Ramsar-Konvention nicht direkt rechtswirksam.
Die Massnahmen, zu denen sich die Schweiz bei der Ratifikation 1976 verpflichtet
hat, müssen auf Bundes- und/oder Kantonsebene im Rahmen von Gesetzen und
Verordnungen umgesetzt werden.
Minimale Geodatenmodelle beschreiben den gemeinsamen Kern eines Satzes von
Geodaten (Ebene Bund), auf welchem erweiterte Datenmodelle aufbauen können
(Ebene Kanton oder Gemeinde), um die unterschiedlichen Bedürfnisse im Vollzug
abbilden zu können. Das nachfolgend vorgegebene minimale Geodatenmodell
verpflichtet das Bundesamt die Daten in dieser Form zu pflegen und mit den im
Datenmodell definierten Relationen zur Verfügung zu stellen.
Ramsar-Konvention
Rechtlicher Stellenwert

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**3**


## 2. Ziel und Zweck


**2.1.**


**Ausgangslage der Erhebung von Informationen zu Ramsar-Objekten**

Zum Schutz der Feuchtgebiete, insbesondere als Lebensraum für Wasser- und
Watvögel, wurde 1971 in der iranischen Stadt Ramsar eine Konvention von
internationaler Bedeutung unterzeichnet. Die Schweiz ratifizierte das meist als
Ramsar-Konvention bezeichnete Übereinkommen 1976 und verpflichtet sich damit,
die nachhaltige Nutzung von Feuchtgebieten sicherzustellen und diesen Gebieten
speziellen Schutz zu gewähren. Bislang sind in 4 Etappen 11 Gebiete bei der
Ramsar-Konvention angemeldet worden, wobei Objekt 6 im Jahre 2000 und Objekt
5 im Jahre 2011 erweitert wurden. Die Gebiete umfassen Uferabschnitte von Seen,
Flussdeltas, gestaute Flussabschnitte, ein Riedgebiet und im alpinen Bereich
Gletschervorfelder und ein Moorgebiet.

**2.2.**


**Umsetzung**

Mit
der
Unterzeichnung
der
Ramsar-Konvention
verpflichten
sich
die
Vertragsparteien dazu, die Feuchtgebiete zu erhalten, höchstens nachhaltig zu
nutzen und jene von internationaler Bedeutung  spezifisch zu schützen. Die
Feuchtgebiete sollen für die Liste nach ihrer ökologischen, botanischen,
zoologischen, limnologischen und hydrologischen Bedeutung ausgewählt werden.
In erster Linie sollen Feuchtgebiete, die während der Jahreszeiten im Hinblick auf
Wat- und Wasservögel von internationaler Bedeutung sind, in die Liste
aufgenommen werden.

**2.3.**


**Welche Objekte werden erfasst?**

Bei der Abgrenzung der Ramsar-Objekte wurden mit Ausnahme der Objekte Fanel
und Laubersmad bestehende Perimeter von Bundesinventaren (BLN, Wasser- u.
Zugvogelreservate, Auen) oder kantonalen Schutzgebieten übernommen bzw. in
Absprache mit den Kantonen bei drei Objekten neu festgelegt. Die Objekte Rade
de Genève, Bolle di Magadino, Klingnau und Niederried entsprechen bezüglich
Perimeter den Objekten des BLN oder WZVV-Inventars, Rhonegletschervorfeld
und Vadret da Roseg sind  Bestandteil des Aueninventars. Beim Rive sud du lac
de Neuchâtel entspricht der Perimeter dem interkantonalen Richtplan der Kantone
VD und FR von 1982. Das  Gebiet Grangettes umfasst seit 2011 einen Perimeter
welcher sowohl WZVV wie auch die Moorlandschaft enthält. Der Perimeter des
Kaltbrunner Riet wurde 2004 an den kantonalen Schutzperimeter angepasst.

**2.4.**


**Welche Informationen werden wie veröffentlicht?**

Die Objektblätter sind Bestandteil der Fiche für die Anmeldung der Objekte beim
Büro der Ramsar-Konvention. Die Geodaten werden in der BGDI dargestellt und
sind auf der Homepage des BAFU integriert, wo sie gemäss den Bestimmungen
des Geoinformationsgesetzes öffentlich zur Verfügung stehen.
Biologische Vielfalt
Biodiversitätspolitik
Grundlage für den Schutz
Langfristig geschützte
Ramsar-Objekte
Veröffentlichung der Daten

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**4**


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
Geodaten
Geobasisdaten
Georeferenzdaten

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**5**


## 3. Modellbeschreibung


**3.1.**


**Ramsar- Konvention**

Ramsar-Objekte sind Schutzgebiete im Rahmen des „Übereinkommen über
Feuchtgebiete, insbesondere als Lebensraum für Wasser- und Watvögel, von
internationaler Bedeutung“. Da ihre Umsetzung im Rahmen von Gesetzen und
Verordnungen auf Stufe Bund oder Kanton erfolgt sind die Objekte entweder in
Bundesinventaren aufgeführt oder in kantonalen Schutzbeschlüssen festgehalten.
Die Perimeter wurden jeweils aus den entsprechenden digitalen Datensätzen
entnommen und für das Objekt „Laubersmad“ ab der Landeskarte 1:25‘000
digitalisiert.
Abbildung 1: Georeferenzierung des Objekts mittels PK25

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**6**


## 4. Modell-Struktur: konzeptionelles Datenmodell


**4.1.**


**Graphische Darstellung**

Die Abbildung 2 zeigt das UML-Diagramm für die Ramsar- Konvention
DesignationType
<<enumeration>>
SAC
SPA
SCI
RAMSAR
NDA
MultilingualMText
IUCNCategory
<<enumeration>>
Strict_Nature_Reserve_Ia
Wilderness_Area_Ib
National_Park_II
Natural_Monument_III
Habitat_or_Species_Management_Area_IV
Protected_Landscape_or_Seascape_V
Managed_Resource_Protected_Area_VI
RAMSAR
ObjNummer[1] : Zeichenkette
Name[1] : Zeichenkette
RefObjBlatt[0..1] : URI
DesignatType[1] : DesignationType
IUCNCategory[1] : IUCNCategory
Obj_GISFlaeche[1] : Numerisch
Inkraftsetzungsdatum[1] : XMLDate
Mutationsdatum[0..1] : XMLDate
MultiSurface
RAMSAR_Teilobjekt
Teilobj_Nr[1] : Zeichenkette
Mutationsgrund_Text
+
0..1
1..*
1
Geo_Obj
+
1
Abbildung 2: Darstellung der Ramsar- Konvention als UML-Diagramm

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**7**


**4.2.**


**Objektklassenkatalog**

Entität R AMSAR
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

**Objekts**


**TEXT**


**9**


**Nummer Grundlage Bund**

Obligatorisch
A1.2
Name
Bezeichnung des

**Objekts**


**TEXT**

Laubersmad-

**Salwidili**

Obligatorisch
A1.3
RefObjBlatt
URL
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


**ramsar**

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

IV
(Management

**Area)**

http://www.unep-
wcmc.org/protected_areas/categories/index.

**html**

Obligatorisch

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**8**

MCPFE und der
Kategorien der IUCN

**gemacht.**

A1.6
Obj_GISFlaeche
GIS-Gesamtfläche des

**Objekts in ha**


**DOUBLE**


**10.737 ha**

Obligatorisch
A1.7
Inkraftsetzungsdatum
Datum der
Inkraftsetzung des
Objekts
DATE

**01.02.1991**

Obligatorisch
A1.8
Mutationsdatum
Datum der Mutation
des Objekts
DATE

**1.07.2007**

Fakultativ
A1.9
Mutationsgrund
Angaben zur Mutation
des Objekts
TEXT
Vergrösserung
Objekt auf

**Antrag Kt**

Fakultativ
Entität Ramsar_Teilobjekt
Merkmal (Attribut)
Erklärung
der
Merkmale
Datentyp
Beispiel
Bemerkungen
Pflichtattribut
A1.10
Teilobj_Nr
Identifikationsnummer
des Teilobjekts
TEXT
Bundesinterne Identifikationsnummer des
Teilobjekts
Obligatorisch
A.1.11
Geo_Obj
Ausdehnung des
Objekts
POLYGON

**Obligatorisch**


**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**9**


**4.3.**


**Beschreibung mit INTERLIS 2.3**

Eine Beschreibung des Modells im Format INTERLIS 2.3 befindet sich im Anhang. Gegenüber INTERLIS
1 bietet INTERLIS 2 verschiedene Vorteile. So können zum Beispiel Bedingungen (Constraints) formuliert
werden. Weiter ist die Möglichkeit der Vererbung für die Kantone interessant, welche das Bundesmodell
ergänzen möchten. Aus diesen Gründen hat sich das BAFU entschieden, die Version 2.3 von INTERLIS
zu verwenden.

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**10**


## 5. Darstellung der Daten der Ramsar-Objekte


**5.1.**


**Darstellungsmodell Bund**

Die Daten der Ramsar-Objekte werden vom BAFU für den Vollzug des Arten- und
Biotopschutzes verwendet. Die Darstellung erfolgt im Rahmen der Anmeldung
resp. bei Revisionen der Objekte. Dabei gelangt die folgende geographische
Darstellungsart zur Anwendung (Abbildung 3).
Abbildung 3: Geographische Lage der Ramsar- Objekte.
Legende:
Darstellungsmodell Bund

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**11**


## Anhang


**I Datenmodell im Format INTERLIS 2.3**

Bei Abweichungen zwischen der INTERLIS-Modelldefinition in der Modelldokumentation und dem Model Repository gilt die Version m Model Repository.
INTERLIS 2.3;
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=2.1
MODEL RAMSAR_LV03_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-03-28"  =
IMPORTS GeometryCHLV03_V1,LocalisationCH_V1,Units;
TOPIC RAMSAR =
DOMAIN
/* Aufzählungslisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA
);

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

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
/* Klasse für RAMSAR-Teilobjekt */
CLASS RAMSAR_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT*30;
Geo_Obj : MANDATORY GeometryCHLV03_V1.MultiSurface;
END RAMSAR_Teilobjekt;
/* Klasse für gesamtes RAMSAR-Objekt */
CLASS RAMSAR =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Obj_GISFlaeche : MANDATORY 0.000 .. 999999.000 [Units.ha];
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund_Text : LocalisationCH_V1.MultilingualMText;
END RAMSAR;

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**13**

ASSOCIATION RAMSAR_TeilobjektRAMSAR =
RAMSAR_Teilobjekt -- {1..*} RAMSAR_Teilobjekt;
RAMSAR -<#> {1} RAMSAR;
END RAMSAR_TeilobjektRAMSAR;
END RAMSAR;
END RAMSAR_LV03_V1_1.
!!@ furtherInformation=https://www.bafu.admin.ch/geodatenmodelle
!!@ technicalContact=mailto:gis@bafu.admin.ch
!!@ IDGeoIV=2.1
MODEL RAMSAR_LV95_V1_1 (de)
AT "https://models.geo.admin.ch/BAFU/"
VERSION "2017-03-28"  =
IMPORTS GeometryCHLV95_V1,LocalisationCH_V1,Units;
TOPIC RAMSAR =
DOMAIN
/* Aufzählungslisten */
DesignationType = (
SAC,
SPA,
SCI,
RAMSAR,
NDA

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**14**

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
/* Klasse für RAMSAR-Teilobjekt */
CLASS RAMSAR_Teilobjekt =
Teilobj_Nr : MANDATORY TEXT*30;
Geo_Obj : MANDATORY GeometryCHLV95_V1.MultiSurface;
END RAMSAR_Teilobjekt;
/* Klasse für gesamtes RAMSAR-Objekt */
CLASS RAMSAR =
ObjNummer : MANDATORY TEXT*30;
Name : MANDATORY TEXT*80;
RefObjBlatt : INTERLIS.URI;
DesignatType : DesignationType;
IUCNCategory : MANDATORY IUCNCategory;
Obj_GISFlaeche : MANDATORY 0.000 .. 999999.000 [Units.ha];
Inkraftsetzungsdatum : MANDATORY INTERLIS.XMLDate;
Mutationsdatum : INTERLIS.XMLDate;
Mutationsgrund_Text : LocalisationCH_V1.MultilingualMText;

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**15**

END RAMSAR;
ASSOCIATION RAMSAR_TeilobjektRAMSAR =
RAMSAR_Teilobjekt -- {1..*} RAMSAR_Teilobjekt;
RAMSAR -<#> {1} RAMSAR;
END RAMSAR_TeilobjektRAMSAR;
END RAMSAR;
END RAMSAR_LV95_V1_1.

**BAFU 2018**

Ramsar- Konvention: Umsetzung des Geoinformationsgesetzes

**16**


**II Darstellungsmodell Ramsar- Konvention**


**(Ramsar)**
