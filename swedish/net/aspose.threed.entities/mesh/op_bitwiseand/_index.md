---
title: "Mesh.op_BitwiseAnd"
second_title: "Aspose.3D för .NET API‑referens"
description: "Mesh-metod. Beräkna skärningen av två meshar"
type: docs
weight: 130
url: /sv/net/aspose.threed.entities/mesh/op_bitwiseand/
---
## Mesh BitwiseAnd operator

Beräkna skärningen av två meshar

```csharp
public static Mesh operator &(Mesh a, Mesh b)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | Mesh | Första mesh |
| b | Mesh | Andra mesh |

### Returvärde

Resultat mesh

## Exempel

Följande kod visar hur man beräknar skillnaden mellan två meshar:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 & box2;
```

### Se även

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


