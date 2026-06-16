---
title: "PbrMaterial"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مادة للتصيير القائم على الفيزياء تعتمد على لون الألبيدو/المعدن/الخشونة."
type: docs
weight: 121
url: /ar/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

مادة للتصيير القائم على الفيزياء تعتمد على لون الألبيدو/المعدن/الخشونة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | إنشاء نسخة مادة PBR افتراضية |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | إنشاء مادة PBR افتراضية مع قيمة لون الألبيدو المحددة. |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | السماح بتحويل مادة أخرى إلى PbrMaterial **Example:** |
| [getAlbedo()](#getAlbedo--) | يحصل على اللون الأساسي للمادة |
| [getAlbedoTexture()](#getAlbedoTexture--) | يحصل على الملمس للألبيدو |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | يحصل على اللون المشع |
| [getEmissiveTexture()](#getEmissiveTexture--) | يحصل على القوام للإنبعاث |
| [getMetallicFactor()](#getMetallicFactor--) | يحصل على معدنية المادة، القيمة 1 تعني أن المادة معدن والقيمة 0 تعني أن المادة عازلة. |
| [getMetallicRoughness()](#getMetallicRoughness--) | يحصل على الملمس للمعدن (في قناة R) والخشونة (في قناة G) |
| [getName()](#getName--) | يحصل على الاسم. |
| [getNormalTexture()](#getNormalTexture--) | يحصل على القوام لتخطيط العادي |
| [getOcclusionFactor()](#getOcclusionFactor--) | يحصل على عامل الإغلاق المحيطي |
| [getOcclusionTexture()](#getOcclusionTexture--) | يحصل على الملمس للإغلاق المحيطي |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRoughnessFactor()](#getRoughnessFactor--) | يحصل على خشونة المادة، القيمة 1 تعني أن المادة خشنة تمامًا والقيمة 0 تعني أن المادة ناعمة تمامًا |
| [getSpecularTexture()](#getSpecularTexture--) | يحصل على الملمس للون الانعكاس |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | يحصل على النسيج من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معامل المعالج |
| [getTransparency()](#getTransparency--) | يحصل على عامل الشفافية. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يحصل على المُعدد لتعداد فتحات النسيج الداخلية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | يضبط اللون الأساسي للمادة |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | يضبط القوام للـ albedo |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | يضبط اللون المشع |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | يضبط النسيج للانبعاث |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | يضبط معدنية المادة، القيمة 1 تعني أن المادة معدن والقيمة 0 تعني أن المادة عازلة. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | يضبط القوام للـ metallic (في قناة R) و roughness (في قناة G) |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | يضبط نسيج تمثيل العادي |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | يضبط عامل الإخفاء المحيطي |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | يضبط القوام للإخفاء المحيطي |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | يضبط خشونة المادة، القيمة 1 تعني أن المادة خشنة تمامًا والقيمة 0 تعني أن المادة ناعمة تمامًا |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | يضبط القوام للون الانعكاس |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | يعيّن النسيج للفتحة المحددة |
| [setTransparency(double value)](#setTransparency-double-) | يضبط عامل الشفافية. |
| [toString()](#toString--) | يقوم بتنسيق الكائن إلى سلسلة |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


إنشاء نسخة مادة PBR افتراضية

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


إنشاء مادة PBR افتراضية مع قيمة لون الألبيدو المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | قيمة لون الـ albedo الافتراضية |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


السماح بتحويل مادة أخرى إلى PbrMaterial **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


يحصل على اللون الأساسي للمادة

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


يحصل على الملمس للألبيدو

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


يحصل على اللون المشع

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


يحصل على القوام للإنبعاث

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


يحصل على معدنية المادة، القيمة 1 تعني أن المادة معدن والقيمة 0 تعني أن المادة عازلة.

**Returns:**
double - معدنية المادة، القيمة 1 تعني أن المادة معدن والقيمة 0 تعني أن المادة عازلة.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


يحصل على الملمس للمعدن (في قناة R) والخشونة (في قناة G)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


يحصل على عامل الإغلاق المحيطي

**Returns:**
double - عامل الإخفاء المحيطي
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


يحصل على الملمس للإغلاق المحيطي

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


يحصل على خشونة المادة، القيمة 1 تعني أن المادة خشنة تمامًا والقيمة 0 تعني أن المادة ناعمة تمامًا

**Returns:**
double - خشونة المادة، القيمة 1 تعني أن المادة خشنة تمامًا والقيمة 0 تعني أن المادة ناعمة تمامًا
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


يحصل على الملمس للون الانعكاس

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


يضبط اللون الأساسي للمادة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


يضبط القوام للـ albedo

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | القيمة الجديدة |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


يضبط اللون المشع

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


يضبط معدنية المادة، القيمة 1 تعني أن المادة معدن والقيمة 0 تعني أن المادة عازلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


يضبط القوام للـ metallic (في قناة R) و roughness (في قناة G)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | القيمة الجديدة |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


يضبط عامل الإخفاء المحيطي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


يضبط القوام للإخفاء المحيطي

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


يضبط خشونة المادة، القيمة 1 تعني أن المادة خشنة تمامًا والقيمة 0 تعني أن المادة ناعمة تمامًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


يضبط القوام للون الانعكاس

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

