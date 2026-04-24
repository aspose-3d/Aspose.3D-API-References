---
title: RvmSaveOptions
second_title: Aspose.3D for Java API Reference
description: Aveva PDMS RVM फ़ाइल के लिए सहेजने के विकल्प।
type: docs
weight: 158
url: /hi/java/com.aspose.threed/rvmsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class RvmSaveOptions extends SaveOptions
```

Aveva PDMS RVM फ़ाइल के लिए सहेजने के विकल्प। **Example:** निम्नलिखित कोड दिखाता है कि RVM में गुण को कैसे निर्यात किया जाए।

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [RvmSaveOptions()](#RvmSaveOptions--) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) का कंस्ट्रक्टर |
| [RvmSaveOptions(FileContentType contentType)](#RvmSaveOptions-com.aspose.threed.FileContentType-) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) का कंस्ट्रक्टर |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributeListFile()](#getAttributeListFile--) | गुण सूची फ़ाइल का फ़ाइल नाम प्राप्त करता है, निर्यातकर्ता इस गुण के अपरिभाषित होने पर .rvm फ़ाइल नाम के आधार पर एक नाम उत्पन्न करेगा, डिफ़ॉल्ट मान null है। |
| [getAttributePrefix()](#getAttributePrefix--) | उन गुणों का उपसर्ग प्राप्त करता है जो निर्यात किए जाएंगे, निर्यातित गुण में कोई उपसर्ग नहीं होगा, विभिन्न उपसर्ग वाले कस्टम गुण निर्यात नहीं किए जाएंगे, डिफ़ॉल्ट मान 'rvm:' है। |
| [getAuthor()](#getAuthor--) | लेखक जानकारी, डिफ़ॉल्ट मान '3d@aspose' है |
| [getClass()](#getClass--) |  |
| [getCreationTime()](#getCreationTime--) | इस फ़ाइल को निर्यात करने वाला टाइमस्टैम्प, डिफ़ॉल्ट मान वर्तमान समय है |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getExportAttributes()](#getExportAttributes--) | जाँचता है कि क्या एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात किया जाए, डिफ़ॉल्ट मान false है। |
| [getExportTextures()](#getExportTextures--) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [getFileFormat()](#getFileFormat--) | वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [getFileNote()](#getFileNote--) | फ़ाइल हेडर में फ़ाइल नोट। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributeListFile(String value)](#setAttributeListFile-java.lang.String-) | एट्रिब्यूट सूची फ़ाइल का फ़ाइल नाम सेट करता है, जब यह प्रॉपर्टी अपरिभाषित हो तो निर्यातकर्ता .rvm फ़ाइल नाम के आधार पर नाम उत्पन्न करेगा, डिफ़ॉल्ट मान null है। |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | निर्यात होने वाले एट्रिब्यूट्स का प्रीफ़िक्स सेट करता है, निर्यातित प्रॉपर्टी में कोई प्रीफ़िक्स नहीं होगा, अलग प्रीफ़िक्स वाले कस्टम प्रॉपर्टी निर्यात नहीं होंगे, डिफ़ॉल्ट मान 'rvm:' है। |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | लेखक जानकारी, डिफ़ॉल्ट मान '3d@aspose' है |
| [setCreationTime(String value)](#setCreationTime-java.lang.String-) | इस फ़ाइल को निर्यात करने वाला टाइमस्टैम्प, डिफ़ॉल्ट मान वर्तमान समय है |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setExportAttributes(boolean value)](#setExportAttributes-boolean-) | एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात करना है या नहीं सेट करता है, डिफ़ॉल्ट मान false है। |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [setFileNote(String value)](#setFileNote-java.lang.String-) | फ़ाइल हेडर में फ़ाइल नोट। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmSaveOptions() {#RvmSaveOptions--}
```
public RvmSaveOptions()
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) का कंस्ट्रक्टर

