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
