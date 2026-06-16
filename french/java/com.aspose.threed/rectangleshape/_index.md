---
title: "RectangleShape"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Forme rectangulaire compatible IFC avec des coins arrondis."
type: docs
weight: 145
url: /fr/java/com.aspose.threed/rectangleshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class RectangleShape extends ParameterizedProfile
```

Forme rectangulaire compatible IFC avec des coins arrondis.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RectangleShape()](#RectangleShape--) | Constructeur de [RectangleShape](../../com.aspose.threed/rectangleshape) |
| [RectangleShape(double xdim, double ydim)](#RectangleShape-double-double-) | Constructeur de [RectangleShape](../../com.aspose.threed/rectangleshape) avec les dimensions spécifiées sur les axes x et y. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getExtent()](#getExtent--) | Obtient l'étendue dans les dimensions x et y. |
| [getName()](#getName--) | Obtient le nom. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRoundingRadius()](#getRoundingRadius--) | Obtient le rayon des arcs circulaires des quatre coins, mesuré en degrés. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getXDim()](#getXDim--) | Obtient l'étendue du rectangle dans la direction de l'axe x. La valeur par défaut est 2.0 |
| [getYDim()](#getYDim--) | Obtient l'étendue du rectangle dans la direction de l'axe y. La valeur par défaut est 2.0 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRoundingRadius(double value)](#setRoundingRadius-double-) | Définit le rayon des arcs circulaires des quatre coins, mesuré en degrés. |
| [setXDim(double value)](#setXDim-double-) | Définit l'étendue du rectangle dans la direction de l'axe x. La valeur par défaut est 2.0 |
| [setYDim(double value)](#setYDim-double-) | Définit l'étendue du rectangle dans la direction de l'axe y. La valeur par défaut est 2.0 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleShape() {#RectangleShape--}
```
public RectangleShape()
```


Constructeur de [RectangleShape](../../com.aspose.threed/rectangleshape)

### RectangleShape(double xdim, double ydim) {#RectangleShape-double-double-}
```
public RectangleShape(double xdim, double ydim)
```


Constructeur de [RectangleShape](../../com.aspose.threed/rectangleshape) avec les dimensions spécifiées sur les axes x et y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xdim | double |  |
| ydim | double |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtient la clé du rendu d'entité enregistré dans le moteur de rendu

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtient si l'entité doit être exclue lors de l'exportation.

**Returns:**
booléen - indique si l'entité doit être exclue lors de l'exportation.
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


Obtient l'étendue dans les dimensions x et y.

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
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
### getRoundingRadius() {#getRoundingRadius--}
```
public double getRoundingRadius()
```


Obtient le rayon des arcs circulaires des quatre coins, mesuré en degrés. La valeur par défaut est 0.0

**Returns:**
double - le rayon des arcs circulaires des quatre coins, mesuré en degrés. La valeur par défaut est 0.0
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getXDim() {#getXDim--}
```
public double getXDim()
```


Obtient l'étendue du rectangle dans la direction de l'axe x. La valeur par défaut est 2.0

**Returns:**
double - l'étendue du rectangle dans la direction de l'axe x. La valeur par défaut est 2.0
### getYDim() {#getYDim--}
```
public double getYDim()
```


Obtient l'étendue du rectangle dans la direction de l'axe y. La valeur par défaut est 2.0

**Returns:**
double - l'étendue du rectangle dans la direction de l'axe y. La valeur par défaut est 2.0
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

### setRoundingRadius(double value) {#setRoundingRadius-double-}
```
public void setRoundingRadius(double value)
```


Définit le rayon des arcs circulaires des quatre coins, mesuré en degrés. La valeur par défaut est 0.0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setXDim(double value) {#setXDim-double-}
```
public void setXDim(double value)
```


Définit l'étendue du rectangle dans la direction de l'axe x. La valeur par défaut est 2.0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setYDim(double value) {#setYDim-double-}
```
public void setYDim(double value)
```


Définit l'étendue du rectangle dans la direction de l'axe y. La valeur par défaut est 2.0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

