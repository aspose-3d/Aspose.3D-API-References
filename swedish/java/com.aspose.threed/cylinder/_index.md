---
title: Cylinder
second_title: Aspose.3D for Java API-referens
description: Parametriserad cylinder.
type: docs
weight: 40
url: /sv/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Parametriserad Cylinder. Den kan också användas för att representera en kon när någon av radiusTop/radiusBottom är noll.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Cylinder()](#Cylinder--) | Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getBoundingBox()](#getBoundingBox--) | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| [getCastShadows()](#getCastShadows--) | Hämtar om denna geometri kan kasta skugga |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [getExcluded()](#getExcluded--) | Hämtar om denna enhet ska exkluderas vid export. |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Hämtar om en fan‑stil cylinder ska genereras när ThetaLength är mindre än 2\*PI, annars kommer modellen inte att kapas. |
| [getHeight()](#getHeight--) | Hämtar cylinderns höjd. |
| [getHeightSegments()](#getHeightSegments--) | Hämtar höjsegmenten. |
| [getName()](#getName--) | Hämtar namnet. |
| [getOffsetBottom()](#getOffsetBottom--) | Hämtar vertex‑transformationsoffseten för den nedre sidan. |
| [getOffsetTop()](#getOffsetTop--) | Hämtar vertex‑transformationsoffseten för den övre sidan. |
| [getOpenEnded()](#getOpenEnded--) | Hämtar ett värde som indikerar om denna [Cylinder](../../com.aspose.threed/cylinder) är öppen i ändarna. |
| [getParentNode()](#getParentNode--) | Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [getParentNodes()](#getParentNodes--) | Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getRadialSegments()](#getRadialSegments--) | Hämtar de radiella segmenten. |
| [getRadiusBottom()](#getRadiusBottom--) | Hämtar radien på cylinderns nedre lock. |
| [getRadiusTop()](#getRadiusTop--) | Hämtar radien för cylinderns övre lock. |
| [getReceiveShadows()](#getReceiveShadows--) | Hämtar om denna geometri kan ta emot skugga. |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [getShearBottom()](#getShearBottom--) | Hämtar skjuvtransformen för den nedre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0) |
| [getShearTop()](#getShearTop--) | Hämtar skjuvtransformen för den övre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0) |
| [getThetaLength()](#getThetaLength--) | Hämtar längden på theta. |
| [getThetaStart()](#getThetaStart--) | Hämtar theta-starten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ställer in om denna geometri kan kasta skugga |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ställer in om denna enhet ska exkluderas vid export. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | Ställer in om en fläktstilcylinder ska genereras när ThetaLength är mindre än 2\*PI, annars kommer modellen inte att kapas. |
| [setHeight(double value)](#setHeight-double-) | Ställer in cylinderns höjd. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Ställer in höjdsegmenten. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Ställer in vertextransformationsoffseten för den nedre sidan. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Ställer in vertextransformationsoffseten för den övre sidan. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Ställer in ett värde som indikerar om denna [Cylinder](../../com.aspose.threed/cylinder) är öppen. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Ställer in de radiella segmenten. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Ställer in radien på cylinderns nedre lock. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Ställer in radien på cylinderns övre lock. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Ställer in om denna geometri kan ta emot skugga. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Ställer in skjuvtransformen för den nedre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0) |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Ställer in skjuvtransformen för den övre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0) |
| [setThetaLength(double value)](#setThetaLength-double-) | Ställer in längden på theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Ställer in theta-starten. |
| [toMesh()](#toMesh--) | Konvertera aktuellt objekt till mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder).

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radius | double | Radie för det övre och nedre locket. |
| höjd | double | Höjd. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radiusTop | double | Övre radie. |
| radiusBottom | double | Nedre radie. |
| höjd | double | Höjd. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radiusTop | double | Radie på cylinderns övre lock. |
| radiusBottom | double | Radie på cylinderns nedre lock. |
| höjd | double | Höjd på cylindern. |
| radialSegments | int | Radiella segment för både övre och nedre cirklar.. |
| heightSegments | int | Höjdsegment. |
| openEnded | boolean | Om den är inställd på  true  skulle cylindern sakna botten-/topplock.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Initierar en ny instans av klassen [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namnet på detta objekt |
| radiusTop | double | Radie på cylinderns övre lock. |
| radiusBottom | double | Radie på cylinderns nedre lock. |
| höjd | double | Höjd på cylindern. |
| radialSegments | int | Radiella segment för både övre och nedre cirklar.. |
| heightSegments | int | Höjdsegment. |
| openEnded | boolean | Om den är inställd på  true  skulle cylindern sakna botten-/topplock.. |
| thetaStart | double | Theta-start. |
| thetaLength | double | Theta-längd. |

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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Hämtar om en fan‑stil cylinder ska genereras när ThetaLength är mindre än 2\*PI, annars kommer modellen inte att kapas.

**Returns:**
boolean - huruvida en fläkt‑formad cylinder ska genereras när ThetaLength är mindre än 2\*PI, annars kommer modellen inte att skäras.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar cylinderns höjd.

**Returns:**
double - cylinderns höjd.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Hämtar höjsegmenten.

**Returns:**
int - höjdsegmenten.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Hämtar vertex‑transformationsoffseten för den nedre sidan.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Hämtar vertex‑transformationsoffseten för den övre sidan.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Hämtar ett värde som indikerar om denna [Cylinder](../../com.aspose.threed/cylinder) är öppen i ändarna. Standardvärdet är false.

**Returns:**
boolean - ett värde som indikerar om denna [Cylinder](../../com.aspose.threed/cylinder) är öppen i ändarna. Standardvärdet är false.
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


Hämtar de radiella segmenten.

**Returns:**
int - de radiella segmenten.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Hämtar radien på cylinderns nedre lock.

**Returns:**
double - radien på cylinderns bottenlock.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Hämtar radien för cylinderns övre lock.

**Returns:**
double - radien på cylinderns topplock.
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
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Hämtar skjuvtransformen för den nedre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Hämtar skjuvtransformen för den övre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Hämtar längden på theta. Standardvärdet är 2\\u03c0.

**Returns:**
double - längden på theta. Standardvärdet är 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Hämtar theta‑starten. Standardvärdet är 0.

**Returns:**
double - theta‑starten. Standardvärdet är 0.
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

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


Ställer in om en fläktstilcylinder ska genereras när ThetaLength är mindre än 2\*PI, annars kommer modellen inte att kapas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Ställer in cylinderns höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Ställer in höjdsegmenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Ställer in vertextransformationsoffseten för den nedre sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Ställer in vertextransformationsoffseten för den övre sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Ställer in ett värde som indikerar om denna [Cylinder](../../com.aspose.threed/cylinder) är öppen i ändarna. Standardvärdet är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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


Ställer in de radiella segmenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Ställer in radien på cylinderns nedre lock.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Ställer in radien på cylinderns övre lock.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Ställer in om denna geometri kan ta emot skugga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Ställer in skjuvtransformen för den nedre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Ställer in skjuvtransformen för den övre sidan, vektorn lagrar (x-axel, z-axel) skjuvvärdet som mäts i radian, standardvärdet är (0, 0)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Ställer in längden på theta. Standardvärdet är 2\\u03c0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Ställer in theta‑starten. Standardvärdet är 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Konvertera aktuellt objekt till mesh

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

