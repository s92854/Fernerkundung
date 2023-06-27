B1 - B7.TIF auswählen --> Multiple --> Virtual Stack

Raster --> Spectral --> Layer Stack --> Input: *.vsk; Output: *.img --> Layer: All --> Add --> OK

## Area of Interest
* Basemap löschen
Rechtsklick --> New AOI Layer --> Polygonfunktion wählen --> Mauerverlauf (Westberlin) kartieren --> Für Abschluss: Letzter Punkt Doppelklick --> Rechtsklick auf die Maske im Contentsmenü --> Save Layer as

### Subset mit Inquire Box
ggf. Basemap löschen --> Multispectral --> Subset&Chip --> Ganz Berlin mit der sich öffnenden Box (Inquire Box) wählen und ein wenig mehr --> Outputfile wählen

### Subset mit AOI-Maske
* Raster --> Subset&Chip --> Create Subset Image
* Inputfile: Landsat89.img; Output: *.img; AOI: AOI Datei wählen; Ignore Zero in Output Stats --> OK

### Mithilfe einer Shapedatei
