---
title: TextureData
second_title: Aspose.3D for Java API Reference
description: Questa classe contiene i dati grezzi e la definizione del formato di una texture.
type: docs
weight: 187
url: /it/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Questa classe contiene i dati grezzi e la definizione del formato di una texture.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Costruttore di [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Crea un nuovo [TextureData](../../com.aspose.threed/texturedata) e alloca i dati dei pixel. |
| [TextureData()](#TextureData--) | Costruttore di [TextureData](../../com.aspose.threed/texturedata) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Carica una texture da file |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Carica una texture da stream |
| [getBytesPerPixel()](#getBytesPerPixel--) | Numero di byte di un pixel |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Byte grezzi dei dati del pixel |
| [getHeight()](#getHeight--) | Numero di pixel verticali |
| [getName()](#getName--) | Ottiene il nome. |
| [getPixelFormat()](#getPixelFormat--) | Il formato del pixel |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getStride()](#getStride--) | Numero di byte di una scanline. |
| [getWidth()](#getWidth--) | Numero di pixel orizzontali |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Mappa tutti i pixel per lettura/scrittura |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mappa tutti i pixel per lettura/scrittura nel formato pixel specificato |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mappa i pixel indirizzati da rect per lettura/scrittura nel formato pixel specificato |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Salva i dati della texture nel formato immagine specificato |
| [save(String fileName)](#save-java.lang.String-) | Salva i dati della texture in un file immagine |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Salva i dati della texture in un file immagine |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Trasforma il layout del pixel in un nuovo formato pixel. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Costruttore di [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int |  |
| altezza | int |  |
| stride | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| dati | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Crea un nuovo [TextureData](../../com.aspose.threed/texturedata) e alloca i dati dei pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int |  |
| altezza | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Costruttore di [TextureData](../../com.aspose.threed/texturedata)

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Carica una texture da file

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Carica una texture da stream

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Numero di byte di un pixel

**Returns:**
int - Numero di byte di un pixel
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


Byte grezzi dei dati del pixel

**Returns:**
byte[] - Byte grezzi dei dati del pixel
### getHeight() {#getHeight--}
```
public int getHeight()
```


Numero di pixel verticali

**Returns:**
int - Numero di pixel verticali
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Il formato del pixel

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


Numero di byte di una scanline.

**Returns:**
int - Numero di byte di una scanline.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Numero di pixel orizzontali

**Returns:**
int - Numero di pixel orizzontali
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


Mappa tutti i pixel per lettura/scrittura

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Modalità di mappatura |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Mappa tutti i pixel per lettura/scrittura nel formato pixel specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Modalità di mappatura |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Formato pixel |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Mappa i pixel indirizzati da rect per lettura/scrittura nel formato pixel specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | L'area dei pixel da accedere |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Modalità di mappatura |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Formato pixel |

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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Salva i dati della texture nel formato immagine specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Il flusso che contiene l'immagine salvata |
| formato | java.lang.String | Formato immagine, solitamente estensione file |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Salva i dati della texture in un file immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome file del percorso in cui l'immagine sarà salvata. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Salva i dati della texture in un file immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome file del percorso in cui l'immagine sarà salvata. |
| formato | java.lang.String | Formato immagine del file di output. |

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


Trasforma il layout del pixel in un nuovo formato pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Formato pixel di destinazione |

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

