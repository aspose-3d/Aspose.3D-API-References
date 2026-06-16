---
title: "Skeleton 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Skeleton 类。Skeleton 主要被 CAD 软件使用，以帮助设计师操作骨架结构的变换，在 CAD 软件之外通常无用。为了使骨架层级在 CAD 软件中表现为一个对象，需要通过将 Type 设置为 Skeleton 将顶层 Skeleton 节点标记为根节点，并将所有子节点设置为 Bone。"
type: docs
weight: 710
url: /zh/net/aspose.threed.entities/skeleton/
---
## Skeleton class

The `Skeleton`主要用于CAD软件，帮助设计师操作骨架结构的变换，在CAD软件之外通常无用。为了使骨架层次在CAD软件中表现为一个对象，需要通过将[`Type`](./type/)设置为Skeleton，将顶部`Skeleton`节点标记为根节点，并将所有子节点设置为Bone。

```csharp
public class Skeleton : Entity
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | 初始化 `Skeleton` 类的新实例。 |
| [Skeleton](skeleton/#constructor_1)(string) | 初始化 `Skeleton` 类的新实例。 |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | 初始化 `Skeleton` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | 获取或设置在CAD软件中用于表示骨骼大小的肢体节点尺寸。 |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | 获取或设置骨架的类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


