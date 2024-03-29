# Grundlagen der Fernerkundung: Zusammenfassung
## Definition
Fernerkundung ist die Gesamtheit der Verfahren zur Gewinnung von Informationen über die Erdoberfläche durch Messung und Interpretation der von ihr ausgehenden (Energie-)Felder. Sie erfolgt berührungslos und als Informationsträger dient die von der Erde reflektierte oder emittierte elektromagnetische Strahlung.
* Fernerkundung = Interpretieren (Thematische Informationen)
* Photogrammetrie = Messen (geom. Objektrekonstruktionen)


## Vorgehensweise
* Aufnahme
* Speicherung
* (Digitale Bildverarbeitung)
* Auswertung
  * Visuelle Bildinterpretation
  * Digitale Bildauswertung
* (GIS, GDIS)
> bspw. auch Zusammenhänge zur Geologie und Geomorphologie herstellen (z.B. Verzweigung des Entwässerungsnetzes im Untergrund)

> in der Archäologie kann durch Fernerkundung auf altes Niveau geschlussfolgert werden

![bewuchsmerkmale](https://github.com/s92854/Fernerkundung/assets/134683810/f5b3e325-ee2c-4819-860d-241e4c2490fc)
![gebäudegrundriss-auf-feld](https://github.com/s92854/Fernerkundung/assets/134683810/18bf3241-80b9-4b89-b409-308df5423515)

## Elektromagnetische Strahlung
* Wellenstrahlung
* Form der Energieausbreitung - mit Lichtgeschwindigkeit $c$
* besitzt Frequenz $\nu$ und Wellenlänge $\lambda$

![Elektromagnetisches Spektrum](https://github.com/s92854/Fernerkundung/assets/134683810/d9e0c60e-6b14-47af-9e1c-3d42fb2d2f1f)

![Strahlungsfluss](https://github.com/s92854/Fernerkundung/assets/134683810/686ed4e9-fcbc-485e-ac90-ed3434fb3891)

* Reflexionsgrad $\rho$
* Absorptionsgrad $\alpha$
* Transmissionsgrad $\tau$
* Emissionsgrad $\epsilon$

$$\rho = {\Phi r \over \Phi}$$

$$\alpha = {\Phi a \over \Phi}$$

$$\tau = {\Phi d \over \Phi}$$

$$\epsilon = {\Phi e \over \Phi s}$$

$\rho ,\alpha ,\tau$ sind dimensionslos: $\rho + \alpha + \tau = 1$
Wellenlängen der optischen Fernerkundung: $\tau = 0$, da die meisten Körper undurchlässig > $\rho + \alpha = 1$
Schwarzer Körper absorbiert Strahlung vollständig und erhitzt sich auf eine bestimmte Temperatur, bis diese erreicht ist, dann emittiert er die Strahlung vollständig ($\lambda$ ist abhängig von der Temperatur des Körpers)

### Kirchhoffsches Gesetz
$\epsilon = \alpha$
Ein Körper, der stark absorbiert ist auch ein guter Strahler und umgekehrt.
$\epsilon$ und §\alpha$ sind stark wellenlängenabhängig

### Plank
#### Plank'sches Strahlungsgesetz
* Zusammenhang zwischen Strahlunsleistung pro Fläche und Raumwinkel bei einer bestimmten Wellenlänge und der Temperatur eines Körpers
#### Planksches Strahlungsspektrum
* Darstellung der spektralen Strahldichte L<sub>SK</sub>
#### Spektrale Strahldichte L<sub>SK</sub>
* Angabe der Emission der Strahlungsleistung [in Watt] eines Körpers pro Fläche [m²] pro Raumwinkel [Steradiant: sr] in Abhängigkeit von der Wellenlänge der Strahlung [µm] bei einer bestimmten absoluten Temperatur [Kelvin].
#### Steradiant
* Maßeinheit für Raumwinkel
* Bei Kungel mit r = 1: Kugelkalotte mit Fläche auf Kugeloberfläche von 1m²

![steradiant](https://github.com/s92854/Fernerkundung/assets/134683810/77436f81-0264-42b1-b1ba-d1e7be9edd1f)

> Raumwinkel der gesamten Kugeloberfläche: $4 \pi sr$

### Berücksichtigung der Wellenlängenabhängigkeit
$\alpha(\lambda)$: Spektraler Absorptionsgrad

$\epsilon(\lambda)$: Spektraler Emissionsgrad

$\rho(\lambda)$: Spektraler Reflexionsgrad

$\tau(\lambda)$: Spektraler Transmissionsgrad

## Einflüsse der Atmosphäre
| Name | Einfluss |
|------|----------|
|Refraktion| Atmosphärische Strahlenbrechung durch Dichteveränderungen in der Luft |
|Absorption|Umwandlung von Strahlungsendergie in Wärme|
|Streuung|Streuung an kleinen Materieteilchen (Aerosolen)|
|Extinktion: Absorption & Streuung|Auslöschung der für die Fernerkundung nutzbaren Strahlung|

### Atmosphärische Fenster
* Für die Fernerkundung nutzbare Wellenlängenbereiche
* Atmosphäre ist hier durchlässig
* Sichtbares Licht ($\lambda > 0,3µm$) - Mikrowellen ($\lambda < 1m$)

### Strahlungsverhältnisse bei der Aufnahme

![strahlungsverhältnisse](https://github.com/s92854/Fernerkundung/assets/134683810/6c145079-4fb5-4da0-8dde-5b288ae95847)

* Direkte (gerichtete) Sonnenstrahlung: Primärstrahlung
* Indirekte (diffuse) Himmelsstrahlung (Streuung an Aerosolen): sekundäre Strahlungsquelle

### Luftlicht
* Anteil diffuser Himmelsstrahlung
* verringert Kontraste
* kurzwellige Wellenlängen überwiegen

![luftlicht](https://github.com/s92854/Fernerkundung/assets/134683810/d2f6966b-ab3c-4440-8f02-8d7c931c934e)

* Am Boden reflektiert der Nadelwald 1% der Strahlung, der trockene Sand 30% > Ergibt ein 1:30 Objektkontrast
* In 3000m Höhe: Überlagerung von 3% durch Luftlicht > ergibt 4:33 ≈ 1:8 Bildkontrast
--> Wolken sind ein Problem: $\lambda > 3cm$ kann Wolken durchdringen

### Reflexion
![reflexion_oberfläche](https://github.com/s92854/Fernerkundung/assets/134683810/4b513644-4a8a-4fc1-94f1-1e224b3c1056)

#### Reflexion bei Blättern
![blätter-reflexion](https://github.com/s92854/Fernerkundung/assets/134683810/512939ee-14cb-4521-8cbd-78fd4b2e52c9)

* Mechanismen bezüglich Umgebungsstrahlung bis heute nicht vollständig erforscht
* wichtige Komponente der biochemischen Prozesse auf der Erde
* wichtige Rolle spielen Chlorophylle und Karotine, Wasser, Zellulose, Ligin, Stärke, Proteine, uvm.

### Mitlicht - Gegenlicht
![mitlicht-gegenlicht](https://github.com/s92854/Fernerkundung/assets/134683810/888a8336-1e4b-48e2-99c8-cfbe2c21938d)

#### Mitlichtbereich
![mitlicht](https://github.com/s92854/Fernerkundung/assets/134683810/2fda5fc9-3717-4951-a248-7bf9b7eb7eb5)

#### Bildmitte
![mitte](https://github.com/s92854/Fernerkundung/assets/134683810/638610a0-e79f-4924-8b8b-7f42ae71dc90)

#### Gegenlichtbereich
![gegenlicht](https://github.com/s92854/Fernerkundung/assets/134683810/af521dc7-587b-4ebd-bf19-77aa7a2a5feb)

### Strahlungsverhältnisse an Wasserflächen
![strahlung-wasserflächen](https://github.com/s92854/Fernerkundung/assets/134683810/24ce27bd-41ca-4f2a-adfa-2e051be6fc3b)

#### Geometrischer Zusammenhang
![geom-zusammenhang](https://github.com/s92854/Fernerkundung/assets/134683810/7495c655-afbf-4471-90af-2cf98bf9c59c)

### Strahlungsgrößen
* Albedo
  * Verhältnis Ausstrahlung-Einstrahlung der Erdoberfläche (kruzwelliger Sketralbereich)
* Top of Atmosphere (TOA) Reflectance
  * Verhältnis Ausstrahlung-Einstrahlung auf Sensor-Ebene außerhalb Erdatmosphäre
* Surface Directional Reflextance (SDR)
  * atmosphärisch korrigierte TOAR
* Surface Reflectance (SR)
  * wie SDR + winkelabhängige Effekte (bidirektionale Reflektanzverteilungsfunktion: BRDF)

## Thermalstrahlung
* in FIR (fernes Infrarot): 8 - 14 µm

![thermalstrahlung](https://github.com/s92854/Fernerkundung/assets/134683810/597d64b8-5719-4e26-b799-57580c118d1d)

$L$<sub>SK</sub>$[{W \over m² sr µm}]$

* Datenaufnahme im Thermalbereich nahezu unbeeinflusst von reflektiertem Sonnenlicht
* Plank'sches Strahlungsgesetz gilt nur für schwarze Körper > reale Körper strahlen weniger > Kennzeichnung durch spektralen Emissionsgrad $\epsilon$

$\epsilon = {\Phi e \over \Phi s}$

* $\epsilon$ ist wellenlängenabhängig > daher eigentlich $\epsilon(\lambda)$ > $\epsilon$ als Näherungsangabe

### Strahlungstemperatur T<sub>S</sub>
* Annahme: $\epsilon = 1$
* aus Strahldichte L<sub>SK</sub> lässt sich Temperatur T<sub>S</sub> ableiten
* es gilt: T<sub>S</sub> < T (wahre Oberflächentemperatur)
* T = T<sub>S</sub> + $\tau$ (Korrekturbetrag (abhängig von Art der Oberfläche))

#### Bestimmung von $\tau$
* Messung der Temperatur von verschiedenen Oberflächen im Gelände
* "in situ" Messungen = Messungen im Gelände

### Einflüsse der Atmosphäre
* Streuungsvorgänge spielen keine Rolle
* starke Absorptionserscheinungen
* Atmosphäre gibt selbst Strahlung ab
  * Gegenstrahlung (Meteorologie) ist der Anteil, der zur Erdoberfläche gelangt
  * der zum Sensor gerichtete Anteil ist ein Störfaktor
* Absorption am geringsten im Bereich 8-13µm (Absorptionsband des Ozons: 9,6µm)

## Mikrowellen
* Bei $\lambda > 3cm$ kaum Einflüsse der Atmosphäre (Wolken werden durchdrungen)
* $1mm < \lambda < 3cm$ werden auch Mikrowellen von der Atmosphäre beeinflusst
* Materialien an der Erdoberfläche erzeugen aufgrund ihrer Temperatur (schwache) Mikrowellenstrahlung
* Empfang mit Mikrowellenradiometern möglich (passives System)
* Messung nur mit geringer geometrischer Auflösung
* passive Mikrowellen-Fernerkundung liefert keine Bilder, die für die Interpretation geeignet sind > große Rolle spielen aktive Systeme

![passive-aktive-mikrowellensysteme](https://github.com/s92854/Fernerkundung/assets/134683810/03f97488-7056-4664-8a89-3482fc576a37)

# Visuelle Bildinterpretation
* ohne, kann Mensch sich in Umwelt weder orientieren, noch sie verstehen
* qualitativ hochwertigste Ergebnisse
* 3 Hauptkomponenten:
  * Physik, Physiologie, Psychologie
* Farbbilder leichter als Graustufenbilder interpretierbar (nur 20-30 Grautöne wahrnehmbar, aber viel mehr Farben)
#### Aber Achtung! Künstliche Farbskalen können frei gewählt und angeordnet worden sein
* Farbskala nicht wertfrei, da Menschen mit bestimmten Farben bestimmte Assoziationen haben (z.B. rot - blau: warm - kalt): daher auf Legende achten

### Gradienten
* Gefälle bzw. Steigung der Reizverteilung im Sehfeld
  * Größengradienten
  * Dichtegradienten
  * Texturgradienten
  * Kontrastgradienten
  * Farbgradienten
  * Helligkeitsgradienten

## Interpretationsfaktoren
* Helligkeit einer Fläche
* Helligkeitsunterschiede
* Zeit / Zeitliche Unterschiede
* Farbton
* Sättigung
* Farbunterschiede
* Form von Objekten
* Größe von Objekten
* Textur einer Oberfläche

* Schattierungen
* Helligkeitsgradienten
* Fehlwahrnehmungen (Inversionen)
* Schlagschatten
* Relative Lage von Objekten
* Vegetationsmuster
* Siedlungsmuster
* Stereoskoptischer Effekt


### Phänologie
periodisch wiederkehrende Entwicklungen in der Natur
Im Jahresverlauf ändernde Texturen sind phänologische Erscheinungen

![Entwässerungsnetz Übersicht](https://github.com/s92854/Fernerkundung/assets/134683810/03fb2c5f-9a8a-4a7a-b6c4-58c6130b6b10)

Dentritisches Netz bspw. bei tonigem Gestein

Radiales Netz bspw. an einem Vulkankegel

![Entwässerungsnetz](https://github.com/s92854/Fernerkundung/assets/134683810/eba2aa42-1617-4f23-8c2d-c4767e9fac61)

![Schema: Interpretationsvorgang](https://github.com/s92854/Fernerkundung/assets/134683810/e4908ae9-b5b8-48dc-9186-48a4ce8d4a7d)

## Stereoskopisches Sehen

![stereo](https://github.com/s92854/Fernerkundung/assets/134683810/9d42cc48-c32e-4a08-9466-bab2ba6a7360)

5" - 10" kleinster Wert für $\epsilon$ (stereoskoptische Sehschärfe)
Monoskopische Sehschärfe liegt bei 30"
Größter Wert für $\epsilon$ liegt bei 1,3 gon bzw. 4212". Danach zerfällt das Bild in Vorder- und Hintergrund

### Bedingungen für künstliches stereoskopisches Sehen
* Zwei Bilder zeigen selbe Szene von verschiedenen Orten mit gleichem Maßstab
* Beide Augen betrachten beide Bilder getrennt, aber gleichzeitig
* Bilder müssen so angeordnet werden, dass Sehstrahlen der Augen im Raum in homologen Punkten am Objekt schneiden (Bilder müssen relativ orientiert sein)

### Prinzip des stereoskopischen Messens

![Prinzip Stereomessen](https://github.com/s92854/Fernerkundung/assets/134683810/84d2e356-2b93-409d-a4d6-6746d6da1493)

#### Hilfsmittel
* Linsenstereokop
* Spiegelstereokop
* Interpretationsstereokop
* Messkeil und Messkreise
* Stereomonitor

#### Methoden der Bildinterpretation

![Schema Arbeitsvorgänge](https://github.com/s92854/Fernerkundung/assets/134683810/1ef97ba6-479a-49ba-adc4-58961685df49)

### Interpreationsaufgaben
* Klassifikation
* Zählung
* Messung
* Abgrenzung

### Minimal Mapping Unit (kleinste zu kartierende Einheit)
* Für praktische Durchführung einer Interpretationsaufgabe für flächenhafte Objekte, ist Festlegung der kleinsten noch zu kartierenden Einheit wichtig
* = Mindestgröße, die ein flächenhaftes Objekt haben muss, um noch kartiert zu werden
* Angabe in Einheiten der Bildvorlage oder in Geländeeinheiten
* Für vergleichbare Interpretationsergebnisse eines Projekts nicht mehr ändern
* von Nutzer festgelegt, ≠ Kartierungsgenauigkeit, aber = Detaillierungsgrad

### Kartierungsgenauigkeit (mapping accuracy)
Gibt an, mit welcher Genauigkeit Obekte in der Natur in einem bestimmten Kartenmaßstab dargestellt werden können
Bei gedruckten Karten = kleinste in der Karte noch darstellbare Strichstärke (Maßstab 1:25.000 > Kartierungsgenauigkeit von 5m in Geländeeinheiten). D.h. Objekte < 5m sind in Karte nicht mehr maßsstäblich korrekt, also ohne Generalisierung darstellbar. Wird mit Stiften dickerer Strichstärke gearbeitet, leidet die Kartierungsgenauigkeit darunter.
Digitale Rasterkarten sollte Pixelgröße in Geländeeinheiten der Kartierungsgenauigkeit entsprechen.
Bei digitalen Vektorkarten muss die Kartiergenauigkeit in den Metadaten angegeben sein. Enthält Bezug auf den Kartenmaßsstab, sowie Standardabweichungen für die Knotenkoordinaten.

![Gliederung Bildinhalt](https://github.com/s92854/Fernerkundung/assets/134683810/ee487f48-cdd0-4245-8223-203b82632f31)

![Interpretationsschlüssel Bäume](https://github.com/s92854/Fernerkundung/assets/134683810/1828ee1e-6807-4d31-a7c5-5697f163a63b)

Der Interpretationsschlüssel am Beispiel

![beispiel](https://github.com/s92854/Fernerkundung/assets/134683810/04223be5-22be-4eb3-b130-474af2c4933b)

![Interpretationsschlüssel beispiel](https://github.com/s92854/Fernerkundung/assets/134683810/46a6a2ad-2b97-4957-978e-aa4efbd29f38)

#### Geometrische Eigenschaften

![Geometrische Eigenschaften](https://github.com/s92854/Fernerkundung/assets/134683810/ee95768d-935a-4ad5-bf7c-746aedb9fa58)

![Inhalt: Satellitenbild vs. Topographische Karte](https://github.com/s92854/Fernerkundung/assets/134683810/48866292-d582-4ac7-bd05-0efbfe0f307e)

![Darstellung: Satellitenbild vs. Topographische Karte](https://github.com/s92854/Fernerkundung/assets/134683810/1abc97a5-888f-46db-b31f-a78092139f6e)

![Interpretation und Lesbarkeit: Satellitenbild vs. Topographische Karte](https://github.com/s92854/Fernerkundung/assets/134683810/ebe52330-dc13-40f6-8133-1a6a54d9d185)

## Auflösungsvermögen Sensor
Für Bestimmung wird Testtafel oder Siemensstern verwendet. AV gibt an, wie viele dunkle Balken von ihren gleich großen hellen Zwischenräumen in der Abbildung gerade noch unterscheidbar sind. Angabe in Linien pro Millimeter [L/mm] oder Linienpaare pro Millimeter [Lp/mm] - 1:25,4 = AV[L/mm] : AV[dpi]

### Vorgehensweise
* Aufnahme einer Testtafel mit Linien verschiedener Ortsfrequenz (unterschiedliche Liniendicke und -abstand pro einheitliche Wegstrecke)
* Feststellen, ab wann die Linien gerade noch erkennbar sind (in Linien pro mm: nur dunkle Linien)
* kontrastabhängig

### Faktoren
* Beugungsunschärfe
* Abberation (sphärische A. und chromatische A.)
* Position im Bild (Vignettierung)
* Körnigkeit des Films (analoge Fotographie)
* Detektorgröße und Empfindlichkeit (digitale Fotographie)
* Kontrast

### Beugungsunschärfe $u$

![Auflösungsvermögen Sensor](https://github.com/s92854/Fernerkundung/assets/134683810/a6abffb4-7472-4e5e-b500-afae65c5b2a6)

![Beugungsunschärfe](https://github.com/s92854/Fernerkundung/assets/134683810/e7871430-1b8d-491f-a71c-6f40c1603c69)

> Zwei trennbare Beugungsscheiben mit Interferenzringen. Die Beugungsscheiben verschmelzen zu einem Punkt wenn die Auflösungsgrenze $\delta$<sub>min</sub> unterschritten wird

* durch Beugung an einer Blende kein idealer Punkt in der Bildebene
* zentrales Beugungsscheibchen mit 84% der Strahlungsenergie
* Interferenzringe mit 7%, 3%, etc. der Strahlungsenergie
* der Sensor hält meistens nur das zentrale Beugungsscheibchen fest

#### theoretischer Gesamtdurchmesser u<sub>th</sub>

$u$<sub>th</sub>$[qm] = 2,44 * k * \lambda$

> $\lambda$ = Wällenlänge in µm

> k = $c \over d$ = Blendenzahl

Für fotografische Emulsion gilt aus Erfahrung
$u = 0,75 * u$<sub>th</sub>

#### Für die mittlere Wellenlänge des sichtbaren Lichts

$\lambda$ = 0,55µm

gilt:

$u [µm] ≈ k = c \over d$

$\delta$<sub>min</sub> ≈ $u \over 2$

> k = Blendenzahl

> c = Kamerakonstante

> d = Blendendurchmesser

> $\delta$<sub>min</sub> = Abstand von zwei zentralen Beugungsscheibchen

#### Beugungsunschärfe $u$ als Funktion der Blendenzahl $k$

![Beugungskurve](https://github.com/s92854/Fernerkundung/assets/134683810/a0caa62d-9bab-494d-99e2-58076cd19a86)

Je größer die Blendenöffnung, desto kleiner die Blendenzahl, desto höher das Auflösungsvermögen

## Aberation
... ist eine Abweichung von der idealen geometrisch-optischen Abbildung
* spärische Aberration (Öffnungsfehler)
  * parallel objektseitig auf eine Sammellinse einfallende Strahlen schneiden sich bildseitig nicht in einem Punkt

![sphärische aberration](https://github.com/s92854/Fernerkundung/assets/134683810/46806147-b193-4526-905c-0f22c00ec5e6)

* chromatische Aberration (Farbfehler)
  * unterschiedliche Wellenlängen > bei Übergang zwischen zwei Medien untersch. stark gebrochen > Farbfehler in optischer Abbildung

![chromatische aberration](https://github.com/s92854/Fernerkundung/assets/134683810/0b019868-0f71-48f2-bc6c-97438d034489)

### Optimales Auflösungsvermögen: Zusammenhang Blende, Beugungsunschärfe

![Optimales Auflösungsvermögen](https://github.com/s92854/Fernerkundung/assets/134683810/85479442-68e4-478b-aa27-c439aa797bc3)

### Vignette
... ist ein Lichtabfall von der Bildmitte zum Bildrand hin. Damit nimmt auch die Auflösung zum Bildrand hin ab.

### Körnung des analogen Films
* nichtentwickelter Film - Körner = Silberhalogenidkristalle
* entwickelter Film - Körner = Ballungen aus Silbermolekülen von 0,5 - 2 µm Durchmesser
* angegeben in RMSG (root mean square granularity)
* je grobkörniger, desto lichtempfidlicher der Film

### Kontrast
Die Ortsfreuquenz $f$ des Objekts beeinflusst den Kontrast im Bild ($f = 1 \over d$)
Balkenmuster als Testobjekt

#### Kontrast K bzw. C
wird auf Grundlage größter und kleinster Intensitäten definiert

$$K = I max \over I min$$

$$C = I max - I min \over I max + I min$$

$(0 <= C <= 1)$

&nbsp;

| K | C |
|----------|----------|
| 1000:1 | 0,998  |
| 6,3:1   | 0,73  |
| 1,6:1    | 0,23  |

#### Kontrastübertragung
Balkenmuster im Bild. Je höher die Ortsfrequenz $f$ des Objekts (je kleiner der Abstand der Balken), desto niedriger der Kontrast C' im Bild.

##### Kontrastübertragungsfunktion
... gibt in Abhängigkeit von den Ortsfrequenzen $f$ an, wie viel Prozent der vom Objekt ausgehenden Strahlungsintensität in die Bildebene übertragen wird.

![Kontrastübertragungsfunktion](https://github.com/s92854/Fernerkundung/assets/134683810/b3a54eaf-d970-4041-9bf0-d899d5418bf1)

$$CT = C' \over C$$

Der Bildkontrast ist von der Ortsfreuquenz des aufgenommenen Objekts abhängig (je höher die die Ortsfrequenz, desto schlechter der Kontrast). Umgekehrt begrenzt der Bildkontrast die Auflösungsgrenze, d.h. die Ortsfrequenzen, die im BIld gerade noch wiedergegeben werden können.
#### Fazit
Das maximale Auflösungsvermögen eines Filmmaterials oder eines digitalen Sensors lässt sich exakt nur für einen eindeutig definierten Objektkontrast angeben.

### Detektorgröße
Detektorgröße $\delta x, \delta y$ ist für Auflösung und Lichtempfindlichkeit entscheidend (je größer Detektorfläche, desto Lichtempfindlicher). Abstand der Detektoren (Digitalisierungsabstand $\delta n$<sub>s</sub>) wichtig.

### (Nyquist-Shannon-) Abtasttheorem

![Abtasttheorem](https://github.com/s92854/Fernerkundung/assets/134683810/7aba5f7e-861c-45b8-a334-ec0e4ee34a41)

### Aliasing-Effekt

![Aliasing](https://github.com/s92854/Fernerkundung/assets/134683810/ed52fbcb-0727-45a8-a7e1-86a365f22c73)

### Moiré-Effekt

![Moiré](https://github.com/s92854/Fernerkundung/assets/134683810/55583e82-af20-4a09-a5d9-0358f6c6e1b6)

## Geometrische Auflösung
= Bodenauflösung (bei Satellitenbildern) : GSD = Ground Sampling Distance [m]
Je höher der Objektkontrast, desto kleinere Objekte können im digitalen Bild noch erkannt werden (und umgekhert).

$$ geometrische Auflösung = \frac{Pixelgröße}{Brennweite} * Abstand zum Objekt$$

![geometrische Auflösung](https://github.com/s92854/Fernerkundung/assets/134683810/ed4b5dd3-e1a7-418a-b4e3-5b23d49b8f33)

> Pixelgröße = Seitenlänge eines quadratischen Pixels mit Bezug auf die Bildebene des Sensors. Ø 1px: 3 - 8µm

Bei hohem Kontrast können auch Objekte kleiner als die geometrische Auflösung erkennbar sein. Umgekehrt können Objekte, die größer als die geometrische Auflösung durch geringen Kontrast zum Umfeld nicht sichbar sein.

### Auflösungsvermögen und Kontrastübertragung

![mittelwertbildung pixel](https://github.com/s92854/Fernerkundung/assets/134683810/aac2e0ba-e64d-4ce9-ab83-28fe84e79a9d)

Weshalb eine 5m breite Straße mit 30m Bodenauflösung erkannt werden kann:

![landsat-wüste](https://github.com/s92854/Fernerkundung/assets/134683810/ee6b36a3-1073-464f-8571-f2ceeaf95259)


### Kell-Faktor
Kein Zusammenhang zwischen Auflösungsvermögen und in Pixelgrößen angegebener Auflösung digitaler Rasterdaten > Vergleichbarkeit herstellen (z.B. Kell-Faktor).
Auflösung [m/lp] ≈ 2,8 * Auflösung [m/px]

## Radiometrische Auflösung
### A/D Wandlung (analog/digital)
* Abtastung des analogen Sensorsignals
* Angabe, in wieviele Grauwerte der Bereich zwischen Schwarz und Weiß unterteilt wird
* je höher r.Auflösung, desto mehr Details lassen sich auch bei schwachem Kontrast erkennen

#### 1 Bit Radiometrische Auflösung

![1bit r.a.](https://github.com/s92854/Fernerkundung/assets/134683810/f0e5a1f3-86bd-4d0a-a0ea-989a0431858d)

> Elektrooptischer Wandler gibt 0 oder 1 (schwarz/weiß) aus (Binärbild)

&nbsp;

#### 12 Bit Radiometrische Auflösung

![12bit r.a.](https://github.com/s92854/Fernerkundung/assets/134683810/25a1849c-a6d8-45b2-93eb-1e8f9e33ecd7)

> Elektrooptischer Wandler hat 2<sup>12</sup> = 4096 mögliche Grauwerte (Wertebereich von 0 bis 4095) > deutlich Detailreicher

Tatsächlicher Grauwertumfang hängt von radiometrischer Kalibrierung der Kamera ab

#### Typische Schärzungskurve Analoges Filmmaterial

![Schwärzungskurve Analog](https://github.com/s92854/Fernerkundung/assets/134683810/b6e0421f-2ecf-4bf1-8e7b-b81627e01520)

#### Typische Kennlinie CCD-Element

![Kennlinie CCD](https://github.com/s92854/Fernerkundung/assets/134683810/b6290b33-b145-42dd-a484-33f4c34d00c1)


## Spektrale Auflösung
Angabe, wie viele unterschiedliche Spektralkanäle aufgezeichnet werden, sowie welcher Bereich von einem Kanal erfasst wird (Grenzen jedes Kanals).

### Begriffe
VNIR = visible + near infrared
* visible = sichtbares Licht (Wellenlängenbereich ca. 0,4µm - 0,7µm)
* near infrared = nahes Infrarot (0,7 - 1,4µm)
* SWIR = short wavelenght infrared (1,4  3,0µm)
* MWIR = mid wavelenght infrared (3,0 - 8,0µm)
* LWIR = long wavelenght infrared (Thermales Infrarot) (8,0 - 15,0µm)
* Spektrale Auflösung = spectral resolution
* Panchromatisch = 1 Kanal
* Multispektral = 2-12 Kanäle
* Hyperspektral = > 100 Kanäle

Je höher die spektrale Auflösung, desto geringer ist die Bandbreite. Bsp.: Ein Panchromatischer Kanal hat eine größere Bandbreite, als jeweils einer der drei Farbkanäle.

![Aufteilung spektrale Auflösung](https://github.com/s92854/Fernerkundung/assets/134683810/456ce3fd-ac81-4872-a5fb-e5fef9afa4f9)

* Digitale Aufnahmesysteme können mehrere Spektralbereiche simultan aufnehmen
* Spektrale Eigenschaften eines digitalen Aufnahmesystems sind kalibrierbar. Fotochemiches Filmmaterial (analoger Film ist radiometrisch nicht kalibrierbar)
* Messung von Reflektanzen möglich

Unterschiedliche Kanäle offenbaren andere Strukturen (bspw. sind Gewässer im NIR-Kanal sehr gut erkennbar und im Grünkanal fast gar nicht)

## Temporale Auflösung (Wiederholrate)
= kürzeste Zeitintervall mit dem ein Fernerkundungssystem einen identischen Ausschnitt der Erdoberfläche wiederholt aufnehmen kann

### Umlaufbahn der LANDSAT-Satelliten
* Bahn ist polar, kreisförmig und sonnensynchron
  * Sonnensynchron = Äquator wird stets zur selben Ortszeit (9:30 Uhr) überflogen (dient dazu, annähernd gleiche Aufnahmebedingungen zu erreichen)

## Optisch-Mechanischer Sensor
...auch Whisk-Broom (Wischbesen) Scanner genannt

![Optisch-mechanischer Sensor](https://github.com/s92854/Fernerkundung/assets/134683810/b077f009-4b4d-473d-b717-bd3155d742f7)

### Temperaturreferenz zur Aufnahme von Thermalstrahlung

![Temperaturreferenz](https://github.com/s92854/Fernerkundung/assets/134683810/409d326d-e521-4417-9eab-e57c50fe31f9)

### Geometrie der optisch-mechanischen Abtastung

![Geometrie](https://github.com/s92854/Fernerkundung/assets/134683810/ba28cd57-cf98-427f-ae9d-41f026824da0)

### Überlagerung von Flug- und Rotationsbewegung des Spiegels
Panorama- und S-förmige Verzerrung

![Überlagerung](https://github.com/s92854/Fernerkundung/assets/134683810/16ca3c39-32b8-4083-beab-76d42635572c)

#### Unkorrigiertes Luftbild

![unkorrigiert](https://github.com/s92854/Fernerkundung/assets/134683810/1d9b9e94-5e3b-4810-9bcc-f9be949881cf)

#### Korrigiertes Luftbild

![korrigiert](https://github.com/s92854/Fernerkundung/assets/134683810/abf62c1c-e6be-46ff-a0cd-3dad0f57ad5b)

## Optoelektrische Zeilenkameras
... auch Push-Broom (Schiebebesen) Scanner genannt.

![optoel. Zeilenkamera](https://github.com/s92854/Fernerkundung/assets/134683810/626ea2c1-0228-4e1f-9f30-268010200e76)

![Mehrzeilensensor](https://github.com/s92854/Fernerkundung/assets/134683810/b1ed5bd6-88b7-4e81-83bc-41de35b77d87)
> HRSC-AX

> Panchromatische Zeilen: SA, PA, Nd, PF, SF

> Multispektrale Zeilen: Bl = blau, Gr = grün, Rd = rot, IR = nahes Infrarot

![Korrektur](https://github.com/s92854/Fernerkundung/assets/134683810/ffab887c-5525-4064-8aa1-f9c28a7d3710)

### Photogrammetrische Punktbestimmung

![photog. Punktbestimmung](https://github.com/s92854/Fernerkundung/assets/134683810/9376b38d-1cf2-46d5-9c1b-99981ecafe60)

## Optoelektrische Flächenkameras
Sie soll mit analogen Reihenmesskameras konkurrieren, in puncto:
* Bildformat
* geometrischer Auflösung
* Radiometrischer Auflösung
* Spektraler Auflösung

Ein digitaler Flächensensor müsste über 26.000px * 26.000px = 2,1 Gigapixel verfügen, um 23cm * 23cm analogem Bild mit 5µm Pixelgröße zu entsprechen > bis heute unmöglich

### Technische Realisierungen
#### Flächensensoren
* Butterfly-Typ

![image](https://github.com/s92854/Fernerkundung/assets/134683810/e5c6ff8e-eb2b-42b0-a5a2-5234e0009fe6)

* Patchwork-Typ
* Single-Array-Typ
#### Zeilensensoren (Pixelteppich-Typ)
* Sensoren mit einer Zeile
* Mehreilensensoren

#### Monolithischer-CCD-Sensor (DMC II)
Für die Multispektralen Kanäle:
* 4 42Mpx CCDs mit 7,2µm Pixelgröße > 43,9mm x 49,3mm / 6096px x 6846px
* 45mm Brennweite

Für den Panchromatischen Kanal
Option 1: DMC 140
* 1 140 Mpx Sensor mit 7,2µm Pixelgröße > 88mm x 82mm / 12240 px x 11418 px
* 92mm Brennweite
Option 2: DMC 250
* 1 250 Mpx Sensor mit 5,6µm Pixelgröße > 90mm x 84mm / 17216 px x 15556 px
* 112mm Brennweite

##### Postprocessing
* Geometrische Auflösung MS/Pan = 1:2
* Hochauflösende MS-Bilder durch Pan-Sharpening

##### CCD des Panchromatischen Kanals

![ccd-pan](https://github.com/s92854/Fernerkundung/assets/134683810/e01411cc-55db-4c9b-831d-da9603b8a7c7)


### Photogrammetrische Punktbestimmung

![photog. Punktbestimmung](https://github.com/s92854/Fernerkundung/assets/134683810/c52b2572-fee2-4967-af6b-3bea4c76077f)

#### Geometrische Eigenschaften
> Luftbild entsteht in Zentralprojektion

![zentralprojektion](https://github.com/s92854/Fernerkundung/assets/134683810/5c3e0b5a-4066-40e5-bf86-d4494aeec10b)

* Radiale Punktversetzung durch Höhenunterschiede

![Radiale Punktversetzung](https://github.com/s92854/Fernerkundung/assets/134683810/24fd6c87-8927-4696-a203-f14d102ecb03)

### Abbildende Spektrometer
* Hyperspektrometer
* kontinuierliche Erfassung von weiten Bereichen des elektromagnetischen Spektrums mit sehr vielen Kanälen > "Datenwürfel" (z.B. vom Zürichsee, SCHWEIZ) bestehend aus 126 Spektralkanälen

![Datenwürfel](https://github.com/s92854/Fernerkundung/assets/134683810/1ddf20ff-091a-4349-a844-b89e69efce1f)

### Lidar Laserscanner
Prinzip:
* gepulste Laserscanner (pulsed laser scanner)
* permanent messende Laserscanner (continous wave laser, cw laser, full waveform laser)

![Lidar](https://github.com/s92854/Fernerkundung/assets/134683810/e54913a8-6073-4699-8e51-323ba80383ee)

#### Aufnahme mit gepulstem Laserscanner Leica ALS60 (200kHz)

![Gepulst](https://github.com/s92854/Fernerkundung/assets/134683810/f9771e84-8a60-4f22-aac8-4c0e17092a41)

#### Einfach- und Mehrfachechos bei gepulsten Laserscannern

![Einfach- und Mehrfachechos bei gepulsten Laserscannern](https://github.com/s92854/Fernerkundung/assets/134683810/7a5ec79f-7c38-4372-8c3e-55bc0bf0eb5e)

#### Mehrfachechos bei gepulsten Laserscannern

![Mehrfachechos](https://github.com/s92854/Fernerkundung/assets/134683810/c7d7456c-6387-4ebe-8269-0c332920373b)

![Wald Vectorlayer](https://github.com/s92854/Fernerkundung/assets/134683810/ea86be67-87dd-4958-a0f8-dde74f2db81d)

> Gewinnung von Höhendaten > Visualisierbar

> Anbieter von flugzeuggetragenen Laserscannern: Fugro, Hexagon, IGI, Leica Geosystems, ...

## Satellitengestütze Stereoaufnahme
* Stereoaufnahme durch schwenkbare Aufnahmesysteme
  * Stereo in Flugrichtung (along-track stereo)
  * Stereo quer zur Flugrichtung (across-track stereo)
* Zwei- und Mehrzeilenscanner
* permanente Stereoaufnahme nur mit Zwei- und Mehrzeilenscannern möglich

#### IKONOS als Beispiel für eine Stereoaufnahme in Flugrichtung
![IKONOS Stereo](https://github.com/s92854/Fernerkundung/assets/134683810/a689f05a-5a34-463c-b3e1-aefb89d36281)

#### SPOT als Beispiel für eine Stereoaufnahme quer zur Flugrichtung
![SPOT Stereo Quer](https://github.com/s92854/Fernerkundung/assets/134683810/8773f995-e149-4c1a-b15a-669059d1cdcb)

#### ASTER Zweizeilenscanner
![ASTER Stereo](https://github.com/s92854/Fernerkundung/assets/134683810/b178b3ef-8092-46a3-b5b6-a5fec1d74065)

### Zusammenfassung Fernerkundungssysteme nach Ehlers

![Zusammenfassung Fernerkundungssysteme](https://github.com/s92854/Fernerkundung/assets/134683810/17713552-5a8f-4473-9a90-1c6fb8b6522d)
