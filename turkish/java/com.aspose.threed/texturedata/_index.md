---
title: "TextureData"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu sınıf bir dokunun ham verisini ve format tanımını içerir."
type: docs
weight: 187
url: /tr/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Bu sınıf bir dokunun ham verisini ve format tanımını içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | [TextureData](../../com.aspose.threed/texturedata) yapıcısı |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Yeni bir [TextureData](../../com.aspose.threed/texturedata) oluşturur ve piksel verilerini ayırır. |
| [TextureData()](#TextureData--) | [TextureData](../../com.aspose.threed/texturedata) yapıcısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Dosyadan bir doku yükle |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Akıştan bir doku yükle |
| [getBytesPerPixel()](#getBytesPerPixel--) | Bir pikselin bayt sayısı |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Piksel verisinin ham baytları |
| [getHeight()](#getHeight--) | Dikey piksel sayısı |
| [getName()](#getName--) | Adı alır. |
| [getPixelFormat()](#getPixelFormat--) | Pikselin biçimi |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getStride()](#getStride--) | Bir tarama satırının bayt sayısı. |
| [getWidth()](#getWidth--) | Yatay piksel sayısı |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Tüm pikselleri okuma/yazma için eşle |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Verilen piksel biçiminde tüm pikselleri okuma/yazma için eşle |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Dikdörtgen tarafından adreslenen pikselleri verilen piksel biçiminde okuma/yazma için eşle |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Doku verilerini belirtilen görüntü biçimine kaydet |
| [save(String fileName)](#save-java.lang.String-) | Doku verilerini görüntü dosyasına kaydet |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Doku verilerini görüntü dosyasına kaydet |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Piksel düzenini yeni piksel biçimine dönüştür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


[TextureData](../../com.aspose.threed/texturedata) yapıcısı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int |  |
| yükseklik | int |  |
| adım | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| veri | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Yeni bir [TextureData](../../com.aspose.threed/texturedata) oluşturur ve piksel verilerini ayırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int |  |
| yükseklik | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


[TextureData](../../com.aspose.threed/texturedata) yapıcısı

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty) veya native property(Identified by its name) olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyName | java.lang.String | Özellik adı. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Dosyadan bir doku yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Akıştan bir doku yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Bir pikselin bayt sayısı

**Returns:**
int - Bir pikselin bayt sayısı
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


Piksel verisinin ham baytları

**Returns:**
byte[] - Piksel verisinin ham baytları
### getHeight() {#getHeight--}
```
public int getHeight()
```


Dikey piksel sayısı

**Returns:**
int - Dikey piksel sayısı
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Pikselin biçimi

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Tüm özelliklerin koleksiyonunu alır.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Belirtilen özelliğin değerini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |

**Returns:**
java.lang.Object - Bulunan özelliğin değeri
### getStride() {#getStride--}
```
public int getStride()
```


Bir tarama satırının bayt sayısı.

**Returns:**
int - Bir tarama satırının bayt sayısı.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Yatay piksel sayısı

**Returns:**
int - Yatay piksel sayısı
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


Tüm pikselleri okuma/yazma için eşle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Eşleme modu |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Verilen piksel biçiminde tüm pikselleri okuma/yazma için eşle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Eşleme modu |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Piksel biçimi |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Dikdörtgen tarafından adreslenen pikselleri verilen piksel biçiminde okuma/yazma için eşle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | Erişilecek piksel alanı |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Eşleme modu |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Piksel biçimi |

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


Dinamik bir özelliği kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


İsimle tanımlanan belirtilen özelliği kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Doku verilerini belirtilen görüntü biçimine kaydet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Kaydedilen görüntüyü tutan akış |
| biçim | java.lang.String | Görüntü biçimi, genellikle dosya uzantısı |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Doku verilerini görüntü dosyasına kaydet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Görüntünün kaydedileceği dosya adı. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Doku verilerini görüntü dosyasına kaydet

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Görüntünün kaydedileceği dosya adı. |
| biçim | java.lang.String | Çıktı dosyasının görüntü biçimi. |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Belirtilen özelliğin değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |
| değer | java.lang.Object | Özelliğin değeri |

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


Piksel düzenini yeni piksel biçimine dönüştür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Hedef piksel biçimi |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

