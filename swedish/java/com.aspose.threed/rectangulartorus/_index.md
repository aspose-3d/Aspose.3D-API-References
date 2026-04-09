---
title: RectangularTorus
second_title: Aspose.3D for Java API-referens
description: Parametriserad rektangulär torus.
type: docs
weight: 146
url: /sv/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

Parametriserad rektangulär torus.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | Konstruktor för [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | Konstruktor för [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getAngleStart()](#getAngleStart--) | Startvinkeln för bågen, mätt i radian. |
| [getArc()](#getArc--) | Den totala vinkeln för bågen, mätt i radian. |
| [getBoundingBox()](#getBoundingBox--) | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| [getCastShadows()](#getCastShadows--) | Hämtar om denna geometri kan kasta skugga |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [getExcluded()](#getExcluded--) | Hämtar om denna enhet ska exkluderas vid export. |
| [getHeight()](#getHeight--) | Höjden på den rektangulära torusen. |
| [getInnerRadius()](#getInnerRadius--) | Den inre radien på den rektangulära torusen Standardvärdet är 17 |
| [getName()](#getName--) | Hämtar namnet. |
| [getOuterRadius()](#getOuterRadius--) | Den yttre radien på den rektangulära torusen Standardvärdet är 20 |
| [getParentNode()](#getParentNode--) | Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [getParentNodes()](#getParentNodes--) | Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getRadialSegments()](#getRadialSegments--) | De radiella segmenten, standardvärdet är 10 |
| [getReceiveShadows()](#getReceiveShadows--) | Hämtar om denna geometri kan ta emot skugga. |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setAngleStart(double value)](#setAngleStart-double-) | Startvinkeln för bågen, mätt i radian. |
| [setArc(double value)](#setArc-double-) | Den totala vinkeln för bågen, mätt i radian. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ställer in om denna geometri kan kasta skugga |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ställer in om denna enhet ska exkluderas vid export. |
| [setHeight(double value)](#setHeight-double-) | Höjden på den rektangulära torusen. |
| [setInnerRadius(double value)](#setInnerRadius-double-) | Den inre radien på den rektangulära torusen Standardvärdet är 17 |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setOuterRadius(double value)](#setOuterRadius-double-) | Den yttre radien på den rektangulära torusen Standardvärdet är 20 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setRadialSegments(int value)](#setRadialSegments-int-) | De radiella segmenten, standardvärdet är 10 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ställer in om denna geometri kan ta emot skugga. |
| [toMesh()](#toMesh--) | Konvertera detta primitiv till [Mesh](../../com.aspose.threed/mesh) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


Konstruktor för [RectangularTorus](../../com.aspose.threed/rectangulartorus)

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


Konstruktor för [RectangularTorus](../../com.aspose.threed/rectangulartorus)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


Startvinkeln för bågen, mätt i radian. Standardvärdet är 0

**Returns:**
double - Startvinkeln för bågen, mätt i radian. Standardvärdet är 0
### getArc() {#getArc--}
```
public double getArc()
```


Den totala vinkeln för bågen, mätt i radian. Standardvärdet är PI

**Returns:**
double - Den totala vinkeln för bågen, mätt i radian. Standardvärdet är PI
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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Hämtar om denna geometri kan kasta skugga

**Returns:**
boolean - whether this geometry can cast shadow
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Höjden på den rektangulära torusen. Standardvärdet är 20

**Returns:**
double - Höjden på den rektangulära torusen. Standardvärdet är 20
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


Den inre radien på den rektangulära torusen Standardvärdet är 17

**Returns:**
double - Den inre radien på den rektangulära torusen. Standardvärdet är 17
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


Den yttre radien på den rektangulära torusen Standardvärdet är 20

**Returns:**
double - Den yttre radien på den rektangulära torusen. Standardvärdet är 20
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


De radiella segmenten, standardvärdet är 10

**Returns:**
int - De radiella segmenten, standardvärdet är 10
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Hämtar om denna geometri kan ta emot skugga.

**Returns:**
boolean - huruvida denna geometri kan ta emot skugga.
### getScene() {#getScene--}
```
public Scene getScene()
```


Hämtar scenen som detta objekt tillhör

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
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


Startvinkeln för bågen, mätt i radian. Standardvärdet är 0

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


Den totala vinkeln för bågen, mätt i radian. Standardvärdet är PI

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Ställer in om denna geometri kan kasta skugga

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ställer in om denna enhet ska exkluderas vid export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Höjden på den rektangulära torusen. Standardvärdet är 20

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


Den inre radien på den rektangulära torusen Standardvärdet är 17

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


Den yttre radien på den rektangulära torusen Standardvärdet är 20

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


De radiella segmenten, standardvärdet är 10

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Ställer in om denna geometri kan ta emot skugga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Konvertera detta primitiv till [Mesh](../../com.aspose.threed/mesh)

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

