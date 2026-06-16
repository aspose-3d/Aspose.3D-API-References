---
title: "Mesh"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un maillage est composé de nombreux polygones à n côtés."
type: docs
weight: 102
url: /fr/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Un maillage est composé de nombreux polygones à n côtés. **Exemple :** Pour ajouter un polygone dans le maillage :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Parcourir tous les polygones du maillage :

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Mesh()](#Mesh--) | Initialise une nouvelle instance de la classe [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | Initialise une nouvelle instance de la classe [Mesh](../../com.aspose.threed/mesh). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Obtient tous les déformateurs avec les types de déformateur spécifiés |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Ajoutez un nouveau point de contrôle au maillage, c'est plus efficace. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Ajoutez un nouveau point de contrôle au maillage, c'est plus efficace. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Ajoute un élément de sommet existant à la géométrie actuelle |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Crée un [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crée un [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Créer un polygone avec 3 sommets(triangle) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Créer un polygone avec 4 sommets(quad) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Crée un nouveau polygone avec tous les sommets définis dans `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Crée un nouveau polygone avec tous les sommets définis dans `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calculer la différence de deux maillages |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Effectuer une opération booléenne sur deux maillages |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getCastShadows()](#getCastShadows--) | Obtient si cette géométrie peut projeter une ombre |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Obtient tous les points de contrôle |
| [getDeformers()](#getDeformers--) | Obtient tous les déformateurs associés à cette géométrie. |
| [getEdges()](#getEdges--) | Obtient les arêtes du maillage. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Obtient un élément de sommet avec le type spécifié |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getName()](#getName--) | Obtient le nom. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getPolygonCount()](#getPolygonCount--) | Obtient le nombre de polygones |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Obtient le nombre de sommets du polygone spécifié. |
| [getPolygons()](#getPolygons--) | Obtient la définition des polygones du maillage |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getReceiveShadows()](#getReceiveShadows--) | Obtient si cette géométrie peut recevoir une ombre. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Obtient une instance de [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné |
| [getVertexElements()](#getVertexElements--) | Obtient tous les éléments de sommet |
| [getVisible()](#getVisible--) | Obtient si la géométrie est visible |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calculer l'intersection de deux maillages |
| [isManifold()](#isManifold--) | Vérifier si le maillage actuel est un maillage manifold. |
| [iterator()](#iterator--) | Obtient l'énumérateur pour chaque polygone interne. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Définit si cette géométrie peut projeter une ombre |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Définit si cette géométrie peut recevoir une ombre. |
| [setVisible(boolean value)](#setVisible-boolean-) | Définit si la géométrie est visible |
| [toMesh()](#toMesh--) | Obtient l'instance Mesh de l'entité actuelle. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Renvoie le maillage triangulé |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calcule l'union de deux maillages |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Initialise une nouvelle instance de la classe [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Initialise une nouvelle instance de la classe [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Obtient tous les déformateurs avec les types de déformateur spécifiés

**Returns:**
java.util.Collection<T> - Collection de déformateurs
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Ajoutez un nouveau point de contrôle au maillage, c'est plus efficace.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | Le composant x du point de contrôle |
| y | double | Le composant y du point de contrôle |
| z | double | Le composant z du point de contrôle |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Ajoutez un nouveau point de contrôle au maillage, c'est plus efficace.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | Le composant x du point de contrôle |
| y | double | Le composant y du point de contrôle |
| z | double | Le composant z du point de contrôle |
| w | double | Le composant w du point de contrôle |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Ajoute un élément de sommet existant à la géométrie actuelle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | L'élément de sommet à ajouter |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Type d'élément de sommet |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Type d'élément de sommet |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Mode de mappage par défaut |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Mode de référence par défaut |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Crée un [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Quel type de mappage de texture créer |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Crée un [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Quel type de mappage de texture créer |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Mode de mappage par défaut |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Mode de référence par défaut |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Créer un polygone avec 3 sommets(triangle)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v1 | int | Indice du premier sommet |
| v2 | int | Indice du deuxième sommet |
|  | v3 | int | Indice du troisième sommet **Example:** Le code suivant montre comment créer un nouveau polygone avec les indices du point de contrôle. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Créer un polygone avec 4 sommets(quad)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v1 | int | Indice du premier sommet |
| v2 | int | Indice du deuxième sommet |
| v3 | int | Indice du troisième sommet |
|  | v4 | int | Indice du quatrième sommet **Example:** Le code suivant montre comment créer un nouveau polygone avec les indices du point de contrôle. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Crée un nouveau polygone avec tous les sommets définis dans `indices`. Pour créer le polygone sommet par sommet, veuillez utiliser [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | indices | int[] | Tableau des indices du polygone, chaque indice pointe vers un point de contrôle qui forme le polygone. **Exemple:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Crée un nouveau polygone avec tous les sommets définis dans `indices`. Pour créer le polygone sommet par sommet, veuillez utiliser [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indices | int[] | Tableau des indices du polygone, chaque indice pointe vers un point de contrôle qui forme le polygone. |
| décalage | int | Le décalage du premier indice du polygone |
|  | longueur | int | La longueur des indices **Exemple:** Le code suivant montre comment créer un nouveau polygone avec les indices du point de contrôle. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Calculer la différence de deux maillages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Premier maillage |
| b | [Mesh](../../com.aspose.threed/mesh) | Deuxième maillage |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Effectuer une opération booléenne sur deux maillages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Le type d'opération booléenne. |
| a | [Mesh](../../com.aspose.threed/mesh) | Premier maillage à opérer. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Matrice de transformation du premier maillage |
| b | [Mesh](../../com.aspose.threed/mesh) | Deuxième maillage à opérer |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Matrice de transformation du deuxième maillage |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Obtient si cette géométrie peut projeter une ombre

**Returns:**
boolean - indique si cette géométrie peut projeter une ombre
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Obtient tous les points de contrôle

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tous les points de contrôle
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Obtient tous les déformateurs associés à cette géométrie.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - tous les déformateurs associés à cette géométrie.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Obtient les arêtes du maillage. L'arête est facultative dans le maillage, elle peut donc être vide.

**Returns:**
java.util.List<java.lang.Integer> - arêtes du maillage. L'arête est facultative dans le maillage, elle peut donc être vide.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Obtient un élément de sommet avec le type spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | quel type d'élément de sommet rechercher |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtient la clé du rendu d'entité enregistré dans le moteur de rendu

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtient si l'entité doit être exclue lors de l'exportation.

**Returns:**
booléen - indique si l'entité doit être exclue lors de l'exportation.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Obtient le nombre de polygones

**Returns:**
int - le nombre de polygones **Exemple:** Le code suivant montre comment obtenir le nombre de polygones du maillage.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Obtient le nombre de sommets du polygone spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Indice. |

**Returns:**
int - La taille du polygone.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Obtient la définition des polygones du maillage

**Returns:**
java.util.List<int[]> - la définition des polygones du maillage
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Obtient si cette géométrie peut recevoir une ombre.

**Returns:**
boolean - si cette géométrie peut recevoir une ombre.
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Obtient une instance de [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Obtient tous les éléments de sommet

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - tous les éléments de sommet
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Obtient si la géométrie est visible

**Returns:**
boolean - si la géométrie est visible
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


Calculer l'intersection de deux maillages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Premier maillage |
| b | [Mesh](../../com.aspose.threed/mesh) | Deuxième maillage |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Vérifiez si le maillage actuel est un maillage manifold. Cette fonction ne mettra pas en cache le résultat du calcul du manifold.

**Returns:**
boolean - vrai si le maillage est un maillage manifold.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Obtient l'énumérateur pour chaque polygone interne.

**Returns:**
java.util.Iterator<int[]> - L'énumérateur.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vertexElements | boolean | Optimiser les données d'éléments de sommet dupliquées |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vertexElements | boolean | Optimiser les données d'éléments de sommet dupliquées |
| toleranceControlPoint | float | La tolérance pour le point de contrôle, la valeur par défaut est 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vertexElements | boolean | Optimiser les données d'éléments de sommet dupliquées |
| toleranceControlPoint | float | La tolérance pour le point de contrôle, la valeur par défaut est 1e-9 |
| toleranceNormal | float | La tolérance pour la normale/tangente/binormale, la valeur par défaut est 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vertexElements | boolean | Optimiser les données d'éléments de sommet dupliquées |
| toleranceControlPoint | float | La tolérance pour le point de contrôle, la valeur par défaut est 1e-9 |
| toleranceNormal | float | La tolérance pour la normale/tangente/binormale, la valeur par défaut est 1e-9 |
| toleranceUV | float | La tolérance pour les uv, la valeur par défaut est 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Optimiser l'utilisation de la mémoire du maillage en éliminant les points de contrôle dupliqués

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vertexElements | boolean | Optimiser les données d'éléments de sommet dupliquées |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Définit si cette géométrie peut projeter une ombre

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Définit si l'entité doit être exclue lors de l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Définit si cette géométrie peut recevoir une ombre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Définit si la géométrie est visible

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Obtient l'instance Mesh de l'entité actuelle.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


Renvoie le maillage triangulé

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


Calcule l'union de deux maillages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Premier maillage |
| b | [Mesh](../../com.aspose.threed/mesh) | Deuxième maillage |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

