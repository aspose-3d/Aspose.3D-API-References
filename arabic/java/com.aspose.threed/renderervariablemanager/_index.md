---
title: "RendererVariableManager"
second_title: "مرجع Aspose.3D لـ Java API"
description: "هذه الفئة تدير المتغيرات المستخدمة في العرض"
type: docs
weight: 154
url: /ar/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

هذه الفئة تدير المتغيرات المستخدمة في العرض
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | موضع الكاميرا في نظام إحداثيات العالم |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | تحيز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | مصفوفة لتحويل مساحة الإضاءة |
| [getMatrixProjection()](#getMatrixProjection--) | مصفوفة لتحويل الإسقاط |
| [getMatrixView()](#getMatrixView--) | مصفوفة لتحويل العرض |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | مصفوفة لتحويل العرض والإسقاط. |
| [getMatrixWorld()](#getMatrixWorld--) | مصفوفة لتحويل العالم |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | مصفوفة لتحويل المتجه العادي من الكائن إلى مساحة العالم. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | مصفوفة لعرض العالم وتحويل الإسقاط |
| [getShadowCaster()](#getShadowCaster--) | موضع مصدر الظل في نظام إحداثيات العالم |
| [getShadowmap()](#getShadowmap--) | ملمس العمق المستخدم لتخطيط الظلال |
| [getViewportSize()](#getViewportSize--) | حجم نافذة العرض، مقاسًا بالبكسل |
| [getWorldAmbient()](#getWorldAmbient--) | لون الإضاءة المحيطة المحدد في نافذة العرض. |
| [getWorldTime()](#getWorldTime--) | الوقت بالثواني |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | موضع الكاميرا في نظام إحداثيات العالم |
| [setDepthBias(float value)](#setDepthBias-float-) | تحيز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | مصفوفة لتحويل مساحة الإضاءة |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | مصفوفة لتحويل الإسقاط |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | مصفوفة لتحويل العرض |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | موضع مصدر الظل في نظام إحداثيات العالم |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | ملمس العمق المستخدم لتخطيط الظلال |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | حجم نافذة العرض، مقاسًا بالبكسل |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | لون الإضاءة المحيطة المحدد في نافذة العرض. |
| [setWorldTime(float value)](#setWorldTime-float-) | الوقت بالثواني |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


موضع الكاميرا في نظام إحداثيات العالم

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Camera's position in world coordinate system
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthBias() {#getDepthBias--}
```
public float getDepthBias()
```


تحيز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001

**Returns:**
float - انحياز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


مصفوفة لتحويل مساحة الإضاءة

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


مصفوفة لتحويل الإسقاط

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


مصفوفة لتحويل العرض

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


مصفوفة لتحويل العرض والإسقاط.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


مصفوفة لتحويل العالم

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


مصفوفة لتحويل المتجه العادي من الكائن إلى مساحة العالم.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


مصفوفة لعرض العالم وتحويل الإسقاط

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


موضع مصدر الظل في نظام إحداثيات العالم

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


ملمس العمق المستخدم لتخطيط الظلال

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


حجم نافذة العرض، مقاسًا بالبكسل

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


لون الإضاءة المحيطة المحدد في نافذة العرض.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


الوقت بالثواني

**Returns:**
float - الوقت بالثواني
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




### setCameraPosition(FVector3 value) {#setCameraPosition-com.aspose.threed.FVector3-}
```
public void setCameraPosition(FVector3 value)
```


موضع الكاميرا في نظام إحداثيات العالم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | قيمة جديدة |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


تحيز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float | قيمة جديدة |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


مصفوفة لتحويل مساحة الإضاءة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | قيمة جديدة |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


مصفوفة لتحويل الإسقاط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | قيمة جديدة |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


مصفوفة لتحويل العرض

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | قيمة جديدة |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


موضع مصدر الظل في نظام إحداثيات العالم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | قيمة جديدة |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


ملمس العمق المستخدم لتخطيط الظلال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | قيمة جديدة |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


حجم نافذة العرض، مقاسًا بالبكسل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | قيمة جديدة |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


لون الإضاءة المحيطة المحدد في نافذة العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | قيمة جديدة |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


الوقت بالثواني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float | قيمة جديدة |

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

