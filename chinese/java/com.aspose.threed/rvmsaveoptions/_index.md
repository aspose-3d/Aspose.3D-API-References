---
title: "RvmSaveOptions"
second_title: "Aspose.3D for Java API 参考"
description: "保存 Aveva PDMS RVM 文件的选项。"
type: docs
weight: 158
url: /zh/java/com.aspose.threed/rvmsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class RvmSaveOptions extends SaveOptions
```

Aveva PDMS RVM 文件的保存选项。**示例：** 以下代码展示了如何在 RVM 中导出属性。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RvmSaveOptions()](#RvmSaveOptions--) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) 的构造函数 |
| [RvmSaveOptions(FileContentType contentType)](#RvmSaveOptions-com.aspose.threed.FileContentType-) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) 的构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributeListFile()](#getAttributeListFile--) | 获取属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。 |
| [getAttributePrefix()](#getAttributePrefix--) | 获取将被导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。 |
| [getAuthor()](#getAuthor--) | 作者信息，默认值为 '3d@aspose' |
| [getClass()](#getClass--) |  |
| [getCreationTime()](#getCreationTime--) | 导出此文件的时间戳，默认值为当前时间 |
| [getEncoding()](#getEncoding--) | 获取基于文本的文件的默认编码。 |
| [getExportAttributes()](#getExportAttributes--) | 获取是否将属性列表导出到外部 .att 文件，默认值为 false。 |
| [getExportTextures()](#getExportTextures--) | 尝试将场景中使用的纹理复制到输出目录。 |
| [getFileFormat()](#getFileFormat--) | 获取当前保存/加载选项中指定的文件格式。 |
| [getFileName()](#getFileName--) | 导出/导入场景的文件名。 |
| [getFileNote()](#getFileNote--) | 文件头中的文件备注。 |
| [getFileSystem()](#getFileSystem--) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | 获取 FileSystem 的工厂类。 |
| [getLookupPaths()](#getLookupPaths--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributeListFile(String value)](#setAttributeListFile-java.lang.String-) | 设置属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。 |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | 设置将要导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 作者信息，默认值为 '3d@aspose' |
| [setCreationTime(String value)](#setCreationTime-java.lang.String-) | 导出此文件的时间戳，默认值为当前时间 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置基于文本的文件的默认编码。 |
| [setExportAttributes(boolean value)](#setExportAttributes-boolean-) | 设置是否将属性列表导出到外部 .att 文件，默认值为 false。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 尝试将场景中使用的纹理复制到输出目录。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 导出/导入场景的文件名。 |
| [setFileNote(String value)](#setFileNote-java.lang.String-) | 文件头中的文件备注。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | 设置 FileSystem 的工厂类。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmSaveOptions() {#RvmSaveOptions--}
```
public RvmSaveOptions()
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) 的构造函数

### RvmSaveOptions(FileContentType contentType) {#RvmSaveOptions-com.aspose.threed.FileContentType-}
```
public RvmSaveOptions(FileContentType contentType)
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) 的构造函数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | 文本还是二进制 RVM 文件？ |

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
### getAttributeListFile() {#getAttributeListFile--}
```
public String getAttributeListFile()
```


获取属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。

**Returns:**
java.lang.String - 属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。 **Example:** 以下代码展示了如何在 RVM 中导出属性。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


获取将要导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。例如，如果属性为 rvm:Refno=345，导出的属性将为 Refno = 345，前缀被去除。

**Returns:**
java.lang.String - 将要导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。例如，如果属性为 rvm:Refno=345，导出的属性将为 Refno = 345，前缀被去除。 **Example:** 以下代码展示了如何在 RVM 中导出属性。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


作者信息，默认值为 '3d@aspose'

**Returns:**
java.lang.String - 作者信息，默认值为 '3d@aspose' **Example:** 以下代码展示了如何在 RVM 中导出属性。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationTime() {#getCreationTime--}
```
public String getCreationTime()
```


导出此文件的时间戳，默认值为当前时间

**Returns:**
java.lang.String - 导出此文件的时间戳，默认值为当前时间
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


获取基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Returns:**
java.nio.charset.Charset - 基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。
### getExportAttributes() {#getExportAttributes--}
```
public boolean getExportAttributes()
```


获取是否将属性列表导出到外部 .att 文件，默认值为 false。

**Returns:**
boolean - 是否将属性列表导出到外部 .att 文件，默认值为 false。 **Example:** 以下代码展示了如何在 RVM 中导出属性。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
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
### getFileNote() {#getFileNote--}
```
public String getFileNote()
```


文件头中的文件备注。

**Returns:**
java.lang.String - 文件头中的文件备注。 **Example:** 以下代码展示了如何在 RVM 中导出属性。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
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




### setAttributeListFile(String value) {#setAttributeListFile-java.lang.String-}
```
public void setAttributeListFile(String value)
```


设置属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 新值 **Example:** 以下代码展示了如何在 RVM 中导出属性。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


设置将要导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。例如，如果属性为 rvm:Refno=345，导出的属性将为 Refno = 345，前缀被去除。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 新值 **Example:** 以下代码展示了如何在 RVM 中导出属性。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


作者信息，默认值为 '3d@aspose'

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 新值 **Example:** 以下代码展示了如何在 RVM 中导出属性。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setCreationTime(String value) {#setCreationTime-java.lang.String-}
```
public void setCreationTime(String value)
```


导出此文件的时间戳，默认值为当前时间

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


设置基于文本文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset | 新值 |

### setExportAttributes(boolean value) {#setExportAttributes-boolean-}
```
public void setExportAttributes(boolean value)
```


设置是否将属性列表导出到外部 .att 文件，默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | 布尔 | 新值 **Example:** 以下代码展示了如何在 RVM 中导出属性。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

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

### setFileNote(String value) {#setFileNote-java.lang.String-}
```
public void setFileNote(String value)
```


文件头中的文件备注。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 新值 **Example:** 以下代码展示了如何在 RVM 中导出属性。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

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

