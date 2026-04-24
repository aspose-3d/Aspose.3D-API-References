---
title: PlySaveOptions
second_title: Aspose.3D for Java API 레퍼런스
description: 씬을 PLY 파일로 내보내기 위한 저장 옵션입니다.
type: docs
weight: 131
url: /ko/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

씬을 PLY 파일로 내보내기 위한 저장 옵션입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions)의 생성자 |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions)의 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | 내보낸 STL 파일의 축 시스템을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | Vertex 색상의 구성 요소 이름이며, 기본값은 (\"red\", \"green\", \"blue\")입니다. |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. |
| [getExportTextures()](#getExportTextures--) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [getFaceElement()](#getFaceElement--) | 얼굴 데이터의 요소 이름, 기본값은 "face"입니다. |
| [getFaceProperty()](#getFaceProperty--) | 얼굴 데이터의 속성 이름, 기본값은 "vertex\_index"입니다. |
| [getFileFormat()](#getFileFormat--) | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [getFileName()](#getFileName--) | 내보내기/가져오기 씬의 파일 이름. |
| [getFileSystem()](#getFileSystem--) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem에 대한 팩토리 클래스를 가져옵니다. |
| [getFlipCoordinate()](#getFlipCoordinate--) | 씬을 저장하는 동안 좌표를 뒤집습니다, 기본값은 true입니다. |
| [getLookupPaths()](#getLookupPaths--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [getNormalComponents()](#getNormalComponents--) | 노멀 데이터의 구성 요소 이름, 기본값은 ("nx", "ny", "nz")입니다. |
| [getPointCloud()](#getPointCloud--) | 씬을 포인트 클라우드로 내보냅니다, 기본값은 false입니다. |
| [getPositionComponents()](#getPositionComponents--) | 위치 데이터의 구성 요소 이름, 기본값은 ("x", "y", "z")입니다. |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | 텍스처 좌표 데이터의 구성 요소 이름, 기본값은 ("u", "v")입니다. |
| [getVertexElement()](#getVertexElement--) | 버텍스 데이터의 요소 이름, 기본값은 "vertex"입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | 내보낸 STL 파일의 축 시스템을 설정합니다. |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Vertex 색상의 구성 요소 이름이며, 기본값은 (\"red\", \"green\", \"blue\")입니다. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | 얼굴 데이터의 요소 이름, 기본값은 "face"입니다. |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | 얼굴 데이터의 속성 이름, 기본값은 "vertex\_index"입니다. |
| [setFileName(String value)](#setFileName-java.lang.String-) | 내보내기/가져오기 씬의 파일 이름. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem에 대한 팩토리 클래스를 설정합니다. |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | 씬을 저장하는 동안 좌표를 뒤집습니다, 기본값은 true입니다. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | 노멀 데이터의 구성 요소 이름, 기본값은 ("nx", "ny", "nz")입니다. |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | 씬을 포인트 클라우드로 내보냅니다, 기본값은 false입니다. |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | 위치 데이터의 구성 요소 이름, 기본값은 ("x", "y", "z")입니다. |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | 텍스처 좌표 데이터의 구성 요소 이름, 기본값은 ("u", "v")입니다. |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | 버텍스 데이터의 요소 이름, 기본값은 "vertex"입니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions)의 생성자

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions)의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


내보낸 STL 파일의 축 시스템을 가져옵니다.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported stl file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponents() {#getColorComponents--}
```
public Tuple_3<String,String,String> getColorComponents()
```


Vertex 색상의 구성 요소 이름이며, 기본값은 (\"red\", \"green\", \"blue\")입니다.

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - 버텍스 색상의 구성 요소 이름, 기본값은 ("red", "green", "blue")입니다.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.

**Returns:**
java.nio.charset.Charset - 텍스트 기반 파일에 대한 기본 인코딩. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다.

**Returns:**
boolean - 장면에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다.
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


얼굴 데이터의 요소 이름, 기본값은 "face"입니다.

**Returns:**
java.lang.String - 얼굴 데이터의 요소 이름, 기본값은 "face"입니다.
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


얼굴 데이터의 속성 이름, 기본값은 "vertex\_index"입니다.

**Returns:**
java.lang.String - 얼굴 데이터의 속성 이름, 기본값은 "vertex\_index"입니다.
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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


씬을 저장하는 동안 좌표를 뒤집습니다, 기본값은 true입니다.

**Returns:**
boolean - 씬을 저장하는 동안 좌표를 뒤집습니다, 기본값은 true입니다.
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
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


노멀 데이터의 구성 요소 이름, 기본값은 ("nx", "ny", "nz")입니다.

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - 노멀 데이터의 구성 요소 이름, 기본값은 ("nx", "ny", "nz")입니다.
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


씬을 포인트 클라우드로 내보냅니다, 기본값은 false입니다.

**Returns:**
boolean - 씬을 포인트 클라우드로 내보냅니다, 기본값은 false입니다.
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


위치 데이터의 구성 요소 이름, 기본값은 ("x", "y", "z")입니다.

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - 위치 데이터의 구성 요소 이름, 기본값은 ("x", "y", "z")입니다.
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


텍스처 좌표 데이터의 구성 요소 이름, 기본값은 ("u", "v")입니다.

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - 텍스처 좌표 데이터의 구성 요소 이름, 기본값은 ("u", "v")입니다.
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


버텍스 데이터의 요소 이름, 기본값은 "vertex"입니다.

**Returns:**
java.lang.String - 버텍스 데이터의 요소 이름, 기본값은 "vertex"입니다.
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




### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


내보낸 STL 파일의 축 시스템을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | 새 값 **Remarks:** FlipCoordinateSystem을 사용하려면 이 기능을 활성화해야 합니다. |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


Vertex 색상의 구성 요소 이름이며, 기본값은 (\"red\", \"green\", \"blue\")입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | 새 값 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset | 새 값 |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


얼굴 데이터의 요소 이름, 기본값은 "face"입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


얼굴 데이터의 속성 이름, 기본값은 "vertex\_index"입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


씬을 저장하는 동안 좌표를 뒤집습니다, 기본값은 true입니다.

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

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


노멀 데이터의 구성 요소 이름, 기본값은 ("nx", "ny", "nz")입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | 새 값 |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


씬을 포인트 클라우드로 내보냅니다, 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


위치 데이터의 구성 요소 이름, 기본값은 ("x", "y", "z")입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | 새 값 |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


텍스처 좌표 데이터의 구성 요소 이름, 기본값은 ("u", "v")입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | 새 값 |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


버텍스 데이터의 요소 이름, 기본값은 "vertex"입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

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

