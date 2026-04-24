---
title: 类 Scene
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Scene 类。Scene 是一个顶层对象，包含节点、几何体、材质、纹理、动画、姿势、子场景等。Scene 可以拥有子场景，在 collada、blender、fbx 等文件中充当多文档支持。节点层次结构可通过 RootNode 访问。Library 用于在序列化期间保存未附加对象的引用（如元数据或自定义对象），因此可用作库。
type: docs
weight: 2500
url: /zh/net/aspose.threed/scene/
---
## Scene class

场景是一个顶层对象，包含节点、几何体、材质、纹理、动画、姿势、子场景等。Scene 可以拥有子场景，在 collada、blender、fbx 等文件中充当多文档支持。节点层次结构可通过 [`RootNode`](./rootnode/)[`Library`](./library/) 访问，Library 用于在序列化期间保存未附加对象的引用（如元数据或自定义对象），因此可用作库。

```csharp
public class Scene : SceneObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Scene](scene/#constructor)() | 初始化 `Scene` 类的新实例。 |
| [Scene](scene/#constructor_1)(Entity) | 初始化 `Scene` 类的新实例，并将实体附加到一个新节点。 |
| [Scene](scene/#constructor_2)(Scene, string) | 将 `Scene` 类初始化为子场景实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | 获取场景中定义的所有 [`AnimationClip`](../../aspose.threed.animation/animationclip/)。 |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | 获取或设置顶层资产信息。 |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | 获取或设置活动的[`AnimationClip`](../../aspose.threed.animation/animationclip/) |
| [Library](../../aspose.threed/scene/library/) { get; } | 未直接在场景层次结构中使用的对象可以在库中定义。当使用子场景并将可重用组件放在子场景下时，这非常有用。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Poses](../../aspose.threed/scene/poses/) { get; } | 获取此场景中使用的所有[`Pose`](../pose/)。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | 获取场景的根节点。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | 获取所有子场景 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | 从给定路径打开场景 |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | 从给定路径打开场景 |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | 使用指定的文件格式从给定路径打开场景。 |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | 使用指定的文件格式从给定路径打开场景。 |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | 从给定流打开场景 |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | 使用指定的文件格式从给定流打开场景。 |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | 使用指定的 IO 配置从给定流打开场景。 |
| [Clear](../../aspose.threed/scene/clear/)() | 清除场景内容并恢复默认设置。 |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | 一个用于创建和注册[`AnimationClip`](../../aspose.threed.animation/animationclip/)的简写函数。第一个[`AnimationClip`](../../aspose.threed.animation/animationclip/)将被分配给[`CurrentAnimationClip`](./currentanimationclip/)。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | 获取具名的[`AnimationClip`](../../aspose.threed.animation/animationclip/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | 从给定流打开场景 |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | 从给定路径打开场景 |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | 从给定流打开场景 |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | 从给定路径打开场景 |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | 使用指定的文件格式从给定路径打开场景。 |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | 使用指定的文件格式从给定流打开场景。 |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | 使用指定的 IO 配置从给定流打开场景。 |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | 使用指定的文件格式从给定路径打开场景。 |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | 使用指定的文件格式从给定路径打开场景。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | 从给定相机的视角将场景渲染为外部文件。默认输出尺寸为 1024x768，输出格式为 png |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | 从给定相机视角将场景渲染为位图。 |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | 从给定相机视角将场景渲染为位图。 |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | 从给定相机视角将场景渲染为外部文件。 |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | 从给定相机视角将场景渲染为外部文件。 |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | 使用指定的文件格式将场景保存到指定路径。 |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | 使用指定的文件格式将场景保存到流中。 |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | 使用指定的文件格式将场景保存到流中。 |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | 使用指定的文件格式将场景保存到指定路径。 |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | 使用指定的文件格式将场景保存到指定路径。 |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | 使用指定的文件格式将场景保存到流中。 |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | 使用指定的文件格式将场景保存到流中。 |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | 使用指定的文件格式将场景保存到指定路径。 |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | 使用指定的文件格式将场景保存到指定路径。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | 获取当前发布版本 |

### 另请参见

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


