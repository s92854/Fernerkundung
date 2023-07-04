# Übung 3: Bildinterpretation

## 1. [Konfluencepunkt](https://www.confluence.org/) heraussuchen

## 2. Account bei [EarthExplorer](https://earthexplorer.usgs.gov) erstellen und Daten herunterladen
* Land auswählen
* Datenfilter hinzufügen
* Landsat --> Landsat Collection 2 Level-2 --> richtigen Landsatdatensatz auswählen und herunterladen

## 3. B1 - B7 hinzufügen

## 4. vsk-Datei erzeugen

## 5. Layerstack-Datei erzeugen
* Raster --> Spectral --> Layerstack

<img width="317" alt="image" src="https://github.com/s92854/Fernerkundung/assets/134683810/60209ea7-fc04-46be-8b96-f1e64e2b6780">

## 6. Koordinaten berechnen
* Home --> Inquire --> von **Map** auf **Lat/Lon** stellen --> Koordinaten des Konfluenzpunktes eingeben (z.B. 49 N, 104 E für meinen [K-Punkt](https://www.confluence.org/confluence.php?lat=49&lon=104)) --> Enter (IMAGINE errechnet Koordinaten für das img) --> Wechsel von **Lat/Lon** auf **Map** --> Koordinaten einmal -5000 und einmal +5000 berechnen

Bsp.:
```
-5000:  426865.28, 5428490.85 --> 421865.28, 5423490.85
+5000:  426865.28, 5428490.85 --> 431865.28, 5433490.85
```

## 7. Subset erstellen
* Multispektral --> Utilities --> Subset & Chip --> -5000 Koordinaten bei UL eingeben und +5000 bei LR eingeben

<img width="325" alt="image" src="https://github.com/s92854/Fernerkundung/assets/134683810/68a44ab4-47c8-4948-9a4f-a9add64a86b9">

## 8. NDVI erstellen
* Help --> Search --> NDVI

<img width="477" alt="image" src="https://github.com/s92854/Fernerkundung/assets/134683810/88dad62c-e0bc-49a8-a099-b74dd48823b3">

