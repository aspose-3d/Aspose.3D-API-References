---
title: "NurbsDirection"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "كائن 3D  لديه اتجاهان الـ  و الـ  ، الـ  يحدد البيانات لكل اتجاه."
type: docs
weight: 113
url: /ar/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

كائن 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) لديه اتجاهان، الـ [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) و [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV)، الـ [NurbsDirection](../../com.aspose.threed/nurbsdirection) يحدد البيانات لكل اتجاه. الاتجاه في الواقع هو منحنى NURBS، وهذا يعني أنه يُعرّف أيضًا بواسطة [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder)، و [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors)، ومجموعة من نقاط التحكم المرجحة (المعرفة في [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | إنشاء نسخة جديدة من [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | يحصل على عدد نقاط التحكم في الاتجاه الحالي. |
| [getDegree()](#getDegree--) | يحصل على درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1 |
| [getDivisions()](#getDivisions--) | يحصل على عدد الأقسام بين نقاط التحكم المتجاورة في الاتجاه الحالي. |
| [getKnotVectors()](#getKnotVectors--) | يحصل على متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS. |
| [getMultiplicity()](#getMultiplicity--) | يحصل على التعددية. |
| [getOrder()](#getOrder--) | يحصل على ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى. |
| [getType()](#getType--) | يحصل على نوع الاتجاه الحالي. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | يضبط عدد نقاط التحكم في الاتجاه الحالي. |
| [setDegree(int value)](#setDegree-int-) | يضبط درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1 |
| [setDivisions(int value)](#setDivisions-int-) | يضبط عدد الأقسام بين نقاط التحكم المتجاورة في الاتجاه الحالي. |
| [setOrder(int value)](#setOrder-int-) | يضبط ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | يضبط نوع الاتجاه الحالي. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


إنشاء نسخة جديدة من [NurbsDirection](../../com.aspose.threed/nurbsdirection)

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
### getCount() {#getCount--}
```
public int getCount()
```


يحصل على عدد نقاط التحكم في الاتجاه الحالي.

**Returns:**
عدد صحيح - عدد نقاط التحكم في الاتجاه الحالي.
### getDegree() {#getDegree--}
```
public int getDegree()
```


يحصل على درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1

**Returns:**
int - درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


يحصل على عدد الأقسام بين نقاط التحكم المتجاورة في الاتجاه الحالي.

**Returns:**
int - عدد الأقسام بين نقاط التحكم المتجاورة في الاتجاه الحالي.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


يحصل على متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS.

**Returns:**
java.util.List<java.lang.Double> - متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


يحصل على التعددية.

**Returns:**
java.util.List<java.lang.Integer> - التعددية.
### getOrder() {#getOrder--}
```
public int getOrder()
```


يحصل على ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى.

**Returns:**
int - رتبة منحنى NURBS، تُحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة على المنحنى.
### getType() {#getType--}
```
public NurbsType getType()
```


يحصل على نوع الاتجاه الحالي.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
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




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


يضبط عدد نقاط التحكم في الاتجاه الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


يضبط درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


يضبط عدد الأقسام بين نقاط التحكم المتجاورة في الاتجاه الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


يضبط ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


يضبط نوع الاتجاه الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | القيمة الجديدة |

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

