---
title: "Mesh.op_BitwiseAnd"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Mesh-Methode. Berechnet die Schnittmenge zweier Meshes"
type: docs
weight: 130
url: /de/net/aspose.threed.entities/mesh/op_bitwiseand/
---
## Mesh BitwiseAnd operator

Berechnet die Schnittmenge zweier Meshes

```csharp
public static Mesh operator &(Mesh a, Mesh b)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | Mesh | Erstes Mesh |
| b | Mesh | Zweites Mesh |

### Rückgabewert

Ergebnis-Mesh

## Beispiele

Der folgende Code zeigt, wie man die Differenz zweier Meshes berechnet:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 & box2;
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


