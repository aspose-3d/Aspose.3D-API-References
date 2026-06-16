---
title: FileSystem
second_title: Referencia de API de Aspose.3D para Java
description: Encapsulación del sistema de archivos.
type: docs
weight: 67
url: /es/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Encapsulación del sistema de archivos. Aspose.3D usará esto para leer/escribir dependencias. **Example:** El siguiente código muestra cómo importar un archivo y proporcionar archivos dependientes en un directorio dado

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Libere el sistema de archivos y libere sus recursos. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Crea un sistema de archivos ficticio, las operaciones de lectura/escritura son operaciones ficticias. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Inicializa un nuevo [FileSystem](../../com.aspose.threed/filesystem) que solo accede al directorio local. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Crea un sistema de archivos basado en memoria que asignará las operaciones de lectura/escritura a la memoria. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Crea un sistema de archivos basado en memoria que asignará las operaciones de lectura/escritura a la memoria. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Crea un sistema de archivos para proporcionar acceso de solo lectura a un archivo zip especificado o a un flujo zip. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Crea un sistema de archivos para proporcionar acceso de solo lectura a un archivo zip especificado o a un flujo zip. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Sistema de archivos para proporcionar acceso de solo lectura a un archivo zip especificado o a un flujo zip. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Cree un flujo para leer dependencias. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Cree un flujo para escribir dependencias. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Libere el sistema de archivos y libere sus recursos.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Crea un sistema de archivos ficticio, las operaciones de lectura/escritura son operaciones ficticias.

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


Inicializa un nuevo [FileSystem](../../com.aspose.threed/filesystem) que solo accede al directorio local. Todas las lecturas/escrituras de archivos en esta instancia de FileSystem se asignarán al directorio especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| directorio | java.lang.String | El directorio en tu sistema de archivos físico como el directorio raíz virtual. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Crea un sistema de archivos basado en memoria que asignará las operaciones de lectura/escritura a la memoria.

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


Crea un sistema de archivos basado en memoria que asignará las operaciones de lectura/escritura a la memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivos | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Esto le permite leer/escribir los archivos virtuales. |

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


Crea un sistema de archivos para proporcionar acceso de solo lectura a un archivo zip especificado o a un flujo zip. El sistema de archivos se eliminará después de la operación de abrir/guardar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | El flujo para acceder al archivo zip |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Crea un sistema de archivos para proporcionar acceso de solo lectura a un archivo zip especificado o a un flujo zip. El sistema de archivos se eliminará después de la operación de abrir/guardar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | El flujo para acceder al archivo zip |
| baseDir | java.lang.String | El directorio base dentro del archivo zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Sistema de archivos para proporcionar acceso de solo lectura a un archivo zip especificado o a un flujo zip. El sistema de archivos se eliminará después de la operación de abrir/guardar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre de archivo del zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Cree un flujo para leer dependencias.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo para abrir en modo lectura |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opciones de guardar o cargar |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


Cree un flujo para escribir dependencias.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre del archivo para abrir en modo escritura |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Opciones de guardar o cargar |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
