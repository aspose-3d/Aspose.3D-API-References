---
title: LocalFileSystem
second_title: Aspose.3D for Java API-referens
description: Den  kommer att mappa läs/skriv‑operationerna till en lokal katalog.
type: docs
weight: 91
url: /sv/java/com.aspose.threed/localfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class LocalFileSystem extends FileSystem
```

Den [LocalFileSystem](../../com.aspose.threed/localfilesystem) kommer att mappa läs/skriv‑operationerna till en lokal katalog. **Example:** Följande kod visar hur man importerar en fil och tillhandahåller beroende filer i en given katalog

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LocalFileSystem(String directory)](#LocalFileSystem-java.lang.String-) | Initiera ett nytt [LocalFileSystem](../../com.aspose.threed/localfilesystem) med angiven baskatalog. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Avsluta filsystemet och frigör dess resurser. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Skapa en ström för att läsa beroenden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Skapa en ström för att skriva beroenden. |
### LocalFileSystem(String directory) {#LocalFileSystem-java.lang.String-}
```
public LocalFileSystem(String directory)
```


Initiera ett nytt [LocalFileSystem](../../com.aspose.threed/localfilesystem) med angiven baskatalog.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| katalog | java.lang.String |  |

### close() {#close--}
```
public void close()
```


Avsluta filsystemet och frigör dess resurser.

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


Skapa en ström för att läsa beroenden.

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


Skapa en ström för att skriva beroenden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
