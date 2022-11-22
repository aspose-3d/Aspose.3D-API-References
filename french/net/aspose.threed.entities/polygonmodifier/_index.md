---
title: PolygonModifier
second_title: Référence de l'API Aspose.3D pour .NET
description: Utilitaires pour modifier les polygones
type: docs
weight: 560
url: /fr/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Utilitaires pour modifier les polygones

```csharp
public class PolygonModifier
```

## Méthodes

| Nom | La description |
| --- | --- |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal#buildtangentbinormal)(Mesh) | Cela créera une tangente et une binormale sur le maillage La normale est requise, si la normale n'existe pas sur le maillage, cela créera également les données normales à partir de la position. L'UV est également requis, une exception sera levée si aucune UV n'est trouvée. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal#buildtangentbinormal_1)(Scene) | Cela créera une tangente et une binormale sur tous les maillages de la scène La normale est requise, si la normale n'existe pas sur le maillage, cela créera également les données normales à partir de la position. L'UV est également requis, le maillage sera ignoré s'il n'y a pas d'UV est défini. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal)(Mesh) | Générer des données normales à partir de la définition de maillage |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv#generateuv)(Mesh) | Générer des données UV à partir du maillage d'entrée donné |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv#generateuv_1)(Mesh, VertexElementNormal) | Générer des données UV à partir du maillage d'entrée donné et des données normales spécifiées. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh#mergemesh)(Node) | Convertir un nœud entier en un seul maillage transformé Les éléments de sommet comme les coordonnées normales/de texture ne sont pas encore pris en charge |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh#mergemesh_1)(Scene) | Convertir une scène entière en un seul maillage transformé Les éléments de sommet comme les coordonnées normales/de texture ne sont pas encore pris en charge |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale#scale_1)(Node, Vector3) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle et non la matrice de transformation) dans ce nœud |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale#scale)(Scene, Vector3) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle et non la matrice de transformation) dans cette scène |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh#splitmesh)(Mesh, SplitMeshPolicy) | Diviser le maillage en sous-maillages par[`VertexElementMaterial`](../vertexelementmaterial) . Chaque sous-maillage n'utilisera qu'un seul matériau. Le maillage d'origine ne sera pas modifié. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Diviser le maillage en sous-maillages par[`VertexElementMaterial`](../vertexelementmaterial) . Chaque sous-maillage n'utilisera qu'un seul matériau. Effectue la division du maillage sur tous les nœuds de la scène. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Diviser le maillage en sous-maillages par[`VertexElementMaterial`](../vertexelementmaterial) . Chaque sous-maillage n'utilisera qu'un seul matériau. Effectue le fractionnement du maillage sur un nœud |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate)(Mesh) | Convertir un maillage basé sur un polygone en un maillage triangulaire complet |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_5)(Scene) | Convertir tous les maillages basés sur des polygones en maillage triangulaire complet |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### Voir également

* espace de noms [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->