---
title: "RevolvedAreaSolid"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cette classe représente un modèle solide en faisant tourner une section transversale fournie par un profil autour d'un axe."
type: docs
weight: 155
url: /fr/java/com.aspose.threed/revolvedareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class RevolvedAreaSolid extends Entity implements IMeshConvertible
```

Cette classe représente un modèle solide en faisant pivoter une section transversale fournie par un profil autour d'un axe. **Example:** Le code suivant montre comment utiliser RevolvedAreaSolid pour faire pivoter une forme en un modèle solide.

```
//Create a new 3D scene
         Scene scene = new Scene();
 
         // Initialize the base profile to be extruded
         var profile = new RectangleShape();
         profile.setRoundingRadius(0.3);
 
         var revolved = new RevolvedAreaSolid();
         revolved.setShape(profile);
         revolved.setOrigin(new Vector3(1, 0, 0));
         revolved.setAngleStart(0);
         revolved.setAngleEnd(Math.PI);
         scene.getRootNode().createChildNode(revolved);
 
         scene.save("revolved.obj");
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RevolvedAreaSolid()](#RevolvedAreaSolid--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAngleEnd()](#getAngleEnd--) | Obtient l'angle final de la procédure de rotation, mesuré en radians, la valeur par défaut est pi. |
| [getAngleStart()](#getAngleStart--) | Obtient l'angle de départ de la procédure de révolution, mesuré en radian, la valeur par défaut est 0. |
| [getAxis()](#getAxis--) | Obtient la direction de l'axe, la valeur par défaut est (0, 1, 0). |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getName()](#getName--) | Obtient le nom. |
| [getOrigin()](#getOrigin--) | Obtient le point d'origine de la révolution, la valeur par défaut est (0, 0, 0). |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getShape()](#getShape--) | Obtient le profil de base utilisé pour la révolution. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAngleEnd(double value)](#setAngleEnd-double-) | Définit l'angle final de la procédure de révolution, mesuré en radian, la valeur par défaut est pi. |
| [setAngleStart(double value)](#setAngleStart-double-) | Définit l'angle de départ de la procédure de révolution, mesuré en radian, la valeur par défaut est 0. |
| [setAxis(Vector3 value)](#setAxis-com.aspose.threed.Vector3-) | Définit la direction de l'axe, la valeur par défaut est (0, 1, 0). |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setOrigin(Vector3 value)](#setOrigin-com.aspose.threed.Vector3-) | Définit le point d'origine de la révolution, la valeur par défaut est (0, 0, 0). |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | Définit le profil de base utilisé pour la révolution. |
| [toMesh()](#toMesh--) | Convertit le [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) en maillage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RevolvedAreaSolid() {#RevolvedAreaSolid--}
```
public RevolvedAreaSolid()
```


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
### getAngleEnd() {#getAngleEnd--}
```
public double getAngleEnd()
```


Obtient l'angle final de la procédure de rotation, mesuré en radians, la valeur par défaut est pi.

**Returns:**
double - l'angle final de la procédure de révolution, mesuré en radian, la valeur par défaut est pi.
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


Obtient l'angle de départ de la procédure de révolution, mesuré en radian, la valeur par défaut est 0.

**Returns:**
double - l'angle de départ de la procédure de révolution, mesuré en radian, la valeur par défaut est 0.
### getAxis() {#getAxis--}
```
public Vector3 getAxis()
```


Obtient la direction de l'axe, la valeur par défaut est (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the axis direction, default value is (0, 1, 0).
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
### getOrigin() {#getOrigin--}
```
public Vector3 getOrigin()
```


Obtient le point d'origine de la révolution, la valeur par défaut est (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the origin point of the revolving, default value is (0, 0, 0).
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


Obtient le profil de base utilisé pour la révolution.

**Returns:**
[Profile](../../com.aspose.threed/profile) - the base profile used to revolve.
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
### setAngleEnd(double value) {#setAngleEnd-double-}
```
public void setAngleEnd(double value)
```


Définit l'angle final de la procédure de révolution, mesuré en radian, la valeur par défaut est pi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


Définit l'angle de départ de la procédure de révolution, mesuré en radian, la valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setAxis(Vector3 value) {#setAxis-com.aspose.threed.Vector3-}
```
public void setAxis(Vector3 value)
```


Définit la direction de l'axe, la valeur par défaut est (0, 1, 0).

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

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setOrigin(Vector3 value) {#setOrigin-com.aspose.threed.Vector3-}
```
public void setOrigin(Vector3 value)
```


Définit le point d'origine de la révolution, la valeur par défaut est (0, 0, 0).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

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


Définit le profil de base utilisé pour la révolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | Nouvelle valeur |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Convertit le [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) en maillage.

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

