---
title: Textuur
second_title: Aspose.3D for Java API-referentie
description: Deze klasse definieert de textuur uit een extern bestand.
type: docs
weight: 184
url: /nl/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

Deze klasse definieert de textuur uit een extern bestand.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Texture()](#Texture--) | Initialiseert een nieuw exemplaar van de [Texture](../../com.aspose.threed/texture) klasse. |
| [Texture(String name)](#Texture-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Texture](../../com.aspose.threed/texture) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getAlpha()](#getAlpha--) | Haalt de standaard alfa-waarde van de textuur op. Dit is geldig wanneer de [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) is [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) Standaardwaarde is 1.0, geldig bereik is tussen 0 en 1. |
| [getAlphaSource()](#getAlphaSource--) | Geeft aan of de textuur het alfac kanaal definieert. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Haalt de binaire inhoud van de textuur op. |
| [getEnableMipMap()](#getEnableMipMap--) | Geeft aan of de mipmap is ingeschakeld voor deze textuur. |
| [getFileName()](#getFileName--) | Haalt het gekoppelde textuurbestand op. |
| [getMagFilter()](#getMagFilter--) | Haalt het filter voor vergroting op. |
| [getMinFilter()](#getMinFilter--) | Haalt het filter voor verkleining op. |
| [getMipFilter()](#getMipFilter--) | Haalt het filter voor mip-niveau sampling op. |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getUVRotation()](#getUVRotation--) | Haalt de rotatie van de textuur op. |
| [getUVScale()](#getUVScale--) | Haalt de UV-schaal op. |
| [getUVTranslation()](#getUVTranslation--) | Haalt de UV-translatie op. |
| [getWrapModeU()](#getWrapModeU--) | Haalt de textuur wrap-modi op in U. |
| [getWrapModeV()](#getWrapModeV--) | Haalt de textuur wrap-modi op in V. |
| [getWrapModeW()](#getWrapModeW--) | Haalt de textuur wrap-modi op in W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setAlpha(double value)](#setAlpha-double-) | Stelt de standaard alfa-waarde van de textuur in. Dit is geldig wanneer de [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) is [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) Standaardwaarde is 1.0, geldig bereik is tussen 0 en 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Stelt in of de textuur het alfac kanaal definieert. |
| [setContent(byte[] value)](#setContent-byte---) | Stelt de binaire inhoud van de textuur in. |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | Stelt in of de mipmap is ingeschakeld voor deze textuur |
| [setFileName(String value)](#setFileName-java.lang.String-) | Stelt het gekoppelde textuurbestand in. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Stelt het filter voor vergroting in. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Stelt het filter voor verkleining in. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Stelt het filter voor mip-niveau sampling in. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRotation(double u, double v)](#setRotation-double-double-) | Stelt de UV-rotatie in. |
| [setScale(double u, double v)](#setScale-double-double-) | Stelt de UV-schaal in. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Stelt de UV-translatie in. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Stelt de rotatie van de textuur in |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Stelt de UV-schaal in. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Stelt de UV-translatie in. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Stelt de textuur-wrappingmodi in U in. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Stelt de textuur-wrappingmodi in V in. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Stelt de textuur-wrappingmodi in W in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


Initialiseert een nieuw exemplaar van de [Texture](../../com.aspose.threed/texture) klasse.

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


Initialiseert een nieuw exemplaar van de [Texture](../../com.aspose.threed/texture) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Haalt de standaard alfa-waarde van de textuur op. Dit is geldig wanneer de [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) is [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) Standaardwaarde is 1.0, geldig bereik is tussen 0 en 1.

**Returns:**
double - de standaard alfa-waarde van de textuur. Dit is geldig wanneer de [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) is [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Standaardwaarde is 1.0, geldig bereik is tussen 0 en 1.
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Haalt op of de textuur het alfa-kanaal definieert. Standaardwaarde is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE).

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContent() {#getContent--}
```
public byte[] getContent()
```


Haalt de binaire inhoud van de textuur op. De ingebedde textuurinhoud is optioneel; de gebruiker moet de textuur uit een extern bestand laden als deze ontbreekt.

**Returns:**
byte[] - de binaire inhoud van de textuur. De ingebedde textuurinhoud is optioneel; de gebruiker moet de textuur uit een extern bestand laden als deze ontbreekt.
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


Geeft aan of de mipmap is ingeschakeld voor deze textuur.

**Returns:**
boolean - of de mipmap is ingeschakeld voor deze textuur
### getFileName() {#getFileName--}
```
public String getFileName()
```


Haalt het gekoppelde textuurbestand op.

**Returns:**
java.lang.String - het gekoppelde textuurbestand.
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Haalt het filter voor vergroting op.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Haalt het filter voor verkleining op.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Haalt het filter voor mip-niveau sampling op.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Haalt de rotatie van de textuur op.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Haalt de UV-schaal op.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Haalt de UV-translatie op.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Haalt de textuur wrap-modi op in U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Haalt de textuur wrap-modi op in V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Haalt de textuur wrap-modi op in W.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Stelt de standaard alfa-waarde van de textuur in. Dit is geldig wanneer de [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) is [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) Standaardwaarde is 1.0, geldig bereik is tussen 0 en 1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Stelt in of de textuur het alfa-kanaal definieert. Standaardwaarde is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Nieuwe waarde |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Stelt de binaire inhoud van de textuur in. De ingebedde textuurinhoud is optioneel; de gebruiker moet de textuur uit een extern bestand laden als deze ontbreekt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] | Nieuwe waarde |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


Stelt in of de mipmap is ingeschakeld voor deze textuur

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Stelt het gekoppelde textuurbestand in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Stelt het filter voor vergroting in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nieuwe waarde |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Stelt het filter voor verkleining in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nieuwe waarde |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Stelt het filter voor mip-niveau sampling in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nieuwe waarde |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Stelt de UV-rotatie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Stelt de UV-schaal in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Stelt de UV-translatie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Stelt de rotatie van de textuur in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Stelt de UV-schaal in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Stelt de UV-translatie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Stelt de textuur-wrappingmodi in U in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nieuwe waarde |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Stelt de textuur-wrappingmodi in V in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nieuwe waarde |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Stelt de textuur-wrappingmodi in W in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nieuwe waarde |

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

