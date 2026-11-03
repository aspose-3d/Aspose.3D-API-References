---
title: "Klasse GltfSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.GltfSaveOptions Klasse. Speicheroptionen für das glTF-Format"
type: docs
weight: 1280
url: /de/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

Speicheroptionen für das glTF-Format.

```csharp
public class GltfSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | Konstruktor von `GltfSaveOptions` |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | Konstruktor von `GltfSaveOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | Wende [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) auf das Mesh an. Standardwert ist false. |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | Der Dateiname der externen Pufferdatei, die zum Speichern binärer Daten verwendet wird. Wenn diese Datei nicht angegeben ist, erzeugt Aspose.3D einen Namen für Sie. Dies wird ignoriert, wenn glTF im Binärmodus exportiert wird. |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | Liest oder setzt, ob die Draco-Kompression aktiviert werden soll |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | Betten Sie alle externen Assets als Base64 in eine einzelne Datei im ASCII-Modus ein, Standardwert ist false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | Verwenden Sie einen externen Draco-Encoder, um die Draco-Kompressionsgeschwindigkeit zu erhöhen. |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | Wenn der GLTF2-Exporter einen ungültigen Normalenvektor erkennt, wird dieser stattdessen anstelle des ursprünglichen Werts verwendet, um die Validierung zu umgehen. Standardwert ist (0, 1, 0) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | Umdrehen der Texturkoordinate v(t)-Komponente, Standardwert ist true. |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | Standard‑glTF unterstützt nur PNG/JPG als Texturformat; diese Option bestimmt, wie Aspose.3D nicht standardmäßige Bilder während des Exports in ein unterstütztes Format konvertiert. Standardwert ist Png. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | Benutzerdefinierter Konverter, um das Material der Geometrie in ein PBR-Material zu konvertieren. Wenn dies nicht zugewiesen ist, konvertiert der glTF‑2.0‑Exporter das Standardmaterial automatisch in ein PBR-Material. Standardwert ist null. Diese Eigenschaft wird beim Export einer Szene in eine glTF‑2.0‑Datei verwendet. |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | Der JSON-Inhalt der GLTF-Datei ist für die menschliche Lesbarkeit eingerückt, Standardwert ist false |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | Speichern Sie die dynamischen Eigenschaften des Szenenobjekts in 'extra'-Felder in der erzeugten glTF-Datei. Dies ist nützlich, um anwendungsspezifische Daten bereitzustellen. Der Standardwert ist false. |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | Serialisieren Sie Materialien mithilfe der KHR‑Common‑Material‑Erweiterungen, der Standardwert ist false. Wenn Sie dies auf false setzen, führt dies dazu, dass Aspose.3D ein Satz von Vertex/Fragment‑Shadern exportiert, wenn ExportShaders aktiviert ist. |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


