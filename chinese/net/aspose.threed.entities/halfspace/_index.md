---
title: 类 HalfSpace
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Entities.HalfSpace 类。 HalfSpace 表示一个被平面划分的无限空间，可与 BooleanOperator 一起使用
type: docs
weight: 420
url: /zh/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` 表示一个被平面划分的无限空间，可与[`BooleanOperator`](../booleanoperator/)一起使用

```csharp
public class HalfSpace : Entity
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | 构造一个 `HalfSpace` 的新实例 |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | 使用给定的法向量和切割平面上的位置构造一个 `HalfSpace` 的新实例； |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | 分割平面的法向量，平面定义为 N * P + D = 0，其中 N 为法向量，P 为平面上的任意点。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点；如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | 分割平面上的任意点，平面定义为 N * P + D = 0，其中 N 为法向量，P 为平面上的任意点。 |
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

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


