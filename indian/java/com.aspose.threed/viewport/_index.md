---
title: Viewport
second_title: Aspose.3D for Java API Reference
description: एक  दृश्य को रेंडर करने के लिए कम से कम एक viewport रखता है।
type: docs
weight: 229
url: /hi/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

एक [IRenderTarget](../../com.aspose.threed/irendertarget) दृश्य को रेंडर करने के लिए कम से कम एक viewport रखता है।
## Methods

| Method | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | render target में viewport का क्षेत्र प्राप्त करता है। |
| [getBackgroundColor()](#getBackgroundColor--) | viewport का बैकग्राउंड रंग प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | depth buffer बिट सेट होने पर viewport को साफ़ करने के लिए उपयोग किया गया depth मान प्राप्त करता है। |
| [getEnabled()](#getEnabled--) | इस viewport को सक्षम या अक्षम करें। |
| [getFrustum()](#getFrustum--) | इस [Viewport](../../com.aspose.threed/viewport) का कैमरा प्राप्त करता है। |
| [getRenderTarget()](#getRenderTarget--) | इस viewport को बनाने वाले render target को प्राप्त करता है। |
| [getZOrder()](#getZOrder--) | व्यूपोर्ट का Z-ऑर्डर प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | रेंडर टार्गेट में व्यूपोर्ट का क्षेत्र सेट करता है। |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | व्यूपोर्ट की पृष्ठभूमि रंग सेट करता है। |
| [setDepthClear(float value)](#setDepthClear-float-) | जब गहराई बफ़र बिट सेट हो तो व्यूपोर्ट को साफ़ करने के लिए उपयोग किया जाने वाला गहराई मान सेट करता है। |
| [setEnabled(boolean value)](#setEnabled-boolean-) | इस viewport को सक्षम या अक्षम करें। |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | इस [Viewport](../../com.aspose.threed/viewport) का कैमरा सेट करता है। |
| [setZOrder(int value)](#setZOrder-int-) | व्यूपोर्ट का Z-ऑर्डर सेट करता है। |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


render target में viewport का क्षेत्र प्राप्त करता है।

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


viewport का बैकग्राउंड रंग प्राप्त करता है।

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


depth buffer बिट सेट होने पर viewport को साफ़ करने के लिए उपयोग किया गया depth मान प्राप्त करता है।

**Returns:**
float - जब गहराई बफ़र बिट सेट हो तो व्यूपोर्ट को साफ़ करने के लिए उपयोग किया जाने वाला गहराई मान।
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


इस viewport को सक्षम या अक्षम करें।

**Returns:**
boolean - इस व्यूपोर्ट को सक्षम या अक्षम करें।
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


इस [Viewport](../../com.aspose.threed/viewport) का कैमरा प्राप्त करता है।

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


इस viewport को बनाने वाले render target को प्राप्त करता है।

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


व्यूपोर्ट का Z-ऑर्डर प्राप्त करता है।

**Returns:**
int - व्यूपोर्ट का Z-ऑर्डर।
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


रेंडर टार्गेट में व्यूपोर्ट का क्षेत्र सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | नया मान |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


व्यूपोर्ट की पृष्ठभूमि रंग सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


जब गहराई बफ़र बिट सेट हो तो व्यूपोर्ट को साफ़ करने के लिए उपयोग किया जाने वाला गहराई मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | फ़्लोट | नया मान |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


इस viewport को सक्षम या अक्षम करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


इस [Viewport](../../com.aspose.threed/viewport) का कैमरा सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | नया मान |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


व्यूपोर्ट का Z-ऑर्डर सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

