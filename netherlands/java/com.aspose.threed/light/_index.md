---
title: Light
second_title: Aspose.3D for Java API-referentie
description: Het licht verlicht de scène.
type: docs
weight: 94
url: /nl/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

Het licht verlicht de scène.

De formule om de totale demping van licht te berekenen is:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Light()](#Light--) | Initialiseert een nieuw exemplaar van de [Light](../../com.aspose.threed/light) klasse. |
| [Light(String name)](#Light-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Light](../../com.aspose.threed/light) klasse. |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Initialiseert een nieuw exemplaar van de [Light](../../com.aspose.threed/light) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getAspect()](#getAspect--) | Haalt de beeldverhouding van het frustum op |
| [getBoundingBox()](#getBoundingBox--) | Haalt de omsluitende doos op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |
| [getCastLight()](#getCastLight--) | Haalt op of de huidige Light‑instantie andere objecten kan verlichten. |
| [getCastShadows()](#getCastShadows--) | Haalt op of het licht schaduwen kan werpen op andere objecten. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Haalt de kleur van het licht op |
| [getConstantAttenuation()](#getConstantAttenuation--) | Haalt de constante demping op om de totale demping van het licht te berekenen |
| [getDirection()](#getDirection--) | Haalt de richting op waar de camera naar kijkt. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer. |
| [getExcluded()](#getExcluded--) | Haalt op of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [getFalloff()](#getFalloff--) | Haalt de afschuifhoek van de kegel op (in graden). |
| [getFarPlane()](#getFarPlane--) | Haalt de afstand tot het verre vlak van het frustum op. |
| [getHotSpot()](#getHotSpot--) | Haalt de kegelhoek van de hotspot op (in graden). |
| [getIntensity()](#getIntensity--) | Haalt de intensiteit van het licht op, standaardwaarde is 100 |
| [getLightType()](#getLightType--) | Haalt het type van het licht op |
| [getLinearAttenuation()](#getLinearAttenuation--) | Haalt de lineaire demping op om de totale demping van het licht te berekenen |
| [getLookAt()](#getLookAt--) | Haalt de geïnteresseerde positie op waar de camera naar kijkt. |
| [getName()](#getName--) | Haalt de naam op. |
| [getNearPlane()](#getNearPlane--) | Haalt de afstand van het nabijvlak van de frustum op. |
| [getOrthoHeight()](#getOrthoHeight--) | Haalt de hoogte op wanneer de frustum in orthografische projectie staat. |
| [getParentNode()](#getParentNode--) | Haalt de eerste bovenliggende knoop op; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [getParentNodes()](#getParentNodes--) | Haalt alle bovenliggende knopen op; een entiteit kan aan meerdere bovenliggende knopen worden gekoppeld voor geometrie‑instantiatie. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Haalt de kwadratische demping op om de totale demping van het licht te berekenen |
| [getRotationMode()](#getRotationMode--) | Haalt de oriëntatiemodus van de frustum op. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getShadowColor()](#getShadowColor--) | Haalt de kleur van de schaduw op. |
| [getTarget()](#getTarget--) | Haalt het doel op waar de camera naar kijkt. |
| [getUp()](#getUp--) | Haalt de opwaartse richting van de camera op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setAspect(double value)](#setAspect-double-) | Stelt de beeldverhouding van de frustum in |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Stelt in of de huidige lichtinstantie andere objecten kan verlichten. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Stelt in of het licht schaduwen kan werpen op andere objecten. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Stelt de kleur van het licht in |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Stelt de constante demping in om de totale demping van het licht te berekenen |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Stelt de richting in waar de camera naar kijkt. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| [setFalloff(double value)](#setFalloff-double-) | Stelt de afnemingskegelhoek in (in graden). |
| [setFarPlane(double value)](#setFarPlane-double-) | Stelt de afstand van het verre vlak van de frustum in. |
| [setHotSpot(double value)](#setHotSpot-double-) | Stelt de kegelhoek van de hotspot in (in graden). |
| [setIntensity(double value)](#setIntensity-double-) | Stelt de intensiteit van het licht in, standaardwaarde is 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Stelt het type van het licht in |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Stelt de lineaire demping in om de totale demping van het licht te berekenen |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Stelt de geïnteresseerde positie in waar de camera naar kijkt. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setNearPlane(double value)](#setNearPlane-double-) | Stelt de afstand van de near plane van de frustum in. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Stelt de hoogte in wanneer de frustum zich in orthografische projectie bevindt. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Stelt de kwadratische demping in om de totale demping van het licht te berekenen |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Stelt de kleur van de schaduw in. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Stelt het doel in waar de camera naar kijkt. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Stelt de opwaartse richting van de camera in |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Initialiseert een nieuw exemplaar van de [Light](../../com.aspose.threed/light) klasse.

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Initialiseert een nieuw exemplaar van de [Light](../../com.aspose.threed/light) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Initialiseert een nieuw exemplaar van de [Light](../../com.aspose.threed/light) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |
| type | [LightType](../../com.aspose.threed/lighttype) | Nieuw type licht |

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
### getAspect() {#getAspect--}
```
public double getAspect()
```


Haalt de beeldverhouding van het frustum op

**Returns:**
double - de beeldverhouding van de frustum
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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Haalt op of de huidige Light‑instantie andere objecten kan verlichten.

**Returns:**
boolean - of de huidige lichtinstantie andere objecten kan verlichten.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Haalt op of het licht schaduwen kan werpen op andere objecten.

**Returns:**
boolean - of het licht schaduwen kan werpen op andere objecten.
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


Haalt de kleur van het licht op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Haalt de constante demping op om de totale demping van het licht te berekenen

**Returns:**
double - de constante demping om de totale demping van het licht te berekenen
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Haalt de richting op waar de camera naar kijkt. Wijzigingen in deze eigenschap zullen ook de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) en [getTarget](../../com.aspose.threed/frustum\#getTarget) beïnvloeden.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Haalt de afschuifhoek van de kegel op (in graden).

**Returns:**
double - de afschuifhoek van de kegel (in graden).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Haalt de afstand tot het verre vlak van het frustum op.

**Returns:**
double - de afstand van het far plane van de frustum.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Haalt de kegelhoek van de hotspot op (in graden).

**Returns:**
double - de hoek van de hotspotkegel (in graden).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Haalt de intensiteit van het licht op, standaardwaarde is 100

**Returns:**
double - de intensiteit van het licht, standaardwaarde is 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Haalt het type van het licht op

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Haalt de lineaire demping op om de totale demping van het licht te berekenen

**Returns:**
double - de lineaire demping om de totale demping van het licht te berekenen
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Haalt de geïnteresseerde positie op waar de camera naar kijkt.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Haalt de afstand van het nabijvlak van de frustum op.

**Returns:**
double - de afstand van het near plane van de frustum.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Haalt de hoogte op wanneer de frustum in orthografische projectie staat.

**Returns:**
double - de hoogte wanneer de frustum zich in orthografische projectie bevindt.
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Haalt de kwadratische demping op om de totale demping van het licht te berekenen

**Returns:**
double - de kwadratische demping om de totale demping van het licht te berekenen
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Haalt de oriëntatiemodus van de frustum op. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. Als de waarde [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) is, wordt de richting altijd berekend door de eigenschap [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Anders wordt de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) altijd berekend door de [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Haalt de kleur van de schaduw op.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Haalt het doel op waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) eigenschap komen.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Haalt de opwaartse richting van de camera op.

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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Stelt de beeldverhouding van de frustum in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Stelt in of de huidige lichtinstantie andere objecten kan verlichten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Stelt in of het licht schaduwen kan werpen op andere objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Stelt de kleur van het licht in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Stelt de constante demping in om de totale demping van het licht te berekenen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Stelt de richting in waar de camera naar kijkt. Wijzigingen in deze eigenschap zullen ook de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) en [getTarget](../../com.aspose.threed/frustum\#getTarget) beïnvloeden.

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Stelt de afnemingskegelhoek in (in graden).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Stelt de afstand van het verre vlak van de frustum in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Stelt de kegelhoek van de hotspot in (in graden).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Stelt de intensiteit van het licht in, standaardwaarde is 100

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Stelt het type van het licht in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Nieuwe waarde |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Stelt de lineaire demping in om de totale demping van het licht te berekenen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Stelt de geïnteresseerde positie in waar de camera naar kijkt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Stelt de afstand van de near plane van de frustum in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Stelt de hoogte in wanneer de frustum zich in orthografische projectie bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Stelt de kwadratische demping in om de totale demping van het licht te berekenen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer de [getTarget](../../com.aspose.threed/frustum\#getTarget) null is. Als de waarde [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) is, wordt de richting altijd berekend door de eigenschap [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Anders wordt de [getLookAt](../../com.aspose.threed/frustum\#getLookAt) altijd berekend door de [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nieuwe waarde |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Stelt de kleur van de schaduw in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Stelt het doel in waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de eigenschap [getLookAt](../../com.aspose.threed/frustum\#getLookAt) staan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Stelt de opwaartse richting van de camera in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

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

