---
title: "Dönüşüm"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir dönüşüm, nesnelerin çeviri/ölçekleme/dönme veya dönüşüm matrisine minimum maliyetle erişim sağlayan bilgileri içerir  Bu, yerel dönüşüm tarafından kullanılır."
type: docs
weight: 190
url: /tr/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

Bir dönüşüm, nesnenin çeviri/ölçekleme/dönme veya dönüşüm matrisine minimum maliyetle erişim sağlayan bilgileri içerir  Bu, yerel dönüşüm tarafından kullanılır. **Example:** Aşağıdaki kod, düğümün dönüşümünü nasıl değiştireceğinizi gösterir:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Euler açıları cinsinden derece ölçüsüyle temsil edilen dönüşüm alınır |
| [getGeometricRotation()](#getGeometricRotation--) | Geometrik Euler dönüşümünü (derece cinsinden ölçülür) alır. |
| [getGeometricScaling()](#getGeometricScaling--) | Geometrik ölçeklemeyi alır. |
| [getGeometricTranslation()](#getGeometricTranslation--) | Geometrik çeviriyi alır. |
| [getName()](#getName--) | Adı alır. |
| [getPostRotation()](#getPostRotation--) | Derece cinsinden temsil edilen sonrası dönüşümü alır |
| [getPreRotation()](#getPreRotation--) | Derece cinsinden temsil edilen ön dönüşümü alır |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRotation()](#getRotation--) | Kuaternion cinsinden temsil edilen dönüşüm alınır. |
| [getRotationOffset()](#getRotationOffset--) | Dönüşüm ofsetini alır |
| [getRotationPivot()](#getRotationPivot--) | Dönüş pivotunu alır |
| [getScaling()](#getScaling--) | Ölçeklemeyi alır |
| [getScalingOffset()](#getScalingOffset--) | Ölçekleme ofsetini alır |
| [getScalingPivot()](#getScalingPivot--) | Ölçekleme pivotunu alır |
| [getTransformMatrix()](#getTransformMatrix--) | Dönüşüm matrisi alınır. |
| [getTranslation()](#getTranslation--) | Çeviri alınır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | Derece cinsinden ölçülen Euler açılarıyla temsil edilen dönüşümü ayarlar |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | Mevcut dönüşümün Euler açılarını derece cinsinden ayarlar. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | Geometrik Euler dönüşümünü (derece cinsinden) ayarlar. |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | Geometrik Euler dönüşümünü (derece cinsinden) ayarlar. |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | Geometrik ölçeklemeyi ayarlar. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | Geometrik ölçeklemeyi ayarlar. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | Geometrik çeviriyi ayarlar. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | Geometrik çeviriyi ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | Derece cinsinden temsil edilen sonrası dönüşümü ayarlar |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | Derece cinsinden temsil edilen sonrası dönüşümü ayarlar **Example:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | Derece cinsinden temsil edilen ön dönüşümü ayarlar |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | Derece cinsinden temsil edilen ön dönüşümü ayarlar **Example:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | Kuaternion ile temsil edilen dönüşümü ayarlar. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | Mevcut dönüşümün dönüşümünü (kuaternion bileşenleri olarak) ayarlar. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | Dönüşüm ofsetini ayarlar |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | Dönüşüm pivotunu ayarlar |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | Mevcut dönüşümün ölçeğini ayarlar. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | Ölçeklemeyi ayarlar |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | Ölçekleme ofsetini ayarlar |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | Ölçekleme pivotunu ayarlar |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | Dönüşüm matrisini ayarlar. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | Çeviriyi ayarlar |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | Mevcut dönüşümün çevirisini ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty) veya native property(Identified by its name) olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyName | java.lang.String | Özellik adı. |

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


Euler açıları cinsinden derece ölçüsüyle temsil edilen dönüşüm alınır

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


Geometrik Euler dönüşümünü (derece cinsinden) alır. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Desteklemeyen dosya türlerine geometrik dönüşümü dışa aktardığınızda, yerel dönüşüm olarak birleştirilecektir.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


Geometrik ölçeklemeyi alır. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir.

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


Geometrik çeviriyi alır. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir.

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


Adı alır.

**Returns:**
java.lang.String - ad.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


Derece cinsinden temsil edilen sonrası dönüşümü alır

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


Derece cinsinden temsil edilen ön dönüşümü alır

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


Tüm özelliklerin koleksiyonunu alır.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Belirtilen özelliğin değerini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |

**Returns:**
java.lang.Object - Bulunan özelliğin değeri
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


Kuaternion cinsinden temsil edilen dönüşüm alınır.

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


Dönüşüm ofsetini alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


Dönüş pivotunu alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


Ölçeklemeyi alır

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


Ölçekleme ofsetini alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


Ölçekleme pivotunu alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


Dönüşüm matrisi alınır.

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


Çeviri alınır

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


Dinamik bir özelliği kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


İsimle tanımlanan belirtilen özelliği kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


Derece cinsinden ölçülen Euler açılarıyla temsil edilen dönüşümü ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


Mevcut dönüşümün Euler açılarını derece cinsinden ayarlar. **Örnek:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Geometrik Euler dönüşümünü (derece cinsinden ölçülür) ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


Geometrik Euler dönüşümünü (derece cinsinden ölçülür) ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir. **Örnek:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Geometrik ölçeklemeyi ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


Geometrik ölçeklemeyi ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir. **Örnek:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Geometrik çeviriyi ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


Geometrik çeviriyi ayarlar. Geometrik dönüşüm yalnızca ekli varlıkları etkiler ve alt düğümleri etkilemez. Geometrik dönüşümü desteklemeyen dosya türlerine dışa aktarırken yerel dönüşüm olarak birleştirilecektir. **Örnek:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


Derece cinsinden temsil edilen sonrası dönüşümü ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


Derece cinsinden temsil edilen sonrası dönüşümü ayarlar **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Derece cinsinden temsil edilen ön dönüşümü ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


Derece cinsinden temsil edilen ön dönüşümü ayarlar **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Belirtilen özelliğin değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |
| değer | java.lang.Object | Özelliğin değeri |

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


Kuaternion ile temsil edilen dönüşümü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


Mevcut dönüşümün rotasyonunu (kuaternion bileşenleri olarak) ayarlar. **Örnek:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Dönüşüm ofsetini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


Dönüşüm pivotunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


Mevcut dönüşümün ölçeğini ayarlar. **Örnek:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Ölçeklemeyi ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


Ölçekleme ofsetini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


Ölçekleme pivotunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


Dönüşüm matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | Yeni değer **Açıklamalar:** Bu atama, [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) ve [getRotation](../../com.aspose.threed/transform\#getRotation) işlevlerini sıfırlar, [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) ve [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) etkilenmez. **Örnek:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


Çeviriyi ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer **Örnek:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


Mevcut dönüşümün çevirisini ayarlar. **Örnek:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

