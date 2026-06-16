---
title: "TransformBuilder.Scale"
second_title: "Aspose.3D for .NET API 参考"
description: "TransformBuilder 方法. 链式添加一个缩放变换矩阵，其中组件按 s 缩放"
type: docs
weight: 140
url: /zh/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

将缩放变换矩阵与按 s 缩放的组件链接

```csharp
public TransformBuilder Scale(double s)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | Double |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

链接缩放变换矩阵

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

链接缩放变换

```csharp
public TransformBuilder Scale(Vector3 s)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | Vector3 |  |

## 示例

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### 另请参见

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)


