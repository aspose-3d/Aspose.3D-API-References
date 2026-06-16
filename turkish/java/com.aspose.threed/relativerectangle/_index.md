---
title: "RelativeRectangle"
second_title: "Aspose.3D for Java API Referansı"
description: "Göreceli dikdörtgen  Göreceli bileşen ile mutlak değer arasındaki formül:  Ölçek  Referans Genişliği  offset  Eğer mutlak bir değer temsil etmesini istiyorsak, tüm ölçek alanlarını sıfır bırakın ve bunun yerine offset alanlarını kullanın."
type: docs
weight: 147
url: /tr/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Göreceli dikdörtgen Göreceli bileşen ile mutlak değer arasındaki formül: Scale \* (Reference Width) + offset. Bu yüzden mutlak bir değeri temsil etmesini istiyorsak, tüm ölçek alanlarını sıfır bırakın ve bunun yerine offset alanlarını kullanın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Bir [RelativeRectangle](../../com.aspose.threed/relativerectangle) oluştur |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Verilen parametrelerden alınan ölçek alanları ve tüm offset alanları sıfır olan bir [RelativeRectangle](../../com.aspose.threed/relativerectangle) oluştur |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Yükseklik için offset değerini alır |
| [getOffsetWidth()](#getOffsetWidth--) | Genişlik için offset değerini alır |
| [getOffsetX()](#getOffsetX--) | X koordinatı için offset değerini alır |
| [getOffsetY()](#getOffsetY--) | Y koordinatı için offset değerini alır |
| [getScaleHeight()](#getScaleHeight--) | Göreceli yükseklik |
| [getScaleWidth()](#getScaleWidth--) | Göreceli genişlik |
| [getScaleX()](#getScaleX--) | Göreceli X koordinatı |
| [getScaleY()](#getScaleY--) | Göreceli Y koordinatı |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Yükseklik için offset değerini ayarlar |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Genişlik için offset değerini ayarlar |
| [setOffsetX(int value)](#setOffsetX-int-) | X koordinatı için offset değerini ayarlar |
| [setOffsetY(int value)](#setOffsetY-int-) | Y koordinatı için offset değerini ayarlar |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Göreceli yükseklik |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Göreceli genişlik |
| [setScaleX(float value)](#setScaleX-float-) | Göreceli X koordinatı |
| [setScaleY(float value)](#setScaleY-float-) | Göreceli Y koordinatı |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Göreceli dikdörtgeni mutlak dikdörtgene dönüştür |
| [toString()](#toString--) | Bu örneğin değerini bir java.lang.String'e dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Bir [RelativeRectangle](../../com.aspose.threed/relativerectangle) oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | int |  |
| üst | int |  |
| genişlik | int |  |
| yükseklik | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


Mevcut örneği kopyala

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Verilen parametrelerden alınan ölçek alanları ve tüm offset alanları sıfır olan bir [RelativeRectangle](../../com.aspose.threed/relativerectangle) oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


Yükseklik için offset değerini alır

**Returns:**
int - yükseklik ofseti
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Genişlik için offset değerini alır

**Returns:**
int - genişlik ofseti
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


X koordinatı için offset değerini alır

**Returns:**
int - X koordinatı ofseti
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Y koordinatı için offset değerini alır

**Returns:**
int - Y koordinatı ofseti
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Göreceli yükseklik

**Returns:**
float - Göreceli yükseklik
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Göreceli genişlik

**Returns:**
float - Göreceli genişlik
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Göreceli X koordinatı

**Returns:**
float - Göreceli X koordinatı
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Göreceli Y koordinatı

**Returns:**
float - Göreceli Y koordinatı
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


Yükseklik için offset değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Genişlik için offset değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


X koordinatı için offset değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Y koordinatı için offset değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Göreceli yükseklik

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Göreceli genişlik

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Göreceli X koordinatı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Göreceli Y koordinatı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Göreceli dikdörtgeni mutlak dikdörtgene dönüştür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | int | Dikdörtgenin sol tarafı |
| üst | int | Dikdörtgenin üst tarafı |
| genişlik | int | Dikdörtgenin genişliği |
| yükseklik | int | Dikdörtgenin yüksekliği |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Bu örneğin değerini bir java.lang.String'e dönüştürür.

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

