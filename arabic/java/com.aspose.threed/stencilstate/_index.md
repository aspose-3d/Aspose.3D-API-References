---
title: "StencilState"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "حالات القالب لكل وجه."
type: docs
weight: 175
url: /ar/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

حالات القالب لكل وجه.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لكائن محدد. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | يحصل على دالة المقارنة المستخدمة في اختبار الـ stencil. |
| [getDepthFailAction()](#getDepthFailAction--) | يحصل على إجراء الـ stencil عندما ينجح اختبار الـ stencil لكن يفشل اختبار العمق. |
| [getFailAction()](#getFailAction--) | يحصل على إجراء الـ stencil عندما يفشل اختبار الـ stencil. |
| [getPassAction()](#getPassAction--) | يحصل على إجراء الـ stencil عندما ينجح كل من اختبار الـ stencil واختبار العمق. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة (hash code) لهذه المثيلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | يضبط دالة المقارنة المستخدمة في اختبار الـ stencil. |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | يضبط إجراء الـ stencil عندما ينجح اختبار الـ stencil لكن يفشل اختبار العمق. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | يضبط إجراء الـ stencil عندما يفشل اختبار الـ stencil. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | يضبط إجراء الـ stencil عندما ينجح كل من اختبار الـ stencil واختبار العمق. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


يحصل على دالة المقارنة المستخدمة في اختبار الـ stencil.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


يحصل على إجراء الـ stencil عندما ينجح اختبار الـ stencil لكن يفشل اختبار العمق.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


يحصل على إجراء الـ stencil عندما يفشل اختبار الـ stencil.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


يحصل على إجراء الـ stencil عندما ينجح كل من اختبار الـ stencil واختبار العمق.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


يضبط دالة المقارنة المستخدمة في اختبار الـ stencil.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | القيمة الجديدة |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


يضبط إجراء الـ stencil عندما ينجح اختبار الـ stencil لكن يفشل اختبار العمق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | القيمة الجديدة |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


يضبط إجراء الـ stencil عندما يفشل اختبار الـ stencil.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | القيمة الجديدة |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


يضبط إجراء الـ stencil عندما ينجح كل من اختبار الـ stencil واختبار العمق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | القيمة الجديدة |

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

