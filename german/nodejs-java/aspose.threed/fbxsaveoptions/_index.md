---
title: FbxSaveOptions
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Speicheroptionen für die Fbx-Datei.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(format) | Initialisiert ein FbxSaveOptions |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Form | FileFormat | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(contentType) | Initialisiere ein FbxSaveOptions mit der neuesten unterstützten Version. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Name | Beschreibung |
| --- | --- |
| getReusePrimitiveMesh() | Verwenden Sie das Mesh für Primitive mit denselben Parametern erneut, dies reduziert die Größe der FBX-Ausgabe erheblich, wenn die Szene aus einer großen Menge primitiver Formen (wie aus CAD-Dateien importiert) aufgebaut ist. Der Standardwert ist false |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Name | Beschreibung |
| --- | --- |
| setReusePrimitiveMesh(value) | Verwenden Sie das Mesh für Primitive mit denselben Parametern erneut, dies reduziert die Größe der FBX-Ausgabe erheblich, wenn die Szene aus einer großen Menge primitiver Formen (wie aus CAD-Dateien importiert) aufgebaut ist. Der Standardwert ist false |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Name | Beschreibung |
| --- | --- |
| getEnableCompression() | Komprimierung großer Binärdaten in der FBX-Datei (z. B. Animationsdaten, Kontrollpunkte, Vertex-Element-Daten, Indizes), Standardwert ist true. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Name | Beschreibung |
| --- | --- |
| setEnableCompression(value) | Komprimierung großer Binärdaten in der FBX-Datei (z. B. Animationsdaten, Kontrollpunkte, Vertex-Element-Daten, Indizes), Standardwert ist true. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Name | Beschreibung |
| --- | --- |
| getFoldRepeatedCurveData() | Liest oder setzt, ob wiederholte Kurvendaten wiederverwendet werden, indem der Referenzzähler der letzten Daten erhöht wird; true, wenn wiederholte Kurvendaten gefaltet werden; andernfalls false. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Name | Beschreibung |
| --- | --- |
| getExportLegacyMaterialProperties() | Liest oder setzt, ob Legacy-Materialeigenschaften exportiert werden, verwendet für die Rückwärtskompatibilität. Diese Option ist standardmäßig aktiviert. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Name | Beschreibung |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Liest oder setzt, ob Legacy-Materialeigenschaften exportiert werden, verwendet für die Rückwärtskompatibilität. Diese Option ist standardmäßig aktiviert. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Name | Beschreibung |
| --- | --- |
| getVideoForTexture() | Liest oder setzt, ob eine Video-Instanz für Textur beim Exportieren als FBX erzeugt wird. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Name | Beschreibung |
| --- | --- |
| setVideoForTexture(value) | Liest oder setzt, ob eine Video-Instanz für Textur beim Exportieren als FBX erzeugt wird. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Name | Beschreibung |
| --- | --- |
| getEmbedTextures() | Liest oder setzt, ob die Textur in die endgültige Ausgabedatei eingebettet werden soll. Der FBX Exporter versucht, die Rohdaten der Textur aus dem FileSystem zu finden und die Datei in die endgültige FBX file einzubetten. Der Standardwert ist false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Name | Beschreibung |
| --- | --- |
| setEmbedTextures(value) | Liest oder setzt, ob die Textur in die endgültige Ausgabedatei eingebettet werden soll. Der FBX Exporter versucht, die Rohdaten der Textur aus dem FileSystem zu finden und die Datei in die endgültige FBX file einzubetten. Der Standardwert ist false. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Name | Beschreibung |
| --- | --- |
| getGenerateVertexElementMaterial() | Liest oder setzt, ob immer ein VertexElementMaterial für Geometrien erzeugt wird, wenn der angehängte Knoten Materialien enthält. Dies ist standardmäßig deaktiviert. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Name | Beschreibung |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Liest oder setzt, ob immer ein VertexElementMaterial für Geometrien erzeugt wird, wenn der angehängte Knoten Materialien enthält. Dies ist standardmäßig deaktiviert. |

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



