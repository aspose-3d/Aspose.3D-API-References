---
title: "Matrix4.Translate"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Matrix4. تنشئ مصفوفة تُترجم على طول المحور x والمحور y والمحور z"
type: docs
weight: 60
url: /ar/net/aspose.threed.utilities/matrix4/translate/
---
## Translate(Vector3) {#translate}

ينشئ مصفوفة تقوم بالترجمة على طول المحور x، والمحور y، والمحور z

```csharp
public static Matrix4 Translate(Vector3 t)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| t | Vector3 | إزاحة الترجمة |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية الترجمة.

```csharp
var t = Matrix4.Translate(new Vector3(10, 0, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Translate(double, double, double) {#translate_1}

ينشئ مصفوفة تقوم بالترجمة على طول المحور x، والمحور y، والمحور z

```csharp
public static Matrix4 Translate(double tx, double ty, double tz)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| tx | Double | إزاحة إحداثي X |
| ty | Double | إزاحة إحداثي Y |
| tz | Double | إزاحة إحداثي Z |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية الترجمة.

```csharp
var t = Matrix4.Translate(10, 0, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


