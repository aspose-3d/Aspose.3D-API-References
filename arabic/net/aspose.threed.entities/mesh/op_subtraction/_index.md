---
title: "Mesh.op_Subtraction"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Mesh. احسب الفرق بين شبكتين"
type: docs
weight: 150
url: /ar/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

احسب الفرق بين شبكتين

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| a | Mesh | الـ mesh الأول |
| b | Mesh | الـ mesh الثاني |

### قيمة الإرجاع

نتيجة الشبكة

## أمثلة

الكود التالي يوضح كيفية حساب الفرق بين شبكتين:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


