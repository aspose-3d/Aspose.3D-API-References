---
title: "RenderState"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "حالة العرض لبناء خط الأنابيب. التغييرات التي تُجرى على حالة العرض لن تؤثر على مثيلات خط الأنابيب المُنشأة."
type: docs
weight: 151
url: /ar/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

حالة العرض لبناء خط الأنابيب التغييرات التي تُجرى على حالة العرض لن تؤثر على نسخ خط الأنابيب المُنشأة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RenderState()](#RenderState--) | منشئ [RenderState](../../com.aspose.threed/renderstate) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) | تحرير [RenderState](../../com.aspose.threed/renderstate) وإطلاق جميع الموارد الداخلية. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | قارن حالة العرض مع نسخة أخرى. |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لكائن محدد. |
| [getBlend()](#getBlend--) | تمكين أو تعطيل دمج الشظايا. |
| [getBlendColor()](#getBlendColor--) | يحصل على لون الدمج حيث يُستخدم في [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | تمكين أو تعطيل قص الوجه. |
| [getCullFaceMode()](#getCullFaceMode--) | يحصل على الوجه الذي سيتم قصه. |
| [getDepthFunction()](#getDepthFunction--) | يحصل على دالة المقارنة المستخدمة في اختبار العمق. |
| [getDepthMask()](#getDepthMask--) | تمكين أو تعطيل كتابة العمق. |
| [getDepthTest()](#getDepthTest--) | تمكين أو تعطيل اختبار العمق. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | يحصل على طريقة دمج اللون. |
| [getFrontFace()](#getFrontFace--) | يحصل على أي ترتيب هو الوجه الأمامي. |
| [getPolygonMode()](#getPolygonMode--) | يحصل على وضع عرض المضلع. |
| [getScissorTest()](#getScissorTest--) | تمكين أو تعطيل اختبار المقص. |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | يحصل على طريقة دمج اللون. |
| [getStencilBackFace()](#getStencilBackFace--) | يحصل على حالة القالب للوجه الخلفي. |
| [getStencilFrontFace()](#getStencilFrontFace--) | يحصل على حالة القالب للوجه الأمامي. |
| [getStencilMask()](#getStencilMask--) | يحصل على القناع الذي يتم تطبيق عملية AND معه على كل من القيمة المرجعية والقيمة المخزنة للقالب عند الانتهاء من الاختبار. |
| [getStencilReference()](#getStencilReference--) | يحصل على القيمة المرجعية لاختبار القالب. |
| [getStencilTest()](#getStencilTest--) | تمكين أو تعطيل اختبار القالب. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة (hash code) لهذه المثيلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | تمكين أو تعطيل دمج الشظايا. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | يضبط لون الدمج حيث يُستخدم في [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | تمكين أو تعطيل قص الوجه. |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | يضبط أي وجه سيتم قصه. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | يضبط دالة المقارنة المستخدمة في اختبار العمق. |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | تمكين أو تعطيل كتابة العمق. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | تمكين أو تعطيل اختبار العمق. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | يضبط طريقة دمج اللون. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | يضبط أي ترتيب هو الوجه الأمامي. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | يضبط وضع عرض المضلع. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | تمكين أو تعطيل اختبار المقص. |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | يضبط طريقة دمج اللون. |
| [setStencilMask(int value)](#setStencilMask-int-) | يضبط القناع الذي يتم تطبيق عملية AND عليه مع كل من القيمة المرجعية والقيمة المخزنة للستينسل عند الانتهاء من الاختبار. |
| [setStencilReference(int value)](#setStencilReference-int-) | يضبط القيمة المرجعية لاختبار الستينسل. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | تمكين أو تعطيل اختبار القالب. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


منشئ [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


تحرير [RenderState](../../com.aspose.threed/renderstate) وإطلاق جميع الموارد الداخلية.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


قارن حالة العرض مع نسخة أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | حالة عرض أخرى للمقارنة |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لكائن محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


تمكين أو تعطيل دمج الشظايا.

**Returns:**
boolean - تمكين أو تعطيل دمج القطع.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


يحصل على لون الدمج حيث يُستخدم في [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


تمكين أو تعطيل قص الوجه.

**Returns:**
boolean - تمكين أو تعطيل إلغاء الوجه
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


يحصل على الوجه الذي سيتم قصه.

**Returns:**
int - أي وجه سيتم إلغاؤه.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


يحصل على دالة المقارنة المستخدمة في اختبار العمق.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


تمكين أو تعطيل كتابة العمق.

**Returns:**
boolean - تمكين أو تعطيل كتابة العمق.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


تمكين أو تعطيل اختبار العمق.

**Returns:**
boolean - تمكين أو تعطيل اختبار العمق.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


يحصل على طريقة دمج اللون.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


يحصل على أي ترتيب هو الوجه الأمامي.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


يحصل على وضع عرض المضلع.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


تمكين أو تعطيل اختبار المقص.

**Returns:**
boolean - تمكين أو تعطيل اختبار المقص
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


يحصل على طريقة دمج اللون.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


يحصل على حالة القالب للوجه الخلفي.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


يحصل على حالة القالب للوجه الأمامي.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


يحصل على القناع الذي يتم تطبيق عملية AND معه على كل من القيمة المرجعية والقيمة المخزنة للقالب عند الانتهاء من الاختبار.

**Returns:**
int - القناع الذي يتم تطبيق عملية AND عليه مع كل من القيمة المرجعية والقيمة المخزنة للستينسل عند الانتهاء من الاختبار.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


يحصل على القيمة المرجعية لاختبار القالب.

**Returns:**
int - القيمة المرجعية لاختبار الستينسل.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


تمكين أو تعطيل اختبار القالب.

**Returns:**
boolean - تمكين أو تعطيل اختبار الستينسل.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة (hash code) لهذه المثيلة.

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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


تمكين أو تعطيل دمج الشظايا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


يضبط لون الدمج حيث يُستخدم في [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | القيمة الجديدة |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


تمكين أو تعطيل قص الوجه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


يضبط أي وجه سيتم قصه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


يضبط دالة المقارنة المستخدمة في اختبار العمق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | القيمة الجديدة |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


تمكين أو تعطيل كتابة العمق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


تمكين أو تعطيل اختبار العمق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


يضبط طريقة دمج اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | القيمة الجديدة |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


يضبط أي ترتيب هو الوجه الأمامي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | القيمة الجديدة |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


يضبط وضع عرض المضلع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | القيمة الجديدة |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


تمكين أو تعطيل اختبار المقص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


يضبط طريقة دمج اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | القيمة الجديدة |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


يضبط القناع الذي يتم تطبيق عملية AND عليه مع كل من القيمة المرجعية والقيمة المخزنة للستينسل عند الانتهاء من الاختبار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


يضبط القيمة المرجعية لاختبار الستينسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


تمكين أو تعطيل اختبار القالب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

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

