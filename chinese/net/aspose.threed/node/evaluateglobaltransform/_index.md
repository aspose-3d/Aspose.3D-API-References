---
title: "Node.EvaluateGlobalTransform"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。评估全局变换是否包含几何变换"
type: docs
weight: 180
url: /zh/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

评估全局变换，是否包含几何变换。

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| withGeometricTransform | Boolean | 是否需要几何变换。 |

### 返回值

全局变换矩阵。

## 示例

以下代码展示了如何读取节点的全局变换矩阵。

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//将盒子放置在 (10, 0, 0) 处
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### 另请参见

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


