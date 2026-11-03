---
title: "BoundingBox.FromGeometry"
second_title: "Aspose.3D für .NET API-Referenz"
description: "BoundingBox-Methode. Erstellt eine BoundingBox aus gegebener Geometrie."
type: docs
weight: 40
url: /de/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

Erstelle eine Begrenzungsbox aus gegebener Geometrie

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Geometrie | Geometrie | Die Geometrie zur Berechnung der BoundingBox. |

### Rückgabewert

Die BoundingBox der gegebenen Geometrie.

## Beispiele

Der folgende Code zeigt, wie man eine BoundingBox aus einer Geometrie-Instanz erstellt.

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Siehe auch

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


