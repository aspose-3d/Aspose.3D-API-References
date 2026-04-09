---
title: FbxSaveOptions
second_title: Aspose.3D for Java API 레퍼런스
description: Fbx 파일에 대한 저장 옵션.
type: docs
weight: 63
url: /ko/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Fbx 파일에 대한 저장 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)를 초기화합니다. |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | 최신 지원 버전을 사용하여 [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | 텍스처를 최종 출력 파일에 포함시킬지 여부를 가져옵니다. |
| [getEnableCompression()](#getEnableCompression--) | FBX 파일에서 큰 바이너리 데이터를 압축합니다(예: |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | 레거시 재질 속성을 내보낼지 여부를 가져옵니다(호환성을 위해 사용). |
| [getExportTextures()](#getExportTextures--) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [getFileFormat()](#getFileFormat--) | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [getFileName()](#getFileName--) | 내보내기/가져오기 씬의 파일 이름. |
| [getFileSystem()](#getFileSystem--) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem에 대한 팩토리 클래스를 가져옵니다. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | 마지막 데이터의 참조 카운트를 증가시켜 반복되는 곡선 데이터를 재사용할지 여부를 가져옵니다. |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | 첨부된 노드에 재질이 포함된 경우, 기하학에 대해 항상 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 생성할지 여부를 가져옵니다. |
| [getLookupPaths()](#getLookupPaths--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | 같은 매개변수를 가진 프리미티브에 대해 메쉬를 재사용하면, 대량의 프리미티브 형태로 구성된 씬의 FBX 출력 크기를 크게 줄일 수 있습니다(CAD 파일에서 가져온 경우와 같이). |
| [getVideoForTexture()](#getVideoForTexture--) | FBX로 내보낼 때 [Texture](../../com.aspose.threed/texture)에 대한 Video 인스턴스를 생성할지 여부를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | 텍스처를 최종 출력 파일에 포함시킬지 여부를 설정합니다. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | FBX 파일에서 큰 바이너리 데이터를 압축합니다(예: |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 기반 파일에 대한 기본 인코딩을 설정합니다. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | 레거시 재질 속성을 내보낼지 여부를 설정합니다(호환성을 위해 사용). |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [setFileName(String value)](#setFileName-java.lang.String-) | 내보내기/가져오기 씬의 파일 이름. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem에 대한 팩토리 클래스를 설정합니다. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | 마지막 데이터의 참조 카운트를 증가시켜 반복되는 곡선 데이터를 재사용할지 여부를 설정합니다. |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | 첨부된 노드에 재질이 포함된 경우, 기하학에 대해 항상 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 생성할지 여부를 설정합니다. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있도록 허용합니다. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | 같은 매개변수를 가진 프리미티브에 대해 메쉬를 재사용하면, 대량의 프리미티브 형태로 구성된 씬의 FBX 출력 크기를 크게 줄일 수 있습니다(CAD 파일에서 가져온 경우와 같이). |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | FBX로 내보낼 때 [Texture](../../com.aspose.threed/texture)에 대한 Video 인스턴스를 생성할지 여부를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


[FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat)의 인스턴스로, 유효한 FBX 형식이어야 합니다. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


최신 지원 버전을 사용하여 [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | 바이너리 또는 ASCII |

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
### getEmbedTextures() {#getEmbedTextures--}
```
public boolean getEmbedTextures()
```


텍스처를 최종 출력 파일에 포함시킬지 여부를 가져옵니다. FBX Exporter는 [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem)에서 텍스처의 원시 데이터를 찾은 후 파일을 최종 FBX 파일에 포함시킵니다. 기본값은 false입니다.

**Returns:**
boolean - 텍스처를 최종 출력 파일에 포함시킬지 여부. FBX Exporter는 [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem)에서 텍스처의 원시 데이터를 찾은 후 파일을 최종 FBX 파일에 포함시킵니다. 기본값은 false입니다.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


FBX 파일에서 큰 바이너리 데이터를 압축합니다(예: 애니메이션 데이터, 제어 포인트, 정점 요소 데이터, 인덱스), 기본값은 true입니다.

**Returns:**
boolean - FBX 파일에서 큰 바이너리 데이터를 압축합니다(예: 애니메이션 데이터, 제어 포인트, 정점 요소 데이터, 인덱스), 기본값은 true입니다.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


텍스트 기반 파일에 대한 기본 인코딩을 가져옵니다. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.

**Returns:**
java.nio.charset.Charset - 텍스트 기반 파일에 대한 기본 인코딩. 기본값은 null이며, 이는 가져오기/내보내기 프로그램이 사용할 인코딩을 결정함을 의미합니다.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


레거시 재질 속성을 내보낼지 여부를 가져옵니다(호환성을 위해 사용). 이 옵션은 기본적으로 켜져 있습니다.

**Returns:**
boolean - 레거시 재질 속성을 내보낼지 여부(호환성을 위해 사용). 이 옵션은 기본적으로 켜져 있습니다.
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
### getFoldRepeatedCurveData() {#getFoldRepeatedCurveData--}
```
public Boolean getFoldRepeatedCurveData()
```


마지막 데이터의 참조 카운트를 증가시켜 반복되는 곡선 데이터를 재사용할지 여부를 가져옵니다.

**Returns:**
java.lang.Boolean - 마지막 데이터의 참조 카운트를 증가시켜 반복되는 곡선 데이터를 재사용할지 여부
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


첨부된 노드에 재질이 포함된 경우, 기하학에 대해 항상 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 생성할지 여부를 가져옵니다. 이 옵션은 기본적으로 꺼져 있습니다.

**Returns:**
boolean - 첨부된 노드에 재질이 포함된 경우, 기하학에 대해 항상 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 생성할지 여부. 이 옵션은 기본적으로 꺼져 있습니다.
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
### getReusePrimitiveMesh() {#getReusePrimitiveMesh--}
```
public boolean getReusePrimitiveMesh()
```


같은 매개변수를 가진 프리미티브에 대해 메쉬를 재사용하면, 대량의 프리미티브 형태로 구성된 씬의 FBX 출력 크기를 크게 줄일 수 있습니다(CAD 파일에서 가져온 경우와 같이). 기본값은 false입니다.

**Returns:**
boolean - 동일한 매개변수를 가진 프리미티브에 대해 메시를 재사용하면, 대량의 프리미티브 형태(예: CAD 파일에서 가져온)로 구성된 씬의 FBX 출력 크기를 크게 줄일 수 있습니다. 기본값은 false입니다.
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


FBX로 내보낼 때 [Texture](../../com.aspose.threed/texture)에 대한 Video 인스턴스를 생성할지 여부를 가져옵니다.

**Returns:**
boolean - FBX로 내보낼 때 [Texture](../../com.aspose.threed/texture) 에 대한 Video 인스턴스를 생성할지 여부.
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




### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


텍스처를 최종 출력 파일에 포함시킬지 설정합니다. FBX Exporter는 [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem)에서 텍스처의 원시 데이터를 찾고, 파일을 최종 FBX 파일에 포함시킵니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


FBX 파일에서 큰 바이너리 데이터를 압축합니다(예: 애니메이션 데이터, 제어 포인트, 정점 요소 데이터, 인덱스), 기본값은 true입니다.

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

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


레거시 머티리얼 속성을 내보낼지 설정합니다. 이는 이전 호환성을 위해 사용됩니다. 이 옵션은 기본적으로 켜져 있습니다.

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

### setFoldRepeatedCurveData(Boolean value) {#setFoldRepeatedCurveData-java.lang.Boolean-}
```
public void setFoldRepeatedCurveData(Boolean value)
```


마지막 데이터의 참조 카운트를 증가시켜 반복되는 곡선 데이터를 재사용할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Boolean | 새 값 |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


첨부된 노드에 머티리얼이 포함된 경우, 기하학에 대해 항상 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 을 생성할지 설정합니다. 기본값은 꺼져 있습니다.

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

### setReusePrimitiveMesh(boolean value) {#setReusePrimitiveMesh-boolean-}
```
public void setReusePrimitiveMesh(boolean value)
```


같은 매개변수를 가진 프리미티브에 대해 메쉬를 재사용하면, 대량의 프리미티브 형태로 구성된 씬의 FBX 출력 크기를 크게 줄일 수 있습니다(CAD 파일에서 가져온 경우와 같이). 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


FBX로 내보낼 때 [Texture](../../com.aspose.threed/texture)에 대한 Video 인스턴스를 생성할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

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

