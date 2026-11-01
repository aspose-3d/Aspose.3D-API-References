---
title: "VertexElement"
second_title: "مرجع Aspose.3D لـ Java API"
description: "الفئة الأساسية لعناصر القمة."
type: docs
weight: 207
url: /ar/java/com.aspose.threed/vertexelement/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.IIndexedVertexElement](../../com.aspose.threed/iindexedvertexelement)
```
public abstract class VertexElement implements IIndexedVertexElement
```

الفئة الأساسية لعناصر الرؤوس. يتم تحديد نوع عنصر الرأس بواسطة VertexElementType. يصف VertexElement كيفية ربط عنصر الرأس بسطح هندسي وكيفية ترتيب معلومات الربط في الذاكرة. يحتوي VertexElement على Normals، UVs أو أنواع أخرى من المعلومات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clear()](#clear--) | يمسح جميع البيانات من عنصر الرأس هذا. |
| [clone(boolean withData)](#clone-boolean-) | استنساخ عميق لعنصر الرأس |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIndices()](#getIndices--) | يحصل على بيانات الفهارس |
| [getMappingMode()](#getMappingMode--) | يحصل على كيفية تعيين العنصر. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getReferenceMode()](#getReferenceMode--) | يحصل على كيفية إشارة العنصر. |
| [getVertexElementType()](#getVertexElementType--) | يحصل على نوع الـ [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setIndices(int[] data)](#setIndices-int---) | تحميل الفهارس |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | يحدد كيفية تعيين العنصر. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | يحدد كيفية إشارة العنصر. |
| [toString()](#toString--) | تمثيل السلسلة لعنصر الرأس. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clear() {#clear--}
```
public abstract void clear()
```


يمسح جميع البيانات من عنصر الرأس هذا.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


استنساخ عميق لعنصر الرأس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| withData | boolean | استنساخ الرأس مع مصفوفة direct ومصفوفة index |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
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
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


يحصل على بيانات الفهارس

**Returns:**
java.util.List<java.lang.Integer> - بيانات الفهارس
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


يحصل على كيفية تعيين العنصر.

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


يحصل على كيفية إشارة العنصر.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


يحصل على نوع الـ [VertexElement](../../com.aspose.threed/vertexelement)

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




### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


تحميل الفهارس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


يحدد كيفية تعيين العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | قيمة جديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


يحدد كيفية إشارة العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | قيمة جديدة |

### toString() {#toString--}
```
public String toString()
```


تمثيل السلسلة لعنصر الرأس.

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

