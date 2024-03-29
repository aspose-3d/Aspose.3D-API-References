---
title: AnimationNode
second_title: Aspose.3D for .NET API 参考
description: Aspose.3D 支持动画层次结构每个动画可以由多个动画和动画的关键帧定义组成 AnimationNode./animationnode定义一个属性值随时间的变换例如动画节点可以用来控制一个节点的变换或其他A3DObject../aspose.threed/a3dobject对象的数值属性.
type: docs
weight: 40
url: /zh/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D 支持动画层次结构，每个动画可以由多个动画和动画的关键帧定义组成。 [`AnimationNode`](../animationnode)定义一个属性值随时间的变换，例如动画节点可以用来控制一个节点的变换或其他[`A3DObject`](../../aspose.threed/a3dobject)对象的数值属性.

```csharp
public class AnimationNode : A3DObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [AnimationNode](animationnode#constructor)() | 初始化[`AnimationNode`](../animationnode)类. |
| [AnimationNode](animationnode#constructor_1)(string) | 初始化[`AnimationNode`](../animationnode)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints) { get; } | 获取当前属性绑定点 |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | 获取所有属性的集合。 |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations) { get; } | 获取当前动画下的子动画节点 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint)(A3DObject, string) | 基于属性数据类型创建一个 BindPoint。 |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint)(string) | 按名称查找绑定点。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | 查找属性。 可以是动态属性（由 CreateDynamicProperty/SetProperty 创建） 或原生属性（由其名称标识） |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint)(A3DObject, string, bool) | 获取给定属性的动画绑定点。 |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence#getkeyframesequence)(A3DObject, string, bool) | 获取给定属性的关键帧序列。 |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence#getkeyframesequence_1)(A3DObject, string, string, bool) | 获取给定属性和通道上的关键帧序列。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | 删除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | 移除名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | 设置指定属性的值 |

### 也可以看看

* class [A3DObject](../../aspose.threed/a3dobject)
* 命名空间 [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
