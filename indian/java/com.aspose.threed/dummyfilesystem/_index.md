---
title: "DummyFileSystem"
second_title: "Aspose.3D for Java API Reference"
description: "रीड/राइट ऑपरेशन डमी ऑपरेशन हैं।"
type: docs
weight: 46
url: /hi/java/com.aspose.threed/dummyfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class DummyFileSystem extends FileSystem
```

रीड/राइट ऑपरेशन डमी ऑपरेशन हैं। **Example:** निम्नलिखित कोड दिखाता है कि फ़ाइल को मेमोरी में कैसे निर्यात किया जाए, और सभी निर्भर फ़ाइल जनरेशन को अनदेखा किया जाए।

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var dfs = new DummyFileSystem();
     opt.setFileSystem(dfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
```
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DummyFileSystem()](#DummyFileSystem--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [close()](#close--) | फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें। |
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
### DummyFileSystem() {#DummyFileSystem--}
```
public DummyFileSystem()
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
| पैरामीटर | प्रकार | विवरण |
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
public Stream readFile(String fileName, IOConfig options)
```


निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public Stream writeFile(String fileName, IOConfig options)
```


निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
