---
title: DracoFormat
second_title: Aspose.3D for Java API 레퍼런스
description: Google Draco 형식 예제         다음 코드는 Mesh를 바이트 배열로 인코딩 및 디코딩하는 방법을 보여줍니다
type: docs
weight: 46
url: /ko/java/com.aspose.threed/dracoformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class DracoFormat extends FileFormat
```

Google Draco 형식 **Example:** 다음 코드는 메쉬를 바이트 배열로 인코딩하고 디코딩하는 방법을 보여줍니다:

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into Draco format
             byte[] draco = FileFormat.DRACO.encode(mesh);
             //decode mesh from Draco format
             Mesh decodedMesh = (Mesh)FileFormat.DRACO.decode(draco);
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [AMF](#AMF) | 적층 제조 파일 형식 |
| [ASE](#ASE) | 3D Studio Max의 ASCII 씬 내보내기 형식. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D 웹 형식. |
| [BLENDER](#BLENDER) | Blender의 3D 파일 형식 |
| [COLLADA](#COLLADA) | Collada 파일 형식 |
| [DISCREET3DS](#DISCREET3DS) | 3D Studio의 파일 형식 |
| [DRACO](#DRACO) | Google Draco 메쉬 |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX 파일 형식, 버전 6.1.0 포함 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Binary FBX 파일 형식, 버전 6.1.0 포함 |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX 파일 형식, 버전 7.2.0 포함 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Binary FBX 파일 형식, 버전 7.2.0 포함 |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX 파일 형식, 버전 7.3.0 포함 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Binary FBX 파일 형식, 버전 7.3.0 포함 |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX 파일 형식, 버전 7.4.0 포함 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Binary FBX 파일 형식, 버전 7.4.0 포함 |
| [FBX7500ASCII](#FBX7500ASCII) | ASCII FBX 파일 형식, 7.5.0 버전 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Binary FBX 파일 형식, 7.5.0 버전 |
| [FBX7600ASCII](#FBX7600ASCII) | ASCII FBX 파일 형식, 7.6.0 버전 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Binary FBX 파일 형식, 7.6.0 버전 |
| [FBX7700ASCII](#FBX7700ASCII) | ASCII FBX 파일 형식, 7.7.0 버전 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Binary FBX 파일 형식, 7.7.0 버전 |
| [GLTF](#GLTF) | Khronos Group의 glTF |
| [GLTF2](#GLTF2) | Khronos Group의 glTF 버전 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | Khronos Group의 glTF 버전 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | Khronos Group의 glTF 바이너리 형식 |
| [HTML5](#HTML5) | HTML5 파일 |
| [IFC](#IFC) | ISO 16739-1 Industry Foundation Classes 데이터 모델. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya ASCII 형식 |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya 바이너리 형식 |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing Format |
| [PCD](#PCD) | PCL Point Cloud Data 파일 ASCII 모드 |
| [PCD_BINARY](#PCD-BINARY) | PCL Point Cloud Data 파일 바이너리 모드 |
| [PDF](#PDF) | Adobe의 Portable Document Format |
| [PLY](#PLY) | Polygon File Format 또는 Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | AVEVA Plant Design Management System 모델 바이너리 형식 |
| [RVM_TEXT](#RVM-TEXT) | AVEVA Plant Design Management System 모델 텍스트 형식 |
| [SIEMENSJT8](#SIEMENSJT8) | Siemens JT 파일 버전 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Siemens JT 파일 버전 9 |
| [STLASCII](#STLASCII) | ASCII STL 파일 형식 |
| [STL_BINARY](#STL-BINARY) | Binary STL 파일 형식 |
| [UNIVERSAL3D](#UNIVERSAL3D) | Universal3D 파일 형식 |
| [USD](#USD) | 범용 장면 설명 |
| [USDA](#USDA) | ASCII 형식의 범용 장면 설명. |
| [USDZ](#USDZ) | 압축된 범용 장면 설명 |
| [VRML](#VRML) | 가상 현실 모델링 언어 |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Wavefront의 Obj 파일 형식 |
| [XYZ](#XYZ) | Xyz 포인트 클라우드 파일 |
| [X_BINARY](#X-BINARY) | 바이너리 형식의 DirectX X 파일 |
| [X_TEXT](#X-TEXT) | 바이너리 형식의 DirectX X 파일 |
| [ZIP](#ZIP) | 다른 3D 파일 형식을 포함하는 Zip 아카이브. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | 이 파일 형식에 대한 기본 로드 옵션 생성 |
| [createSaveOptions()](#createSaveOptions--) | 이 파일 형식에 대한 기본 저장 옵션 생성 |
| [decode(byte[] data)](#decode-byte---) | 메모리 데이터에서 포인트 클라우드 또는 메시를 디코드합니다. |
| [decode(String fileName)](#decode-java.lang.String-) | 지정된 파일 이름에서 포인트 클라우드 또는 메시를 디코드합니다. |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | 데이터 스트림에서 파일 형식을 감지하고, 매직 헤더가 없는 유형을 추측하기 위해 파일 이름은 선택 사항입니다. |
| [detect(String fileName)](#detect-java.lang.String-) | 파일 이름으로 파일 형식을 감지합니다. 파일은 읽을 수 있어야 하며, Aspose.3D가 파일 헤더를 통해 파일 형식을 감지할 수 있습니다. |
| [encode(Entity entity)](#encode-com.aspose.threed.Entity-) | 엔티티를 Draco 원시 데이터로 인코드합니다. |
| [encode(Entity entity, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-com.aspose.threed.DracoSaveOptions-) | 엔티티를 Draco 원시 데이터로 인코드합니다. |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | 엔티티를 지정된 스트림으로 인코드합니다. |
| [encode(Entity entity, Stream stream, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.DracoSaveOptions-) | 엔티티를 지정된 스트림으로 인코드합니다. |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | 엔티티를 지정된 파일로 인코드합니다. |
| [encode(Entity entity, String fileName, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.DracoSaveOptions-) | 엔티티를 지정된 파일로 인코드합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Aspose.3D가 현재 파일 형식으로 장면 내보내기를 지원하는지 여부를 가져옵니다. |
| [getCanImport()](#getCanImport--) | Aspose.3D가 현재 파일 형식에서 장면 가져오기를 지원하는지 여부를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | 파일 형식 콘텐츠 유형을 가져옵니다 |
| [getExtension()](#getExtension--) | 이 유형의 확장자 이름을 가져옵니다. |
| [getExtensions()](#getExtensions--) | 이 유형의 확장자 이름들을 가져옵니다. |
| [getFileFormatType()](#getFileFormatType--) | 파일 형식 유형을 가져옵니다 |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | 파일 확장자 이름에서 선호하는 파일 형식을 가져옵니다. 확장자 이름은 점('.')으로 시작해야 합니다. |
| [getFormats()](#getFormats--) | 지원되는 모든 형식에 접근 |
| [getVersion()](#getVersion--) | 파일 형식 버전을 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 형식을 문자열로 변환 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


적층 제조 파일 형식

### ASE {#ASE}
```
public static final FileFormat ASE
```


3D Studio Max의 ASCII 씬 내보내기 형식.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D 웹 형식.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Blender의 3D 파일 형식

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada 파일 형식

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


3D Studio의 파일 형식

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Google Draco 메쉬

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


ASCII FBX 파일 형식, 버전 6.1.0 포함

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Binary FBX 파일 형식, 버전 6.1.0 포함

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX 파일 형식, 버전 7.2.0 포함

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Binary FBX 파일 형식, 버전 7.2.0 포함

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX 파일 형식, 버전 7.3.0 포함

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Binary FBX 파일 형식, 버전 7.3.0 포함

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX 파일 형식, 버전 7.4.0 포함

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Binary FBX 파일 형식, 버전 7.4.0 포함

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


ASCII FBX 파일 형식, 7.5.0 버전

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Binary FBX 파일 형식, 7.5.0 버전

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


ASCII FBX 파일 형식, 7.6.0 버전

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Binary FBX 파일 형식, 7.6.0 버전

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


ASCII FBX 파일 형식, 7.7.0 버전

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Binary FBX 파일 형식, 7.7.0 버전

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


Khronos Group의 glTF

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


Khronos Group의 glTF 버전 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


Khronos Group의 glTF 버전 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


Khronos Group의 glTF 바이너리 형식

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


HTML5 파일

### IFC {#IFC}
```
public static final FileFormat IFC
```


ISO 16739-1 Industry Foundation Classes 데이터 모델.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya ASCII 형식

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya 바이너리 형식

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing Format

### PCD {#PCD}
```
public static final FileFormat PCD
```


PCL Point Cloud Data 파일 ASCII 모드

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


PCL Point Cloud Data 파일 바이너리 모드

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Adobe의 Portable Document Format

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format 또는 Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


AVEVA Plant Design Management System 모델 바이너리 형식

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


AVEVA Plant Design Management System 모델 텍스트 형식

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Siemens JT 파일 버전 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Siemens JT 파일 버전 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


ASCII STL 파일 형식

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Binary STL 파일 형식

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Universal3D 파일 형식

### USD {#USD}
```
public static final FileFormat USD
```


범용 장면 설명

### USDA {#USDA}
```
public static final FileFormat USDA
```


ASCII 형식의 범용 장면 설명.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


압축된 범용 장면 설명

### VRML {#VRML}
```
public static final FileFormat VRML
```


가상 현실 모델링 언어

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Wavefront의 Obj 파일 형식

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Xyz 포인트 클라우드 파일

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


바이너리 형식의 DirectX X 파일

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


바이너리 형식의 DirectX X 파일

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


다른 3D 파일 형식을 포함하는 Zip 아카이브.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


이 파일 형식에 대한 기본 로드 옵션 생성

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


이 파일 형식에 대한 기본 저장 옵션 생성

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### decode(byte[] data) {#decode-byte---}
```
public Geometry decode(byte[] data)
```


메모리 데이터에서 포인트 클라우드 또는 메시를 디코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 원시 drc 바이트 |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance depends on the content
### decode(String fileName) {#decode-java.lang.String-}
```
public Geometry decode(String fileName)
```


지정된 파일 이름에서 포인트 클라우드 또는 메시를 디코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름에 drc 파일이 포함됩니다. |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance depends on the file content
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


데이터 스트림에서 파일 형식을 감지하고, 매직 헤더가 없는 유형을 추측하기 위해 파일 이름은 선택 사항입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 감지를 위한 데이터를 포함하는 스트림 |
| fileName | java.lang.String | 데이터의 원본 파일 이름, 힌트로 사용됩니다. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


파일 이름으로 파일 형식을 감지합니다. 파일은 읽을 수 있어야 하며, Aspose.3D가 파일 헤더를 통해 파일 형식을 감지할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 형식을 감지할 파일 경로. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### encode(Entity entity) {#encode-com.aspose.threed.Entity-}
```
public byte[] encode(Entity entity)
```


엔티티를 Draco 원시 데이터로 인코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 인코드될 엔티티 |

**Returns:**
byte[] - 바이트로 표현된 인코드된 draco 데이터 **Example:** 다음 코드는 Mesh를 바이트 배열로 인코드 및 디코드하는 방법을 보여줍니다:

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


엔티티를 Draco 원시 데이터로 인코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 인코드될 엔티티 |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | 포인트 클라우드 인코딩을 위한 추가 옵션 |

**Returns:**
byte[] - 바이트로 표현된 인코드된 draco 데이터 **Example:** 다음 코드는 Mesh를 바이트 배열로 인코드 및 디코드하는 방법을 보여줍니다:

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


엔티티를 지정된 스트림으로 인코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 인코드될 엔티티 |
| stream | [Stream](../../com.aspose.threed/stream) | 인코드된 데이터가 기록될 스트림 |

### encode(Entity entity, Stream stream, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.DracoSaveOptions-}
```
public void encode(Entity entity, Stream stream, DracoSaveOptions options)
```


엔티티를 지정된 스트림으로 인코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 인코드될 엔티티 |
| stream | [Stream](../../com.aspose.threed/stream) | 인코드된 데이터가 기록될 스트림 |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | 포인트 클라우드 인코딩을 위한 추가 옵션 |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


엔티티를 지정된 파일로 인코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 인코드될 엔티티 |
| fileName | java.lang.String | 작성될 파일 이름 |

### encode(Entity entity, String fileName, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.DracoSaveOptions-}
```
public void encode(Entity entity, String fileName, DracoSaveOptions options)
```


엔티티를 지정된 파일로 인코드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 인코드될 엔티티 |
| fileName | java.lang.String | 작성될 파일 이름 |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | 포인트 클라우드 인코딩을 위한 추가 옵션 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Aspose.3D가 현재 파일 형식으로 장면 내보내기를 지원하는지 여부를 가져옵니다.

**Returns:**
boolean - Aspose.3D가 현재 파일 형식으로 씬을 내보내는 것을 지원하는지 여부. **예시:** 다음 코드는 지정된 형식으로 내보내기가 지원되는지 확인하는 방법을 보여줍니다.

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


Aspose.3D가 현재 파일 형식에서 장면 가져오기를 지원하는지 여부를 가져옵니다.

**Returns:**
boolean - Aspose.3D가 현재 파일 형식에서 씬을 가져오는 것을 지원하는지 여부. **예시:** 다음 코드는 지정된 형식으로 가져오기가 지원되는지 확인하는 방법을 보여줍니다.

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


파일 형식 콘텐츠 유형을 가져옵니다

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


이 유형의 확장자 이름을 가져옵니다.

**Returns:**
java.lang.String - 이 타입의 확장자 이름입니다. **예시:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


이 유형의 확장자 이름들을 가져옵니다.

**Returns:**
java.lang.String[] - 이 타입의 확장자 이름들입니다.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


파일 형식 유형을 가져옵니다

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


파일 확장자 이름에서 선호하는 파일 형식을 가져옵니다. 확장자 이름은 점('.')으로 시작해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| extensionName | java.lang.String | 확장자 이름은 쿼리를 위해 '.'으로 시작합니다. |

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


지원되는 모든 형식에 접근

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - 지원되는 모든 형식에 대한 접근
### getVersion() {#getVersion--}
```
public Version getVersion()
```


파일 형식 버전을 가져옵니다

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


형식을 문자열로 변환

**Returns:**
java.lang.String - 객체 문자열
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

