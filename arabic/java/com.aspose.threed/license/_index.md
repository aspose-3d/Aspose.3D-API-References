---
title: "رخصة"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 93
url: /ar/java/com.aspose.threed/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

يوفر طرقًا لترخيص المكوّن.

لمعرفة المزيد، قم بزيارة مقالة الوثائق **Licensing and Subscription**.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [License()](#License--) | يقوم بتهيئة نسخة جديدة من هذه الفئة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | يرخص المكوّن. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


يقوم بتهيئة نسخة جديدة من هذه الفئة.

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


يرخص المكوّن.

استخدم هذه الطريقة لتحميل رخصة من تدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق يحتوي على الترخيص. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


يرخص المكوّن.

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على ملف JAR الخاص بمكوّن Aspose.

3. المجلد الذي يحتوي على ملف JAR الخاص بالعميل المستدعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | java.lang.String | يمكن أن يكون اسم ملف كامل أو مختصر. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

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

