---
title: "PolygonModifier.Scale"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PolygonModifier. Mettre à l’échelle toutes les géométries. Mettre à l’échelle les points de contrôle, pas la matrice de transformation dans cette scène"
type: docs
weight: 60
url: /fr/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans cette scène

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| scène | Scène | La scène à mettre à l’échelle |
| échelle | Vector3 | Le facteur d’échelle |

## Exemples

Le code suivant montre comment mettre à l’échelle toutes les géométries de la scène par 10 fois.

```csharp
//Charger un fichier de test pour la mise à l’échelle
var scene = Scene.FromFile("input.fbx");
//mettre à l’échelle toutes les géométries par 10 fois.
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Voir aussi

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans ce nœud

```csharp
public static void Scale(Node node, Vector3 scale)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nœud | Nœud | Le nœud à mettre à l’échelle |
| échelle | Vector3 | Le facteur d’échelle |

## Exemples

Le code suivant montre comment mettre à l’échelle toutes les géométries de la scène par 10 fois.

```csharp
//Charger un fichier de test pour la mise à l’échelle
var scene = Scene.FromFile("input.fbx");
//mettre à l’échelle toutes les géométries par 10 fois.
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Voir aussi

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


