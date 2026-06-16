---
title: "RvmLoadOptions"
second_title: "Aspose.3D for Java API 参考"
description: "AVEVA Plant Design Management Systems RVM 文件的加载选项。"
type: docs
weight: 157
url: /zh/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

AVEVA Plant Design Management System 的 RVM 文件的加载选项。**Example:** 以下代码展示了如何使用 RvmLoadOptions 自定义从 RVM 文件导入的原始几何体的细分参数。

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | 构造一个 [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 实例 |
| [RvmLoadOptions()](#RvmLoadOptions--) | 构造一个 [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 实例 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | 获取在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:" |
| [getCenterScene()](#getCenterScene--) | 在加载后将场景居中。 |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | 获取圆柱体的径向段数，默认值为 16 |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | 获取碟形体的纬度段数，默认值为 8 |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | 获取碟形体的经度段数，默认值为 12 |
| [getEncoding()](#getEncoding--) | 获取基于文本的文件的默认编码。 |
| [getFileFormat()](#getFileFormat--) | 获取当前保存/加载选项中指定的文件格式。 |
| [getFileName()](#getFileName--) | 导出/导入场景的文件名。 |
| [getFileSystem()](#getFileSystem--) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | 获取 FileSystem 的工厂类。 |
| [getGenerateMaterials()](#getGenerateMaterials--) | 如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。 |
| [getLookupAttributes()](#getLookupAttributes--) | 获取是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。 |
| [getLookupPaths()](#getLookupPaths--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | 获取矩形环面的径向段数，默认值为 20 |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | 获取环面的管段数，默认值为 20 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | 设置在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:" |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | 在加载后将场景居中。 |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | 设置圆柱体的径向段数，默认值为 16 |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | 设置碟形体的纬度段数，默认值为 8 |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | 设置碟形体的经度段数，默认值为 12 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置基于文本的文件的默认编码。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 导出/导入场景的文件名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | 设置 FileSystem 的工厂类。 |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | 如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。 |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | 设置是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | 设置矩形环面的径向段数，默认值为 20 |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | 设置环面的管段数，默认值为 20 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


构造一个 [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


构造一个 [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) 实例

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


获取在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:"

**Returns:**
java.lang.String - 在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


在加载后将场景居中。

**Returns:**
boolean - 在加载后居中场景。
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


获取圆柱体的径向段数，默认值为 16

**Returns:**
int - 圆柱体的径向段数，默认值为 16
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


获取碟形体的纬度段数，默认值为 8

**Returns:**
int - 餐盘的纬度段数，默认值为 8
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


获取碟形体的经度段数，默认值为 12

**Returns:**
int - 餐盘的经度段数，默认值为 12
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


获取基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Returns:**
java.nio.charset.Charset - 基于文本的文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。默认值为 true

**Returns:**
boolean - 如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。默认值为 true
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


获取是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。

**Returns:**
boolean - 是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


获取矩形环面的径向段数，默认值为 20

**Returns:**
int - 矩形环的径向段数，默认值为 20
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


获取环面的管段数，默认值为 20

**Returns:**
int - 环的管状段数，默认值为 20
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


设置在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:"

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


在加载后将场景居中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


设置圆柱体的径向段数，默认值为 16

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


设置碟形体的纬度段数，默认值为 8

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


设置碟形体的经度段数，默认值为 12

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


设置基于文本文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset | 新值 |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。默认值为 true

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


设置是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


设置矩形环面的径向段数，默认值为 20

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


设置环面的管段数，默认值为 20

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

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

