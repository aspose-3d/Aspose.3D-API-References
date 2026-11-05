---
title: "Mesh.Triangulate"
second_title: "Aspose.3D för .NET API‑referens"
description: "Mesh metod. Returnera triangulerad mesh"
type: docs
weight: 120
url: /sv/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Returnera triangulerad mesh

```csharp
public Mesh Triangulate()
```

### Returvärde

Aktuell mesh om den aktuella meshen redan är triangulerad, annars beräknas en ny triangulerad mesh och returneras

## Exempel

Följande kod visar hur man triangulerar en mesh:

```csharp
//Planmeshen har bara en polygon med 4 kontrollpunkter
var mesh = (new Plane()).ToMesh();
//Efter triangulering blir den nya meshens rektangel två trianglar.
var triangulated = mesh.Triangulate();
```

### Se även

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


