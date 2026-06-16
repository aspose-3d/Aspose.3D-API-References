---
title: "RectangularTorus"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Tore rectangulaire paramétré."
type: docs
weight: 146
url: /fr/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

Tore rectangulaire paramétré.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | Constructeur de [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | Constructeur de [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAngleStart()](#getAngleStart--) | L'angle de départ de l'arc, mesuré en radians. |
| [getArc()](#getArc--) | L'angle total de l'arc, mesuré en radians. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getCastShadows()](#getCastShadows--) | Obtient si cette géométrie peut projeter une ombre |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getHeight()](#getHeight--) | La hauteur du tore rectangulaire. |
| [getInnerRadius()](#getInnerRadius--) | Le rayon intérieur du tore rectangulaire. Valeur par défaut : 17 |
| [getName()](#getName--) | Obtient le nom. |
| [getOuterRadius()](#getOuterRadius--) | Le rayon extérieur du tore rectangulaire. Valeur par défaut : 20 |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRadialSegments()](#getRadialSegments--) | Les segments radiaux, valeur par défaut : 10 |
| [getReceiveShadows()](#getReceiveShadows--) | Obtient si cette géométrie peut recevoir une ombre. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAngleStart(double value)](#setAngleStart-double-) | L'angle de départ de l'arc, mesuré en radians. |
| [setArc(double value)](#setArc-double-) | L'angle total de l'arc, mesuré en radians. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Définit si cette géométrie peut projeter une ombre |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setHeight(double value)](#setHeight-double-) | La hauteur du tore rectangulaire. |
| [setInnerRadius(double value)](#setInnerRadius-double-) | Le rayon intérieur du tore rectangulaire. Valeur par défaut : 17 |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setOuterRadius(double value)](#setOuterRadius-double-) | Le rayon extérieur du tore rectangulaire. Valeur par défaut : 20 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Les segments radiaux, valeur par défaut : 10 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Définit si cette géométrie peut recevoir une ombre. |
| [toMesh()](#toMesh--) | Convertir cette primitive en [Mesh](../../com.aspose.threed/mesh) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


Constructeur de [RectangularTorus](../../com.aspose.threed/rectangulartorus)

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


Constructeur de [RectangularTorus](../../com.aspose.threed/rectangulartorus)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


L'angle de départ de l'arc, mesuré en radians. Valeur par défaut : 0

**Returns:**
double - L'angle de départ de l'arc, mesuré en radians. La valeur par défaut est 0
### getArc() {#getArc--}
```
public double getArc()
```


L'angle total de l'arc, mesuré en radians. La valeur par défaut est PI

**Returns:**
double - L'angle total de l'arc, mesuré en radians. La valeur par défaut est PI
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


La hauteur du tore rectangulaire. La valeur par défaut est 20

**Returns:**
double - La hauteur du tore rectangulaire. La valeur par défaut est 20
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


Le rayon intérieur du tore rectangulaire. Valeur par défaut : 17

**Returns:**
double - Le rayon interne du tore rectangulaire. La valeur par défaut est 17
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


Le rayon extérieur du tore rectangulaire. Valeur par défaut : 20

**Returns:**
double - Le rayon externe du tore rectangulaire. La valeur par défaut est 20
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Les segments radiaux, valeur par défaut : 10

**Returns:**
int - Les segments radiaux, la valeur par défaut est 10
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
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


L'angle de départ de l'arc, mesuré en radians. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


L'angle total de l'arc, mesuré en radians. La valeur par défaut est PI

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


La hauteur du tore rectangulaire. La valeur par défaut est 20

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


Le rayon intérieur du tore rectangulaire. Valeur par défaut : 17

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


Le rayon extérieur du tore rectangulaire. Valeur par défaut : 20

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Les segments radiaux, valeur par défaut : 10

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Définit si cette géométrie peut recevoir une ombre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Convertir cette primitive en [Mesh](../../com.aspose.threed/mesh)

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

