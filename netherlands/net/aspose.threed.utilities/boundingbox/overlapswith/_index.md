---
title: "BoundingBox.OverlapsWith"
second_title: "Aspose.3D voor .NET API-referentie"
description: "BoundingBox-methode. Controleer of het huidige begrenzingsvak overlapt met het opgegeven begrenzingsvak"
type: docs
weight: 140
url: /nl/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Controleer of het huidige begrenzingsvak overlapt met het opgegeven begrenzingsvak.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vak | BoundingBox | Het andere begrenzingsvak om te testen |

### Retourwaarde

Waar als het huidige begrenzingsvak overlapt met het opgegeven vak.

## Voorbeelden

De volgende code laat zien hoe je controleert of twee begrenzingsvakken elkaar overlappen.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Zie ook

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


