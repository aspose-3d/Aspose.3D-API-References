---
title: "BoundingBox.FromGeometry"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode BoundingBox. Construit une boîte englobante à partir de la géométrie donnée"
type: docs
weight: 40
url: /fr/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

Construire une boîte englobante à partir de la géométrie donnée

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| géométrie | Geometry | La géométrie pour calculer la boîte englobante |

### Valeur de retour

La boîte englobante de la géométrie donnée

## Exemples

Le code suivant montre comment construire une boîte englobante à partir d'une instance de géométrie.

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Voir aussi

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


