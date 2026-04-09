---
title: GltfSaveOptions
second_title: Aspose.3D for Java API 레퍼런스
description: glTF 형식에 대한 저장 옵션.
type: docs
weight: 74
url: /ko/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

glTF 형식에 대한 저장 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | 생성자 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | 생성자 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | 메시에 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 적용합니다. |
| [getBufferFile()](#getBufferFile--) | 바이너리 데이터를 저장하는 데 사용되는 외부 버퍼 파일의 파일 이름. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | draco 압축을 활성화할지 여부를 가져옵니다. |
| [getEmbedAssets()](#getEmbedAssets--) | 외부 자산을 모두 base64로 인코딩하여 ASCII 모드의 단일 파일에 포함합니다. 기본값은 false입니다. |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. |
| [getExportTextures()](#getExportTextures--) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | 외부 draco 인코더를 사용하여 draco 압축 속도를 가속화합니다. |
| [getFallbackNormal()](#getFallbackNormal--) | GLTF2 내보내기가 잘못된 노멀을 감지했을 때, 검증을 우회하기 위해 원래 값 대신 이것이 사용됩니다. |
| [getFileFormat()](#getFileFormat--) | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [getFileName()](#getFileName--) | 내보내기/가져오기 씬의 파일 이름. |
| [getFileSystem()](#getFileSystem--) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem에 대한 팩토리 클래스를 가져옵니다. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | 텍스처 좌표 v(t) 구성 요소를 뒤집습니다. 기본값은 true입니다. |
| [getImageFormat()](#getImageFormat--) | 표준 glTF는 텍스처 형식으로 PNG/JPG만 지원하므로, 이 옵션은 내보내기 중 Aspose.3D가 비표준 이미지를 지원되는 형식으로 변환하는 방식을 안내합니다. |
| [getLookupPaths()](#getLookupPaths--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [getMaterialConverter()](#getMaterialConverter--) | 지오메트리의 재질을 PBR 재질로 변환하는 사용자 지정 변환기. 이 값이 지정되지 않으면 glTF 2.0 내보내기 도구가 표준 재질을 자동으로 PBR 재질로 변환합니다. |
| [getPrettyPrint()](#getPrettyPrint--) | GLTF 파일의 JSON 내용은 사람이 읽기 쉽도록 들여쓰기됩니다. 기본값은 false입니다. |
| [getSaveExtras()](#getSaveExtras--) | 생성된 glTF 파일의 'extra' 필드에 씬 객체의 동적 속성을 저장합니다. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | KHR 공통 재질 확장을 사용하여 재질을 직렬화합니다. 기본값은 false입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | 메시에 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 적용합니다. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | 바이너리 데이터를 저장하는 데 사용되는 외부 버퍼 파일의 파일 이름. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | draco 압축을 활성화할지 여부를 설정합니다. |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | 외부 자산을 모두 base64로 인코딩하여 ASCII 모드의 단일 파일에 포함합니다. 기본값은 false입니다. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | 외부 draco 인코더를 사용하여 draco 압축 속도를 가속화합니다. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | GLTF2 내보내기가 잘못된 노멀을 감지했을 때, 검증을 우회하기 위해 원래 값 대신 이것이 사용됩니다. |
| [setFileName(String value)](#setFileName-java.lang.String-) | 내보내기/가져오기 씬의 파일 이름. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem에 대한 팩토리 클래스를 설정합니다. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | 텍스처 좌표 v(t) 구성 요소를 뒤집습니다. 기본값은 true입니다. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | 표준 glTF는 텍스처 형식으로 PNG/JPG만 지원하므로, 이 옵션은 내보내기 중 Aspose.3D가 비표준 이미지를 지원되는 형식으로 변환하는 방식을 안내합니다. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | 지오메트리의 재질을 PBR 재질로 변환하는 사용자 지정 변환기. 이 값이 지정되지 않으면 glTF 2.0 내보내기 도구가 표준 재질을 자동으로 PBR 재질로 변환합니다. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | GLTF 파일의 JSON 내용은 사람이 읽기 쉽도록 들여쓰기됩니다. 기본값은 false입니다. |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | 생성된 glTF 파일의 'extra' 필드에 씬 객체의 동적 속성을 저장합니다. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | KHR 공통 재질 확장을 사용하여 재질을 직렬화합니다. 기본값은 false입니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


생성자 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


생성자 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


메시에 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 적용합니다. 기본값은 false입니다.

**Returns:**
boolean - [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor)을(를) 메시에 적용합니다. 기본값은 false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


바이너리 데이터를 저장하는 외부 버퍼 파일의 파일 이름입니다. 이 파일을 지정하지 않으면 Aspose.3D가 이름을 자동으로 생성합니다. glTF를 바이너리 모드로 내보낼 때는 무시됩니다.

**Returns:**
java.lang.String - 바이너리 데이터를 저장하는 외부 버퍼 파일의 파일 이름입니다. 이 파일을 지정하지 않으면 Aspose.3D가 이름을 자동으로 생성합니다. glTF를 바이너리 모드로 내보낼 때는 무시됩니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDracoCompression() {#getDracoCompression--}
```
public boolean getDracoCompression()
```


draco 압축을 활성화할지 여부를 가져옵니다.

**Returns:**
boolean - draco 압축을 활성화할지 여부
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


외부 자산을 모두 base64로 인코딩하여 ASCII 모드의 단일 파일에 포함합니다. 기본값은 false입니다.

**Returns:**
boolean - 모든 외부 자산을 base64로 인코딩하여 ASCII 모드의 단일 파일에 포함합니다. 기본값은 false입니다.
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
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


외부 draco 인코더를 사용하여 draco 압축 속도를 가속화합니다.

**Returns:**
java.lang.String - 외부 draco 인코더를 사용하여 draco 압축 속도를 가속합니다. **Remarks:** Aspose.3D는 메쉬를 draco 형식으로 인코딩하기 위해 새로운 하위 프로세스를 생성하므로, 사용 시 위험을 감수하십시오.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


GLTF2 내보내기 도구가 잘못된 노멀을 감지하면, 검증을 우회하기 위해 원래 값 대신 이 값이 사용됩니다. 기본값은 (0, 1, 0)입니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
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
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


텍스처 좌표 v(t) 구성 요소를 뒤집습니다. 기본값은 true입니다.

**Returns:**
boolean - 텍스처 좌표 v(t) 구성 요소를 뒤집습니다. 기본값은 true입니다.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


표준 glTF는 텍스처 형식으로 PNG/JPG만 지원하므로, 이 옵션은 내보내기 중 Aspose.3D가 비표준 이미지를 지원되는 형식으로 변환하는 방식을 안내합니다. 기본값은 [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)입니다.

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
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
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


지오메트리의 재질을 PBR 재질로 변환하는 사용자 지정 변환기. 이 값이 지정되지 않으면 glTF 2.0 내보내기 도구가 표준 재질을 자동으로 PBR 재질로 변환합니다. 기본값은 null이며, 이 속성은 씬을 glTF 2.0 파일로 내보낼 때 사용됩니다.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


GLTF 파일의 JSON 내용은 사람이 읽기 쉽도록 들여쓰기됩니다. 기본값은 false입니다.

**Returns:**
boolean - GLTF 파일의 JSON 내용은 사람이 읽기 쉽도록 들여쓰기됩니다. 기본값은 false입니다.
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


생성된 glTF 파일의 'extra' 필드에 씬 객체의 동적 속성을 저장합니다. 이는 애플리케이션별 데이터를 제공하는 데 유용합니다. 기본값은 false입니다.

**Returns:**
boolean - 생성된 glTF 파일의 'extra' 필드에 씬 객체의 동적 속성을 저장합니다. 이는 애플리케이션별 데이터를 제공하는 데 유용합니다. 기본값은 false입니다.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


KHR 공통 재질 확장을 사용하여 재질을 직렬화합니다. 기본값은 false이며, 이를 false로 설정하면 [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)인 경우 Aspose.3D가 정점/프래그먼트 셰이더 세트를 내보냅니다.

**Returns:**
boolean - KHR 공통 재질 확장을 사용하여 재질을 직렬화합니다. 기본값은 false이며, 이를 false로 설정하면 [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)인 경우 Aspose.3D가 정점/프래그먼트 셰이더 세트를 내보냅니다. **Remarks:** 이 속성은 glTF 1.0에서만 작동합니다.
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




### setApplyUnitScale(boolean value) {#setApplyUnitScale-boolean-}
```
public void setApplyUnitScale(boolean value)
```


메시에 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 적용합니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


바이너리 데이터를 저장하는 외부 버퍼 파일의 파일 이름입니다. 이 파일을 지정하지 않으면 Aspose.3D가 이름을 자동으로 생성합니다. glTF를 바이너리 모드로 내보낼 때는 무시됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


draco 압축을 활성화할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


외부 자산을 모두 base64로 인코딩하여 ASCII 모드의 단일 파일에 포함합니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

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

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


외부 draco 인코더를 사용하여 draco 압축 속도를 가속화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 **Remarks:** Aspose.3D는 메쉬를 draco 형식으로 인코딩하기 위해 새로운 하위 프로세스를 생성하므로, 사용 시 위험을 감수하십시오. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


GLTF2 내보내기 도구가 잘못된 노멀을 감지하면, 검증을 우회하기 위해 원래 값 대신 이 값이 사용됩니다. 기본값은 (0, 1, 0)입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

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

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


텍스처 좌표 v(t) 구성 요소를 뒤집습니다. 기본값은 true입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


표준 glTF는 텍스처 형식으로 PNG/JPG만 지원하므로, 이 옵션은 내보내기 중 Aspose.3D가 비표준 이미지를 지원되는 형식으로 변환하는 방식을 안내합니다. 기본값은 [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | 새 값 |

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

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


지오메트리의 재질을 PBR 재질로 변환하는 사용자 지정 변환기. 이 값이 지정되지 않으면 glTF 2.0 내보내기 도구가 표준 재질을 자동으로 PBR 재질로 변환합니다. 기본값은 null이며, 이 속성은 씬을 glTF 2.0 파일로 내보낼 때 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | 새 값 |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


GLTF 파일의 JSON 내용은 사람이 읽기 쉽도록 들여쓰기됩니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


생성된 glTF 파일의 'extra' 필드에 씬 객체의 동적 속성을 저장합니다. 이는 애플리케이션별 데이터를 제공하는 데 유용합니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


KHR 공통 재질 확장을 사용하여 재질을 직렬화합니다. 기본값은 false이며, 이를 false로 설정하면 [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)인 경우 Aspose.3D가 정점/프래그먼트 셰이더 세트를 내보냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 **Remarks:** 이 속성은 glTF 1.0에서만 작동합니다. |

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

