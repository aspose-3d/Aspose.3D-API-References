---
title: "BoundingBox.BoundingBox"
second_title: "Aspose.3D für .NET API-Referenz"
description: "BoundingBox-Konstruktor. Initialisiert eine endliche BoundingBox mit gegebener minimaler und maximaler Ecke."
type: docs
weight: 10
url: /de/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

Initialisiert eine endliche Begrenzungsbox mit angegebenen minimalen und maximalen Eckpunkten.

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Minimum | Vector3 | Die minimale Ecke |
| Maximum | Vector3 | Die maximale Ecke |

## Beispiele

Der folgende Code zeigt, wie man eine BoundingBox aus minimalen und maximalen Ecken erstellt.

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Siehe auch

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

Initialisiert eine endliche Begrenzungsbox mit angegebenen minimalen und maximalen Eckpunkten.

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| minX | Double | Die X-Koordinate der minimalen Ecke. |
| minY | Double | Die Y-Koordinate der minimalen Ecke. |
| minZ | Double | Die Z-Koordinate der minimalen Ecke. |
| maxX | Double | Der X-Wert der maximalen Ecke |
| maxY | Double | Der Y-Wert der maximalen Ecke |
| maxZ | Double | Der Z-Wert der maximalen Ecke |

## Beispiele

Der folgende Code zeigt, wie man eine BoundingBox aus minimalen und maximalen Ecken erstellt.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Siehe auch

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


