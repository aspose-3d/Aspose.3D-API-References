---
title: RvmSaveOptions
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 1330
url: /net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Save options for Aveva PDMS RVM file.

```csharp
public class RvmSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions)() | Constructor of [`RvmSaveOptions`](../rvmsaveoptions) |
| [RvmSaveOptions](rvmsaveoptions)(FileContentType) | Constructor of [`RvmSaveOptions`](../rvmsaveoptions) |

## Properties

| Name | Description |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile) { get; set; } | Gets or sets the file name of attribute list file, exporter will generate a name based on the .rvm file name when this property is undefined, default value is null. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix) { get; set; } | Gets or sets the prefix of which attributes that will be exported, the exported property will contains no prefix, custom properties with different prefix will not be exported, default value is 'rvm:'. For example if a property is rvm:Refno=345, the exported attribute will be Refno = 345, the prefix is stripped. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author) { get; set; } | Author information, default value is '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime) { get; set; } | The timestamp that exported this file, default value is current time |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Gets or sets the default encoding for text-based files. Default value is null which means the importer/exporter will decide which encoding to use. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes) { get; set; } | Gets or sets whether to export the attribute list to an external .att file, default value is false. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Gets the file format that specified in current Save/Load option. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | The file name of the exporting/importing scene. This is optional, but useful when serialize external assets like OBJ's material. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote) { get; set; } | File note in the file header. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Allow user to handle how to manage the external dependencies during load/save. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Some files like OBJ depends on external file, the lookup paths will allows Aspose.3D to look for external file to load. |

### See Also

* class [SaveOptions](../saveoptions)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
