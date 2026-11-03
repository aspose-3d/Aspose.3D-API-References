---
title: "Mesh.Optimize"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Mesh. تحسين استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة"
type: docs
weight: 100
url: /ar/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

تحسين استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

```csharp
public Mesh Optimize(bool vertexElements)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vertexElements | Boolean | تحسين بيانات عناصر الرؤوس المكررة |

### قيمة الإرجاع

مثيل شبكة جديد باستخدام ذاكرة مدمجة

## أمثلة

الكود التالي يوضح كيفية إزالة نقاط التحكم المكررة من شبكة غير مُحسّنة:

```csharp
//Sphere.ToMesh يولد 117 نقطة تحكم
var mesh = (new Sphere()).ToMesh();
//بعد التحسين، لا توجد سوى 86 نقطة تحكم، كما تم إعادة تعيين مؤشرات المضلعات.
var optimized = mesh.Optimize(true);
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

تحسين استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vertexElements | Boolean | تحسين بيانات عناصر الرؤوس المكررة |
| toleranceControlPoint | Single | التحمل لنقطة التحكم، القيمة الافتراضية هي 1e-9 |
| toleranceNormal | Single | التحمل للمتجه العادي/المماس/الثنائي القاعدة، القيمة الافتراضية هي 1e-9 |
| toleranceUV | Single | التحمل للـ uv، القيمة الافتراضية هي 1e-9 |

### قيمة الإرجاع

مثيل شبكة جديد باستخدام ذاكرة مدمجة

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


