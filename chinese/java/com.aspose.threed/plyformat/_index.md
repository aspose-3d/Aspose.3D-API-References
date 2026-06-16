---
title: "PlyFormat"
second_title: "Aspose.3D for Java API 参考"
description: "PLY 格式。"
type: docs
weight: 129
url: /zh/java/com.aspose.threed/plyformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class PlyFormat extends FileFormat
```

PLY 格式。 **示例:** 以下代码展示了如何从 PLY 文件解码网格：

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [AMF](#AMF) | 增材制造文件格式 |
| [ASE](#ASE) | 3D Studio Max 的 ASCII 场景导出器格式。 |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D Web 格式。 |
| [BLENDER](#BLENDER) | Blender 的 3D 文件格式 |
| [COLLADA](#COLLADA) | Collada 文件格式 |
| [DISCREET3DS](#DISCREET3DS) | 3D Studio 的文件格式 |
| [DRACO](#DRACO) | Google Draco 网格 |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX 文件格式，版本 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | 二进制 FBX 文件格式，版本 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX 文件格式，版本 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | 二进制 FBX 文件格式，版本 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX 文件格式，版本 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | 二进制 FBX 文件格式，版本 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX 文件格式，版本 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | 二进制 FBX 文件格式，版本 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | ASCII FBX 文件格式，版本为 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Binary FBX 文件格式，版本为 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | ASCII FBX 文件格式，版本为 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Binary FBX 文件格式，版本为 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | ASCII FBX 文件格式，版本为 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Binary FBX 文件格式，版本为 7.7.0 |
| [GLTF](#GLTF) | Khronos Group 的 glTF |
| [GLTF2](#GLTF2) | Khronos Group 的 glTF 2.0 版 |
| [GLTF2_BINARY](#GLTF2-BINARY) | Khronos Group 的 glTF 2.0 版 |
| [GLTF_BINARY](#GLTF-BINARY) | Khronos Group 的 glTF（二进制格式） |
| [HTML5](#HTML5) | HTML5 文件 |
| [IFC](#IFC) | ISO 16739-1 行业基础类数据模型。 |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya（ASCII 格式） |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya（Binary 格式） |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D 制造格式 |
| [PCD](#PCD) | PCL 点云数据文件（ASCII 模式） |
| [PCD_BINARY](#PCD-BINARY) | PCL 点云数据文件（Binary 模式） |
| [PDF](#PDF) | Adobe 的可移植文档格式 |
| [PLY](#PLY) | 多边形文件格式或 Stanford 三角形格式 |
| [RVM_BINARY](#RVM-BINARY) | AVEVA Plant Design Management System 模型（二进制格式） |
| [RVM_TEXT](#RVM-TEXT) | AVEVA Plant Design Management System 模型（文本格式） |
| [SIEMENSJT8](#SIEMENSJT8) | Siemens JT 文件版本 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Siemens JT 文件版本 9 |
| [STLASCII](#STLASCII) | ASCII STL 文件格式 |
| [STL_BINARY](#STL-BINARY) | Binary STL 文件格式 |
| [UNIVERSAL3D](#UNIVERSAL3D) | Universal3D 文件格式 |
| [USD](#USD) | 通用场景描述 |
| [USDA](#USDA) | ASCII 格式的通用场景描述。 |
| [USDZ](#USDZ) | 压缩的通用场景描述 |
| [VRML](#VRML) | 虚拟现实建模语言 |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Wavefront 的 Obj 文件格式 |
| [XYZ](#XYZ) | Xyz 点云文件 |
| [X_BINARY](#X-BINARY) | 二进制格式的 DirectX X 文件 |
| [X_TEXT](#X-TEXT) | 二进制格式的 DirectX X 文件 |
| [ZIP](#ZIP) | 包含其他 3D 文件格式的 Zip 存档。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | 为此文件格式创建默认加载选项 |
| [createSaveOptions()](#createSaveOptions--) | 为此文件格式创建默认保存选项 |
| [decode(Stream stream)](#decode-com.aspose.threed.Stream-) | 从指定的流中解码点云或网格。 |
| [decode(Stream stream, PlyLoadOptions opt)](#decode-com.aspose.threed.Stream-com.aspose.threed.PlyLoadOptions-) | 从指定的流中解码点云或网格。 |
| [decode(String fileName)](#decode-java.lang.String-) | 从指定的流中解码点云或网格。 |
| [decode(String fileName, PlyLoadOptions opt)](#decode-java.lang.String-com.aspose.threed.PlyLoadOptions-) | 从指定的流中解码点云或网格。 |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | 从数据流检测文件格式，文件名是可选的，用于猜测没有魔术头的类型。 |
| [detect(String fileName)](#detect-java.lang.String-) | 从文件名检测文件格式，文件必须可读，以便 Aspose.3D 能通过文件头检测文件格式。 |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | 对实体进行编码并将结果保存到流中。 |
| [encode(Entity entity, Stream stream, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-) | 对实体进行编码并将结果保存到流中。 |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | 对实体进行编码并将结果保存到外部文件中。 |
| [encode(Entity entity, String fileName, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-) | 对实体进行编码并将结果保存到外部文件中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | 获取 Aspose.3D 是否支持将场景导出为当前文件格式。 |
| [getCanImport()](#getCanImport--) | 获取 Aspose.3D 是否支持从当前文件格式导入场景。 |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | 获取文件格式的内容类型 |
| [getExtension()](#getExtension--) | 获取此类型的扩展名。 |
| [getExtensions()](#getExtensions--) | 获取此类型的扩展名列表。 |
| [getFileFormatType()](#getFileFormatType--) | 获取文件格式类型 |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | 根据文件扩展名获取首选文件格式，扩展名应以点（'.'）开头。 |
| [getFormats()](#getFormats--) | 访问所有受支持的格式 |
| [getVersion()](#getVersion--) | 获取文件格式版本 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 将格式转换为字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


增材制造文件格式

### ASE {#ASE}
```
public static final FileFormat ASE
```


3D Studio Max 的 ASCII 场景导出器格式。

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D Web 格式。

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Blender 的 3D 文件格式

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada 文件格式

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


3D Studio 的文件格式

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Google Draco 网格

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


ASCII FBX 文件格式，版本 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


二进制 FBX 文件格式，版本 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX 文件格式，版本 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


二进制 FBX 文件格式，版本 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX 文件格式，版本 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


二进制 FBX 文件格式，版本 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX 文件格式，版本 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


二进制 FBX 文件格式，版本 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


ASCII FBX 文件格式，版本为 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Binary FBX 文件格式，版本为 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


ASCII FBX 文件格式，版本为 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Binary FBX 文件格式，版本为 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


ASCII FBX 文件格式，版本为 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Binary FBX 文件格式，版本为 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


Khronos Group 的 glTF

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


Khronos Group 的 glTF 2.0 版

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


Khronos Group 的 glTF 2.0 版

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


Khronos Group 的 glTF（二进制格式）

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


HTML5 文件

### IFC {#IFC}
```
public static final FileFormat IFC
```


ISO 16739-1 行业基础类数据模型。

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya（ASCII 格式）

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya（Binary 格式）

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D 制造格式

### PCD {#PCD}
```
public static final FileFormat PCD
```


PCL 点云数据文件（ASCII 模式）

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


PCL 点云数据文件（Binary 模式）

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Adobe 的可移植文档格式

### PLY {#PLY}
```
public static final PlyFormat PLY
```


多边形文件格式或 Stanford 三角形格式

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


AVEVA Plant Design Management System 模型（二进制格式）

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


AVEVA Plant Design Management System 模型（文本格式）

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Siemens JT 文件版本 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Siemens JT 文件版本 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


ASCII STL 文件格式

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Binary STL 文件格式

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Universal3D 文件格式

### USD {#USD}
```
public static final FileFormat USD
```


通用场景描述

### USDA {#USDA}
```
public static final FileFormat USDA
```


ASCII 格式的通用场景描述。

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


压缩的通用场景描述

### VRML {#VRML}
```
public static final FileFormat VRML
```


虚拟现实建模语言

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Wavefront 的 Obj 文件格式

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Xyz 点云文件

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


二进制格式的 DirectX X 文件

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


二进制格式的 DirectX X 文件

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


包含其他 3D 文件格式的 Zip 存档。

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


为此文件格式创建默认加载选项

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


为此文件格式创建默认保存选项

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### decode(Stream stream) {#decode-com.aspose.threed.Stream-}
```
public Geometry decode(Stream stream)
```


从指定的流中解码点云或网格。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流 |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### decode(Stream stream, PlyLoadOptions opt) {#decode-com.aspose.threed.Stream-com.aspose.threed.PlyLoadOptions-}
```
public Geometry decode(Stream stream, PlyLoadOptions opt)
```


从指定的流中解码点云或网格。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流 |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | PLY 格式的加载选项 |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### decode(String fileName) {#decode-java.lang.String-}
```
public Geometry decode(String fileName)
```


从指定的流中解码点云或网格。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 输入流 |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### decode(String fileName, PlyLoadOptions opt) {#decode-java.lang.String-com.aspose.threed.PlyLoadOptions-}
```
public Geometry decode(String fileName, PlyLoadOptions opt)
```


从指定的流中解码点云或网格。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 输入流 |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | PLY 格式的加载选项 |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


从数据流检测文件格式，文件名是可选的，用于猜测没有魔术头的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 包含用于检测的数据流 |
| 文件名 | java.lang.String | 数据的原始文件名，用作提示。 |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


从文件名检测文件格式，文件必须可读，以便 Aspose.3D 能通过文件头检测文件格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 用于检测文件格式的文件路径。 |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### encode(Entity entity, Stream stream) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-}
```
public void encode(Entity entity, Stream stream)
```


对实体进行编码并将结果保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 要编码的实体 |
|  | stream | [Stream](../../com.aspose.threed/stream) | 写入的流，此方法不会关闭此流 **Example:** 以下代码展示了如何将网格编码为 PLY 文件： |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, Stream stream, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, Stream stream, PlySaveOptions opt)
```


