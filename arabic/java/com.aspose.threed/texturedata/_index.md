---
title: "TextureData"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تحتوي هذه الفئة على البيانات الخام وتعريف تنسيق القوام."
type: docs
weight: 187
url: /ar/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

تحتوي هذه الفئة على البيانات الخام وتعريف تنسيق القوام.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | منشئ [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | ينشئ [TextureData](../../com.aspose.threed/texturedata) جديد ويخصص بيانات البكسل. |
| [TextureData()](#TextureData--) | منشئ [TextureData](../../com.aspose.threed/texturedata) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | تحميل نسيج من ملف |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | تحميل نسيج من تدفق |
| [getBytesPerPixel()](#getBytesPerPixel--) | عدد البايتات في البكسل |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | البايتات الخام لبيانات البكسل |
| [getHeight()](#getHeight--) | عدد البكسلات العمودية |
| [getName()](#getName--) | يحصل على الاسم. |
| [getPixelFormat()](#getPixelFormat--) | تنسيق البكسل |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getStride()](#getStride--) | عدد البايتات في سطر المسح. |
| [getWidth()](#getWidth--) | عدد البكسلات الأفقية |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | تعيين جميع البكسلات للقراءة/الكتابة |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | تعيين جميع البكسلات للقراءة/الكتابة بالتنسيق البكسلي المحدد |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | تعيين البكسلات المحددة بالمستطيل للقراءة/الكتابة بالتنسيق البكسلي المحدد |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | حفظ بيانات القوام في تنسيق الصورة المحدد |
| [save(String fileName)](#save-java.lang.String-) | حفظ بيانات القوام في ملف صورة |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | حفظ بيانات القوام في ملف صورة |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | تحويل تخطيط البكسل إلى تنسيق بكسلي جديد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


منشئ [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int |  |
| الارتفاع | int |  |
| stride | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| بيانات | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


ينشئ [TextureData](../../com.aspose.threed/texturedata) جديد ويخصص بيانات البكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int |  |
| الارتفاع | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


منشئ [TextureData](../../com.aspose.threed/texturedata)

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyName | java.lang.String | اسم الخاصية. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


تحميل نسيج من ملف

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


تحميل نسيج من تدفق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


عدد البايتات في البكسل

**Returns:**
int - عدد البايتات في بكسل واحد
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


البايتات الخام لبيانات البكسل

**Returns:**
byte[] - البايتات الخام لبيانات البكسل
### getHeight() {#getHeight--}
```
public int getHeight()
```


عدد البكسلات العمودية

**Returns:**
int - عدد البكسلات العمودية
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


تنسيق البكسل

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


يحصل على مجموعة جميع الخصائص.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


احصل على قيمة الخاصية المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |

**Returns:**
java.lang.Object - قيمة الخاصية التي تم العثور عليها
### getStride() {#getStride--}
```
public int getStride()
```


عدد البايتات في سطر المسح.

**Returns:**
int - عدد البايتات في سطر المسح.
### getWidth() {#getWidth--}
```
public int getWidth()
```


عدد البكسلات الأفقية

**Returns:**
int - عدد البكسلات الأفقية
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


تعيين جميع البكسلات للقراءة/الكتابة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | وضع التعيين |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


تعيين جميع البكسلات للقراءة/الكتابة بالتنسيق البكسلي المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | وضع التعيين |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | تنسيق البكسل |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


تعيين البكسلات المحددة بالمستطيل للقراءة/الكتابة بالتنسيق البكسلي المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | منطقة البكسلات التي سيتم الوصول إليها |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | وضع التعيين |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | تنسيق البكسل |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


يزيل خاصية ديناميكية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


إزالة الخاصية المحددة التي تم التعرف عليها بالاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


حفظ بيانات القوام في تنسيق الصورة المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | الدفق الذي يحتوي على الصورة المحفوظة |
| تنسيق | java.lang.String | تنسيق الصورة، عادةً امتداد الملف |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


حفظ بيانات القوام في ملف صورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف حيث سيتم حفظ الصورة. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


حفظ بيانات القوام في ملف صورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف حيث سيتم حفظ الصورة. |
| تنسيق | java.lang.String | تنسيق الصورة للملف الناتج. |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


يضبط قيمة الخاصية المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |
| القيمة | java.lang.Object | قيمة الخاصية |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


تحويل تخطيط البكسل إلى تنسيق بكسلي جديد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | تنسيق البكسل الوجهة |

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

