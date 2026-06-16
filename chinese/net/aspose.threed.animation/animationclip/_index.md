---
title: "类 AnimationClip"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Animation.AnimationClip 类。Animation clip 是动画的集合。场景可以拥有一个或多个动画剪辑。"
type: docs
weight: 30
url: /zh/net/aspose.threed.animation/animationclip/
---
## AnimationClip class

动画剪辑是动画的集合。场景可以拥有一个或多个动画剪辑。

```csharp
public class AnimationClip : SceneObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AnimationClip](animationclip/#constructor)() | 初始化 `AnimationClip` 类的新实例。 |
| [AnimationClip](animationclip/#constructor_1)(string) | 初始化 `AnimationClip` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Animations](../../aspose.threed.animation/animationclip/animations/) { get; } | 获取剪辑中包含的动画。 |
| [Description](../../aspose.threed.animation/animationclip/description/) { get; set; } | 获取或设置此动画剪辑的描述 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Start](../../aspose.threed.animation/animationclip/start/) { get; set; } | 获取或设置剪辑开始时的时间（秒）。 |
| [Stop](../../aspose.threed.animation/animationclip/stop/) { get; set; } | 获取或设置剪辑结束时的时间（秒）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateAnimationNode](../../aspose.threed.animation/animationclip/createanimationnode/)(string) | 在当前剪辑上创建并注册动画节点的简写函数。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [SceneObject](../../aspose.threed/sceneobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


