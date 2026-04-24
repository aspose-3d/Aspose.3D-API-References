---
title: Viewport
second_title: Aspose.3D for Java API Reference
description: Ένα  περιέχει τουλάχιστον ένα παράθυρο προβολής για την απόδοση της σκηνής.
type: docs
weight: 229
url: /el/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

Ένα [IRenderTarget](../../com.aspose.threed/irendertarget) περιέχει τουλάχιστον ένα παράθυρο προβολής για την απόδοση της σκηνής.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Λαμβάνει την περιοχή του παράθυρου προβολής στον στόχο απόδοσης. |
| [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει το χρώμα φόντου του παράθυρου προβολής. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Λαμβάνει την τιμή βάθους που χρησιμοποιείται όταν καθαρίζεται το παράθυρο προβολής με ενεργοποιημένο το bit του buffer βάθους. |
| [getEnabled()](#getEnabled--) | Ενεργοποίηση ή απενεργοποίηση αυτού του παράθυρου προβολής. |
| [getFrustum()](#getFrustum--) | Λαμβάνει την κάμερα αυτού του [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | Λαμβάνει τον στόχο απόδοσης που δημιούργησε αυτό το παράθυρο προβολής. |
| [getZOrder()](#getZOrder--) | Λαμβάνει τη σειρά Z του viewport. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Ορίζει την περιοχή του viewport στο render target. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Ορίζει το χρώμα φόντου του viewport. |
| [setDepthClear(float value)](#setDepthClear-float-) | Ορίζει την τιμή βάθους που χρησιμοποιείται όταν καθαρίζεται το viewport με το bit του depth buffer ενεργοποιημένο. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Ενεργοποίηση ή απενεργοποίηση αυτού του παράθυρου προβολής. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Ορίζει την κάμερα αυτού του [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | Ορίζει τη σειρά Z του viewport. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clone() {#clone--}
```
public Viewport clone()
```




**Returns:**
[Viewport](../../com.aspose.threed/viewport)
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
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Λαμβάνει την περιοχή του παράθυρου προβολής στον στόχο απόδοσης.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Λαμβάνει το χρώμα φόντου του παράθυρου προβολής.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the background color of the viewport.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthClear() {#getDepthClear--}
```
public float getDepthClear()
```


Λαμβάνει την τιμή βάθους που χρησιμοποιείται όταν καθαρίζεται το παράθυρο προβολής με ενεργοποιημένο το bit του buffer βάθους.

**Returns:**
float - η τιμή βάθους που χρησιμοποιείται όταν καθαρίζεται το viewport με το bit του depth buffer ενεργοποιημένο.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Ενεργοποίηση ή απενεργοποίηση αυτού του παράθυρου προβολής.

**Returns:**
boolean - Ενεργοποίηση ή απενεργοποίηση αυτού του viewport.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Λαμβάνει την κάμερα αυτού του [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Λαμβάνει τον στόχο απόδοσης που δημιούργησε αυτό το παράθυρο προβολής.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Λαμβάνει τη σειρά Z του viewport.

**Returns:**
int - η σειρά Z του viewport.
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




### setArea(RelativeRectangle value) {#setArea-com.aspose.threed.RelativeRectangle-}
```
public void setArea(RelativeRectangle value)
```


Ορίζει την περιοχή του viewport στο render target.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Νέα τιμή |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Ορίζει το χρώμα φόντου του viewport.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Ορίζει την τιμή βάθους που χρησιμοποιείται όταν καθαρίζεται το viewport με το bit του depth buffer ενεργοποιημένο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Ενεργοποίηση ή απενεργοποίηση αυτού του παράθυρου προβολής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Ορίζει την κάμερα αυτού του [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Νέα τιμή |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Ορίζει τη σειρά Z του viewport.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

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

