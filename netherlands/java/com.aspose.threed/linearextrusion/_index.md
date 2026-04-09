---
title: LinearExtrusion
second_title: Aspose.3D for Java API-referentie
description: Lineaire extrusie neemt een 2D-vorm als invoer en breidt de vorm uit in de derde dimensie.
type: docs
weight: 96
url: /nl/java/com.aspose.threed/linearextrusion/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class LinearExtrusion extends Entity implements IMeshConvertible
```

Linear extrusion neemt een 2D-vorm als invoer en breidt de vorm uit in de derde dimensie. **Voorbeeld:** De volgende code laat zien hoe je LinearExtrusion gebruikt om een vorm tot een solide model te extruderen.

```
//Create a new 3D scene
 		Scene scene = new Scene();
 
 		// Initialize the base profile to be extruded
 		var profile = new RectangleShape();
 		profile.setRoundingRadius(0.3);
 
 		// Create left node
 		var left = scene.getRootNode().createChildNode();
 		left.createChildNode(new Box(0.01, 3, 3));
 
 		// Create right node
 		var right = scene.getRootNode().createChildNode();
 		right.createChildNode(new Box(0.01, 3, 3));
 		right.getTransform().setTranslation(new Vector3(5, 0, 0));
 
 		//Perform linear extrusion on left node using center and slices property
 		var l = new LinearExtrusion(profile, 10);
 		l.setCenter(false);
 		l.setSlices(3);
 		l.setTwist(20);
 		left.createChildNode(l);
 
 		// Perform linear extrusion on left node using center and slices property
 		var r = new LinearExtrusion(profile, 10);
 		r.setCenter(true);
 		r.setSlices(3);
 		r.setTwist(90);
 		right.createChildNode(r);
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LinearExtrusion()](#LinearExtrusion--) | Constructor van instantie [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
| [LinearExtrusion(Profile shape, double height)](#LinearExtrusion-com.aspose.threed.Profile-double-) | Constructor van instantie [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getCenter()](#getCenter--) | Als deze waarde onwaar is, is het Z-bereik van de lineaire extrusie van 0 tot hoogte, anders is het bereik van -hoogte/2 tot hoogte/2. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | De richting van de extrusie, standaardwaarde is (0, 0, 1) |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getHeight()](#getHeight--) | De hoogte van de geëxtrudeerde geometrie, standaardwaarde is 1.0 |
| [getName()](#getName--) | Haalt de naam op. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getShape()](#getShape--) | De basisvorm die geëxtrudeerd moet worden. |
| [getSlices()](#getSlices--) | De segmenten van de gedraaide geëxtrudeerde geometrie, standaardwaarde is 1. |
| [getTwist()](#getTwist--) | Het aantal graden waardoor de vorm wordt geëxtrudeerd. |
| [getTwistOffset()](#getTwistOffset--) | De offset die wordt gebruikt bij het draaien, standaardwaarde is (0, 0, 0). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setCenter(boolean value)](#setCenter-boolean-) | Als deze waarde onwaar is, is het Z-bereik van de lineaire extrusie van 0 tot hoogte, anders is het bereik van -hoogte/2 tot hoogte/2. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | De richting van de extrusie, standaardwaarde is (0, 0, 1) |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setHeight(double value)](#setHeight-double-) | De hoogte van de geëxtrudeerde geometrie, standaardwaarde is 1.0 |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | De basisvorm die geëxtrudeerd moet worden. |
| [setSlices(int value)](#setSlices-int-) | De segmenten van de gedraaide geëxtrudeerde geometrie, standaardwaarde is 1. |
| [setTwist(double value)](#setTwist-double-) | Het aantal graden waardoor de vorm wordt geëxtrudeerd. |
| [setTwistOffset(Vector3 value)](#setTwistOffset-com.aspose.threed.Vector3-) | De offset die wordt gebruikt bij het draaien, standaardwaarde is (0, 0, 0). |
| [toMesh()](#toMesh--) | Converteer de extrusie naar een mesh. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearExtrusion() {#LinearExtrusion--}
```
public LinearExtrusion()
```


Constructor van instantie [LinearExtrusion](../../com.aspose.threed/linearextrusion).

### LinearExtrusion(Profile shape, double height) {#LinearExtrusion-com.aspose.threed.Profile-double-}
```
public LinearExtrusion(Profile shape, double height)
```


Constructor van instantie [LinearExtrusion](../../com.aspose.threed/linearextrusion).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Profile](../../com.aspose.threed/profile) |  |
| hoogte | double |  |

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
### getCenter() {#getCenter--}
```
public boolean getCenter()
```


Als deze waarde onwaar is, is het Z-bereik van de lineaire extrusie van 0 tot hoogte, anders is het bereik van -hoogte/2 tot hoogte/2.

**Returns:**
boolean - Als deze waarde onwaar is, is het Z-bereik van de lineaire extrusie van 0 tot hoogte, anders is het bereik van -hoogte/2 tot hoogte/2.
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


De richting van de extrusie, standaardwaarde is (0, 0, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The direction of extrusion, default value is (0, 0, 1)
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


De hoogte van de geëxtrudeerde geometrie, standaardwaarde is 1.0

**Returns:**
double - De hoogte van de geëxtrudeerde geometrie, standaardwaarde is 1.0
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
### getShape() {#getShape--}
```
public Profile getShape()
```


De basisvorm die geëxtrudeerd moet worden.

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base shape to be extruded.
### getSlices() {#getSlices--}
```
public int getSlices()
```


De segmenten van de gedraaide geëxtrudeerde geometrie, standaardwaarde is 1.

**Returns:**
int - De segmenten van de gedraaide geëxtrudeerde geometrie, standaardwaarde is 1.
### getTwist() {#getTwist--}
```
public double getTwist()
```


Het aantal graden waardoor de vorm wordt geëxtrudeerd.

**Returns:**
double - Het aantal graden waardoor de vorm wordt geëxtrudeerd.
### getTwistOffset() {#getTwistOffset--}
```
public Vector3 getTwistOffset()
```


De offset die wordt gebruikt bij het draaien, standaardwaarde is (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The offset that used in twisting, default value is (0, 0, 0).
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
### setCenter(boolean value) {#setCenter-boolean-}
```
public void setCenter(boolean value)
```


Als deze waarde onwaar is, is het Z-bereik van de lineaire extrusie van 0 tot hoogte, anders is het bereik van -hoogte/2 tot hoogte/2.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


De richting van de extrusie, standaardwaarde is (0, 0, 1)

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


De hoogte van de geëxtrudeerde geometrie, standaardwaarde is 1.0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


De basisvorm die geëxtrudeerd moet worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | Nieuwe waarde |

### setSlices(int value) {#setSlices-int-}
```
public void setSlices(int value)
```


De segmenten van de gedraaide geëxtrudeerde geometrie, standaardwaarde is 1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setTwist(double value) {#setTwist-double-}
```
public void setTwist(double value)
```


Het aantal graden waardoor de vorm wordt geëxtrudeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setTwistOffset(Vector3 value) {#setTwistOffset-com.aspose.threed.Vector3-}
```
public void setTwistOffset(Vector3 value)
```


De offset die wordt gebruikt bij het draaien, standaardwaarde is (0, 0, 0).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Converteer de extrusie naar een mesh.

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