### RvmSaveOptions(FileContentType contentType) {#RvmSaveOptions-com.aspose.threed.FileContentType-}
```
public RvmSaveOptions(FileContentType contentType)
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) का कंस्ट्रक्टर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | टेक्स्ट या बाइनरी RVM फ़ाइल? |

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
### getAttributeListFile() {#getAttributeListFile--}
```
public String getAttributeListFile()
```


गुण सूची फ़ाइल का फ़ाइल नाम प्राप्त करता है, निर्यातकर्ता इस गुण के अपरिभाषित होने पर .rvm फ़ाइल नाम के आधार पर एक नाम उत्पन्न करेगा, डिफ़ॉल्ट मान null है।

**Returns:**
java.lang.String - एट्रिब्यूट सूची फ़ाइल का फ़ाइल नाम, जब यह प्रॉपर्टी अपरिभाषित हो तो निर्यातकर्ता .rvm फ़ाइल नाम के आधार पर नाम उत्पन्न करेगा, डिफ़ॉल्ट मान null है। **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें।

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


जाँचता है कि कौन से एट्रिब्यूट्स का प्रीफ़िक्स निर्यात होगा, निर्यातित प्रॉपर्टी में कोई प्रीफ़िक्स नहीं होगा, अलग प्रीफ़िक्स वाले कस्टम प्रॉपर्टी निर्यात नहीं होंगे, डिफ़ॉल्ट मान 'rvm:' है। उदाहरण के लिए यदि प्रॉपर्टी rvm:Refno=345 है, तो निर्यातित एट्रिब्यूट Refno = 345 होगा, प्रीफ़िक्स हटाया जाएगा।

**Returns:**
java.lang.String - निर्यात होने वाले एट्रिब्यूट्स का प्रीफ़िक्स, निर्यातित प्रॉपर्टी में कोई प्रीफ़िक्स नहीं होगा, अलग प्रीफ़िक्स वाले कस्टम प्रॉपर्टी निर्यात नहीं होंगे, डिफ़ॉल्ट मान 'rvm:' है। उदाहरण के लिए यदि प्रॉपर्टी rvm:Refno=345 है, तो निर्यातित एट्रिब्यूट Refno = 345 होगा, प्रीफ़िक्स हटाया जाएगा। **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें।

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


लेखक जानकारी, डिफ़ॉल्ट मान '3d@aspose' है

**Returns:**
java.lang.String - लेखक जानकारी, डिफ़ॉल्ट मान '3d@aspose' है **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें।

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationTime() {#getCreationTime--}
```
public String getCreationTime()
```


इस फ़ाइल को निर्यात करने वाला टाइमस्टैम्प, डिफ़ॉल्ट मान वर्तमान समय है

**Returns:**
java.lang.String - इस फ़ाइल को निर्यात करने वाला टाइमस्टैम्प, डिफ़ॉल्ट मान वर्तमान समय है
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।

**Returns:**
java.nio.charset.Charset - टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।
### getExportAttributes() {#getExportAttributes--}
```
public boolean getExportAttributes()
```


जाँचता है कि क्या एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात किया जाए, डिफ़ॉल्ट मान false है।

**Returns:**
boolean - एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात करना है या नहीं, डिफ़ॉल्ट मान false है। **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें।

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Returns:**
boolean - दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।
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
### getFileNote() {#getFileNote--}
```
public String getFileNote()
```


फ़ाइल हेडर में फ़ाइल नोट।

**Returns:**
java.lang.String - फ़ाइल हेडर में फ़ाइल नोट। **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें।

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
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




### setAttributeListFile(String value) {#setAttributeListFile-java.lang.String-}
```
public void setAttributeListFile(String value)
```


एट्रिब्यूट सूची फ़ाइल का फ़ाइल नाम सेट करता है, जब यह प्रॉपर्टी अपरिभाषित हो तो निर्यातकर्ता .rvm फ़ाइल नाम के आधार पर नाम उत्पन्न करेगा, डिफ़ॉल्ट मान null है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | नया मान **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें। |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


निर्यात होने वाले एट्रिब्यूट्स का प्रीफ़िक्स सेट करता है, निर्यातित प्रॉपर्टी में कोई प्रीफ़िक्स नहीं होगा, अलग प्रीफ़िक्स वाले कस्टम प्रॉपर्टी निर्यात नहीं होंगे, डिफ़ॉल्ट मान 'rvm:' है। उदाहरण के लिए यदि प्रॉपर्टी rvm:Refno=345 है, तो निर्यातित एट्रिब्यूट Refno = 345 होगा, प्रीफ़िक्स हटाया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | नया मान **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें। |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


लेखक जानकारी, डिफ़ॉल्ट मान '3d@aspose' है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | नया मान **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें। |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setCreationTime(String value) {#setCreationTime-java.lang.String-}
```
public void setCreationTime(String value)
```


इस फ़ाइल को निर्यात करने वाला टाइमस्टैम्प, डिफ़ॉल्ट मान वर्तमान समय है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सी एन्कोडिंग उपयोग करनी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset | नया मान |

### setExportAttributes(boolean value) {#setExportAttributes-boolean-}
```
public void setExportAttributes(boolean value)
```


एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात करना है या नहीं सेट करता है, डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | नया मान **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें। |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


दृश्य में उपयोग किए गए टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setFileNote(String value) {#setFileNote-java.lang.String-}
```
public void setFileNote(String value)
```


फ़ाइल हेडर में फ़ाइल नोट।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | नया मान **Example:** निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें। |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

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

