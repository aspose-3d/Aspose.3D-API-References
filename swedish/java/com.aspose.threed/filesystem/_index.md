---
title: FileSystem
second_title: Aspose.3D for Java API-referens
description: Filssysteminkapsling.
type: docs
weight: 67
url: /sv/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Filsysteminkapsling. Aspose.3D kommer att använda detta för att läsa/skriva beroenden. **Exempel:** Följande kod visar hur man importerar en fil och tillhandahåller beroende filer i en given katalog

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
| [FileSystem()](#FileSystem--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Avsluta filsystemet och frigör dess resurser. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Skapa ett dummy-filsystem, läs/skriv‑operationer är dummy‑operationer. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Initiera ett nytt [FileSystem](../../com.aspose.threed/filesystem) som endast får åtkomst till en lokal katalog. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Skapa ett minnesbaserat filsystem som mappar läs/skriv‑operationerna till minnet. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Skapa ett minnesbaserat filsystem som mappar läs/skriv‑operationerna till minnet. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Skapa ett filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Skapa ett filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. |
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
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Avsluta filsystemet och frigör dess resurser.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Skapa ett dummy-filsystem, läs/skriv‑operationer är dummy‑operationer.

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


Initiera ett nytt [FileSystem](../../com.aspose.threed/filesystem) som endast får åtkomst till en lokal katalog. All läs/skriv av filer på detta FileSystem‑instans kommer att mappas till den specificerade katalogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| katalog | java.lang.String | Katalogen i ditt fysiska filsystem som den virtuella rotkatalogen. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Skapa ett minnesbaserat filsystem som mappar läs/skriv‑operationerna till minnet.

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


Skapa ett minnesbaserat filsystem som mappar läs/skriv‑operationerna till minnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filer | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Detta låter dig läsa/skriva de virtuella filerna. |

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


Skapa ett filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. Filsystemet kommer att avyttras efter öppna/spara‑operationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Strömmen för att komma åt zip‑filen |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Skapa ett filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. Filsystemet kommer att avyttras efter öppna/spara‑operationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Strömmen för att komma åt zip‑filen |
| baseDir | java.lang.String | Bas‑katalogen i zip‑filen. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Filsystem för att ge skrivskyddad åtkomst till en specificerad zip‑fil eller zip‑ström. Filsystemet kommer att avyttras efter öppna/spara‑operationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn till zip‑filen. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
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
public abstract Stream readFile(String fileName, IOConfig options)
```


Skapa en ström för att läsa beroenden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filens namn att öppna för läsning |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Spara eller ladda alternativ |

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
public abstract Stream writeFile(String fileName, IOConfig options)
```


Skapa en ström för att skriva beroenden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filens namn att öppna för skrivning |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Spara eller ladda alternativ |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
