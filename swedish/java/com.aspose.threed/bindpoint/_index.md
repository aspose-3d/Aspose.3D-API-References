---
title: BindPoint
second_title: Aspose.3D for Java API-referens
description: En  skapas vanligtvis på ett objekts egenskap; vissa egenskapstyper innehåller flera komponentfält (t.ex. ett Vector3-fält) som genererar en kanal för varje komponentfält och kopplar fältet till en eller flera nyckelramsekvensinstanser via kanalerna.
type: docs
weight: 19
url: /sv/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

En [BindPoint](../../com.aspose.threed/bindpoint) skapas vanligtvis på ett objekts egenskap, vissa egenskapstyper innehåller flera komponentfält (t.ex. ett Vector3-fält), [BindPoint](../../com.aspose.threed/bindpoint) kommer att generera en kanal för varje komponentfält och kopplar fältet till en eller flera nyckelramsekvensinstans(er) via kanalerna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Initierar en ny instans av klassen [BindPoint](../../com.aspose.threed/bindpoint). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Lägger till den angivna kanal‑egenskapen. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Lägger till den angivna kanal‑egenskapen. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Bind nyckelramsekvensen till angiven kanal |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Skapar en ny kurva och ansluter den till den första kanalen i kurvavbildningen |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [get(String channelName)](#get-java.lang.String-) | Hämtar kanal efter angivet namn |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Hämtar kanal efter angivet namn |
| [getChannelsCount()](#getChannelsCount--) | Hämtar det totala antalet egenskapskanaler som definierats i denna animationskurvavbildning. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Hämtar den första nyckelramsekvensen i angiven kanal |
| [getName()](#getName--) | Hämtar namnet. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty()](#getProperty--) | Hämtar egenskapen som är associerad med CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [resetChannels()](#resetChannels--) | Tömmer egenskapskanalerna i denna animationskurvavbildning. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Hämtar egenskapen som är associerad med CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [toString()](#toString--) | Formaterar objekt till sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Initierar en ny instans av klassen [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Scenen som innehåller animationen. |
| prop | [Property](../../com.aspose.threed/property) | Egenskap. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Lägger till den angivna kanal‑egenskapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn. |
| type | java.lang.Class<?> | Typ. |
| värde | java.lang.Object | Värde. |

**Returns:**
boolean - true, om kanalen lades till, false annars.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Lägger till den angivna kanal‑egenskapen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn. |
| värde | java.lang.Object | Värde. |

**Returns:**
boolean - true, om kanalen lades till, false annars.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Bind nyckelramsekvensen till angiven kanal

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelName | java.lang.String | Vilken kanal nyckelramsekvensen kommer att bindas till |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Nyckelramsekvensen att binda |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Skapar en ny kurva och ansluter den till den första kanalen i kurvavbildningen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Det nya sekvensens namn. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String | Egenskapsnamn. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Hämtar kanal efter angivet namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelName | java.lang.String | Kanalnamn |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Hämtar kanal efter angivet namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelName | java.lang.String | Kanalnamnet att söka efter |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Hämtar det totala antalet egenskapskanaler som definierats i denna animationskurvavbildning.

**Returns:**
int - Antalet kanaler.
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


Hämtar den första nyckelramsekvensen i angiven kanal

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| channelName | java.lang.String | Kanalnamnet att söka efter |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Hämtar egenskapen som är associerad med CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Hämta värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Värdet på den hittade egenskapen
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


Tar bort en dynamisk egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Ta bort den angivna egenskapen identifierad med namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Tömmer egenskapskanalerna i denna animationskurvavbildning.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Hämtar egenskapen som är associerad med CurveMapping

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Nytt värde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ställer in värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |
| värde | java.lang.Object | Värdet på egenskapen |

### toString() {#toString--}
```
public String toString()
```


Formaterar objekt till sträng

**Returns:**
java.lang.String - Objektsträng
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

