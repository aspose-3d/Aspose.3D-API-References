---
title: "类 LinearExtrusion"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.LinearExtrusion 类。 线性挤压以 2D 形状为输入，并在第三维度上扩展该形状。"
type: docs
weight: 490
url: /zh/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

线性拉伸以二维形状为输入，并在第三维度上扩展该形状。

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | `LinearExtrusion` 实例的构造函数。 |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | `LinearExtrusion` 实例的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | 如果此值为 false，线性挤压的 Z 范围为 0 到 height，否则范围为 -height/2 到 height/2。 |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | 挤压方向，默认值为 (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | 挤压几何体的高度，默认值为 1.0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | 要挤压的基础形状。 |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | 扭曲挤压几何体的切片数，默认值为 1。 |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | 形状被挤压的角度数（度）。 |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | 用于扭曲的偏移量，默认值为 (0, 0, 0)。 |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | 将挤压转换为网格。 |

## 示例

以下代码展示了如何使用 LinearExtrusion 将形状挤压成实体模型。

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//创建一个新的 3D 场景
Scene scene = new Scene();

// 初始化要拉伸的基准轮廓
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// 创建左节点
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// 创建右节点
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//使用 center 和 slices 属性对左节点执行线性拉伸
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// 使用 center 和 slices 属性对左节点执行线性拉伸
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### 另请参见

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


