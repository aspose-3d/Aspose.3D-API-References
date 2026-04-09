---
title: PlyFormat
second_title: Aspose.3D for Java API Reference
description: PLY फ़ॉर्मेट।
type: docs
weight: 129
url: /hi/java/com.aspose.threed/plyformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class PlyFormat extends FileFormat
```

PLY फ़ॉर्मेट। **Example:** निम्नलिखित कोड दिखाता है कि PLY फ़ाइल से मेष को कैसे डिकोड किया जाए:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [AMF](#AMF) | ऐडिटिव मैन्युफैक्चरिंग फ़ाइल फ़ॉर्मेट |
| [ASE](#ASE) | 3D Studio Max का ASCII सीन एक्सपोर्टर फ़ॉर्मेट। |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D वेब फ़ॉर्मेट। |
| [BLENDER](#BLENDER) | Blender का 3D फ़ाइल फ़ॉर्मेट |
| [COLLADA](#COLLADA) | Collada फ़ाइल फ़ॉर्मेट |
| [DISCREET3DS](#DISCREET3DS) | 3D Studio का फ़ाइल फ़ॉर्मेट |
| [DRACO](#DRACO) | Google Draco मेष |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 6.1.0 के साथ |
| [FBX6100_BINARY](#FBX6100-BINARY) | बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 6.1.0 के साथ |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.2.0 के साथ |
| [FBX7200_BINARY](#FBX7200-BINARY) | बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.2.0 के साथ |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.3.0 के साथ |
| [FBX7300_BINARY](#FBX7300-BINARY) | बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.3.0 के साथ |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.4.0 के साथ |
| [FBX7400_BINARY](#FBX7400-BINARY) | बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.4.0 के साथ |
| [FBX7500ASCII](#FBX7500ASCII) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.5.0 के साथ |
| [FBX7500_BINARY](#FBX7500-BINARY) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.5.0 के साथ |
| [FBX7600ASCII](#FBX7600ASCII) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.6.0 के साथ |
| [FBX7600_BINARY](#FBX7600-BINARY) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.6.0 के साथ |
| [FBX7700ASCII](#FBX7700ASCII) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.7.0 के साथ |
| [FBX7700_BINARY](#FBX7700-BINARY) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.7.0 के साथ |
| [GLTF](#GLTF) | Khronos Group का glTF |
| [GLTF2](#GLTF2) | Khronos Group का glTF संस्करण 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | Khronos Group का glTF संस्करण 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | Khronos Group का glTF बाइनरी फ़ॉर्मेट में |
| [HTML5](#HTML5) | HTML5 फ़ाइल |
| [IFC](#IFC) | ISO 16739-1 Industry Foundation Classes डेटा मॉडल। |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya ASCII फ़ॉर्मेट में |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya बाइनरी फ़ॉर्मेट में |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing फ़ॉर्मेट |
| [PCD](#PCD) | PCL पॉइंट क्लाउड डेटा फ़ाइल ASCII मोड में |
| [PCD_BINARY](#PCD-BINARY) | PCL पॉइंट क्लाउड डेटा फ़ाइल बाइनरी मोड में |
| [PDF](#PDF) | Adobe का Portable Document Format |
| [PLY](#PLY) | Polygon फ़ाइल फ़ॉर्मेट या Stanford Triangle फ़ॉर्मेट |
| [RVM_BINARY](#RVM-BINARY) | AVEVA Plant Design Management System मॉडल बाइनरी फ़ॉर्मेट में |
| [RVM_TEXT](#RVM-TEXT) | AVEVA Plant Design Management System मॉडल टेक्स्ट फ़ॉर्मेट में |
| [SIEMENSJT8](#SIEMENSJT8) | Siemens JT फ़ाइल संस्करण 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Siemens JT फ़ाइल संस्करण 9 |
| [STLASCII](#STLASCII) | ASCII STL फ़ाइल फ़ॉर्मेट |
| [STL_BINARY](#STL-BINARY) | Binary STL फ़ाइल फ़ॉर्मेट |
| [UNIVERSAL3D](#UNIVERSAL3D) | Universal3D फ़ाइल फ़ॉर्मेट |
| [USD](#USD) | यूनिवर्सल सीन विवरण |
| [USDA](#USDA) | ASCII फ़ॉर्मेट में यूनिवर्सल सीन विवरण। |
| [USDZ](#USDZ) | संपीड़ित यूनिवर्सल सीन विवरण |
| [VRML](#VRML) | वर्चुअल रियलिटी मॉडलिंग भाषा |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Wavefront की Obj फ़ाइल फ़ॉर्मेट |
| [XYZ](#XYZ) | Xyz पॉइंट क्लाउड फ़ाइल |
| [X_BINARY](#X-BINARY) | बाइनरी फ़ॉर्मेट में DirectX X फ़ाइल |
| [X_TEXT](#X-TEXT) | बाइनरी फ़ॉर्मेट में DirectX X फ़ाइल |
| [ZIP](#ZIP) | ज़िप आर्काइव जिसमें अन्य 3D फ़ाइल फ़ॉर्मेट शामिल हैं। |
## Methods

| Method | विवरण |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट लोड विकल्प बनाएं |
| [createSaveOptions()](#createSaveOptions--) | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट सेव विकल्प बनाएं |
| [decode(Stream stream)](#decode-com.aspose.threed.Stream-) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [decode(Stream stream, PlyLoadOptions opt)](#decode-com.aspose.threed.Stream-com.aspose.threed.PlyLoadOptions-) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [decode(String fileName)](#decode-java.lang.String-) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [decode(String fileName, PlyLoadOptions opt)](#decode-java.lang.String-com.aspose.threed.PlyLoadOptions-) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | डेटा स्ट्रीम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल नाम वैकल्पिक है उन प्रकारों का अनुमान लगाने के लिए जिनमें कोई मैजिक हेडर नहीं है। |
| [detect(String fileName)](#detect-java.lang.String-) | फ़ाइल नाम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल पढ़ने योग्य होनी चाहिए ताकि Aspose.3D फ़ाइल हेडर के माध्यम से फ़ॉर्मेट का पता लगा सके। |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | इकाई को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें। |
| [encode(Entity entity, Stream stream, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-) | इकाई को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें। |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | इकाई को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें। |
| [encode(Entity entity, String fileName, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-) | इकाई को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट में सीन निर्यात का समर्थन करता है या नहीं। |
| [getCanImport()](#getCanImport--) | जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट से सीन आयात का समर्थन करता है या नहीं। |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | फ़ाइल फ़ॉर्मेट की कंटेंट टाइप प्राप्त करता है |
| [getExtension()](#getExtension--) | इस प्रकार का एक्सटेंशन नाम प्राप्त करता है। |
| [getExtensions()](#getExtensions--) | इस प्रकार के एक्सटेंशन नाम प्राप्त करता है। |
| [getFileFormatType()](#getFileFormatType--) | फ़ाइल फ़ॉर्मेट प्रकार प्राप्त करता है |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | फ़ाइल एक्सटेंशन नाम से पसंदीदा फ़ाइल फ़ॉर्मेट प्राप्त करता है। एक्सटेंशन नाम डॉट ('.') से शुरू होना चाहिए। |
| [getFormats()](#getFormats--) | सभी समर्थित फ़ॉर्मेट तक पहुंच |
| [getVersion()](#getVersion--) | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | फ़ॉर्मेट को स्ट्रिंग में बदलें |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


ऐडिटिव मैन्युफैक्चरिंग फ़ाइल फ़ॉर्मेट

### ASE {#ASE}
```
public static final FileFormat ASE
```


3D Studio Max का ASCII सीन एक्सपोर्टर फ़ॉर्मेट।

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D वेब फ़ॉर्मेट।

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Blender का 3D फ़ाइल फ़ॉर्मेट

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada फ़ाइल फ़ॉर्मेट

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


3D Studio का फ़ाइल फ़ॉर्मेट

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Google Draco मेष

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 6.1.0 के साथ

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 6.1.0 के साथ

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.2.0 के साथ

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.2.0 के साथ

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.3.0 के साथ

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.3.0 के साथ

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.4.0 के साथ

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


बाइनरी FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.4.0 के साथ

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.5.0 के साथ

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.5.0 के साथ

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.6.0 के साथ

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.6.0 के साथ

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.7.0 के साथ

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.7.0 के साथ

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


Khronos Group का glTF

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


Khronos Group का glTF संस्करण 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


Khronos Group का glTF संस्करण 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


Khronos Group का glTF बाइनरी फ़ॉर्मेट में

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


HTML5 फ़ाइल

### IFC {#IFC}
```
public static final FileFormat IFC
```


ISO 16739-1 Industry Foundation Classes डेटा मॉडल।

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya ASCII फ़ॉर्मेट में

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya बाइनरी फ़ॉर्मेट में

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing फ़ॉर्मेट

### PCD {#PCD}
```
public static final FileFormat PCD
```


PCL पॉइंट क्लाउड डेटा फ़ाइल ASCII मोड में

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


PCL पॉइंट क्लाउड डेटा फ़ाइल बाइनरी मोड में

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Adobe का Portable Document Format

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon फ़ाइल फ़ॉर्मेट या Stanford Triangle फ़ॉर्मेट

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


AVEVA Plant Design Management System मॉडल बाइनरी फ़ॉर्मेट में

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


AVEVA Plant Design Management System मॉडल टेक्स्ट फ़ॉर्मेट में

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Siemens JT फ़ाइल संस्करण 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Siemens JT फ़ाइल संस्करण 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


ASCII STL फ़ाइल फ़ॉर्मेट

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Binary STL फ़ाइल फ़ॉर्मेट

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Universal3D फ़ाइल फ़ॉर्मेट

### USD {#USD}
```
public static final FileFormat USD
```


यूनिवर्सल सीन विवरण

### USDA {#USDA}
```
public static final FileFormat USDA
```


ASCII फ़ॉर्मेट में यूनिवर्सल सीन विवरण।

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


संपीड़ित यूनिवर्सल सीन विवरण

### VRML {#VRML}
```
public static final FileFormat VRML
```


वर्चुअल रियलिटी मॉडलिंग भाषा

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Wavefront की Obj फ़ाइल फ़ॉर्मेट

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Xyz पॉइंट क्लाउड फ़ाइल

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


बाइनरी फ़ॉर्मेट में DirectX X फ़ाइल

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


बाइनरी फ़ॉर्मेट में DirectX X फ़ाइल

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


ज़िप आर्काइव जिसमें अन्य 3D फ़ाइल फ़ॉर्मेट शामिल हैं।

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट लोड विकल्प बनाएं

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट सेव विकल्प बनाएं

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### decode(Stream stream) {#decode-com.aspose.threed.Stream-}
```
public Geometry decode(Stream stream)
```


निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम |

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


निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | PLY फ़ॉर्मेट का लोड विकल्प |

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


निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | इनपुट स्ट्रीम |

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


निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | इनपुट स्ट्रीम |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | PLY फ़ॉर्मेट का लोड विकल्प |

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


डेटा स्ट्रीम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल नाम वैकल्पिक है उन प्रकारों का अनुमान लगाने के लिए जिनमें कोई मैजिक हेडर नहीं है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | डेटा को पहचानने के लिए स्ट्रीम जिसमें डेटा है |
| fileName | java.lang.String | डेटा का मूल फ़ाइल नाम, संकेत के रूप में उपयोग किया जाता है। |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


फ़ाइल नाम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल पढ़ने योग्य होनी चाहिए ताकि Aspose.3D फ़ाइल हेडर के माध्यम से फ़ॉर्मेट का पता लगा सके।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल फ़ॉर्मेट का पता लगाने के लिए फ़ाइल का पाथ। |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### encode(Entity entity, Stream stream) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-}
```
public void encode(Entity entity, Stream stream)
```


इकाई को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | एन्कोड करने वाली इकाई |
|  | stream | [Stream](../../com.aspose.threed/stream) | लिखने के लिए स्ट्रीम, यह मेथड इस स्ट्रीम को बंद नहीं करेगा **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक मेष को PLY फ़ाइल में एन्कोड किया जाए: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, Stream stream, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, Stream stream, PlySaveOptions opt)
```


