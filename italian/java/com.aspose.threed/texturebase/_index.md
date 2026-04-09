---
title: TextureBase
second_title: Aspose.3D for Java API Reference
description: Classe base per tutte le texture concrete.
type: docs
weight: 185
url: /it/java/com.aspose.threed/texturebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureBase extends A3DObject
```

Classe base per tutte le texture concrete. Texture definisce l'aspetto e la sensazione di una superficie geometrica.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextureBase(String name)](#TextureBase-java.lang.String-) | Inizializza una nuova istanza della classe [TextureBase](../../com.aspose.threed/texturebase). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getAlpha()](#getAlpha--) | Ottiene il valore alpha predefinito della texture. Questo è valido quando il [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) è [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Il valore predefinito è 1.0, l'intervallo di valori valido è compreso tra 0 e 1. |
| [getAlphaSource()](#getAlphaSource--) | Ottiene se la texture definisce il canale alpha. |
| [getClass()](#getClass--) |  |
| [getMagFilter()](#getMagFilter--) | Ottiene il filtro per l'ingrandimento. |
| [getMinFilter()](#getMinFilter--) | Ottiene il filtro per la riduzione. |
| [getMipFilter()](#getMipFilter--) | Ottiene il filtro per il campionamento a livello di mip. |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getUVRotation()](#getUVRotation--) | Ottiene la rotazione della texture. |
| [getUVScale()](#getUVScale--) | Ottiene la scala UV. |
| [getUVTranslation()](#getUVTranslation--) | Ottiene la traslazione UV. |
| [getWrapModeU()](#getWrapModeU--) | Ottiene le modalità di avvolgimento texture in U. |
| [getWrapModeV()](#getWrapModeV--) | Ottiene le modalità di avvolgimento texture in V. |
| [getWrapModeW()](#getWrapModeW--) | Ottiene le modalità di avvolgimento texture in W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setAlpha(double value)](#setAlpha-double-) | Imposta il valore alpha predefinito della texture. Questo è valido quando il [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) è [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Il valore predefinito è 1.0, l'intervallo di valori valido è compreso tra 0 e 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Imposta se la texture definisce il canale alpha. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Imposta il filtro per l'ingrandimento. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Imposta il filtro per la riduzione. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Imposta il filtro per il campionamento dei livelli di mip. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRotation(double u, double v)](#setRotation-double-double-) | Imposta la rotazione UV. |
| [setScale(double u, double v)](#setScale-double-double-) | Imposta la scala UV. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Imposta la traslazione UV. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Imposta la rotazione della texture |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Imposta la scala UV. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Imposta la traslazione UV. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Imposta le modalità di avvolgimento della texture in U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Imposta le modalità di avvolgimento della texture in V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Imposta le modalità di avvolgimento della texture in W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBase(String name) {#TextureBase-java.lang.String-}
```
public TextureBase(String name)
```


Inizializza una nuova istanza della classe [TextureBase](../../com.aspose.threed/texturebase).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trova la proprietà. Può essere una proprietà dinamica (creata con CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata per nome).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | java.lang.String | Nome della proprietà. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Ottiene il valore alpha predefinito della texture. Questo è valido quando il [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) è [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Il valore predefinito è 1.0, l'intervallo di valori valido è compreso tra 0 e 1.

**Returns:**
double - il valore alpha predefinito della texture. Questo è valido quando il [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) è [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Il valore predefinito è 1.0, l'intervallo di valori valido è compreso tra 0 e 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Restituisce se la texture definisce il canale alpha. Il valore predefinito è [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Ottiene il filtro per l'ingrandimento.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Ottiene il filtro per la riduzione.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Ottiene il filtro per il campionamento a livello di mip.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Ottiene la collezione di tutte le proprietà.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Ottieni il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |

**Returns:**
java.lang.Object - Il valore della proprietà trovata
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Ottiene la rotazione della texture.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Ottiene la scala UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Ottiene la traslazione UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Ottiene le modalità di avvolgimento texture in U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Ottiene le modalità di avvolgimento texture in V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Ottiene le modalità di avvolgimento texture in W.

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


Rimuove una proprietà dinamica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Rimuove la proprietà specificata identificata per nome

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Imposta il valore alpha predefinito della texture. Questo è valido quando il [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) è [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Il valore predefinito è 1.0, l'intervallo di valori valido è compreso tra 0 e 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Imposta se la texture definisce il canale alpha. Il valore predefinito è [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Nuovo valore |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Imposta il filtro per l'ingrandimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuovo valore |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Imposta il filtro per la riduzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuovo valore |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Imposta il filtro per il campionamento dei livelli di mip.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Imposta il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |
| valore | java.lang.Object | Il valore della proprietà |

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Imposta la rotazione UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Imposta la scala UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Imposta la traslazione UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Imposta la rotazione della texture

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Imposta la scala UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Imposta la traslazione UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Imposta le modalità di avvolgimento della texture in U.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuovo valore |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Imposta le modalità di avvolgimento della texture in V.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuovo valore |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Imposta le modalità di avvolgimento della texture in W.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

