---
title: "LinearExtrusion"
second_title: "Référence d'API Aspose.3D pour Java"
description: "L'extrusion linéaire prend une forme 2D en entrée et étend la forme dans la troisième dimension."
type: docs
weight: 96
url: /fr/java/com.aspose.threed/linearextrusion/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class LinearExtrusion extends Entity implements IMeshConvertible
```

L'extrusion linéaire prend une forme 2D en entrée et étend la forme dans la troisième dimension. **Exemple:** Le code suivant montre comment utiliser LinearExtrusion pour extruder une forme en modèle solide.

```
//Create a new 3D scene
 		Scene scene = new Scene();
 
 		// Initialize the base profile to be extruded
 		var profile = new RectangleShape();
 		profile.setRoundingRadius(0.3);
 
 		// Create left node
 		var left = scene.getRootNode().createChildNode();
 		left.createChildNode(new Box(0.01, 3, 3));
 
 		// Create right node
 		var right = scene.getRootNode().createChildNode();
 		right.createChildNode(new Box(0.01, 3, 3));
 		right.getTransform().setTranslation(new Vector3(5, 0, 0));
 
 		//Perform linear extrusion on left node using center and slices property
 		var l = new LinearExtrusion(profile, 10);
 		l.setCenter(false);
 		l.setSlices(3);
 		l.setTwist(20);
 		left.createChildNode(l);
 
 		// Perform linear extrusion on left node using center and slices property
 		var r = new LinearExtrusion(profile, 10);
 		r.setCenter(true);
 		r.setSlices(3);
 		r.setTwist(90);
 		right.createChildNode(r);
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LinearExtrusion()](#LinearExtrusion--) | Constructeur de l'instance [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
| [LinearExtrusion(Profile shape, double height)](#LinearExtrusion-com.aspose.threed.Profile-double-) | Constructeur de l'instance [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getCenter()](#getCenter--) | Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | La direction de l'extrusion, la valeur par défaut est (0, 0, 1) |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getHeight()](#getHeight--) | La hauteur de la géométrie extrudée, la valeur par défaut est 1.0 |
| [getName()](#getName--) | Obtient le nom. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getShape()](#getShape--) | La forme de base à extruder. |
| [getSlices()](#getSlices--) | Les tranches de la géométrie extrudée tordue, la valeur par défaut est 1. |
| [getTwist()](#getTwist--) | Le nombre de degrés selon lesquels la forme est extrudée. |
| [getTwistOffset()](#getTwistOffset--) | Le décalage utilisé dans la torsion, la valeur par défaut est (0, 0, 0). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setCenter(boolean value)](#setCenter-boolean-) | Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | La direction de l'extrusion, la valeur par défaut est (0, 0, 1) |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setHeight(double value)](#setHeight-double-) | La hauteur de la géométrie extrudée, la valeur par défaut est 1.0 |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | La forme de base à extruder. |
| [setSlices(int value)](#setSlices-int-) | Les tranches de la géométrie extrudée tordue, la valeur par défaut est 1. |
| [setTwist(double value)](#setTwist-double-) | Le nombre de degrés selon lesquels la forme est extrudée. |
| [setTwistOffset(Vector3 value)](#setTwistOffset-com.aspose.threed.Vector3-) | Le décalage utilisé dans la torsion, la valeur par défaut est (0, 0, 0). |
| [toMesh()](#toMesh--) | Convertir l'extrusion en maillage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearExtrusion() {#LinearExtrusion--}
```
public LinearExtrusion()
```


Constructeur de l'instance [LinearExtrusion](../../com.aspose.threed/linearextrusion).

### LinearExtrusion(Profile shape, double height) {#LinearExtrusion-com.aspose.threed.Profile-double-}
```
public LinearExtrusion(Profile shape, double height)
```


Constructeur de l'instance [LinearExtrusion](../../com.aspose.threed/linearextrusion).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Profile](../../com.aspose.threed/profile) |  |
| hauteur | double |  |

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
### getCenter() {#getCenter--}
```
public boolean getCenter()
```


Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2.

**Returns:**
boolean - Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


La direction de l'extrusion, la valeur par défaut est (0, 0, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The direction of extrusion, default value is (0, 0, 1)
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


La hauteur de la géométrie extrudée, la valeur par défaut est 1.0

**Returns:**
double - La hauteur de la géométrie extrudée, la valeur par défaut est 1.0
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShape() {#getShape--}
```
public Profile getShape()
```


La forme de base à extruder.

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base shape to be extruded.
### getSlices() {#getSlices--}
```
public int getSlices()
```


Les tranches de la géométrie extrudée tordue, la valeur par défaut est 1.

**Returns:**
int - Les tranches de la géométrie extrudée tordue, la valeur par défaut est 1.
### getTwist() {#getTwist--}
```
public double getTwist()
```


Le nombre de degrés selon lesquels la forme est extrudée.

**Returns:**
double - Le nombre de degrés selon lesquels la forme est extrudée.
### getTwistOffset() {#getTwistOffset--}
```
public Vector3 getTwistOffset()
```


Le décalage utilisé dans la torsion, la valeur par défaut est (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The offset that used in twisting, default value is (0, 0, 0).
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
### setCenter(boolean value) {#setCenter-boolean-}
```
public void setCenter(boolean value)
```


Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


La direction de l'extrusion, la valeur par défaut est (0, 0, 1)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

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


La hauteur de la géométrie extrudée, la valeur par défaut est 1.0

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


La forme de base à extruder.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | Nouvelle valeur |

### setSlices(int value) {#setSlices-int-}
```
public void setSlices(int value)
```


Les tranches de la géométrie extrudée tordue, la valeur par défaut est 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setTwist(double value) {#setTwist-double-}
```
public void setTwist(double value)
```


Le nombre de degrés selon lesquels la forme est extrudée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setTwistOffset(Vector3 value) {#setTwistOffset-com.aspose.threed.Vector3-}
```
public void setTwistOffset(Vector3 value)
```


Le décalage utilisé dans la torsion, la valeur par défaut est (0, 0, 0).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Convertir l'extrusion en maillage.

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

