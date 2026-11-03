---
title: "Mesh.Triangulate"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Mesh. إرجاع شبكة مُثلثة"
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

الشبكة الحالية إذا كانت الشبكة الحالية مُمثلّثة بالفعل، وإلا سيتم حساب شبكة مُمثلّثة جديدة وإرجاعها

## أمثلة

الكود التالي يوضح كيفية تمثيل شبكة:

```csharp
//شبكة السطح تحتوي على مضلع واحد فقط مع 4 نقاط تحكم
var mesh = (new Plane()).ToMesh();
//بعد التمثيل، سيتحول مستطيل الشبكة الجديدة إلى مثلثين.
var triangulated = mesh.Triangulate();
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


