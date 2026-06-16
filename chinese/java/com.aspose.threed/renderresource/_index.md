---
title: "RenderResource"
second_title: "Aspose.3D for Java API 参考"
description: "所有渲染资源的抽象类。渲染器释放时，所有渲染资源将被释放。"
type: docs
weight: 150
url: /zh/java/com.aspose.threed/renderresource/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class RenderResource implements Closeable
```

所有渲染资源的抽象类。渲染器释放时，所有渲染资源将被释放。类似 [Mesh](../../com.aspose.threed/mesh)/[Texture](../../com.aspose.threed/texture) 的类将拥有相应的 RenderResource。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RenderResource()](#RenderResource--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 释放由 [RenderResource](../../com.aspose.threed/renderresource) 使用的内部资源 |
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


释放由 [RenderResource](../../com.aspose.threed/renderresource) 使用的内部资源

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

