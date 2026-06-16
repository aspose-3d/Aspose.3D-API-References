---
title: "类 BindPoint"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Animation.BindPoint 类。BindPoint 通常在对象的属性上创建，某些属性类型包含多个组件字段，例如 Vector3 字段。BindPoint 将为每个组件字段生成通道，并通过这些通道将字段连接到一个或多个关键帧序列实例。"
type: docs
weight: 50
url: /zh/net/aspose.threed.animation/bindpoint/
---
## BindPoint class

`BindPoint` 通常在对象的属性上创建，某些属性类型包含多个组件字段（如 Vector3 字段），`BindPoint` 将为每个组件字段生成通道，并通过这些通道将字段连接到一个或多个关键帧序列实例。

```csharp
public class BindPoint : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | 初始化 `BindPoint` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | 获取此动画曲线映射中定义的属性通道总数。 |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | 获取与 CurveMapping 关联的属性 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | 添加指定的通道属性。 |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | 添加指定的通道属性。 |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | 将关键帧序列绑定到指定通道 |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | 创建新曲线并将其连接到曲线映射的第一个通道 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | 通过给定名称获取通道 |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | 获取指定通道中的第一个关键帧序列 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | 清空此动画曲线映射的属性通道。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | 将对象格式化为字符串。 |

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


