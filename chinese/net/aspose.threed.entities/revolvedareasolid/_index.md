---
title: "类 RevolvedAreaSolid"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.RevolvedAreaSolid 类。此类通过围绕轴旋转由轮廓提供的横截面来表示实体模型。"
type: docs
weight: 680
url: /zh/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

此类通过围绕轴旋转由轮廓提供的横截面来表示实体模型。

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | 获取或设置旋转过程的结束角度，单位为弧度，默认值为 π。 |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | 获取或设置旋转过程的起始角度，单位为弧度，默认值为 0。 |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | 获取或设置轴的方向，默认值为 (0, 1, 0)。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | 获取或设置旋转的原点，默认值为 (0, 0, 0)。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | 获取或设置用于旋转的基准轮廓。 |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | 将 `RevolvedAreaSolid` 转换为网格。 |

## 示例

以下代码展示了如何使用 RevolvedAreaSolid 将形状旋转为实体模型。

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//创建一个新的 3D 场景
Scene scene = new Scene();

// 初始化要旋转的基准轮廓
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//创建一个 RevolvedAreaSolid 实例
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//创建一个新的 3D 场景
Scene scene = new Scene();

// 初始化要拉伸的基准轮廓
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### 另请参见

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


