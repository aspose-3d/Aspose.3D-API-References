---
title: "BoundingBox.Contains"
second_title: "Aspose.3D för .NET API‑referens"
description: "BoundingBox-metod. Kontrollera om punkten p är inne i avgränsningsrutan"
type: docs
weight: 100
url: /sv/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Kontrollera om punkten p är inne i avgränsningsrutan

```csharp
public bool Contains(Vector3 p)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | Vector3 | Punkten att testa |

### Returvärde

Sant om punkten är inne i avgränsningsrutan

## Exempel

Följande kod visar hur man kontrollerar om en punkt är inne i avgränsningsrutan.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Se även

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Avgränsningsrutan för att kontrollera om den är inne i den aktuella avgränsningsrutan.

```csharp
public bool Contains(BoundingBox bbox)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Se även

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


