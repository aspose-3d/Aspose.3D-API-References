---
title: "Frustum"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La classe de base de  et "
type: docs
weight: 69
url: /fr/java/com.aspose.threed/frustum/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public abstract class Frustum extends Entity implements IOrientable
```

La classe de base de [Camera](../../com.aspose.threed/camera) et [Light](../../com.aspose.threed/light)
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAspect()](#getAspect--) | Obtient le rapport d'aspect du frustum |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Obtient la direction vers laquelle la caméra regarde. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getFarPlane()](#getFarPlane--) | Obtient la distance du plan lointain du frustum. |
| [getLookAt()](#getLookAt--) | Obtient la position d'intérêt vers laquelle la caméra regarde. |
| [getName()](#getName--) | Obtient le nom. |
| [getNearPlane()](#getNearPlane--) | Obtient la distance du plan proche du frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Obtient la hauteur lorsque le frustum est en projection orthographique. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRotationMode()](#getRotationMode--) | Obtient le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getTarget()](#getTarget--) | Obtient la cible vers laquelle la caméra regarde. |
| [getUp()](#getUp--) | Obtient la direction vers le haut de la caméra |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAspect(double value)](#setAspect-double-) | Définit le rapport d'aspect du frustum |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Définit la direction vers laquelle la caméra regarde. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setFarPlane(double value)](#setFarPlane-double-) | Définit la distance du plan lointain du frustum. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Définit la position d'intérêt vers laquelle la caméra regarde. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setNearPlane(double value)](#setNearPlane-double-) | Définit la distance du plan proche du frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Définit la hauteur lorsque le frustum est en projection orthographique. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Définit la cible vers laquelle la caméra regarde. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Définit la direction vers le haut de la caméra. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspect() {#getAspect--}
```
public double getAspect()
```


Obtient le rapport d'aspect du frustum

**Returns:**
double - le rapport d'aspect du frustum
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
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Obtient la direction vers laquelle la caméra regarde. Les modifications de cette propriété affecteront également le [getLookAt](../../com.aspose.threed/frustum\#getLookAt) et le [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Obtient la distance du plan lointain du frustum.

**Returns:**
double - la distance du plan lointain du frustum.
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Obtient la position d'intérêt vers laquelle la caméra regarde.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Obtient la distance du plan proche du frustum.

**Returns:**
double - la distance du plan proche du frustum.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Obtient la hauteur lorsque le frustum est en projection orthographique.

**Returns:**
double - la hauteur lorsque le frustum est en projection orthographique.
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
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Obtient le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. Si la valeur est [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la direction est toujours calculée par la propriété [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Sinon, le [getLookAt](../../com.aspose.threed/frustum\#getLookAt) est toujours calculé par le [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Obtient la cible vers laquelle la caméra regarde. Si l'utilisateur prend en charge cette propriété, elle doit précéder la propriété [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Obtient la direction vers le haut de la caméra

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Définit le rapport d'aspect du frustum

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Définit la direction vers laquelle la caméra regarde. Les modifications de cette propriété affecteront également le [getLookAt](../../com.aspose.threed/frustum\#getLookAt) et le [getTarget](../../com.aspose.threed/frustum\#getTarget).

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Définit la distance du plan lointain du frustum.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Définit la position d'intérêt vers laquelle la caméra regarde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Définit la distance du plan proche du frustum.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Définit la hauteur lorsque le frustum est en projection orthographique.

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. Si la valeur est [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la direction est toujours calculée par la propriété [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Sinon, le [getLookAt](../../com.aspose.threed/frustum\#getLookAt) est toujours calculé par le [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nouvelle valeur |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Définit la cible que la caméra regarde. Si l'utilisateur prend en charge cette propriété, elle doit être définie avant la propriété [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Définit la direction vers le haut de la caméra.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

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

