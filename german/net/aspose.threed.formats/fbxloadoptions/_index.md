---
title: FbxLoadOptions
second_title: Aspose.3D für .NET-API-Referenz
description: Ladeoptionen für das FbxFormat.
type: docs
weight: 1110
url: /de/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Ladeoptionen für das Fbx-Format.

```csharp
public class FbxLoadOptions : LoadOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions#constructor)() | Konstrukteur von[`FbxLoadOptions`](../fbxloadoptions) |
| [FbxLoadOptions](fbxloadoptions#constructor_1)(FileFormat) | Konstrukteur von[`FbxLoadOptions`](../fbxloadoptions) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Ruft die Standardcodierung für textbasierte Dateien ab oder legt sie fest. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter entscheidet, welche Codierung verwendet wird. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Ruft das Dateiformat ab, das in der aktuellen Option Speichern/Laden angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Der Dateiname der Export-/Importszene. Dies ist optional, aber nützlich, wenn externe Assets wie OBJ-Material serialisiert werden. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Dem Benutzer erlauben, die externen Abhängigkeiten während des Ladens/Speicherns zu verwalten. |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings) { get; set; } | Ruft ab oder legt fest, ob die integrierten Eigenschaften in GlobalSettings beibehalten werden sollen, die einen nativen Eigenschaftsersatz enthalten[`AssetInfo`](../../aspose.threed/assetinfo) . Setzen Sie dies auf „true“, wenn Sie die vollständigen Eigenschaften in GlobalSettings haben möchten. Der Standardwert ist „false “. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Einige Dateien wie OBJ hängen von einer externen Datei ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |

### Siehe auch

* class [LoadOptions](../loadoptions)
* namensraum [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
