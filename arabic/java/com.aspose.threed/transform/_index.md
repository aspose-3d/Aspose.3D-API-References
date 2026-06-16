---
title: "تحويل"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يحتوي التحويل على معلومات تسمح بالوصول إلى ترجمة/تحجيم/دوران الكائنات أو مصفوفة التحويل بأقل تكلفة  يُستخدم هذا في التحويل المحلي."
type: docs
weight: 190
url: /ar/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

يحتوي التحويل على معلومات تسمح بالوصول إلى ترجمة/تحجيم/دوران الكائن أو مصفوفة التحويل بأقل تكلفة يُستخدم هذا في التحويل المحلي. **Example:** يوضح الكود التالي كيفية تغيير تحويل العقدة:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | يحصل على الدوران الممثَّل بزوايا أويلر، مقاسًا بالدرجة |
| [getGeometricRotation()](#getGeometricRotation--) | يحصل على دوران أويلر الهندسي (مقاس بالدرجة). |
| [getGeometricScaling()](#getGeometricScaling--) | يحصل على التحجيم الهندسي. |
| [getGeometricTranslation()](#getGeometricTranslation--) | يحصل على الترجمة الهندسية. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getPostRotation()](#getPostRotation--) | يحصل على الدوران اللاحق الممثّل بالدرجة |
| [getPreRotation()](#getPreRotation--) | يحصل على الدوران السابق الممثّل بالدرجة |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRotation()](#getRotation--) | يحصل على الدوران الممثَّل بالكوارتيرن. |
| [getRotationOffset()](#getRotationOffset--) | يحصل على إزاحة الدوران |
| [getRotationPivot()](#getRotationPivot--) | يحصل على محور الدوران |
| [getScaling()](#getScaling--) | يحصل على التحجيم |
| [getScalingOffset()](#getScalingOffset--) | يحصل على إزاحة التحجيم |
| [getScalingPivot()](#getScalingPivot--) | يحصل على محور التحجيم |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل على مصفوفة التحويل. |
| [getTranslation()](#getTranslation--) | يحصل على الترجمة |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | يضبط الدوران الممثل بزاوية أويلر، مقاسًا بالدرجة |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | يضبط زوايا أويلر بالدرجات للتحويل الحالي. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | يضبط دوران أويلر الهندسي(مقاسًا بالدرجة). |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | يضبط دوران أويلر الهندسي(مقاسًا بالدرجة). |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | يضبط التحجيم الهندسي. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | يضبط التحجيم الهندسي. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | يضبط الإزاحة الهندسية. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | يضبط الإزاحة الهندسية. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | يضبط ما بعد الدوران الممثل بالدرجة |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | يضبط ما بعد الدوران الممثل بالدرجة **Example:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | يضبط ما قبل الدوران الممثل بالدرجة |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | يضبط ما قبل الدوران الممثل بالدرجة **Example:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | يضبط الدوران الممثل بالكواترن. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | يضبط الدوران(كمكونات كواترن) للتحويل الحالي. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | يضبط إزاحة الدوران |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | يضبط محور الدوران |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | يضبط مقياس التحويل الحالي. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | يضبط التحجيم |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | يضبط إزاحة التحجيم |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | يضبط محور التحجيم |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | يضبط مصفوفة التحويل. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | يضبط الإزاحة |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | يضبط إزاحة التحويل الحالي. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getEulerAngles() {#getEulerAngles--}
```
public Vector3 getEulerAngles()
```


يحصل على الدوران الممثَّل بزوايا أويلر، مقاسًا بالدرجة

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
```
### getGeometricRotation() {#getGeometricRotation--}
```
public Vector3 getGeometricRotation()
```


يحصل على دوران أويلر الهندسي(مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تأثير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


يحصل على التحجيم الهندسي. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric scaling. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
```
### getGeometricTranslation() {#getGeometricTranslation--}
```
public Vector3 getGeometricTranslation()
```


يحصل على الإزاحة الهندسية. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric translation. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
```
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


يحصل على الدوران اللاحق الممثّل بالدرجة

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
```
### getPreRotation() {#getPreRotation--}
```
public Vector3 getPreRotation()
```


يحصل على الدوران السابق الممثّل بالدرجة

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
```
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
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


يحصل على الدوران الممثَّل بالكوارتيرن.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
```
### getRotationOffset() {#getRotationOffset--}
```
public Vector3 getRotationOffset()
```


يحصل على إزاحة الدوران

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


يحصل على محور الدوران

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


يحصل على التحجيم

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling **Example:**

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
```
### getScalingOffset() {#getScalingOffset--}
```
public Vector3 getScalingOffset()
```


يحصل على إزاحة التحجيم

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


يحصل على محور التحجيم

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


يحصل على مصفوفة التحويل.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Remarks:** Assign on this will reset the [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) and [getRotation](../../com.aspose.threed/transform\#getRotation), the [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) and [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) will not be affected. **Example:**

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


يحصل على الترجمة

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
```
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
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


يضبط الدوران الممثل بزاوية أويلر، مقاسًا بالدرجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


يضبط زوايا أويلر بالدرجات للتحويل الحالي. **مثال:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricRotation(Vector3 value) {#setGeometricRotation-com.aspose.threed.Vector3-}
```
public void setGeometricRotation(Vector3 value)
```


يضبط دوران أويلر الهندسي (مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


يضبط دوران أويلر الهندسي (مقاسًا بالدرجة). التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه. **مثال:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricScaling(Vector3 value) {#setGeometricScaling-com.aspose.threed.Vector3-}
```
public void setGeometricScaling(Vector3 value)
```


يضبط التحجيم الهندسي. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


يضبط التحجيم الهندسي. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه. **مثال:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricTranslation(Vector3 value) {#setGeometricTranslation-com.aspose.threed.Vector3-}
```
public void setGeometricTranslation(Vector3 value)
```


يضبط الإزاحة الهندسية. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


يضبط الإزاحة الهندسية. التحويل الهندسي يؤثر فقط على الكيانات المرفقة ويترك العقد الفرعية دون تغيير. سيتم دمجه كتحويل محلي عند تصدير التحويل الهندسي إلى أنواع الملفات التي لا تدعمه. **مثال:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


يضبط ما بعد الدوران الممثل بالدرجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


يضبط ما بعد الدوران الممثل بالدرجة **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setPreRotation(Vector3 value) {#setPreRotation-com.aspose.threed.Vector3-}
```
public void setPreRotation(Vector3 value)
```


يضبط ما قبل الدوران الممثل بالدرجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


يضبط ما قبل الدوران الممثل بالدرجة **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


يضبط الدوران الممثل بالكواترن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


يضبط دوران (كمكونات رباعية) للتحويل الحالي. **مثال:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rw | double |  |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setRotationOffset(Vector3 value) {#setRotationOffset-com.aspose.threed.Vector3-}
```
public void setRotationOffset(Vector3 value)
```


يضبط إزاحة الدوران

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


يضبط محور الدوران

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


يضبط مقياس التحويل الحالي. **مثال:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setScaling(Vector3 value) {#setScaling-com.aspose.threed.Vector3-}
```
public void setScaling(Vector3 value)
```


يضبط التحجيم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


يضبط إزاحة التحجيم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


يضبط محور التحجيم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


يضبط مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | القيمة الجديدة **ملاحظة:** تعيين على هذا سيعيد ضبط [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) و[getRotation](../../com.aspose.threed/transform\#getRotation)، بينما [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) و[getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) لن تتأثر. **مثال:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


يضبط الإزاحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة **Example:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


يضبط إزاحة التحويل الحالي. **مثال:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

