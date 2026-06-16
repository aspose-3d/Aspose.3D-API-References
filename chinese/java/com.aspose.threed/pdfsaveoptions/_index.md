---
title: "PdfSaveOptions"
second_title: "Aspose.3D for Java API 参考"
description: "PDF 导出中的保存选项。"
type: docs
weight: 125
url: /zh/java/com.aspose.threed/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

PDF 导出中的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | [PdfSaveOptions](../../com.aspose.threed/pdfsaveoptions) 的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuxiliaryColor()](#getAuxiliaryColor--) | 获取渲染 3D 内容时使用的辅助颜色。 |
| [getBackgroundColor()](#getBackgroundColor--) | PDF 文件中 3D 视图的背景颜色。 |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | 将外部纹理嵌入 PDF 文件，默认值为 false。 |
| [getEncoding()](#getEncoding--) | 获取基于文本的文件的默认编码。 |
| [getExportTextures()](#getExportTextures--) | 尝试将场景中使用的纹理复制到输出目录。 |
| [getFaceColor()](#getFaceColor--) | 获取渲染 3D 内容时使用的面颜色。 |
| [getFileFormat()](#getFileFormat--) | 获取当前保存/加载选项中指定的文件格式。 |
| [getFileName()](#getFileName--) | 导出/导入场景的文件名。 |
| [getFileSystem()](#getFileSystem--) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | 获取 FileSystem 的工厂类。 |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | 获取在导出期间翻转场景坐标系的设置。 |
| [getLightingScheme()](#getLightingScheme--) | LightingScheme 指定要应用于 3D 艺术作品的照明。 |
| [getLookupPaths()](#getLookupPaths--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [getRenderMode()](#getRenderMode--) | 渲染模式指定 3D 艺术作品的渲染风格。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAuxiliaryColor(Vector3 value)](#setAuxiliaryColor-com.aspose.threed.Vector3-) | 设置渲染 3D 内容时使用的辅助颜色。 |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | PDF 文件中 3D 视图的背景颜色。 |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | 将外部纹理嵌入 PDF 文件，默认值为 false。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置基于文本的文件的默认编码。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 尝试将场景中使用的纹理复制到输出目录。 |
| [setFaceColor(Vector3 value)](#setFaceColor-com.aspose.threed.Vector3-) | 设置渲染 3D 内容时使用的面颜色。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 导出/导入场景的文件名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | 设置 FileSystem 的工厂类。 |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | 设置在导出期间翻转场景坐标系。 |
| [setLightingScheme(PdfLightingScheme value)](#setLightingScheme-com.aspose.threed.PdfLightingScheme-) | LightingScheme 指定要应用于 3D 艺术作品的照明。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [setRenderMode(PdfRenderMode value)](#setRenderMode-com.aspose.threed.PdfRenderMode-) | 渲染模式指定 3D 艺术作品的渲染风格。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


[PdfSaveOptions](../../com.aspose.threed/pdfsaveoptions) 的构造函数

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
### getAuxiliaryColor() {#getAuxiliaryColor--}
```
public Vector3 getAuxiliaryColor()
```


获取渲染 3D 内容时使用的辅助颜色。此颜色的解释取决于 [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the auxiliary color to be used when rendering the 3D content. The interpretation of this color depends on the [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode)
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


PDF 文件中 3D 视图的背景颜色。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Background color of the 3D view in PDF file.
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


将外部纹理嵌入 PDF 文件，默认值为 false。

**Returns:**
boolean - 将外部纹理嵌入 PDF 文件，默认值为 false。
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
### getFaceColor() {#getFaceColor--}
```
public Vector3 getFaceColor()
```


获取渲染 3D 内容时使用的面颜色。仅当 [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) 的值为 Illustration 时才相关。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the face color to be used when rendering the 3D content. This is only relevant only when the [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) has a value of Illustration.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


获取在导出期间翻转场景坐标系的设置。

**Returns:**
boolean - 在导出期间翻转场景坐标系。
### getLightingScheme() {#getLightingScheme--}
```
public PdfLightingScheme getLightingScheme()
```


LightingScheme 指定要应用于 3D 艺术作品的照明。

**Returns:**
[PdfLightingScheme](../../com.aspose.threed/pdflightingscheme) - LightingScheme specifies the lighting to apply to 3D artwork.
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
### getRenderMode() {#getRenderMode--}
```
public PdfRenderMode getRenderMode()
```


渲染模式指定 3D 艺术作品的渲染风格。

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode) - Render mode specifies the style in which the 3D artwork is rendered.
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




### setAuxiliaryColor(Vector3 value) {#setAuxiliaryColor-com.aspose.threed.Vector3-}
```
public void setAuxiliaryColor(Vector3 value)
```


设置渲染 3D 内容时使用的辅助颜色。此颜色的解释取决于 [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


PDF 文件中 3D 视图的背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


将外部纹理嵌入 PDF 文件，默认值为 false。

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

### setFaceColor(Vector3 value) {#setFaceColor-com.aspose.threed.Vector3-}
```
public void setFaceColor(Vector3 value)
```


设置渲染 3D 内容时使用的面颜色。仅当 [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) 的值为 Illustration 时才相关。

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


设置在导出期间翻转场景坐标系。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setLightingScheme(PdfLightingScheme value) {#setLightingScheme-com.aspose.threed.PdfLightingScheme-}
```
public void setLightingScheme(PdfLightingScheme value)
```


LightingScheme 指定要应用于 3D 艺术作品的照明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfLightingScheme](../../com.aspose.threed/pdflightingscheme) | 新值 |

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

### setRenderMode(PdfRenderMode value) {#setRenderMode-com.aspose.threed.PdfRenderMode-}
```
public void setRenderMode(PdfRenderMode value)
```


渲染模式指定 3D 艺术作品的渲染风格。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfRenderMode](../../com.aspose.threed/pdfrendermode) | 新值 |

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

