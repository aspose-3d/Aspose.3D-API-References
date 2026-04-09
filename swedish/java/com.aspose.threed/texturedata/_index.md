---
title: TextureData
second_title: Aspose.3D for Java API-referens
description: Denna klass innehåller rådata och formatdefinitionen för en textur.
type: docs
weight: 187
url: /sv/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Denna klass innehåller rådata och formatdefinitionen för en textur.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Konstruktor för [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Skapar en ny [TextureData](../../com.aspose.threed/texturedata) och allokerar bilddata. |
| [TextureData()](#TextureData--) | Konstruktor för [TextureData](../../com.aspose.threed/texturedata) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Läs in en textur från fil |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Läs in en textur från ström |
| [getBytesPerPixel()](#getBytesPerPixel--) | Antal byte per pixel |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Rå byte av bilddata |
| [getHeight()](#getHeight--) | Antal vertikala pixlar |
| [getName()](#getName--) | Hämtar namnet. |
| [getPixelFormat()](#getPixelFormat--) | Pixelns format |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getStride()](#getStride--) | Antal byte i en skannrad. |
| [getWidth()](#getWidth--) | Antal horisontella pixlar |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Mappa alla pixlar för läsning/skrivning |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mappa alla pixlar för läsning/skrivning i angivet pixelformat |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mappa pixlar adresserade av rektangel för läsning/skrivning i angivet pixelformat |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Spara texturdata i angivet bildformat |
| [save(String fileName)](#save-java.lang.String-) | Spara texturdata i bildfil |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Spara texturdata i bildfil |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Transformera pixelns layout till ett nytt pixelformat. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Konstruktor för [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int |  |
| höjd | int |  |
| radsteg | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| data | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Skapar en ny [TextureData](../../com.aspose.threed/texturedata) och allokerar bilddata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int |  |
| höjd | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Konstruktor för [TextureData](../../com.aspose.threed/texturedata)

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Läs in en textur från fil

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Läs in en textur från ström

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Antal byte per pixel

**Returns:**
int - Antal byte i en pixel
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


Rå byte av bilddata

**Returns:**
byte[] - Rå byte av pixeldata
### getHeight() {#getHeight--}
```
public int getHeight()
```


Antal vertikala pixlar

**Returns:**
int - Antal vertikala pixlar
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Pixelns format

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


Antal byte i en skannrad.

**Returns:**
int - Antal byte i en skannrad.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Antal horisontella pixlar

**Returns:**
int - Antal horisontella pixlar
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


Mappa alla pixlar för läsning/skrivning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Kartläge |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Mappa alla pixlar för läsning/skrivning i angivet pixelformat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Kartläge |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Pixelformat |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Mappa pixlar adresserade av rektangel för läsning/skrivning i angivet pixelformat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | Området av pixlar som ska nås |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Kartläge |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Pixelformat |

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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Spara texturdata i angivet bildformat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Strömmen som innehåller den sparade bilden |
| format | java.lang.String | Bildformat, vanligtvis filändelse |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Spara texturdata i bildfil

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamnet där bilden kommer att sparas. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Spara texturdata i bildfil

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamnet där bilden kommer att sparas. |
| format | java.lang.String | Bildformat för utdatafilen. |

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


Transformera pixelns layout till ett nytt pixelformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Målpixelformat |

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

