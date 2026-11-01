---
title: "IIndexBuffer"
second_title: "مرجع Aspose.3D لـ Java API"
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
| [getCount()](#getCount--) | يحصل على عدد الفهارس في هذا المخزن المؤقت. |
| [getIndexDataType()](#getIndexDataType--) | يحصل على نوع البيانات لكل عنصر. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | تحميل بيانات الفهارس من [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | تحميل بيانات الفهارس |
| [loadData(short[] indices)](#loadData-short---) | تحميل بيانات الفهارس |
### getCount() {#getCount--}
```
public abstract int getCount()
```


يحصل على عدد الفهارس في هذا المخزن المؤقت.

**Returns:**
int - عدد الفهارس في هذا المخزن المؤقت.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


يحصل على نوع البيانات لكل عنصر.

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


تحميل بيانات الفهارس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المؤشرات | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


تحميل بيانات الفهارس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المؤشرات | short[] |  |

