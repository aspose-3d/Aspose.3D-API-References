---
title: "PolygonBuilder"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "فئة مساعدة لبناء مضلع لـ  Example"
type: docs
weight: 133
url: /ar/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

فئة مساعدة لبناء مضلع لـ [Mesh](../../com.aspose.threed/mesh) **مثال:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

يساوي :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

إذا كانت جميع الفهارس جاهزة للاستخدام، يُفضَّل [Mesh](../../com.aspose.threed/mesh)، وإلا فسيكون [PolygonBuilder](../../com.aspose.threed/polygonbuilder) خيارًا أفضل.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | يُنشئ مثيلًا جديدًا للفئة [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | يضيف فهرس رأس إلى المضلع |
| [begin()](#begin--) | يبدأ في إضافة مضلع جديد |
| [end()](#end--) | ينهي إنشاء المضلع |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


يُنشئ مثيلًا جديدًا للفئة [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | على أي شبكة يتم بناء المضلع. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


يضيف فهرس رأس إلى المضلع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int |  |

### begin() {#begin--}
```
public void begin()
```


يبدأ في إضافة مضلع جديد

### end() {#end--}
```
public void end()
```


ينهي إنشاء المضلع

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

