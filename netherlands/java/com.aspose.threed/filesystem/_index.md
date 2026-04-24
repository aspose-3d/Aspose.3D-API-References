---
title: FileSystem
second_title: Aspose.3D for Java API-referentie
description: Encapsulatie van het bestandssysteem.
type: docs
weight: 67
url: /nl/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Bestandssysteem encapsulatie. Aspose.3D zal dit gebruiken om afhankelijkheden te lezen/schrijven. **Example:** De volgende code toont hoe een bestand te importeren, en afhankelijke bestanden in een opgegeven map te leveren.

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

| Constructor | Beschrijving |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Maak het bestandssysteem vrij en geef de bronnen vrij. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Maak een dummy-bestandssysteem, lees-/schrijfbewerkingen zijn dummy-bewerkingen. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Initialiseer een nieuw [FileSystem](../../com.aspose.threed/filesystem) dat alleen toegang heeft tot de lokale map. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Maak een geheugen-gebaseerd bestandssysteem dat de lees-/schrijfbewerkingen naar het geheugen mappt. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Maak een geheugen-gebaseerd bestandssysteem dat de lees-/schrijfbewerkingen naar het geheugen mappt. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Maak een bestandssysteem om alleen-lezen toegang te bieden tot een opgegeven zip-bestand of zip-stream. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Maak een bestandssysteem om alleen-lezen toegang te bieden tot een opgegeven zip-bestand of zip-stream. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Bestandssysteem om alleen-lezen toegang te bieden tot een opgegeven zip‑bestand of zip‑stream. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Maak een stream aan voor het lezen van afhankelijkheden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Maak een stream aan voor het schrijven van afhankelijkheden. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Maak het bestandssysteem vrij en geef de bronnen vrij.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Maak een dummy-bestandssysteem, lees-/schrijfbewerkingen zijn dummy-bewerkingen.

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


Initialiseer een nieuw [FileSystem](../../com.aspose.threed/filesystem) dat alleen toegang heeft tot de lokale map. Alle lees-/schrijfbewerkingen op deze FileSystem-instantie worden gemapt naar de opgegeven map.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| map | java.lang.String | De map in uw fysieke bestandssysteem als de virtuele hoofdmap. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Maak een geheugen-gebaseerd bestandssysteem dat de lees-/schrijfbewerkingen naar het geheugen mappt.

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


Maak een geheugen-gebaseerd bestandssysteem dat de lees-/schrijfbewerkingen naar het geheugen mappt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestanden | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Dit stelt u in staat om de virtuele bestanden te lezen/schrijven. |

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


Maak een bestandssysteem om alleen-lezen toegang te bieden tot een opgegeven zip-bestand of zip-stream. Het bestandssysteem wordt verwijderd na de open-/opslaanbewerking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | De stream om toegang te krijgen tot het zip-bestand |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Maak een bestandssysteem om alleen-lezen toegang te bieden tot een opgegeven zip-bestand of zip-stream. Het bestandssysteem wordt verwijderd na de open-/opslaanbewerking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | De stream om toegang te krijgen tot het zip-bestand |
| baseDir | java.lang.String | De basismap binnen het zip-bestand. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Bestandssysteem om alleen-lezen toegang te bieden tot een opgegeven zip-bestand of zip-stream. Het bestandssysteem wordt verwijderd na de open-/opslaanbewerking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam van het zip-bestand. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Maak een stream aan voor het lezen van afhankelijkheden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam om te openen voor lezen |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opslaan of laadopties |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


Maak een stream aan voor het schrijven van afhankelijkheden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De bestandsnaam om te openen voor schrijven |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opslaan of laadopties |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
