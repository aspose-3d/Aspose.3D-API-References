---
title: "Material"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "المادة تُعرّف المعلمات اللازمة للمظهر البصري للهندسة."
type: docs
weight: 98
url: /ar/java/com.aspose.threed/material/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class Material extends A3DObject implements Iterable<TextureSlot>
```

المادة تُعرّف المعلمات اللازمة للمظهر البصري للهندسة. Aspose.3D توفر نموذج التظليل لـ [LambertMaterial](../../com.aspose.threed/lambertmaterial), [PhongMaterial](../../com.aspose.threed/phongmaterial) و[ShaderMaterial](../../com.aspose.threed/shadermaterial) **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     for(var slot : mat)
     {
         System.out.printf("Texture slot %s = %s", slot.getSlotName(), slot.getTexture());
     }
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج محيطي. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج منتشر. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج مشع. |
| [MAP_NORMAL](#MAP-NORMAL) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج عادي. |
| [MAP_SPECULAR](#MAP-SPECULAR) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج انعكاسي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | يحصل على النسيج من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معامل المعالج |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يحصل على المُعدد لتعداد فتحات النسيج الداخلية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | يعيّن النسيج للفتحة المحددة |
| [toString()](#toString--) | يقوم بتنسيق الكائن إلى سلسلة |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج محيطي.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج منتشر.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج مشع.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج عادي.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج انعكاسي.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


يحصل على النسيج من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معامل المعالج

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| slotName | java.lang.String | اسم الفتحة. |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


يحصل على المُعدد لتعداد فتحات النسيج الداخلية.

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
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

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


يعيّن النسيج للفتحة المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| slotName | java.lang.String | اسم الفتحة. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | الملمس. **Example:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### toString() {#toString--}
```
public String toString()
```


يقوم بتنسيق الكائن إلى سلسلة

**Returns:**
java.lang.String - سلسلة الكائن
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

