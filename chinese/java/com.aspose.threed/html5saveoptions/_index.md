---
title: "Html5SaveOptions"
second_title: "Aspose.3D for Java API 参考"
description: "HTML5 的保存选项。"
type: docs
weight: 80
url: /zh/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

HTML5 的保存选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | 使用所有默认设置的 [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | 获取相机的初始位置，默认值为 (10, 10, 10)。 |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | 获取基于文本的文件的默认编码。 |
| [getExportTextures()](#getExportTextures--) | 尝试将场景中使用的纹理复制到输出目录。 |
| [getFarPlane()](#getFarPlane--) | 获取相机的远裁剪面，默认值为 1000。 |
| [getFieldOfView()](#getFieldOfView--) | 获取视场角，默认值为 45，单位为度。 |
| [getFileFormat()](#getFileFormat--) | 获取当前保存/加载选项中指定的文件格式。 |
| [getFileName()](#getFileName--) | 导出/导入场景的文件名。 |
| [getFileSystem()](#getFileSystem--) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | 获取 FileSystem 的工厂类。 |
| [getLookAt()](#getLookAt--) | 获取默认的观察目标位置，默认值为 (0, 0, 0)。 |
| [getLookupPaths()](#getLookupPaths--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [getNearPlane()](#getNearPlane--) | 获取相机的近裁剪面，默认值为 1。 |
| [getOrientationBox()](#getOrientationBox--) | 显示方向框。 |
| [getShowGrid()](#getShowGrid--) | 在场景中显示网格。 |
| [getShowRulers()](#getShowRulers--) | 在场景中显示 x/y/z 轴的标尺以测量模型。 |
| [getShowUI()](#getShowUI--) | 在场景中显示简易 UI。 |
| [getUpVector()](#getUpVector--) | 获取上向量，取值可以是 "x"/"y"/"z"，默认值为 "y" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | 设置相机的初始位置，默认值为 (10, 10, 10) |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 设置基于文本的文件的默认编码。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | 尝试将场景中使用的纹理复制到输出目录。 |
| [setFarPlane(double value)](#setFarPlane-double-) | 设置相机的远平面，默认值为 1000。 |
| [setFieldOfView(double value)](#setFieldOfView-double-) | 设置视野的视场，默认值为 45，单位为度。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 导出/导入场景的文件名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | 设置 FileSystem 的工厂类。 |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | 设置默认的观察位置，默认值为 (0, 0, 0) |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [setNearPlane(double value)](#setNearPlane-double-) | 设置相机的近平面，默认值为 1 |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | 显示方向框。 |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | 在场景中显示网格。 |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | 在场景中显示 x/y/z 轴的标尺以测量模型。 |
| [setShowUI(boolean value)](#setShowUI-boolean-) | 在场景中显示简易 UI。 |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | 设置上向量，取值可以是 "x"/"y"/"z"，默认值为 "y" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


使用所有默认设置的 [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) 构造函数。

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
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


获取相机的初始位置，默认值为 (10, 10, 10)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the initial position of the camera, default value is (10, 10, 10)
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
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


尝试将场景中使用的纹理复制到输出目录。

**Returns:**
boolean - 尝试将场景中使用的纹理复制到输出目录。
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


获取相机的远裁剪面，默认值为 1000。

**Returns:**
double - 相机的远平面，默认值为 1000。
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


获取视场角，默认值为 45，单位为度。

**Returns:**
double - 视野的视场，默认值为 45，单位为度。
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
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


获取默认的观察目标位置，默认值为 (0, 0, 0)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
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
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


获取相机的近裁剪面，默认值为 1。

**Returns:**
double - 相机的近平面，默认值为 1
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


显示方向框。默认值为 true。

**Returns:**
boolean - 显示方向框。默认值为 true。
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


在场景中显示网格。默认值为 true。

**Returns:**
boolean - 在场景中显示网格。默认值为 true。
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


在场景中显示 x/y/z 轴的标尺以测量模型。默认值为 false。

**Returns:**
boolean - 在场景中显示 x/y/z 轴的标尺以测量模型。默认值为 false。
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


在场景中显示简易 UI。默认值为 true。

**Returns:**
boolean - 在场景中显示简易 UI。默认值为 true。
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


获取上向量，取值可以是 "x"/"y"/"z"，默认值为 "y"

**Returns:**
java.lang.String - 上向量，取值可以是 "x"/"y"/"z"，默认值为 "y"
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




### setCameraPosition(Vector3 value) {#setCameraPosition-com.aspose.threed.Vector3-}
```
public void setCameraPosition(Vector3 value)
```


设置相机的初始位置，默认值为 (10, 10, 10)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


设置相机的远平面，默认值为 1000。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


设置视野的视场，默认值为 45，单位为度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

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

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


设置默认的观察位置，默认值为 (0, 0, 0)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

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

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


设置相机的近平面，默认值为 1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


显示方向框。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


在场景中显示网格。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


在场景中显示 x/y/z 轴的标尺以测量模型。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


在场景中显示简易 UI。默认值为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


设置上向量，取值可以是 "x"/"y"/"z"，默认值为 "y"

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

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

