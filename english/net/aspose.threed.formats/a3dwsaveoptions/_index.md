---
title: Class A3dwSaveOptions
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Formats.A3dwSaveOptions class. Save options for A3DW format
type: docs
weight: 1050
url: /net/aspose.threed.formats/a3dwsaveoptions/
---
## A3dwSaveOptions class

Save options for A3DW format.

```csharp
public class A3dwSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [A3dwSaveOptions](a3dwsaveoptions/)() | Constructor of `A3dwSaveOptions` |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Gets or sets the default encoding for text-based files. Default value is null which means the importer/exporter will decide which encoding to use. |
| [ExportMetaData](../../aspose.threed.formats/a3dwsaveoptions/exportmetadata/) { get; set; } | Export meta data associated with Scene/Node to client Default value is true |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Try to copy textures used in scene to output directory. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Gets the file format that specified in current Save/Load option. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | The file name of the exporting/importing scene. This is optional, but useful when serialize external assets like OBJ's material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Allow user to handle how to manage the external dependencies during load/save. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Some files like OBJ depends on external file, the lookup paths will allows Aspose.3D to look for external file to load. |
| [MetaDataPrefix](../../aspose.threed.formats/a3dwsaveoptions/metadataprefix/) { get; set; } | If this property is non-null, only the properties of Scene/Node that start with this prefix will be exported, and the prefix will be removed. |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


