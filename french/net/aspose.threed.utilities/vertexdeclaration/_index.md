---
title: "Classe VertexDeclaration"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Utilities.VertexDeclaration. La déclaration d'une structure de sommets définie sur mesure"
type: docs
weight: 2910
url: /fr/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

La déclaration de la structure d'un sommet défini sur mesure

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | Obtient le nombre de tous les champs définis dans ce `VertexDeclaration` |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | Une `VertexDeclaration` sera scellée lorsqu'elle aura été utilisée par [`TriMesh`](../../aspose.threed.entities/trimesh-1/) ou [`TriMesh`](../../aspose.threed.entities/trimesh/), aucune modification supplémentaire n'est autorisée. |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | La taille en octets de la structure de sommet. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | Créez une `VertexDeclaration` basée sur la disposition d'une [`Geometry`](../../aspose.threed.entities/geometry/). |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | Ajoutez un nouveau champ de sommet |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | Effacez tous les champs. |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | Compare cette instance à un objet spécifié et renvoie une indication de leurs valeurs relatives. |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | Détermine si cette instance et un objet spécifié, qui doit également être un objet `VertexDeclaration`, ont la même valeur. |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | Obtient un énumérateur pour parcourir tous les champs de sommet dans cette instance. |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | Renvoie le code de hachage pour cette chaîne. |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | Représentation sous forme de chaîne de `VertexDeclaration` |

### Voir aussi

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


