---
title: 类 Entity
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Entity 类。所有实体的基类。Entity 表示附加在类似 Light/Geometry 节点下的具体对象
type: docs
weight: 1030
url: /zh/net/aspose.threed/entity/
---
## Entity class

所有实体的基类。Entity 表示附加在类似[`Light`](../../aspose.threed.entities/light/)/[`Geometry`](../../aspose.threed.entities/geometry/)节点下的具体对象。

```csharp
public abstract class Entity : SceneObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Entity](entity/)(string) | 初始化 `Entity` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点；如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的边界框。 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


