---
title: LocalFileSystem
second_title: Aspose.3D for Java API Reference
description: यह पढ़ने/लिखने के संचालन को स्थानीय निर्देशिका में मैप करेगा।
type: docs
weight: 91
url: /hi/java/com.aspose.threed/localfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class LocalFileSystem extends FileSystem
```

The [LocalFileSystem](../../com.aspose.threed/localfilesystem) स्थानीय निर्देशिका के लिए पढ़ने/लिखने के संचालन को मैप करेगा। **Example:** निम्नलिखित कोड दिखाता है कि फ़ाइल कैसे आयात करें, और दिए गए निर्देशिका में निर्भर फ़ाइलें कैसे प्रदान करें

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
| [LocalFileSystem(String directory)](#LocalFileSystem-java.lang.String-) | निर्दिष्ट बेस डायरेक्टरी के साथ नया [LocalFileSystem](../../com.aspose.threed/localfilesystem) प्रारंभ करें। |
## Methods

| Method | विवरण |
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
### LocalFileSystem(String directory) {#LocalFileSystem-java.lang.String-}
```
public LocalFileSystem(String directory)
```


निर्दिष्ट बेस डायरेक्टरी के साथ नया [LocalFileSystem](../../com.aspose.threed/localfilesystem) प्रारंभ करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डायरेक्टरी | java.lang.String |  |

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
