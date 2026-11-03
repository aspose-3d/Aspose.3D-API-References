---
title: "Entity.GetBoundingBox"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Entity-Methode. Gibt die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem zurück."
type: docs
weight: 50
url: /de/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

Ermittelt die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem.

```csharp
public BoundingBox GetBoundingBox()
```

### Rückgabewert

die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem.

## Beispiele

Der folgende Code zeigt, wie die Bounding-Box einer Form berechnet wird

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### Siehe auch

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)


