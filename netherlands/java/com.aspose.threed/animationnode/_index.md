---
title: AnimationNode
second_title: Aspose.3D for Java API-referentie
description: Aspose.3Ds ondersteunt animatiehiërarchie; elke animatie kan worden samengesteld uit meerdere animaties en animatie‑key-frame‑definities.
type: docs
weight: 15
url: /nl/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D ondersteunt animatiehiërarchie, elke animatie kan worden samengesteld uit meerdere animaties en de key-frame-definitie van animaties. [AnimationNode](../../com.aspose.threed/animationnode) definieert de transformatie van een eigenschapswaarde in de tijd; bijvoorbeeld, een animatienode kan worden gebruikt om de transformatie van een knoop of andere numerieke eigenschappen van een [A3DObject](../../com.aspose.threed/a3dobject) object te regelen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | Initialiseert een nieuw exemplaar van de klasse [AnimationNode](../../com.aspose.threed/animationnode). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Maakt een BindPoint aan op basis van het gegevenstype van de eigenschap. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Vindt het bindpunt op basis van doel en naam. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Haalt het animatie‑bindpunt op voor de opgegeven eigenschap. |
| [getBindPoints()](#getBindPoints--) | Haalt de huidige eigenschap‑bindpunten op. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Haalt de keyframe‑reeks op voor de opgegeven eigenschap. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Haalt de keyframe‑reeks op voor de opgegeven eigenschap en kanaal. |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getSubAnimations()](#getSubAnimations--) | Haalt de sub‑animatienodes op onder de huidige animaties |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Initialiseert een nieuw exemplaar van de klasse [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Initialiseert een nieuw exemplaar van de klasse [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Maakt een BindPoint aan op basis van het gegevenstype van de eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Object. |
| propName | java.lang.String | Eigenschapnaam. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Vindt het bindpunt op basis van doel en naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Doel van het bindpunt om te vinden. |
| naam | java.lang.String | Naam van het bindpunt om te vinden. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Haalt het animatie‑bindpunt op voor de opgegeven eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Op welk object het bindpunt moet worden aangemaakt. |
| propName | java.lang.String | De naam van de eigenschap. |
| maken | boolean | Indien ingesteld op  true  maak het bindpunt aan als het niet bestaat. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Haalt de huidige eigenschap‑bindpunten op.

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - de huidige bindpunten van de eigenschap
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Haalt de keyframe‑reeks op voor de opgegeven eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Op welke instantie de keyframe‑reeks moet worden aangemaakt. |
| propName | java.lang.String | De naam van de eigenschap. |
| maken | boolean | Indien ingesteld op  true , maak de reeks aan als deze niet bestaat. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Haalt de keyframe‑reeks op voor de opgegeven eigenschap en kanaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Op welke instantie de keyframe‑reeks moet worden aangemaakt. |
| propName | java.lang.String | De naam van de eigenschap. |
| channelName | java.lang.String | De naam van het kanaal. |
| maken | boolean | Indien ingesteld op  true  maak de animatiereeks aan als deze niet bestaat. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Haalt de sub‑animatienodes op onder de huidige animaties

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - de sub‑animatienodes onder de huidige animaties
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

