---
title: 类 GlobalTransform
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.GlobalTransform 类。全局变换类似于 Transform，但它是不可变的，因为它表示最终评估的变换。评估全局变换时使用右手坐标系。
type: docs
weight: 1560
url: /zh/net/aspose.threed/globaltransform/
---
## GlobalTransform class

全局变换类似于 [`Transform`](../transform/)，但它是不可变的，因为它表示最终评估的变换。评估全局变换时使用右手坐标系。

```csharp
public class GlobalTransform
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | 获取以欧拉角表示的旋转，单位为度 |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | 获取以四元数表示的旋转。 |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | 获取缩放 |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | 获取变换矩阵。 |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | 获取平移 |

## 示例

以下代码演示如何读取节点的全局变换

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//将盒子放置在 (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### 另请参见

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


