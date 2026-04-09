---
title: FileSystem
second_title: Aspose.3D for Java API Reference
description: फ़ाइल सिस्टम का एन्कैप्सुलेशन।
type: docs
weight: 67
url: /hi/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

फ़ाइल सिस्टम एन्कैप्सुलेशन। Aspose.3D इसका उपयोग निर्भरताओं को पढ़ने/लिखने के लिए करेगा। **Example:** निम्नलिखित कोड दिखाता है कि फ़ाइल को कैसे आयात करें, और दिए गए निर्देशिका में निर्भर फ़ाइलें प्रदान करें।

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [close()](#close--) | फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें। |
| [createDummyFileSystem()](#createDummyFileSystem--) | डमी फ़ाइल सिस्टम बनाएं, पढ़ने/लिखने के संचालन डमी संचालन हैं। |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | नया [FileSystem](../../com.aspose.threed/filesystem) प्रारंभ करें जो केवल स्थानीय निर्देशिका तक पहुंचता है। |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | एक मेमोरी-आधारित फ़ाइल सिस्टम बनाएं जो पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा। |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | एक मेमोरी-आधारित फ़ाइल सिस्टम बनाएं जो पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा। |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | एक फ़ाइल सिस्टम बनाएं जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम के केवल-पढ़ने योग्य एक्सेस प्रदान करे। |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | एक फ़ाइल सिस्टम बनाएं जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम के केवल-पढ़ने योग्य एक्सेस प्रदान करे। |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | फ़ाइल सिस्टम जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-पढ़ने योग्य पहुँच प्रदान करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं। |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें।

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


डमी फ़ाइल सिस्टम बनाएं, पढ़ने/लिखने के संचालन डमी संचालन हैं।

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A dummy file system **Example:** The following code shows how to export file to memory, and ignore all dependent file generation.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var dfs = FileSystem.CreateDummyFileSystem();
     opt.setFileSystem(dfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
```
### createLocalFileSystem(String directory) {#createLocalFileSystem-java.lang.String-}
```
public static FileSystem createLocalFileSystem(String directory)
```


नया [FileSystem](../../com.aspose.threed/filesystem) प्रारंभ करें जो केवल स्थानीय निर्देशिका तक पहुंचता है। इस FileSystem इंस्टेंस पर सभी फ़ाइल पढ़ने/लिखने को निर्दिष्ट निर्देशिका में मैप किया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डायरेक्टरी | java.lang.String | आपके भौतिक फ़ाइल सिस्टम में निर्देशिका को वर्चुअल रूट निर्देशिका के रूप में उपयोग किया जाता है। |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


एक मेमोरी-आधारित फ़ाइल सिस्टम बनाएं जो पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा।

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createMemoryFileSystem(HashMap<String,MemoryStream> files) {#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--}
```
public static FileSystem createMemoryFileSystem(HashMap<String,MemoryStream> files)
```


एक मेमोरी-आधारित फ़ाइल सिस्टम बनाएं जो पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| फ़ाइलें | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | यह आपको वर्चुअल फ़ाइलें पढ़ने/लिखने की अनुमति देता है। |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createZipFileSystem(Stream stream) {#createZipFileSystem-com.aspose.threed.Stream-}
```
public static FileSystem createZipFileSystem(Stream stream)
```


एक फ़ाइल सिस्टम बनाएं जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम के केवल-पढ़ने योग्य एक्सेस प्रदान करे। फ़ाइल सिस्टम को खोलने/सहेजने के ऑपरेशन के बाद नष्ट कर दिया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | ज़िप फ़ाइल तक पहुंचने के लिए स्ट्रीम |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


एक फ़ाइल सिस्टम बनाएं जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम के केवल-पढ़ने योग्य एक्सेस प्रदान करे। फ़ाइल सिस्टम को खोलने/सहेजने के ऑपरेशन के बाद नष्ट कर दिया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | ज़िप फ़ाइल तक पहुंचने के लिए स्ट्रीम |
| baseDir | java.lang.String | ज़िप फ़ाइल के अंदर बेस निर्देशिका। |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


फ़ाइल सिस्टम जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम के केवल-पढ़ने योग्य एक्सेस प्रदान करता है। फ़ाइल सिस्टम को खोलने/सहेजने के ऑपरेशन के बाद नष्ट कर दिया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | ज़िप फ़ाइल का फ़ाइल नाम। |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### readFile(String fileName, IOConfig options) {#readFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream readFile(String fileName, IOConfig options)
```


निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल का नाम पढ़ने के लिए खोलने हेतु |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | सेव या लोड विकल्प |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for reading the file.
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

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल का नाम लिखने के लिए खोलने हेतु |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | सेव या लोड विकल्प |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
