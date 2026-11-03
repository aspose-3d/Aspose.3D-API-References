---
title: "Entity.GetBoundingBox"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Entity méthode. Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet"
type: docs
weight: 50
url: /fr/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet.

```csharp
public BoundingBox GetBoundingBox()
```

### Valeur de retour

la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet.

## Exemples

Le code suivant montre comment calculer la boîte englobante d'une forme

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### Voir aussi

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)


