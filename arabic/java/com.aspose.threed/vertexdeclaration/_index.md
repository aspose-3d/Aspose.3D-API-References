---
title: "VertexDeclaration"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تصريح بنية رؤوس مخصصة معرفة"
type: docs
weight: 206
url: /ar/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

إعلان بنية رأس مُعرّف مخصّص
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | أضف حقل قمة جديد |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | أضف حقل قمة جديد |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | أضف حقل قمة جديد |
| [clear()](#clear--) | امسح جميع الحقول. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | يقارن هذه الحالة مع كائن محدد ويعيد إشارة إلى قيمهما النسبية. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة والكيان المحدد، الذي يجب أن يكون أيضًا كائنًا من نوع [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)، لهما نفس القيمة. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | أنشئ [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) استنادًا إلى تخطيط [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | يحصل على [VertexField](../../com.aspose.threed/vertexfield) حسب الفهرس |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | يحصل على عدد جميع الحقول المعرفة في هذا [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | سيتم إغلاق [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) عندما يتم استخدامه بواسطة [TriMesh](../../com.aspose.threed/trimesg)، ولا يُسمح بمزيد من التعديلات. |
| [getSize()](#getSize--) | حجم بنية القمة بالبايت. |
| [hashCode()](#hashCode--) | يرجع رمز التجزئة لهذا النص. |
| [iterator()](#iterator--) | يحصل على مُعدِّد للتنقل عبر جميع حقول القمة في هذه الحالة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | تمثيل نصي لـ [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


أضف حقل قمة جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataType | int | نوع البيانات لحقل القمة |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | كيف سيُستخدم هذا الحقل |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


أضف حقل قمة جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataType | int | نوع البيانات لحقل القمة |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | كيف سيُستخدم هذا الحقل |
| الفهرس | int | الفهرس للمعنى نفسه للحقل، -1 للتوليد التلقائي |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


أضف حقل قمة جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataType | int | نوع البيانات لحقل القمة |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | كيف سيُستخدم هذا الحقل |
| الفهرس | int | الفهرس للمعنى نفسه للحقل، -1 للتوليد التلقائي |
| الاسم المستعار | java.lang.String | الاسم المستعار للحقل |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


امسح جميع الحقول.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


يقارن هذه الحالة مع كائن محدد ويعيد إشارة إلى قيمهما النسبية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة والكيان المحدد، الذي يجب أن يكون أيضًا كائنًا من نوع [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)، لهما نفس القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


أنشئ [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) استنادًا إلى تخطيط [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | استخدم float بدلاً من النوع double |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


يحصل على [VertexField](../../com.aspose.threed/vertexfield) حسب الفهرس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


يحصل على عدد جميع الحقول المعرفة في هذا [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - عدد جميع الحقول المعرفة في هذه [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


سيتم إغلاق [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) عندما يتم استخدامه بواسطة [TriMesh](../../com.aspose.threed/trimesg)، ولا يُسمح بمزيد من التعديلات.

**Returns:**
boolean - سيتم إغلاق [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) عندما يتم استخدامها من قبل [TriMesh](../../com.aspose.threed/trimesh)، لا يُسمح بمزيد من التعديلات.
### getSize() {#getSize--}
```
public int getSize()
```


حجم بنية القمة بالبايت.

**Returns:**
int - حجم بنية الرأس بالبايت.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز التجزئة لهذا النص.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32 بت.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


يحصل على مُعدِّد للتنقل عبر جميع حقول القمة في هذه الحالة.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - عداد
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


تمثيل نصي لـ [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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

