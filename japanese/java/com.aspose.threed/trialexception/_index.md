---
title: TrialException
second_title: Aspose.3D for Java API リファレンス
description: ライセンスが適用されていない場合、Scene.Open/Scene.Saveでこれが発生します。
type: docs
weight: 195
url: /ja/java/com.aspose.threed/trialexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class TrialException extends RuntimeException
```

ライセンスが適用されていない場合に Scene.Open/Scene.Save で発生します。SuppressTrialException を true に設定することでこの例外をオフにできます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TrialException(String msg)](#TrialException-java.lang.String-) | [TrialException](../../com.aspose.threed/trialexception) のコンストラクタ |
| [TrialException()](#TrialException--) | [TrialException](../../com.aspose.threed/trialexception) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressTrialException()](#getSuppressTrialException--) | この値を true に設定すると、未ライセンス使用時のトライアル例外を抑制しますが、制限は解除されません。 |
| [getSuppressed()](#getSuppressed--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [setSuppressTrialException(boolean value)](#setSuppressTrialException-boolean-) | この値を true に設定すると、未ライセンス使用時のトライアル例外を抑制しますが、制限は解除されません。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TrialException(String msg) {#TrialException-java.lang.String-}
```
public TrialException(String msg)
```


[TrialException](../../com.aspose.threed/trialexception) のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| msg | java.lang.String |  |

### TrialException() {#TrialException--}
```
public TrialException()
```


[TrialException](../../com.aspose.threed/trialexception) のコンストラクタ

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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


この値を true に設定すると、未ライセンス使用時のトライアル例外を抑制しますが、制限は解除されません。制限を解除するには、適切なライセンスをご使用ください。また、この値を true に設定することは、未ライセンスの制限を認識していることを意味します。

**Returns:**
boolean - この値を true に設定すると、未ライセンス使用時のトライアル例外を抑制しますが、制限は解除されません。制限を解除するには、適切なライセンスをご使用ください。また、この値を true に設定することは、未ライセンスの制限を認識していることを意味します。
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
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### setSuppressTrialException(boolean value) {#setSuppressTrialException-boolean-}
```
public static void setSuppressTrialException(boolean value)
```


この値を true に設定すると、未ライセンス使用時のトライアル例外を抑制しますが、制限は解除されません。制限を解除するには、適切なライセンスをご使用ください。また、この値を true に設定することは、未ライセンスの制限を認識していることを意味します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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

