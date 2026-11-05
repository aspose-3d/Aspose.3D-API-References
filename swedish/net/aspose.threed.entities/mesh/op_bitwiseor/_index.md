---
title: "Mesh.op_BitwiseOr"
second_title: "Aspose.3D för .NET API‑referens"
description: "Mesh metod. Beräkna unionen av två meshar"
type: docs
weight: 140
url: /sv/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Beräkna unionen av två meshar

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | Mesh | Första mesh |
| b | Mesh | Andra mesh |

### Returvärde

Resultat mesh

## Exempel

Följande kod visar hur man förenar två meshar till en mesh:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Se även

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


