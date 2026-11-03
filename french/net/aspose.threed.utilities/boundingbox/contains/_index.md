---
title: "BoundingBox.Contains"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode BoundingBox. Vérifie si le point p est à l'intérieur de la boîte englobante"
type: docs
weight: 100
url: /fr/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Vérifier si le point p est à l'intérieur de la boîte englobante

```csharp
public bool Contains(Vector3 p)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| p | Vector3 | Le point à tester |

### Valeur de retour

Vrai si le point est à l'intérieur de la boîte englobante

## Exemples

Le code suivant montre comment vérifier si un point est à l'intérieur de la boîte englobante.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Voir aussi

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

La boîte englobante à vérifier si elle est à l'intérieur de la boîte englobante actuelle.

```csharp
public bool Contains(BoundingBox bbox)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Voir aussi

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


