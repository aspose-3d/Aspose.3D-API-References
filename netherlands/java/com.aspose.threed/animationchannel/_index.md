---
title: AnimationChannel
second_title: Aspose.3D for Java API-referentie
description: Een kanaal koppelt het componentveld van een eigenschap aan een reeks keyframe‑sequenties
type: docs
weight: 13
url: /nl/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Een kanaal koppelt het componentveld van een eigenschap aan een reeks keyframe‑sequenties
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Maak een nieuw keyframe met opgegeven waarde. |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Maak een nieuw keyframe met opgegeven waarde. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBindPoint()](#getBindPoint--) | Haalt het eigenschap-bindpunt op dat deze curve bezit. |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Haalt het type van het componentveld op |
| [getDefaultValue()](#getDefaultValue--) | Haalt de Default‑waarde van het kanaal op. |
| [getKeyFrames()](#getKeyFrames--) | Haalt de keyframes van deze curve op. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Haalt de bijbehorende keyframe‑sequentie op binnen dit kanaal |
| [getName()](#getName--) | Haalt de naam op. |
| [getPostBehavior()](#getPostBehavior--) | Haalt het postgedrag op dat aangeeft wat de bemonsterde waarde moet zijn na het laatste keyframe. |
| [getPreBehavior()](#getPreBehavior--) | Haalt het pregedrag op dat aangeeft wat de bemonsterde waarde moet zijn vóór het eerste keyframe. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Haalt de enumerator op om alle keyframes te doorlopen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [reset()](#reset--) | Verwijdert alle keyframes en reset de post-/pre-gedragingen. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Stelt de standaardwaarde van het kanaal in. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Haalt de bijbehorende keyframe‑sequentie op binnen dit kanaal |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Maak een nieuw keyframe met opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tijd | double | Tijdpositie (gemeten in seconden) |
| waarde | float | De waarde op deze tijdpositie |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Maak een nieuw keyframe met opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tijd | double | Tijdpositie (gemeten in seconden) |
| waarde | float | De waarde op deze tijdpositie |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Het interpolatietype van dit keyframe |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Haalt het eigenschap-bindpunt op dat deze curve bezit.

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


Haalt het type van het componentveld op

**Returns:**
java.lang.Class<?> - het type van het componentveld
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Haalt de Default‑waarde van het kanaal op. Als een kanaal geen gekoppelde keyframe‑sequenties heeft, wordt de standaardwaarde gebruikt tijdens de animatie‑evaluatie. Een praktisch voorbeeld: animatie animeert alleen de x‑coördinaat van een knooppunt, de y‑ en z‑coördinaten blijven ongewijzigd, dan wordt de standaardwaarde gebruikt tijdens de volledige translatie‑evaluatie.

**Returns:**
java.lang.Object - de Default‑waarde van het kanaal. Als een kanaal geen gekoppelde keyframe‑sequenties heeft, wordt de standaardwaarde gebruikt tijdens de animatie‑evaluatie. Een praktisch voorbeeld: animatie animeert alleen de x‑coördinaat van een knooppunt, de y‑ en z‑coördinaten blijven ongewijzigd, dan wordt de standaardwaarde gebruikt tijdens de volledige translatie‑evaluatie.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Haalt de keyframes van deze curve op.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - de keyframes van deze curve.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Haalt de bijbehorende keyframe‑sequentie op binnen dit kanaal

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Haalt het postgedrag op dat aangeeft wat de bemonsterde waarde moet zijn na het laatste keyframe.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Haalt het pregedrag op dat aangeeft wat de bemonsterde waarde moet zijn vóór het eerste keyframe.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Haalt de enumerator op om alle keyframes te doorlopen.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


Verwijdert alle keyframes en reset de post-/pre-gedragingen.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Stelt de Default‑waarde van het kanaal in. Als een kanaal geen gekoppelde keyframe‑sequenties heeft, wordt de standaardwaarde gebruikt tijdens de animatie‑evaluatie. Een praktisch voorbeeld: animatie animeert alleen de x‑coördinaat van een knooppunt, de y‑ en z‑coördinaten blijven ongewijzigd, dan wordt de standaardwaarde gebruikt tijdens de volledige translatie‑evaluatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object | Nieuwe waarde |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Haalt de bijbehorende keyframe‑sequentie op binnen dit kanaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Nieuwe waarde |

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

