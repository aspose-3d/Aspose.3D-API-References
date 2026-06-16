---
title: "Mesh.Triangulate"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Mesh. تُعيد شبكة مُمثلّثة"
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

الشبكة الحالية إذا كانت مُمثلّثة بالفعل، وإلا سيتم حساب وإرجاع شبكة مُمثلّثة جديدة

## أمثلة

الكود التالي يوضح كيفية تقسيم mesh إلى مثلثات:

```csharp
//شبكة plane mesh لديها مضلع واحد فقط مع 4 control points
var mesh = (new Plane()).ToMesh();
//بعد التقسيم إلى مثلثات، سيصبح مستطيل mesh الجديد مكوّنًا من مثلثين.
var triangulated = mesh.Triangulate();
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


