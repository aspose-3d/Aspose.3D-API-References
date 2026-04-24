---
title: Pose
second_title: Aspose.3D for Java API-referentie
description: De pose wordt gebruikt om de transformatie-matrix op te slaan wanneer de geometrie geskinnd is.
type: docs
weight: 135
url: /nl/java/com.aspose.threed/pose/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Pose extends A3DObject
```

De pose wordt gebruikt om de transformatie-matrix op te slaan wanneer de geometrie is geskinnd. De pose is een set van [BonePose](../../com.aspose.threed/bonepose), elke [BonePose](../../com.aspose.threed/bonepose) slaat de concrete transformatie-informatie van het botknooppunt op.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Pose(String name)](#Pose-java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse [Pose](../../com.aspose.threed/pose). |
| [Pose()](#Pose--) | Initialiseert een nieuw exemplaar van de klasse [Pose](../../com.aspose.threed/pose). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addBonePose(Node node, Matrix4 matrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Slaat de pose-transformatie-matrix op voor het opgegeven botknooppunt. |
| [addBonePose(Node node, Matrix4 matrix, boolean localMatrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-) | Slaat de pose-transformatie-matrix op voor het opgegeven botknooppunt. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getBonePoses()](#getBonePoses--) | Haalt alle [BonePose](../../com.aspose.threed/bonepose) op. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Haalt de naam op. |
| [getPoseType()](#getPoseType--) | Haalt het type van de pose op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setPoseType(PoseType value)](#setPoseType-com.aspose.threed.PoseType-) | Stelt het type van de pose in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pose(String name) {#Pose-java.lang.String-}
```
public Pose(String name)
```


Initialiseert een nieuw exemplaar van de klasse [Pose](../../com.aspose.threed/pose).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |

### Pose() {#Pose--}
```
public Pose()
```


Initialiseert een nieuw exemplaar van de klasse [Pose](../../com.aspose.threed/pose).

### addBonePose(Node node, Matrix4 matrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public void addBonePose(Node node, Matrix4 matrix)
```


Slaat de pose-transformatiematrix op voor het opgegeven botknooppunt. De globale transformatiematrix wordt geïmpliceerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Botknooppunt. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Transformatiematrix. |

### addBonePose(Node node, Matrix4 matrix, boolean localMatrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-}
```
public void addBonePose(Node node, Matrix4 matrix, boolean localMatrix)
```


Slaat de pose-transformatie-matrix op voor het opgegeven botknooppunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Botknooppunt. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Transformatiematrix. |
| localMatrix | boolean | Als ingesteld op  true  betekent dit dat de lokale matrix wordt gebruikt, anders betekent dit de globale matrix. |

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
### getBonePoses() {#getBonePoses--}
```
public List<BonePose> getBonePoses()
```


Haalt alle [BonePose](../../com.aspose.threed/bonepose) op.

**Returns:**
java.util.List<com.aspose.threed.BonePose> - alle [BonePose](../../com.aspose.threed/bonepose).
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
### getPoseType() {#getPoseType--}
```
public PoseType getPoseType()
```


Haalt het type van de pose op.

**Returns:**
[PoseType](../../com.aspose.threed/posetype) - the type of the pose.
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setPoseType(PoseType value) {#setPoseType-com.aspose.threed.PoseType-}
```
public void setPoseType(PoseType value)
```


Stelt het type van de pose in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PoseType](../../com.aspose.threed/posetype) | Nieuwe waarde |

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

