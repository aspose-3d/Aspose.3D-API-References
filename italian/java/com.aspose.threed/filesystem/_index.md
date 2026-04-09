---
title: FileSystem
second_title: Aspose.3D for Java API Reference
description: Incapsulamento del file system.
type: docs
weight: 67
url: /it/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Incapsulamento del file system. Aspose.3D utilizzerà questo per leggere/scrivere dipendenze. **Example:** Il codice seguente mostra come importare un file e fornire i file dipendenti in una directory specificata

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Rilascia il file system e libera le sue risorse. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Crea un file system fittizio, le operazioni di lettura/scrittura sono operazioni fittizie. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Inizializza un nuovo [FileSystem](../../com.aspose.threed/filesystem) che accede solo alla directory locale. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Crea un file system basato sulla memoria che mapperà le operazioni di lettura/scrittura in memoria. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Crea un file system basato sulla memoria che mapperà le operazioni di lettura/scrittura in memoria. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Crea un file system per fornire l'accesso in sola lettura a un file zip specificato o a uno stream zip. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Crea un file system per fornire l'accesso in sola lettura a un file zip specificato o a uno stream zip. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | File system per fornire l'accesso in sola lettura al file zip specificato o al flusso zip. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Crea uno stream per leggere le dipendenze. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Crea uno stream per scrivere le dipendenze. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Rilascia il file system e libera le sue risorse.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Crea un file system fittizio, le operazioni di lettura/scrittura sono operazioni fittizie.

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


Inizializza un nuovo [FileSystem](../../com.aspose.threed/filesystem) che accede solo alla directory locale. Tutte le operazioni di lettura/scrittura dei file su questa istanza di FileSystem saranno mappate alla directory specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| directory | java.lang.String | La directory nel tuo file system fisico come directory radice virtuale. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Crea un file system basato sulla memoria che mapperà le operazioni di lettura/scrittura in memoria.

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


Crea un file system basato sulla memoria che mapperà le operazioni di lettura/scrittura in memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Questo ti consente di leggere/scrivere i file virtuali. |

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


Crea un file system per fornire l'accesso in sola lettura a un file zip specificato o a uno stream zip. Il file system verrà eliminato dopo l'operazione di apertura/salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Lo stream per accedere al file zip |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Crea un file system per fornire l'accesso in sola lettura a un file zip specificato o a uno stream zip. Il file system verrà eliminato dopo l'operazione di apertura/salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Lo stream per accedere al file zip |
| baseDir | java.lang.String | La directory base all'interno del file zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


File system per fornire l'accesso in sola lettura a un file zip specificato o a uno stream zip. Il file system verrà eliminato dopo l'operazione di apertura/salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Crea uno stream per leggere le dipendenze.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file da aprire per la lettura |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opzioni di salvataggio o caricamento |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


Crea uno stream per scrivere le dipendenze.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome del file da aprire per scrittura |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opzioni di salvataggio o caricamento |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
