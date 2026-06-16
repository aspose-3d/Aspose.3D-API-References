---
title: "Matrix4.Scale"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Matrix4. ينشئ مصفوفة تقوم بالتحجيم على طول المحور x والمحور y والمحور z"
type: docs
weight: 50
url: /ar/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z.

```csharp
public static Matrix4 Scale(Vector3 s)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| s | Vector3 | تطبيقات التحجيم تنطبق على المحور x، والمحور y، والمحور z |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية التحجيم.

```csharp
var t = Matrix4.Scale(new Vector3(10, 10, 10));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double) {#scale_1}

ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z.

```csharp
public static Matrix4 Scale(double s)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| s | Double | تطبيقات التحجيم تنطبق على جميع المحاور |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية التحجيم.

```csharp
var t = Matrix4.Scale(10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z.

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| sx | Double | تطبيق مقياس المصانع على المحور x |
| sy | Double | تطبيق مقياس المصانع على المحور y |
| sz | Double | تطبيق مقياس المصانع على المحور z |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية التحجيم.

```csharp
var t = Matrix4.Scale(10, 20, 10);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


