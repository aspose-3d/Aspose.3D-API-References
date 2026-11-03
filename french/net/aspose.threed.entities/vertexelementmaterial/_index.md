---
title: "Classe VertexElementMaterial"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.VertexElementMaterial. Définit l'index de matériau pour les composants spécifiés. Un nœud peut avoir plusieurs matériaux ; le VertexElementMaterial est utilisé pour rendre différentes parties de la géométrie avec différents matériaux"
type: docs
weight: 880
url: /fr/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

Définit l'index de matériau pour les composants spécifiés. Un nœud peut avoir plusieurs matériaux, le `VertexElementMaterial` est utilisé pour rendre différentes parties de la géométrie avec différents matériaux.

```csharp
public class VertexElementMaterial : VertexElement
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | Initialise une nouvelle instance de la classe `VertexElementMaterial`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Obtient les données des indices |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Obtient ou définit comment l'élément est mappé. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Obtient ou définit le nom. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Obtient ou définit comment l'élément est référencé. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Obtient le type du [`VertexElement`](../vertexelement/) |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | Supprime tous les éléments des tableaux direct et index. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Charger les indices |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Représentation sous forme de chaîne de l'élément de sommet. |

## Exemples

Le code suivant montre comment assigner différents matériaux à différentes faces d'une boîte.

```csharp
// Crée un maillage d'une boîte (une boîte est composée de 6 plans)
Mesh box = (new Box()).ToMesh();
// Crée un élément de matériau sur ce maillage
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Et spécifie un index de matériau différent pour chaque plan
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### Voir aussi

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


