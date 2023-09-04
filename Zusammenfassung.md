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
