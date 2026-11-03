---
title: "क्लास PolygonBuilder"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.PolygonBuilder क्लास। Mesh के लिए बहुभुज बनाने के लिए एक सहायक क्लास"
type: docs
weight: 610
url: /hi/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

[`Mesh`](../mesh/) के लिए बहुभुज बनाने के लिए एक सहायक क्लास।

```csharp
public sealed class PolygonBuilder
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | `PolygonBuilder` क्लास का एक नया उदाहरण प्रारंभ करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | बहुभुज में एक वर्टेक्स इंडेक्स जोड़ता है |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | एक नया बहुभुज जोड़ना शुरू करता है |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | बहुभुज निर्माण समाप्त करता है |

## उदाहरण

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

के बराबर :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

यदि सभी इंडेक्स उपयोग के लिए तैयार हैं, तो [`CreatePolygon`](../mesh/createpolygon/) को प्राथमिकता दी जाती है, अन्यथा `PolygonBuilder` बेहतर विकल्प होगा।

### देखें भी

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


