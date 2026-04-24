---
title: Discreet3dsSaveOptions
second_title: Aspose.3D for Java API 레퍼런스
description: 3DS 파일 저장 옵션.
type: docs
weight: 44
url: /ko/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

3DS 파일 저장 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)의 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | 중복된 이름에 대한 새 이름을 생성할 때 사용되는 카운터이며, 기본값은 2입니다. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | 중복 카운터의 형식이며, 기본값은 빈 문자열입니다. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | 객체 이름과 중복 카운터 사이의 구분자이며, 기본값은 "\\_"입니다. |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. |
| [getExportCamera()](#getExportCamera--) | 씬의 모든 카메라를 내보낼지 여부를 가져옵니다. |
| [getExportLight()](#getExportLight--) | 씬의 모든 조명을 내보낼지 여부를 가져옵니다. |
| [getExportTextures()](#getExportTextures--) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [getFileFormat()](#getFileFormat--) | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [getFileName()](#getFileName--) | 내보내기/가져오기 씬의 파일 이름. |
| [getFileSystem()](#getFileSystem--) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem에 대한 팩토리 클래스를 가져옵니다. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | 가져오기/내보내기 중 제어점/법선의 좌표계 반전을 가져옵니다. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | 3ds 파일은 동일한 속성에 대해 원본 색상과 감마 보정 색상을 모두 포함할 수 있습니다. 이를 true로 설정하면 가능한 경우 감마 보정 색상을 사용하고, 그렇지 않으면 Aspose.3D가 원본 색상을 사용하려고 시도합니다. |
| [getHighPreciseColor()](#getHighPreciseColor--) | 이 값을 true로 설정하면 생성된 3ds 파일이 고정밀 색상을 사용하며, 이는 빨강/녹색/파랑 각 채널이 32비트 부동소수점으로 표현된다는 의미입니다. |
| [getLookupPaths()](#getLookupPaths--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [getMasterScale()](#getMasterScale--) | 내보내기에 사용되는 마스터 스케일을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | 중복된 이름에 대한 새 이름을 생성할 때 사용되는 카운터이며, 기본값은 2입니다. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | 중복 카운터의 형식이며, 기본값은 빈 문자열입니다. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | 객체 이름과 중복 카운터 사이의 구분자이며, 기본값은 "\\_"입니다. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | 장면의 모든 카메라를 내보낼지 여부를 설정합니다. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | 장면의 모든 조명을 내보낼지 여부를 설정합니다. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [setFileName(String value)](#setFileName-java.lang.String-) | 내보내기/가져오기 씬의 파일 이름. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem에 대한 팩토리 클래스를 설정합니다. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | 가져오기/내보내기 중 제어점/법선의 좌표계 반전을 설정합니다. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | 3ds 파일은 동일한 속성에 대해 원본 색상과 감마 보정 색상을 모두 포함할 수 있습니다. 이를 true로 설정하면 가능한 경우 감마 보정 색상을 사용하고, 그렇지 않으면 Aspose.3D가 원본 색상을 사용하려고 시도합니다. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | 이 값을 true로 설정하면 생성된 3ds 파일이 고정밀 색상을 사용하며, 이는 빨강/녹색/파랑 각 채널이 32비트 부동소수점으로 표현된다는 의미입니다. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [setMasterScale(double value)](#setMasterScale-double-) | 내보내기에 사용되는 마스터 스케일을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


[Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)의 생성자

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
### getDuplicatedNameCounterBase() {#getDuplicatedNameCounterBase--}
```
public int getDuplicatedNameCounterBase()
```


중복된 이름에 대한 새 이름을 생성할 때 사용되는 카운터이며, 기본값은 2입니다.

**Returns:**
int - 중복된 이름에 대한 새 이름을 생성할 때 사용되는 카운터이며, 기본값은 2입니다.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


중복 카운터의 형식이며, 기본값은 빈 문자열입니다.

**Returns:**
java.lang.String - 중복 카운터의 형식이며, 기본값은 빈 문자열입니다.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


객체 이름과 중복 카운터 사이의 구분자이며, 기본값은 "\\_"입니다. 장면에 동일한 이름을 사용하는 객체가 포함된 경우, Aspose.3D 3DS 내보내기는 해당 객체에 다른 이름을 생성합니다. 예를 들어 "Box"라는 이름을 가진 두 노드가 있다면, 첫 번째 노드의 이름은 "Box"이고 두 번째 노드는 기본 구성으로 "Box\\_2"라는 새 이름을 갖게 됩니다.

**Returns:**
java.lang.String - 객체 이름과 중복 카운터 사이의 구분자이며, 기본값은 "\\_"입니다. 장면에 동일한 이름을 사용하는 객체가 포함된 경우, Aspose.3D 3DS 내보내기는 해당 객체에 다른 이름을 생성합니다. 예를 들어 "Box"라는 이름을 가진 두 노드가 있다면, 첫 번째 노드의 이름은 "Box"이고 두 번째 노드는 기본 구성으로 "Box\\_2"라는 새 이름을 갖게 됩니다.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.

**Returns:**
java.nio.charset.Charset - 텍스트 기반 파일에 대한 기본 인코딩. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


씬의 모든 카메라를 내보낼지 여부를 가져옵니다.

**Returns:**
boolean - 장면의 모든 카메라를 내보낼지 여부.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


씬의 모든 조명을 내보낼지 여부를 가져옵니다.

**Returns:**
boolean - 장면의 모든 조명을 내보낼지 여부.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다.

**Returns:**
boolean - 장면에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


내보내기/가져오기 씬의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다.

**Returns:**
java.lang.String - 내보내기/가져오기 씬의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

그리고 자체 구현을 사용할 수도 있습니다.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


FileSystem에 대한 팩토리 클래스를 가져옵니다. 기본 팩토리는 com.aspose.threed.LocalFileSystem을 생성하는데, 이는 서버 환경에 적합하지 않습니다.

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


가져오기/내보내기 중 제어점/법선의 좌표계 반전을 가져옵니다.

**Returns:**
boolean - 가져오기/내보내기 중 제어점/법선의 좌표계를 뒤집습니다.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


3ds 파일은 동일한 속성에 대해 원본 색상과 감마 보정 색상을 모두 포함할 수 있습니다. 이를 true로 설정하면 가능한 경우 감마 보정 색상을 사용하고, 그렇지 않으면 Aspose.3D가 원본 색상을 사용하려고 시도합니다.

**Returns:**
boolean - 3ds 파일은 동일한 속성에 대해 원본 색상과 감마 보정 색상을 모두 포함할 수 있으며, 이를 true로 설정하면 가능한 경우 감마 보정 색상을 사용하고, 그렇지 않으면 Aspose.3D가 원본 색상을 사용하려고 시도합니다.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


이 값을 true로 설정하면 생성된 3ds 파일은 고정밀 색상을 사용하며, 빨강/초록/파랑 각 채널이 32비트 부동소수점으로 표현됩니다. 그렇지 않으면 생성된 파일은 24비트 색상을 사용하고 각 채널은 8비트 바이트로 저장됩니다. 기본값은 false이며, 모든 애플리케이션이 고정밀 색상을 지원하는 것은 아니기 때문입니다.

**Returns:**
boolean - 이 값을 true로 설정하면 생성된 3ds 파일은 고정밀 색상을 사용하며, 빨강/초록/파랑 각 채널이 32비트 부동소수점으로 표현됩니다. 그렇지 않으면 생성된 파일은 24비트 색상을 사용하고 각 채널은 8비트 바이트로 저장됩니다. 기본값은 false이며, 모든 애플리케이션이 고정밀 색상을 지원하는 것은 아니기 때문입니다.
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다.

**Returns:**
java.util.ArrayList<java.lang.String> - OBJ와 같은 일부 파일은 외부 파일에 의존하므로, 조회 경로를 통해 Aspose.3D가 외부 파일을 찾을 수 있게 합니다. **Example:** 다음 코드는 텍스처를 수동으로 지정하는 방법을 보여주며, 가져오기자가 찾을 수 있도록 합니다.

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


내보내기에 사용되는 마스터 스케일을 가져옵니다.

**Returns:**
double - 내보내기에 사용되는 마스터 스케일.
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




### setDuplicatedNameCounterBase(int value) {#setDuplicatedNameCounterBase-int-}
```
public void setDuplicatedNameCounterBase(int value)
```


중복된 이름에 대한 새 이름을 생성할 때 사용되는 카운터이며, 기본값은 2입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


중복 카운터의 형식이며, 기본값은 빈 문자열입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


객체 이름과 중복 카운터 사이의 구분자이며, 기본값은 "\\_"입니다. 장면에 동일한 이름을 사용하는 객체가 포함된 경우, Aspose.3D 3DS 내보내기는 해당 객체에 다른 이름을 생성합니다. 예를 들어 "Box"라는 이름을 가진 두 노드가 있다면, 첫 번째 노드의 이름은 "Box"이고 두 번째 노드는 기본 구성으로 "Box\\_2"라는 새 이름을 갖게 됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset | 새 값 |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


장면의 모든 카메라를 내보낼지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


장면의 모든 조명을 내보낼지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


내보내기/가져오기 씬의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | 새 값 **Example:** 기본 FileSystem은 LocalFileSystem이며, 서버 측과 같은 환경에서는 안전하지 않습니다. 그러나 다른 구현을 지정하여 파일 시스템 접근을 재정의할 수 있습니다. Aspose.3D는 다음과 같은 다양한 FileSystem 구현을 제공합니다: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

그리고 자체 구현을 사용할 수도 있습니다.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


FileSystem에 대한 팩토리 클래스를 설정합니다. 기본 팩토리는 com.aspose.threed.LocalFileSystem을 생성하는데, 이는 서버 환경에 적합하지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | 새 값 **Example:** SaveOptions/LoadOptions의 기본 FileSystem은 디렉터리 기반 파일 시스템이며, IOConfig.FileSystemFactory를 통해 지정하여 기본 구현을 재정의할 수 있습니다. |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


가져오기/내보내기 중 제어점/법선의 좌표계 반전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


3ds 파일은 동일한 속성에 대해 원본 색상과 감마 보정 색상을 모두 포함할 수 있습니다. 이를 true로 설정하면 가능한 경우 감마 보정 색상을 사용하고, 그렇지 않으면 Aspose.3D가 원본 색상을 사용하려고 시도합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


이 값을 true로 설정하면 생성된 3ds 파일은 고정밀 색상을 사용하며, 빨강/초록/파랑 각 채널이 32비트 부동소수점으로 표현됩니다. 그렇지 않으면 생성된 파일은 24비트 색상을 사용하고 각 채널은 8비트 바이트로 저장됩니다. 기본값은 false이며, 모든 애플리케이션이 고정밀 색상을 지원하는 것은 아니기 때문입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.ArrayList<java.lang.String> | 새 값 **Example:** 다음 코드는 텍스처를 수동으로 지정하는 방법을 보여주며, 가져오기자가 찾을 수 있도록 합니다. |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


내보내기에 사용되는 마스터 스케일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

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

