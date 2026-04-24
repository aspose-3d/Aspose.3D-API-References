---
title: NurbsCurve
second_title: Aspose.3D for Java API-referentie
description: Een NURBS-curve is een curve die wordt weergegeven door een NURBS Non-uniform rational basis spline. Een NURBS-curve wordt gedefinieerd door zijn een verzameling gewogen ... en een ... Het w‑component in het controlepunt wordt gebruikt als gewicht van het controlepunt, wat het ook moge zijn, of
type: docs
weight: 112
url: /nl/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Initialiseert een nieuw exemplaar van de klasse [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Evalueer de NURBS-curve |
| [evaluate(int steps)](#evaluate-int-) | Evalueer de NURBS-curve |
| [evaluateAt(double u)](#evaluateAt-double-) | Evalueer het punt van de curve op de opgegeven positie |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Haalt de kleur van de lijn op, standaardwaarde is wit(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Geeft alle controlepunten terug |
| [getCurveType()](#getCurveType--) | Haalt het type van de curve op. |
| [getDegree()](#getDegree--) | Haalt de graad van een NURBS-curve op, de graad wordt gedefinieerd als Order - 1 |
| [getDimension()](#getDimension--) | Haalt de dimensie van de curve op. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getKnotVectors()](#getKnotVectors--) | Haalt de knoopvector op, dit is een reeks parameterwaarden die bepalen waar en hoe de controlepunten de NURBS-curve beïnvloeden. |
| [getMultiplicity()](#getMultiplicity--) | Haalt de multipliciteit op. |
| [getName()](#getName--) | Haalt de naam op. |
| [getOrder()](#getOrder--) | Haalt de orde van een NURBS-curve op, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRational()](#getRational--) | Haalt op of het rationaal is, deze waarde geeft aan of deze [NurbsCurve](../../com.aspose.threed/nurbscurve) een rationele spline of een niet-rationele spline is. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Stelt de kleur van de lijn in, standaardwaarde is wit(1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Stelt het type van de curve in. |
| [setDegree(int value)](#setDegree-int-) | Stelt de graad van een NURBS-curve in, de graad wordt gedefinieerd als Order - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Stelt de dimensie van de curve in. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setOrder(int value)](#setOrder-int-) | Stelt de orde van een NURBS-curve in, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRational(boolean value)](#setRational-boolean-) | Stelt in of het rationaal is, deze waarde geeft aan of deze [NurbsCurve](../../com.aspose.threed/nurbscurve) een rationele spline of een niet-rationele spline is. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Initialiseert een nieuw exemplaar van de klasse [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Initialiseert een nieuw exemplaar van de klasse [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Evalueer de NURBS-curve

**Returns:**
com.aspose.threed.Vector4[] - Punten in de curve
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Evalueer de NURBS-curve

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stappen | int | De evaluatiefrequentie tussen twee aangrenzende knopen, standaardwaarde is 20 |

**Returns:**
com.aspose.threed.Vector4[] - Punten in de curve
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Evalueer het punt van de curve op de opgegeven positie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| u | double | De positie in de curve, tussen 0 en 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Haalt de kleur van de lijn op, standaardwaarde is wit(1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Geeft alle controlepunten terug

**Returns:**
java.util.List<com.aspose.threed.Vector4> - alle controlepunten
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Haalt het type van de curve op.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Haalt de graad van een NURBS-curve op, de graad wordt gedefinieerd als Order - 1

**Returns:**
int - de graad van een NURBS-curve, de graad wordt gedefinieerd als Order - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Haalt de dimensie van de curve op.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren.

**Returns:**
boolean - of deze entiteit moet worden uitgesloten tijdens het exporteren.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Haalt de knoopvector op, dit is een reeks parameterwaarden die bepalen waar en hoe de controlepunten de NURBS-curve beïnvloeden.

**Returns:**
java.util.List<java.lang.Double> - de knoopvector, dit is een reeks parameterwaarden die bepalen waar en hoe de controlepunten de NURBS-curve beïnvloeden.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Haalt de multipliciteit op.

**Returns:**
java.util.List<java.lang.Integer> - de multipliciteit.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Haalt de orde van een NURBS-curve op, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden.

**Returns:**
int - de orde van een NURBS-curve, deze definieert het aantal nabije controlepunten die elk punt op de curve beïnvloeden.
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
### getRational() {#getRational--}
```
public boolean getRational()
```


Geeft aan of het rationaal is, deze waarde geeft aan of deze [NurbsCurve](../../com.aspose.threed/nurbscurve) een rationele spline is of een niet-rationele spline. Niet-rationele B-spline is een speciaal geval van rationele B-splines.

**Returns:**
boolean - of het rationaal is, deze waarde geeft aan of deze [NurbsCurve](../../com.aspose.threed/nurbscurve) een rationele spline is of een niet-rationele spline. Niet-rationele B-spline is een speciaal geval van rationele B-splines.
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort

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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Stelt de kleur van de lijn in, standaardwaarde is wit(1, 1, 1)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Stelt het type van de curve in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nieuwe waarde |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Stelt de graad van een NURBS-curve in, de graad wordt gedefinieerd als Order - 1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Stelt de dimensie van de curve in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Nieuwe waarde **Opmerkingen:** Voor een [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve wordt de z-component in het controlepunt niet gebruikt. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Stelt de orde van een NURBS-curve in, dit definieert het aantal naburige controlepunten die elk punt op de curve beïnvloeden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Stelt in of het rationaal is, deze waarde geeft aan of deze [NurbsCurve](../../com.aspose.threed/nurbscurve) een rationele spline is of een niet-rationele spline. Niet-rationele B-spline is een speciaal geval van rationele B-splines.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

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

