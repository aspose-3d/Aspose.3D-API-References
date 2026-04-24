---
title: ShaderMaterial
second_title: Aspose.3D for Java API-referens
description: Ett shadermaterial möjliggör att beskriva materialet med en extern renderingsmotor eller shader-språk.
type: docs
weight: 164
url: /sv/java/com.aspose.threed/shadermaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class ShaderMaterial extends Material
```

En shadermaterial gör det möjligt att beskriva materialet med en extern renderingsmotor eller shader‑språk. [ShaderMaterial](../../com.aspose.threed/shadermaterial) använder [ShaderTechnique](../../com.aspose.threed/shadertechnique) för att beskriva de konkreta renderingsdetaljerna, och den mest lämpliga kommer att användas enligt den slutgiltiga renderingsplattformen. Till exempel kan din [ShaderMaterial](../../com.aspose.threed/shadermaterial)‑instans ha två tekniker, en definierad av HLSL och en annan definierad av GLSL. På icke‑Windows‑plattform bör GLSL användas istället för HLSL
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ShaderMaterial()](#ShaderMaterial--) | Initierar en ny instans av klassen [ShaderMaterial](../../com.aspose.threed/shadermaterial). |
| [ShaderMaterial(String name)](#ShaderMaterial-java.lang.String-) | Initierar en ny instans av klassen [ShaderMaterial](../../com.aspose.threed/shadermaterial). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en ambient texturkartläggning. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en diffus texturkartläggning. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en emissiv texturkartläggning. |
| [MAP_NORMAL](#MAP-NORMAL) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en normal texturkartläggning. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en spekulär texturkartläggning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Hämtar namnet. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getTechniques()](#getTechniques--) | Hämtar alla tillgängliga tekniker som definierats i detta material. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Hämtar texturen från den angivna platsen, den kan vara materialets egenskapsnamn eller shaderns parameternamn |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Hämtar enumeratorn för att enumerera interna texturplatser. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ställer in texturen till angiven plats |
| [toString()](#toString--) | Formaterar objekt till sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderMaterial() {#ShaderMaterial--}
```
public ShaderMaterial()
```


Initierar en ny instans av klassen [ShaderMaterial](../../com.aspose.threed/shadermaterial).

### ShaderMaterial(String name) {#ShaderMaterial-java.lang.String-}
```
public ShaderMaterial(String name)
```


Initierar en ny instans av klassen [ShaderMaterial](../../com.aspose.threed/shadermaterial).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en ambient texturkartläggning.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en diffus texturkartläggning.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en emissiv texturkartläggning.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en normal texturkartläggning.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en spekulär texturkartläggning.

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
### getTechniques() {#getTechniques--}
```
public List<ShaderTechnique> getTechniques()
```


Hämtar alla tillgängliga tekniker som definierats i detta material.

**Returns:**
java.util.List<com.aspose.threed.ShaderTechnique> - alla tillgängliga tekniker som definierats i detta material.
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Hämtar texturen från den angivna platsen, den kan vara materialets egenskapsnamn eller shaderns parameternamn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slotName | java.lang.String | Slotnamn. |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


Hämtar enumeratorn för att enumerera interna texturplatser.

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
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

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Ställer in texturen till angiven plats

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slotName | java.lang.String | Slotnamn. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Textur. **Exempel:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### toString() {#toString--}
```
public String toString()
```


Formaterar objekt till sträng

**Returns:**
java.lang.String - Objektsträng
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

