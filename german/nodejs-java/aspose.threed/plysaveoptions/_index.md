---
title: PlySaveOptions
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Speicheroptionen für den Export der Szene als PLY-Datei.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor von PlySaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(contentType) | Konstruktor von PlySaveOptions |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| Name | Beschreibung |
| --- | --- |
| getPointCloud() | Die Szene als Punktwolke exportieren, der Standardwert ist false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Name | Beschreibung |
| --- | --- |
| setPointCloud(value) | Die Szene als Punktwolke exportieren, der Standardwert ist false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Name | Beschreibung |
| --- | --- |
| getFlipCoordinate() | Koordinaten beim Speichern der Szene umkehren, Standardwert ist true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Name | Beschreibung |
| --- | --- |
| setFlipCoordinate(value) | Koordinaten beim Speichern der Szene umkehren, Standardwert ist true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Name | Beschreibung |
| --- | --- |
| getVertexElement() | Der Elementname für die Vertexdaten, Standardwert ist "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Name | Beschreibung |
| --- | --- |
| setVertexElement(value) | Der Elementname für die Vertexdaten, Standardwert ist "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Name | Beschreibung |
| --- | --- |
| getPositionComponents() | Die Komponentenbezeichnungen für Positionsdaten, Standardwert ist ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Name | Beschreibung |
| --- | --- |
| getNormalComponents() | Die Komponentenbezeichnungen für Normaldaten, Standardwert ist ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Name | Beschreibung |
| --- | --- |
| getTextureCoordinateComponents() | Die Komponentenbezeichnungen für Texturkoordinatendaten, Standardwert ist ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Name | Beschreibung |
| --- | --- |
| getColorComponents() | Die Komponentenbezeichnungen für Vertex‑Farbe, Standardwert ist ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Name | Beschreibung |
| --- | --- |
| getFaceElement() | Der Elementname für die Flächendaten, Standardwert ist "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Name | Beschreibung |
| --- | --- |
| setFaceElement(value) | Der Elementname für die Flächendaten, Standardwert ist "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Name | Beschreibung |
| --- | --- |
| getFaceProperty() | Der Name der Eigenschaft für die Face-Daten, Standardwert ist "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Name | Beschreibung |
| --- | --- |
| setFaceProperty(value) | Der Name der Eigenschaft für die Face-Daten, Standardwert ist "vertex_index" |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Name | Beschreibung |
| --- | --- |
| getExportTextures() | Versucht, im Szene verwendete Texturen in das Ausgabeverzeichnis zu kopieren. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Name | Beschreibung |
| --- | --- |
| setExportTextures(value) | Versucht, im Szene verwendete Texturen in das Ausgabeverzeichnis zu kopieren. |

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



