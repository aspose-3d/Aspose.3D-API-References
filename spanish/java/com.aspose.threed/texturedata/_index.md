---
title: TextureData
second_title: Referencia de API de Aspose.3D para Java
description: Esta clase contiene los datos sin procesar y la definición de formato de una textura.
type: docs
weight: 187
url: /es/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Esta clase contiene los datos sin procesar y la definición de formato de una textura.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Constructor de [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Construye un nuevo [TextureData](../../com.aspose.threed/texturedata) y asigna datos de píxeles. |
| [TextureData()](#TextureData--) | Constructor de [TextureData](../../com.aspose.threed/texturedata) |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Cargar una textura desde un archivo |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Cargar una textura desde un flujo |
| [getBytesPerPixel()](#getBytesPerPixel--) | Número de bytes de un píxel |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Bytes sin procesar de los datos del píxel |
| [getHeight()](#getHeight--) | Número de píxeles verticales |
| [getName()](#getName--) | Obtiene el nombre. |
| [getPixelFormat()](#getPixelFormat--) | Formato del píxel |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getStride()](#getStride--) | Número de bytes de una línea de escaneo. |
| [getWidth()](#getWidth--) | Número de píxeles horizontales |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Mapear todos los píxeles para lectura/escritura |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mapear todos los píxeles para lectura/escritura en el formato de píxel dado |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mapear píxeles dirigidos por rect para lectura/escritura en el formato de píxel dado |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Guardar datos de textura en el formato de imagen especificado |
| [save(String fileName)](#save-java.lang.String-) | Guardar datos de textura en un archivo de imagen |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Guardar datos de textura en un archivo de imagen |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Transformar la disposición del píxel al nuevo formato de píxel. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Constructor de [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int |  |
| altura | int |  |
| paso | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| datos | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Construye un nuevo [TextureData](../../com.aspose.threed/texturedata) y asigna datos de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int |  |
| altura | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Constructor de [TextureData](../../com.aspose.threed/texturedata)

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Cargar una textura desde un archivo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Cargar una textura desde un flujo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Número de bytes de un píxel

**Returns:**
int - Número de bytes de un píxel
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


Bytes sin procesar de los datos del píxel

**Returns:**
byte[] - Bytes sin procesar de datos de píxel
### getHeight() {#getHeight--}
```
public int getHeight()
```


Número de píxeles verticales

**Returns:**
int - Número de píxeles verticales
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Formato del píxel

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


Número de bytes de una línea de escaneo.

**Returns:**
int - Número de bytes de una línea de escaneo.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Número de píxeles horizontales

**Returns:**
int - Número de píxeles horizontales
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


Mapear todos los píxeles para lectura/escritura

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Modo de mapeo |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Mapear todos los píxeles para lectura/escritura en el formato de píxel dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Modo de mapeo |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Formato de píxel |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Mapear píxeles dirigidos por rect para lectura/escritura en el formato de píxel dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | El área de píxeles a la que se accederá |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Modo de mapeo |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Formato de píxel |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Guardar datos de textura en el formato de imagen especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | El flujo que contiene la imagen guardada |
| formato | java.lang.String | Formato de imagen, usualmente extensión de archivo |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Guardar datos de textura en un archivo de imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre de archivo donde se guardará la imagen. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Guardar datos de textura en un archivo de imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre de archivo donde se guardará la imagen. |
| formato | java.lang.String | Formato de imagen del archivo de salida. |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


Transformar la disposición del píxel al nuevo formato de píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Formato de píxel de destino |

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

