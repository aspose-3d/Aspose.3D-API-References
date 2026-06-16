---
title: "IIndexBuffer"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مخزن الفهرس يصف الهندسة المستخدمة في أنابيب التصيير."
type: docs
weight: 242
url: /ar/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

مخزن الفهرس يصف الهندسة المستخدمة في أنابيب التصيير.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | الحصول على عدد الفهارس في هذا buffer. |
| [getIndexDataType()](#getIndexDataType--) | الحصول على نوع البيانات لكل عنصر. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | تحميل بيانات الفهارس من [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | تحميل بيانات المؤشر |
| [loadData(short[] indices)](#loadData-short---) | تحميل بيانات المؤشر |
### getCount() {#getCount--}
```
public abstract int getCount()
```


الحصول على عدد الفهارس في هذا buffer.

**Returns:**
int - عدد الفهارس في هذا المخزن المؤقت.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


الحصول على نوع البيانات لكل عنصر.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


تحميل بيانات الفهارس من [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


تحميل بيانات المؤشر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| indices | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


تحميل بيانات المؤشر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| indices | short[] |  |

