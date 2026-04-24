---
title: ZipArchiveFileSystem
second_title: Aspose.3D for Java API 레퍼런스
description: 지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 액세스를 제공하는 파일 시스템.
type: docs
weight: 221
url: /ko/java/com.aspose.threed/ziparchivefilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class ZipArchiveFileSystem extends FileSystem
```

지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 액세스를 제공하는 파일 시스템입니다. 파일 시스템은 열기/저장 작업 후에 해제됩니다. **Example:** 다음 코드는 파일을 가져오고 zip 압축 파일에 종속 파일을 제공하는 방법을 보여줍니다.

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new ZipArchiveFileSystem("textures.zip"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ZipArchiveFileSystem(Stream stream, String baseDir)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-) | 스트림을 통해 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)를 구성합니다. |
| [ZipArchiveFileSystem(Stream stream)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-) | 스트림을 통해 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)를 구성합니다. |
| [ZipArchiveFileSystem(String fileName)](#ZipArchiveFileSystem-java.lang.String-) | 파일 이름을 통해 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)를 구성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | ZipArchiveFileSystem을 해제하고 내부 리소스를 반환합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | 읽기를 위해 파일 열기 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | 쓰기를 위해 파일 열기, 이 클래스에서는 구현되지 않음. |
### ZipArchiveFileSystem(Stream stream, String baseDir) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-}
```
public ZipArchiveFileSystem(Stream stream, String baseDir)
```


스트림을 통해 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)를 구성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | com.aspose.csporter.helpers.Stream |  |
| baseDir | java.lang.String |  |

### ZipArchiveFileSystem(Stream stream) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-}
```
public ZipArchiveFileSystem(Stream stream)
```


스트림을 통해 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)를 구성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | com.aspose.csporter.helpers.Stream |  |

### ZipArchiveFileSystem(String fileName) {#ZipArchiveFileSystem-java.lang.String-}
```
public ZipArchiveFileSystem(String fileName)
```


파일 이름을 통해 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)를 구성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String |  |

### close() {#close--}
```
public void close()
```


ZipArchiveFileSystem을 해제하고 내부 리소스를 반환합니다.

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
public Stream readFile(String fileName, IOConfig options)
```


읽기를 위해 파일 열기

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
public Stream writeFile(String fileName, IOConfig options)
```


쓰기를 위해 파일 열기, 이 클래스에서는 구현되지 않음.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
