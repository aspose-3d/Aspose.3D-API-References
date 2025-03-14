---
title: Class ColladaSaveOptions
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Formats.ColladaSaveOptions class. Save options for collada
type: docs
weight: 1070
url: /net/aspose.threed.formats/colladasaveoptions/
---
## ColladaSaveOptions class

Save options for collada

```csharp
public class ColladaSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ColladaSaveOptions](colladasaveoptions/)() | Constructor of `ColladaSaveOptions` |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Gets or sets the default encoding for text-based files. Default value is null which means the importer/exporter will decide which encoding to use. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Try to copy textures used in scene to output directory. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Gets the file format that specified in current Save/Load option. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | The file name of the exporting/importing scene. This is optional, but useful when serialize external assets like OBJ's material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Allow user to handle how to manage the external dependencies during load/save. |
| [Indented](../../aspose.threed.formats/colladasaveoptions/indented/) { get; set; } | Gets or sets whether the exported XML document is indented. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Some files like OBJ depends on external file, the lookup paths will allows Aspose.3D to look for external file to load. |
| [TransformStyle](../../aspose.threed.formats/colladasaveoptions/transformstyle/) { get; set; } | Gets or sets the style of node transformation |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


