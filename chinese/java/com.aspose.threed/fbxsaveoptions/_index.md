---
title: "FbxSaveOptions"
second_title: "Aspose.3D for Java API 参考"
description: "Fbx 文件的保存选项。"
type: docs
weight: 63
url: /zh/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Fbx 文件的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | 初始化一个 [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | 使用最新支持的版本初始化一个 [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | 获取是否将纹理嵌入最终输出文件。 |
| [getEnableCompression()](#getEnableCompression--) | 压缩 FBX 文件中的大型二进制数据（例如 |
| [getEncoding()](#getEncoding--) | 获取基于文本的文件的默认编码。 |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | 获取是否导出遗留材质属性，用于向后兼容。 |
| [getExportTextures()](#getExportTextures--) | 尝试将场景中使用的纹理复制到输出目录。 |
| [getFileFormat()](#getFileFormat--) | 获取当前保存/加载选项中指定的文件格式。 |
| [getFileName()](#getFileName--) | 导出/导入场景的文件名。 |
| [getFileSystem()](#getFileSystem--) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | 获取 FileSystem 的工厂类。 |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | 获取是否通过增加上一次数据的引用计数来复用重复的曲线数据 |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | 获取当附加节点包含材质时，是否始终为几何体生成 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)。 |
| [getLookupPaths()](#getLookupPaths--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | 对具有相同参数的原语复用网格，这将显著减小由大量原始形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。 |
| [getVideoForTexture()](#getVideoForTexture--) | 获取在导出为 FBX 时是否为 [Texture](../../com.aspose.threed/texture) 生成 Video 实例。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | 设置是否将纹理嵌入最终输出文件。 |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | 压缩 FBX 文件中的大型二进制数据（例如 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置基于文本的文件的默认编码。 |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | 设置是否导出遗留材质属性，用于向后兼容。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 尝试将场景中使用的纹理复制到输出目录。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 导出/导入场景的文件名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | 设置 FileSystem 的工厂类。 |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | 设置是否通过增加上一次数据的引用计数来复用重复的曲线数据 |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | 设置当附加节点包含材质时，是否始终为几何体生成 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | 对具有相同参数的原语复用网格，这将显著减小由大量原始形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。 |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | 设置在导出为 FBX 时是否为 [Texture](../../com.aspose.threed/texture) 生成 Video 实例。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


初始化一个 [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 是 [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat) 的实例，它应为有效的 FBN 格式。 |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


使用最新支持的版本初始化一个 [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | 二进制或 ASCII |

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


获取是否将纹理嵌入最终输出文件。FBX 导出器将尝试从 [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) 获取纹理的原始数据，并将文件嵌入最终的 FBX 文件。默认值为 false。

**Returns:**
boolean - 是否将纹理嵌入最终输出文件。FBX 导出器将尝试从 [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) 获取纹理的原始数据，并将文件嵌入最终的 FBX 文件。默认值为 false。
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


压缩 FBX 文件中的大型二进制数据（例如动画数据、控制点、顶点元素数据、索引），默认值为 true。

**Returns:**
boolean - 压缩 FBX 文件中的大型二进制数据（例如动画数据、控制点、顶点元素数据、索引），默认值为 true。
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


获取基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Returns:**
java.nio.charset.Charset - 基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


获取是否导出遗留材质属性，用于向后兼容。此选项默认开启。

**Returns:**
boolean - 是否导出遗留材质属性，用于向后兼容。此选项默认开启。
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


尝试将场景中使用的纹理复制到输出目录。

**Returns:**
boolean - 尝试将场景中使用的纹理复制到输出目录。
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
### getFoldRepeatedCurveData() {#getFoldRepeatedCurveData--}
```
public Boolean getFoldRepeatedCurveData()
```


获取是否通过增加上一次数据的引用计数来复用重复的曲线数据

**Returns:**
java.lang.Boolean - 是否通过增加上一次数据的引用计数来复用重复的曲线数据
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


获取当附加节点包含材质时，是否始终为几何体生成 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)。此选项默认关闭。

**Returns:**
boolean - 是否当附加节点包含材质时，始终为几何体生成 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)。此选项默认关闭。
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
### getReusePrimitiveMesh() {#getReusePrimitiveMesh--}
```
public boolean getReusePrimitiveMesh()
```


对具有相同参数的原语复用网格，这将显著减小由大量原始形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。默认值为 false

**Returns:**
boolean - 重用具有相同参数的基元网格，这将显著减小由大量基元形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。默认值为 false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


获取在导出为 FBX 时是否为 [Texture](../../com.aspose.threed/texture) 生成 Video 实例。

**Returns:**
boolean - 在导出为 FBX 时是否为 [Texture](../../com.aspose.threed/texture) 生成 Video 实例。
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


设置是否将纹理嵌入最终输出文件。FBX Exporter 将尝试从 [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\\#getFileSystem) 获取纹理的原始数据，并将文件嵌入最终的 FBX 文件。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


压缩 FBX 文件中的大型二进制数据（例如动画数据、控制点、顶点元素数据、索引），默认值为 true。

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

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


设置是否导出旧版材质属性，用于向后兼容。此选项默认开启。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


尝试将场景中使用的纹理复制到输出目录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

### setFoldRepeatedCurveData(Boolean value) {#setFoldRepeatedCurveData-java.lang.Boolean-}
```
public void setFoldRepeatedCurveData(Boolean value)
```


设置是否通过增加上一次数据的引用计数来复用重复的曲线数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Boolean | 新值 |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


设置是否在附加节点包含材质时始终为几何体生成 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)。默认关闭。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

### setReusePrimitiveMesh(boolean value) {#setReusePrimitiveMesh-boolean-}
```
public void setReusePrimitiveMesh(boolean value)
```


对具有相同参数的原语复用网格，这将显著减小由大量原始形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。默认值为 false

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


设置在导出为 FBX 时是否为 [Texture](../../com.aspose.threed/texture) 生成 Video 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

