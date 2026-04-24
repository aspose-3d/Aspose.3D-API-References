---
title: DescriptorSetUpdater
second_title: Aspose.3D for Java API リファレンス
description: このクラスは、チェーン操作で  を更新できるようにします。
type: docs
weight: 42
url: /ja/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

このクラスは、チェーン操作で [IDescriptorSet](../../com.aspose.threed/idescriptorset) を更新できるようにします。
## Methods

| Method | 説明 |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | 現在のディスクリプタにバッファ全体をバインドする |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | 現在のディスクリプタセットにバッファをバインドする |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | 現在のディスクリプタセットにテクスチャユニットをバインドする |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | 指定されたバインディング位置で現在のディスクリプタセットにバッファをバインドする。 |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | 指定されたバインディング位置で現在のディスクリプタセットにバッファをバインドする。 |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | 現在のディスクリプタセットにテクスチャユニットをバインドする |
| [close()](#close--) | アップデータを破棄し、変更をハードウェアデバイスにコミットする。 |
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


現在のディスクリプタにバッファ全体をバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


現在のディスクリプタセットにバッファをバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | どのバッファをバインドするか |
| オフセット | int | バインドするバッファのオフセット |
| サイズ | int | バインドするバッファのサイズ |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


現在のディスクリプタセットにテクスチャユニットをバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | バインドするテクスチャユニット |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


指定されたバインディング位置で現在のディスクリプタセットにバッファをバインドする。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| バインディング | int | バインディング位置 |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | バインドする全体バッファ |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


指定されたバインディング位置で現在のディスクリプタセットにバッファをバインドする。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| バインディング | int | バインディング位置 |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | バインドするバッファ |
| オフセット | int | バインドするバッファのオフセット |
| サイズ | int | バインドするバッファのサイズ |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


現在のディスクリプタセットにテクスチャユニットをバインドする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| バインディング | int | バインディング位置 |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | バインドするテクスチャユニット |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


アップデータを破棄し、変更をハードウェアデバイスにコミットする。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

