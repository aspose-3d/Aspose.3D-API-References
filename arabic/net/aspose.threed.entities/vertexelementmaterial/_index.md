---
title: "فئة VertexElementMaterial"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.Entities.VertexElementMaterial. تُعرّف فهرس المادة للمكونات المحددة. يمكن للعقدة أن تحتوي على مواد متعددة، يُستخدم VertexElementMaterial لتصيير أجزاء مختلفة من الهندسة بمواد مختلفة"
type: docs
weight: 880
url: /ar/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

يُعرّف فهرس المادة للمكونات المحددة. يمكن للعقدة أن تحتوي على مواد متعددة، يُستخدم `VertexElementMaterial` لتصيير أجزاء مختلفة من الهندسة بمواد مختلفة.

```csharp
public class VertexElementMaterial : VertexElement
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | يُهيئ مثيلاً جديدًا من فئة `VertexElementMaterial`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | يحصل على بيانات الفهارس |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | يحصل أو يضبط كيفية تعيين العنصر. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | يحصل أو يضبط كيفية الإشارة إلى العنصر. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | يحصل على نوع الـ [`VertexElement`](../vertexelement/) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | يزيل جميع العناصر من المصفوفات المباشرة ومصفوفات الفهارس. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | تحميل الفهارس |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | تمثيل نصي لعنصر الرأس. |

## أمثلة

الكود التالي يوضح كيفية تعيين مادة مختلفة لوجه مختلف من الصندوق.

```csharp
// إنشاء شبكة لصندوق (الصندوق يتكون من 6 مستويات)
Mesh box = (new Box()).ToMesh();
// إنشاء عنصر مادة على هذه الشبكة
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// وتحديد فهرس مادة مختلف لكل مستوى
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### انظر أيضًا

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


