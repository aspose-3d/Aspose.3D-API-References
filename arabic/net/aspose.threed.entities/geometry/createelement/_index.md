---
title: "Geometry.CreateElement"
second_title: "مرجع Aspose.3D for .NET API"
description: "Geometry method. تنشئ عنصر رأس بالنوع المحدد وتضيفه إلى الشكل"
type: docs
weight: 90
url: /ar/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة.

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| type | VertexElementType | نوع عنصر الرأس |

### قيمة الإرجاع

تم إنشاء العنصر.

## ملاحظات

إذا كان النوع UV، سيتم إنشاء [`VertexElementUV`](../../vertexelementuv/) بنوع تخطيط النسيج إلى Diffuse.

### انظر أيضًا

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة.

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| type | VertexElementType | نوع عنصر الرأس |
| mappingMode | MappingMode | وضع التخطيط الافتراضي |
| referenceMode | ReferenceMode | وضع المرجع الافتراضي |

### قيمة الإرجاع

تم إنشاء العنصر.

## ملاحظات

إذا كان النوع UV، سيتم إنشاء [`VertexElementUV`](../../vertexelementuv/) بنوع تخطيط النسيج إلى Diffuse.

### انظر أيضًا

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)


