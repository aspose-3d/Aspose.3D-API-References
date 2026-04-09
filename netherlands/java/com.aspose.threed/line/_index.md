---
title: Lijn
second_title: Aspose.3D for Java API-referentie
description: Een polyline is een pad gedefinieerd door een reeks punten met  en verbonden door   wat betekent dat het ook een reeks verbonden lijnsegmenten kan zijn.
type: docs
weight: 95
url: /nl/java/com.aspose.threed/line/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class Line extends Curve
```

Een polyline is een pad gedefinieerd door een reeks punten met [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints), en verbonden door [getSegments](../../com.aspose.threed/line\#getSegments), wat betekent dat het ook een reeks verbonden lijnsegmenten kan zijn. De lijn is meestal een lineair object, wat betekent dat het niet kan worden gebruikt om een kromme weer te geven; om een kromme weer te geven, gebruik [NurbsCurve](../../com.aspose.threed/nurbscurve).
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Line()](#Line--) | Initialiseert een nieuw exemplaar van de [Line](../../com.aspose.threed/line) klasse. |
| [Line(String name)](#Line-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Line](../../com.aspose.threed/line) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [fromPoints(Vector3[] points)](#fromPoints-com.aspose.threed.Vector3...-) | Construeer een [Line](../../com.aspose.threed/line) exemplaar uit een reeks punten. |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Haalt de kleur van de lijn op, standaardwaarde is wit(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Geeft alle controlepunten terug |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getName()](#getName--) | Haalt de naam op. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getSegments()](#getSegments--) | Haalt de segmenten van de lijn op |
| [getVisible()](#getVisible--) | Geeft aan of de geometrie zichtbaar is |
| [hashCode()](#hashCode--) |  |
| [makeDefaultIndices()](#makeDefaultIndices--) | Genereer de reeks 0,1,2,3....[Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints).Length-1 naar [getSegments](../../com.aspose.threed/line\#getSegments) zodat de ControlPoints als één lijn kunnen worden gebruikt |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Stelt de kleur van de lijn in, standaardwaarde is wit(1, 1, 1) |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setVisible(boolean value)](#setVisible-boolean-) | Stelt in of de geometrie zichtbaar is |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Line() {#Line--}
```
public Line()
```


Initialiseert een nieuw exemplaar van de [Line](../../com.aspose.threed/line) klasse.

### Line(String name) {#Line-java.lang.String-}
```
public Line(String name)
```


Initialiseert een nieuw exemplaar van de [Line](../../com.aspose.threed/line) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |

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
### fromPoints(Vector3[] points) {#fromPoints-com.aspose.threed.Vector3...-}
```
public static Line fromPoints(Vector3[] points)
```


Construeer een [Line](../../com.aspose.threed/line) exemplaar uit een reeks punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Line](../../com.aspose.threed/line)
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
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSegments() {#getSegments--}
```
public List<int[]> getSegments()
```


Haalt de segmenten van de lijn op

**Returns:**
java.util.List<int[]> - de segmenten van de lijn
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Geeft aan of de geometrie zichtbaar is

**Returns:**
boolean - of de geometrie zichtbaar is
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### makeDefaultIndices() {#makeDefaultIndices--}
```
public void makeDefaultIndices()
```


Genereer de reeks 0,1,2,3....[Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints).Length-1 naar [getSegments](../../com.aspose.threed/line\#getSegments) zodat de ControlPoints als één lijn kunnen worden gebruikt

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

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Stelt in of de geometrie zichtbaar is

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

