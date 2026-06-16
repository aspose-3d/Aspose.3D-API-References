---
title: "IBuffer"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "الواجهة الأساسية لجميع المخازن المُدارة المستخدمة في التصيير"
type: docs
weight: 239
url: /ar/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

الواجهة الأساسية لجميع المخازن المُدارة المستخدمة في التصيير
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | حجم هذا المخزن المؤقت بالبايت |
| [loadData(byte[] data)](#loadData-byte---) | حمّل البيانات في المخزن المؤقت الحالي |
### getSize() {#getSize--}
```
public abstract int getSize()
```


حجم هذا المخزن المؤقت بالبايت

**Returns:**
int - حجم هذا المخزن المؤقت بالبايت
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


حمّل البيانات في المخزن المؤقت الحالي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] |  |

