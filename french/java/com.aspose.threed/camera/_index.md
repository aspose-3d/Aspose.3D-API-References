---
title: "Camera"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La caméra décrit le point de vue de l'observateur regardant la scène."
type: docs
weight: 28
url: /fr/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

La caméra décrit le point de vue de l'observateur regardant la scène.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Camera()](#Camera--) | Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera). |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera). |
| [Camera(String name)](#Camera-java.lang.String-) | Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera). |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getApertureMode()](#getApertureMode--) | Obtient le mode d'ouverture de la caméra |
| [getAspect()](#getAspect--) | Obtient le rapport d'aspect du frustum |
| [getAspectRatio()](#getAspectRatio--) | Obtient le rapport d'aspect du plan de visualisation. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Obtient la direction vers laquelle la caméra regarde. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getFarPlane()](#getFarPlane--) | Obtient la distance du plan lointain du frustum. |
| [getFieldOfView()](#getFieldOfView--) | Obtient le champ de vision de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ou [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | Obtient le champ de vision horizontal de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | Obtient le champ de vision vertical de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | Obtient la hauteur du plan de visualisation mesurée en pouces |
| [getLookAt()](#getLookAt--) | Obtient la position d'intérêt vers laquelle la caméra regarde. |
| [getMagnification()](#getMagnification--) | Obtient le grossissement utilisé dans la caméra orthographique |
| [getName()](#getName--) | Obtient le nom. |
| [getNearPlane()](#getNearPlane--) | Obtient la distance du plan proche du frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Obtient la hauteur lorsque le frustum est en projection orthographique. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProjectionType()](#getProjectionType--) | Obtient le type de projection de la caméra. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRotationMode()](#getRotationMode--) | Obtient le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getTarget()](#getTarget--) | Obtient la cible vers laquelle la caméra regarde. |
| [getUp()](#getUp--) | Obtient la direction vers le haut de la caméra |
| [getWidth()](#getWidth--) | Obtient la largeur du plan de visualisation mesurée en pouces |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Déplace la caméra vers l'avant dans sa direction ou vers sa cible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Définit le mode d'ouverture de la caméra |
| [setAspect(double value)](#setAspect-double-) | Définit le rapport d'aspect du frustum |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Définit le rapport d'aspect du plan de visualisation. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Définit la direction vers laquelle la caméra regarde. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setFarPlane(double value)](#setFarPlane-double-) | Définit la distance du plan lointain du frustum. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Définit le champ de vision de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ou [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Définit le champ de vision horizontal de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Définit le champ de vision vertical de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | Définit la hauteur du plan de visualisation mesurée en pouces |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Définit la position d'intérêt vers laquelle la caméra regarde. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Définit le grossissement utilisé dans la caméra orthographique |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setNearPlane(double value)](#setNearPlane-double-) | Définit la distance du plan proche du frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Définit la hauteur lorsque le frustum est en projection orthographique. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Définit le type de projection de la caméra. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Définit la cible vers laquelle la caméra regarde. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Définit la direction vers le haut de la caméra. |
| [setWidth(double value)](#setWidth-double-) | Définit la largeur du plan de visualisation mesurée en pouces |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera).

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Type de projection. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Initialise une nouvelle instance de la classe [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Type de projection. |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Obtient le mode d'ouverture de la caméra

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Obtient le rapport d'aspect du frustum

**Returns:**
double - le rapport d'aspect du frustum
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Obtient le rapport d'aspect du plan de visualisation.

**Returns:**
double - le rapport d'aspect du plan de visualisation.
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
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Obtient le champ de vision de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ou [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
double - le champ de vision de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ou [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Obtient le champ de vision horizontal de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - le champ de vision horizontal de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Obtient le champ de vision vertical de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - le champ de vision vertical de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur du plan de visualisation mesurée en pouces

**Returns:**
double - la hauteur du plan de visualisation mesurée en pouces
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Obtient la position d'intérêt vers laquelle la caméra regarde.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Obtient le grossissement utilisé dans la caméra orthographique

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Obtient le type de projection de la caméra. Par défaut, la projection perspective est utilisée.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur du plan de visualisation mesurée en pouces

**Returns:**
double - la largeur du plan de vue mesurée en pouces
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


Déplace la caméra vers l'avant dans sa direction ou vers sa cible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| distance | double | Durée du déplacement vers l'avant |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Définit le mode d'ouverture de la caméra

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Nouvelle valeur |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Définit le rapport d'aspect du frustum

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Définit le rapport d'aspect du plan de visualisation.

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

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Définit le champ de vision de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ou [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Définit le champ de vision horizontal de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Définit le champ de vision vertical de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Définit la hauteur du plan de visualisation mesurée en pouces

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

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Définit le grossissement utilisé dans la caméra orthographique

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

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

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Définit le type de projection de la caméra. Par défaut, la projection perspective est utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Nouvelle valeur |

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

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Définit la largeur du plan de visualisation mesurée en pouces

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

