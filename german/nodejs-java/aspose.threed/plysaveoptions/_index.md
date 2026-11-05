---
title: "PlySaveOptions"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Speicheroptionen für den Export einer Szene als PLY-Datei.


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
| getPointCloud() | Exportiert die Szene als Punktwolke, der Standardwert ist false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Name | Beschreibung |
| --- | --- |
| setPointCloud(value) | Exportiert die Szene als Punktwolke, der Standardwert ist false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Name | Beschreibung |
| --- | --- |
| getFlipCoordinate() | Kippt die Koordinate beim Speichern der Szene, der Standardwert ist true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Name | Beschreibung |
| --- | --- |
| setFlipCoordinate(value) | Kippt die Koordinate beim Speichern der Szene, der Standardwert ist true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Name | Beschreibung |
| --- | --- |
| getVertexElement() | Der Elementname für die Vertex-Daten, der Standardwert ist "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Name | Beschreibung |
| --- | --- |
| setVertexElement(value) | Der Elementname für die Vertex-Daten, der Standardwert ist "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Name | Beschreibung |
| --- | --- |
| getPositionComponents() | Die Komponentenbezeichnungen für Positionsdaten, der Standardwert ist ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Name | Beschreibung |
| --- | --- |
| getNormalComponents() | Die Komponentenbezeichnungen für Normaldaten, der Standardwert ist ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Name | Beschreibung |
| --- | --- |
| getTextureCoordinateComponents() | Die Komponentenbezeichnungen für Texturkoordinatendaten, der Standardwert ist ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Name | Beschreibung |
| --- | --- |
| getColorComponents() | Die Komponentenbezeichnungen für Vertex-Farbe, der Standardwert ist ("red", "green", "blue") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Name | Beschreibung |
| --- | --- |
| getFaceElement() | Der Elementname für die Face-Daten, der Standardwert ist "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Name | Beschreibung |
| --- | --- |
| setFaceElement(value) | Der Elementname für die Face-Daten, der Standardwert ist "face" |

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
| getExportTextures() | Versuchen Sie, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Name | Beschreibung |
| --- | --- |
| setExportTextures(value) | Versuchen Sie, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Name | Beschreibung |
| --- | --- |
| getFileFormat() | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |

 **Result:**



---


### getEncoding{#getEncoding}

| Name | Beschreibung |
| --- | --- |
| getEncoding() | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Name | Beschreibung |
| --- | --- |
| getFileSystem() | Ermöglicht dem Benutzer, zu steuern, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Name | Beschreibung |
| --- | --- |
| setFileSystem(value) | Ermöglicht dem Benutzer, zu steuern, wie externe Abhängigkeiten beim Laden/Speichern verwaltet werden. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Name | Beschreibung |
| --- | --- |
| getLookupPaths() | Einige Dateien wie OBJ hängen von externen Dateien ab; die Suchpfade ermöglichen Aspose.3D, nach externen Dateien zum Laden zu suchen. |

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



