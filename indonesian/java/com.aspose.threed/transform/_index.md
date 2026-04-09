---
title: Transformasi
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah transformasi berisi informasi yang memungkinkan akses ke translasi/skala/rotasi objek atau matriks transformasi dengan biaya minimal  Ini digunakan oleh transformasi lokal.
type: docs
weight: 190
url: /id/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

Sebuah transformasi berisi informasi yang memungkinkan akses ke translasi/skala/rotasi objek atau matriks transformasi dengan biaya minimal Ini digunakan oleh transformasi lokal. **Example:** Kode berikut menunjukkan cara mengubah transformasi node:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Mendapatkan rotasi yang direpresentasikan dalam sudut Euler, diukur dalam derajat |
| [getGeometricRotation()](#getGeometricRotation--) | Mendapatkan rotasi Euler geometrik (diukur dalam derajat). |
| [getGeometricScaling()](#getGeometricScaling--) | Mendapatkan skala geometrik. |
| [getGeometricTranslation()](#getGeometricTranslation--) | Mendapatkan translasi geometrik. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getPostRotation()](#getPostRotation--) | Mendapatkan post-rotasi yang direpresentasikan dalam derajat |
| [getPreRotation()](#getPreRotation--) | Mendapatkan pre-rotasi yang direpresentasikan dalam derajat |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRotation()](#getRotation--) | Mendapatkan rotasi yang direpresentasikan dalam quaternion. |
| [getRotationOffset()](#getRotationOffset--) | Mendapatkan offset rotasi |
| [getRotationPivot()](#getRotationPivot--) | Mendapatkan poros rotasi |
| [getScaling()](#getScaling--) | Mendapatkan skala |
| [getScalingOffset()](#getScalingOffset--) | Mendapatkan offset skala |
| [getScalingPivot()](#getScalingPivot--) | Mendapatkan poros skala |
| [getTransformMatrix()](#getTransformMatrix--) | Mendapatkan matriks transformasi. |
| [getTranslation()](#getTranslation--) | Mendapatkan translasi |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | Mengatur rotasi yang direpresentasikan dalam sudut Euler, diukur dalam derajat |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | Mengatur sudut Euler dalam derajat untuk transformasi saat ini. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | Mengatur rotasi Euler geometris(diukur dalam derajat). |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | Mengatur rotasi Euler geometris(diukur dalam derajat). |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | Mengatur skala geometris. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | Mengatur skala geometris. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | Mengatur translasi geometris. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | Mengatur translasi geometris. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | Mengatur post-rotasi yang direpresentasikan dalam derajat |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | Mengatur post-rotasi yang direpresentasikan dalam derajat **Example:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | Mengatur pre-rotasi yang direpresentasikan dalam derajat |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | Mengatur pre-rotasi yang direpresentasikan dalam derajat **Example:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | Mengatur rotasi yang direpresentasikan dalam quaternion. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | Mengatur rotasi(as komponen quaternion) untuk transformasi saat ini. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | Mengatur offset rotasi |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | Mengatur poros rotasi |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | Mengatur skala transformasi saat ini. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | Mengatur skala |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | Mengatur offset skala |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | Mengatur poros skala |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | Mengatur matriks transformasi. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | Mengatur translasi |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | Mengatur translasi transformasi saat ini. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Menemukan properti. Itu dapat menjadi properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | java.lang.String | Nama properti. |

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


Mendapatkan rotasi yang direpresentasikan dalam sudut Euler, diukur dalam derajat

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


Mendapatkan rotasi Euler geometris (diukur dalam derajat). Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke jenis file yang tidak mendukungnya.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


Mendapatkan skala geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya.

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


Mendapatkan translasi geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya.

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


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


Mendapatkan post-rotasi yang direpresentasikan dalam derajat

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


Mendapatkan pre-rotasi yang direpresentasikan dalam derajat

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


Mendapatkan koleksi semua properti.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Dapatkan nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |

**Returns:**
java.lang.Object - Nilai dari properti yang ditemukan
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


Mendapatkan rotasi yang direpresentasikan dalam quaternion.

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


Mendapatkan offset rotasi

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


Mendapatkan poros rotasi

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


Mendapatkan skala

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


Mendapatkan offset skala

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


Mendapatkan poros skala

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


Mendapatkan matriks transformasi.

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


Mendapatkan translasi

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


Menghapus properti dinamis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Hapus properti yang ditentukan yang diidentifikasi dengan nama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


Mengatur rotasi yang direpresentasikan dalam sudut Euler, diukur dalam derajat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


Mengatur sudut Euler dalam derajat dari transformasi saat ini. **Contoh:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur rotasi Euler geometris (diukur dalam derajat). Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


Mengatur rotasi Euler geometris (diukur dalam derajat). Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya. **Contoh:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur skala geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


Mengatur skala geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya. **Contoh:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur translasi geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


Mengatur translasi geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke tipe file yang tidak mendukungnya. **Contoh:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


Mengatur post-rotasi yang direpresentasikan dalam derajat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


Mengatur post-rotasi yang direpresentasikan dalam derajat **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur pre-rotasi yang direpresentasikan dalam derajat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


Mengatur pre-rotasi yang direpresentasikan dalam derajat **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |
| nilai | java.lang.Object | Nilai properti |

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


Mengatur rotasi yang direpresentasikan dalam quaternion.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


Mengatur rotasi (sebagai komponen kuaternion) dari transformasi saat ini. **Contoh:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur offset rotasi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


Mengatur poros rotasi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


Mengatur skala dari transformasi saat ini. **Contoh:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mengatur skala

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


Mengatur offset skala

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


Mengatur poros skala

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


Mengatur matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | Nilai baru **Catatan:** Menetapkan pada ini akan mengatur ulang [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) dan [getRotation](../../com.aspose.threed/transform\#getRotation), serta [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) dan [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) tidak akan terpengaruh. **Contoh:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


Mengatur translasi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru **Example:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


Mengatur translasi dari transformasi saat ini. **Contoh:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

