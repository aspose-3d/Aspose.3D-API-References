---
title: "Viewport"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "A يحتوي على منفذ عرض واحد على الأقل لتصوير المشهد."
type: docs
weight: 229
url: /ar/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

A [IRenderTarget](../../com.aspose.threed/irendertarget) يحتوي على منفذ عرض واحد على الأقل لتصوير المشهد.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | يحصل على مساحة منفذ العرض في هدف العرض. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون خلفية منفذ العرض. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | يحصل على قيمة العمق المستخدمة عند مسح منفذ العرض مع ضبط بت مخزن العمق. |
| [getEnabled()](#getEnabled--) | تمكين أو تعطيل هذا المنفذ العرض. |
| [getFrustum()](#getFrustum--) | يحصل على كاميرا هذا [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | يحصل على هدف العرض الذي أنشأ هذا المنفذ العرض. |
| [getZOrder()](#getZOrder--) | يحصل على ترتيب Z لمنطقة العرض. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | يضبط مساحة منطقة العرض في هدف التصيير. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | يضبط لون الخلفية لمنطقة العرض. |
| [setDepthClear(float value)](#setDepthClear-float-) | يضبط قيمة العمق المستخدمة عند مسح منطقة العرض مع تعيين بت مخزن العمق. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | تمكين أو تعطيل هذا المنفذ العرض. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | يضبط الكاميرا لهذه [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | يضبط ترتيب Z لمنطقة العرض. |
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


يحصل على لون خلفية منفذ العرض.

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
float - قيمة العمق المستخدمة عند مسح منطقة العرض مع تعيين بت مخزن العمق.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


تمكين أو تعطيل هذا المنفذ العرض.

**Returns:**
boolean - تمكين أو تعطيل هذه منطقة العرض.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


يحصل على كاميرا هذا [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


يحصل على هدف العرض الذي أنشأ هذا المنفذ العرض.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


يحصل على ترتيب Z لمنطقة العرض.

**Returns:**
int - ترتيب Z لمنطقة العرض.
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


يضبط مساحة منطقة العرض في هدف التصيير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | القيمة الجديدة |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


يضبط لون الخلفية لمنطقة العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


يضبط قيمة العمق المستخدمة عند مسح منطقة العرض مع تعيين بت مخزن العمق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


تمكين أو تعطيل هذا المنفذ العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


يضبط الكاميرا لهذه [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | القيمة الجديدة |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


يضبط ترتيب Z لمنطقة العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

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

