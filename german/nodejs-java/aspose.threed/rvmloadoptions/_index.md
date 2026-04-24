---
title: RvmLoadOptions
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

Ladeoptionen für die RVM-Datei des AVEVA Plant Design Management Systems.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| Konstruktor(contentType) | Erstelle eine RvmLoadOptions-Instanz |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Erstelle eine RvmLoadOptions-Instanz |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| Name | Beschreibung |
| --- | --- |
| getGenerateMaterials() | Materialien mit zufälligen Farben für jedes Objekt in der Szene erzeugen, wenn die Farbpalette nicht im RVM‑Datei exportiert wird. Standardwert ist true |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| Name | Beschreibung |
| --- | --- |
| setGenerateMaterials(value) | Materialien mit zufälligen Farben für jedes Objekt in der Szene erzeugen, wenn die Farbpalette nicht im RVM‑Datei exportiert wird. Standardwert ist true |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| Name | Beschreibung |
| --- | --- |
| getCylinderRadialSegments() | Liest oder setzt die Anzahl der radialen Segmente des Zylinders, Standardwert ist 16 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| Name | Beschreibung |
| --- | --- |
| setCylinderRadialSegments(value) | Liest oder setzt die Anzahl der radialen Segmente des Zylinders, Standardwert ist 16 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| Name | Beschreibung |
| --- | --- |
| getDishLongitudeSegments() | Liest oder setzt die Anzahl der Längensegmente der Schüssel, Standardwert ist 12 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| Name | Beschreibung |
| --- | --- |
| setDishLongitudeSegments(value) | Liest oder setzt die Anzahl der Längensegmente der Schüssel, Standardwert ist 12 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| Name | Beschreibung |
| --- | --- |
| getDishLatitudeSegments() | Liest oder setzt die Anzahl der Breitensegmente der Schüssel, Standardwert ist 8 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| Name | Beschreibung |
| --- | --- |
| setDishLatitudeSegments(value) | Liest oder setzt die Anzahl der Breitensegmente der Schüssel, Standardwert ist 8 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| Name | Beschreibung |
| --- | --- |
| getTorusTubularSegments() | Liest oder setzt die Anzahl der röhrenförmigen Segmente des Torus, Standardwert ist 20 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| Name | Beschreibung |
| --- | --- |
| setTorusTubularSegments(value) | Liest oder setzt die Anzahl der röhrenförmigen Segmente des Torus, Standardwert ist 20 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| Name | Beschreibung |
| --- | --- |
| getRectangularTorusSegments() | Liest oder setzt die Anzahl der radialen Segmente des rechteckigen Torus, Standardwert ist 20 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| Name | Beschreibung |
| --- | --- |
| setRectangularTorusSegments(value) | Liest oder setzt die Anzahl der radialen Segmente des rechteckigen Torus, Standardwert ist 20 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| Name | Beschreibung |
| --- | --- |
| getCenterScene() | Zentriere die Szene, nachdem sie geladen wurde. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| Name | Beschreibung |
| --- | --- |
| setCenterScene(value) | Zentriere die Szene, nachdem sie geladen wurde. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Name | Beschreibung |
| --- | --- |
| getAttributePrefix() | Liest oder setzt das Präfix der Attribute, die in externen Attributdateien definiert wurden. Das Präfix wird verwendet, um Namenskonflikte zu vermeiden, Standardwert ist "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Name | Beschreibung |
| --- | --- |
| setAttributePrefix(value) | Liest oder setzt das Präfix der Attribute, die in externen Attributdateien definiert wurden. Das Präfix wird verwendet, um Namenskonflikte zu vermeiden, Standardwert ist "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| Name | Beschreibung |
| --- | --- |
| getLookupAttributes() | Liest oder setzt, ob Attribute aus einer externen Attributlisten-Datei (.att/.attrib/.txt) geladen werden sollen, Standardwert ist true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| Name | Beschreibung |
| --- | --- |
| setLookupAttributes(value) | Liest oder setzt, ob Attribute aus einer externen Attributlisten-Datei (.att/.attrib/.txt) geladen werden sollen, Standardwert ist true. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Name | Beschreibung |
| --- | --- |
| getFileFormat() | Liefert das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |

 **Result:**



---


### getEncoding{#getEncoding}

| Name | Beschreibung |
| --- | --- |
| getEncoding() | Liest oder setzt die Standardkodierung für textbasierte Dateien. Standardwert ist null, was bedeutet, dass der Importer/Exporter entscheidet, welche Kodierung verwendet wird. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Name | Beschreibung |
| --- | --- |
| getFileSystem() | Erlaubt dem Benutzer zu bestimmen, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Name | Beschreibung |
| --- | --- |
| setFileSystem(value) | Erlaubt dem Benutzer zu bestimmen, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Name | Beschreibung |
| --- | --- |
| getLookupPaths() | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |

 **Result:**



---


### getFileName{#getFileName}

| Name | Beschreibung |
| --- | --- |
| getFileName() | Der Dateiname der exportierenden/ importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Name | Beschreibung |
| --- | --- |
| setFileName(value) | Der Dateiname der exportierenden/ importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |

 **Result:**



---



