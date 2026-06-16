---
title: "DracoFormat"
second_title: "Aspose.3D for Java API Referansı"
description: "Google Draco formatı Örneği         Aşağıdaki kod, bir Mesh'i bayt dizisine kodlama ve kod çözme işlemlerinin nasıl yapılacağını gösterir"
type: docs
weight: 46
url: /tr/java/com.aspose.threed/dracoformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class DracoFormat extends FileFormat
```

Google Draco formatı **Örnek:** Aşağıdaki kod, bir Mesh'i bayt dizisine kodlamak ve çözmek için nasıl kullanılacağını gösterir:

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into Draco format
             byte[] draco = FileFormat.DRACO.encode(mesh);
             //decode mesh from Draco format
             Mesh decodedMesh = (Mesh)FileFormat.DRACO.decode(draco);
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
| [decode(byte[] data)](#decode-byte---) | Nokta bulutunu veya mesh'i bellek verisinden çöz. |
| [decode(String fileName)](#decode-java.lang.String-) | Nokta bulutunu veya mesh'i belirtilen dosya adından çöz. |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Dosya formatını veri akışından tespit et, dosya adı sihirli başlık olmayan türleri tahmin etmek için isteğe bağlıdır. |
| [detect(String fileName)](#detect-java.lang.String-) | Dosya formatını dosya adından tespit et, dosya okunabilir olmalı ki Aspose.3D dosya başlığı üzerinden formatı algılayabilsin. |
| [encode(Entity entity)](#encode-com.aspose.threed.Entity-) | Varlığı Draco ham verisine kodla. |
| [encode(Entity entity, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-com.aspose.threed.DracoSaveOptions-) | Varlığı Draco ham verisine kodla. |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | Varlığı belirtilen akışa kodla. |
| [encode(Entity entity, Stream stream, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.DracoSaveOptions-) | Varlığı belirtilen akışa kodla. |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | Varlığı belirtilen dosyaya kodla. |
| [encode(Entity entity, String fileName, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.DracoSaveOptions-) | Varlığı belirtilen dosyaya kodla. |
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
### decode(byte[] data) {#decode-byte---}
```
public Geometry decode(byte[] data)
```


Nokta bulutunu veya mesh'i bellek verisinden çöz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Ham drc baytları |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance depends on the content
### decode(String fileName) {#decode-java.lang.String-}
```
public Geometry decode(String fileName)
```


Nokta bulutunu veya mesh'i belirtilen dosya adından çöz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosya adı drc dosyasını içerir. |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance depends on the file content
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
### encode(Entity entity) {#encode-com.aspose.threed.Entity-}
```
public byte[] encode(Entity entity)
```


Varlığı Draco ham verisine kodla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |

**Returns:**
byte[] - Bayt cinsinden temsil edilen kodlanmış draco verisi **Örnek:** Aşağıdaki kod, bir Mesh'i bayt dizisine kodlama ve kod çözme işlemlerinin nasıl yapılacağını gösterir:

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into Draco format
             byte[] draco = FileFormat.DRACO.encode(mesh);
             //decode mesh from Draco format
             Mesh decodedMesh = (Mesh)FileFormat.DRACO.decode(draco);
```
### encode(Entity entity, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-com.aspose.threed.DracoSaveOptions-}
```
public byte[] encode(Entity entity, DracoSaveOptions options)
```


Varlığı Draco ham verisine kodla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | Nokta bulutunu kodlamak için ekstra seçenekler |

**Returns:**
byte[] - Bayt cinsinden temsil edilen kodlanmış draco verisi **Örnek:** Aşağıdaki kod, bir Mesh'i bayt dizisine kodlama ve kod çözme işlemlerinin nasıl yapılacağını gösterir:

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into Draco format
             byte[] draco = FileFormat.DRACO.encode(mesh);
             //decode mesh from Draco format
             Mesh decodedMesh = (Mesh)FileFormat.DRACO.decode(draco);
```
### encode(Entity entity, Stream stream) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-}
```
public void encode(Entity entity, Stream stream)
```


Varlığı belirtilen akışa kodla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
| stream | [Stream](../../com.aspose.threed/stream) | Kodlanmış verinin yazılacağı akış |

### encode(Entity entity, Stream stream, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.DracoSaveOptions-}
```
public void encode(Entity entity, Stream stream, DracoSaveOptions options)
```


Varlığı belirtilen akışa kodla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
| stream | [Stream](../../com.aspose.threed/stream) | Kodlanmış verinin yazılacağı akış |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | Nokta bulutunu kodlamak için ekstra seçenekler |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


Varlığı belirtilen dosyaya kodla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
| fileName | java.lang.String | Yazılacak dosya adı |

### encode(Entity entity, String fileName, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.DracoSaveOptions-}
```
public void encode(Entity entity, String fileName, DracoSaveOptions options)
```


Varlığı belirtilen dosyaya kodla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Kodlanacak varlık |
| fileName | java.lang.String | Yazılacak dosya adı |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | Nokta bulutunu kodlamak için ekstra seçenekler |

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

