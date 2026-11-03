---
title: "BoundingBox.OverlapsWith"
second_title: "Aspose.3D für .NET API-Referenz"
description: "BoundingBox-Methode. Prüft, ob die aktuelle Begrenzungsbox mit der angegebenen Begrenzungsbox überlappt"
type: docs
weight: 140
url: /de/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Prüfen, ob die aktuelle Begrenzungsbox mit der angegebenen Begrenzungsbox überlappt.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Box | BoundingBox | Die andere Begrenzungsbox zum Testen |

### Rückgabewert

Wahr, wenn die aktuelle Begrenzungsbox mit der angegebenen überlappt.

## Beispiele

Der folgende Code zeigt, wie man prüft, ob zwei Begrenzungsboxen miteinander überlappen.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Siehe auch

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


