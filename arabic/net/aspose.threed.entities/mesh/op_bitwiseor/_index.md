---
title: Mesh.op_BitwiseOr
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة Mesh. حساب اتحاد شبكتين
type: docs
weight: 140
url: /ar/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

احسب اتحاد شبكتين

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| a | شبكة | الشبكة الأولى |
| b | شبكة | الشبكة الثانية |

### قيمة الإرجاع

شبكة النتيجة

## Examples

يعرض الكود التالي كيفية دمج نموذجين ثلاثيين إلى نموذج ثلاثي واحد:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


