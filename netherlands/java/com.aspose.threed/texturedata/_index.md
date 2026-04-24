---
title: TextureData
second_title: Aspose.3D for Java API-referentie
description: Deze klasse bevat de ruwe data en de formaatdefinitie van een textuur.
type: docs
weight: 187
url: /nl/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Deze klasse bevat de ruwe data en de formaatdefinitie van een textuur.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Constructor van [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Construeert een nieuwe [TextureData](../../com.aspose.threed/texturedata) en reserveert pixelgegevens. |
| [TextureData()](#TextureData--) | Constructor van [TextureData](../../com.aspose.threed/texturedata) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Laad een textuur vanaf bestand. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Laad een textuur vanaf stream. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Aantal bytes van een pixel |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Ruwe bytes van pixelgegevens |
| [getHeight()](#getHeight--) | Aantal verticale pixels |
| [getName()](#getName--) | Haalt de naam op. |
| [getPixelFormat()](#getPixelFormat--) | Het formaat van de pixel |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getStride()](#getStride--) | Aantal bytes van een scanregel. |
| [getWidth()](#getWidth--) | Aantal horizontale pixels |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Alle pixels in kaart brengen voor lezen/schrijven |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Alle pixels in kaart brengen voor lezen/schrijven in gegeven pixelindeling |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Pixels die door een rechthoek worden aangesproken in kaart brengen voor lezen/schrijven in gegeven pixelindeling |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Textuurgegevens opslaan in opgegeven afbeeldingsformaat |
| [save(String fileName)](#save-java.lang.String-) | Textuurgegevens opslaan in afbeeldingsbestand |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Textuurgegevens opslaan in afbeeldingsbestand |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Lay-out van pixel transformeren naar nieuw pixelformaat. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Constructor van [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int |  |
| hoogte | int |  |
| stride | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| gegevens | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Construeert een nieuwe [TextureData](../../com.aspose.threed/texturedata) en reserveert pixelgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int |  |
| hoogte | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Constructor van [TextureData](../../com.aspose.threed/texturedata)

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Laad een textuur vanaf bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Laad een textuur vanaf stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Aantal bytes van een pixel

**Returns:**
int - Aantal bytes van een pixel
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


Ruwe bytes van pixelgegevens

**Returns:**
byte[] - Ruwe bytes van pixelgegevens
### getHeight() {#getHeight--}
```
public int getHeight()
```


Aantal verticale pixels

**Returns:**
int - Aantal verticale pixels
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Het formaat van de pixel

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


Aantal bytes van een scanregel.

**Returns:**
int - Aantal bytes van een scanregel.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Aantal horizontale pixels

**Returns:**
int - Aantal horizontale pixels
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


Alle pixels in kaart brengen voor lezen/schrijven

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Kaartmodus |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Alle pixels in kaart brengen voor lezen/schrijven in gegeven pixelindeling

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Kaartmodus |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Pixelindeling |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Pixels die door een rechthoek worden aangesproken in kaart brengen voor lezen/schrijven in gegeven pixelindeling

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | Het gebied van pixels dat benaderd moet worden |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Kaartmodus |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Pixelindeling |

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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Textuurgegevens opslaan in opgegeven afbeeldingsformaat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | De stream die de opgeslagen afbeelding bevat |
| formaat | java.lang.String | Afbeeldingsformaat, meestal bestandsextensie |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Textuurgegevens opslaan in afbeeldingsbestand

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De bestandsnaam waar de afbeelding wordt opgeslagen. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Textuurgegevens opslaan in afbeeldingsbestand

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De bestandsnaam waar de afbeelding wordt opgeslagen. |
| formaat | java.lang.String | Afbeeldingsformaat van het uitvoerbestand. |

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
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


Lay-out van pixel transformeren naar nieuw pixelformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Doelpixelindeling |

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

