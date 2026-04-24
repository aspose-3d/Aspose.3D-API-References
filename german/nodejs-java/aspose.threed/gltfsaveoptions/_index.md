---
title: GltfSaveOptions
second_title: Aspose.3D für Node.js via Java API-Referenz
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
| Konstruktor(contentType) | Konstruktor von GltfSaveOptions |

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
| Form | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Name | Beschreibung |
| --- | --- |
| getPrettyPrint() | Der JSON‑Inhalt der GLTF‑Datei ist für die Lesbarkeit durch Menschen eingerückt, Standardwert ist false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Name | Beschreibung |
| --- | --- |
| setPrettyPrint(value) | Der JSON‑Inhalt der GLTF‑Datei ist für die Lesbarkeit durch Menschen eingerückt, Standardwert ist false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Name | Beschreibung |
| --- | --- |
| getFallbackNormal() | Wenn der GLTF2‑Exporter eine ungültige Normale erkennt, wird dieser Wert anstelle des ursprünglichen Wertes verwendet, um die Validierung zu umgehen. Standardwert ist (0, 1, 0). |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Name | Beschreibung |
| --- | --- |
| getEmbedAssets() | Betten Sie alle externen Assets als Base64 in eine einzelne Datei im ASCII‑Modus ein, der Standardwert ist false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Name | Beschreibung |
| --- | --- |
| setEmbedAssets(value) | Betten Sie alle externen Assets als Base64 in eine einzelne Datei im ASCII‑Modus ein, der Standardwert ist false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Name | Beschreibung |
| --- | --- |
| getImageFormat() | Standard‑glTF unterstützt nur PNG/JPG als Texturformat; diese Option bestimmt, wie Aspose.3D nicht‑standardmäßige Bilder während des Exports in ein unterstütztes Format konvertiert. Der Standardwert ist GltfEmbeddedImageFormat.PNG. Der Wert der Eigenschaft ist die Ganzzahlkonstante GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Name | Beschreibung |
| --- | --- |
| setImageFormat(value) | Standard‑glTF unterstützt nur PNG/JPG als Texturformat; diese Option bestimmt, wie Aspose.3D nicht‑standardmäßige Bilder während des Exports in ein unterstütztes Format konvertiert. Der Standardwert ist GltfEmbeddedImageFormat.PNG. Der Wert der Eigenschaft ist die Ganzzahlkonstante GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Name | Beschreibung |
| --- | --- |
| getMaterialConverter() | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR‑Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der glTF 2.0‑Exporter das Standardmaterial automatisch in ein PBR‑Material. Standardwert ist null. Diese Eigenschaft wird beim Export einer Szene in eine glTF 2.0‑Datei verwendet. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Name | Beschreibung |
| --- | --- |
| setMaterialConverter(value) | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR‑Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der glTF 2.0‑Exporter das Standardmaterial automatisch in ein PBR‑Material. Standardwert ist null. Diese Eigenschaft wird beim Export einer Szene in eine glTF 2.0‑Datei verwendet. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Name | Beschreibung |
| --- | --- |
| getUseCommonMaterials() | Serialisiert Materialien mithilfe der KHR‑Common‑Material‑Erweiterungen, Standardwert ist false. Setzt man dies auf false, führt dies dazu, dass Aspose.3D ein Satz von Vertex‑/Fragment‑Shadern exportiert, wenn #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Name | Beschreibung |
| --- | --- |
| setUseCommonMaterials(value) | Serialisiert Materialien mithilfe der KHR‑Common‑Material‑Erweiterungen, Standardwert ist false. Setzt man dies auf false, führt dies dazu, dass Aspose.3D ein Satz von Vertex‑/Fragment‑Shadern exportiert, wenn #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Name | Beschreibung |
| --- | --- |
| getExternalDracoEncoder() | Verwendet einen externen Draco‑Encoder, um die Draco‑Komprimierungsgeschwindigkeit zu beschleunigen. Aspose.3D erstellt einen neuen Unterprozess, um das Mesh in das Draco‑Format zu kodieren; verwenden Sie ihn auf eigenes Risiko. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Name | Beschreibung |
| --- | --- |
| setExternalDracoEncoder(value) | Verwendet einen externen Draco‑Encoder, um die Draco‑Komprimierungsgeschwindigkeit zu beschleunigen. Aspose.3D erstellt einen neuen Unterprozess, um das Mesh in das Draco‑Format zu kodieren; verwenden Sie ihn auf eigenes Risiko. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Name | Beschreibung |
| --- | --- |
| getFlipTexCoordV() | Vertauschen Sie die v(t)-Komponente der Texturkoordinate, der Standardwert ist true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Name | Beschreibung |
| --- | --- |
| setFlipTexCoordV(value) | Vertauschen Sie die v(t)-Komponente der Texturkoordinate, der Standardwert ist true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Name | Beschreibung |
| --- | --- |
| getBufferFile() | Der Dateiname der externen Pufferdatei, die zum Speichern binärer Daten verwendet wird. Wenn diese Datei nicht angegeben wird, erzeugt Aspose.3D einen Namen für Sie. Dies wird ignoriert, wenn glTF im Binärmodus exportiert wird. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Name | Beschreibung |
| --- | --- |
| setBufferFile(value) | Der Dateiname der externen Pufferdatei, die zum Speichern binärer Daten verwendet wird. Wenn diese Datei nicht angegeben wird, erzeugt Aspose.3D einen Namen für Sie. Dies wird ignoriert, wenn glTF im Binärmodus exportiert wird. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Name | Beschreibung |
| --- | --- |
| getSaveExtras() | Speichere die dynamischen Eigenschaften des Szenenobjekts in den 'extra'-Feldern der erzeugten glTF‑Datei. Dies ist nützlich, um anwendungsspezifische Daten bereitzustellen. Standardwert ist false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Name | Beschreibung |
| --- | --- |
| setSaveExtras(value) | Speichere die dynamischen Eigenschaften des Szenenobjekts in den 'extra'-Feldern der erzeugten glTF‑Datei. Dies ist nützlich, um anwendungsspezifische Daten bereitzustellen. Standardwert ist false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Name | Beschreibung |
| --- | --- |
| getApplyUnitScale() | Wenden Sie AssetInfo.UnitScaleFactor auf das Mesh an. Der Standardwert ist false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Name | Beschreibung |
| --- | --- |
| setApplyUnitScale(value) | Wenden Sie AssetInfo.UnitScaleFactor auf das Mesh an. Der Standardwert ist false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Name | Beschreibung |
| --- | --- |
| getDracoCompression() | Liest oder setzt, ob die Draco-Komprimierung aktiviert werden soll |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Name | Beschreibung |
| --- | --- |
| setDracoCompression(value) | Liest oder setzt, ob die Draco-Komprimierung aktiviert werden soll |

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



