---
title: "Klasse FbxLoadOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.FbxLoadOptions Klasse. Ladeoptionen für das FBX‑Format"
type: docs
weight: 1170
url: /de/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Ladeoptionen für das FBX-Format.

```csharp
public class FbxLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | Konstruktor von `FbxLoadOptions` |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | Konstruktor von `FbxLoadOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | Liest oder setzt, ob der Kompatibilitätsmodus aktiviert werden soll. Der Kompatibilitätsmodus versucht, nicht‑standardmäßige FBX‑Definitionen wie von Blender exportierte PBR‑Materialien zu unterstützen. Standardwert ist false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | Liest oder setzt, ob die eingebauten Eigenschaften in GlobalSettings beibehalten werden sollen, die eine native Eigenschaftsersetzung in [`AssetInfo`](../../aspose.threed/assetinfo/) haben. Setzen Sie dies auf true, wenn Sie die vollständigen Eigenschaften in GlobalSettings wünschen. Standardwert ist false |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |

### Siehe auch

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


