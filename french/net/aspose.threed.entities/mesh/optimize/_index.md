---
title: "Mesh.Optimize"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Mesh. Optimise l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués"
type: docs
weight: 100
url: /fr/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Optimise l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués

```csharp
public Mesh Optimize(bool vertexElements)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vertexElements | Boolean | Optimiser les données d'éléments de sommet dupliquées |

### Valeur de retour

Nouvelle instance de maillage avec une utilisation compacte de la mémoire

## Exemples

Le code suivant montre comment éliminer les points de contrôle dupliqués d'un maillage non optimisé :

```csharp
//Sphere.ToMesh génère 117 points de contrôle
var mesh = (new Sphere()).ToMesh();
//Après optimisation, il ne reste que 86 points de contrôle, les indices des polygones sont également remappés.
var optimized = mesh.Optimize(true);
```

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Optimise l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| vertexElements | Boolean | Optimiser les données d'éléments de sommet dupliquées |
| toleranceControlPoint | Single | La tolérance pour le point de contrôle, la valeur par défaut est 1e-9 |
| toleranceNormal | Single | La tolérance pour normal/tangente/binormale, la valeur par défaut est 1e-9 |
| toleranceUV | Single | La tolérance pour uv, la valeur par défaut est 1e-9 |

### Valeur de retour

Nouvelle instance de maillage avec une utilisation compacte de la mémoire

### Voir aussi

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


