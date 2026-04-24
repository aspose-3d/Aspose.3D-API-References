---
title: ZipArchiveFileSystem
second_title: Aspose.3D for Java API Reference
description: फ़ाइल सिस्टम जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-पढ़ने योग्य पहुँच प्रदान करता है।
type: docs
weight: 221
url: /hi/java/com.aspose.threed/ziparchivefilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class ZipArchiveFileSystem extends FileSystem
```

फ़ाइल सिस्टम जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-पढ़ने योग्य पहुँच प्रदान करता है। फ़ाइल सिस्टम को खुलने/सहेजने के ऑपरेशन के बाद नष्ट कर दिया जाएगा। **Example:** निम्नलिखित कोड दिखाता है कि फ़ाइल को कैसे आयात करें, और ज़िप आर्काइव फ़ाइल में निर्भर फ़ाइलें प्रदान करें।

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new ZipArchiveFileSystem("textures.zip"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [ZipArchiveFileSystem(Stream stream, String baseDir)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-) | एक स्ट्रीम के माध्यम से [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) बनाएं। |
| [ZipArchiveFileSystem(Stream stream)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-) | एक स्ट्रीम के माध्यम से [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) बनाएं। |
| [ZipArchiveFileSystem(String fileName)](#ZipArchiveFileSystem-java.lang.String-) | फ़ाइल नाम के माध्यम से [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) बनाएं। |
## Methods

| Method | विवरण |
| --- | --- |
| [close()](#close--) | ZipArchiveFileSystem को नष्ट करें और उसकी आंतरिक संसाधनों को मुक्त करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | फ़ाइल को पढ़ने के लिए खोलें |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | फ़ाइल को लिखने के लिए खोलें, इस वर्ग में लागू नहीं है। |
### ZipArchiveFileSystem(Stream stream, String baseDir) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-}
```
public ZipArchiveFileSystem(Stream stream, String baseDir)
```


एक स्ट्रीम के माध्यम से [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | com.aspose.csporter.helpers.Stream |  |
| baseDir | java.lang.String |  |

### ZipArchiveFileSystem(Stream stream) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-}
```
public ZipArchiveFileSystem(Stream stream)
```


एक स्ट्रीम के माध्यम से [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | com.aspose.csporter.helpers.Stream |  |

### ZipArchiveFileSystem(String fileName) {#ZipArchiveFileSystem-java.lang.String-}
```
public ZipArchiveFileSystem(String fileName)
```


फ़ाइल नाम के माध्यम से [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |

### close() {#close--}
```
public void close()
```


ZipArchiveFileSystem को नष्ट करें और उसकी आंतरिक संसाधनों को मुक्त करें।

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


फ़ाइल को पढ़ने के लिए खोलें

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


फ़ाइल को लिखने के लिए खोलें, इस वर्ग में लागू नहीं है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
