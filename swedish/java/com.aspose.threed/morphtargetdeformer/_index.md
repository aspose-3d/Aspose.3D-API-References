---
title: MorphTargetDeformer
second_title: Aspose.3D for Java API-referens
description: MorphTargetDeformer tillhandahåller per-vertex-animering.
type: docs
weight: 108
url: /sv/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer tillhandahåller per-vertex‑animation. MorphTargetDeformer organiserar alla mål via [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel), varje kanal kan organisera flera mål. En vanlig användning av morph target‑deformer är att applicera ansiktsuttryck på en karaktär. Mer detaljer finns på https://en.wikipedia.org/wiki/Morph\\_target\\_animation
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | Initierar en ny instans av klassen [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | Initierar en ny instans av klassen [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Hämtar vikten för given geometri, detta är ett förkortat sätt att ändra vikten för mål utan att komma åt kanalen. |
| [getChannels()](#getChannels--) | Hämtar alla kanaler som finns i denna deformer |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Hämtar namnet. |
| [getOwner()](#getOwner--) | Hämtar geometrin som äger denna deformer |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Ställer in vikten för given geometri, detta är ett förkortat sätt att ändra vikten för mål utan att komma åt kanalen. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


Initierar en ny instans av klassen [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn. |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


Initierar en ny instans av klassen [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Hämtar vikten för given geometri, detta är ett förkortat sätt att ändra vikten för mål utan att komma åt kanalen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Målgeometri |

**Returns:**
double - Vikt
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


Hämtar alla kanaler som finns i denna deformer

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - alla kanaler som ingår i denna deformerare
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


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


Hämtar geometrin som äger denna deformer

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Ställer in vikten för given geometri, detta är ett förkortat sätt att ändra vikten för mål utan att komma åt kanalen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Målgeometri |
| värde | double | Nytt värde |

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

