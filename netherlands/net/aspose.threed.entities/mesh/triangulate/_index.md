---
title: "Mesh.Triangulate"
second_title: "Aspose.3D voor .NET API-referentie"
description: "Mesh‑methode. Retourneer getrianguleerde mesh"
type: docs
weight: 120
url: /nl/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Retourneer getrianguleerde mesh

```csharp
public Mesh Triangulate()
```

### Retourwaarde

Huidige mesh als de huidige mesh al getrianguleerd is, anders wordt een nieuwe getrianguleerde mesh berekend en geretourneerd

## Voorbeelden

De volgende code toont hoe een mesh te trianguleren:

```csharp
//De vlakke mesh heeft slechts één polygoon met 4 controlepunten
var mesh = (new Plane()).ToMesh();
//Na triangulatie zal de rechthoek van de nieuwe mesh uit 2 driehoeken bestaan.
var triangulated = mesh.Triangulate();
```

### Zie ook

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


