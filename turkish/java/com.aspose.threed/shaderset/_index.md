---
title: "ShaderSet"
second_title: "Aspose.3D for Java API Referansı"
description: "Her türlü malzeme için shader programları."
type: docs
weight: 166
url: /tr/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Her türlü malzeme için shader programları.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | [ShaderSet](../../com.aspose.threed/shaderset) örneğini oluşturun. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | Bu örneği yok edin ve tüm gölgelendirici programlarını serbest bırakın. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Gerekli gölgelendirici mevcut olmadığında yedek gölgelendiriciyi alır. |
| [getLambert()](#getLambert--) | Lambert malzemesini renderlamak için kullanılan gölgelendiriciyi alır. |
| [getPbr()](#getPbr--) | PBR malzemesini renderlamak için kullanılan gölgelendiriciyi alır. |
| [getPhong()](#getPhong--) | Phong malzemesini renderlamak için kullanılan gölgelendiriciyi alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Gerekli gölgelendirici mevcut olmadığında yedek gölgelendiriciyi ayarlar. |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Lambert malzemesini renderlamak için kullanılan gölgelendiriciyi ayarlar. |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | PBR malzemesini renderlamak için kullanılan gölgelendiriciyi ayarlar. |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Phong malzemesini renderlamak için kullanılan gölgelendiriciyi ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


[ShaderSet](../../com.aspose.threed/shaderset) örneğini oluşturun.

### close() {#close--}
```
public void close()
```


Bu örneği yok edin ve tüm gölgelendirici programlarını serbest bırakın.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


Gerekli gölgelendirici mevcut olmadığında yedek gölgelendiriciyi alır.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Lambert malzemesini renderlamak için kullanılan gölgelendiriciyi alır.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


PBR malzemesini renderlamak için kullanılan gölgelendiriciyi alır.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Phong malzemesini renderlamak için kullanılan gölgelendiriciyi alır.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


Gerekli gölgelendirici mevcut olmadığında yedek gölgelendiriciyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Yeni değer |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Lambert malzemesini renderlamak için kullanılan gölgelendiriciyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Yeni değer |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


PBR malzemesini renderlamak için kullanılan gölgelendiriciyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Yeni değer |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Phong malzemesini renderlamak için kullanılan gölgelendiriciyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Yeni değer |

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

