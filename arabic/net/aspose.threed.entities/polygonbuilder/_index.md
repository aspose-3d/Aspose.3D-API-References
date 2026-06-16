---
title: "فئة PolygonBuilder"
second_title: "مرجع Aspose.3D for .NET API"
description: "Aspose.ThreeD.Entities.PolygonBuilder فئة. فئة مساعدة لبناء مضلع لـ Mesh"
type: docs
weight: 610
url: /ar/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

فئة مساعدة لبناء مضلع لـ [`Mesh`](../mesh/)

```csharp
public sealed class PolygonBuilder
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | يُنشئ مثلاً جديداً من الفئة `PolygonBuilder`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | يضيف فهرس رأس إلى المضلع |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | يبدأ بإضافة مضلع جديد |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | يُنهي إنشاء المضلع |

## أمثلة

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

يساوي :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

إذا كانت جميع الفهارس جاهزة للاستخدام، يُفضَّل [`CreatePolygon`](../mesh/createpolygon/)، وإلا فإن `PolygonBuilder` سيكون خيارًا أفضل.

### انظر أيضًا

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


