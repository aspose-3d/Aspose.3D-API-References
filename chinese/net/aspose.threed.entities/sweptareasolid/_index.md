---
title: "类 SweptAreaSolid"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.SweptAreaSolid 类。SweptAreaSolid 通过沿导线扫掠轮廓来构建几何体。"
type: docs
weight: 750
url: /zh/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

一个 `SweptAreaSolid` 通过沿导线扫掠轮廓来构建几何体。

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SweptAreaSolid](sweptareasolid/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix/) { get; set; } | SweptAreaSolid 所扫掠的导线。 |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint/) { get; set; } | 导线的端点。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape/) { get; set; } | 用于构建几何体的基础轮廓。 |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint/) { get; set; } | 导线的起点。 |

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
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh/)() | 将当前对象转换为网格 |

## 示例

以下代码展示了如何通过在圆上扫掠 C 形来建模实体。

```csharp
var directrix = new Circle(20);
var shape = new CShape();

var swept = new SweptAreaSolid()
{
  Shape = shape,
  Directrix = directrix,
  StartPoint = EndPoint.FromDegree(0),
  EndPoint = EndPoint.FromDegree(130)
};

var scene = new Scene();
scene.RootNode.CreateChildNode(swept);
scene.Save("swept.obj");
```

### 另请参见

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


