---
title: 类 BooleanOperator
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Entities.BooleanOperator 类。布尔运算符允许您对两个 IMeshConvertible 实例执行布尔操作。
type: docs
weight: 280
url: /zh/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

布尔运算符允许您对两个 [`IMeshConvertible`](../imeshconvertible/) 实例执行布尔操作。

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | `BooleanOperator` 的构造函数 |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | 使用两个操作数构造一个新的 `BooleanOperator` 实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | 布尔运算符的第一个操作数 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | 用于创建结果网格的操作中的布尔运算符。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点；如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | 布尔运算符的第二个操作数 |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | 对两个操作数执行布尔运算 |

### 另请参见

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


