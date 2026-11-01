---
title: "Viewport"
second_title: "مرجع Aspose.3D لـ Java API"
description: "يحتوي على منفذ عرض واحد على الأقل لتصوير المشهد."
type: docs
weight: 229
url: /ar/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

يحتوي [IRenderTarget](../../com.aspose.threed/irendertarget) على منفذ عرض واحد على الأقل لتصوير المشهد.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | يحصل على مساحة منفذ العرض في هدف العرض. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية لمنفذ العرض. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | يحصل على قيمة العمق المستخدمة عند مسح منفذ العرض مع ضبط بت مخزن العمق. |
| [getEnabled()](#getEnabled--) | تمكين أو تعطيل هذا المنفذ. |
| [getFrustum()](#getFrustum--) | يحصل على الكاميرا لهذا [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | يحصل على هدف العرض الذي أنشأ هذا منفذ العرض. |
| [getZOrder()](#getZOrder--) | يحصل على ترتيب Z للـ viewport. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | يضبط مساحة الـ viewport في render target. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | يضبط لون الخلفية للـ viewport. |
| [setDepthClear(float value)](#setDepthClear-float-) | يضبط قيمة العمق المستخدمة عند مسح الـ viewport مع تعيين بت مخزن العمق. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | تمكين أو تعطيل هذا المنفذ. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | يضبط الكاميرا لهذا [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | يضبط ترتيب Z للـ viewport. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


يحصل على مساحة منفذ العرض في هدف العرض.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


يحصل على لون الخلفية لمنفذ العرض.

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


يحصل على قيمة العمق المستخدمة عند مسح منفذ العرض مع ضبط بت مخزن العمق.

**Returns:**
float - قيمة العمق المستخدمة عند مسح الـ viewport مع تعيين بت مخزن العمق.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


تمكين أو تعطيل هذا المنفذ.

**Returns:**
boolean - تمكين أو تعطيل هذا الـ viewport.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


يحصل على الكاميرا لهذا [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


يحصل على هدف العرض الذي أنشأ هذا منفذ العرض.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


يحصل على ترتيب Z للـ viewport.

**Returns:**
int - ترتيب Z للـ viewport.
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


يضبط مساحة الـ viewport في render target.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | قيمة جديدة |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


يضبط لون الخلفية للـ viewport.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


يضبط قيمة العمق المستخدمة عند مسح الـ viewport مع تعيين بت مخزن العمق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float | قيمة جديدة |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


تمكين أو تعطيل هذا المنفذ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


يضبط الكاميرا لهذا [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | قيمة جديدة |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


يضبط ترتيب Z للـ viewport.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int | قيمة جديدة |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

