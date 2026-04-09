---
title: Frustum
second_title: Referensi API Aspose.3D untuk Java
description: Kelas dasar dari  dan
type: docs
weight: 69
url: /id/java/com.aspose.threed/frustum/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public abstract class Frustum extends Entity implements IOrientable
```

Kelas dasar dari [Camera](../../com.aspose.threed/camera) dan [Light](../../com.aspose.threed/light)
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAspect()](#getAspect--) | Mendapatkan rasio aspek dari frustum |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Mendapatkan arah yang dilihat kamera. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getFarPlane()](#getFarPlane--) | Mendapatkan jarak bidang jauh frustum. |
| [getLookAt()](#getLookAt--) | Mendapatkan posisi yang diminati yang dilihat kamera. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getNearPlane()](#getNearPlane--) | Mendapatkan jarak bidang dekat frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Mendapatkan tinggi ketika frustum dalam proyeksi ortografis. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRotationMode()](#getRotationMode--) | Mendapatkan mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getTarget()](#getTarget--) | Mendapatkan target yang dilihat kamera. |
| [getUp()](#getUp--) | Mendapatkan arah atas kamera |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAspect(double value)](#setAspect-double-) | Mengatur rasio aspek frustum |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Mengatur arah yang dilihat kamera. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setFarPlane(double value)](#setFarPlane-double-) | Mengatur jarak bidang jauh frustum. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Mengatur posisi yang diminati yang dilihat kamera. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setNearPlane(double value)](#setNearPlane-double-) | Mengatur jarak bidang dekat frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Mengatur tinggi ketika frustum dalam proyeksi ortografik. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Mengatur mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Mengatur target yang dilihat kamera. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Mengatur arah atas kamera |
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
### getAspect() {#getAspect--}
```
public double getAspect()
```


Mendapatkan rasio aspek dari frustum

**Returns:**
double - rasio aspek frustum
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Mendapatkan arah yang dilihat kamera. Perubahan pada properti ini juga akan memengaruhi [getLookAt](../../com.aspose.threed/frustum\#getLookAt) dan [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Mendapatkan kunci renderer entitas yang terdaftar di renderer

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor.

**Returns:**
boolean - apakah entitas ini akan dikecualikan saat mengekspor.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Mendapatkan jarak bidang jauh frustum.

**Returns:**
double - jarak bidang jauh frustum.
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Mendapatkan posisi yang diminati yang dilihat kamera.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Mendapatkan jarak bidang dekat frustum.

**Returns:**
double - jarak bidang dekat frustum.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Mendapatkan tinggi ketika frustum dalam proyeksi ortografis.

**Returns:**
double - tinggi ketika frustum dalam proyeksi ortografik.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - semua node induk, sebuah entitas dapat terhubung ke beberapa node induk untuk instansi geometri
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
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Mendapatkan mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. Jika nilai adalah [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), arah selalu dihitung oleh properti [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Jika tidak, [getLookAt](../../com.aspose.threed/frustum\#getLookAt) selalu dihitung oleh [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Mendapatkan adegan yang dimiliki objek ini

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Mendapatkan target yang dilihat kamera. Jika pengguna mendukung properti ini, seharusnya diprioritaskan sebelum properti [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Mendapatkan arah atas kamera

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Mengatur rasio aspek frustum

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Mengatur arah yang dilihat kamera. Perubahan pada properti ini juga akan memengaruhi [getLookAt](../../com.aspose.threed/frustum\#getLookAt) dan [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Mengatur apakah entitas ini akan dikecualikan saat mengekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Mengatur jarak bidang jauh frustum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Mengatur posisi yang diminati yang dilihat kamera.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Mengatur jarak bidang dekat frustum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Mengatur tinggi ketika frustum dalam proyeksi ortografik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nilai baru |

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Mengatur mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. Jika nilai adalah [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), arah selalu dihitung oleh properti [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Jika tidak, [getLookAt](../../com.aspose.threed/frustum\#getLookAt) selalu dihitung oleh [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nilai baru |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Mengatur target yang dilihat kamera. Jika pengguna mendukung properti ini, harus ditempatkan sebelum properti [getLookAt](../../com.aspose.threed/frustum\\#getLookAt).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nilai baru |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Mengatur arah atas kamera

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

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

