---
title: Cylinder
second_title: Aspose.3D for Java API-referentie
description: Geparameteriseerde Cilinder.
type: docs
weight: 40
url: /nl/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Geparameteriseerde cilinder. Het kan ook worden gebruikt om de kegel weer te geven wanneer een van radiusTop/radiusBottom nul is.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Cylinder()](#Cylinder--) | Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse. |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse. |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse. |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse. |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse. |
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
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Haalt op of de fan-achtige cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2\*PI, anders wordt het model niet gesneden. |
| [getHeight()](#getHeight--) | Haalt de hoogte van de cilinder op. |
| [getHeightSegments()](#getHeightSegments--) | Haalt de hoogtesegmenten op. |
| [getName()](#getName--) | Haalt de naam op. |
| [getOffsetBottom()](#getOffsetBottom--) | Haalt de vertices-transformatie-offset van de onderkant op. |
| [getOffsetTop()](#getOffsetTop--) | Haalt de vertices-transformatie-offset van de bovenkant op. |
| [getOpenEnded()](#getOpenEnded--) | Haalt een waarde op die aangeeft of deze [Cylinder](../../com.aspose.threed/cylinder) open eindig is. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRadialSegments()](#getRadialSegments--) | Haalt de radiale segmenten op. |
| [getRadiusBottom()](#getRadiusBottom--) | Haalt de radius van de onderkap van de cilinder op. |
| [getRadiusTop()](#getRadiusTop--) | Haalt de straal van de bovenste kap van de cilinder op. |
| [getReceiveShadows()](#getReceiveShadows--) | Geeft aan of deze geometrie schaduwen kan ontvangen. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getShearBottom()](#getShearBottom--) | Haalt de schuiftransformatie van de onderkant op, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0) |
| [getShearTop()](#getShearTop--) | Haalt de schuiftransformatie van de bovenkant op, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0) |
| [getThetaLength()](#getThetaLength--) | Haalt de lengte van de theta op. |
| [getThetaStart()](#getThetaStart--) | Haalt de theta-start op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Stelt in of deze geometrie schaduwen kan werpen |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | Stelt in of een fan‑stijl cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2\*PI, anders wordt het model niet gesneden. |
| [setHeight(double value)](#setHeight-double-) | Stelt de hoogte van de cilinder in. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Sets the height segments. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Stelt de vertices-transformatie‑offset van de onderkant in. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Stelt de vertices-transformatie‑offset van de bovenkant in. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Stelt een waarde in die aangeeft of deze [Cylinder](../../com.aspose.threed/cylinder) open eindig is. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Stelt de radiale segmenten in. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Stelt de straal van de onderkap van de cilinder in. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Stelt de straal van de bovenkap van de cilinder in. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Stelt in of deze geometrie schaduwen kan ontvangen. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Stelt de schuiftransformatie van de onderkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0) |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Stelt de schuiftransformatie van de bovenkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0) |
| [setThetaLength(double value)](#setThetaLength-double-) | Sets the length of the theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Sets the theta start. |
| [toMesh()](#toMesh--) | Converteer huidig object naar mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse.

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | Straal van de boven- en onderkap. |
| hoogte | double | Hoogte. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radiusTop | double | Straal boven. |
| radiusBottom | double | Straal onder. |
| hoogte | double | Hoogte. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radiusTop | double | Straal van de bovenkap van de cilinder. |
| radiusBottom | double | Straal van de onderkap van de cilinder. |
| hoogte | double | Hoogte van de cilinder. |
| radialSegments | int | Radiale segmenten van zowel de boven- als ondercirkel.. |
| heightSegments | int | Height segments. |
| openEnded | boolean | Als ingesteld op true, zou de cilinder geen onder- of bovenkap hebben.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Initialiseert een nieuw exemplaar van de [Cylinder](../../com.aspose.threed/cylinder) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van dit object |
| radiusTop | double | Straal van de bovenkap van de cilinder. |
| radiusBottom | double | Straal van de onderkap van de cilinder. |
| hoogte | double | Hoogte van de cilinder. |
| radialSegments | int | Radiale segmenten van zowel de boven- als ondercirkel.. |
| heightSegments | int | Height segments. |
| openEnded | boolean | Als ingesteld op true, zou de cilinder geen onder- of bovenkap hebben.. |
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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Haalt op of de fan-achtige cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2\*PI, anders wordt het model niet gesneden.

**Returns:**
boolean - of een fan-achtige cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2\*PI, anders wordt het model niet gesneden.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van de cilinder op.

**Returns:**
double - de hoogte van de cilinder.
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
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Haalt de vertices-transformatie-offset van de onderkant op.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Haalt de vertices-transformatie-offset van de bovenkant op.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Haalt een waarde op die aangeeft of deze [Cylinder](../../com.aspose.threed/cylinder) open eindig is. De standaardwaarde is false.

**Returns:**
boolean - een waarde die aangeeft of deze [Cylinder](../../com.aspose.threed/cylinder) open eindig is. De standaardwaarde is false.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Haalt de radiale segmenten op.

**Returns:**
int - de radiale segmenten.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Haalt de radius van de onderkap van de cilinder op.

**Returns:**
double - de radius van de onderkap van de cilinder.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Haalt de straal van de bovenste kap van de cilinder op.

**Returns:**
double - de radius van de bovenkap van de cilinder.
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
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Haalt de schuiftransformatie van de onderkant op, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Haalt de schuiftransformatie van de bovenkant op, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Haalt de lengte van de theta op. De standaardwaarde is 2\\u03c0.

**Returns:**
double - de lengte van de theta. De standaardwaarde is 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Haalt de theta-start op. De standaardwaarde is 0.

**Returns:**
double - de theta-start. De standaardwaarde is 0.
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

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


Stelt in of een fan‑stijl cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2\*PI, anders wordt het model niet gesneden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Stelt de hoogte van de cilinder in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Stelt de vertices-transformatie‑offset van de onderkant in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Stelt de vertices-transformatie‑offset van de bovenkant in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Stelt een waarde in die aangeeft of deze [Cylinder](../../com.aspose.threed/cylinder) open eindig is. De standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Stelt de radiale segmenten in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Stelt de straal van de onderkap van de cilinder in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Stelt de straal van de bovenkap van de cilinder in.

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

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Stelt de schuiftransformatie van de onderkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Stelt de schuiftransformatie van de bovenkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Stelt de lengte van de theta in. De standaardwaarde is 2\\u03c0.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Stelt de theta-start in. De standaardwaarde is 0.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

