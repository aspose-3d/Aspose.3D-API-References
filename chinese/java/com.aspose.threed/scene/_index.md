---
title: "场景"
second_title: "Aspose.3D for Java API 参考"
description: 
type: docs
weight: 161
url: /zh/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | 使用附加到新节点的实体初始化 [Scene](../../com.aspose.threed/scene) 类的新实例。 |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | 将 [Scene](../../com.aspose.threed/scene) 类初始化为子场景的新实例。 |
| [Scene()](#Scene--) | 初始化 [Scene](../../com.aspose.threed/scene) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [VERSION](#VERSION) | 获取当前发布版本 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [clear()](#clear--) | 清除场景内容并恢复默认设置。 |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | 用于创建和注册 [AnimationClip](../../com.aspose.threed/animationclip) 的简写函数。第一个 [AnimationClip](../../com.aspose.threed/animationclip) 将分配给 [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | 从给定路径打开场景 |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | 从给定路径打开场景 |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | 使用指定的文件格式从给定路径打开场景。 |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定路径打开场景。 |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | 使用指定的文件格式从给定路径打开场景。 |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定路径打开场景。 |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | 从给定流打开场景 |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | 从给定流打开场景 |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 使用指定的文件格式从给定流打开场景。 |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定流打开场景。 |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | 使用指定的 IO 配置从给定流打开场景。 |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 使用指定的 IO 配置从给定流打开场景。 |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 从给定流打开场景 |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | 从给定流打开场景 |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | 使用指定的文件格式从给定流打开场景。 |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定流打开场景。 |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | 使用指定的 IO 配置从给定流打开场景。 |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 使用指定的 IO 配置从给定流打开场景。 |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | 获取已命名的 [AnimationClip](../../com.aspose.threed/animationclip) |
| [getAnimationClips()](#getAnimationClips--) | 获取场景中定义的所有 [AnimationClip](../../com.aspose.threed/animationclip)。 |
| [getAssetInfo()](#getAssetInfo--) | 获取顶层资产信息 |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | 获取活动的 [AnimationClip](../../com.aspose.threed/animationclip) |
| [getLibrary()](#getLibrary--) | 未直接在场景层次结构中使用的对象可以在库中定义。 |
| [getName()](#getName--) | 获取名称。 |
| [getPoses()](#getPoses--) | 获取此场景中使用的所有 [Pose](../../com.aspose.threed/pose)。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getRootNode()](#getRootNode--) | 获取场景的根节点。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getSubScenes()](#getSubScenes--) | 获取所有子场景 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | 从给定流打开场景 |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | 从给定流打开场景 |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 使用指定的文件格式从给定流打开场景。 |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定流打开场景。 |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | 使用指定的 IO 配置从给定流打开场景。 |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 使用指定的 IO 配置从给定流打开场景。 |
| [open(InputStream stream)](#open-java.io.InputStream-) | 从给定流打开场景 |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | 从给定流打开场景 |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | 使用指定的文件格式从给定流打开场景。 |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定流打开场景。 |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | 使用指定的 IO 配置从给定流打开场景。 |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 使用指定的 IO 配置从给定流打开场景。 |
| [open(String fileName)](#open-java.lang.String-) | 从给定路径打开场景 |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | 从给定路径打开场景 |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | 使用指定的文件格式从给定路径打开场景。 |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定路径打开场景。 |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | 使用指定的文件格式从给定路径打开场景。 |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 使用指定的文件格式从给定路径打开场景。 |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | 从给定相机视角将场景渲染为位图。 |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | 从给定相机视角将场景渲染为位图。 |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | 从给定相机视角将场景渲染为外部文件。 |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | 从给定相机视角将场景渲染为外部文件。 |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | 从给定相机视角将场景渲染为外部文件。 |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 使用指定的文件格式将场景保存到流中。 |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式将场景保存到流中。 |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | 使用指定的文件格式将场景保存到流中。 |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 使用指定的文件格式将场景保存到流中。 |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | 使用指定的文件格式将场景保存到流中。 |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式将场景保存到流中。 |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | 使用指定的文件格式将场景保存到流中。 |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 使用指定的文件格式将场景保存到流中。 |
| [save(String fileName)](#save-java.lang.String-) | 使用指定的文件格式将场景保存到指定路径。 |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | 使用指定的文件格式将场景保存到指定路径。 |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 使用指定的文件格式将场景保存到指定路径。 |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | 使用指定的文件格式将场景保存到指定路径。 |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 使用指定的文件格式将场景保存到指定路径。 |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | 设置顶层资产信息 |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | 设置活动的[AnimationClip](../../com.aspose.threed/animationclip) |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


使用附加到新节点的实体初始化 [Scene](../../com.aspose.threed/scene) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | 附加到场景的初始实体 **示例：** 以下代码演示如何直接从[Entity](../../com.aspose.threed/entity)创建一个[getScene](../../com.aspose.threed/scene\#getScene)： |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


将 [Scene](../../com.aspose.threed/scene) 类初始化为子场景的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | 父场景。 |
| 名称 | java.lang.String | 场景名称。 |

### Scene() {#Scene--}
```
public Scene()
```


初始化 [Scene](../../com.aspose.threed/scene) 类的新实例。

### VERSION {#VERSION}
```
public static final String VERSION
```


获取当前发布版本

### clear() {#clear--}
```
public void clear()
```


清除场景内容并恢复默认设置。

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


用于创建和注册 [AnimationClip](../../com.aspose.threed/animationclip) 的简写函数。第一个 [AnimationClip](../../com.aspose.threed/animationclip) 将分配给 [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 动画剪辑名称 |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


从给定路径打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


从给定路径打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 流 | java.io.InputStream | 输入流，用户负责关闭流。 **示例：** 以下代码演示如何使用取消令牌源从流创建场景 |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 **示例：** 以下代码演示如何使用取消令牌源从流创建场景 |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 **示例：** 以下代码演示如何从流创建场景 |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 **示例：** 以下代码演示如何从流创建场景 |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 **示例：** 以下代码演示如何使用加载选项从流创建场景 |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 **示例：** 以下代码演示如何使用加载选项从流创建场景 |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


获取已命名的 [AnimationClip](../../com.aspose.threed/animationclip)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要查找的[AnimationClip](../../com.aspose.threed/animationclip)名称 |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


获取场景中定义的所有 [AnimationClip](../../com.aspose.threed/animationclip)。

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - 场景中定义的所有[AnimationClip](../../com.aspose.threed/animationclip)。
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


获取顶层资产信息

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


获取活动的 [AnimationClip](../../com.aspose.threed/animationclip)

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


未直接在场景层次结构中使用的对象可以在库中定义。当使用子场景并将可重用组件放在子场景下时，这非常有用。

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - 未直接在场景层次结构中使用的对象可以在库中定义。当使用子场景并将可重用组件放在子场景下时，这非常有用。
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


获取此场景中使用的所有 [Pose](../../com.aspose.threed/pose)。

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - 此场景中使用的所有[Pose](../../com.aspose.threed/pose)。
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


获取场景的根节点。

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


获取所有子场景

**Returns:**
java.util.List<com.aspose.threed.Scene> - 所有子场景
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




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 流 | java.io.InputStream | 输入流，用户负责关闭流。 **示例：** 以下代码演示如何从流打开场景 |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


从给定流打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 **示例:** 以下代码展示了如何使用取消令牌从流中打开场景 |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 **示例:** 以下代码展示了如何从流中打开场景 |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 **示例:** 以下代码展示了如何从流中打开场景 |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 **示例:** 以下代码展示了如何使用额外的加载选项从流中打开场景 |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


使用指定的 IO 配置从给定流打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 输入流，用户负责关闭流。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 **示例:** 以下代码展示了如何使用额外的加载选项从流中打开场景 |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


从给定路径打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


从给定路径打开场景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 文件格式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


使用指定的文件格式从给定路径打开场景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 打开流的更详细配置。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 加载任务的取消令牌 |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


从给定相机视角将场景渲染为位图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 从哪个相机的视角渲染场景 |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 渲染结果的目标 |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


从给定相机视角将场景渲染为位图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 从哪个相机的视角渲染场景 |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 渲染结果的目标 |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | 自定义某些内部设置的选项。 |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


从给定相机的视角将场景渲染为外部文件。默认输出尺寸为 1024x768，输出格式为 png

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 从哪个相机的视角渲染场景 |
| 文件名 | java.lang.String | 输出文件的文件名 |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


从给定相机视角将场景渲染为外部文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 从哪个相机的视角渲染场景 |
| 文件名 | java.lang.String | 输出文件的文件名 |
| size | [Vector2](../../com.aspose.threed/vector2) | 最终渲染图像的尺寸 |
| 格式 | java.lang.String | 输出文件的图像格式 |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


从给定相机视角将场景渲染为外部文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 从哪个相机的视角渲染场景 |
| 文件名 | java.lang.String | 输出文件的文件名 |
| size | [Vector2](../../com.aspose.threed/vector2) | 最终渲染图像的尺寸 |
| 格式 | java.lang.String | 输出文件的图像格式 |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | 自定义某些内部设置的选项。 |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 格式。 |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 格式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存任务的取消令牌 |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 保存流的更详细配置。 |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 输入流，用户负责关闭流。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 保存流的更详细配置。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存任务的取消令牌 |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 输入流，用户负责关闭流。 |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | 格式。 **示例:** 以下代码展示了如何保存场景 |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 输入流，用户负责关闭流。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 格式。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存任务的取消令牌 **示例:** 以下代码展示了如何保存场景 |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 输入流，用户负责关闭流。 |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | 保存流的更详细配置。 **示例:** 以下代码展示了如何保存场景 |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


使用指定的文件格式将场景保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 输入流，用户负责关闭流。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 保存流的更详细配置。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存任务的取消令牌 **示例:** 以下代码展示了如何保存场景 |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


使用指定的文件格式将场景保存到指定路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


使用指定的文件格式将场景保存到指定路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 格式。 |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


使用指定的文件格式将场景保存到指定路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 格式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存任务的取消令牌 |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


使用指定的文件格式将场景保存到指定路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 保存流的更详细配置。 |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


使用指定的文件格式将场景保存到指定路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 保存流的更详细配置。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存任务的取消令牌 |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


设置顶层资产信息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | 新值 **示例:** 以下代码展示了如何从 FBX 文件读取应用程序信息： |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


设置活动的[AnimationClip](../../com.aspose.threed/animationclip)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

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

