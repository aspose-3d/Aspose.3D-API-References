---
title: RvmLoadOptions
second_title: Aspose.3D for Java API 레퍼런스
description: AVEVA Plant Design Management Systems RVM 파일에 대한 로드 옵션.
type: docs
weight: 157
url: /ko/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

AVEVA Plant Design Management System의 RVM 파일에 대한 로드 옵션. **Example:** 다음 코드는 RvmLoadOptions를 사용하여 RVM 파일에서 가져온 기본 기하학의 테셀레이션 매개변수를 사용자 정의하는 방법을 보여줍니다.

```
RvmLoadOptions opt = new RvmLoadOptions();
             opt.setRectangularTorusSegments(30);
             opt.setCylinderRadialSegments(20);
             opt.setDishLatitudeSegments(20);
             opt.setDishLongitudeSegments(20);
             opt.setCenterScene(true);
             var scene = Scene.fromFile("input.rvm", opt);
             scene.save("output.obj");
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 인스턴스를 생성합니다 |
| [RvmLoadOptions()](#RvmLoadOptions--) | [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 인스턴스를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | 외부 속성 파일에 정의된 속성들의 접두사를 가져옵니다. 접두사는 이름 충돌을 방지하기 위해 사용되며, 기본값은 "rvm:"입니다. |
| [getCenterScene()](#getCenterScene--) | 로드된 후 장면을 중앙에 배치합니다. |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | 실린더의 방사형 세그먼트 수를 가져옵니다. 기본값은 16입니다. |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | 디시의 위도 세그먼트 수를 가져옵니다. 기본값은 8입니다. |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | 디시의 경도 세그먼트 수를 가져옵니다. 기본값은 12입니다. |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. |
| [getFileFormat()](#getFileFormat--) | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [getFileName()](#getFileName--) | 내보내기/가져오기 씬의 파일 이름. |
| [getFileSystem()](#getFileSystem--) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem에 대한 팩토리 클래스를 가져옵니다. |
| [getGenerateMaterials()](#getGenerateMaterials--) | RVM 파일에 색상 테이블이 내보내지지 않은 경우, 장면의 각 객체에 대해 무작위 색상의 재질을 생성합니다. |
| [getLookupAttributes()](#getLookupAttributes--) | 외부 속성 목록 파일(.att/.attrib/.txt)에서 속성을 로드할지 여부를 가져옵니다. 기본값은 true입니다. |
| [getLookupPaths()](#getLookupPaths--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | 직사각형 토러스의 방사형 세그먼트 수를 가져옵니다. 기본값은 20입니다. |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | 토러스의 튜블 세그먼트 수를 가져옵니다. 기본값은 20입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | 외부 속성 파일에 정의된 속성들의 접두사를 설정합니다. 접두사는 이름 충돌을 방지하기 위해 사용되며, 기본값은 "rvm:"입니다. |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | 로드된 후 장면을 중앙에 배치합니다. |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | 실린더의 방사형 세그먼트 수를 설정합니다. 기본값은 16입니다. |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | 디시의 위도 세그먼트 수를 설정합니다. 기본값은 8입니다. |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | 디시의 경도 세그먼트 수를 설정합니다. 기본값은 12입니다. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. |
| [setFileName(String value)](#setFileName-java.lang.String-) | 내보내기/가져오기 씬의 파일 이름. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem에 대한 팩토리 클래스를 설정합니다. |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | RVM 파일에 색상 테이블이 내보내지지 않은 경우, 장면의 각 객체에 대해 무작위 색상의 재질을 생성합니다. |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | 외부 속성 목록 파일(.att/.attrib/.txt)에서 속성을 로드할지 여부를 설정합니다. 기본값은 true입니다. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | 직사각형 토러스의 방사형 세그먼트 수를 설정합니다. 기본값은 20입니다. |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | 토러스의 튜블 세그먼트 수를 설정합니다. 기본값은 20입니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


[RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 인스턴스를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


[RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 인스턴스를 생성합니다

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


외부 속성 파일에 정의된 속성들의 접두사를 가져옵니다. 접두사는 이름 충돌을 방지하기 위해 사용되며, 기본값은 "rvm:"입니다.

**Returns:**
java.lang.String - 외부 속성 파일에서 정의된 속성들의 접두사이며, 접두사는 이름 충돌을 방지하기 위해 사용됩니다. 기본값은 "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


로드된 후 장면을 중앙에 배치합니다.

**Returns:**
boolean - 로드된 후 장면을 중앙에 배치합니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCylinderRadialSegments() {#getCylinderRadialSegments--}
```
public int getCylinderRadialSegments()
```


실린더의 방사형 세그먼트 수를 가져옵니다. 기본값은 16입니다.

**Returns:**
int - 실린더의 방사형 세그먼트 수, 기본값은 16입니다.
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


디시의 위도 세그먼트 수를 가져옵니다. 기본값은 8입니다.

**Returns:**
int - 접시의 위도 세그먼트 수, 기본값은 8입니다.
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


디시의 경도 세그먼트 수를 가져옵니다. 기본값은 12입니다.

**Returns:**
int - 접시의 경도 세그먼트 수, 기본값은 12입니다.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.

**Returns:**
java.nio.charset.Charset - 텍스트 기반 파일에 대한 기본 인코딩. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


색상 테이블이 RVM 파일에 내보내지지 않은 경우 장면의 각 객체에 대해 무작위 색상의 재질을 생성합니다. 기본값은 true입니다.

**Returns:**
boolean - 색상 테이블이 RVM 파일에 내보내지지 않은 경우 장면의 각 객체에 대해 무작위 색상의 재질을 생성합니다. 기본값은 true입니다.
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


외부 속성 목록 파일(.att/.attrib/.txt)에서 속성을 로드할지 여부를 가져옵니다. 기본값은 true입니다.

**Returns:**
boolean - 외부 속성 목록 파일(.att/.attrib/.txt)에서 속성을 로드할지 여부, 기본값은 true입니다.
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


직사각형 토러스의 방사형 세그먼트 수를 가져옵니다. 기본값은 20입니다.

**Returns:**
int - 직사각형 토러스의 방사형 세그먼트 수, 기본값은 20입니다.
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


토러스의 튜블 세그먼트 수를 가져옵니다. 기본값은 20입니다.

**Returns:**
int - 토러스의 튜브 세그먼트 수, 기본값은 20입니다.
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




### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


외부 속성 파일에 정의된 속성들의 접두사를 설정합니다. 접두사는 이름 충돌을 방지하기 위해 사용되며, 기본값은 "rvm:"입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


로드된 후 장면을 중앙에 배치합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


실린더의 방사형 세그먼트 수를 설정합니다. 기본값은 16입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


디시의 위도 세그먼트 수를 설정합니다. 기본값은 8입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


디시의 경도 세그먼트 수를 설정합니다. 기본값은 12입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset | 새 값 |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


색상 테이블이 RVM 파일에 내보내지지 않은 경우 장면의 각 객체에 대해 무작위 색상의 재질을 생성합니다. 기본값은 true입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


외부 속성 목록 파일(.att/.attrib/.txt)에서 속성을 로드할지 여부를 설정합니다. 기본값은 true입니다.

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


직사각형 토러스의 방사형 세그먼트 수를 설정합니다. 기본값은 20입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


토러스의 튜블 세그먼트 수를 설정합니다. 기본값은 20입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

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

