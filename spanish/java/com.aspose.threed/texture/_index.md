---
title: Textura
second_title: Referencia de API de Aspose.3D para Java
description: Esta clase define la textura a partir de un archivo externo.
type: docs
weight: 184
url: /es/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

Esta clase define la textura a partir de un archivo externo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Texture()](#Texture--) | Inicializa una nueva instancia de la clase [Texture](../../com.aspose.threed/texture). |
| [Texture(String name)](#Texture-java.lang.String-) | Inicializa una nueva instancia de la clase [Texture](../../com.aspose.threed/texture). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getAlpha()](#getAlpha--) | Obtiene el valor alfa predeterminado de la textura. Esto es válido cuando el [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) es [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). El valor predeterminado es 1.0, el rango de valores válidos está entre 0 y 1. |
| [getAlphaSource()](#getAlphaSource--) | Obtiene si la textura define el canal alfa. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Obtiene el contenido binario de la textura. |
| [getEnableMipMap()](#getEnableMipMap--) | Obtiene si el mipmap está habilitado para esta textura |
| [getFileName()](#getFileName--) | Obtiene el archivo de textura asociado. |
| [getMagFilter()](#getMagFilter--) | Obtiene el filtro para magnificación. |
| [getMinFilter()](#getMinFilter--) | Obtiene el filtro para minificación. |
| [getMipFilter()](#getMipFilter--) | Obtiene el filtro para el muestreo de nivel mip. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getUVRotation()](#getUVRotation--) | Obtiene la rotación de la textura. |
| [getUVScale()](#getUVScale--) | Obtiene la escala UV. |
| [getUVTranslation()](#getUVTranslation--) | Obtiene la traducción UV. |
| [getWrapModeU()](#getWrapModeU--) | Obtiene los modos de ajuste de textura en U. |
| [getWrapModeV()](#getWrapModeV--) | Obtiene los modos de ajuste de textura en V. |
| [getWrapModeW()](#getWrapModeW--) | Obtiene los modos de ajuste de textura en W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setAlpha(double value)](#setAlpha-double-) | Establece el valor alfa predeterminado de la textura. Esto es válido cuando el [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) es [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). El valor predeterminado es 1.0, el rango de valores válidos está entre 0 y 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Establece si la textura define el canal alfa. |
| [setContent(byte[] value)](#setContent-byte---) | Establece el contenido binario de la textura. |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | Establece si el mipmap está habilitado para esta textura |
| [setFileName(String value)](#setFileName-java.lang.String-) | Establece el archivo de textura asociado. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Establece el filtro para la ampliación. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Establece el filtro para la minificación. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Establece el filtro para el muestreo de niveles mip. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setRotation(double u, double v)](#setRotation-double-double-) | Establece la rotación UV. |
| [setScale(double u, double v)](#setScale-double-double-) | Establece la escala UV. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Establece la traslación UV. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Establece la rotación de la textura |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Establece la escala UV. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Establece la traslación UV. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Establece los modos de envoltura de la textura en U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Establece los modos de envoltura de la textura en V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Establece los modos de envoltura de la textura en W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


Inicializa una nueva instancia de la clase [Texture](../../com.aspose.threed/texture).

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


Inicializa una nueva instancia de la clase [Texture](../../com.aspose.threed/texture).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | java.lang.String | Nombre de la propiedad. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Obtiene el valor alfa predeterminado de la textura. Esto es válido cuando el [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) es [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). El valor predeterminado es 1.0, el rango de valores válidos está entre 0 y 1.

**Returns:**
double - el valor alfa predeterminado de la textura. Esto es válido cuando el [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) es [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Valor predeterminado es 1.0, rango de valores válido entre 0 y 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Obtiene si la textura define el canal alfa. El valor predeterminado es [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

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


Obtiene el contenido binario de la textura. El contenido de textura incrustado es opcional, el usuario debe cargar la textura desde un archivo externo si falta.

**Returns:**
byte[] - el contenido binario de la textura. El contenido de textura incrustado es opcional, el usuario debe cargar la textura desde un archivo externo si falta.
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


Obtiene si el mipmap está habilitado para esta textura

**Returns:**
boolean - si el mipmap está habilitado para esta textura
### getFileName() {#getFileName--}
```
public String getFileName()
```


Obtiene el archivo de textura asociado.

**Returns:**
java.lang.String - el archivo de textura asociado.
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Obtiene el filtro para magnificación.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Obtiene el filtro para minificación.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Obtiene el filtro para el muestreo de nivel mip.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtiene la colección de todas las propiedades.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtiene el valor de la propiedad especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |

**Returns:**
java.lang.Object - El valor de la propiedad encontrada
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Obtiene la rotación de la textura.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Obtiene la escala UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Obtiene la traducción UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Obtiene los modos de ajuste de textura en U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Obtiene los modos de ajuste de textura en V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Obtiene los modos de ajuste de textura en W.

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


Elimina una propiedad dinámica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Elimina la propiedad especificada identificada por nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Establece el valor alfa predeterminado de la textura. Esto es válido cuando el [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) es [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). El valor predeterminado es 1.0, el rango de valores válidos está entre 0 y 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Establece si la textura define el canal alfa. El valor predeterminado es [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Nuevo valor |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Establece el contenido binario de la textura. El contenido de textura incrustado es opcional, el usuario debe cargar la textura desde un archivo externo si falta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] | Nuevo valor |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


Establece si el mipmap está habilitado para esta textura

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Establece el archivo de textura asociado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Establece el filtro para la ampliación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuevo valor |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Establece el filtro para la minificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuevo valor |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Establece el filtro para el muestreo de niveles mip.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Establece el valor de la propiedad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |
| valor | java.lang.Object | El valor de la propiedad |

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Establece la rotación UV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Establece la escala UV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Establece la traslación UV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Establece la rotación de la textura

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Establece la escala UV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Establece la traslación UV.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Establece los modos de envoltura de la textura en U.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuevo valor |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Establece los modos de envoltura de la textura en V.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuevo valor |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Establece los modos de envoltura de la textura en W.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nuevo valor |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

