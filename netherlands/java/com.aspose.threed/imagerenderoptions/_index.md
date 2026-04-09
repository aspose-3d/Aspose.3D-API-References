---
title: ImageRenderOptions
second_title: Aspose.3D for Java API-referentie
description: Opties voor  en
type: docs
weight: 83
url: /nl/java/com.aspose.threed/imagerenderoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class ImageRenderOptions extends A3DObject
```

Opties voor [Scene](../../com.aspose.threed/scene) en [Scene](../../com.aspose.threed/scene)
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageRenderOptions()](#ImageRenderOptions--) | Initialiseer een instantie van [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getAssetDirectories()](#getAssetDirectories--) | Mappen die externe assets(zoals texturen) opslaan |
| [getBackgroundColor()](#getBackgroundColor--) | De achtergrondkleur van het renderresultaat. |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | Geeft aan of schaduwen moeten worden gerenderd. |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setAssetDirectories(ArrayList<String> value)](#setAssetDirectories-java.util.ArrayList-java.lang.String--) | Mappen die externe assets(zoals texturen) opslaan |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | De achtergrondkleur van het renderresultaat. |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | Stelt in of schaduwen moeten worden gerenderd. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageRenderOptions() {#ImageRenderOptions--}
```
public ImageRenderOptions()
```


Initialiseer een instantie van [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions)

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
### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


Mappen die externe assets(zoals texturen) opslaan

**Returns:**
java.util.ArrayList<java.lang.String> - Mappen die externe assets(zoals texturen) opslaan
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


De achtergrondkleur van het renderresultaat.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The background color of the render result.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableShadows() {#getEnableShadows--}
```
public boolean getEnableShadows()
```


Geeft aan of schaduwen moeten worden gerenderd.

**Returns:**
boolean - of schaduwen moeten worden gerenderd.
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
### setAssetDirectories(ArrayList<String> value) {#setAssetDirectories-java.util.ArrayList-java.lang.String--}
```
public void setAssetDirectories(ArrayList<String> value)
```


Mappen die externe assets(zoals texturen) opslaan

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.ArrayList<java.lang.String> | Nieuwe waarde |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


De achtergrondkleur van het renderresultaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


Stelt in of schaduwen moeten worden gerenderd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

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

