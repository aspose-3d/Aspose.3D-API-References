---
title: PlySaveOptions
second_title: Aspose.3D for Java API Reference
description: सीन को PLY फ़ाइल के रूप में निर्यात करने के लिए सहेजने के विकल्प।
type: docs
weight: 131
url: /hi/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

सीन को PLY फ़ाइल के रूप में निर्यात करने के लिए सहेजने के विकल्प।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) का कंस्ट्रक्टर |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) का कंस्ट्रक्टर |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | निर्यात किए गए stl फ़ाइल में अक्ष प्रणाली प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | वर्टेक्स रंग के घटक नाम, डिफ़ॉल्ट मान ("red", "green", "blue") है। |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getExportTextures()](#getExportTextures--) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [getFaceElement()](#getFaceElement--) | फ़ेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "face" है |
| [getFaceProperty()](#getFaceProperty--) | फ़ेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान "vertex\_index" है |
| [getFileFormat()](#getFileFormat--) | वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getFlipCoordinate()](#getFlipCoordinate--) | सीन को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [getNormalComponents()](#getNormalComponents--) | नॉर्मल डेटा के घटक नाम, डिफ़ॉल्ट मान ("nx", "ny", "nz") हैं |
| [getPointCloud()](#getPointCloud--) | सीन को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है। |
| [getPositionComponents()](#getPositionComponents--) | पोजीशन डेटा के घटक नाम, डिफ़ॉल्ट मान ("x", "y", "z") हैं |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | टेक्सचर कोऑर्डिनेट डेटा के घटक नाम, डिफ़ॉल्ट मान ("u", "v") हैं |
| [getVertexElement()](#getVertexElement--) | वर्टेक्स डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "vertex" है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | निर्यात किए गए STL फ़ाइल में अक्ष प्रणाली सेट करता है। |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | वर्टेक्स रंग के घटक नाम, डिफ़ॉल्ट मान ("red", "green", "blue") है। |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | फ़ेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "face" है |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | फ़ेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान "vertex\_index" है |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | सीन को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | नॉर्मल डेटा के घटक नाम, डिफ़ॉल्ट मान ("nx", "ny", "nz") हैं |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | सीन को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है। |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | पोजीशन डेटा के घटक नाम, डिफ़ॉल्ट मान ("x", "y", "z") हैं |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | टेक्सचर कोऑर्डिनेट डेटा के घटक नाम, डिफ़ॉल्ट मान ("u", "v") हैं |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | वर्टेक्स डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "vertex" है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions) का कंस्ट्रक्टर

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions) का कंस्ट्रक्टर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


निर्यात किए गए stl फ़ाइल में अक्ष प्रणाली प्राप्त करता है।

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported stl file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponents() {#getColorComponents--}
```
public Tuple_3<String,String,String> getColorComponents()
```


वर्टेक्स रंग के घटक नाम, डिफ़ॉल्ट मान ("red", "green", "blue") है।

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - वर्टेक्स रंग के घटक नाम, डिफ़ॉल्ट मान ("red", "green", "blue") हैं
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
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


फ़ेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "face" है

**Returns:**
java.lang.String - फ़ेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "face" है
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


फ़ेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान "vertex\_index" है

**Returns:**
java.lang.String - फ़ेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान "vertex\_index" है
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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


सीन को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है

**Returns:**
boolean - सीन को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है
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
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


नॉर्मल डेटा के घटक नाम, डिफ़ॉल्ट मान ("nx", "ny", "nz") हैं

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - नॉर्मल डेटा के घटक नाम, डिफ़ॉल्ट मान ("nx", "ny", "nz") हैं
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


सीन को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है।

**Returns:**
boolean - सीन को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है।
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


पोजीशन डेटा के घटक नाम, डिफ़ॉल्ट मान ("x", "y", "z") हैं

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - पोजीशन डेटा के घटक नाम, डिफ़ॉल्ट मान ("x", "y", "z") हैं
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


टेक्सचर कोऑर्डिनेट डेटा के घटक नाम, डिफ़ॉल्ट मान ("u", "v") हैं

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - टेक्सचर कोऑर्डिनेट डेटा के घटक नाम, डिफ़ॉल्ट मान ("u", "v") हैं
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


वर्टेक्स डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "vertex" है

**Returns:**
java.lang.String - वर्टेक्स डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "vertex" है
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




### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


निर्यात किए गए STL फ़ाइल में अक्ष प्रणाली सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | नया मान **Remarks:** इस सुविधा का उपयोग करने के लिए FlipCoordinateSystem को सक्षम होना चाहिए। |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


वर्टेक्स रंग के घटक नाम, डिफ़ॉल्ट मान ("red", "green", "blue") है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | नया मान |

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

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


फ़ेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "face" है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


फ़ेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान "vertex\_index" है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


सीन को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

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

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


नॉर्मल डेटा के घटक नाम, डिफ़ॉल्ट मान ("nx", "ny", "nz") हैं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | नया मान |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


सीन को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


पोजीशन डेटा के घटक नाम, डिफ़ॉल्ट मान ("x", "y", "z") हैं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | नया मान |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


टेक्सचर कोऑर्डिनेट डेटा के घटक नाम, डिफ़ॉल्ट मान ("u", "v") हैं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | नया मान |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


वर्टेक्स डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान "vertex" है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

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

