---
title: "Mesh.Optimize"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Mesh. تحسين استخدام الذاكرة للـ meshs عن طريق إزالة duplicated control points"
type: docs
weight: 100
url: /ar/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

```csharp
public Mesh Optimize(bool vertexElements)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vertexElements | Boolean | تحسين بيانات عناصر الرؤوس المكررة |

### قيمة الإرجاع

مثيل mesh جديد باستخدام ذاكرة مضغوطة

## أمثلة

الكود التالي يوضح كيفية إزالة duplicated control points من mesh غير محسّن:

```csharp
//Sphere.ToMesh يولد 117 control points
var mesh = (new Sphere()).ToMesh();
//بعد التحسين، لا يتبقّى سوى 86 control points، كما تم إعادة تعيين مؤشرات المضلع.
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

| معامل | النوع | الوصف |
| --- | --- | --- |
| vertexElements | Boolean | تحسين بيانات عناصر الرؤوس المكررة |
| toleranceControlPoint | Single | التحمل لنقطة التحكم، القيمة الافتراضية هي 1e-9 |
| toleranceNormal | Single | التحمل للـ normal/tangent/binormal، القيمة الافتراضية هي 1e-9 |
| toleranceUV | Single | التحمل للـ uv، القيمة الافتراضية هي 1e-9 |

### قيمة الإرجاع

مثيل mesh جديد باستخدام ذاكرة مضغوطة

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


