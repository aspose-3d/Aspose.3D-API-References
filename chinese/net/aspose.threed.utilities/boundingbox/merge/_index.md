---
title: BoundingBox.Merge
second_title: Aspose.3D for .NET API 参考手册
description: BoundingBox 方法。将当前包围盒与给定点合并
type: docs
weight: 130
url: /zh/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

将当前边界框与给定点合并

```csharp
public void Merge(Vector4 pt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | Vector4 | 要合并到边界框的点 |

## 示例

以下代码演示如何将点合并到包围盒中。

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### 另请参见

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

将当前边界框与给定点合并

```csharp
public void Merge(Vector3 pt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | Vector3 | 要合并到边界框的点 |

## 示例

以下代码演示如何将点合并到包围盒中。

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### 另请参见

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

将当前边界框与给定点合并

```csharp
public void Merge(double x, double y, double z)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | 要合并到边界框的点 |
| y | Double | 要合并到边界框的点 |
| z | Double | 要合并到边界框的点 |

## 示例

以下代码演示如何将点合并到包围盒中。

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### 另请参见

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

将新盒合并到当前包围盒中。

```csharp
public void Merge(BoundingBox bb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bb | BoundingBox | 要合并的包围盒 |

### 另请参见

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


