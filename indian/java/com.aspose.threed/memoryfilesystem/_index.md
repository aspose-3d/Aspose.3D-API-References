---
title: MemoryFileSystem
second_title: Aspose.3D for Java API Reference
description: यह  पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा।
type: docs
weight: 95
url: /hi/java/com.aspose.threed/memoryfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class MemoryFileSystem extends FileSystem
```

यह [MemoryFileSystem](../../com.aspose.threed/memoryfilesystem) पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा। **Example:** निम्नलिखित कोड दिखाता है कि फ़ाइल को मेमोरी में कैसे निर्यात किया जाए, और MemoryFileSystem का उपयोग करके निर्भर फ़ाइल को शामिल करता है।

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new MemoryFileSystem();
     opt.setFileSystem(mfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.getFileContent("test.mtl");
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [MemoryFileSystem()](#MemoryFileSystem--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [close()](#close--) | फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileContent(String fileName)](#getFileContent-java.lang.String-) | निर्दिष्ट फ़ाइल की कच्ची सामग्री लौटाता है। |
| [getFileNames()](#getFileNames--) | फ़ाइल नाम जो इस मेमोरी फ़ाइल सिस्टम में हैं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं। |
### MemoryFileSystem() {#MemoryFileSystem--}
```
public MemoryFileSystem()
```


### close() {#close--}
```
public void close()
```


फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें।

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
### getFileContent(String fileName) {#getFileContent-java.lang.String-}
```
public byte[] getFileContent(String fileName)
```


निर्दिष्ट फ़ाइल की कच्ची सामग्री लौटाता है। यदि निर्दिष्ट फ़ाइल मौजूद नहीं है तो java.io.FileNotFoundException फेंके।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
byte[]
### getFileNames() {#getFileNames--}
```
public List<String> getFileNames()
```


फ़ाइल नाम जो इस मेमोरी फ़ाइल सिस्टम में हैं।

**Returns:**
java.util.List<java.lang.String>
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
public Stream readFile(String fileName, IOConfig options)
```


निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
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
public Stream writeFile(String fileName, IOConfig options)
```


निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
