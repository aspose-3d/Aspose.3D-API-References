---
title: Class FbxSaveOptions
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Formats.FbxSaveOptions class. Save options for Fbx file
type: docs
weight: 1150
url: /net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Save options for Fbx file.

```csharp
public class FbxSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | Initialize a `FbxSaveOptions` using latest supported version. |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | Initializes a `FbxSaveOptions` |

## Properties

| Name | Description |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | Gets or sets whether to embed the texture to the final output file. FBX Exporter will try to find the texture's raw data from [`FileSystem`](../ioconfig/filesystem/), and embed the file to final FBX file. Default value is false. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | Compression large binary data in the FBX file(e.g. animation data, control points, vertex element data, indices), default value is true. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Gets or sets the default encoding for text-based files. Default value is null which means the importer/exporter will decide which encoding to use. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | Gets or sets whether export legacy material properties, used for back compatibility. This option is turned on by default. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Try to copy textures used in scene to output directory. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Gets the file format that specified in current Save/Load option. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | The file name of the exporting/importing scene. This is optional, but useful when serialize external assets like OBJ's material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Allow user to handle how to manage the external dependencies during load/save. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | Gets or sets whether reuse repeated curve data by increasing last data's ref count |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | Gets or sets whether always generate a [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) for geometries if the attached node contains materials. This is turned off by default. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Some files like OBJ depends on external file, the lookup paths will allows Aspose.3D to look for external file to load. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | Reuse the mesh for the primitives with same parameters, this will significantly reduce the size of FBX output which scene was constructed by large set of primitive shapes(like imported from CAD files). Default value is false |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | Gets or sets whether generate a Video instance for [`Texture`](../../aspose.threed.shading/texture/) when exporting as FBX. |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


