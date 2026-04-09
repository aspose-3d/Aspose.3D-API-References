---
title: BoundingBox.Merge
second_title: مرجع API Aspose.3D لـ .NET
description: BoundingBox method. Merge current bounding box with given point
type: docs
weight: 130
url: /ar/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

دمج مربع الحد الحالي مع النقطة المعطاة

```csharp
public void Merge(Vector4 pt)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | Vector4 | النقطة التي سيتم دمجها في صندوق الاحتواء |

## Examples

The following code shows how to merge a point to bounding box.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

دمج مربع الحد الحالي مع النقطة المعطاة

```csharp
public void Merge(Vector3 pt)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | Vector3 | النقطة التي سيتم دمجها في صندوق الاحتواء |

## Examples

The following code shows how to merge a point to bounding box.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

دمج مربع الحد الحالي مع النقطة المعطاة

```csharp
public void Merge(double x, double y, double z)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | النقطة التي سيتم دمجها في صندوق الاحتواء |
| y | Double | النقطة التي سيتم دمجها في صندوق الاحتواء |
| z | Double | النقطة التي سيتم دمجها في صندوق الاحتواء |

## Examples

The following code shows how to merge a point to bounding box.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

يدمج الصندوق الجديد في صندوق الحدود الحالي.

```csharp
public void Merge(BoundingBox bb)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| bb | BoundingBox | صندوق الحدود للدمج |

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


