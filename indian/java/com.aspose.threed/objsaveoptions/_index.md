---
title: "ObjSaveOptions"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "Wavefront obj फ़ाइल के लिए सहेजने विकल्प।"
type: docs
weight: 116
url: /hi/java/com.aspose.threed/objsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class ObjSaveOptions extends SaveOptions
```

Wavefront obj फ़ाइल के लिए सहेजने विकल्प।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ObjSaveOptions()](#ObjSaveOptions--) | कंस्ट्रक्टर [ObjSaveOptions](../../com.aspose.threed/objsaveoptions) का |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। |
| [getAxisSystem()](#getAxisSystem--) | निर्यातित फ़ाइल में अक्ष प्रणाली प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getEnableMaterials()](#getEnableMaterials--) | प्रत्येक ऑब्जेक्ट के लिए आयात/निर्यात सामग्री की स्थिति प्राप्त करता है |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getExportTextures()](#getExportTextures--) | सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [getFileFormat()](#getFileFormat--) | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल के फ़्लिप कोऑर्डिनेट सिस्टम की स्थिति प्राप्त करता है। |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [getPointCloud()](#getPointCloud--) | फ़्लैग प्राप्त करता है कि क्या एक्सपोर्टर को सीन को पॉइंट क्लाउड (टोपोलॉजिकल संरचना के बिना) के रूप में निर्यात करना चाहिए, डिफ़ॉल्ट मान false है। |
| [getSerializeW()](#getSerializeW--) | मॉडल के वर्टेक्स स्थिति में W घटक को सीरियलाइज़ करने की स्थिति प्राप्त करता है। |
| [getVerbose()](#getVerbose--) | प्रत्येक सेक्शन के लिए टिप्पणियाँ उत्पन्न करने की स्थिति प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | मेश पर [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) लागू करें। |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | निर्यातित फ़ाइल में अक्ष प्रणाली सेट करता है। |
| [setEnableMaterials(boolean value)](#setEnableMaterials-boolean-) | प्रत्येक ऑब्जेक्ट के लिए आयात/निर्यात सामग्री की स्थिति सेट करता है। |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | सीन में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल के फ़्लिप कोऑर्डिनेट सिस्टम की स्थिति सेट करता है। |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | फ़्लैग सेट करता है कि क्या एक्सपोर्टर को सीन को पॉइंट क्लाउड (टोपोलॉजिकल संरचना के बिना) के रूप में निर्यात करना चाहिए, डिफ़ॉल्ट मान false है। |
| [setSerializeW(boolean value)](#setSerializeW-boolean-) | सेट करता है कि मॉडल के वर्टेक्स स्थिति में W घटक को सीरियलाइज़ किया जाए या नहीं। |
| [setVerbose(boolean value)](#setVerbose-boolean-) | सेट करता है कि प्रत्येक सेक्शन के लिए टिप्पणी उत्पन्न की जाए या नहीं। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ObjSaveOptions() {#ObjSaveOptions--}
```
public ObjSaveOptions()
```


कंस्ट्रक्टर [ObjSaveOptions](../../com.aspose.threed/objsaveoptions) का

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


निर्यातित फ़ाइल में अक्ष प्रणाली प्राप्त करता है।

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableMaterials() {#getEnableMaterials--}
```
public boolean getEnableMaterials()
```


प्रत्येक ऑब्जेक्ट के लिए आयात/निर्यात सामग्री की स्थिति प्राप्त करता है

**Returns:**
बूलियन - क्या प्रत्येक ऑब्जेक्ट के लिए सामग्री आयात/निर्यात की जाए।
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल के फ़्लिप कोऑर्डिनेट सिस्टम की स्थिति प्राप्त करता है।

**Returns:**
boolean - इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल के फ़्लिप कोऑर्डिनेट सिस्टम की स्थिति।
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
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


फ़्लैग प्राप्त करता है कि क्या एक्सपोर्टर को सीन को पॉइंट क्लाउड (टोपोलॉजिकल संरचना के बिना) के रूप में निर्यात करना चाहिए, डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन - यह फ़्लैग कि एक्सपोर्टर को सीन को पॉइंट क्लाउड (बिना टोपोलॉजिकल संरचना) के रूप में निर्यात करना चाहिए या नहीं, डिफ़ॉल्ट मान false है।
### getSerializeW() {#getSerializeW--}
```
public boolean getSerializeW()
```


मॉडल के वर्टेक्स स्थिति में W घटक को सीरियलाइज़ करने की स्थिति प्राप्त करता है।

**Returns:**
बूलियन - क्या मॉडल के वर्टेक्स स्थिति में W घटक को सीरियलाइज़ किया जाए।
### getVerbose() {#getVerbose--}
```
public boolean getVerbose()
```


प्रत्येक सेक्शन के लिए टिप्पणियाँ उत्पन्न करने की स्थिति प्राप्त करता है।

**Returns:**
बूलियन - क्या प्रत्येक सेक्शन के लिए टिप्पणी उत्पन्न की जाए।
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

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


निर्यातित फ़ाइल में अक्ष प्रणाली सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | नई मान **Remarks:** इस सुविधा का उपयोग करने के लिए FlipCoordinateSystem को सक्षम होना चाहिए। |

### setEnableMaterials(boolean value) {#setEnableMaterials-boolean-}
```
public void setEnableMaterials(boolean value)
```


प्रत्येक ऑब्जेक्ट के लिए आयात/निर्यात सामग्री की स्थिति सेट करता है।

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


इम्पोर्ट/एक्सपोर्ट के दौरान कंट्रोल पॉइंट्स/नॉर्मल के फ़्लिप कोऑर्डिनेट सिस्टम की स्थिति सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

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

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


फ़्लैग सेट करता है कि क्या एक्सपोर्टर को सीन को पॉइंट क्लाउड (टोपोलॉजिकल संरचना के बिना) के रूप में निर्यात करना चाहिए, डिफ़ॉल्ट मान false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setSerializeW(boolean value) {#setSerializeW-boolean-}
```
public void setSerializeW(boolean value)
```


सेट करता है कि मॉडल के वर्टेक्स स्थिति में W घटक को सीरियलाइज़ किया जाए या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setVerbose(boolean value) {#setVerbose-boolean-}
```
public void setVerbose(boolean value)
```


सेट करता है कि प्रत्येक सेक्शन के लिए टिप्पणी उत्पन्न की जाए या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

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

