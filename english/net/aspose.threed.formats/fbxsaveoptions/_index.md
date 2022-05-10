---
title: FbxSaveOptions
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 1120
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
| [FbxSaveOptions](fbxsaveoptions)(FileContentType) | Initialize a [`FbxSaveOptions`](../fbxsaveoptions) using latest supported version. |
| [FbxSaveOptions](fbxsaveoptions)(FileFormat) | Initializes a [`FbxSaveOptions`](../fbxsaveoptions) |

## Properties

| Name | Description |
| --- | --- |
| [EmbedTextures](embedtextures) { get; set; } | Gets or sets whether to embed the texture to the final output file. FBX Exporter will try to find the texture's raw data from [`FileSystem`](../ioconfig/filesystem), and embed the file to final FBX file. Default value is false. |
| [EnableCompression](enablecompression) { get; set; } | Compression large binary data in the FBX file(e.g. animation data, control points, vertex element data, indices), default value is true. |
| [ExportLegacyMaterialProperties](exportlegacymaterialproperties) { get; set; } | Gets or sets whether export legacy material properties, used for back compatibility. This option is turned on by default. |
| [FoldRepeatedCurveData](foldrepeatedcurvedata) { get; set; } | Gets or sets whether reuse repeated curve data by increasing last data's ref count |
| [GenerateVertexElementMaterial](generatevertexelementmaterial) { get; set; } | Gets or sets whether always generate a [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial) for geometries if the attached node contains materials. This is turned off by default. |
| [ReusePrimitiveMesh](reuseprimitivemesh) { get; set; } | Reuse the mesh for the primitives with same parameters, this will significantly reduce the size of FBX output which scene was constructed by large set of primitive shapes(like imported from CAD files). Default value is false |
| [VideoForTexture](videofortexture) { get; set; } | Gets or sets whether generate a Video instance for [`Texture`](../../aspose.threed.shading/texture) when exporting as FBX. |

### See Also

* class [SaveOptions](../saveoptions)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->