---
title: Frustum
second_title: Aspose.3D for Java API-referens
description: Bas-klassen för  och
type: docs
weight: 69
url: /sv/java/com.aspose.threed/frustum/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public abstract class Frustum extends Entity implements IOrientable
```

Bas-klassen för [Camera](../../com.aspose.threed/camera) och [Light](../../com.aspose.threed/light)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getAspect()](#getAspect--) | Hämtar bildförhållandet för frustumet |
| [getBoundingBox()](#getBoundingBox--) | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Hämtar riktningen som kameran tittar mot. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [getExcluded()](#getExcluded--) | Hämtar om denna enhet ska exkluderas vid export. |
| [getFarPlane()](#getFarPlane--) | Hämtar frustumets avlägsna planavstånd. |
| [getLookAt()](#getLookAt--) | Hämtar den intresserade positionen som kameran tittar på. |
| [getName()](#getName--) | Hämtar namnet. |
| [getNearPlane()](#getNearPlane--) | Hämtar frustumets närplanavstånd. |
| [getOrthoHeight()](#getOrthoHeight--) | Hämtar höjden när frustumet är i ortografisk projektion. |
| [getParentNode()](#getParentNode--) | Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [getParentNodes()](#getParentNodes--) | Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getRotationMode()](#getRotationMode--) | Hämtar frustumets orienteringsläge. Denna egenskap fungerar endast när [getTarget](../../com.aspose.threed/frustum\\#getTarget) är null. |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [getTarget()](#getTarget--) | Hämtar målet som kameran tittar på. |
| [getUp()](#getUp--) | Hämtar kamerans uppåtriktning |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setAspect(double value)](#setAspect-double-) | Ställer in aspektförhållandet för frustumet |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Ställer in riktningen som kameran tittar på. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ställer in om denna enhet ska exkluderas vid export. |
| [setFarPlane(double value)](#setFarPlane-double-) | Ställer in frustumets fjärrplanavstånd. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Ställer in den intresserade positionen som kameran tittar på. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setNearPlane(double value)](#setNearPlane-double-) | Ställer in frustumens närplanavstånd. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Ställer in höjden när frustum är i ortografisk projektion. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Ställer in frustumens orienteringsläge. Denna egenskap fungerar endast när [getTarget](../../com.aspose.threed/frustum\#getTarget) är null. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Ställer in målet som kameran tittar på. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Ställer in kamerans uppåtriktning |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String | Egenskapsnamn. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAspect() {#getAspect--}
```
public double getAspect()
```


Hämtar bildförhållandet för frustumet

**Returns:**
double - frustumens bildförhållande
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem.

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


Hämtar riktningen som kameran tittar på. Ändringar av denna egenskap kommer också att påverka [getLookAt](../../com.aspose.threed/frustum\#getLookAt) och [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Hämtar nyckeln för enhetens renderare som är registrerad i renderaren

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Hämtar om denna enhet ska exkluderas vid export.

**Returns:**
boolean - om denna enhet ska exkluderas vid export.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Hämtar frustumets avlägsna planavstånd.

**Returns:**
double - frustumens fjärrplanavstånd.
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Hämtar den intresserade positionen som kameran tittar på.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Hämtar frustumets närplanavstånd.

**Returns:**
double - frustumens närplanavstånd.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Hämtar höjden när frustumet är i ortografisk projektion.

**Returns:**
double - höjden när frustum är i ortografisk projektion.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - alla föräldranoder, en entitet kan fästas på flera föräldranoder för geometriinstansering
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Hämta värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Värdet på den hittade egenskapen
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Hämtar frustumens orienteringsläge. Denna egenskap fungerar endast när [getTarget](../../com.aspose.threed/frustum\#getTarget) är null. Om värdet är [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), beräknas riktningen alltid av egenskapen [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Annars beräknas [getLookAt](../../com.aspose.threed/frustum\#getLookAt) alltid av [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Hämtar scenen som detta objekt tillhör

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Hämtar målet som kameran tittar på. Om användaren stödjer denna egenskap bör den vara före [getLookAt](../../com.aspose.threed/frustum\#getLookAt) egenskapen.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Hämtar kamerans uppåtriktning

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


Tar bort en dynamisk egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Ta bort den angivna egenskapen identifierad med namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Ställer in aspektförhållandet för frustumet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Ställer in riktningen som kameran tittar på. Ändringar av denna egenskap kommer också att påverka [getLookAt](../../com.aspose.threed/frustum\#getLookAt) och [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ställer in om denna enhet ska exkluderas vid export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Ställer in frustumets fjärrplanavstånd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Ställer in den intresserade positionen som kameran tittar på.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Ställer in frustumens närplanavstånd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Ställer in höjden när frustum är i ortografisk projektion.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nytt värde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ställer in värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |
| värde | java.lang.Object | Värdet på egenskapen |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Ställer in frustumens orienteringsläge. Denna egenskap fungerar endast när [getTarget](../../com.aspose.threed/frustum\#getTarget) är null. Om värdet är [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), beräknas riktningen alltid av egenskapen [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Annars beräknas [getLookAt](../../com.aspose.threed/frustum\#getLookAt) alltid av [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nytt värde |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Ställer in målet som kameran tittar på. Om användaren stöder denna egenskap bör den vara före [getLookAt](../../com.aspose.threed/frustum\#getLookAt) egenskapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nytt värde |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Ställer in kamerans uppåtriktning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

