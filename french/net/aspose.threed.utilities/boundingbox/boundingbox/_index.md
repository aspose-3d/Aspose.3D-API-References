---
title: "BoundingBox.BoundingBox"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Constructeur BoundingBox. Initialise une boîte englobante finie avec les coins minimum et maximum donnés"
type: docs
weight: 10
url: /fr/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

Initialisez une boîte englobante finie avec les coins minimum et maximum donnés

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| minimum | Vector3 | Le coin minimum |
| maximum | Vector3 | Le coin maximum |

## Exemples

Le code suivant montre comment construire une boîte englobante à partir des coins minimum et maximum.

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Voir aussi

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

Initialisez une boîte englobante finie avec les coins minimum et maximum donnés

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| minX | Double | Le X du coin minimum |
| minY | Double | Le Y du coin minimum |
| minZ | Double | Le Z du coin minimum |
| maxX | Double | Le X du coin maximum |
| maxY | Double | Le Y du coin maximum |
| maxZ | Double | Le Z du coin maximum |

## Exemples

Le code suivant montre comment construire une boîte englobante à partir des coins minimum et maximum.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Voir aussi

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


