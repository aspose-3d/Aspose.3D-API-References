---
title: "Light"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La lumière éclaire la scène."
type: docs
weight: 94
url: /fr/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

La lumière éclaire la scène.

La formule pour calculer l'atténuation totale de la lumière est :  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Light()](#Light--) | Initialise une nouvelle instance de la classe [Light](../../com.aspose.threed/light). |
| [Light(String name)](#Light-java.lang.String-) | Initialise une nouvelle instance de la classe [Light](../../com.aspose.threed/light). |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Initialise une nouvelle instance de la classe [Light](../../com.aspose.threed/light). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAspect()](#getAspect--) | Obtient le rapport d'aspect du frustum |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getCastLight()](#getCastLight--) | Obtient si l'instance de lumière actuelle peut illuminer d'autres objets. |
| [getCastShadows()](#getCastShadows--) | Obtient si la lumière peut projeter des ombres sur d'autres objets. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtient la couleur de la lumière |
| [getConstantAttenuation()](#getConstantAttenuation--) | Obtient l'atténuation constante pour calculer l'atténuation totale de la lumière |
| [getDirection()](#getDirection--) | Obtient la direction vers laquelle la caméra regarde. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getFalloff()](#getFalloff--) | Obtient l'angle du cône de chute (en degrés). |
| [getFarPlane()](#getFarPlane--) | Obtient la distance du plan lointain du frustum. |
| [getHotSpot()](#getHotSpot--) | Obtient l'angle du cône du point chaud (en degrés). |
| [getIntensity()](#getIntensity--) | Obtient l'intensité de la lumière, la valeur par défaut est 100 |
| [getLightType()](#getLightType--) | Obtient le type de la lumière |
| [getLinearAttenuation()](#getLinearAttenuation--) | Obtient l'atténuation linéaire pour calculer l'atténuation totale de la lumière |
| [getLookAt()](#getLookAt--) | Obtient la position d'intérêt vers laquelle la caméra regarde. |
| [getName()](#getName--) | Obtient le nom. |
| [getNearPlane()](#getNearPlane--) | Obtient la distance du plan proche du frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Obtient la hauteur lorsque le frustum est en projection orthographique. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Obtient l'atténuation quadratique pour calculer l'atténuation totale de la lumière |
| [getRotationMode()](#getRotationMode--) | Obtient le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getShadowColor()](#getShadowColor--) | Obtient la couleur de l'ombre. |
| [getTarget()](#getTarget--) | Obtient la cible vers laquelle la caméra regarde. |
| [getUp()](#getUp--) | Obtient la direction vers le haut de la caméra |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAspect(double value)](#setAspect-double-) | Définit le rapport d'aspect du frustum |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Définit si l'instance actuelle de lumière peut éclairer d'autres objets. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Définit si la lumière peut projeter des ombres sur d'autres objets. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Définit la couleur de la lumière |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Définit l'atténuation constante pour calculer l'atténuation totale de la lumière |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Définit la direction vers laquelle la caméra regarde. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setFalloff(double value)](#setFalloff-double-) | Définit l'angle du cône de décroissance (en degrés). |
| [setFarPlane(double value)](#setFarPlane-double-) | Définit la distance du plan lointain du frustum. |
| [setHotSpot(double value)](#setHotSpot-double-) | Définit l'angle du cône du point chaud (en degrés). |
| [setIntensity(double value)](#setIntensity-double-) | Définit l'intensité de la lumière, la valeur par défaut est 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Définit le type de la lumière |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Définit l'atténuation linéaire pour calculer l'atténuation totale de la lumière |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Définit la position d'intérêt vers laquelle la caméra regarde. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setNearPlane(double value)](#setNearPlane-double-) | Définit la distance du plan proche du frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Définit la hauteur lorsque le frustum est en projection orthographique. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Définit l'atténuation quadratique pour calculer l'atténuation totale de la lumière. |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Définit la couleur de l'ombre. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Définit la cible vers laquelle la caméra regarde. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Définit la direction vers le haut de la caméra. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Initialise une nouvelle instance de la classe [Light](../../com.aspose.threed/light).

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Initialise une nouvelle instance de la classe [Light](../../com.aspose.threed/light).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Initialise une nouvelle instance de la classe [Light](../../com.aspose.threed/light).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |
| type | [LightType](../../com.aspose.threed/lighttype) | Nouveau type de lumière |

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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Obtient si l'instance de lumière actuelle peut illuminer d'autres objets.

**Returns:**
booléen - si l'instance de lumière actuelle peut éclairer d'autres objets.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Obtient si la lumière peut projeter des ombres sur d'autres objets.

**Returns:**
booléen - si la lumière peut projeter des ombres sur d'autres objets.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Obtient la couleur de la lumière

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Obtient l'atténuation constante pour calculer l'atténuation totale de la lumière

**Returns:**
double - l'atténuation constante pour calculer l'atténuation totale de la lumière
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Obtient l'angle du cône de chute (en degrés).

**Returns:**
double - l'angle du cône d'atténuation (en degrés).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Obtient la distance du plan lointain du frustum.

**Returns:**
double - la distance du plan lointain du frustum.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Obtient l'angle du cône du point chaud (en degrés).

**Returns:**
double - l'angle du cône du point chaud (en degrés).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Obtient l'intensité de la lumière, la valeur par défaut est 100

**Returns:**
double - l'intensité de la lumière, la valeur par défaut est 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Obtient le type de la lumière

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Obtient l'atténuation linéaire pour calculer l'atténuation totale de la lumière

**Returns:**
double - l'atténuation linéaire pour calculer l'atténuation totale de la lumière
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Obtient l'atténuation quadratique pour calculer l'atténuation totale de la lumière

**Returns:**
double - l'atténuation quadratique pour calculer l'atténuation totale de la lumière
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
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Obtient la couleur de l'ombre.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
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

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Définit si l'instance actuelle de lumière peut éclairer d'autres objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Définit si la lumière peut projeter des ombres sur d'autres objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Définit la couleur de la lumière

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Définit l'atténuation constante pour calculer l'atténuation totale de la lumière

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Définit l'angle du cône de décroissance (en degrés).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Définit la distance du plan lointain du frustum.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Définit l'angle du cône du point chaud (en degrés).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Définit l'intensité de la lumière, la valeur par défaut est 100

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Définit le type de la lumière

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Nouvelle valeur |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Définit l'atténuation linéaire pour calculer l'atténuation totale de la lumière

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Définit l'atténuation quadratique pour calculer l'atténuation totale de la lumière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [getTarget](../../com.aspose.threed/frustum\#getTarget) est nul. Si la valeur est [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), la direction est toujours calculée par la propriété [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Sinon, le [getLookAt](../../com.aspose.threed/frustum\#getLookAt) est toujours calculé par le [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nouvelle valeur |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Définit la couleur de l'ombre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

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

