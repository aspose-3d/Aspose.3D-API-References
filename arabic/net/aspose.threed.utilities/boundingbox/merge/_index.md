---
title: "BoundingBox.Merge"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة BoundingBox. دمج مربع الحدود الحالي مع النقطة المعطاة"
type: docs
weight: 130
url: /ar/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

دمج صندوق الحدود الحالي مع النقطة المحددة.

```csharp
public void Merge(Vector4 pt)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pt | Vector4 | النقطة التي سيتم دمجها في مربع الحدود |

## أمثلة

الكود التالي يوضح كيفية دمج نقطة إلى مربع الحدود.

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

دمج صندوق الحدود الحالي مع النقطة المحددة.

```csharp
public void Merge(Vector3 pt)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| pt | Vector3 | النقطة التي سيتم دمجها في مربع الحدود |

## أمثلة

الكود التالي يوضح كيفية دمج نقطة إلى مربع الحدود.

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

دمج صندوق الحدود الحالي مع النقطة المحددة.

```csharp
public void Merge(double x, double y, double z)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | مضاعف | النقطة التي سيتم دمجها في مربع الحدود |
| y | مضاعف | النقطة التي سيتم دمجها في مربع الحدود |
| z | مضاعف | النقطة التي سيتم دمجها في مربع الحدود |

## أمثلة

الكود التالي يوضح كيفية دمج نقطة إلى مربع الحدود.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| bb | BoundingBox | صندوق الحدود للدمج |

### انظر أيضًا

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


