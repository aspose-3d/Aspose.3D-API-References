---
title: "Mesh.op_BitwiseOr"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Mesh-methode. Bereken de unie van twee meshes"
type: docs
weight: 140
url: /nl/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Bereken de unie van twee meshes

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | Mesh | Eerste mesh |
| b | Mesh | Tweede mesh |

### Retourwaarde

Resultaat mesh

## Voorbeelden

De volgende code laat zien hoe twee meshes te combineren tot één mesh:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Zie ook

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


