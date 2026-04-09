---
title: 类 Group
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Group 类。Group 表示 Node 的逻辑关系
type: docs
weight: 1570
url: /zh/net/aspose.threed/group/
---
## Group class

`Group` 表示[`Node`](../node/)的逻辑关系。

```csharp
public class Group : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Group](group/)(string) | 构造 `Group` 的新实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | 子组 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | 此组中的节点 |
| [Parent](../../aspose.threed/group/parent/) { get; } | 当前组的父组 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| override [ToString](../../aspose.threed/group/tostring/)() | 获取 `Group` 的字符串表示 |

### 另请参见

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


