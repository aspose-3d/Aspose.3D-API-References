---
title: "Node.EvaluateGlobalTransform"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Évalue la transformation globale en incluant ou non la transformation géométrique"
type: docs
weight: 180
url: /fr/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

Évaluer la transformation globale, inclure ou non la transformation géométrique.

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| withGeometricTransform | Boolean | Indique si la transformation géométrique est nécessaire. |

### Valeur de retour

La matrice de transformation globale.

## Exemples

Le code suivant montre comment lire la matrice de transformation globale du nœud.

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//placez la boîte à (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### Voir aussi

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


