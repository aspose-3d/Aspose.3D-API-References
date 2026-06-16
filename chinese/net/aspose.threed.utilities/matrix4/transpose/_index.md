---
title: "Matrix4.Transpose"
second_title: "Aspose.3D for .NET API 参考"
description: "Matrix4 方法。转置此实例"
type: docs
weight: 310
url: /zh/net/aspose.threed.utilities/matrix4/transpose/
---
## Matrix4.Transpose method

转置此实例。

```csharp
public Matrix4 Transpose()
```

### 返回值

转置矩阵。

## 示例

以下代码展示了如何转置矩阵

```csharp
var t = Matrix4.Translate(0, 10, 9);
var mat = t.Transpose();
Console.WriteLine($"Transposed Matrix: {mat}");
```

### 另请参见

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


