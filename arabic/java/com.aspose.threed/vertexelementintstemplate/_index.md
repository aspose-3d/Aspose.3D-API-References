---
title: "VertexElementIntsTemplate"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "فئة مساعدة لتعريف تطبيقات ملموسة."
type: docs
weight: 212
url: /ar/java/com.aspose.threed/vertexelementintstemplate/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementIntsTemplate extends VertexElement
```

فئة مساعدة لتعريف تطبيقات ملموسة لـ [VertexElement](../../com.aspose.threed/vertexelement).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clear()](#clear--) | يزيل جميع العناصر من مصفوفات الـ direct والـ index. |
| [clone(boolean withData)](#clone-boolean-) | إنشاء نسخة عميقة من عنصر القمة. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementIntsTemplate target)](#copyTo-com.aspose.threed.VertexElementIntsTemplate-) | ينسخ البيانات إلى العنصر المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | يحصل على بيانات القمة. |
| [getIndices()](#getIndices--) | يحصل على بيانات الفهارس. |
| [getMappingMode()](#getMappingMode--) | يحصل على طريقة تعيين العنصر. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getReferenceMode()](#getReferenceMode--) | يحصل على طريقة الإشارة إلى العنصر. |
| [getVertexElementType()](#getVertexElementType--) | يحصل على نوع الـ [VertexElement](../../com.aspose.threed/vertexelement). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(int[] data)](#setData-int---) | تحميل البيانات. |
| [setIndices(int[] data)](#setIndices-int---) | تحميل الفهارس. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | يضبط طريقة تعيين العنصر. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | يضبط طريقة الإشارة إلى العنصر. |
| [toString()](#toString--) | تمثيل نصي لعنصر القمة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clear() {#clear--}
```
public void clear()
```


يزيل جميع العناصر من مصفوفات الـ direct والـ index.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


إنشاء نسخة عميقة من عنصر القمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| withData | boolean | إنشاء نسخة من القمة مع مصفوفة الـ direct ومصفوفة الـ index. |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### copyTo(VertexElementIntsTemplate target) {#copyTo-com.aspose.threed.VertexElementIntsTemplate-}
```
public void copyTo(VertexElementIntsTemplate target)
```


ينسخ البيانات إلى العنصر المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [VertexElementIntsTemplate](../../com.aspose.threed/vertexelementintstemplate) | الهدف. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public List<Integer> getData()
```


يحصل على بيانات القمة.

**Returns:**
java.util.List<java.lang.Integer> - بيانات القمم
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


يحصل على بيانات الفهارس.

**Returns:**
java.util.List<java.lang.Integer> - بيانات الفهارس.
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


يحصل على طريقة تعيين العنصر.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


يحصل على طريقة الإشارة إلى العنصر.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


يحصل على نوع الـ [VertexElement](../../com.aspose.threed/vertexelement).

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(int[] data) {#setData-int---}
```
public void setData(int[] data)
```


تحميل البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | int[] |  |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


تحميل الفهارس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


يضبط طريقة تعيين العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


يضبط طريقة الإشارة إلى العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | القيمة الجديدة |

### toString() {#toString--}
```
public String toString()
```


تمثيل نصي لعنصر القمة.

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

