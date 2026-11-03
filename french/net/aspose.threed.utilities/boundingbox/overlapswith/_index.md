---
title: "BoundingBox.OverlapsWith"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode BoundingBox. Vérifie si la boîte englobante actuelle chevauche la boîte englobante spécifiée"
type: docs
weight: 140
url: /fr/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Vérifiez si la boîte englobante actuelle chevauche la boîte englobante spécifiée.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| boîte | BoundingBox | L'autre boîte englobante à tester |

### Valeur de retour

Vrai si la boîte englobante actuelle chevauche celle donnée.

## Exemples

Le code suivant montre comment vérifier si deux boîtes englobantes se chevauchent.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Voir aussi

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


