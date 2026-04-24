---
title: Ben
second_title: Aspose.3D for Java API-referens
description: Ett ben definierar delmängden av geometrins kontrollpunkter och definierar blandningsvikt för varje kontrollpunkt.
type: docs
weight: 20
url: /sv/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Ett ben definierar delmängden av geometrins kontrollpunkt och definierar blandningsvikt för varje kontrollpunkt. Objektet [Bone](../../com.aspose.threed/bone) kan inte användas direkt, en [SkinDeformer](../../com.aspose.threed/skindeformer)‑instans används för att deformera geometrin, och [SkinDeformer](../../com.aspose.threed/skindeformer) levereras med en uppsättning ben, där varje ben är länkat till en nod. OBS: En kontrollpunkt i en geometri kan vara bunden till mer än ett ben.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Initierar en ny instans av klassen [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | Initierar en ny instans av klassen [Bone](../../com.aspose.threed/bone). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [get(int index)](#get-int-) | Hämtar blandningsvikten för angiven kontrollpunkt |
| [getBoneTransform()](#getBoneTransform--) | Hämtar transformmatrisen för benet. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | Ett bens länkningsläge avser hur ett ben är anslutet eller länkat till sitt föräldrabens inom en hierarkisk struktur. |
| [getName()](#getName--) | Hämtar namnet. |
| [getNode()](#getNode--) | Hämtar noden. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getTransform()](#getTransform--) | Hämtar transformmatrisen för noden som innehåller benet. |
| [getWeight(int index)](#getWeight-int-) | Hämtar vikten för kontrollpunkten som anges med index |
| [getWeightCount()](#getWeightCount--) | Hämtar antalet vikter, detta utökas automatiskt av [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [set(int index, double value)](#set-int-double-) | Ställer in blandningsvikten för den angivna kontrollpunkten |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Ställer in transformmatrisen för benet. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | Ett bens länkningsläge avser hur ett ben är anslutet eller länkat till sitt föräldrabens inom en hierarkisk struktur. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Ställer in noden. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Ställer in transformmatrisen för noden som innehåller benet. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Ställer in vikten för kontrollpunkten som anges med index |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Initierar en ny instans av klassen [Bone](../../com.aspose.threed/bone).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn. |

### Bone() {#Bone--}
```
public Bone()
```


Initierar en ny instans av klassen [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Hämtar blandningsvikten för angiven kontrollpunkt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Viktens index |

**Returns:**
double - Vikten
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Hämtar transformmatrisen för benet.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


Ett bens länkningsläge avser hur ett ben är anslutet eller länkat till sitt föräldrabens inom en hierarkisk struktur.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getNode() {#getNode--}
```
public Node getNode()
```


Hämtar noden. Ben-noden är benet som huden är fäst vid, [SkinDeformer](../../com.aspose.threed/skindeformer) kommer att använda ben-noden för att påverka förskjutningen av kontrollpunkterna. Ben-noden har vanligtvis ett [Skeleton](../../com.aspose.threed/skeleton) bifogat, men det är inte obligatoriskt. Det bifogade [Skeleton](../../com.aspose.threed/skeleton) används vanligtvis av DCC-programvara för att visa skelettet för användaren.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Hämtar transformmatrisen för noden som innehåller benet.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Hämtar vikten för kontrollpunkten som anges med index

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Kontrollpunktens index |

**Returns:**
double - vikten vid angivet index, eller 0 om indexet är ogiltigt
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Hämtar antalet vikter, detta utökas automatiskt av [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - antalet vikter, detta utökas automatiskt av [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Ställer in blandningsvikten för den angivna kontrollpunkten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Viktens index |
| värde | double | Nytt värde |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Ställer in transformmatrisen för benet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nytt värde |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


Ett bens länkningsläge avser hur ett ben är anslutet eller länkat till sitt föräldrabens inom en hierarkisk struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Ställer in noden. Ben-noden är benet som huden är fäst vid, [SkinDeformer](../../com.aspose.threed/skindeformer) kommer att använda ben-noden för att påverka förskjutningen av kontrollpunkterna. Ben-noden har vanligtvis ett [Skeleton](../../com.aspose.threed/skeleton) bifogat, men det är inte obligatoriskt. Det bifogade [Skeleton](../../com.aspose.threed/skeleton) används vanligtvis av DCC-programvara för att visa skelettet för användaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nytt värde |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Ställer in transformmatrisen för noden som innehåller benet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nytt värde |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Ställer in vikten för kontrollpunkten som anges med index

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Kontrollpunktens index |
| vikt | double | Ny vikt |

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

