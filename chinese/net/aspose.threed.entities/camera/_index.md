---
title: "类 Camera"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.Camera 类。相机描述了观看场景的观察者的视点"
type: docs
weight: 300
url: /zh/net/aspose.threed.entities/camera/
---
## Camera class

相机描述了观察者观看场景的视点。

```csharp
public class Camera : Frustum
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Camera](camera/#constructor)() | 初始化 `Camera` 类的新实例。 |
| [Camera](camera/#constructor_1)(ProjectionType) | 初始化 `Camera` 类的新实例。 |
| [Camera](camera/#constructor_2)(string) | 初始化 `Camera` 类的新实例。 |
| [Camera](camera/#constructor_3)(string, ProjectionType) | 初始化 `Camera` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApertureMode](../../aspose.threed.entities/camera/aperturemode/) { get; set; } | 获取或设置相机的光圈模式 |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | 获取或设置视锥体的宽高比 |
| [AspectRatio](../../aspose.threed.entities/camera/aspectratio/) { get; set; } | 获取或设置视平面的宽高比。 |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | 获取或设置相机所看的方向。对此属性的更改还会影响[`LookAt`](../frustum/lookat/)和[`Target`](../frustum/target/)。 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 获取或设置在导出时是否排除此实体。 |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | 获取或设置视锥体的远平面距离。 |
| [FieldOfView](../../aspose.threed.entities/camera/fieldofview/) { get; set; } | 获取或设置相机的视场角（以度为单位），仅在 ApertureMode 为 Horizontal 或 Vertical 时使用此属性 |
| [FieldOfViewX](../../aspose.threed.entities/camera/fieldofviewx/) { get; set; } | 获取或设置相机的水平视场角（以度为单位），仅在 ApertureMode 为 HorizAndVert 时使用此属性 |
| [FieldOfViewY](../../aspose.threed.entities/camera/fieldofviewy/) { get; set; } | 获取或设置相机的垂直视场角（以度为单位），仅在 ApertureMode 为 HorizAndVert 时使用此属性 |
| [Height](../../aspose.threed.entities/camera/height/) { get; set; } | 获取或设置以英寸为单位的视平面高度 |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | 获取或设置相机所看的感兴趣位置。 |
| [Magnification](../../aspose.threed.entities/camera/magnification/) { get; set; } | 获取或设置正交相机使用的放大倍率 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | 获取或设置视锥体的近平面距离。 |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | 获取或设置视锥体在正交投影时的高度。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化 |
| [ProjectionType](../../aspose.threed.entities/camera/projectiontype/) { get; set; } | 获取或设置相机的投影类型。默认使用透视投影。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | 获取或设置视锥体的方向模式。此属性仅在[`Target`](../frustum/target/)为 null 时有效。如果值为 FixedTarget，则方向始终由属性[`LookAt`](../frustum/lookat/)计算；否则[`LookAt`](../frustum/lookat/)始终由[`Direction`](../frustum/direction/)计算。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 获取此对象所属的场景 |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | 获取或设置相机所看的目标。如果用户支持此属性，它应优先于[`LookAt`](../frustum/lookat/)属性。 |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | 获取或设置相机的上方向 |
| [Width](../../aspose.threed.entities/camera/width/) { get; set; } | 获取或设置以英寸为单位的视平面宽度 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 获取当前实体在其对象空间坐标系中的包围盒。 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 获取在渲染器中注册的实体渲染器的键 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [MoveForward](../../aspose.threed.entities/camera/moveforward/)(double) | 将相机向前移动，朝向其方向或目标。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


