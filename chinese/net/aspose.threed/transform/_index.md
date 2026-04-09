---
title: 类 Transform
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Transform 类。Transform 包含允许以最小成本访问对象的平移/缩放/旋转或变换矩阵的信息，这用于局部变换
type: docs
weight: 2650
url: /zh/net/aspose.threed/transform/
---
## Transform class

变换包含允许以最低成本访问对象的平移/缩放/旋转或变换矩阵的信息，这用于局部变换。

```csharp
public class Transform : A3DObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | 获取或设置以欧拉角表示的旋转，单位为度 |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | 获取或设置几何欧拉旋转（单位为度）。几何变换仅影响附加的实体，而不影响子节点。当导出到不支持几何变换的文件类型时，它将合并为局部变换。 |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | 获取或设置几何缩放。几何变换仅影响附加的实体，而不影响子节点。当导出到不支持几何变换的文件类型时，它将合并为局部变换。 |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | 获取或设置几何平移。几何变换仅影响附加的实体，而不影响子节点。当导出到不支持几何变换的文件类型时，它将合并为局部变换。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | 获取或设置后置旋转，单位为度 |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | 获取或设置前置旋转，单位为度 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | 获取或设置以四元数表示的旋转。 |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | 获取或设置旋转偏移 |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | 获取或设置旋转枢轴 |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | 获取或设置缩放 |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | 获取或设置缩放偏移 |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | 获取或设置缩放枢轴 |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | 获取或设置变换矩阵。 |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | 获取或设置平移 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称标识的指定属性 |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | 设置当前变换的欧拉角（单位为度）。 |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | 设置几何欧拉旋转（以度为单位）。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出为不支持该功能的文件类型时，它将合并为局部变换。 |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | 设置几何缩放。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出为不支持该功能的文件类型时，它将合并为局部变换。 |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | 设置几何平移。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出为不支持该功能的文件类型时，它将合并为局部变换。 |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | 设置后置旋转（单位为度） |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | 设置前置旋转（单位为度） |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | 设置当前变换的旋转（作为四元数分量）。 |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | 设置当前变换的比例。 |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | 设置当前变换的平移。 |

## 示例

以下代码展示了如何更改节点的变换：

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//将盒子放置在 (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### 另请参见

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


