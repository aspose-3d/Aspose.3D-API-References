---
title: "الملمس"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تعرف هذه الفئة القوام من ملف خارجي."
type: docs
weight: 184
url: /ar/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object، [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)، [com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

تعرف هذه الفئة القوام من ملف خارجي.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Texture()](#Texture--) | يُنشئ مثيلًا جديدًا للفئة [Texture](../../com.aspose.threed/texture). |
| [Texture(String name)](#Texture-java.lang.String-) | يُنشئ مثيلًا جديدًا للفئة [Texture](../../com.aspose.threed/texture). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAlpha()](#getAlpha--) | يحصل على قيمة ألفا الافتراضية للملمس. هذا صالح عندما يكون [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) هو [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). القيمة الافتراضية هي 1.0، ونطاق القيم الصالحة بين 0 و 1. |
| [getAlphaSource()](#getAlphaSource--) | يحصل على ما إذا كان الملمس يحدد قناة ألفا. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | يحصل على المحتوى الثنائي للملمس. |
| [getEnableMipMap()](#getEnableMipMap--) | يحصل على ما إذا كان الـ mipmap مفعلاً لهذا الملمس. |
| [getFileName()](#getFileName--) | يحصل على ملف الملمس المرتبط. |
| [getMagFilter()](#getMagFilter--) | يحصل على الفلتر للتكبير. |
| [getMinFilter()](#getMinFilter--) | يحصل على الفلتر للتصغير. |
| [getMipFilter()](#getMipFilter--) | يحصل على الفلتر لأخذ عينات مستوى الـ mip. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getUVRotation()](#getUVRotation--) | يحصل على دوران الملمس. |
| [getUVScale()](#getUVScale--) | يحصل على مقياس UV. |
| [getUVTranslation()](#getUVTranslation--) | يحصل على إزاحة UV. |
| [getWrapModeU()](#getWrapModeU--) | يحصل على أوضاع لف الملمس في U. |
| [getWrapModeV()](#getWrapModeV--) | يحصل على أوضاع لف الملمس في V. |
| [getWrapModeW()](#getWrapModeW--) | يحصل على أوضاع لف الملمس في W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setAlpha(double value)](#setAlpha-double-) | يضبط قيمة ألفا الافتراضية للملمس. هذا صالح عندما يكون [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) هو [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). القيمة الافتراضية هي 1.0، ونطاق القيم الصالحة بين 0 و 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | يضبط ما إذا كان الملمس يحدد قناة ألفا. |
| [setContent(byte[] value)](#setContent-byte---) | يضبط المحتوى الثنائي للملمس. |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | يضبط ما إذا كان الـ mipmap مفعلاً لهذا الملمس |
| [setFileName(String value)](#setFileName-java.lang.String-) | يضبط ملف الملمس المرتبط. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | يضبط الفلتر للتكبير. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | يضبط الفلتر للتصغير. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | يضبط الفلتر لأخذ عينات مستوى الـ mip. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRotation(double u, double v)](#setRotation-double-double-) | يضبط دوران الـ UV. |
| [setScale(double u, double v)](#setScale-double-double-) | يضبط مقياس الـ UV. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | يضبط إزاحة الـ UV. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | يضبط دوران الملمس |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | يضبط مقياس الـ UV. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | يضبط إزاحة الـ UV. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | يضبط أوضاع لف الملمس في U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | يضبط أوضاع لف الملمس في V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | يضبط أوضاع لف الملمس في W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


يُنشئ مثيلًا جديدًا للفئة [Texture](../../com.aspose.threed/texture).

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


يُنشئ مثيلًا جديدًا للفئة [Texture](../../com.aspose.threed/texture).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


يحصل على قيمة ألفا الافتراضية للملمس. هذا صالح عندما يكون [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) هو [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). القيمة الافتراضية هي 1.0، ونطاق القيم الصالحة بين 0 و 1.

**Returns:**
double - القيمة الافتراضية لألفا للملمس. هذا صالح عندما يكون [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) هو [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). القيمة الافتراضية هي 1.0، نطاق القيم الصالحة بين 0 و 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


يحصل على ما إذا كان الملمس يحدد قناة ألفا. القيمة الافتراضية هي [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContent() {#getContent--}
```
public byte[] getContent()
```


يحصل على المحتوى الثنائي للملمس. محتوى الملمس المدمج اختياري، يجب على المستخدم تحميل الملمس من ملف خارجي إذا كان مفقودًا.

**Returns:**
byte[] - المحتوى الثنائي للملمس. محتوى الملمس المدمج اختياري، يجب على المستخدم تحميل الملمس من ملف خارجي إذا كان مفقودًا.
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


يحصل على ما إذا كان الـ mipmap مفعلاً لهذا الملمس.

**Returns:**
boolean - ما إذا كان الـ mipmap مفعلاً لهذا الملمس
### getFileName() {#getFileName--}
```
public String getFileName()
```


يحصل على ملف الملمس المرتبط.

**Returns:**
java.lang.String - ملف الملمس المرتبط.
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


يحصل على الفلتر للتكبير.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


يحصل على الفلتر للتصغير.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


يحصل على الفلتر لأخذ عينات مستوى الـ mip.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


يحصل على دوران الملمس.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


يحصل على مقياس UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


يحصل على إزاحة UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


يحصل على أوضاع لف الملمس في U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


يحصل على أوضاع لف الملمس في V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


يحصل على أوضاع لف الملمس في W.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


يضبط قيمة ألفا الافتراضية للملمس. هذا صالح عندما يكون [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) هو [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). القيمة الافتراضية هي 1.0، ونطاق القيم الصالحة بين 0 و 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


يضبط ما إذا كان الملمس يحدد قناة ألفا. القيمة الافتراضية هي [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | القيمة الجديدة |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


يضبط المحتوى الثنائي للملمس. محتوى الملمس المدمج اختياري، يجب على المستخدم تحميل الملمس من ملف خارجي إذا كان مفقودًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] | القيمة الجديدة |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


يضبط ما إذا كان الـ mipmap مفعلاً لهذا الملمس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


يضبط ملف الملمس المرتبط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


يضبط الفلتر للتكبير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | القيمة الجديدة |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


يضبط الفلتر للتصغير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | القيمة الجديدة |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


يضبط الفلتر لأخذ عينات مستوى الـ mip.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | القيمة الجديدة |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


يضبط دوران الـ UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


يضبط مقياس الـ UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


يضبط إزاحة الـ UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


يضبط دوران الملمس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


يضبط مقياس الـ UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


يضبط إزاحة الـ UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


يضبط أوضاع لف الملمس في U.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | القيمة الجديدة |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


يضبط أوضاع لف الملمس في V.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | القيمة الجديدة |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


يضبط أوضاع لف الملمس في W.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | القيمة الجديدة |

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

