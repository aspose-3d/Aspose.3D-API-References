---
title: "Matrix4.Concatenate"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Matrix4. تجمع المصفوفتين"
type: docs
weight: 240
url: /ar/net/aspose.threed.utilities/matrix4/concatenate/
---
## Matrix4.Concatenate method

يجمع المصفوفتين

```csharp
public Matrix4 Concatenate(Matrix4 m2)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

### قيمة الإرجاع

جديدة matrix4

## أمثلة

```csharp
var t = Matrix4.Translate(0, 10, 9);
var s = Matrix4.Scale(10, 10, 10);
var transform = t.Concatenate(s);
var pos = new Vector3(10, 0, -1);
var transformed = transform * pos;
```

### انظر أيضًا

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)


