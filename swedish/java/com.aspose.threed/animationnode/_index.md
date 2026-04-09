---
title: AnimationNode
second_title: Aspose.3D for Java API-referens
description: Aspose.3Ds stöder animationshierarki; varje animation kan bestå av flera animationer och animationers nyckelramdefinition.
type: docs
weight: 15
url: /sv/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D stöder animationshierarki, varje animation kan bestå av flera animationer och animationens nyckelramdefinition. [AnimationNode](../../com.aspose.threed/animationnode) definierar transformationen av ett egenskapsvärde över tid, till exempel kan animationsnoden användas för att kontrollera en nods transformation eller andra numeriska egenskaper hos ett [A3DObject](../../com.aspose.threed/a3dobject)-objekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Initierar en ny instans av klassen [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | Initierar en ny instans av klassen [AnimationNode](../../com.aspose.threed/animationnode). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Skapar en BindPoint baserat på egenskapens datatyp. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Hittar bindpunkten efter mål och namn. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Hämtar animationsbindpunkten för given egenskap. |
| [getBindPoints()](#getBindPoints--) | Hämtar de aktuella egenskapsbindpunkterna |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Hämtar nyckelramsekvensen för given egenskap. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Hämtar nyckelbildsekvensen för given egenskap och kanal. |
| [getName()](#getName--) | Hämtar namnet. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getSubAnimations()](#getSubAnimations--) | Hämtar delanimationsnoderna under aktuella animationer |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Initierar en ny instans av klassen [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Initierar en ny instans av klassen [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Skapar en BindPoint baserat på egenskapens datatyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Objekt. |
| propName | java.lang.String | Egenskapsnamn. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Hittar bindpunkten efter mål och namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Bindningspunktens mål att hitta. |
| namn | java.lang.String | Bindningspunktens namn att hitta. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Hämtar animationsbindpunkten för given egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | På vilket objekt bindningspunkten ska skapas. |
| propName | java.lang.String | Egenskapens namn. |
| skapa | boolean | Om inställt på  true  skapa bindningspunkten om den inte finns. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Hämtar de aktuella egenskapsbindpunkterna

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - de aktuella egenskapsbindningspunkterna
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


Hämtar nyckelramsekvensen för given egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | På vilken instans nyckelbildsekvensen ska skapas. |
| propName | java.lang.String | Egenskapens namn. |
| skapa | boolean | Om inställt på  true , skapa sekvensen om den inte finns. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Hämtar nyckelbildsekvensen för given egenskap och kanal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | På vilken instans nyckelbildsekvensen ska skapas. |
| propName | java.lang.String | Egenskapens namn. |
| channelName | java.lang.String | Kanalens namn. |
| skapa | boolean | Om inställt på  true  skapa animationssekvensen om den inte finns. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Hämtar delanimationsnoderna under aktuella animationer

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - delanimationsnoderna under aktuella animationer
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

