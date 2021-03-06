---
title: Skeleton
second_title: Aspose.3D for .NET API 参考
description: Skeleton./skeleton主要用于 CAD 软件帮助设计者操纵骨骼结构的变换它通常在 CAD 软件之外是无用的 为了使骨架层次在 CAD 软件中像一个对象一样需要通过设置将顶部的Skeleton./skeleton节点标记为根节点Type./skeleton/type到Skeleton 和所有孩子设置为Bone
type: docs
weight: 650
url: /zh/net/aspose.threed.entities/skeleton/
---
## Skeleton class

[`Skeleton`](../skeleton)主要用于 CAD 软件帮助设计者操纵骨骼结构的变换，它通常在 CAD 软件之外是无用的。 为了使骨架层次在 CAD 软件中像一个对象一样，需要通过设置将顶部的[`Skeleton`](../skeleton)节点标记为根节点[`Type`](./type)到Skeleton, 和所有孩子设置为Bone

```csharp
public class Skeleton : Entity
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Skeleton](skeleton#constructor)() | 初始化[`Skeleton`](../skeleton)类的新实例。 |
| [Skeleton](skeleton#constructor_1)(string) | 初始化[`Skeleton`](../skeleton)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | 获取或设置是否在导出时排除该实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，该实体将与其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | 获取所有父节点，一个实体可以附加到多个父节点进行几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | 获取该对象所属的场景 |
| [Size](../../aspose.threed.entities/skeleton/size) { get; set; } | 获取或设置 CAD 软件中用于表示骨骼大小的肢体节点大小。 |
| [Type](../../aspose.threed.entities/skeleton/type) { get; set; } | 获取或设置骨架的类型。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | 查找属性。 可以是动态属性（由 CreateDynamicProperty/SetProperty 创建） 或本机属性（由其名称标识） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | 获取当前实体在其对象空间坐标系中的边界框。 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | 获取在渲染器中注册的实体渲染器的key |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | 删除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | 删除名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | 设置指定属性的值 |

### 也可以看看

* class [Entity](../../aspose.threed/entity)
* 命名空间 [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
