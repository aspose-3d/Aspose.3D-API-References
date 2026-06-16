---
title: "PhongMaterial"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مادة لنموذج إضاءة بلين-فونغ."
type: docs
weight: 126
url: /ar/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

مادة لنموذج إضاءة بلين-فونغ.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | يُنشئ مثلاً جديدًا من الفئة [PhongMaterial](../../com.aspose.threed/phongmaterial). |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | يُنشئ مثلاً جديدًا من الفئة [PhongMaterial](../../com.aspose.threed/phongmaterial). |
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
| [getAmbientColor()](#getAmbientColor--) | يحصل على اللون المحيطي |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | يحصل على اللون المنتشر |
| [getEmissiveColor()](#getEmissiveColor--) | يحصل على اللون المشع |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getReflectionColor()](#getReflectionColor--) | يحصل على لون الانعكاس. |
| [getReflectionFactor()](#getReflectionFactor--) | يحصل على تخفيض لون الانعكاس. |
| [getShininess()](#getShininess--) | يحصل على اللمعان، وهذا يتحكم في حجم الإبراز اللامع. |
| [getSpecularColor()](#getSpecularColor--) | يحصل على اللون اللامع. |
| [getSpecularFactor()](#getSpecularFactor--) | يحصل على معامل اللمعان. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | يحصل على النسيج من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معامل المعالج |
| [getTransparency()](#getTransparency--) | يحصل على عامل الشفافية. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على اللون الشفاف. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يحصل على المُعدد لتعداد فتحات النسيج الداخلية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | يضبط اللون المحيطي |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | يضبط اللون المنتشر |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | يضبط اللون المشع |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | يضبط لون الانعكاس. |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | يضبط تخفيض لون الانعكاس. |
| [setShininess(double value)](#setShininess-double-) | يضبط اللمعان، هذا يتحكم في حجم الإضاءة اللامعة. |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | يضبط لون اللمعان. |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | يضبط عامل اللمعان. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | يعيّن النسيج للفتحة المحددة |
| [setTransparency(double value)](#setTransparency-double-) | يضبط عامل الشفافية. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | يضبط اللون الشفاف. |
| [toString()](#toString--) | يقوم بتنسيق الكائن إلى سلسلة |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


يُنشئ مثلاً جديدًا من الفئة [PhongMaterial](../../com.aspose.threed/phongmaterial).

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


يُنشئ مثلاً جديدًا من الفئة [PhongMaterial](../../com.aspose.threed/phongmaterial).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


يحصل على اللون المحيطي

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


يحصل على اللون المنتشر

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


يحصل على اللون المشع

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


يحصل على لون الانعكاس.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


يحصل على تخفيض لون الانعكاس.

**Returns:**
double - تخفيض لون الانعكاس.
### getShininess() {#getShininess--}
```
public double getShininess()
```


يحصل على اللمعان، هذا يتحكم في حجم الإضاءة اللامعة. صيغة اللمعان: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - اللمعان، هذا يتحكم في حجم الإضاءة اللامعة. صيغة اللمعان: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


يحصل على اللون اللامع.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


يحصل على عامل اللمعان. صيغة اللمعان: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - عامل اللمعان. صيغة اللمعان: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
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
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


يحصل على معامل الشفافية. يجب أن يكون المعامل ضمن النطاق بين 0 (0٪، غير شفاف تمامًا) و 1 (100٪، شفاف تمامًا). أي قيمة معامل غير صالحة سيتم تثبيتها.

**Returns:**
double - معامل الشفافية. يجب أن يكون المعامل ضمن النطاق بين 0 (0٪، غير شفاف تمامًا) و 1 (100٪، شفاف تمامًا). أي قيمة معامل غير صالحة سيتم تثبيتها.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


يحصل على اللون الشفاف.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


يضبط اللون المحيطي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


يضبط اللون المنتشر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


يضبط اللون المشع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


يضبط لون الانعكاس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


يضبط تخفيض لون الانعكاس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


يضبط اللمعان، هذا يتحكم في حجم الإضاءة اللامعة. صيغة اللمعان: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


يضبط لون اللمعان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


يضبط عامل اللمعان. صيغة اللمعان: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

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

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


يضبط معامل الشفافية. يجب أن يكون المعامل ضمن النطاق بين 0 (0٪، غير شفاف تمامًا) و 1 (100٪، شفاف تمامًا). أي قيمة معامل غير صالحة سيتم تثبيتها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


يضبط اللون الشفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

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

