---
title: "DescriptorSetUpdater"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu sınıf, zincir işleminde  güncellemeye izin verir."
type: docs
weight: 42
url: /tr/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Bu sınıf, zincir işleminde [IDescriptorSet](../../com.aspose.threed/idescriptorset) güncellemeye izin verir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Tam tamponu mevcut tanımlayıcıya bağla |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Tamponu mevcut tanımlayıcı kümesine bağla |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Doku birimini mevcut tanımlayıcı kümesine bağla |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Tamponu belirtilen bağlama konumunda mevcut tanımlayıcı kümesine bağla. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Tamponu belirtilen bağlama konumunda mevcut tanımlayıcı kümesine bağla. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Doku birimini mevcut tanımlayıcı kümesine bağla |
| [close()](#close--) | Güncelleyiciyi serbest bırak ve değişiklikleri donanım cihazına gönder. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### bind(IBuffer buffer) {#bind-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(IBuffer buffer)
```


Tam tamponu mevcut tanımlayıcıya bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Tamponu mevcut tanımlayıcı kümesine bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Hangi tampon bağlanacak |
| ofset | int | Bağlanacak tamponun ofseti |
| boyut | int | Bağlanacak tamponun boyutu |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Doku birimini mevcut tanımlayıcı kümesine bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Bağlanacak doku birimi |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Tamponu belirtilen bağlama konumunda mevcut tanımlayıcı kümesine bağla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bağlama | int | Bağlama konumu |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Bağlanacak tüm tampon |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Tamponu belirtilen bağlama konumunda mevcut tanımlayıcı kümesine bağla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bağlama | int | Bağlama konumu |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Bağlanacak tampon |
| ofset | int | Bağlanacak tamponun ofseti |
| boyut | int | Bağlanacak tamponun boyutu |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Doku birimini mevcut tanımlayıcı kümesine bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bağlama | int | Bağlama konumu |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Bağlanacak doku birimi |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Güncelleyiciyi serbest bırak ve değişiklikleri donanım cihazına gönder.

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

