---
title: Camera
second_title: Aspose.3D for Java API-referentie
description: De camera beschrijft het oogpunt van de kijker die naar de scène kijkt.
type: docs
weight: 28
url: /nl/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

De camera beschrijft het oogpunt van de kijker die naar de scène kijkt.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Camera()](#Camera--) | Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse. |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse. |
| [Camera(String name)](#Camera-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse. |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getApertureMode()](#getApertureMode--) | Haalt de diafragmamodus van de camera op |
| [getAspect()](#getAspect--) | Haalt de beeldverhouding van het frustum op |
| [getAspectRatio()](#getAspectRatio--) | Haalt de beeldvlakverhouding op. |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Haalt de richting op waar de camera naar kijkt. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getFarPlane()](#getFarPlane--) | Haalt de afstand tot het verre vlak van het frustum op. |
| [getFieldOfView()](#getFieldOfView--) | Haalt het gezichtsveld van de camera op in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) of [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) is |
| [getFieldOfViewX()](#getFieldOfViewX--) | Haalt het horizontale gezichtsveld van de camera op in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is |
| [getFieldOfViewY()](#getFieldOfViewY--) | Haalt het verticale gezichtsveld van de camera op in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is |
| [getHeight()](#getHeight--) | Haalt de hoogte van het beeldvlak op, gemeten in inches |
| [getLookAt()](#getLookAt--) | Haalt de geïnteresseerde positie op waar de camera naar kijkt. |
| [getMagnification()](#getMagnification--) | Haalt de vergroting op die wordt gebruikt in een orthografische camera |
| [getName()](#getName--) | Haalt de naam op. |
| [getNearPlane()](#getNearPlane--) | Haalt de afstand van het nabijvlak van de frustum op. |
| [getOrthoHeight()](#getOrthoHeight--) | Haalt de hoogte op wanneer de frustum in orthografische projectie staat. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getProjectionType()](#getProjectionType--) | Haalt het projectietype van de camera op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRotationMode()](#getRotationMode--) | Haalt de oriëntatiemodus van de frustum op. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getTarget()](#getTarget--) | Haalt het doel op waar de camera naar kijkt. |
| [getUp()](#getUp--) | Haalt de opwaartse richting van de camera op. |
| [getWidth()](#getWidth--) | Haalt de breedte van het beeldvlak op, gemeten in inches |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Verplaats de camera naar voren in de richting of het doel. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Stelt de diafragmamodus van de camera in |
| [setAspect(double value)](#setAspect-double-) | Stelt de beeldverhouding van de frustum in |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Stelt de beeldvlakverhouding in. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Stelt de richting in waar de camera naar kijkt. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setFarPlane(double value)](#setFarPlane-double-) | Stelt de afstand van het verre vlak van de frustum in. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Stelt het gezichtsveld van de camera in graden in, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) of [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) is |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Stelt het horizontale gezichtsveld van de camera in graden in, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Stelt het verticale gezichtsveld van de camera in graden in, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is |
| [setHeight(double value)](#setHeight-double-) | Stelt de hoogte van het beeldvlak in, gemeten in inches |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Stelt de geïnteresseerde positie in waar de camera naar kijkt. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Stelt de vergroting in die wordt gebruikt in een orthografische camera |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setNearPlane(double value)](#setNearPlane-double-) | Stelt de afstand van de near plane van de frustum in. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Stelt de hoogte in wanneer de frustum zich in orthografische projectie bevindt. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Stelt het projectietype van de camera in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Stelt het doel in waar de camera naar kijkt. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Stelt de opwaartse richting van de camera in |
| [setWidth(double value)](#setWidth-double-) | Stelt de breedte van het beeldvlak in, gemeten in inches |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse.

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Projectietype. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Initialiseert een nieuw exemplaar van de [Camera](../../com.aspose.threed/camera) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Projectietype. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String | Eigenschapnaam. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Haalt de diafragmamodus van de camera op

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Haalt de beeldverhouding van het frustum op

**Returns:**
double - de beeldverhouding van de frustum
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Haalt de beeldvlakverhouding op.

**Returns:**
double - de beeldvlakverhouding.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem.

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


Haalt de richting op waar de camera naar kijkt. Wijzigingen in deze eigenschap zullen ook de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) en [getTarget](../../com.aspose.threed/frustum\#getTarget) beïnvloeden.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren.

**Returns:**
boolean - of deze entiteit moet worden uitgesloten tijdens het exporteren.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Haalt de afstand tot het verre vlak van het frustum op.

**Returns:**
double - de afstand van het far plane van de frustum.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Haalt het gezichtsveld van de camera op in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) of [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) is

**Returns:**
double - het gezichtsveld van de camera in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) of [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) is
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Haalt het horizontale gezichtsveld van de camera op in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is

**Returns:**
double - het horizontale gezichtsveld van de camera in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Haalt het verticale gezichtsveld van de camera op in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is

**Returns:**
double - het verticale gezichtsveld van de camera in graden, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is
### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van het beeldvlak op, gemeten in inches

**Returns:**
double - de hoogte van het beeldvlak, gemeten in inches
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Haalt de geïnteresseerde positie op waar de camera naar kijkt.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Haalt de vergroting op die wordt gebruikt in een orthografische camera

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Haalt de afstand van het nabijvlak van de frustum op.

**Returns:**
double - de afstand van het near plane van de frustum.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Haalt de hoogte op wanneer de frustum in orthografische projectie staat.

**Returns:**
double - de hoogte wanneer de frustum zich in orthografische projectie bevindt.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - alle bovenliggende knooppunten, een entiteit kan aan meerdere bovenliggende knooppunten worden gekoppeld voor geometrie‑instantiatie
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Haalt het projectietype van de camera op. Standaard wordt de perspectiefprojectie gebruikt.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Haalt de verzameling van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde op van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Haalt de oriëntatiemodus van de frustum op. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. Als de waarde [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) is, wordt de richting altijd berekend door de eigenschap [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Anders wordt de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) altijd berekend door de [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Haalt het doel op waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) eigenschap komen.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Haalt de opwaartse richting van de camera op.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt de breedte van het beeldvlak op, gemeten in inches

**Returns:**
double - de breedte van het kijkvlak gemeten in inches
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


Verplaats de camera naar voren in de richting of het doel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| afstand | double | Hoe lang vooruit te bewegen |

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


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijder de opgegeven eigenschap geïdentificeerd op naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Stelt de diafragmamodus van de camera in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Nieuwe waarde |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Stelt de beeldverhouding van de frustum in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Stelt de beeldvlakverhouding in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Stelt de richting in waar de camera naar kijkt. Wijzigingen in deze eigenschap zullen ook de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) en [getTarget](../../com.aspose.threed/frustum\#getTarget) beïnvloeden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Stelt de afstand van het verre vlak van de frustum in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Stelt het gezichtsveld van de camera in graden in, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) of [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) is

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Stelt het horizontale gezichtsveld van de camera in graden in, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Stelt het verticale gezichtsveld van de camera in graden in, deze eigenschap wordt alleen gebruikt wanneer ApertureMode [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) is

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Stelt de hoogte van het beeldvlak in, gemeten in inches

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Stelt de geïnteresseerde positie in waar de camera naar kijkt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Stelt de vergroting in die wordt gebruikt in een orthografische camera

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Stelt de afstand van de near plane van de frustum in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Stelt de hoogte in wanneer de frustum zich in orthografische projectie bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Stelt het projectietype van de camera in. Standaard wordt de perspectiefprojectie gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Nieuwe waarde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Stelt de waarde in van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. Als de waarde [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) is, wordt de richting altijd berekend door de eigenschap [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Anders wordt de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) altijd berekend door de [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nieuwe waarde |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Stelt het doel in waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de eigenschap [getLookAt](../../com.aspose.threed/frustum\#getLookAt) staan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Stelt de opwaartse richting van de camera in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Stelt de breedte van het beeldvlak in, gemeten in inches

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

