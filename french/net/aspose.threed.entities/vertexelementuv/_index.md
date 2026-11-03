---
title: "Classe VertexElementUV"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Entities.VertexElementUV classe. Définit les coordonnées UV pour les composants spécifiés. Une géométrie peut avoir plusieurs éléments VertexElementUV et chacun possède différents TextureMappings"
type: docs
weight: 960
url: /fr/net/aspose.threed.entities/vertexelementuv/
---
## VertexElementUV class

Définit les coordonnées UV pour les composants spécifiés. Une géométrie peut avoir plusieurs éléments `VertexElementUV`, et chacun possède différents [`TextureMapping`](../texturemapping/)s.

```csharp
public class VertexElementUV : VertexElementVector4
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VertexElementUV](vertexelementuv/#constructor)() | Initialise une nouvelle instance de la classe `VertexElementUV`. Le type de mappage de texture par défaut est Diffuse |
| [VertexElementUV](vertexelementuv/#constructor_1)(TextureMapping) | Initialise une nouvelle instance de la classe `VertexElementUV`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Data](../../aspose.threed.entities/vertexelementvector4/data/) { get; } | Obtient les données du sommet |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Obtient les données des indices |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Obtient ou définit comment l'élément est mappé. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Obtient ou définit le nom. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Obtient ou définit comment l'élément est référencé. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Obtient le type du [`VertexElement`](../vertexelement/) |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata)(IEnumerable&lt;Vector2&gt;) |  |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata_1)(IEnumerable&lt;Vector3&gt;) |  |
| override [Clear](../../aspose.threed.entities/vertexelementvector4/clear/)() | Supprime tous les éléments des tableaux direct et index. |
| [CopyTo](../../aspose.threed.entities/vertexelementvector4/copyto/)(VertexElementVector4) | Copie les données vers l'élément spécifié |
| [SetData](../../aspose.threed.entities/vertexelementvector4/setdata/)(Vector4[]) | Charger les données |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Charger les indices |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Représentation sous forme de chaîne de l'élément de sommet. |

### Voir aussi

* class [VertexElementVector4](../vertexelementvector4/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


