---
title: "Geometry"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La classe de base de tous les objets géométriques rendables comme    et etc."
type: docs
weight: 71
url: /fr/java/com.aspose.threed/geometry/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)
```
public class Geometry extends Entity
```

La classe de base de tous les objets géométriques rendables (comme [Mesh](../../com.aspose.threed/mesh), [NurbsSurface](../../com.aspose.threed/nurbssurface), [Patch](../../com.aspose.threed/patch) et etc.).

La classe de base [Geometry](../../com.aspose.threed/geometry) prend en charge :

 *  **Control point management**, control points defines the base 3D spatial structure of the geometry, different geometric types has different way to define concrete 3D models.
 *  **Vertex element definition**, vertex elements applies extra information like normals/uv coordinates/vertex colors to the geometry, see [VertexElement](../../com.aspose.threed/vertexelement) for more details.
 *  **Object deforming**, [Deformer](../../com.aspose.threed/deformer) can be bonded to animate geometry's shape.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Geometry(String name)](#Geometry-java.lang.String-) | Initialise une nouvelle instance de la classe [Geometry](../../com.aspose.threed/geometry). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Obtient tous les déformateurs avec les types de déformateur spécifiés |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Ajoute un élément de sommet existant à la géométrie actuelle |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Crée un [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crée un [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getCastShadows()](#getCastShadows--) | Obtient si cette géométrie peut projeter une ombre |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Obtient tous les points de contrôle |
| [getDeformers()](#getDeformers--) | Obtient tous les déformateurs associés à cette géométrie. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Obtient un élément de sommet avec le type spécifié |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getName()](#getName--) | Obtient le nom. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getReceiveShadows()](#getReceiveShadows--) | Obtient si cette géométrie peut recevoir une ombre. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Obtient une instance de [VertexElementUV](../../com.aspose.threed/vertexelementuv) avec le type de mappage de texture donné |
| [getVertexElements()](#getVertexElements--) | Obtient tous les éléments de sommet |
| [getVisible()](#getVisible--) | Obtient si la géométrie est visible |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Définit si cette géométrie peut projeter une ombre |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Définit si cette géométrie peut recevoir une ombre. |
| [setVisible(boolean value)](#setVisible-boolean-) | Définit si la géométrie est visible |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geometry(String name) {#Geometry-java.lang.String-}
```
public Geometry(String name)
```


Initialise une nouvelle instance de la classe [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Obtient tous les déformateurs avec les types de déformateur spécifiés

**Returns:**
java.util.Collection<T> - Collection de déformateurs
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Ajoute un élément de sommet existant à la géométrie actuelle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | L'élément de sommet à ajouter |

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

