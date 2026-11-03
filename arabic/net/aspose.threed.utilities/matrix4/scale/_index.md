---
title: "Matrix4.Scale"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "Matrix4 طريقة. ينشئ مصفوفة تقوم بالتوسيع على طول xaxis و yaxis و zaxis"
type: docs
weight: 50
url: /ar/net/aspose.threed.utilities/matrix4/scale/
---
## Scale(Vector3) {#scale}

ينشئ مصفوفة تقوم بالتوسيع على طول x-axis، y-axis و z-axis.

```csharp
public static Matrix4 Scale(Vector3 s)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| s | Vector3 | تطبيقات التحجيم تنطبق على x-axis، y-axis و z-axis |

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

ينشئ مصفوفة تقوم بالتوسيع على طول x-axis، y-axis و z-axis.

```csharp
public static Matrix4 Scale(double s)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| s | مضاعف | تطبيقات التحجيم تنطبق على جميع المحاور |

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

ينشئ مصفوفة تقوم بالتوسيع على طول x-axis، y-axis و z-axis.

```csharp
public static Matrix4 Scale(double sx, double sy, double sz)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| sx | مضاعف | تطبيقات التحجيم تنطبق على x-axis |
| sy | مضاعف | تطبيقات التحجيم تنطبق على y-axis |
| sz | مضاعف | تطبيقات التحجيم تنطبق على z-axis |

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


