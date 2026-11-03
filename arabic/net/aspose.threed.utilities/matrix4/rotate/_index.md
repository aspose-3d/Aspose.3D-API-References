---
title: "Matrix4.Rotate"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "Matrix4 طريقة. إنشاء مصفوفة دوران بواسطة زاوية الدوران والمحور"
type: docs
weight: 30
url: /ar/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

إنشاء مصفوفة دوران بواسطة زاوية الدوران والمحور

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| زاوية | مضاعف | زاوية الدوران بالراديان |
| محور | Vector3 | محور الدوران |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية الدوران.

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

إنشاء مصفوفة دوران من كواتيرنيون

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| q | كواتيرنيون | كواتيرنيون الدوران |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية الدوران.

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


