---
title: "GltfSaveOptions"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Speicheroptionen für das glTF-Format.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(contentType) | Konstruktor von GltfSaveOptions |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(format) | Konstruktor von GltfSaveOptions |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Format | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Name | Beschreibung |
| --- | --- |
| getPrettyPrint() | Der JSON-Inhalt der GLTF-Datei ist für die menschliche Lesbarkeit eingerückt, der Standardwert ist false. |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Name | Beschreibung |
| --- | --- |
| setPrettyPrint(value) | Der JSON-Inhalt der GLTF-Datei ist für die menschliche Lesbarkeit eingerückt, der Standardwert ist false. |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Name | Beschreibung |
| --- | --- |
| getFallbackNormal() | Wenn der GLTF2-Exporter einen ungültigen Normalenvektor erkennt, wird dieser stattdessen verwendet, um die Validierung zu umgehen. Der Standardwert ist (0, 1, 0). |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Name | Beschreibung |
| --- | --- |
| getEmbedAssets() | Betten Sie alle externen Assets als Base64 in eine einzelne Datei im ASCII-Modus ein, der Standardwert ist false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Name | Beschreibung |
| --- | --- |
| setEmbedAssets(value) | Betten Sie alle externen Assets als Base64 in eine einzelne Datei im ASCII-Modus ein, der Standardwert ist false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Name | Beschreibung |
| --- | --- |
| getImageFormat() | Standard‑glTF unterstützt nur PNG/JPG als Texturformat, diese Option bestimmt, wie Aspose.3D nicht‑standardmäßige Bilder während des Exports in ein unterstütztes Format konvertiert. Der Standardwert ist GltfEmbeddedImageFormat.PNG. Der Wert der Eigenschaft ist die Ganzzahlkonstante GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Name | Beschreibung |
| --- | --- |
| setImageFormat(value) | Standard‑glTF unterstützt nur PNG/JPG als Texturformat, diese Option bestimmt, wie Aspose.3D nicht‑standardmäßige Bilder während des Exports in ein unterstütztes Format konvertiert. Der Standardwert ist GltfEmbeddedImageFormat.PNG. Der Wert der Eigenschaft ist die Ganzzahlkonstante GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Name | Beschreibung |
| --- | --- |
| getMaterialConverter() | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR‑Material zu konvertieren. Wenn dieser nicht zugewiesen ist, konvertiert der glTF 2.0‑Exporter das Standardmaterial automatisch in ein PBR‑Material. Der Standardwert ist null. Diese Eigenschaft wird beim Export einer Szene in eine glTF 2.0‑Datei verwendet. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Name | Beschreibung |
| --- | --- |
| setMaterialConverter(value) | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR‑Material zu konvertieren. Wenn dieser nicht zugewiesen ist, konvertiert der glTF 2.0‑Exporter das Standardmaterial automatisch in ein PBR‑Material. Der Standardwert ist null. Diese Eigenschaft wird beim Export einer Szene in eine glTF 2.0‑Datei verwendet. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Name | Beschreibung |
| --- | --- |
| getUseCommonMaterials() | Serialisiere Materialien mithilfe der KHR common material extensions, der Standardwert ist false. Setzt man dies auf false, führt dies dazu, dass Aspose.3D ein Satz von Vertex-/Fragment‑Shadern exportiert, wenn #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Name | Beschreibung |
| --- | --- |
| setUseCommonMaterials(value) | Serialisiere Materialien mithilfe der KHR common material extensions, der Standardwert ist false. Setzt man dies auf false, führt dies dazu, dass Aspose.3D ein Satz von Vertex-/Fragment‑Shadern exportiert, wenn #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Name | Beschreibung |
| --- | --- |
| getExternalDracoEncoder() | Verwenden Sie einen externen Draco‑Encoder, um die Draco‑Komprimierungsgeschwindigkeit zu beschleunigen. Aspose.3D erstellt einen neuen Unterprozess, um das Mesh in das Draco‑Format zu kodieren; verwenden Sie ihn auf eigenes Risiko. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Name | Beschreibung |
| --- | --- |
| setExternalDracoEncoder(value) | Verwenden Sie einen externen Draco‑Encoder, um die Draco‑Komprimierungsgeschwindigkeit zu beschleunigen. Aspose.3D erstellt einen neuen Unterprozess, um das Mesh in das Draco‑Format zu kodieren; verwenden Sie ihn auf eigenes Risiko. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Name | Beschreibung |
| --- | --- |
| getFlipTexCoordV() | Drehen Sie die Texturkoordinaten‑Komponente v(t) um, der Standardwert ist true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Name | Beschreibung |
| --- | --- |
| setFlipTexCoordV(value) | Drehen Sie die Texturkoordinaten‑Komponente v(t) um, der Standardwert ist true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Name | Beschreibung |
| --- | --- |
| getBufferFile() | Der Dateiname der externen Pufferdatei, die zum Speichern binärer Daten verwendet wird. Wenn diese Datei nicht angegeben ist, erzeugt Aspose.3D einen Namen für Sie. Dies wird ignoriert, wenn glTF im Binärmodus exportiert wird. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Name | Beschreibung |
| --- | --- |
| setBufferFile(value) | Der Dateiname der externen Pufferdatei, die zum Speichern binärer Daten verwendet wird. Wenn diese Datei nicht angegeben ist, erzeugt Aspose.3D einen Namen für Sie. Dies wird ignoriert, wenn glTF im Binärmodus exportiert wird. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Name | Beschreibung |
| --- | --- |
| getSaveExtras() | Speichert die dynamischen Eigenschaften des Szenenobjekts in den 'extra'-Feldern der erzeugten glTF‑Datei. Dies ist nützlich, um anwendungsspezifische Daten bereitzustellen. Der Standardwert ist false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Name | Beschreibung |
| --- | --- |
| setSaveExtras(value) | Speichert die dynamischen Eigenschaften des Szenenobjekts in den 'extra'-Feldern der erzeugten glTF‑Datei. Dies ist nützlich, um anwendungsspezifische Daten bereitzustellen. Der Standardwert ist false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Name | Beschreibung |
| --- | --- |
| getApplyUnitScale() | Wende AssetInfo.UnitScaleFactor auf das Mesh an. Standardwert ist false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Name | Beschreibung |
| --- | --- |
| setApplyUnitScale(value) | Wende AssetInfo.UnitScaleFactor auf das Mesh an. Standardwert ist false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Name | Beschreibung |
| --- | --- |
| getDracoCompression() | Liest oder legt fest, ob die Draco‑Kompression aktiviert werden soll |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Name | Beschreibung |
| --- | --- |
| setDracoCompression(value) | Liest oder legt fest, ob die Draco‑Kompression aktiviert werden soll |

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



