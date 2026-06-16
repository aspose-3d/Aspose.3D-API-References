---
title: "类 Frustum"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Frustum 类。Camera 和 Light 的基类。"
type: docs
weight: 400
url: /zh/net/aspose.threed.entities/frustum/
---
## Frustum class

[`Camera`](../camera/) 和 [`Light`](../light/) 的基类。

```csharp
public abstract class Frustum : Entity, IOrientable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | 获取或设置视锥体的宽高比 |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | 获取或设置相机所看的方向。对该属性的更改还会影响 [`LookAt`](./lookat/) 和 [`Target`](./target/)。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | 获取或设置视锥体的远平面距离。 |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | 获取或设置相机所看的感兴趣位置。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | 获取或设置视锥体的近平面距离。 |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | 获取或设置视锥体在正交投影时的高度。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | 获取或设置视锥体的方向模式。此属性仅在 [`Target`](./target/) 为 null 时生效。如果值为 FixedTarget，则方向始终由属性 [`LookAt`](./lookat/) 计算；否则 [`LookAt`](./lookat/) 始终由 [`Direction`](./direction/) 计算。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | 获取或设置相机所看的目标。如果用户支持此属性，应优先于 [`LookAt`](./lookat/) 属性。 |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | 获取或设置相机的上方向 |

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
* interface [IOrientable](../iorientable/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


