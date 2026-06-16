---
title: "TrialException"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Ceci est déclenché dans Scene.Open/Scene.Save lorsqu’aucune licence n’est appliquée."
type: docs
weight: 195
url: /fr/java/com.aspose.threed/trialexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class TrialException extends RuntimeException
```

Cette exception est levée dans Scene.Open/Scene.Save lorsqu'aucune licence n'est appliquée. Vous pouvez désactiver cette exception en définissant SuppressTrialException sur true.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TrialException(String msg)](#TrialException-java.lang.String-) | Constructeur de [TrialException](../../com.aspose.threed/trialexception) |
| [TrialException()](#TrialException--) | Constructeur de [TrialException](../../com.aspose.threed/trialexception) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressTrialException()](#getSuppressTrialException--) | Définit cette valeur sur true pour supprimer l'exception d'essai en cas d'utilisation non licenciée, mais les restrictions ne seront pas levées. |
| [getSuppressed()](#getSuppressed--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [setSuppressTrialException(boolean value)](#setSuppressTrialException-boolean-) | Définit cette valeur sur true pour supprimer l'exception d'essai en cas d'utilisation non licenciée, mais les restrictions ne seront pas levées. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TrialException(String msg) {#TrialException-java.lang.String-}
```
public TrialException(String msg)
```


Constructeur de [TrialException](../../com.aspose.threed/trialexception)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| msg | java.lang.String |  |

### TrialException() {#TrialException--}
```
public TrialException()
```


Constructeur de [TrialException](../../com.aspose.threed/trialexception)

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Définit cette valeur sur true pour supprimer l'exception d'essai en cas d'utilisation non licenciée, mais les restrictions ne seront pas levées. Pour lever les restrictions, veuillez utiliser une licence appropriée. Définir cette valeur sur true signifie également que vous êtes conscient des restrictions liées à l'absence de licence.

**Returns:**
boolean - Définit cette valeur sur true pour supprimer l'exception d'essai en cas d'utilisation non licenciée, mais les restrictions ne seront pas levées. Pour lever les restrictions, veuillez utiliser une licence appropriée. Définir cette valeur sur true signifie également que vous êtes conscient des restrictions liées à l'absence de licence.
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### setSuppressTrialException(boolean value) {#setSuppressTrialException-boolean-}
```
public static void setSuppressTrialException(boolean value)
```


Définit cette valeur sur true pour supprimer l'exception d'essai en cas d'utilisation non licenciée, mais les restrictions ne seront pas levées. Pour lever les restrictions, veuillez utiliser une licence appropriée. Définir cette valeur sur true signifie également que vous êtes conscient des restrictions liées à l'absence de licence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

