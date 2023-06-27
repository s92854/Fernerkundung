# Übung 1

## Landsat
* ist eine Fernerkundungsmission
* [Zeitstrahl](https://upload.wikimedia.org/wikipedia/commons/b/bf/Landsat_program_timeline.png) aller Landsatmissionen (Stand: 2023)
* Infrarotbild: Wasserflächen sind dunkel, weil keine Vegetation; Wenn doch, dann Hinweis auf Algen

## Trägerplattformen
* LANDSAT 1
* ...
* LANDSAT 9

## Landsatsensoren
* MSS = Multispectral Scanner System (Landsat 1-5)
* TM = Thematic Mapper (L4,5)
* ETM+ = Enhanced Thematic Imager (L7)
* OLI = Operational Land Imager (L8)
* OLI-2 (L9)
* TIRS = Thermal Infrared Sensor (L8)
* TIRS (L9)

## Vorteil Landsat gegenüber Copernicus
* Landsat geht weiter in die Vergangenheit (Copernicus sehr junges Programm)

## Begriffe
* Veränderungsanalysen/ Zeitreihenanalyse (Change Detection)
* [Elektromagnetisches Spektrum](https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Electromagnetic_spectrum_-de_c.svg/1470px-Electromagnetic_spectrum_-de_c.svg.png)
* Infrarot = jenseits von rot (fernes Infrarot = Wärmestrahlung)
* Spacial Rsolution = Bodenauflösung
* Satellitenbildscene = Das Satellitenbild
* Schwadbreite = Breite, die ein Bild umfasst (Bildbreite)
* Panchromatischer Kanal = Grenzenüberschreitender Kanal

![image](https://github.com/s92854/Fernerkundung/assets/134683810/a9d4e89d-6496-4002-a933-a020a37aa485)

* zwischen 10<sup>-15</sup> und 10<sup>-14</sup> atmosphärische Fenster
* Je größer der abgeckte Bereich, desto mehr Informationen werden auf den Pixeln hinterlegt

Thermalsensor hat geringere Auflösung, da geringere Lichtenergie --> größere Fläche, sodass überhaupt noch Informationen ankommen


## Radiometrische Auflösung
* ... ist der Wertebereich pro Pixel (Grauwertabstufung)
* 7bit = 2<sup>7</sup> = 128 Werte [0,127]
* 8bit = 2<sup>8</sup> = 256 [0,255]
* 12bit = 2<sup>12</sup> = 4096 [0,4095]
* 14bit = 2<sup>14</sup> = 16384 [0,16383]

## Spektrale Auflösung
* Wie viele Farbkanäle werden abgedeckt

## Zeitliche Auflösung
* Wie viel Zeit vergeht zwischen beiden Aufnahmen

## Geometrische Auflösung
* auch Bodenauflösung, GSD (Ground Sampling Distance) genannt


### Begriffe, die man kennen muss
* Elektromagnetisches Spektrum
* Wellenlängenbereiche --> nahs Infrarot (NIR)
* Echtfarbendarstellung
* Falschfarben
* Farbinfrarot
* Schwadbreite


# Einführung in ERDAS IMAGINE
* Wenn bei Layer ein kleines Warndreieck ist --> sehr wahrscheinlich fehlende Bildpyramide
-> Rechtsklick -> Correct Alert Problem -> Fehler wird angezeigt; Bestätigen für Korrektur
* Home -> Basemap -> OpenStreetMap
* Home -> Swipe zum swipen
* Home -> Measure zum Messen
* Rechtsklick -> Metadata; alle Daten zur Bilddatei, Projektion, etc.
* Edit -> Compute Pyramid Layers/ Statistics -> Ignore Value 0 ; errechnet Bilddaten neu
* Messen: Home --> Measure --> Point standard, Polyline/ Polygon auswählen --> Punkt(e) wählen, bei letztenm Punkt Doppelklick

## Datentypen
### nicht mit radiometrischer Auuflösung verwechseln!
unsigned = ohne Vorzeichen
signed = mit Vorzeichen
unsignet 8bit = [0,255]
signed 8bit = [-128,127]

DM = Digital Number für Itensitätswerte
Mode = Modalwert; Wert, der am häufigsten vorkommt
LUT = Look Up Table [Tabelle mit Originalwerten]

Original|Bildschirm
--------|----------
    1   | Ausgabe
    2   | Ausgabe
    3   | Ausgabe


#### Skip-Faktor
1 = alle Werte berechnen
5 = alle fünf Werte berechnen
usw.

### Virtual Stack
Rechtsklick in Arbeitsfläche -> Add Raster Layer -> B1 - B4 wählen -> Multiple -> Virtual Stack (.vsk Datei)

### Falschfarben IR Bild
Multispectral Tab -> Preset: Landsat 1,2,3 MSS und False Color IR -> Red: Layer 3; Green: Layer 2; Blue: Layer 1

### Natural Color Bild
Raster --> Spectral --> Natural Color --> .img wählen--> Ignore Zero in Stats --> Neues .img reinladen
Künstliches Grünfarbenbild


### Sentinel 2
#### Generelles
* Sentinel 2 verwendet Strahlung im L-Band (Lambda: ca. 6cm)
* Senden, Empfangen
    * Vertikal senden, Vertikal empfangen: vv
    * Vertikal senden, horizontal empfangen: vh
    * horizontal senden, vertikal empfangen: hv
    * horizontal senden, horizontal empfangen: hh


Wenn Warnung/ kleines X:
Normale Lizenz: Rechtsklick --> Correct the Alert Problem
Study-Lizenz: Metadata --> Edit --> Compute Pyramid Layers/ Statistics
--> Layer neu reinladen

### Infrarot Bild
* Layer ändern --> Rot: Layer 8; Grün: Layer 4; Blau: Layer 3


### ???
2017 Sentinel 1 --> subset_2_*.img --> Open Raster Layer --> Rechtsklick in Arbeitsfläche --> Swipe (Vergleiche von farbcodierten Wellenlängen möglich)
