---
title: MorphTargetChannel
second_title: Aspose.3D for Java API-referentie
description: Een MorphTargetChannel wordt gebruikt door  om de doelgeometrieën te organiseren.
type: docs
weight: 107
url: /nl/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

Een MorphTargetChannel wordt gebruikt door [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) om de doelgeometrieën te organiseren. Sommige bestandsformaten zoals FBX ondersteunen meerdere kanalen parallel. **Remarks:** Gewicht ligt tussen 0 en 1.0, en het standaardgewicht voor het doel is 0.0;
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Initialiseert een nieuw exemplaar van de [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) klasse. |
| [MorphTargetChannel()](#MorphTargetChannel--) | Initialiseert een nieuw exemplaar van de [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Standaardgewicht voor morph-doelwit. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Haalt het gewicht op voor de opgegeven geometrie |
| [getChannelWeight()](#getChannelWeight--) | Haalt het deformer-gewicht op van dit kanaal. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getTargets()](#getTargets--) | Haalt alle doelwitten op die aan het kanaal zijn gekoppeld. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Haalt het gewicht op voor het opgegeven doelwit; als het doelwit niet tot dit kanaal behoort, wordt de standaardwaarde 0 geretourneerd. |
| [getWeights()](#getWeights--) | Haalt de volledige gewichtswaarden op van doelwitgeometrieën. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Stelt het gewicht in voor de opgegeven geometrie |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Stelt het deformer-gewicht in van dit kanaal. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Stelt het gewicht in voor het opgegeven doelwit, standaardwaarde is 1, bereik moet tussen 0~1 liggen |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Stelt het gewicht in voor het opgegeven doelwit, standaardwaarde is 1, bereik moet tussen 0~1 liggen |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Initialiseert een nieuw exemplaar van de [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Initialiseert een nieuw exemplaar van de [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) klasse.

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Standaardgewicht voor morph-doelwit.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Haalt het gewicht op voor de opgegeven geometrie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Doelwitgeometrie. |

**Returns:**
double - Gewicht
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Haalt het deformer-gewicht op van dit kanaal. Het gewicht ligt tussen 0,0 en 1,0

**Returns:**
double - het deformer-gewicht van dit kanaal. Het gewicht ligt tussen 0,0 en 1,0
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Haalt alle doelwitten op die aan het kanaal zijn gekoppeld.

**Returns:**
java.util.List<com.aspose.threed.Shape> - alle doelwitten die aan het kanaal zijn gekoppeld.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Haalt het gewicht op voor het opgegeven doelwit; als het doelwit niet tot dit kanaal behoort, wordt de standaardwaarde 0 geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Haalt de volledige gewichtswaarden op van doelwitgeometrieën.

**Returns:**
java.util.List<java.lang.Double> - de volledige gewichtswaarden van doelwitgeometrieën.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Stelt het gewicht in voor de opgegeven geometrie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Doelwitgeometrie. |
| waarde | double | Nieuwe waarde |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Stelt het deformer-gewicht in van dit kanaal. Het gewicht ligt tussen 0,0 en 1,0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Stelt het gewicht in voor het opgegeven doelwit, standaardwaarde is 1, bereik moet tussen 0~1 liggen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Stelt het gewicht in voor het opgegeven doelwit, standaardwaarde is 1, bereik moet tussen 0~1 liggen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| gewicht | double |  |

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

