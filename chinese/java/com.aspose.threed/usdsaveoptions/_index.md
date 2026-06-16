---
title: "UsdSaveOptions"
second_title: "Aspose.3D for Java API 参考"
description: "USD/USDZ 格式的保存选项。"
type: docs
weight: 200
url: /zh/java/com.aspose.threed/usdsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class UsdSaveOptions extends SaveOptions
```

USD/USDZ 格式的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [UsdSaveOptions()](#UsdSaveOptions--) | 使用 [FileFormat.USD](../../com.aspose.threed/fileformat\\#USD) 格式初始化一个新的 [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions)。 |
| [UsdSaveOptions(FileFormat fileFormat)](#UsdSaveOptions-com.aspose.threed.FileFormat-) | 使用指定的 USD/USDZ 格式初始化一个新的 [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions)。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | 获取基于文本的文件的默认编码。 |
| [getExportMetaData()](#getExportMetaData--) | 通过 USD 的 customData 字段导出节点的属性。 |
| [getExportTextures()](#getExportTextures--) | 尝试将场景中使用的纹理复制到输出目录。 |
| [getFileFormat()](#getFileFormat--) | 获取当前保存/加载选项中指定的文件格式。 |
| [getFileName()](#getFileName--) | 导出/导入场景的文件名。 |
| [getFileSystem()](#getFileSystem--) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | 获取 FileSystem 的工厂类。 |
| [getLookupPaths()](#getLookupPaths--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [getMaterialConverter()](#getMaterialConverter--) | 自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，USD 导出器将自动将标准材质转换为 PBR 材质。 |
| [getPrimitiveToMesh()](#getPrimitiveToMesh--) | 在导出过程中将原始实体转换为网格。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置基于文本的文件的默认编码。 |
| [setExportMetaData(boolean value)](#setExportMetaData-boolean-) | 通过 USD 的 customData 字段导出节点的属性。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 尝试将场景中使用的纹理复制到输出目录。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 导出/导入场景的文件名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | 设置 FileSystem 的工厂类。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | 自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，USD 导出器将自动将标准材质转换为 PBR 材质。 |
| [setPrimitiveToMesh(boolean value)](#setPrimitiveToMesh-boolean-) | 在导出过程中将原始实体转换为网格。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UsdSaveOptions() {#UsdSaveOptions--}
```
public UsdSaveOptions()
```


使用 [FileFormat.USD](../../com.aspose.threed/fileformat\\#USD) 格式初始化一个新的 [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions)。

### UsdSaveOptions(FileFormat fileFormat) {#UsdSaveOptions-com.aspose.threed.FileFormat-}
```
public UsdSaveOptions(FileFormat fileFormat)
```


使用指定的 USD/USDZ 格式初始化一个新的 [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


获取基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Returns:**
java.nio.charset.Charset - 基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。
### getExportMetaData() {#getExportMetaData--}
```
public boolean getExportMetaData()
```


通过 USD 的 customData 字段导出节点的属性。

**Returns:**
boolean - 通过 USD 的 customData 字段导出节点的属性。
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


自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，USD 导出器将自动将标准材质转换为 PBR 材质。默认值为 null。

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, USD exporter will automatically convert the standard material to PBR material. Default value is null
### getPrimitiveToMesh() {#getPrimitiveToMesh--}
```
public boolean getPrimitiveToMesh()
```


在导出期间将原始实体转换为网格。或者直接将原始实体编码到输出文件（将使用 Aspose 的扩展定义来处理非官方原始体，如 Dish、Torus）。默认值为 true。

**Returns:**
boolean - 在导出期间将原始实体转换为网格。或者直接将原始实体编码到输出文件（将使用 Aspose 的扩展定义来处理非官方原始体，如 Dish、Torus）。默认值为 true。
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




### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


设置基于文本文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset | 新值 |

### setExportMetaData(boolean value) {#setExportMetaData-boolean-}
```
public void setExportMetaData(boolean value)
```


通过 USD 的 customData 字段导出节点的属性。

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


自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，USD 导出器将自动将标准材质转换为 PBR 材质。默认值为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | 新值 |

### setPrimitiveToMesh(boolean value) {#setPrimitiveToMesh-boolean-}
```
public void setPrimitiveToMesh(boolean value)
```


在导出期间将原始实体转换为网格。或者直接将原始实体编码到输出文件（将使用 Aspose 的扩展定义来处理非官方原始体，如 Dish、Torus）。默认值为 true。

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

