---
title: Sphere
second_title: Aspose.3D for Java API-referentie
description: Geparameteriseerde bol.
type: docs
weight: 174
url: /nl/java/com.aspose.threed/sphere/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Sphere extends Primitive
```

Geparameteriseerde bol.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Sphere()](#Sphere--) | Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) met standaardstraal 1. |
| [Sphere(double radius)](#Sphere-double-) | Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) klasse met opgegeven straal. |
| [Sphere(double radius, int widthSegments, int heightSegments)](#Sphere-double-int-int-) | Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) klasse met opgegeven straal, breedtesegmenten en hoogtesegmenten. |
| [Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)](#Sphere-java.lang.String-double-int-int-double-double-double-double-) | Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getCastShadows()](#getCastShadows--) | Geeft aan of deze geometrie schaduwen kan werpen |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getHeightSegments()](#getHeightSegments--) | Haalt de hoogtesegmenten op. |
| [getName()](#getName--) | Haalt de naam op. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getPhiLength()](#getPhiLength--) | Haalt de lengte van de phi op. |
| [getPhiStart()](#getPhiStart--) | Haalt de phi-start op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRadius()](#getRadius--) | Haalt de straal van de bol op. |
| [getReceiveShadows()](#getReceiveShadows--) | Geeft aan of deze geometrie schaduwen kan ontvangen. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getThetaLength()](#getThetaLength--) | Haalt de lengte van de theta op. |
| [getThetaStart()](#getThetaStart--) | Haalt de theta-start op. |
| [getWidthSegments()](#getWidthSegments--) | Haalt de breedtesegmenten op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Stelt in of deze geometrie schaduwen kan werpen |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Sets the height segments. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setPhiLength(double value)](#setPhiLength-double-) | Sets the length of the phi. |
| [setPhiStart(double value)](#setPhiStart-double-) | Sets the phi start. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRadius(double value)](#setRadius-double-) | Sets the radius of the sphere. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Stelt in of deze geometrie schaduwen kan ontvangen. |
| [setThetaLength(double value)](#setThetaLength-double-) | Sets the length of the theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Sets the theta start. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Stelt de breedtesegmenten in. |
| [toMesh()](#toMesh--) | Converteer huidig object naar mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Sphere() {#Sphere--}
```
public Sphere()
```


Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) met standaardstraal 1.

### Sphere(double radius) {#Sphere-double-}
```
public Sphere(double radius)
```


Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) klasse met opgegeven straal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | Radius. |

### Sphere(double radius, int widthSegments, int heightSegments) {#Sphere-double-int-int-}
```
public Sphere(double radius, int widthSegments, int heightSegments)
```


Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) klasse met opgegeven straal, breedtesegmenten en hoogtesegmenten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | Radius of the sphere. |
| widthSegments | int | Breedte segmenten. |
| heightSegments | int | Height segments. |

### Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength) {#Sphere-java.lang.String-double-int-int-double-double-double-double-}
```
public Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)
```


Initialiseert een nieuw exemplaar van de [Sphere](../../com.aspose.threed/sphere) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |
| radius | double | Radius of the sphere. |
| widthSegments | int | Breedte segmenten. |
| heightSegments | int | Height segments. |
| phiStart | double | Phi start. |
| phiLength | double | Phi length. |
| thetaStart | double | Theta start. |
| thetaLength | double | Theta length. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Geeft aan of deze geometrie schaduwen kan werpen

**Returns:**
boolean - of deze geometrie schaduw kan werpen
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
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Haalt de hoogtesegmenten op.

**Returns:**
int - the height segments.
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
### getPhiLength() {#getPhiLength--}
```
public double getPhiLength()
```


Haalt de lengte van de phi op.

**Returns:**
double - the length of the phi.
### getPhiStart() {#getPhiStart--}
```
public double getPhiStart()
```


Haalt de phi-start op.

**Returns:**
double - the phi start.
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
### getRadius() {#getRadius--}
```
public double getRadius()
```


Haalt de straal van de bol op.

**Returns:**
double - the radius of the sphere.
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Geeft aan of deze geometrie schaduwen kan ontvangen.

**Returns:**
boolean - of deze geometrie schaduw kan ontvangen.
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Haalt de lengte van de theta op.

**Returns:**
double - the length of the theta.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Haalt de theta-start op.

**Returns:**
double - the theta start.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Haalt de breedtesegmenten op.

**Returns:**
int - de breedte segmenten.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Stelt in of deze geometrie schaduwen kan werpen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Sets the height segments.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

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

### setPhiLength(double value) {#setPhiLength-double-}
```
public void setPhiLength(double value)
```


Sets the length of the phi.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setPhiStart(double value) {#setPhiStart-double-}
```
public void setPhiStart(double value)
```


Sets the phi start.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

### setRadius(double value) {#setRadius-double-}
```
public void setRadius(double value)
```


Sets the radius of the sphere.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Stelt in of deze geometrie schaduwen kan ontvangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Sets the length of the theta.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Sets the theta start.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Stelt de breedtesegmenten in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Converteer huidig object naar mesh

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

