---
title: "IVertexBuffer"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يحتوي مخزن الرؤوس على بيانات رؤوس المضلعات التي سيتم إرسالها إلى خط أنابيب العرض."
type: docs
weight: 259
url: /ar/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

يحتوي مخزن الرؤوس على بيانات رؤوس المضلعات التي سيتم إرسالها إلى خط أنابيب العرض.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | يحصل على تعريف القمة |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | تحميل بيانات القمة من [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | تحميل البيانات من مصفوفة |
| [loadData(long data, int size)](#loadData-long-int-) | تحميل البيانات من الموضع المحدد |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


يحصل على تعريف القمة

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


تحميل بيانات القمة من [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


تحميل البيانات من مصفوفة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مصفوفة | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


تحميل البيانات من الموضع المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | long |  |
| الحجم | int |  |

