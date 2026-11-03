---
title: "Classe PolygonModifier"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.PolygonModifier. Utilitaires pour modifier les polygones"
type: docs
weight: 620
url: /fr/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Utilitaires pour modifier les polygones

```csharp
public class PolygonModifier
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | Appliquer la matrice de transformation sur les points de contrôle de toutes les géométries |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | Cela créera les tangentes et les binormales sur le maillage. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, une exception sera levée si aucun UV n'est trouvé. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | Cela créera les tangentes et les binormales sur tous les maillages de la scène. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, le maillage sera ignoré s'il n'y a pas d'UV défini. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | Générer les données de normales à partir de la définition du Mesh |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | Générer les données UV à partir du maillage d'entrée fourni |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | Générer les données UV à partir du maillage d'entrée fourni et des données de normales spécifiées. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | Convertir un nœud complet en un seul maillage transformé. Les éléments de sommet comme les normales/coordonnées de texture ne sont pas encore pris en charge. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | Convertir une scène complète en un seul maillage transformé. Les éléments de sommet comme les normales/coordonnées de texture ne sont pas encore pris en charge. |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans ce nœud |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans cette scène |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | Divisez le maillage en sous-maillages par [`VertexElementMaterial`](../vertexelementmaterial/). Chaque sous-maillage utilisera un seul matériau. Le maillage original ne sera pas modifié. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Divisez le maillage en sous-maillages par [`VertexElementMaterial`](../vertexelementmaterial/). Chaque sous-maillage utilisera un seul matériau. Effectuez le découpage du maillage sur tous les nœuds de la scène. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Divisez le maillage en sous-maillages par [`VertexElementMaterial`](../vertexelementmaterial/). Chaque sous-maillage utilisera un seul matériau. Effectuez le découpage du maillage sur un nœud. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | Convertissez un maillage basé sur des polygones en maillage entièrement triangulaire |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | Convertissez tous les maillages basés sur des polygones en maillage entièrement triangulaire |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### Voir aussi

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


