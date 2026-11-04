---
title: "Mesh.op_Subtraction"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Mesh-methode. Bereken het verschil van twee meshes"
type: docs
weight: 150
url: /nl/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

Bereken het verschil van twee meshes

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | Mesh | Eerste mesh |
| b | Mesh | Tweede mesh |

### Retourwaarde

Resultaat mesh

## Voorbeelden

De volgende code toont hoe je het verschil van twee meshes kunt berekenen:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### Zie ook

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


