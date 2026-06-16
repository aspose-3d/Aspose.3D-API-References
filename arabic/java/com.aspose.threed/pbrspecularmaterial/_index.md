---
title: "PbrSpecularMaterial"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مادة للتصيير القائم على الفيزياء تعتمد على اللون المنتشر/specular/اللمعان."
type: docs
weight: 122
url: /ar/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

مادة للتصيير القائم على الفيزياء تعتمد على اللون المنتشر/specular/اللمعان.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | منشئ الفئة [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## الحقول

| حقل | الوصف |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج محيطي. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج منتشر. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج مشع. |
| [MAP_NORMAL](#MAP-NORMAL) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج عادي. |
| [MAP_SPECULAR](#MAP-SPECULAR) | يُستخدم في [setTexture](../../com.aspose.threed/material\#setTexture) لتعيين تخطيط نسيج انعكاسي. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | خريطة القوام لللمعان الانعكاسي |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | يحصل على اللون المنتشر للمادة، القيمة الافتراضية هي (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | يحصل على القوام للانتشار |
| [getEmissiveColor()](#getEmissiveColor--) | يحصل على اللون المنبعث، القيمة الافتراضية هي (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | يحصل على القوام للإنبعاث |
| [getGlossinessFactor()](#getGlossinessFactor--) | يحصل على اللمعان (النعومة) للمادة، 1 يعني ناعماً تماماً و0 يعني خشناً تماماً، القيمة الافتراضية هي 1، النطاق هو [0, 1] |
| [getName()](#getName--) | يحصل على الاسم. |
| [getNormalTexture()](#getNormalTexture--) | يحصل على القوام لتخطيط العادي |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getSpecular()](#getSpecular--) | يحصل على اللون الانعكاسي للمادة، القيمة الافتراضية هي (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | يحصل على القوام للون الانعكاسي، القناة RGB تخزن اللون الانعكاسي والقناة A تخزن اللمعان. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | يحصل على النسيج من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معامل المعالج |
| [getTransparency()](#getTransparency--) | يحصل على عامل الشفافية. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يحصل على المُعدد لتعداد فتحات النسيج الداخلية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | يضبط اللون المنتشر للمادة، القيمة الافتراضية هي (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | يضبط القوام للانتشار |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | يضبط اللون المنبعث، القيمة الافتراضية هي (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | يضبط النسيج للانبعاث |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | يضبط اللمعان (النعومة) للمادة، 1 يعني ناعم تمامًا و0 يعني خشن تمامًا، القيمة الافتراضية هي 1، النطاق هو [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | يضبط نسيج تمثيل العادي |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | يضبط لون الانعكاس للمادة، القيمة الافتراضية هي (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | يضبط النسيج للون الانعكاس، القناة RGB تخزن لون الانعكاس والقناة A تخزن اللمعان. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | يعيّن النسيج للفتحة المحددة |
| [setTransparency(double value)](#setTransparency-double-) | يضبط عامل الشفافية. |
| [toString()](#toString--) | يقوم بتنسيق الكائن إلى سلسلة |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


منشئ الفئة [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


خريطة القوام لللمعان الانعكاسي

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
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


يحصل على اللون المنتشر للمادة، القيمة الافتراضية هي (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


يحصل على القوام للانتشار

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


يحصل على اللون المنبعث، القيمة الافتراضية هي (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


يحصل على القوام للإنبعاث

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


يحصل على اللمعان (النعومة) للمادة، 1 يعني ناعماً تماماً و0 يعني خشناً تماماً، القيمة الافتراضية هي 1، النطاق هو [0, 1]

**Returns:**
double - اللمعان (النعومة) للمادة، 1 يعني ناعم تمامًا و0 يعني خشن تمامًا، القيمة الافتراضية هي 1، النطاق هو [0, 1]
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


يحصل على القوام لتخطيط العادي

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


يحصل على اللون الانعكاسي للمادة، القيمة الافتراضية هي (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


يحصل على القوام للون الانعكاسي، القناة RGB تخزن اللون الانعكاسي والقناة A تخزن اللمعان.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


يضبط اللون المنتشر للمادة، القيمة الافتراضية هي (1, 1, 1)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


يضبط القوام للانتشار

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | القيمة الجديدة |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


يضبط اللون المنبعث، القيمة الافتراضية هي (0, 0, 0)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


يضبط النسيج للانبعاث

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | القيمة الجديدة |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


يضبط اللمعان (النعومة) للمادة، 1 يعني ناعم تمامًا و0 يعني خشن تمامًا، القيمة الافتراضية هي 1، النطاق هو [0, 1]

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


يضبط نسيج تمثيل العادي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | القيمة الجديدة |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


يضبط لون الانعكاس للمادة، القيمة الافتراضية هي (1, 1, 1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


يضبط النسيج للون الانعكاس، القناة RGB تخزن لون الانعكاس والقناة A تخزن اللمعان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | القيمة الجديدة |

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

