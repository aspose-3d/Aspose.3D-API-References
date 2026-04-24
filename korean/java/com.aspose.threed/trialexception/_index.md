---
title: TrialException
second_title: Aspose.3D for Java API 레퍼런스
description: 라이선스가 적용되지 않았을 때 Scene.Open/Scene.Save에서 발생합니다.
type: docs
weight: 195
url: /ko/java/com.aspose.threed/trialexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class TrialException extends RuntimeException
```

이 예외는 Scene.Open/Scene.Save에서 라이선스가 적용되지 않았을 때 발생합니다. SuppressTrialException을 true로 설정하면 이 예외를 끌 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TrialException(String msg)](#TrialException-java.lang.String-) | 생성자 [TrialException](../../com.aspose.threed/trialexception) |
| [TrialException()](#TrialException--) | 생성자 [TrialException](../../com.aspose.threed/trialexception) |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressTrialException()](#getSuppressTrialException--) | 비인가 사용에 대한 trial 예외를 억제하려면 이를 true로 설정하지만, 제한은 해제되지 않습니다. |
| [getSuppressed()](#getSuppressed--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [setSuppressTrialException(boolean value)](#setSuppressTrialException-boolean-) | 비인가 사용에 대한 trial 예외를 억제하려면 이를 true로 설정하지만, 제한은 해제되지 않습니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TrialException(String msg) {#TrialException-java.lang.String-}
```
public TrialException(String msg)
```


생성자 [TrialException](../../com.aspose.threed/trialexception)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| msg | java.lang.String |  |

### TrialException() {#TrialException--}
```
public TrialException()
```


생성자 [TrialException](../../com.aspose.threed/trialexception)

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Returns:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Returns:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```




**Returns:**
java.lang.String
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getSuppressTrialException() {#getSuppressTrialException--}
```
public static boolean getSuppressTrialException()
```


비인가 사용에 대한 trial 예외를 억제하려면 이를 true로 설정하지만, 제한은 해제되지 않습니다. 제한을 해제하려면 적절한 라이선스를 사용하십시오. 또한 이를 true로 설정한다는 것은 비인가 제한을 인지하고 있다는 의미입니다.

**Returns:**
boolean - 비인가 사용에 대한 trial 예외를 억제하려면 이를 true로 설정하지만, 제한은 해제되지 않습니다. 제한을 해제하려면 적절한 라이선스를 사용하십시오. 또한 이를 true로 설정한다는 것은 비인가 제한을 인지하고 있다는 의미입니다.
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Returns:**
java.lang.Throwable[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Returns:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### setSuppressTrialException(boolean value) {#setSuppressTrialException-boolean-}
```
public static void setSuppressTrialException(boolean value)
```


비인가 사용에 대한 trial 예외를 억제하려면 이를 true로 설정하지만, 제한은 해제되지 않습니다. 제한을 해제하려면 적절한 라이선스를 사용하십시오. 또한 이를 true로 설정한다는 것은 비인가 제한을 인지하고 있다는 의미입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

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

