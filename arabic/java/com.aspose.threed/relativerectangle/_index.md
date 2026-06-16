---
title: "RelativeRectangle"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "المستطيل النسبي  الصيغة بين المكوّن النسبي والقيمة المطلقة هي  Scale  Reference Width  offset  لذا إذا أردنا تمثيل قيمة مطلقة، اترك جميع حقول المقياس صفرًا واستخدم حقول الإزاحة بدلاً من ذلك."
type: docs
weight: 147
url: /ar/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

مستطيل نسبي الصيغة بين المكوّن النسبي والقيمة المطلقة هي: Scale \* (Reference Width) + offset لذا إذا أردنا تمثيله كقيمة مطلقة، اترك جميع حقول المقياس صفرًا، واستخدم حقول الإزاحة بدلاً من ذلك.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | إنشاء [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | إنشاء [RelativeRectangle](../../com.aspose.threed/relativerectangle) مع جميع حقول الإزاحة صفرًا وحقول المقياس من المعلمات المعطاة. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | يحصل على الإزاحة للارتفاع |
| [getOffsetWidth()](#getOffsetWidth--) | يحصل على الإزاحة للعرض |
| [getOffsetX()](#getOffsetX--) | يحصل على الإزاحة للإحداثي X |
| [getOffsetY()](#getOffsetY--) | يحصل على الإزاحة للإحداثي Y |
| [getScaleHeight()](#getScaleHeight--) | الارتفاع النسبي |
| [getScaleWidth()](#getScaleWidth--) | العرض النسبي |
| [getScaleX()](#getScaleX--) | الإحداثي النسبي X |
| [getScaleY()](#getScaleY--) | الإحداثي النسبي Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | يضبط الإزاحة للارتفاع |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | يضبط الإزاحة للعرض |
| [setOffsetX(int value)](#setOffsetX-int-) | يضبط الإزاحة للإحداثي X |
| [setOffsetY(int value)](#setOffsetY-int-) | يضبط الإزاحة للإحداثي Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | الارتفاع النسبي |
| [setScaleWidth(float value)](#setScaleWidth-float-) | العرض النسبي |
| [setScaleX(float value)](#setScaleX-float-) | الإحداثي النسبي X |
| [setScaleY(float value)](#setScaleY-float-) | الإحداثي النسبي Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | تحويل المستطيل النسبي إلى مستطيل مطلق |
| [toString()](#toString--) | يحول قيمة هذه المثيلة إلى java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


إنشاء [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اليسار | int |  |
| أعلى | int |  |
| العرض | int |  |
| الارتفاع | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


استنساخ النسخة الحالية

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


إنشاء [RelativeRectangle](../../com.aspose.threed/relativerectangle) مع جميع حقول الإزاحة صفرًا وحقول المقياس من المعلمات المعطاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


يحصل على الإزاحة للارتفاع

**Returns:**
int - الإزاحة للارتفاع
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


يحصل على الإزاحة للعرض

**Returns:**
int - الإزاحة للعرض
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


يحصل على الإزاحة للإحداثي X

**Returns:**
int - الإزاحة لإحداثي X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


يحصل على الإزاحة للإحداثي Y

**Returns:**
int - الإزاحة لإحداثي Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


الارتفاع النسبي

**Returns:**
float - الارتفاع النسبي
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


العرض النسبي

**Returns:**
float - العرض النسبي
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


الإحداثي النسبي X

**Returns:**
float - إحداثي X النسبي
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


الإحداثي النسبي Y

**Returns:**
float - إحداثي Y النسبي
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


يضبط الإزاحة للارتفاع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


يضبط الإزاحة للعرض

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


يضبط الإزاحة للإحداثي X

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


يضبط الإزاحة للإحداثي Y

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


الارتفاع النسبي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


العرض النسبي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


الإحداثي النسبي X

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


الإحداثي النسبي Y

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


تحويل المستطيل النسبي إلى مستطيل مطلق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اليسار | int | يسار المستطيل |
| أعلى | int | أعلى المستطيل |
| العرض | int | عرض المستطيل |
| الارتفاع | int | ارتفاع المستطيل |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


يحول قيمة هذه المثيلة إلى java.lang.String.

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

