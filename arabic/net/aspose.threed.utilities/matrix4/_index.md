---
title: "بنية Matrix4"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Utilities.Matrix4 بنية. تنفيذ مصفوفة 4x4"
type: docs
weight: 2790
url: /ar/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

تنفيذ مصفوفة 4x4.

```csharp
public struct Matrix4
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | يُهيئ نسخة جديدة من بنية `Matrix4`. |
| [Matrix4](matrix4/#constructor)(FMatrix4) | أنشئ `Matrix4` من نسخة [`FMatrix4`](../fmatrix4/) instance |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | يبني المصفوفة من 4 صفوف. |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | يُهيئ نسخة جديدة من بنية `Matrix4`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | يحصل على مصفوفة الهوية. |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | يسترجع محدد المصفوفة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | إنشاء مصفوفة دوران من رباعية |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | إنشاء مصفوفة دوران بزاوية الدوران والمحور |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | إنشاء مصفوفة دوران من زاوية أويلر |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | إنشاء مصفوفة دوران من زاوية أويلر |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z. |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | ينشئ مصفوفة تقوم بالترجمة على طول المحور x، والمحور y، والمحور z |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | ينشئ مصفوفة تقوم بالترجمة على طول المحور x، والمحور y، والمحور z |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | يجمع المصفوفتين |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | يعكس هذا الكائن. |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | يعيد تطبيع هذا الكائن. |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | يُهيئ المصفوفة بالترجمة/الدوران/التحجيم |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | يحوّل المصفوفة إلى مصفوفة. |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | يعيد سلسلة تمثل الـ `Matrix4` الحالي. |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | يقلب هذه النسخة. |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | اضرب المصفوفتين (4 عمليات) |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | ال m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | ال m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | ال m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | ال m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | ال m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | ال m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | ال m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | ال m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | ال m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | ال m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | ال m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | ال m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | ال m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | ال m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | ال m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | ال m33. |

## أمثلة

```csharp
Matrix4 mat = Matrix4.RotateFromEuler(90, 0, 0);
Matrix4 mat2 = Matrix4.Translate(0, 10, -50);
Matrix4 transform = mat2 * mat;
Vector4 pos = new Vector4(10, 9, 0, 1);
Vector4 transformed = transform * pos;

```

### انظر أيضًا

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


