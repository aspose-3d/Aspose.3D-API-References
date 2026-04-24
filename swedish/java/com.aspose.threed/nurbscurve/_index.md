---
title: NurbsCurve
second_title: Aspose.3D for Java API-referens
description: NURBS-kurva är en kurva som representeras av NURBS (Non-uniform rational basis spline). En NURBS-kurva definieras av dess en uppsättning viktade kontrollpunkter och en ... W-komponenten i kontrollpunkten används som kontrollpunktsvikt, oavsett vad det är för ...
type: docs
weight: 112
url: /sv/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Initierar en ny instans av klassen [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Initierar en ny instans av klassen [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Utvärdera NURBS‑kurvan |
| [evaluate(int steps)](#evaluate-int-) | Utvärdera NURBS‑kurvan |
| [evaluateAt(double u)](#evaluateAt-double-) | Utvärdera kurvans punkt vid angiven position |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getBoundingBox()](#getBoundingBox--) | Hämtar den omgivande lådan för den aktuella enheten i dess objektrumskoordinatsystem. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Hämtar färgen på linjen, standardvärdet är vit(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Hämtar alla kontrollpunkter |
| [getCurveType()](#getCurveType--) | Hämtar kurvans typ. |
| [getDegree()](#getDegree--) | Hämtar graden för en NURBS‑kurva, graden definieras som Order - 1 |
| [getDimension()](#getDimension--) | Hämtar kurvans dimension. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |
| [getExcluded()](#getExcluded--) | Hämtar om denna enhet ska exkluderas vid export. |
| [getKnotVectors()](#getKnotVectors--) | Hämtar knutvektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS‑kurvan. |
| [getMultiplicity()](#getMultiplicity--) | Hämtar multipliciteten. |
| [getName()](#getName--) | Hämtar namnet. |
| [getOrder()](#getOrder--) | Hämtar ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan. |
| [getParentNode()](#getParentNode--) | Hämtar den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [getParentNodes()](#getParentNodes--) | Hämtar alla föräldranoder, en enhet kan fästas vid flera föräldranoder för geometrisk instansering |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getRational()](#getRational--) | Hämtar om den är rationell, detta värde indikerar om denna [NurbsCurve](../../com.aspose.threed/nurbscurve) är en rationell spline eller icke‑rationell spline. |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Ställer in färgen på linjen, standardvärdet är vit(1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Ställer in kurvans typ. |
| [setDegree(int value)](#setDegree-int-) | Ställer in graden för en NURBS‑kurva, graden definieras som Order - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Ställer in kurvans dimension. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ställer in om denna enhet ska exkluderas vid export. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setOrder(int value)](#setOrder-int-) | Ställer in ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ställer in den första föräldranoden, om den första föräldranoden sätts, kommer denna enhet att frikopplas från andra föräldranoder. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setRational(boolean value)](#setRational-boolean-) | Ställer in om den är rationell, detta värde indikerar om denna [NurbsCurve](../../com.aspose.threed/nurbscurve) är en rationell spline eller icke‑rationell spline. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Initierar en ny instans av klassen [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Initierar en ny instans av klassen [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Utvärdera NURBS‑kurvan

**Returns:**
com.aspose.threed.Vector4[] - Punkter i kurvan
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Utvärdera NURBS‑kurvan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| steg | int | Utvärderingsfrekvensen mellan två närliggande knutar, standardvärdet är 20 |

**Returns:**
com.aspose.threed.Vector4[] - Punkter i kurvan
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Utvärdera kurvans punkt vid angiven position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| u | double | Positionen i kurvan, mellan 0 och 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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


Hämtar färgen på linjen, standardvärdet är vit(1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Hämtar alla kontrollpunkter

**Returns:**
java.util.List<com.aspose.threed.Vector4> - all control points
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Hämtar kurvans typ.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Hämtar graden för en NURBS‑kurva, graden definieras som Order - 1

**Returns:**
int - graden för en NURBS‑kurva, graden definieras som Order - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Hämtar kurvans dimension.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Hämtar nyckeln för enhetens renderare som är registrerad i renderaren

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Hämtar om denna enhet ska exkluderas vid export.

**Returns:**
boolean - om denna enhet ska exkluderas vid export.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Hämtar knutvektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS‑kurvan.

**Returns:**
java.util.List<java.lang.Double> - knutvektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS‑kurvan.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Hämtar multipliciteten.

**Returns:**
java.util.List<java.lang.Integer> - multipliciteten.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Hämtar ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan.

**Returns:**
int - ordningen för en NURBS-kurva, den definierar antalet närliggande kontrollpunkter som påverkar varje given punkt på kurvan.
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
### getRational() {#getRational--}
```
public boolean getRational()
```


Hämtar om den är rationell, detta värde indikerar om denna [NurbsCurve](../../com.aspose.threed/nurbscurve) är en rationell spline eller icke‑rationell spline. Icke‑rationell B-spline är ett specialfall av rationella B-splines.

**Returns:**
boolean - om den är rationell, detta värde indikerar om denna [NurbsCurve](../../com.aspose.threed/nurbscurve) är en rationell spline eller icke‑rationell spline. Icke‑rationell B-spline är ett specialfall av rationella B-splines.
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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Ställer in färgen på linjen, standardvärdet är vit(1, 1, 1)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Ställer in kurvans typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nytt värde |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Ställer in graden för en NURBS‑kurva, graden definieras som Order - 1

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Ställer in kurvans dimension.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Nytt värde **Kommentarer:** För en [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) kurva är z‑komponenten i kontrollpunkten oanvänd. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ställer in om denna enhet ska exkluderas vid export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Ställer in ordningen för en NURBS‑kurva, den definierar antalet närliggande kontrollpunkter som påverkar en given punkt på kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Ställer in om den är rationell, detta värde indikerar om denna [NurbsCurve](../../com.aspose.threed/nurbscurve) är en rationell spline eller icke‑rationell spline. Icke‑rationell B-spline är ett specialfall av rationella B-splines.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

