---
title: "BoundingBox.Contains"
second_title: "Aspose.3D voor .NET API-referentie"
description: "BoundingBox-methode. Controleer of het punt p zich binnen het begrenzingsvak bevindt"
type: docs
weight: 100
url: /nl/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Controleer of het punt p zich binnen het begrenzingsvak bevindt

```csharp
public bool Contains(Vector3 p)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | Vector3 | Het punt om te testen |

### Retourwaarde

Waar als het punt zich binnen het begrenzingsvak bevindt

## Voorbeelden

De volgende code laat zien hoe je kunt controleren of een punt zich binnen het begrenzingsvak bevindt.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Zie ook

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Het begrenzingsvak om te controleren of het zich binnen het huidige begrenzingsvak bevindt.

```csharp
public bool Contains(BoundingBox bbox)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Zie ook

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


