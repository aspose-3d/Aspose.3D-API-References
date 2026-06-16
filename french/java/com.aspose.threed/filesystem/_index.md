---
title: "FileSystem"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Encapsulation du système de fichiers."
type: docs
weight: 67
url: /fr/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Encapsulation du système de fichiers. Aspose.3D utilisera cela pour lire/écrire les dépendances. **Example:** Le code suivant montre comment importer un fichier et fournir les fichiers dépendants dans un répertoire donné

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Libérez le système de fichiers et libérez ses ressources. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Créez un système de fichiers factice, les opérations de lecture/écriture sont factices. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Initialisez un nouveau [FileSystem](../../com.aspose.threed/filesystem) qui n'accède qu'au répertoire local. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Créez un système de fichiers basé sur la mémoire qui mappe les opérations de lecture/écriture en mémoire. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Créez un système de fichiers basé sur la mémoire qui mappe les opérations de lecture/écriture en mémoire. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Créez un système de fichiers pour fournir un accès en lecture seule à un fichier zip spécifié ou à un flux zip. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Créez un système de fichiers pour fournir un accès en lecture seule à un fichier zip spécifié ou à un flux zip. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Système de fichiers fournissant un accès en lecture seule au fichier zip ou au flux zip spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Créez un flux pour lire les dépendances. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Créez un flux pour écrire les dépendances. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Libérez le système de fichiers et libérez ses ressources.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Créez un système de fichiers factice, les opérations de lecture/écriture sont factices.

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


Initialisez un nouveau [FileSystem](../../com.aspose.threed/filesystem) qui n'accède qu'au répertoire local. Toutes les lectures/écritures de fichiers sur cette instance FileSystem seront mappées au répertoire spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| répertoire | java.lang.String | Le répertoire de votre système de fichiers physique en tant que répertoire racine virtuel. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Créez un système de fichiers basé sur la mémoire qui mappe les opérations de lecture/écriture en mémoire.

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


Créez un système de fichiers basé sur la mémoire qui mappe les opérations de lecture/écriture en mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichiers | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Cela vous permet de lire/écrire les fichiers virtuels. |

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


Créez un système de fichiers pour fournir un accès en lecture seule à un fichier zip spécifié ou à un flux zip. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Le flux pour accéder au fichier zip |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Créez un système de fichiers pour fournir un accès en lecture seule à un fichier zip spécifié ou à un flux zip. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Le flux pour accéder au fichier zip |
| baseDir | java.lang.String | Le répertoire de base à l'intérieur du fichier zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Système de fichiers pour fournir un accès en lecture seule à un fichier zip spécifié ou à un flux zip. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier du zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Créez un flux pour lire les dépendances.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier à ouvrir en lecture |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Enregistrer ou charger les options |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


Créez un flux pour écrire les dépendances.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom du fichier à ouvrir en écriture |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Enregistrer ou charger les options |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
