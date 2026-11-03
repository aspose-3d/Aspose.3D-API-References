---
title: "Classe Mesh"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Mesh. Un maillage est composé de nombreux polygones à n côtés"
type: docs
weight: 510
url: /fr/net/aspose.threed.entities/mesh/
---
## Mesh class

Un maillage est composé de nombreux polygones à n côtés.

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Mesh](mesh/#constructor)() | Initialise une nouvelle instance de la classe `Mesh`. |
| [Mesh](mesh/#constructor_4)(string) | Initialise une nouvelle instance de la classe `Mesh`. |
| [Mesh](mesh/#constructor_1)(TextureData) | Construire un maillage en utilisant la carte de hauteur spécifiée, si le format de pixel de la carte de hauteur contient plusieurs composants, le premier (généralement le rouge) sera utilisé comme valeur de hauteur (z). Les composantes x et y du point de contrôle sont des coordonnées de pixel normalisées. |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | Construire un maillage en utilisant la carte de hauteur spécifiée, si le format de pixel de la carte de hauteur contient plusieurs composants, le premier (généralement le rouge) sera utilisé comme valeur de hauteur (z). Les composantes x et y du point de contrôle sont des coordonnées de pixel normalisées. |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | Construire un maillage en utilisant la carte de hauteur spécifiée, si le format de pixel de la carte de hauteur contient plusieurs composants, le premier (généralement le rouge) sera utilisé comme valeur de hauteur (z). Les composantes x et y du point de contrôle sont des coordonnées de pixel normalisées. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Obtient tous les points de contrôle |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Obtient tous les déformateurs associés à cette géométrie. |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | Obtient les arêtes du Mesh. L'arête est optionnelle dans le maillage, elle peut donc être vide. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | Obtient le nombre de polygones |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | Obtient la définition des polygones du maillage |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Obtient tous les éléments de sommet |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Obtient ou définit si la géométrie est visible |

## Méthodes

| Nom | Description |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Ajoute un élément de sommet existant à la géométrie actuelle |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Crée un [`VertexElementUV`](../vertexelementuv/) avec le type de mappage de texture donné. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Crée un [`VertexElementUV`](../vertexelementuv/) avec le type de mappage de texture donné. |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | Crée un nouveau polygone avec tous les sommets définis dans *indices*. Pour créer le polygone sommet par sommet, veuillez utiliser [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | Crée un polygone avec 3 sommets (triangle) |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | Crée un nouveau polygone avec tous les sommets définis dans *indices*. Pour créer le polygone sommet par sommet, veuillez utiliser [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | Crée un polygone avec 4 sommets (quad) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Obtient un élément de sommet avec le type spécifié |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | Obtient l'énumérateur pour chaque polygone interne. |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | Obtient le nombre de sommets du polygone spécifié. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Obtient une instance de [`VertexElementUV`](../vertexelementuv/) avec le type de mappage de texture donné |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | Vérifie si le maillage actuel est un maillage manifold. Cette fonction ne mettra pas en cache le résultat du calcul du manifold. |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | Optimise l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | Optimise l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | Obtient l'instance Mesh de l'entité actuelle. |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | Renvoie le maillage triangulé |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | Calcule l'intersection de deux maillages |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | Calcule l'union de deux maillages |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | Calculer la différence entre deux maillages |

## Exemples

Pour ajouter un polygone dans le maillage :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Parcourir tous les polygones du maillage :

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //gérer le polygone
}
```

### Voir aussi

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


