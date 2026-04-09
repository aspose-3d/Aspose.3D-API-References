---
title: MorphTargetDeformer
second_title: Aspose.3D for Java API-referentie
description: MorphTargetDeformer biedt per-vertex-animatie.
type: docs
weight: 108
url: /nl/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer biedt per-vertex animatie. MorphTargetDeformer organiseert alle targets via [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel), elk kanaal kan meerdere targets organiseren. Een veelvoorkomende toepassing van morph target deformer is het toepassen van gezichtsuitdrukkingen op een personage. Meer details zijn te vinden op https://en.wikipedia.org/wiki/Morph\\_target\\_animation
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | Initialiseert een nieuw exemplaar van de klasse [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Haalt het gewicht op voor de gegeven geometrie, dit is een verkorte manier om het gewicht voor een target te wijzigen zonder het kanaal te benaderen. |
| [getChannels()](#getChannels--) | Haalt alle kanalen op die in deze deformer zitten |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Haalt de naam op. |
| [getOwner()](#getOwner--) | Geeft de geometrie die deze Deformer bezit. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Stelt het gewicht in voor de gegeven geometrie, dit is een verkorte manier om het gewicht voor een target te wijzigen zonder het kanaal te benaderen. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


Initialiseert een nieuw exemplaar van de klasse [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


Initialiseert een nieuw exemplaar van de klasse [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Haalt het gewicht op voor de gegeven geometrie, dit is een verkorte manier om het gewicht voor een target te wijzigen zonder het kanaal te benaderen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Doelgeometrie |

**Returns:**
double - Gewicht
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


Haalt alle kanalen op die in deze deformer zitten

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - alle kanalen die in deze deformer zitten
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


Geeft de geometrie die deze Deformer bezit.

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Stelt het gewicht in voor de gegeven geometrie, dit is een verkorte manier om het gewicht voor een target te wijzigen zonder het kanaal te benaderen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Doelgeometrie |
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

