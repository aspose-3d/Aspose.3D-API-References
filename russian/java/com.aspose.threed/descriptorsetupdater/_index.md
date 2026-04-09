---
title: DescriptorSetUpdater
second_title: Справочник API Aspose.3D для Java
description: Этот класс позволяет обновлять  в цепочечной операции.
type: docs
weight: 42
url: /ru/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Этот класс позволяет обновлять [IDescriptorSet](../../com.aspose.threed/idescriptorset) в цепочечной операции.
## Методы

| Метод | Описание |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Привязать весь буфер к текущему дескриптору |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Привязать буфер к текущему набору дескрипторов |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Привязать текстурный юнит к текущему набору дескрипторов |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Привязать буфер к текущему набору дескрипторов в указанном месте привязки. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Привязать буфер к текущему набору дескрипторов в указанном месте привязки. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Привязать текстурный юнит к текущему набору дескрипторов |
| [close()](#close--) | Освободить обновляющий объект и зафиксировать изменения на аппаратном устройстве. |
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


Привязать весь буфер к текущему дескриптору

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Привязать буфер к текущему набору дескрипторов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Какой буфер привязать |
| смещение | int | Смещение буфера для привязки |
| размер | int | Размер буфера для привязки |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Привязать текстурный юнит к текущему набору дескрипторов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Юнит текстуры для привязки |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Привязать буфер к текущему набору дескрипторов в указанном месте привязки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| привязка | int | Местоположение привязки |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Весь буфер для привязки |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Привязать буфер к текущему набору дескрипторов в указанном месте привязки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| привязка | int | Местоположение привязки |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Буфер для привязки |
| смещение | int | Смещение буфера для привязки |
| размер | int | Размер буфера для привязки |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Привязать текстурный юнит к текущему набору дескрипторов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| привязка | int | Местоположение привязки |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Юнит текстуры для привязки |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Освободить обновляющий объект и зафиксировать изменения на аппаратном устройстве.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