इकाई को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | एन्कोड करने वाली इकाई |
| stream | [Stream](../../com.aspose.threed/stream) | लिखने के लिए स्ट्रीम, यह मेथड इस स्ट्रीम को बंद नहीं करेगा |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | सेव विकल्प **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक मेष को PLY फ़ाइल में एन्कोड किया जाए: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


इकाई को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | एन्कोड करने वाली इकाई |
|  | fileName | java.lang.String | लिखने के लिए फ़ाइल **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक मेष को PLY फ़ाइल में एन्कोड किया जाए: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, String fileName, PlySaveOptions opt)
```


इकाई को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | एन्कोड करने वाली इकाई |
| fileName | java.lang.String | लिखने के लिए फ़ाइल |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | सेव विकल्प **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक मेष को PLY फ़ाइल में एन्कोड किया जाए: |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट में सीन निर्यात का समर्थन करता है या नहीं।

**Returns:**
boolean - क्या Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट में सीन निर्यात का समर्थन करता है। **उदाहरण:** निम्नलिखित कोड दिखाता है कि निर्दिष्ट फ़ॉर्मेट में निर्यात समर्थित है या नहीं।

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


जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट से सीन आयात का समर्थन करता है या नहीं।

**Returns:**
boolean - क्या Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट से सीन आयात का समर्थन करता है। **उदाहरण:** निम्नलिखित कोड दिखाता है कि निर्दिष्ट फ़ॉर्मेट से आयात समर्थित है या नहीं।

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


फ़ाइल फ़ॉर्मेट की कंटेंट टाइप प्राप्त करता है

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


इस प्रकार का एक्सटेंशन नाम प्राप्त करता है।

**Returns:**
java.lang.String - इस प्रकार का एक्सटेंशन नाम। **उदाहरण:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


इस प्रकार के एक्सटेंशन नाम प्राप्त करता है।

**Returns:**
java.lang.String[] - इस प्रकार के एक्सटेंशन नाम।
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


फ़ाइल फ़ॉर्मेट प्रकार प्राप्त करता है

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


फ़ाइल एक्सटेंशन नाम से पसंदीदा फ़ाइल फ़ॉर्मेट प्राप्त करता है। एक्सटेंशन नाम डॉट ('.') से शुरू होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| extensionName | java.lang.String | एक्सटेंशन नाम क्वेरी के लिए '.' से शुरू होता है। |

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


सभी समर्थित फ़ॉर्मेट तक पहुंच

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - सभी समर्थित फ़ॉर्मेट तक पहुँच
### getVersion() {#getVersion--}
```
public Version getVersion()
```


फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है

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


फ़ॉर्मेट को स्ट्रिंग में बदलें

**Returns:**
java.lang.String - ऑब्जेक्ट स्ट्रिंग
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

