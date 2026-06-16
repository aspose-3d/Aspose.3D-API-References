---
title: "Matrix4.RotateFromEuler"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Matrix4. إنشاء مصفوفة دوران من زاوية أويلر"
type: docs
weight: 40
url: /ar/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

إنشاء مصفوفة دوران من زاوية أويلر

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| eul | Vector3 | دوران بالراديان |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية الدوران.

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

إنشاء مصفوفة دوران من زاوية أويلر

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rx | Double | دوران حول محور x بالراديان |
| ry | Double | دوران حول محور y بالراديان |
| rz | Double | دوران حول محور z بالراديان |

## أمثلة

الكود التالي يوضح كيفية إنشاء مصفوفة لعملية الدوران.

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### انظر أيضًا

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


