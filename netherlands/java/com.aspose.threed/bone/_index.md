---
title: Bot
second_title: Aspose.3D for Java API-referentie
description: Een bot definieert de subset van de controlepunten van de geometrie en bepaalt het blendgewicht voor elk controlepunt.
type: docs
weight: 20
url: /nl/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Een bot definieert de subset van de controlepunten van de geometrie en bepaalt het blendgewicht voor elk controlepunt. Het [Bone](../../com.aspose.threed/bone)-object kan niet direct worden gebruikt; een [SkinDeformer](../../com.aspose.threed/skindeformer)-instantie wordt gebruikt om de geometrie te deformeren, en [SkinDeformer](../../com.aspose.threed/skindeformer) wordt geleverd met een set botten, elk bot gekoppeld aan een knoop. OPMERKING: Een controlepunt van een geometrie kan aan meer dan één bot worden gekoppeld.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Initialiseert een nieuwe instantie van de [Bone](../../com.aspose.threed/bone)-klasse. |
| [Bone()](#Bone--) | Initialiseert een nieuwe instantie van de [Bone](../../com.aspose.threed/bone)-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [get(int index)](#get-int-) | Haalt het blendgewicht op van het opgegeven controlepunt |
| [getBoneTransform()](#getBoneTransform--) | Haalt de transformatiematrix op van het bot. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | De linkmodus van een bot verwijst naar de manier waarop een bot is verbonden of gekoppeld aan zijn bovenliggende bot binnen een hiërarchische structuur. |
| [getName()](#getName--) | Haalt de naam op. |
| [getNode()](#getNode--) | Haalt het knooppunt op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getTransform()](#getTransform--) | Haalt de transformatiematrix op van het knooppunt dat het bot bevat. |
| [getWeight(int index)](#getWeight-int-) | Haalt het gewicht op voor het controlepunt gespecificeerd door index |
| [getWeightCount()](#getWeightCount--) | Haalt het aantal gewichten op, dit wordt automatisch uitgebreid door [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [set(int index, double value)](#set-int-double-) | Stelt het menggewicht in van het gespecificeerde controlepunt |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Stelt de transformatiematrix van het bot in. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | De linkmodus van een bot verwijst naar de manier waarop een bot is verbonden of gekoppeld aan zijn bovenliggende bot binnen een hiërarchische structuur. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Stelt het knooppunt in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Stelt de transformatiematrix in van het knooppunt dat het bot bevat. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Stelt het gewicht in voor het controlepunt gespecificeerd door index |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Initialiseert een nieuwe instantie van de [Bone](../../com.aspose.threed/bone)-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |

### Bone() {#Bone--}
```
public Bone()
```


Initialiseert een nieuwe instantie van de [Bone](../../com.aspose.threed/bone)-klasse.

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Haalt het blendgewicht op van het opgegeven controlepunt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het gewicht |

**Returns:**
double - Het gewicht
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Haalt de transformatiematrix op van het bot.

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


De linkmodus van een bot verwijst naar de manier waarop een bot is verbonden of gekoppeld aan zijn bovenliggende bot binnen een hiërarchische structuur.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getNode() {#getNode--}
```
public Node getNode()
```


Haalt het knooppunt op. Het botknooppunt is het bot waaraan de huid is bevestigd, de [SkinDeformer](../../com.aspose.threed/skindeformer) zal het botknooppunt gebruiken om de verplaatsing van de controlepunten te beïnvloeden. Het botknooppunt heeft meestal een [Skeleton](../../com.aspose.threed/skeleton) gekoppeld, maar dit is niet vereist. Het gekoppelde [Skeleton](../../com.aspose.threed/skeleton) wordt meestal door DCC‑software gebruikt om het skelet aan de gebruiker te tonen.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Haalt de transformatiematrix op van het knooppunt dat het bot bevat.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Haalt het gewicht op voor het controlepunt gespecificeerd door index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het controlepunt |

**Returns:**
double - het gewicht op de gespecificeerde index, of 0 als de index ongeldig is
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Haalt het aantal gewichten op, dit wordt automatisch uitgebreid door [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - het aantal gewichten, dit wordt automatisch uitgebreid door [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Stelt het menggewicht in van het gespecificeerde controlepunt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het gewicht |
| waarde | double | Nieuwe waarde |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Stelt de transformatiematrix van het bot in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nieuwe waarde |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


De linkmodus van een bot verwijst naar de manier waarop een bot is verbonden of gekoppeld aan zijn bovenliggende bot binnen een hiërarchische structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Stelt het knooppunt in. Het botknooppunt is het bot waaraan de huid is bevestigd, de [SkinDeformer](../../com.aspose.threed/skindeformer) zal het botknooppunt gebruiken om de verplaatsing van de controlepunten te beïnvloeden. Het botknooppunt heeft meestal een [Skeleton](../../com.aspose.threed/skeleton) gekoppeld, maar dit is niet vereist. Het gekoppelde [Skeleton](../../com.aspose.threed/skeleton) wordt meestal door DCC‑software gebruikt om het skelet aan de gebruiker te tonen.

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Stelt de transformatiematrix in van het knooppunt dat het bot bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nieuwe waarde |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Stelt het gewicht in voor het controlepunt gespecificeerd door index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het controlepunt |
| gewicht | double | Nieuw gewicht |

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

