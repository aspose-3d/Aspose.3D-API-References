---
title: ZipArchiveFileSystem
second_title: Aspose.3D for Java API-referens
description: Filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström.
type: docs
weight: 221
url: /sv/java/com.aspose.threed/ziparchivefilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class ZipArchiveFileSystem extends FileSystem
```

Filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. Filsystemet kommer att avyttras efter öppna/ spara‑operationen. **Example:** Följande kod visar hur man importerar en fil och tillhandahåller beroende filer i ett zip‑arkiv.

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new ZipArchiveFileSystem("textures.zip"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ZipArchiveFileSystem(Stream stream, String baseDir)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-) | Skapa ett [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) via en ström. |
| [ZipArchiveFileSystem(Stream stream)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-) | Skapa ett [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) via en ström. |
| [ZipArchiveFileSystem(String fileName)](#ZipArchiveFileSystem-java.lang.String-) | Skapa ett [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) via ett filnamn. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Frigör ZipArchiveFileSystem och släpp dess interna resurser. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Öppna fil för läsning |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Öppna fil för skrivning, inte implementerat i denna klass. |
### ZipArchiveFileSystem(Stream stream, String baseDir) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-}
```
public ZipArchiveFileSystem(Stream stream, String baseDir)
```


Skapa ett [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) via en ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.csporter.helpers.Stream |  |
| baseDir | java.lang.String |  |

### ZipArchiveFileSystem(Stream stream) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-}
```
public ZipArchiveFileSystem(Stream stream)
```


Skapa ett [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) via en ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.csporter.helpers.Stream |  |

### ZipArchiveFileSystem(String fileName) {#ZipArchiveFileSystem-java.lang.String-}
```
public ZipArchiveFileSystem(String fileName)
```


Skapa ett [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) via ett filnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String |  |

### close() {#close--}
```
public void close()
```


Frigör ZipArchiveFileSystem och släpp dess interna resurser.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Öppna fil för läsning

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public Stream writeFile(String fileName, IOConfig options)
```


Öppna fil för skrivning, inte implementerat i denna klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
