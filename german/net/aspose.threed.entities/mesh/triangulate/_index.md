---
title: "Mesh.Triangulate"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Mesh-Methode. Gibt ein trianguliertes Mesh zurück"
type: docs
weight: 120
url: /de/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Gibt ein trianguliertes Mesh zurück

```csharp
public Mesh Triangulate()
```

### Rückgabewert

Aktuelles Mesh, wenn das aktuelle Mesh bereits trianguliert ist, andernfalls wird ein neues trianguliertes Mesh berechnet und zurückgegeben

## Beispiele

Der folgende Code zeigt, wie man ein Mesh trianguliert:

```csharp
//Das Ebenen-Mesh hat nur ein Polygon mit 4 Kontrollpunkten
var mesh = (new Plane()).ToMesh();
//Nach der Triangulation wird das Rechteck des neuen Meshes zu 2 Dreiecken.
var triangulated = mesh.Triangulate();
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


