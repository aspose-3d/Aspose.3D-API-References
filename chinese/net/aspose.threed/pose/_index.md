---
title: Pose 类
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Pose 类。姿势用于在几何体蒙皮时存储变换矩阵。姿势是一组 BonePose，每个 BonePose 保存骨节点的具体变换信息。
type: docs
weight: 1650
url: /zh/net/aspose.threed/pose/
---
## Pose class

当几何体进行蒙皮时，姿势用于存储变换矩阵。姿势是一组[`BonePose`](../bonepose/)，每个[`BonePose`](../bonepose/)保存骨骼节点的具体变换信息。

```csharp
public class Pose : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Pose](pose/#constructor)() | 初始化 `Pose` 类的新实例。 |
| [Pose](pose/#constructor_1)(string) | 初始化 `Pose` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | 获取所有[`BonePose`](../bonepose/)。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | 获取或设置姿势的类型。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | 为给定的骨骼节点保存姿势变换矩阵。默认使用全局变换矩阵。 |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | 为给定的骨骼节点保存姿势变换矩阵。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


