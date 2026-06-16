---
title: "DescriptorSetUpdater"
second_title: "Aspose.3D for Java API 参考"
description: "此类允许在链式操作中更新  。"
type: docs
weight: 42
url: /zh/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

此类允许在链式操作中更新 [IDescriptorSet](../../com.aspose.threed/idescriptorset)。
## 方法

| 方法 | 描述 |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | 将整个缓冲区绑定到当前描述符 |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | 将缓冲区绑定到当前描述符集 |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | 将纹理单元绑定到当前描述符集 |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | 在指定的绑定位置将缓冲区绑定到当前描述符集。 |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | 在指定的绑定位置将缓冲区绑定到当前描述符集。 |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | 将纹理单元绑定到当前描述符集 |
| [close()](#close--) | 释放更新器并将更改提交到硬件设备。 |
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


将整个缓冲区绑定到当前描述符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


将缓冲区绑定到当前描述符集

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | 要绑定哪个缓冲区 |
| 偏移 | int | 要绑定的缓冲区的偏移量 |
| 大小 | int | 要绑定的缓冲区的大小 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


将纹理单元绑定到当前描述符集

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | 要绑定的纹理单元 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


在指定的绑定位置将缓冲区绑定到当前描述符集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 绑定 | int | 绑定位置 |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | 要绑定的整个缓冲区 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


在指定的绑定位置将缓冲区绑定到当前描述符集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 绑定 | int | 绑定位置 |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | 要绑定的缓冲区 |
| 偏移 | int | 要绑定的缓冲区的偏移量 |
| 大小 | int | 要绑定的缓冲区的大小 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


将纹理单元绑定到当前描述符集

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 绑定 | int | 绑定位置 |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | 要绑定的纹理单元 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


释放更新器并将更改提交到硬件设备。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

