---
title: GltfSaveOptions
second_title: Aspose.3D für .NET-API-Referenz
description: Speicheroptionen für das glTFFormat.
type: docs
weight: 1160
url: /de/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

Speicheroptionen für das glTF-Format.

```csharp
public class GltfSaveOptions : SaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions#constructor)(FileContentType) | Konstrukteur von[`GltfSaveOptions`](../gltfsaveoptions) |
| [GltfSaveOptions](gltfsaveoptions#constructor_1)(FileFormat) | Konstrukteur von[`GltfSaveOptions`](../gltfsaveoptions) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile) { get; set; } | Der Dateiname der externen Pufferdatei, die zum Speichern von Binärdaten verwendet wird. Wenn diese Datei nicht angegeben wird, generiert Aspose.3D einen Namen für Sie. Dies wird ignoriert, wenn glTF im Binärmodus exportiert wird. |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression) { get; set; } | Ruft ab oder legt fest, ob Draco-Komprimierung aktiviert werden soll |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets) { get; set; } | Betten Sie alle externen Assets als base64 in eine einzelne Datei im ASCII-Modus ein, der Standardwert ist „false“. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Ruft die Standardcodierung für textbasierte Dateien ab oder legt sie fest. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter entscheidet, welche Codierung verwendet wird. |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder) { get; set; } | Verwenden Sie einen externen Draco-Encoder, um die Draco-Komprimierungsgeschwindigkeit zu beschleunigen. |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal) { get; set; } | Wenn der GLTF2-Exporter einen ungültigen Normalwert erkannt hat, wird dieser anstelle seines ursprünglichen Werts verwendet, um die Validierung zu umgehen. Der Standardwert ist (0, 1, 0) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Ruft das Dateiformat ab, das in der aktuellen Option Speichern/Laden angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Der Dateiname der Export-/Importszene. Dies ist optional, aber nützlich, wenn externe Assets wie OBJ-Material serialisiert werden. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Dem Benutzer erlauben, die externen Abhängigkeiten während des Ladens/Speicherns zu verwalten. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv) { get; set; } | Komponente v(t) der Texturkoordinate umkehren, Standardwert ist wahr. |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat) { get; set; } | Standard glTF unterstützt nur PNG/JPG als Texturformat, diese Option steuert, wie Aspose.3D die nicht standardmäßigen Bilder während des Exports in ein unterstütztes Format konvertiert. Der Standardwert istPng |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Einige Dateien wie OBJ hängen von einer externen Datei ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter) { get; set; } | Benutzerdefinierter Konverter zum Konvertieren des Geometriematerials in PBR-Material Wenn dies nicht zugewiesen ist, konvertiert der glTF 2.0-Exporter das Standardmaterial automatisch in PBR-Material. Der Standardwert ist null Diese Eigenschaft wird beim Exportieren einer Szene in eine glTF 2.0-Datei verwendet. |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint) { get; set; } | Der JSON-Inhalt der GLTF-Datei ist für das menschliche Lesen eingerückt, der Standardwert ist false |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras) { get; set; } | Speichern Sie die dynamischen Eigenschaften des Szenenobjekts in „zusätzlichen“ Feldern in der generierten glTF-Datei. Dies ist nützlich, um anwendungsspezifische Daten bereitzustellen. Der Standardwert ist „false“. |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials) { get; set; } | Serialisiert Materialien mit KHR Common Material Extensions, der Standardwert ist „false“. Wenn Sie dies auf „false“ setzen, exportiert Aspose.3D einen Satz von Vertex/Fragment-Shadern, wennExportShaders |

### Siehe auch

* class [SaveOptions](../saveoptions)
* namensraum [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
