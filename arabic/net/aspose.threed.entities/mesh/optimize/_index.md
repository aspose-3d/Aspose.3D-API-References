---
title: Mesh.Optimize
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة Mesh. تحسين استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة
type: docs
weight: 100
url: /ar/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

```csharp
public Mesh Optimize(bool vertexElements)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexElements | Boolean | تحسين بيانات عناصر الرأس المكررة |

### قيمة الإرجاع

مثيل شبكة جديد باستخدام ذاكرة مدمجة

## Examples

يعرض الكود التالي كيفية إزالة نقاط التحكم المكررة من شبكة غير مُحسّنة:

```csharp
//Sphere.ToMesh يولد 117 نقطة تحكم
var mesh = (new Sphere()).ToMesh();
//بعد التحسين، لا يتبقّى سوى 86 نقطة تحكم، كما يتم إعادة تعيين فهارس المضلعات.
var optimized = mesh.Optimize(true);
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexElements | Boolean | تحسين بيانات عناصر الرأس المكررة |
| toleranceControlPoint | Single | التحمل لنقطة التحكم، القيمة الافتراضية هي 1e-9 |
| toleranceNormal | Single | التحمل للمتجه العادي/المماس/المتجه الثانوي، القيمة الافتراضية هي 1e-9 |
| toleranceUV | Single | التحمل للإحداثيات uv، القيمة الافتراضية هي 1e-9 |

### قيمة الإرجاع

مثيل شبكة جديد باستخدام ذاكرة مدمجة

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


