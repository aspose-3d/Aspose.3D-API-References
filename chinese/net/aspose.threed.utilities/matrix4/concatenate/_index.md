---
title: "Matrix4.Concatenate"
second_title: "Aspose.3D for .NET API 参考"
description: "Matrix4 方法。连接两个矩阵"
type: docs
weight: 240
url: /zh/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

连接两个矩阵

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### 返回值

新的 matrix4

## 示例

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### 另请参见

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


