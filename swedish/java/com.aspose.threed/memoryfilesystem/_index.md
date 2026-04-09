---
title: MemoryFileSystem
second_title: Aspose.3D for Java API-referens
description: Den  kommer att mappa läs-/skrivoperationerna till minnet.
type: docs
weight: 95
url: /sv/java/com.aspose.threed/memoryfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class MemoryFileSystem extends FileSystem
```

Den [MemoryFileSystem](../../com.aspose.threed/memoryfilesystem) kommer att mappa läs-/skrivoperationerna till minnet. **Example:** Följande kod visar hur man exporterar en fil till minnet, inkluderar den beroende filen genom att använda MemoryFileSystem.

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MemoryFileSystem()](#MemoryFileSystem--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Avsluta filsystemet och frigör dess resurser. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileContent(String fileName)](#getFileContent-java.lang.String-) | Returnerar det råa innehållet i den angivna filen. |
| [getFileNames()](#getFileNames--) | Filnamn som finns i detta minnesfilsystem. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Skapa en ström för att läsa beroenden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Skapa en ström för att skriva beroenden. |
### MemoryFileSystem() {#MemoryFileSystem--}
```
public MemoryFileSystem()
```


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
### getFileContent(String fileName) {#getFileContent-java.lang.String-}
```
public byte[] getFileContent(String fileName)
```


Returnerar det råa innehållet i den angivna filen. Kastar java.io.FileNotFoundException om den angivna filen inte finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
byte[]
### getFileNames() {#getFileNames--}
```
public List<String> getFileNames()
```


Filnamn som finns i detta minnesfilsystem.

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
