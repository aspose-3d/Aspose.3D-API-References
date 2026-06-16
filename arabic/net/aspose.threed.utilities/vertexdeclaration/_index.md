---
title: "الفئة VertexDeclaration"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Utilities.VertexDeclaration. إعلان بنية رؤوس مخصصة"
type: docs
weight: 2910
url: /ar/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

إعلان بنية القمة المعرفة مخصصًا.

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | يحصل على عدد جميع الحقول المعرفة في هذا `VertexDeclaration` |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | سيتم إغلاق `VertexDeclaration` عندما يُستخدم بواسطة [`TriMesh`](../../aspose.threed.entities/trimesh-1/) أو [`TriMesh`](../../aspose.threed.entities/trimesh/)، ولا يُسمح بمزيد من التعديلات. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | حجم بنية الرأس بالبايت. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | أنشئ `VertexDeclaration` بناءً على تخطيط [`Geometry`](../../aspose.threed.entities/geometry/). |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | أضف حقل رأس جديد |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | امسح جميع الحقول. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | يقارن هذه الحالة مع كائن محدد ويعيد إشارة إلى قيمهما النسبية. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | يحدد ما إذا كان هذا الكائن والكيان المحدد، الذي يجب أن يكون أيضاً كائن `VertexDeclaration`، لهما نفس القيمة. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | يحصل على مُعدِّد للتجول عبر جميع حقول الرأس في هذا الكائن. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | يعيد رمز التجزئة لهذا النص. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | تمثيل نصي لـ `VertexDeclaration` |

### انظر أيضًا

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


