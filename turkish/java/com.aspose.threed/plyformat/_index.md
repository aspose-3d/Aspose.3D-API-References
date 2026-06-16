---
title: "PlyFormat"
second_title: "Aspose.3D for Java API Referansı"
description: "PLY formatı."
type: docs
weight: 129
url: /tr/java/com.aspose.threed/plyformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class PlyFormat extends FileFormat
```

PLY formatı. **Örnek:** Aşağıdaki kod, bir PLY dosyasından bir ağın nasıl çözüleceğini gösterir:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AMF](#AMF) | Katmanlı üretim dosya formatı |
| [ASE](#ASE) | 3D Studio Max'in ASCII Sahne Dışa Aktarıcı formatı. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D Web formatı. |
| [BLENDER](#BLENDER) | Blender'ın 3D dosya formatı |
| [COLLADA](#COLLADA) | Collada dosya formatı |
| [DISCREET3DS](#DISCREET3DS) | 3D Studio'nun dosya formatı |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX dosya formatı, 6.1.0 sürümü ile |
| [FBX6100_BINARY](#FBX6100-BINARY) | Binary FBX dosya formatı, 6.1.0 sürümü ile |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX dosya formatı, 7.2.0 sürümü ile |
| [FBX7200_BINARY](#FBX7200-BINARY) | Binary FBX dosya formatı, 7.2.0 sürümü ile |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX dosya formatı, 7.3.0 sürümü ile |
| [FBX7300_BINARY](#FBX7300-BINARY) | Binary FBX dosya formatı, 7.3.0 sürümü ile |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX dosya formatı, 7.4.0 sürümü ile |
| [FBX7400_BINARY](#FBX7400-BINARY) | Binary FBX dosya formatı, 7.4.0 sürümü ile |
| [FBX7500ASCII](#FBX7500ASCII) | ASCII FBX dosya formatı, 7.5.0 sürümüyle |
| [FBX7500_BINARY](#FBX7500-BINARY) | Binary FBX dosya formatı, 7.5.0 sürümüyle |
| [FBX7600ASCII](#FBX7600ASCII) | ASCII FBX dosya formatı, 7.6.0 sürümüyle |
| [FBX7600_BINARY](#FBX7600-BINARY) | Binary FBX dosya formatı, 7.6.0 sürümüyle |
| [FBX7700ASCII](#FBX7700ASCII) | ASCII FBX dosya formatı, 7.7.0 sürümüyle |
| [FBX7700_BINARY](#FBX7700-BINARY) | Binary FBX dosya formatı, 7.7.0 sürümüyle |
| [GLTF](#GLTF) | Khronos Group'un glTF |
| [GLTF2](#GLTF2) | Khronos Group'un glTF sürümü 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | Khronos Group'un glTF sürümü 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | Khronos Group'un glTF Binary formatında |
| [HTML5](#HTML5) | HTML5 Dosyası |
| [IFC](#IFC) | ISO 16739-1 Industry Foundation Classes veri modeli. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya ASCII formatında |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya Binary formatında |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing Format |
| [PCD](#PCD) | PCL Point Cloud Data dosyası ASCII modunda |
| [PCD_BINARY](#PCD-BINARY) | PCL Point Cloud Data dosyası Binary modunda |
| [PDF](#PDF) | Adobe'un Portable Document Format |
| [PLY](#PLY) | Polygon File Format veya Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | AVEVA Plant Design Management System Model binary formatında |
| [RVM_TEXT](#RVM-TEXT) | AVEVA Plant Design Management System Model metin formatında |
| [SIEMENSJT8](#SIEMENSJT8) | Siemens JT Dosya Sürümü 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Siemens JT Dosya Sürümü 9 |
| [STLASCII](#STLASCII) | ASCII STL dosya formatı |
| [STL_BINARY](#STL-BINARY) | Binary STL dosya formatı |
| [UNIVERSAL3D](#UNIVERSAL3D) | Universal3D dosya formatı |
| [USD](#USD) | Evrensel Sahne Açıklaması |
| [USDA](#USDA) | ASCII formatında Evrensel Sahne Açıklaması. |
| [USDZ](#USDZ) | Sıkıştırılmış Evrensel Sahne Açıklaması |
| [VRML](#VRML) | Sanal Gerçeklik Modelleme Dili |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Wavefront'un Obj dosya formatı |
| [XYZ](#XYZ) | Xyz nokta bulutu dosyası |
| [X_BINARY](#X-BINARY) | Binary formatında DirectX X Dosyası |
| [X_TEXT](#X-TEXT) | Binary formatında DirectX X Dosyası |
| [ZIP](#ZIP) | Diğer 3d dosya formatlarını içeren Zip arşivi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Bu dosya formatı için varsayılan yükleme seçenekleri oluştur |
| [createSaveOptions()](#createSaveOptions--) | Bu dosya formatı için varsayılan kaydetme seçenekleri oluştur |
| [decode(Stream stream)](#decode-com.aspose.threed.Stream-) | Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir. |
| [decode(Stream stream, PlyLoadOptions opt)](#decode-com.aspose.threed.Stream-com.aspose.threed.PlyLoadOptions-) | Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir. |
| [decode(String fileName)](#decode-java.lang.String-) | Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir. |
| [decode(String fileName, PlyLoadOptions opt)](#decode-java.lang.String-com.aspose.threed.PlyLoadOptions-) | Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir. |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Dosya formatını veri akışından tespit et, dosya adı sihirli başlık olmayan türleri tahmin etmek için isteğe bağlıdır. |
| [detect(String fileName)](#detect-java.lang.String-) | Dosya formatını dosya adından tespit et, dosya okunabilir olmalı ki Aspose.3D dosya başlığı üzerinden formatı algılayabilsin. |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | Varlığı kodlayın ve sonucu akışa kaydedin. |
| [encode(Entity entity, Stream stream, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-) | Varlığı kodlayın ve sonucu akışa kaydedin. |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | Varlığı kodlayın ve sonucu harici bir dosyaya kaydedin. |
| [encode(Entity entity, String fileName, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-) | Varlığı kodlayın ve sonucu harici bir dosyaya kaydedin. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Aspose.3D'nin geçerli dosya formatına sahneyi dışa aktarmayı destekleyip desteklemediğini alır. |
| [getCanImport()](#getCanImport--) | Aspose.3D'nin geçerli dosya formatından sahneyi içe aktarmayı destekleyip desteklemediğini alır. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Dosya formatı içerik türünü alır |
| [getExtension()](#getExtension--) | Bu tipin uzantı adını alır. |
| [getExtensions()](#getExtensions--) | Bu tipin uzantı adlarını alır. |
| [getFileFormatType()](#getFileFormatType--) | Dosya formatı tipini alır |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Dosya uzantı adından tercih edilen dosya formatını alır. Uzantı adı bir nokta ('.') ile başlamalıdır. |
| [getFormats()](#getFormats--) | Tüm desteklenen formatlara erişim |
| [getVersion()](#getVersion--) | Dosya formatı sürümünü alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Formatları dizeye dönüştür |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Katmanlı üretim dosya formatı

### ASE {#ASE}
```
public static final FileFormat ASE
```


3D Studio Max'in ASCII Sahne Dışa Aktarıcı formatı.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D Web formatı.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Blender'ın 3D dosya formatı

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada dosya formatı

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


3D Studio'nun dosya formatı

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Google Draco Mesh

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


ASCII FBX dosya formatı, 6.1.0 sürümü ile

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Binary FBX dosya formatı, 6.1.0 sürümü ile

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX dosya formatı, 7.2.0 sürümü ile

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Binary FBX dosya formatı, 7.2.0 sürümü ile

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX dosya formatı, 7.3.0 sürümü ile

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Binary FBX dosya formatı, 7.3.0 sürümü ile

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX dosya formatı, 7.4.0 sürümü ile

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Binary FBX dosya formatı, 7.4.0 sürümü ile

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


ASCII FBX dosya formatı, 7.5.0 sürümüyle

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Binary FBX dosya formatı, 7.5.0 sürümüyle

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


ASCII FBX dosya formatı, 7.6.0 sürümüyle

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Binary FBX dosya formatı, 7.6.0 sürümüyle

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


ASCII FBX dosya formatı, 7.7.0 sürümüyle

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Binary FBX dosya formatı, 7.7.0 sürümüyle

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


Khronos Group'un glTF

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


Khronos Group'un glTF sürümü 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


Khronos Group'un glTF sürümü 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


Khronos Group'un glTF Binary formatında

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


HTML5 Dosyası

### IFC {#IFC}
```
public static final FileFormat IFC
```


ISO 16739-1 Industry Foundation Classes veri modeli.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya ASCII formatında

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya Binary formatında

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing Format

### PCD {#PCD}
```
public static final FileFormat PCD
```


PCL Point Cloud Data dosyası ASCII modunda

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


PCL Point Cloud Data dosyası Binary modunda

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Adobe'un Portable Document Format

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format veya Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


AVEVA Plant Design Management System Model binary formatında

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


AVEVA Plant Design Management System Model metin formatında

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Siemens JT Dosya Sürümü 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Siemens JT Dosya Sürümü 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


ASCII STL dosya formatı

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Binary STL dosya formatı

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Universal3D dosya formatı

### USD {#USD}
```
public static final FileFormat USD
```


Evrensel Sahne Açıklaması

### USDA {#USDA}
```
public static final FileFormat USDA
```


ASCII formatında Evrensel Sahne Açıklaması.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Sıkıştırılmış Evrensel Sahne Açıklaması

### VRML {#VRML}
```
public static final FileFormat VRML
```


Sanal Gerçeklik Modelleme Dili

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Wavefront'un Obj dosya formatı

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Xyz nokta bulutu dosyası

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


Binary formatında DirectX X Dosyası

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


Binary formatında DirectX X Dosyası

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Diğer 3d dosya formatlarını içeren Zip arşivi.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Bu dosya formatı için varsayılan yükleme seçenekleri oluştur

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Bu dosya formatı için varsayılan kaydetme seçenekleri oluştur

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### decode(Stream stream) {#decode-com.aspose.threed.Stream-}
```
public Geometry decode(Stream stream)
```


Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı |

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


Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Giriş akışı |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | PLY formatının yükleme seçeneği |

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


Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Giriş akışı |

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


Belirtilen akıştan bir nokta bulutu veya ağ çözümlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Giriş akışı |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | PLY formatının yükleme seçeneği |

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


Dosya formatını veri akışından tespit et, dosya adı sihirli başlık olmayan türleri tahmin etmek için isteğe bağlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Tespit için veri içeren akış |
| fileName | java.lang.String | Verinin özgün dosya adı, ipucu olarak kullanılır. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Dosya formatını dosya adından tespit et, dosya okunabilir olmalı ki Aspose.3D dosya başlığı üzerinden formatı algılayabilsin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya formatını tespit etmek için dosyanın yolu. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### encode(Entity entity, Stream stream) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-}
```
public void encode(Entity entity, Stream stream)
```


Varlığı kodlayın ve sonucu akışa kaydedin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
|  | stream | [Stream](../../com.aspose.threed/stream) | Yazılacak akış, bu yöntem bu akışı kapatmaz **Example:** Aşağıdaki kod, bir ağın PLY dosyasına nasıl kodlanacağını gösterir: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, Stream stream, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, Stream stream, PlySaveOptions opt)
```


