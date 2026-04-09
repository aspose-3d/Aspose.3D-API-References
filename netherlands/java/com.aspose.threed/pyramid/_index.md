---
title: Piramide
second_title: Aspose.3D for Java API-referentie
description: Geparametriseerde piramide.
type: docs
weight: 142
url: /nl/java/com.aspose.threed/pyramid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Pyramid extends Primitive
```

Geparametriseerde piramide.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Pyramid()](#Pyramid--) | Maak een nieuw piramide-object met standaard bodemgebied (10, 10) en standaard hoogte (5) |
| [Pyramid(double xbottom, double ybottom, double height)](#Pyramid-double-double-double-) | Maak een nieuw piramide-object met gespecificeerd bodemgebied |
| [Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-double-double-double-double-double-) | Maak een nieuw piramide-object met gespecificeerd bodemgebied, bovengebied en hoogte. |
| [Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-java.lang.String-double-double-double-double-double-) | Maak een nieuw piramide-object met gespecificeerd bodemgebied, bovengebied en hoogte. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBottomArea()](#getBottomArea--) | Oppervlakte van de onderkant |
| [getBottomOffset()](#getBottomOffset--) | Offset voor onderliggende hoekpunten |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getCastShadows()](#getCastShadows--) | Geeft aan of deze geometrie schaduwen kan werpen |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getHeight()](#getHeight--) | Hoogte van de piramide |
| [getName()](#getName--) | Haalt de naam op. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getReceiveShadows()](#getReceiveShadows--) | Geeft aan of deze geometrie schaduwen kan ontvangen. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getTopArea()](#getTopArea--) | Oppervlakte van de bovenkant |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setBottomArea(Vector2 value)](#setBottomArea-com.aspose.threed.Vector2-) | Oppervlakte van de onderkant |
| [setBottomOffset(Vector3 value)](#setBottomOffset-com.aspose.threed.Vector3-) | Offset voor onderliggende hoekpunten |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Stelt in of deze geometrie schaduwen kan werpen |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setHeight(double value)](#setHeight-double-) | Hoogte van de piramide |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Stelt in of deze geometrie schaduwen kan ontvangen. |
| [setTopArea(Vector2 value)](#setTopArea-com.aspose.threed.Vector2-) | Oppervlakte van de bovenkant |
| [toMesh()](#toMesh--) | Converteer huidig object naar mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pyramid() {#Pyramid--}
```
public Pyramid()
```


Maak een nieuw piramide-object met standaard bodemgebied (10, 10) en standaard hoogte (5)

### Pyramid(double xbottom, double ybottom, double height) {#Pyramid-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double height)
```


Maak een nieuw piramide-object met gespecificeerd bodemgebied

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xbottom | double | De lengte in x-richting van de onderkant |
| ybottom | double | De lengte in y-richting van de onderkant |
| hoogte | double | De hoogte van de piramide |

### Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-double-double-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)
```


Maak een nieuw piramide-object met gespecificeerd bodemgebied, bovengebied en hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xbottom | double | De lengte in x-richting van het bodemgebied |
| ybottom | double | De lengte in y-richting van het bodemgebied |
| xtop | double | De lengte in x-richting van het bovengebied |
| ytop | double | De lengte in y-richting van het bovengebied |
| hoogte | double | De hoogte van de piramide |

### Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-java.lang.String-double-double-double-double-double-}
```
public Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)
```


Maak een nieuw piramide-object met gespecificeerd bodemgebied, bovengebied en hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de piramide |
| xbottom | double | De lengte in x-richting van het bodemgebied |
| ybottom | double | De lengte in y-richting van het bodemgebied |
| xtop | double | De lengte in x-richting van het bovengebied |
| ytop | double | De lengte in y-richting van het bovengebied |
| hoogte | double | De hoogte van de piramide |

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
### getBottomArea() {#getBottomArea--}
```
public Vector2 getBottomArea()
```


Oppervlakte van de onderkant

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the bottom cap
### getBottomOffset() {#getBottomOffset--}
```
public Vector3 getBottomOffset()
```


Offset voor onderliggende hoekpunten

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Offset for bottom vertices
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Hoogte van de piramide

**Returns:**
double - Hoogte van de piramide
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
### getTopArea() {#getTopArea--}
```
public Vector2 getTopArea()
```


Oppervlakte van de bovenkant

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the top cap
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
### setBottomArea(Vector2 value) {#setBottomArea-com.aspose.threed.Vector2-}
```
public void setBottomArea(Vector2 value)
```


Oppervlakte van de onderkant

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setBottomOffset(Vector3 value) {#setBottomOffset-com.aspose.threed.Vector3-}
```
public void setBottomOffset(Vector3 value)
```


Offset voor onderliggende hoekpunten

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Hoogte van de piramide

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Stelt in of deze geometrie schaduwen kan ontvangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setTopArea(Vector2 value) {#setTopArea-com.aspose.threed.Vector2-}
```
public void setTopArea(Vector2 value)
```


Oppervlakte van de bovenkant

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

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

