---
title: "تعداد MappingMode"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.MappingMode تعداد. يحدد كيفية ربط العنصر بسطح. الـ MappingMode يحدد كيفية ربط VertexElement بسطح الهندسة."
type: docs
weight: 500
url: /ar/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

يحدد كيفية ربط العنصر بسطح. الـ `MappingMode` يحدد كيفية ربط [`VertexElement`](../vertexelement/) بسطح الهندسة.

```csharp
public enum MappingMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ControlPoint | `0` | كل بيانات يتم ربطها بنقطة التحكم في الهندسة. |
| PolygonVertex | `1` | البيانات يتم ربطها برأس المضلع عندما تكون نقطة التحكم مشتركة بين عدة مضلعات، وتتم ربط البيانات كـ PolygonVertex، فإن نقطة التحكم كقمة مضلع مختلفة ستحصل على بياناتها الخاصة. |
| Polygon | `2` | يتم ربط البيانات بالمضلع. كل قمة مضلع تشترك في نفس البيانات عندما يكون وضع الربط هو Polygon. |
| Edge | `3` | يتم ربط البيانات بالحافة. كل نقطة نهاية للحافة تشترك في نفس البيانات عندما يكون وضع الربط هو Edge. |
| AllSame | `4` | بيانات واحدة يتم ربطها بالسطح بالكامل. أيًا كانت البيانات التي تُفسَّر كنقطة تحكم/قمة مضلع/نقاط نهاية حافة، فإن البيانات تكون دائمًا نفسها كما تم تعريفها بواسطة AllSame. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