对实体进行编码并将结果保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 要编码的实体 |
| stream | [Stream](../../com.aspose.threed/stream) | 写入的流，此方法不会关闭此流 |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | 保存选项 **Example:** 以下代码展示了如何将网格编码为 PLY 文件： |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


对实体进行编码并将结果保存到外部文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 要编码的实体 |
|  | 文件名 | java.lang.String | 写入的文件 **Example:** 以下代码展示了如何将网格编码为 PLY 文件： |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, String fileName, PlySaveOptions opt)
```


对实体进行编码并将结果保存到外部文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 要编码的实体 |
| 文件名 | java.lang.String | 写入的文件 |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | 保存选项 **Example:** 以下代码展示了如何将网格编码为 PLY 文件： |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


获取 Aspose.3D 是否支持将场景导出为当前文件格式。

**Returns:**
boolean - 是否 Aspose.3D 支持将场景导出为当前文件格式。**Example:** 以下代码展示了如何检查是否支持导出到指定格式。

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanExport())
         System.out.printf("Can export to %s", outputFormat);
```
### getCanImport() {#getCanImport--}
```
public boolean getCanImport()
```


获取 Aspose.3D 是否支持从当前文件格式导入场景。

**Returns:**
boolean - 是否 Aspose.3D 支持从当前文件格式导入场景。**Example:** 以下代码展示了如何检查是否支持从指定格式导入。

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanImport())
         System.out.printf("Can import from %s", outputFormat);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentType() {#getContentType--}
```
public FileContentType getContentType()
```


获取文件格式的内容类型

**Returns:**
[FileContentType](../../com.aspose.threed/filecontenttype) - file format content type **Example:**

```
var format = FileFormat.MAYA_BINARY;
     if (format.getContentType() == FileContentType.BINARY)
         System.out.printf("%s is binary format", format);
     else
         System.out.printf("%s is text-based format", format);
```
### getExtension() {#getExtension--}
```
public String getExtension()
```


获取此类型的扩展名。

**Returns:**
java.lang.String - 此类型的扩展名。**Example:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


获取此类型的扩展名列表。

**Returns:**
java.lang.String[] - 此类型的扩展名列表。
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


获取文件格式类型

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


根据文件扩展名获取首选文件格式，扩展名应以点（'.'）开头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extensionName | java.lang.String | 扩展名以 '.' 开头以进行查询。 |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - Instance of [FileFormat](../../com.aspose.threed/fileformat), otherwise null returned. **Example:** The following code shows how to save scene to memory using specified format

```
Scene scene = new Scene(new Box());
     var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     var output = new ByteArrayOutputStream();
     scene.save(output);
```
### getFormats() {#getFormats--}
```
public static List<FileFormat> getFormats()
```


访问所有受支持的格式

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - 访问所有受支持的格式
### getVersion() {#getVersion--}
```
public Version getVersion()
```


获取文件格式版本

**Returns:**
[Version](../../com.aspose.threed/version) - file format version
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


将格式转换为字符串

**Returns:**
java.lang.String - 对象字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

