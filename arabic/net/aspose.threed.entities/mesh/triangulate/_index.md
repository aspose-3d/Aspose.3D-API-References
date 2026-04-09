---
title: Mesh.Triangulate
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة Mesh. إرجاع شبكة مُمثلثة
type: docs
weight: 120
url: /ar/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

إرجاع شبكة مُثلثة

```csharp
public Mesh Triangulate()
```

### قيمة الإرجاع

الشبكة الحالية إذا كانت الشبكة الحالية مُمثلثة بالفعل، وإلا سيتم حساب شبكة مُمثلثة جديدة وإرجاعها

## Examples

يعرض الكود التالي كيفية تمثيل شبكة:

```csharp
//شبكة المستوى تحتوي على مضلع واحد فقط مع 4 نقاط تحكم
var mesh = (new Plane()).ToMesh();
//بعد التمثيل، سيصبح مستطيل الشبكة الجديدة مكوّنًا من مثلثين.
var triangulated = mesh.Triangulate();
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


