---
title: "GltfSaveOptions"
second_title: "Aspose.3D for Java API 参考"
description: "glTF 格式的保存选项。"
type: docs
weight: 74
url: /zh/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

glTF 格式的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | 构造函数 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | 构造函数 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | 将 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 应用于网格。 |
| [getBufferFile()](#getBufferFile--) | 用于存储二进制数据的外部缓冲区文件的文件名。 |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | 获取是否启用 draco 压缩 |
| [getEmbedAssets()](#getEmbedAssets--) | 在 ASCII 模式下将所有外部资源以 base64 嵌入单个文件，默认值为 false。 |
| [getEncoding()](#getEncoding--) | 获取基于文本的文件的默认编码。 |
| [getExportTextures()](#getExportTextures--) | 尝试将场景中使用的纹理复制到输出目录。 |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | 使用外部 draco 编码器加速 draco 压缩速度。 |
| [getFallbackNormal()](#getFallbackNormal--) | 当 GLTF2 导出器检测到无效法线时，将使用此值替代原始值以绕过验证。 |
| [getFileFormat()](#getFileFormat--) | 获取当前保存/加载选项中指定的文件格式。 |
| [getFileName()](#getFileName--) | 导出/导入场景的文件名。 |
| [getFileSystem()](#getFileSystem--) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | 获取 FileSystem 的工厂类。 |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | 翻转纹理坐标 v(t) 分量，默认值为 true。 |
| [getImageFormat()](#getImageFormat--) | 标准 glTF 仅支持 PNG/JPG 作为纹理格式，此选项将指导 Aspose.3D 在导出期间如何将非标准图像转换为受支持的格式。 |
| [getLookupPaths()](#getLookupPaths--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [getMaterialConverter()](#getMaterialConverter--) | 自定义转换器用于将几何体的材质转换为 PBR 材质。如果未指定此项，glTF 2.0 导出器将自动将标准材质转换为 PBR 材质。 |
| [getPrettyPrint()](#getPrettyPrint--) | GLTF 文件的 JSON 内容已缩进以便人工阅读，默认值为 false。 |
| [getSaveExtras()](#getSaveExtras--) | 将场景对象的动态属性保存到生成的 glTF 文件的 'extra' 字段中。 |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | 使用 KHR 通用材质扩展序列化材质，默认值为 false。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | 将 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 应用于网格。 |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | 用于存储二进制数据的外部缓冲区文件的文件名。 |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | 设置是否启用 draco 压缩。 |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | 在 ASCII 模式下将所有外部资源以 base64 嵌入单个文件，默认值为 false。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置基于文本的文件的默认编码。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 尝试将场景中使用的纹理复制到输出目录。 |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | 使用外部 draco 编码器加速 draco 压缩速度。 |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | 当 GLTF2 导出器检测到无效法线时，将使用此值替代原始值以绕过验证。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 导出/导入场景的文件名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | 设置 FileSystem 的工厂类。 |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | 翻转纹理坐标 v(t) 分量，默认值为 true。 |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | 标准 glTF 仅支持 PNG/JPG 作为纹理格式，此选项将指导 Aspose.3D 在导出期间如何将非标准图像转换为受支持的格式。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | 自定义转换器用于将几何体的材质转换为 PBR 材质。如果未指定此项，glTF 2.0 导出器将自动将标准材质转换为 PBR 材质。 |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | GLTF 文件的 JSON 内容已缩进以便人工阅读，默认值为 false。 |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | 将场景对象的动态属性保存到生成的 glTF 文件的 'extra' 字段中。 |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | 使用 KHR 通用材质扩展序列化材质，默认值为 false。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


构造函数 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


构造函数 [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


将 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 应用于网格。默认值为 false。

**Returns:**
boolean - 将 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 应用于网格。默认值为 false。
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


用于存储二进制数据的外部缓冲区文件的文件名。如果未指定此文件，Aspose.3D 将为您生成一个名称。导出二进制模式的 glTF 时此设置将被忽略。

**Returns:**
java.lang.String - 用于存储二进制数据的外部缓冲区文件的文件名。如果未指定此文件，Aspose.3D 将为您生成一个名称。导出二进制模式的 glTF 时此设置将被忽略。
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


获取是否启用 draco 压缩

**Returns:**
boolean - 是否启用 draco 压缩
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


在 ASCII 模式下将所有外部资源以 base64 嵌入单个文件，默认值为 false。

**Returns:**
boolean - 在 ASCII 模式下将所有外部资源以 base64 嵌入单个文件，默认值为 false。
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


获取基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Returns:**
java.nio.charset.Charset - 基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


尝试将场景中使用的纹理复制到输出目录。

**Returns:**
boolean - 尝试将场景中使用的纹理复制到输出目录。
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


使用外部 draco 编码器加速 draco 压缩速度。

**Returns:**
java.lang.String - 使用外部 draco 编码器加速 draco 压缩速度。**Remarks:** Aspose.3D 将创建新子进程将网格编码为 draco 格式，使用需自行承担风险。
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


当 GLTF2 导出器检测到无效法线时，将使用此值替代原始值以绕过验证。默认值为 (0, 1, 0)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


获取当前保存/加载选项中指定的文件格式。

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


导出/导入场景的文件名。此项是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。

**Returns:**
java.lang.String - 导出/导入场景的文件名。此项是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


允许用户处理在加载/保存期间如何管理外部依赖项。

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

您也可以使用自己的实现。

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


获取 FileSystem 的工厂类。默认工厂将创建 com.aspose.threed.LocalFileSystem，但它不适用于服务器环境。

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


翻转纹理坐标 v(t) 分量，默认值为 true。

**Returns:**
boolean - 翻转纹理坐标 v(t) 分量，默认值为 true。
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


标准 glTF 仅支持 PNG/JPG 作为纹理格式，此选项将指导 Aspose.3D 在导出期间如何将非标准图像转换为受支持的格式。默认值为 [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)。

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。

**Returns:**
java.util.ArrayList<java.lang.String> - 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。**示例:** 以下代码展示了如何手动指定查找纹理，以便导入器能够找到。

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


自定义转换器用于将几何体的材质转换为 PBR 材质。如果未指定此项，glTF 2.0 导出器将自动将标准材质转换为 PBR 材质。默认值为 null，此属性在导出场景为 glTF 2.0 文件时使用。

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


GLTF 文件的 JSON 内容已缩进以便人工阅读，默认值为 false。

**Returns:**
boolean - GLTF 文件的 JSON 内容已缩进以便人工阅读，默认值为 false。
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


将场景对象的动态属性保存到生成的 glTF 文件的 'extra' 字段中。这对于提供特定于应用程序的数据很有用。默认值为 false。

**Returns:**
boolean - 将场景对象的动态属性保存到生成的 glTF 文件的 'extra' 字段中。这对于提供特定于应用程序的数据很有用，默认值为 false。
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


使用 KHR 通用材质扩展序列化材质，默认值为 false。如果将此设置为 false，Aspose.3D 将在 [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) 时导出一套顶点/片段着色器。

**Returns:**
boolean - 使用 KHR 通用材质扩展序列化材质，默认值为 false。如果将此设置为 false，Aspose.3D 将在 [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) 时导出一套顶点/片段着色器。**Remarks:** 此属性仅适用于 glTF 1.0。
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


将 [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) 应用于网格。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


用于存储二进制数据的外部缓冲区文件的文件名。如果未指定此文件，Aspose.3D 将为您生成一个名称。导出二进制模式的 glTF 时此设置将被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


设置是否启用 draco 压缩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


在 ASCII 模式下将所有外部资源以 base64 嵌入单个文件，默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


设置基于文本文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset | 新值 |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


尝试将场景中使用的纹理复制到输出目录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


使用外部 draco 编码器加速 draco 压缩速度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 **Remarks:** Aspose.3D 将创建新子进程将网格编码为 draco 格式，使用需自行承担风险。 |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


当 GLTF2 导出器检测到无效法线时，将使用此值替代原始值以绕过验证。默认值为 (0, 1, 0)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


导出/导入场景的文件名。此项是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


允许用户处理在加载/保存期间如何管理外部依赖项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | 新值 **示例:** 默认的 FileSystem 是 LocalFileSystem，在服务器端等环境中并不安全，但您可以通过指定不同的实现来覆盖文件系统访问。Aspose.3D 提供了多种 FileSystem 实现，例如： |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

您也可以使用自己的实现。

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


设置 FileSystem 的工厂类。默认工厂将创建 com.aspose.threed.LocalFileSystem，但它不适用于服务器环境。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | 新值 **示例:** SaveOptions/LoadOptions 中的默认 FileSystem 是基于目录的文件系统，您可以通过 IOConfig.FileSystemFactory 指定来覆盖默认实现： |

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


翻转纹理坐标 v(t) 分量，默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


标准 glTF 仅支持 PNG/JPG 作为纹理格式，此选项将指导 Aspose.3D 在导出期间如何将非标准图像转换为受支持的格式。默认值为 [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | 新值 |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.ArrayList<java.lang.String> | 新值 **示例:** 以下代码展示了如何手动指定查找纹理，以便导入器能够找到。 |

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


自定义转换器用于将几何体的材质转换为 PBR 材质。如果未指定此项，glTF 2.0 导出器将自动将标准材质转换为 PBR 材质。默认值为 null，此属性在导出场景为 glTF 2.0 文件时使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | 新值 |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


GLTF 文件的 JSON 内容已缩进以便人工阅读，默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


将场景对象的动态属性保存到生成的 glTF 文件的 'extra' 字段中。这对于提供特定于应用程序的数据很有用。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


使用 KHR 通用材质扩展序列化材质，默认值为 false。如果将此设置为 false，Aspose.3D 将在 [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) 时导出一套顶点/片段着色器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 **Remarks:** 此属性仅适用于 glTF 1.0。 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

