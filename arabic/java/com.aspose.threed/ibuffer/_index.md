---
title: "IBuffer"
second_title: "مرجع Aspose.3D لـ Java API"
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
| [getSize()](#getSize--) | حجم هذه الذاكرة المؤقتة بالبايت |
| [loadData(byte[] data)](#loadData-byte---) | حمّل البيانات في الذاكرة المؤقتة الحالية |
### getSize() {#getSize--}
```
public abstract int getSize()
```


حجم هذه الذاكرة المؤقتة بالبايت

**Returns:**
int - حجم هذه الذاكرة المؤقتة بالبايت
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


حمّل البيانات في الذاكرة المؤقتة الحالية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] |  |

