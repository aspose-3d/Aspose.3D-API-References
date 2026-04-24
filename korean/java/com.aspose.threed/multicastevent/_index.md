---
title: MulticastEvent
second_title: Aspose.3D for Java API 레퍼런스
description: 2017년 4월 24일 lexchou가 만들었습니다.
type: docs
weight: 109
url: /ko/java/com.aspose.threed/multicastevent/
---

**Inheritance:**
java.lang.Object
```
public class MulticastEvent<EventArg>
```

2017년 4월 24일 lexchou가 만들었습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MulticastEvent()](#MulticastEvent--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<EventArg>Subscribe(MulticastEvent<EventArg> e, EventCallback<EventArg> callback)](#-EventArg-Subscribe-com.aspose.threed.MulticastEvent-EventArg--com.aspose.threed.EventCallback-EventArg--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [invoke(Object sender, EventArg arg)](#invoke-java.lang.Object-EventArg-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [subscribe(EventCallback<EventArg> callback)](#subscribe-com.aspose.threed.EventCallback-EventArg--) |  |
| [toString()](#toString--) |  |
| [unsubscribe(EventCallback<EventArg> callback)](#unsubscribe-com.aspose.threed.EventCallback-EventArg--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MulticastEvent() {#MulticastEvent--}
```
public MulticastEvent()
```


### <EventArg>Subscribe(MulticastEvent<EventArg> e, EventCallback<EventArg> callback) {#-EventArg-Subscribe-com.aspose.threed.MulticastEvent-EventArg--com.aspose.threed.EventCallback-EventArg--}
```
public static MulticastEvent<EventArg> <EventArg>Subscribe(MulticastEvent<EventArg> e, EventCallback<EventArg> callback)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| e | [MulticastEvent](../../com.aspose.threed/multicastevent) |  |
| callback | [EventCallback](../../com.aspose.threed/eventcallback) |  |

**Returns:**
[MulticastEvent](../../com.aspose.threed/multicastevent)
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
### invoke(Object sender, EventArg arg) {#invoke-java.lang.Object-EventArg-}
```
public void invoke(Object sender, EventArg arg)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sender | java.lang.Object |  |
| arg | EventArg |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### subscribe(EventCallback<EventArg> callback) {#subscribe-com.aspose.threed.EventCallback-EventArg--}
```
public void subscribe(EventCallback<EventArg> callback)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [EventCallback](../../com.aspose.threed/eventcallback) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unsubscribe(EventCallback<EventArg> callback) {#unsubscribe-com.aspose.threed.EventCallback-EventArg--}
```
public void unsubscribe(EventCallback<EventArg> callback)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [EventCallback](../../com.aspose.threed/eventcallback) |  |

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

