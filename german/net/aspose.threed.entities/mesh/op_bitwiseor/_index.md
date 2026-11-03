---
title: "Mesh.op_BitwiseOr"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Mesh-Methode. Berechnet die Vereinigung zweier Meshes"
type: docs
weight: 140
url: /de/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Berechnet die Vereinigung zweier Meshes

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | Mesh | Erstes Mesh |
| b | Mesh | Zweites Mesh |

### Rückgabewert

Ergebnis-Mesh

## Beispiele

Der folgende Code zeigt, wie man zwei Meshes zu einem Mesh vereinigt:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


