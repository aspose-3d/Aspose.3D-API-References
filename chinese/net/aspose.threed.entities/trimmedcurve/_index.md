---
title: TrimmedCurve
second_title: Aspose.3D for .NET API 参考
description: 在两端修剪基础曲线的有界曲线
type: docs
weight: 750
url: /zh/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

在两端修剪基础曲线的有界曲线。

```csharp
public class TrimmedCurve : Curve
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TrimmedCurve](trimmedcurve)() | 的构造函数[`TrimmedCurve`](../trimmedcurve) |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve) { get; set; } | 要修剪的基础曲线。 |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | 获取或设置线条的颜色，默认值为白色(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | 获取或设置导出时是否排除该实体。 |
| [First](../../aspose.threed.entities/trimmedcurve/first) { get; set; } | 要修剪的第一个端点，可以是笛卡尔点或实参数。 |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，该实体将与其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | 获取所有父节点，一个实体可以附加到多个父节点进行几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | 获取所有属性的集合。 |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection) { get; set; } | 获取或设置修剪后的结果是否使用同方向的基础曲线。 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | 获取该对象所属的场景 |
| [Second](../../aspose.threed.entities/trimmedcurve/second) { get; set; } | 要修剪的第二个端点，可以是笛卡尔点或实参数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | 查找属性。 可以是动态属性（由 CreateDynamicProperty/SetProperty 创建） 或原生属性（由其名称标识） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | 获取当前实体在其对象空间坐标系中的边界框。 |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | 获取渲染器中注册的实体渲染器的key |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | 删除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | 移除名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | 设置指定属性的值 |

### 也可以看看

* class [Curve](../curve)
* 命名空间 [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
