---
title: GltfSaveOptions
second_title: Aspose.3D for Java API Reference
description: glTF फ़ॉर्मेट के लिए सहेजने विकल्प।
type: docs
weight: 74
url: /hi/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

glTF फ़ॉर्मेट के लिए सहेजने विकल्प।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का निर्माणकर्ता |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का निर्माणकर्ता |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। |
| [getBufferFile()](#getBufferFile--) | बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | ड्रैको संपीड़न को सक्षम करने की स्थिति प्राप्त करता है |
| [getEmbedAssets()](#getEmbedAssets--) | सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है। |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getExportTextures()](#getExportTextures--) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें। |
| [getFallbackNormal()](#getFallbackNormal--) | जब GLTF2 निर्यातकर्ता ने एक अमान्य सामान्य पाया, तो मान्यकरण को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। |
| [getFileFormat()](#getFileFormat--) | वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | टेक्सचर निर्देशांक v(t) घटक को उलटें, डिफ़ॉल्ट मान true है। |
| [getImageFormat()](#getImageFormat--) | मानक glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प यह मार्गदर्शन करेगा कि Aspose.3D निर्यात के दौरान गैर-मानक छवियों को समर्थित फ़ॉर्मेट में कैसे परिवर्तित करता है। |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [getMaterialConverter()](#getMaterialConverter--) | ज्यामिति की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 निर्यातक स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। |
| [getPrettyPrint()](#getPrettyPrint--) | GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड है, डिफ़ॉल्ट मान false है। |
| [getSaveExtras()](#getSaveExtras--) | जेनरेट की गई glTF फ़ाइल में 'extra' फ़ील्ड्स में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ सहेजें। |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | निर्धारित करता है कि ड्रैको संपीड़न सक्षम किया जाए या नहीं। |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है। |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें। |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | जब GLTF2 निर्यातकर्ता ने एक अमान्य सामान्य पाया, तो मान्यकरण को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | टेक्सचर निर्देशांक v(t) घटक को उलटें, डिफ़ॉल्ट मान true है। |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | मानक glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प यह मार्गदर्शन करेगा कि Aspose.3D निर्यात के दौरान गैर-मानक छवियों को समर्थित फ़ॉर्मेट में कैसे परिवर्तित करता है। |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | ज्यामिति की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 निर्यातक स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड है, डिफ़ॉल्ट मान false है। |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | जेनरेट की गई glTF फ़ाइल में 'extra' फ़ील्ड्स में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ सहेजें। |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


[GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का निर्माणकर्ता

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


[GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का निर्माणकर्ता

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन - मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। डिफ़ॉल्ट मान false है।
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह तब अनदेखा किया जाता है जब बाइनरी मोड में glTF निर्यात किया जाता है।

**Returns:**
java.lang.String - बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह बाइनरी मोड में glTF निर्यात करते समय अनदेखा किया जाता है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDracoCompression() {#getDracoCompression--}
```
public boolean getDracoCompression()
```


ड्रैको संपीड़न को सक्षम करने की स्थिति प्राप्त करता है

**Returns:**
boolean - ड्रैको संपीड़न सक्षम करना है या नहीं
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है।

**Returns:**
boolean - सभी बाहरी एसेट्स को ASCII मोड में बेस64 के रूप में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है।
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।

**Returns:**
java.nio.charset.Charset - टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Returns:**
boolean - दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें।

**Returns:**
java.lang.String - ड्रैको संपीड़न गति को तेज करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें। **Remarks:** Aspose.3D मेष को ड्रैको फ़ॉर्मेट में एन्कोड करने के लिए नई उप-प्रक्रिया बनाएगा, इसे अपने जोखिम पर उपयोग करें।
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


जब GLTF2 निर्यातक ने एक अमान्य नॉर्मल का पता लगाया, तो वैधता को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। डिफ़ॉल्ट मान (0, 1, 0) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Returns:**
java.lang.String - एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है।

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की इम्प्लीमेंटेशन भी उपयोग कर सकते हैं।

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर वातावरण के लिए उपयुक्त नहीं है।

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


टेक्सचर निर्देशांक v(t) घटक को उलटें, डिफ़ॉल्ट मान true है।

**Returns:**
boolean - टेक्सचर कोऑर्डिनेट v(t) घटक को उलटें, डिफ़ॉल्ट मान true है।
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


मानक glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प यह मार्गदर्शन करेगा कि Aspose.3D निर्यात के दौरान गैर-मानक छवियों को समर्थित फ़ॉर्मेट में कैसे परिवर्तित करता है। डिफ़ॉल्ट मान है [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Returns:**
java.util.ArrayList<java.lang.String> - OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को बाहरी फ़ाइल लोड करने के लिए खोजने की अनुमति देंगे। **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


ज्यामिति की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 निर्यातक स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान null है। यह प्रॉपर्टी सीन को glTF 2.0 फ़ाइल में निर्यात करते समय उपयोग की जाती है।

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड है, डिफ़ॉल्ट मान false है।

**Returns:**
boolean - GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड है, डिफ़ॉल्ट मान false है।
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


जेनरेट की गई glTF फ़ाइल में 'extra' फ़ील्ड्स में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ सहेजें। यह एप्लिकेशन-विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है।

**Returns:**
boolean - जेनरेट की गई glTF फ़ाइल में 'extra' फ़ील्ड्स में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ सहेजें। यह एप्लिकेशन-विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है।
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करेगा यदि [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करेगा यदि [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** यह प्रॉपर्टी केवल glTF 1.0 के लिए काम करती है।
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




### setApplyUnitScale(boolean value) {#setApplyUnitScale-boolean-}
```
public void setApplyUnitScale(boolean value)
```


मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह तब अनदेखा किया जाता है जब बाइनरी मोड में glTF निर्यात किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


निर्धारित करता है कि ड्रैको संपीड़न सक्षम किया जाए या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सी एन्कोडिंग उपयोग करनी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset | नया मान |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान **Remarks:** Aspose.3D मेष को ड्रैको फ़ॉर्मेट में एन्कोड करने के लिए नई उप-प्रक्रिया बनाएगा, इसे अपने जोखिम पर उपयोग करें। |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


जब GLTF2 निर्यातक ने एक अमान्य नॉर्मल का पता लगाया, तो वैधता को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। डिफ़ॉल्ट मान (0, 1, 0) है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | नई मान **Example:** डिफ़ॉल्ट FileSystem LocalFileSystem है, यह सर्वर-साइड जैसे वातावरण में सुरक्षित नहीं है, लेकिन आप अलग इम्प्लीमेंटेशन निर्दिष्ट करके फ़ाइल सिस्टम एक्सेस को ओवरराइड कर सकते हैं। Aspose.3D विभिन्न FileSystem इम्प्लीमेंटेशन प्रदान करता है जैसे: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की इम्प्लीमेंटेशन भी उपयोग कर सकते हैं।

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर वातावरण के लिए उपयुक्त नहीं है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | नई मान **Example:** SaveOptions/LoadOptions में डिफ़ॉल्ट FileSystem डायरेक्टरी-आधारित फ़ाइल सिस्टम है, आप इसे IOConfig.FileSystemFactory के माध्यम से निर्दिष्ट करके डिफ़ॉल्ट इम्प्लीमेंटेशन को ओवरराइड कर सकते हैं: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


टेक्सचर निर्देशांक v(t) घटक को उलटें, डिफ़ॉल्ट मान true है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


मानक glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प यह मार्गदर्शन करेगा कि Aspose.3D निर्यात के दौरान गैर-मानक छवियों को समर्थित फ़ॉर्मेट में कैसे परिवर्तित करता है। डिफ़ॉल्ट मान है [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | नया मान |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.util.ArrayList<java.lang.String> | नई मान **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


ज्यामिति की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कन्वर्टर। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 निर्यातक स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान null है। यह प्रॉपर्टी सीन को glTF 2.0 फ़ाइल में निर्यात करते समय उपयोग की जाती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | नया मान |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड है, डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


जेनरेट की गई glTF फ़ाइल में 'extra' फ़ील्ड्स में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ सहेजें। यह एप्लिकेशन-विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करेगा यदि [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान **Remarks:** यह प्रॉपर्टी केवल glTF 1.0 के लिए काम करती है। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

