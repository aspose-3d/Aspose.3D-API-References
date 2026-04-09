---
title: ShaderSet
second_title: Aspose.3D for Java API Reference
description: Προγράμματα shader για κάθε τύπο υλικών
type: docs
weight: 166
url: /el/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Προγράμματα shader για κάθε τύπο υλικών
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | Δημιουργήστε το στιγμιότυπο του [ShaderSet](../../com.aspose.threed/shaderset) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Καταργήστε αυτό το στιγμιότυπο και απελευθερώστε όλα τα προγράμματα σκίασης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Λαμβάνει το εφεδρικό shader όταν το απαιτούμενο shader δεν είναι διαθέσιμο |
| [getLambert()](#getLambert--) | Λαμβάνει το shader που χρησιμοποιείται για την απόδοση του υλικού lambert |
| [getPbr()](#getPbr--) | Λαμβάνει το shader που χρησιμοποιείται για την απόδοση του υλικού PBR |
| [getPhong()](#getPhong--) | Λαμβάνει το shader που χρησιμοποιείται για την απόδοση του υλικού phong |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Ορίζει το εφεδρικό shader όταν το απαιτούμενο shader δεν είναι διαθέσιμο |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Ορίζει το shader που χρησιμοποιείται για την απόδοση του υλικού lambert |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | Ορίζει το shader που χρησιμοποιείται για την απόδοση του υλικού PBR |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Ορίζει το shader που χρησιμοποιείται για την απόδοση του υλικού phong |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


Δημιουργήστε το στιγμιότυπο του [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


Καταργήστε αυτό το στιγμιότυπο και απελευθερώστε όλα τα προγράμματα σκίασης.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


Λαμβάνει το εφεδρικό shader όταν το απαιτούμενο shader δεν είναι διαθέσιμο

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Λαμβάνει το shader που χρησιμοποιείται για την απόδοση του υλικού lambert

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


Λαμβάνει το shader που χρησιμοποιείται για την απόδοση του υλικού PBR

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Λαμβάνει το shader που χρησιμοποιείται για την απόδοση του υλικού phong

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


Ορίζει το εφεδρικό shader όταν το απαιτούμενο shader δεν είναι διαθέσιμο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Νέα τιμή |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Ορίζει το shader που χρησιμοποιείται για την απόδοση του υλικού lambert

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Νέα τιμή |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


Ορίζει το shader που χρησιμοποιείται για την απόδοση του υλικού PBR

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Νέα τιμή |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Ορίζει το shader που χρησιμοποιείται για την απόδοση του υλικού phong

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Νέα τιμή |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

