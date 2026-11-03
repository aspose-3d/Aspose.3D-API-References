---
title: "BoundingBox.Contains"
second_title: "Aspose.3D für .NET API-Referenz"
description: "BoundingBox-Methode. Prüft, ob der Punkt p innerhalb der Begrenzungsbox liegt"
type: docs
weight: 100
url: /de/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Prüfen, ob der Punkt p innerhalb der Begrenzungsbox liegt

```csharp
public bool Contains(Vector3 p)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | Vector3 | Der zu testende Punkt |

### Rückgabewert

Wahr, wenn der Punkt innerhalb der Begrenzungsbox liegt

## Beispiele

Der folgende Code zeigt, wie man prüft, ob ein Punkt innerhalb der Begrenzungsbox liegt.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Siehe auch

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Die Begrenzungsbox, um zu prüfen, ob sie innerhalb der aktuellen Begrenzungsbox liegt.

```csharp
public bool Contains(BoundingBox bbox)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Siehe auch

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


