---
title: "Classe GlobalTransform"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.GlobalTransform. La transformation globale est similaire à Transform mais elle est immuable tout en représentant la transformation finale évaluée. Un système de coordonnées droitier est utilisé lors de l'évaluation de la transformation globale."
type: docs
weight: 1560
url: /fr/net/aspose.threed/globaltransform/
---
## GlobalTransform class

La transformation globale est similaire à [`Transform`](../transform/) mais elle est immuable tout en représentant la transformation finale évaluée. Un système de coordonnées droitier est utilisé lors de l'évaluation de la transformation globale.

```csharp
public class GlobalTransform
```

## Propriétés

| Nom | Description |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | Obtient la rotation représentée en angles d'Euler, mesurée en degrés |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | Obtient la rotation représentée en quaternion. |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | Obtient l'échelle |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | Obtient la matrice de transformation. |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | Obtient la translation |

## Exemples

Le code suivant montre comment lire la transformation globale du nœud

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//placez la boîte à (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Voir aussi

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


