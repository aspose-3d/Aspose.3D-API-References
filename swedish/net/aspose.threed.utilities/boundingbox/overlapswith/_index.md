---
title: "BoundingBox.OverlapsWith"
second_title: "Aspose.3D för .NET API‑referens"
description: "BoundingBox metod. Kontrollerar om den aktuella begränsningsrutan överlappar med den angivna begränsningsrutan"
type: docs
weight: 140
url: /sv/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Kontrollera om den aktuella begränsningsrutan överlappar med den angivna begränsningsrutan.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| låda | BoundingBox | Den andra avgränsningsrutan att testa |

### Returvärde

Sant om den aktuella avgränsningsrutan överlappar med den angivna.

## Exempel

Följande kod visar hur man kontrollerar om två avgränsningsrutor överlappar varandra.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Se även

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


