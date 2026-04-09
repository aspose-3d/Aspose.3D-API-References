---
title: KeyframeSequence
second_title: Aspose.3D for Java API-referens
description: Sekvensen av nyckelramar beskriver transformationen av ett samplat värde över tid.
type: docs
weight: 90
url: /sv/java/com.aspose.threed/keyframesequence/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class KeyframeSequence extends A3DObject implements Iterable<KeyFrame>
```

Sekvensen av nyckelramar beskriver transformationen av ett samplat värde över tid.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [KeyframeSequence(String name)](#KeyframeSequence-java.lang.String-) | Initierar en ny instans av klassen [KeyframeSequence](../../com.aspose.threed/keyframesequence). |
| [KeyframeSequence()](#KeyframeSequence--) | Initierar en ny instans av klassen [KeyframeSequence](../../com.aspose.threed/keyframesequence). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Skapa en ny nyckelram med angivet värde |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Skapa en ny nyckelram med angivet värde |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getBindPoint()](#getBindPoint--) | Hämtar egenskapsbindningspunkten som äger denna kurva |
| [getClass()](#getClass--) |  |
| [getKeyFrames()](#getKeyFrames--) | Hämtar nyckelramarna för denna kurva. |
| [getName()](#getName--) | Hämtar namnet. |
| [getPostBehavior()](#getPostBehavior--) | Hämtar efterbeteendet som anger vad det samplade värdet ska vara efter den sista nyckelramen. |
| [getPreBehavior()](#getPreBehavior--) | Hämtar förbeteendet som anger vad det samplade värdet ska vara före den första nyckeln. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Hämtar enumeratorn för att traversera alla nyckelramar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [reset()](#reset--) | Tar bort alla nyckelramar och återställer efter-/förbeteendena. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyframeSequence(String name) {#KeyframeSequence-java.lang.String-}
```
public KeyframeSequence(String name)
```


Initierar en ny instans av klassen [KeyframeSequence](../../com.aspose.threed/keyframesequence).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn |

### KeyframeSequence() {#KeyframeSequence--}
```
public KeyframeSequence()
```


Initierar en ny instans av klassen [KeyframeSequence](../../com.aspose.threed/keyframesequence).

### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Skapa en ny nyckelram med angivet värde

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tid | double | Tidsposition (uppmätt i sekunder) |
| värde | float | Värdet vid denna tidsposition |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Skapa en ny nyckelram med angivet värde

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tid | double | Tidsposition (uppmätt i sekunder) |
| värde | float | Värdet vid denna tidsposition |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Interpoleringstypen för denna nyckelram |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Hämtar egenskapsbindningspunkten som äger denna kurva

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Hämtar nyckelramarna för denna kurva.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - nyckelramarna för denna kurva.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Hämtar efterbeteendet som anger vad det samplade värdet ska vara efter den sista nyckelramen.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Hämtar förbeteendet som anger vad det samplade värdet ska vara före den första nyckeln.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Hämtar enumeratorn för att traversera alla nyckelramar.

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
### reset() {#reset--}
```
public void reset()
```


Tar bort alla nyckelramar och återställer efter-/förbeteendena.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

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

