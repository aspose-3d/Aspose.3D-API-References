---
title: "Mesh.op_BitwiseOr"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Mesh. حساب اتحاد meshين"
type: docs
weight: 140
url: /ar/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

احسب اتحاد شبكتين

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| a | Mesh | الـ mesh الأول |
| b | Mesh | الـ mesh الثاني |

### قيمة الإرجاع

نتيجة الشبكة

## أمثلة

الكود التالي يوضح كيفية دمج شبكتين في شبكة واحدة:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


