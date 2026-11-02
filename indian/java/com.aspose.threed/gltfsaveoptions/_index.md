---
title: "GltfSaveOptions"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "glTF फ़ॉर्मेट के लिए सहेजने के विकल्प।"
type: docs
weight: 74
url: /hi/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

glTF फ़ॉर्मेट के लिए सहेजने के विकल्प।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का कंस्ट्रक्टर |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का कंस्ट्रक्टर |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। |
| [getBufferFile()](#getBufferFile--) | बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | जाँचता है कि क्या ड्रैको संपीड़न सक्षम किया जाए |
| [getEmbedAssets()](#getEmbedAssets--) | सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है। |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getExportTextures()](#getExportTextures--) | सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें। |
| [getFallbackNormal()](#getFallbackNormal--) | जब GLTF2 एक्सपोर्टर ने एक अमान्य नॉर्मल का पता लगाया, तो सत्यापन को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। |
| [getFileFormat()](#getFileFormat--) | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | टेक्सचर निर्देशांक v(t) घटक को उलटें, डिफ़ॉल्ट मान true है। |
| [getImageFormat()](#getImageFormat--) | Standard glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प निर्यात के दौरान Aspose.3D को गैर-मानक छवियों को समर्थित फ़ॉर्मेट में बदलने के लिए मार्गदर्शन करेगा। |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [getMaterialConverter()](#getMaterialConverter--) | कस्टम कन्वर्टर ज्योमेट्री की सामग्री को PBR सामग्री में बदलता है। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 एक्सपोर्टर स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। |
| [getPrettyPrint()](#getPrettyPrint--) | GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड होती है, डिफ़ॉल्ट मान false है। |
| [getSaveExtras()](#getSaveExtras--) | जेनरेटेड glTF फ़ाइल में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ को 'extra' फ़ील्ड्स में सहेजें। |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | बाइनरी डेटा संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | ड्रेको संपीड़न को सक्षम करने के लिए सेट करता है। |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है। |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें। |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | जब GLTF2 एक्सपोर्टर ने एक अमान्य नॉर्मल का पता लगाया, तो सत्यापन को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | टेक्सचर निर्देशांक v(t) घटक को उलटें, डिफ़ॉल्ट मान true है। |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Standard glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प निर्यात के दौरान Aspose.3D को गैर-मानक छवियों को समर्थित फ़ॉर्मेट में बदलने के लिए मार्गदर्शन करेगा। |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | कस्टम कन्वर्टर ज्योमेट्री की सामग्री को PBR सामग्री में बदलता है। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 एक्सपोर्टर स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड होती है, डिफ़ॉल्ट मान false है। |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | जेनरेटेड glTF फ़ाइल में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ को 'extra' फ़ील्ड्स में सहेजें। |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


[GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का कंस्ट्रक्टर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


[GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) का कंस्ट्रक्टर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


बाहरी बफ़र फ़ाइल का फ़ाइलनाम जो बाइनरी डेटा संग्रहीत करने के लिए उपयोग किया जाता है। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह बाइनरी मोड में glTF निर्यात करते समय अनदेखा किया जाता है।

**Returns:**
java.lang.String - बाहरी बफ़र फ़ाइल का फ़ाइलनाम जो बाइनरी डेटा संग्रहीत करने के लिए उपयोग किया जाता है। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह बाइनरी मोड में glTF निर्यात करते समय अनदेखा किया जाता है।
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


जाँचता है कि क्या ड्रैको संपीड़न सक्षम किया जाए

**Returns:**
boolean - ड्रेको संपीड़न को सक्षम करने के लिए।
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है।

**Returns:**
boolean - सभी बाहरी एसेट्स को base64 के रूप में एकल फ़ाइल में ASCII मोड में एम्बेड करें, डिफ़ॉल्ट मान false है।
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए।

**Returns:**
java.nio.charset.Charset - टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए।
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Returns:**
boolean - दृश्य में उपयोग की गई टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें।

**Returns:**
java.lang.String - ड्रेको एन्कोडर को बाहरी रूप से उपयोग करके ड्रेको संपीड़न गति को तेज़ करें। **Remarks:** Aspose.3D मेष को ड्रेको फ़ॉर्मेट में एन्कोड करने के लिए नया सब‑प्रोसेस बनाएगा, इसे अपने जोखिम पर उपयोग करें।
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


जब GLTF2 एक्सपोर्टर ने एक अमान्य नॉर्मल पाया, तो वैधता जांच को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। डिफ़ॉल्ट मान (0, 1, 0) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है।

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


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है।

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की कार्यान्वयन भी उपयोग कर सकते हैं।

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


FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर पर्यावरण के लिए उपयुक्त नहीं है।

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
boolean - टेक्सचर कोऑर्डिनेट v(t) घटक को फ़्लिप करें, डिफ़ॉल्ट मान true है।
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Standard glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प निर्यात के दौरान Aspose.3D को गैर-मानक छवियों को समर्थित फ़ॉर्मेट में बदलने के लिए मार्गदर्शन करेगा। डिफ़ॉल्ट मान है [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Returns:**
java.util.ArrayList<java.lang.String> - कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को बाहरी फ़ाइल खोजने और लोड करने की अनुमति देंगे। **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके

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


कस्टम कन्वर्टर ज्योमेट्री की सामग्री को PBR सामग्री में बदलता है। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 एक्सपोर्टर स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान null है। यह प्रॉपर्टी glTF 2.0 फ़ाइल में सीन निर्यात करते समय उपयोग की जाती है।

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड होती है, डिफ़ॉल्ट मान false है।

**Returns:**
boolean - GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड होती है, डिफ़ॉल्ट मान false है।
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


जेनरेटेड glTF फ़ाइल में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ को 'extra' फ़ील्ड्स में सहेजें। यह एप्लिकेशन‑विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है।

**Returns:**
boolean - जेनरेटेड glTF फ़ाइल में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ को 'extra' फ़ील्ड्स में सहेजें। यह एप्लिकेशन‑विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है।
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करेगा यदि [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) उपलब्ध है।

**Returns:**
boolean - KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करेगा यदि [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) उपलब्ध है। **Remarks:** यह प्रॉपर्टी केवल glTF 1.0 के लिए काम करती है।
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


बाहरी बफ़र फ़ाइल का फ़ाइलनाम जो बाइनरी डेटा संग्रहीत करने के लिए उपयोग किया जाता है। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह बाइनरी मोड में glTF निर्यात करते समय अनदेखा किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


ड्रेको संपीड़न को सक्षम करने के लिए सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


सभी बाहरी एसेट्स को बेस64 के रूप में ASCII मोड में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset | नया मान |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


ड्रैको संपीड़न गति को तेज़ करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान **Remarks:** Aspose.3D मेष को ड्रेको फ़ॉर्मेट में एन्कोड करने के लिए नया सब‑प्रोसेस बनाएगा, इसे अपने जोखिम पर उपयोग करें। |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


जब GLTF2 एक्सपोर्टर ने एक अमान्य नॉर्मल पाया, तो वैधता जांच को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। डिफ़ॉल्ट मान (0, 1, 0) है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | नया मान **Example:** डिफ़ॉल्ट FileSystem LocalFileSystem है, यह सर्वर-साइड जैसे पर्यावरण में सुरक्षित नहीं है, लेकिन आप फ़ाइल सिस्टम एक्सेस को अलग कार्यान्वयन निर्दिष्ट करके ओवरराइड कर सकते हैं। Aspose.3D विभिन्न FileSystem कार्यान्वयन प्रदान करता है जैसे: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की कार्यान्वयन भी उपयोग कर सकते हैं।

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


FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर पर्यावरण के लिए उपयुक्त नहीं है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | नया मान **Example:** SaveOptions/LoadOptions में डिफ़ॉल्ट FileSystem डायरेक्टरी-आधारित फ़ाइल सिस्टम है, आप इसे IOConfig.FileSystemFactory के माध्यम से निर्दिष्ट करके डिफ़ॉल्ट कार्यान्वयन को ओवरराइड कर सकते हैं। |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Standard glTF केवल PNG/JPG को अपनी टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प निर्यात के दौरान Aspose.3D को गैर-मानक छवियों को समर्थित फ़ॉर्मेट में बदलने के लिए मार्गदर्शन करेगा। डिफ़ॉल्ट मान है [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | नया मान |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.util.ArrayList<java.lang.String> | नया मान **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके |

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


कस्टम कन्वर्टर ज्योमेट्री की सामग्री को PBR सामग्री में बदलता है। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 एक्सपोर्टर स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान null है। यह प्रॉपर्टी glTF 2.0 फ़ाइल में सीन निर्यात करते समय उपयोग की जाती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | नया मान |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंटेड होती है, डिफ़ॉल्ट मान false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


जेनरेटेड glTF फ़ाइल में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ को 'extra' फ़ील्ड्स में सहेजें। यह एप्लिकेशन‑विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


KHR सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D एक सेट वर्टेक्स/फ़्रैगमेंट शेडर निर्यात करेगा यदि [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) उपलब्ध है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

