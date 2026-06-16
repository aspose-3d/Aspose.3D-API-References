---
title: "类 AnimationNode"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Animation.AnimationNode 类。Aspose.3Ds 支持动画层次结构，每个动画可以由多个动画及其关键帧定义组成。AnimationNode 定义属性值随时间的变换，例如动画节点可用于控制节点的变换或其他 A3DObject 对象的数值属性。"
type: docs
weight: 40
url: /zh/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D 支持动画层次结构，每个动画可以由多个动画及其关键帧定义组成。`AnimationNode` 定义属性值随时间的变换，例如，动画节点可用于控制节点的变换或其他 [`A3DObject`](../../aspose.threed/a3dobject/) 对象的数值属性。

```csharp
public class AnimationNode : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | 初始化 `AnimationNode` 类的新实例。 |
| [AnimationNode](animationnode/#constructor_1)(string) | 初始化 `AnimationNode` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | 获取当前属性绑定点 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | 获取当前动画下的子动画节点 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | 根据属性数据类型创建 BindPoint。 |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | 通过目标和名称查找绑定点。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | 获取给定属性上的动画绑定点。 |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | 获取给定属性上的关键帧序列。 |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | 获取给定属性和通道上的关键帧序列。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


