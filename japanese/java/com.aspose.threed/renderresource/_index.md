---
title: RenderResource
second_title: Aspose.3D for Java API リファレンス
description: すべてのレンダーリソースの抽象クラスです。レンダーが解放されると、すべてのレンダーリソースが破棄されます。
type: docs
weight: 150
url: /ja/java/com.aspose.threed/renderresource/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class RenderResource implements Closeable
```

すべてのレンダーリソースの抽象クラスです。レンダーが解放されると、すべてのレンダーリソースが破棄されます。[Mesh](../../com.aspose.threed/mesh)/[Texture](../../com.aspose.threed/texture) のようなクラスは、対応する RenderResource を持ちます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RenderResource()](#RenderResource--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [close()](#close--) | [RenderResource](../../com.aspose.threed/renderresource) が使用する内部リソースを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderResource() {#RenderResource--}
```
public RenderResource()
```


### close() {#close--}
```
public void close()
```


[RenderResource](../../com.aspose.threed/renderresource) が使用する内部リソースを破棄します。

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

