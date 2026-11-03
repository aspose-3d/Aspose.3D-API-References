---
title: "Classe Patch"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Entities.Patch classe. Un Patch est une surface de modélisation paramétrique similaire à NurbsSurface, elle est également définie par deux PatchDirection, le U et le V. Mais la différence entre Patch et NurbsSurface est que la courbe PatchDirection peut être l'une des suivantes : Bezier QuadraticBezier BasisSpline CardinalSpline et Linear"
type: docs
weight: 560
url: /fr/net/aspose.threed.entities/patch/
---
## Patch class

`Patch` est une surface de modélisation paramétrique, similaire à [`NurbsSurface`](../nurbssurface/), elle est également définie par deux [`PatchDirection`](../patchdirection/), le [`U`](./u/) et le [`V`](./v/). Mais la différence entre `Patch` et [`NurbsSurface`](../nurbssurface/) est que la courbe [`PatchDirection`](../patchdirection/) peut être l'une des suivantes : Bezier, QuadraticBezier, BasisSpline, CardinalSpline et Linear

```csharp
public class Patch : Geometry
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Patch](patch/#constructor)() | Initialise une nouvelle instance de la classe `Patch`. |
| [Patch](patch/#constructor_1)(string) | Initialise une nouvelle instance de la classe `Patch`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Obtient tous les points de contrôle |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Obtient tous les déformateurs associés à cette géométrie. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [U](../../aspose.threed.entities/patch/u/) { get; } | Obtient la direction u. |
| [V](../../aspose.threed.entities/patch/v/) { get; } | Obtient la direction v. |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Obtient tous les éléments de sommet |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Obtient ou définit si la géométrie est visible |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Ajoute un élément de sommet existant à la géométrie actuelle |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Crée un [`VertexElementUV`](../vertexelementuv/) avec le type de mappage de texture donné. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Crée un [`VertexElementUV`](../vertexelementuv/) avec le type de mappage de texture donné. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Obtient un élément de sommet avec le type spécifié |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Obtient une instance de [`VertexElementUV`](../vertexelementuv/) avec le type de mappage de texture donné |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [Geometry](../geometry/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


