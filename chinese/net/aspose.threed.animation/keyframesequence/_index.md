---
title: "类 KeyframeSequence"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Animation.KeyframeSequence 类。关键帧序列描述了随时间对采样值的变换"
type: docs
weight: 100
url: /zh/net/aspose.threed.animation/keyframesequence/
---
## KeyframeSequence class

关键帧序列，描述采样值随时间的变化。

```csharp
public class KeyframeSequence : A3DObject, IEnumerable<KeyFrame>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [KeyframeSequence](keyframesequence/#constructor)() | 初始化 `KeyframeSequence` 类的新实例。 |
| [KeyframeSequence](keyframesequence/#constructor_1)(string) | 初始化 `KeyframeSequence` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | 获取拥有此曲线的属性绑定点 |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | 获取此曲线的关键帧。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | 获取后置行为，指示在最后一个关键帧之后采样值应为何。 |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | 获取前置行为，指示在第一个关键帧之前采样值应为何。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add)(double, float) | 使用指定值创建新的关键帧 |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add_1)(double, float, Interpolation) | 使用指定值创建新的关键帧 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | 获取枚举器以遍历所有关键帧。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | 移除所有关键帧并重置后置/前置行为。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [KeyFrame](../keyframe/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


