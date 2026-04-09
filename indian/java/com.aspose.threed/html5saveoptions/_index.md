---
title: Html5SaveOptions
second_title: Aspose.3D for Java API Reference
description: HTML5 के लिए सहेजने विकल्प
type: docs
weight: 80
url: /hi/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

HTML5 के लिए सहेजने विकल्प
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) का कंस्ट्रक्टर सभी डिफ़ॉल्ट सेटिंग्स के साथ। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | कैमरा की प्रारंभिक स्थिति प्राप्त करता है, डिफ़ॉल्ट मान (10, 10, 10) है। |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getExportTextures()](#getExportTextures--) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [getFarPlane()](#getFarPlane--) | कैमरा की फार प्लेन प्राप्त करता है, डिफ़ॉल्ट मान 1000 है। |
| [getFieldOfView()](#getFieldOfView--) | व्यू का फ़ील्ड प्राप्त करता है, डिफ़ॉल्ट मान 45 है, डिग्री में मापा गया। |
| [getFileFormat()](#getFileFormat--) | वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getLookAt()](#getLookAt--) | डिफ़ॉल्ट लुक एट स्थिति प्राप्त करता है, डिफ़ॉल्ट मान (0, 0, 0) है। |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [getNearPlane()](#getNearPlane--) | कैमरा की नियर प्लेन प्राप्त करता है, डिफ़ॉल्ट मान 1 है। |
| [getOrientationBox()](#getOrientationBox--) | एक ओरिएंटेशन बॉक्स प्रदर्शित करें। |
| [getShowGrid()](#getShowGrid--) | सीन में एक ग्रिड प्रदर्शित करें। |
| [getShowRulers()](#getShowRulers--) | मॉडल को मापने के लिए सीन में x/y/z अक्षों के रूलर प्रदर्शित करें। |
| [getShowUI()](#getShowUI--) | सीन में एक सरल UI प्रदर्शित करें। |
| [getUpVector()](#getUpVector--) | ऊपर वेक्टर प्राप्त करता है, मान "x"/"y"/"z" हो सकता है, डिफ़ॉल्ट मान "y" है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | कैमरा की प्रारंभिक स्थिति सेट करता है, डिफ़ॉल्ट मान (10, 10, 10) है |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [setFarPlane(double value)](#setFarPlane-double-) | कैमरा की फ़ार प्लेन सेट करता है, डिफ़ॉल्ट मान 1000 है। |
| [setFieldOfView(double value)](#setFieldOfView-double-) | व्यू का फ़ील्ड सेट करता है, डिफ़ॉल्ट मान 45 है, डिग्री में मापा गया। |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | डिफ़ॉल्ट लुक एट स्थिति सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [setNearPlane(double value)](#setNearPlane-double-) | कैमरा की नियर प्लेन सेट करता है, डिफ़ॉल्ट मान 1 है |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | एक ओरिएंटेशन बॉक्स प्रदर्शित करें। |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | सीन में एक ग्रिड प्रदर्शित करें। |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | मॉडल को मापने के लिए सीन में x/y/z अक्षों के रूलर प्रदर्शित करें। |
| [setShowUI(boolean value)](#setShowUI-boolean-) | सीन में एक सरल UI प्रदर्शित करें। |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | ऊपर वेक्टर सेट करता है, मान "x"/"y"/"z" हो सकता है, डिफ़ॉल्ट मान "y" है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


[Html5SaveOptions](../../com.aspose.threed/html5saveoptions) का कंस्ट्रक्टर सभी डिफ़ॉल्ट सेटिंग्स के साथ।

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
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


कैमरा की प्रारंभिक स्थिति प्राप्त करता है, डिफ़ॉल्ट मान (10, 10, 10) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the initial position of the camera, default value is (10, 10, 10)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


कैमरा की फार प्लेन प्राप्त करता है, डिफ़ॉल्ट मान 1000 है।

**Returns:**
double - कैमरा की फ़ार प्लेन, डिफ़ॉल्ट मान 1000 है।
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


व्यू का फ़ील्ड प्राप्त करता है, डिफ़ॉल्ट मान 45 है, डिग्री में मापा गया।

**Returns:**
double - व्यू का फ़ील्ड, डिफ़ॉल्ट मान 45 है, डिग्री में मापा गया।
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
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


डिफ़ॉल्ट लुक एट स्थिति प्राप्त करता है, डिफ़ॉल्ट मान (0, 0, 0) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
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
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


कैमरा की नियर प्लेन प्राप्त करता है, डिफ़ॉल्ट मान 1 है।

**Returns:**
double - कैमरा की नियर प्लेन, डिफ़ॉल्ट मान 1 है
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


एक ओरिएंटेशन बॉक्स प्रदर्शित करें। डिफ़ॉल्ट मान true है।

**Returns:**
boolean - एक ओरिएंटेशन बॉक्स प्रदर्शित करें। डिफ़ॉल्ट मान true है।
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


सीन में ग्रिड प्रदर्शित करें। डिफ़ॉल्ट मान true है।

**Returns:**
boolean - सीन में ग्रिड प्रदर्शित करें। डिफ़ॉल्ट मान true है।
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


मॉडल को मापने के लिए सीन में x/y/z अक्षों के रूलर प्रदर्शित करें। डिफ़ॉल्ट मान false है।

**Returns:**
boolean - सीन में x/y/z अक्षों के रूलर प्रदर्शित करें ताकि मॉडल को मापा जा सके। डिफ़ॉल्ट मान false है।
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


सीन में एक सरल UI प्रदर्शित करें। डिफ़ॉल्ट मान true है।

**Returns:**
boolean - सीन में एक सरल UI प्रदर्शित करें। डिफ़ॉल्ट मान true है।
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


ऊपर वेक्टर प्राप्त करता है, मान "x"/"y"/"z" हो सकता है, डिफ़ॉल्ट मान "y" है

**Returns:**
java.lang.String - ऊपर वेक्टर, मान "x"/"y"/"z" हो सकता है, डिफ़ॉल्ट मान "y" है
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




### setCameraPosition(Vector3 value) {#setCameraPosition-com.aspose.threed.Vector3-}
```
public void setCameraPosition(Vector3 value)
```


कैमरा की प्रारंभिक स्थिति सेट करता है, डिफ़ॉल्ट मान (10, 10, 10) है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


कैमरा की फ़ार प्लेन सेट करता है, डिफ़ॉल्ट मान 1000 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


व्यू का फ़ील्ड सेट करता है, डिफ़ॉल्ट मान 45 है, डिग्री में मापा गया।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


डिफ़ॉल्ट लुक एट स्थिति सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

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

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


कैमरा की नियर प्लेन सेट करता है, डिफ़ॉल्ट मान 1 है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


एक ओरिएंटेशन बॉक्स प्रदर्शित करें। डिफ़ॉल्ट मान true है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


सीन में ग्रिड प्रदर्शित करें। डिफ़ॉल्ट मान true है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


मॉडल को मापने के लिए सीन में x/y/z अक्षों के रूलर प्रदर्शित करें। डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


सीन में एक सरल UI प्रदर्शित करें। डिफ़ॉल्ट मान true है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


ऊपर वेक्टर सेट करता है, मान "x"/"y"/"z" हो सकता है, डिफ़ॉल्ट मान "y" है

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

