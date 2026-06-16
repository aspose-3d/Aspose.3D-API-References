---
title: "RendererVariableManager"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "هذه الفئة تدير المتغيّرات المستخدمة في العرض."
type: docs
weight: 154
url: /ar/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

هذه الفئة تدير المتغيّرات المستخدمة في العرض.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | موضع الكاميرا في نظام إحداثيات العالم |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | انحياز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | المصفوفة لتحويل مساحة الضوء |
| [getMatrixProjection()](#getMatrixProjection--) | المصفوفة لتحويل الإسقاط |
| [getMatrixView()](#getMatrixView--) | المصفوفة لتحويل العرض |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | المصفوفة لتحويل العرض والإسقاط. |
| [getMatrixWorld()](#getMatrixWorld--) | المصفوفة لتحويل العالم |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | المصفوفة لتحويل المتجه العادي من الكائن إلى مساحة العالم. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | مصفوفة لعرض العالم وتحويل الإسقاط |
| [getShadowCaster()](#getShadowCaster--) | موضع مصدر الظل في نظام إحداثيات العالم |
| [getShadowmap()](#getShadowmap--) | قوام العمق المستخدم لتخطيط الظلال |
| [getViewportSize()](#getViewportSize--) | حجم نافذة العرض، مقاسًا بالبكسل |
| [getWorldAmbient()](#getWorldAmbient--) | لون الإضاءة المحيطة المحدد في نافذة العرض. |
| [getWorldTime()](#getWorldTime--) | الوقت بالثواني |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | موضع الكاميرا في نظام إحداثيات العالم |
| [setDepthBias(float value)](#setDepthBias-float-) | انحياز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | المصفوفة لتحويل مساحة الضوء |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | المصفوفة لتحويل الإسقاط |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | المصفوفة لتحويل العرض |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | موضع مصدر الظل في نظام إحداثيات العالم |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | قوام العمق المستخدم لتخطيط الظلال |
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


انحياز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001

**Returns:**
float - إزاحة العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


المصفوفة لتحويل مساحة الضوء

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


المصفوفة لتحويل الإسقاط

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


المصفوفة لتحويل العرض

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


المصفوفة لتحويل العرض والإسقاط.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


المصفوفة لتحويل العالم

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


المصفوفة لتحويل المتجه العادي من الكائن إلى مساحة العالم.

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


قوام العمق المستخدم لتخطيط الظلال

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
| value | [FVector3](../../com.aspose.threed/fvector3) | القيمة الجديدة |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


انحياز العمق لتخطيط الظلال، القيمة الافتراضية هي 0.001

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


المصفوفة لتحويل مساحة الضوء

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | القيمة الجديدة |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


المصفوفة لتحويل الإسقاط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | القيمة الجديدة |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


المصفوفة لتحويل العرض

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | القيمة الجديدة |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


موضع مصدر الظل في نظام إحداثيات العالم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | القيمة الجديدة |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


قوام العمق المستخدم لتخطيط الظلال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | القيمة الجديدة |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


حجم نافذة العرض، مقاسًا بالبكسل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | القيمة الجديدة |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


لون الإضاءة المحيطة المحدد في نافذة العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | القيمة الجديدة |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


الوقت بالثواني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

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

