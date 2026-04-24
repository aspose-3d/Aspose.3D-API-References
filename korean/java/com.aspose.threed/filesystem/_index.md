---
title: FileSystem
second_title: Aspose.3D for Java API 레퍼런스
description: 파일 시스템 캡슐화.
type: docs
weight: 67
url: /ko/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

파일 시스템 캡슐화. Aspose.3D는 이를 사용하여 종속성을 읽고/쓰기합니다. **Example:** 다음 코드는 파일을 가져오고 지정된 디렉터리에서 종속 파일을 제공하는 방법을 보여줍니다

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | 파일 시스템을 해제하고 리소스를 해제합니다. |
| [createDummyFileSystem()](#createDummyFileSystem--) | 더미 파일 시스템을 생성합니다. 읽기/쓰기 작업은 더미 작업입니다. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | 로컬 디렉터리만 접근하는 새로운 [FileSystem](../../com.aspose.threed/filesystem)을 초기화합니다. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | 읽기/쓰기 작업을 메모리로 매핑하는 메모리 기반 파일 시스템을 생성합니다. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | 읽기/쓰기 작업을 메모리로 매핑하는 메모리 기반 파일 시스템을 생성합니다. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | 지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 접근을 제공하는 파일 시스템을 생성합니다. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | 지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 접근을 제공하는 파일 시스템을 생성합니다. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | 지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 액세스를 제공하는 파일 시스템. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | 종속성을 읽기 위한 스트림을 생성합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | 종속성을 쓰기 위한 스트림을 생성합니다. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


파일 시스템을 해제하고 리소스를 해제합니다.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


더미 파일 시스템을 생성합니다. 읽기/쓰기 작업은 더미 작업입니다.

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


로컬 디렉터리만 접근하는 새로운 [FileSystem](../../com.aspose.threed/filesystem)을 초기화합니다. 이 FileSystem 인스턴스의 모든 파일 읽기/쓰기는 지정된 디렉터리로 매핑됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 디렉터리 | java.lang.String | 물리 파일 시스템의 디렉터리를 가상 루트 디렉터리로 사용합니다. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


읽기/쓰기 작업을 메모리로 매핑하는 메모리 기반 파일 시스템을 생성합니다.

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


읽기/쓰기 작업을 메모리로 매핑하는 메모리 기반 파일 시스템을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | 가상 파일을 읽고/쓸 수 있게 합니다. |

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


지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 접근을 제공하는 파일 시스템을 생성합니다. 파일 시스템은 열기/저장 작업 후에 폐기됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | zip 파일에 접근하기 위한 스트림 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 접근을 제공하는 파일 시스템을 생성합니다. 파일 시스템은 열기/저장 작업 후에 폐기됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | zip 파일에 접근하기 위한 스트림 |
| baseDir | java.lang.String | zip 파일 내부의 기본 디렉터리. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 접근을 제공하는 파일 시스템입니다. 파일 시스템은 열기/저장 작업 후에 폐기됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | zip 파일의 파일 이름. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


종속성을 읽기 위한 스트림을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 읽기 위해 열 파일의 이름 |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | 저장 또는 로드 옵션 |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


종속성을 쓰기 위한 스트림을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 쓰기 위해 열 파일의 이름 |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | 저장 또는 로드 옵션 |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
