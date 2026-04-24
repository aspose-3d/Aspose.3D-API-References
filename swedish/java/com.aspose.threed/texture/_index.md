---
title: Textur
second_title: Aspose.3D for Java API-referens
description: Denna klass definierar texturen från en extern fil.
type: docs
weight: 184
url: /sv/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

Denna klass definierar texturen från en extern fil.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Texture()](#Texture--) | Initierar en ny instans av klassen [Texture](../../com.aspose.threed/texture). |
| [Texture(String name)](#Texture-java.lang.String-) | Initierar en ny instans av klassen [Texture](../../com.aspose.threed/texture). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getAlpha()](#getAlpha--) | Hämtar standard‑alfavärdet för texturen. Detta är giltigt när [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) är [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Standardvärdet är 1,0, giltigt värdeintervall är mellan 0 och 1. |
| [getAlphaSource()](#getAlphaSource--) | Hämtar om texturen definierar alfakanalen. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Hämtar det binära innehållet i texturen. |
| [getEnableMipMap()](#getEnableMipMap--) | Hämtar om mipmap är aktiverad för denna textur |
| [getFileName()](#getFileName--) | Hämtar den associerade texturfilen. |
| [getMagFilter()](#getMagFilter--) | Hämtar filtret för förstoring. |
| [getMinFilter()](#getMinFilter--) | Hämtar filtret för förminskning. |
| [getMipFilter()](#getMipFilter--) | Hämtar filtret för mip‑nivå‑sampling. |
| [getName()](#getName--) | Hämtar namnet. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getUVRotation()](#getUVRotation--) | Hämtar rotationen för texturen |
| [getUVScale()](#getUVScale--) | Hämtar UV‑skalan. |
| [getUVTranslation()](#getUVTranslation--) | Hämtar UV‑översättningen. |
| [getWrapModeU()](#getWrapModeU--) | Hämtar texturens omslagslägen i U. |
| [getWrapModeV()](#getWrapModeV--) | Hämtar texturens omslagslägen i V. |
| [getWrapModeW()](#getWrapModeW--) | Hämtar texturens omslagslägen i W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setAlpha(double value)](#setAlpha-double-) | Ställer in standard‑alfavärdet för texturen. Detta är giltigt när [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) är [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Standardvärdet är 1,0, giltigt värdeintervall är mellan 0 och 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Ställer in om texturen definierar alfakanalen. |
| [setContent(byte[] value)](#setContent-byte---) | Anger det binära innehållet i texturen. |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | Anger om mipmap är aktiverad för denna textur. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Anger den associerade texturfilen. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Anger filtret för förstoring. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Anger filtret för förminskning. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Anger filtret för mip-nivåprovning. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setRotation(double u, double v)](#setRotation-double-double-) | Anger UV-rotationen. |
| [setScale(double u, double v)](#setScale-double-double-) | Anger UV-skalan. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Anger UV-översättningen. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Anger rotationen av texturen. |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Anger UV-skalan. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Anger UV-översättningen. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Anger texturens omslagslägen i U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Anger texturens omslagslägen i V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Anger texturens omslagslägen i W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


Initierar en ny instans av klassen [Texture](../../com.aspose.threed/texture).

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


Initierar en ny instans av klassen [Texture](../../com.aspose.threed/texture).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn |

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Hämtar standard‑alfavärdet för texturen. Detta är giltigt när [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) är [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Standardvärdet är 1,0, giltigt värdeintervall är mellan 0 och 1.

**Returns:**
double - standard alfa‑värdet för texturen. Detta är giltigt när [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) är [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Standardvärdet är 1.0, giltigt värdeintervall är mellan 0 och 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Hämtar om texturen definierar alfa‑kanalen. Standardvärdet är [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

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


Hämtar det binära innehållet i texturen. Det inbäddade texturinnehållet är valfritt, användaren bör ladda texturen från en extern fil om detta saknas.

**Returns:**
byte[] - det binära innehållet i texturen. Det inbäddade texturinnehållet är valfritt, användaren bör ladda texturen från en extern fil om detta saknas.
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


Hämtar om mipmap är aktiverad för denna textur

**Returns:**
boolean - om mipmap är aktiverad för denna textur
### getFileName() {#getFileName--}
```
public String getFileName()
```


Hämtar den associerade texturfilen.

**Returns:**
java.lang.String - den associerade texturfilen.
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Hämtar filtret för förstoring.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Hämtar filtret för förminskning.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Hämtar filtret för mip‑nivå‑sampling.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Hämtar rotationen för texturen

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Hämtar UV‑skalan.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Hämtar UV‑översättningen.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Hämtar texturens omslagslägen i U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Hämtar texturens omslagslägen i V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Hämtar texturens omslagslägen i W.

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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Ställer in standard‑alfavärdet för texturen. Detta är giltigt när [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) är [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Standardvärdet är 1,0, giltigt värdeintervall är mellan 0 och 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Anger om texturen definierar alfa‑kanalen. Standardvärdet är [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Nytt värde |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Anger det binära innehållet i texturen. Det inbäddade texturinnehållet är valfritt, användaren bör ladda texturen från en extern fil om detta saknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] | Nytt värde |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


Anger om mipmap är aktiverad för denna textur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Anger den associerade texturfilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Anger filtret för förstoring.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nytt värde |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Anger filtret för förminskning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nytt värde |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Anger filtret för mip-nivåprovning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nytt värde |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Anger UV-rotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Anger UV-skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Anger UV-översättningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Anger rotationen av texturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Anger UV-skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Anger UV-översättningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Anger texturens omslagslägen i U.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nytt värde |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Anger texturens omslagslägen i V.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nytt värde |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Anger texturens omslagslägen i W.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nytt värde |

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

