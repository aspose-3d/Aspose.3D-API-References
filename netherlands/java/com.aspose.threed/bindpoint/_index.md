---
title: BindPoint
second_title: Aspose.3D for Java API-referentie
description: Een  wordt meestal gecreëerd op een eigenschap van een object; sommige eigenschapstypen bevatten meerdere componentvelden (zoals een Vector3‑veld) die een kanaal voor elk componentveld genereren en het veld verbinden met één of meer keyframe‑sequentie‑instanties via de kanalen.
type: docs
weight: 19
url: /nl/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Een [BindPoint](../../com.aspose.threed/bindpoint) wordt meestal gecreëerd op een eigenschap van een object; sommige eigenschapstypen bevatten meerdere componentvelden (zoals een Vector3‑veld). [BindPoint](../../com.aspose.threed/bindpoint) genereert een kanaal voor elk componentveld en verbindt het veld met één of meer keyframe‑sequentie‑instanties via de kanalen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Initialiseert een nieuwe instantie van de klasse [BindPoint](../../com.aspose.threed/bindpoint). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Voegt de opgegeven kanaaleigenschap toe. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Voegt de opgegeven kanaaleigenschap toe. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Bind de keyframe‑sequentie aan het opgegeven kanaal |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Maakt een nieuwe curve aan en verbindt deze met het eerste kanaal van de curve‑mapping |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [get(String channelName)](#get-java.lang.String-) | Haalt kanaal op op basis van opgegeven naam |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Haalt kanaal op op basis van opgegeven naam |
| [getChannelsCount()](#getChannelsCount--) | Haalt het totale aantal eigenschapskanalen op dat is gedefinieerd in deze animatie‑curve‑mapping. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Haalt de eerste keyframe‑sequentie op in het opgegeven kanaal |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty()](#getProperty--) | Haalt de eigenschap op die is gekoppeld aan de CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [resetChannels()](#resetChannels--) | Leegt de eigenschapskanalen van deze animatie‑curve‑mapping. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Haalt de eigenschap op die is gekoppeld aan de CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) | Formatteert object naar string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Initialiseert een nieuwe instantie van de klasse [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | De scène die de animatie bevat. |
| prop | [Property](../../com.aspose.threed/property) | Eigenschap. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Voegt de opgegeven kanaaleigenschap toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |
| type | java.lang.Class<?> | Type. |
| waarde | java.lang.Object | Waarde. |

**Returns:**
boolean - true, als het kanaal is toegevoegd, anders false.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Voegt de opgegeven kanaaleigenschap toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |
| waarde | java.lang.Object | Waarde. |

**Returns:**
boolean - true, als het kanaal is toegevoegd, anders false.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Bind de keyframe‑sequentie aan het opgegeven kanaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelName | java.lang.String | Welk kanaal waaraan de keyframe‑sequentie wordt gebonden |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | De te binden keyframe‑sequentie |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Maakt een nieuwe curve aan en verbindt deze met het eerste kanaal van de curve‑mapping

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de nieuwe sequentie. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Haalt kanaal op op basis van opgegeven naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelName | java.lang.String | Kanaalnaam |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Haalt kanaal op op basis van opgegeven naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelName | java.lang.String | De te vinden kanaalnaam |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Haalt het totale aantal eigenschapskanalen op dat is gedefinieerd in deze animatie‑curve‑mapping.

**Returns:**
int - Het aantal kanalen.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


Haalt de eerste keyframe‑sequentie op in het opgegeven kanaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| channelName | java.lang.String | De te vinden kanaalnaam |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Haalt de eigenschap op die is gekoppeld aan de CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Leegt de eigenschapskanalen van deze animatie‑curve‑mapping.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Haalt de eigenschap op die is gekoppeld aan de CurveMapping

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Nieuwe waarde |

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


Formatteert object naar string

**Returns:**
java.lang.String - Objecttekenreeks
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