Varlığı kodlayın ve sonucu akışa kaydedin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
| stream | [Stream](../../com.aspose.threed/stream) | Yazılacak akış, bu yöntem bu akışı kapatmaz |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | Kaydetme seçenekleri **Example:** Aşağıdaki kod, bir ağın PLY dosyasına nasıl kodlanacağını gösterir: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


Varlığı kodlayın ve sonucu harici bir dosyaya kaydedin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
|  | fileName | java.lang.String | Yazılacak dosya **Example:** Aşağıdaki kod, bir ağın PLY dosyasına nasıl kodlanacağını gösterir: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, String fileName, PlySaveOptions opt)
```


Varlığı kodlayın ve sonucu harici bir dosyaya kaydedin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
| fileName | java.lang.String | Yazılacak dosya |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | Kaydetme seçenekleri **Example:** Aşağıdaki kod, bir ağın PLY dosyasına nasıl kodlanacağını gösterir: |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Aspose.3D'nin geçerli dosya formatına sahneyi dışa aktarmayı destekleyip desteklemediğini alır.

**Returns:**
boolean - Aspose.3D'nin geçerli dosya formatına sahneyi dışa aktarmayı destekleyip desteklemediği. **Örnek:** Aşağıdaki kod, belirtilen formata dışa aktarmanın desteklenip desteklenmediğini nasıl kontrol edeceğinizi gösterir.

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


Aspose.3D'nin geçerli dosya formatından sahneyi içe aktarmayı destekleyip desteklemediğini alır.

**Returns:**
boolean - Aspose.3D'nin geçerli dosya formatından sahneyi içe aktarmayı destekleyip desteklemediği. **Örnek:** Aşağıdaki kod, belirtilen formattan içe aktarmanın desteklenip desteklenmediğini nasıl kontrol edeceğinizi gösterir.

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


Dosya formatı içerik türünü alır

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


Bu tipin uzantı adını alır.

**Returns:**
java.lang.String - bu tipin uzantı adı. **Örnek:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Bu tipin uzantı adlarını alır.

**Returns:**
java.lang.String[] - bu tipin uzantı adları.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Dosya formatı tipini alır

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Dosya uzantı adından tercih edilen dosya formatını alır. Uzantı adı bir nokta ('.') ile başlamalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extensionName | java.lang.String | Uzantı adı, sorgulama için '.' ile başlar. |

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


Tüm desteklenen formatlara erişim

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - tüm desteklenen formatlara erişim
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Dosya formatı sürümünü alır

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


Formatları dizeye dönüştür

**Returns:**
java.lang.String - Nesne dizesi
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

