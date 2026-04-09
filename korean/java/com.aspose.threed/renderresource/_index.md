---
title: RenderResource
second_title: Aspose.3D for Java API 레퍼런스
description: 모든 렌더 리소스의 추상 클래스입니다. 렌더러가 해제될 때 모든 렌더 리소스가 해제됩니다.
type: docs
weight: 150
url: /ko/java/com.aspose.threed/renderresource/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class RenderResource implements Closeable
```

모든 렌더 리소스의 추상 클래스입니다. 렌더러가 해제될 때 모든 렌더 리소스가 해제됩니다. [Mesh](../../com.aspose.threed/mesh)/[Texture](../../com.aspose.threed/texture)와 같은 클래스는 해당 RenderResource를 가집니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RenderResource()](#RenderResource--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | [RenderResource](../../com.aspose.threed/renderresource)에서 사용되는 내부 리소스를 해제합니다. |
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


[RenderResource](../../com.aspose.threed/renderresource)에서 사용되는 내부 리소스를 해제합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

