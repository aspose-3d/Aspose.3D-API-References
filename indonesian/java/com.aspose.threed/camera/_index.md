---
title: Camera
second_title: Referensi API Aspose.3D untuk Java
description: Kamera menggambarkan titik mata penonton yang melihat adegan.
type: docs
weight: 28
url: /id/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

Kamera menggambarkan titik mata penonton yang melihat adegan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Camera()](#Camera--) | Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera). |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera). |
| [Camera(String name)](#Camera-java.lang.String-) | Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera). |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getApertureMode()](#getApertureMode--) | Mendapatkan mode aperture kamera |
| [getAspect()](#getAspect--) | Mendapatkan rasio aspek dari frustum |
| [getAspectRatio()](#getAspectRatio--) | Mendapatkan rasio aspek bidang tampilan. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Mendapatkan arah yang dilihat kamera. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getFarPlane()](#getFarPlane--) | Mendapatkan jarak bidang jauh frustum. |
| [getFieldOfView()](#getFieldOfView--) | Mendapatkan bidang pandang kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) atau [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | Mendapatkan bidang pandang horizontal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | Mendapatkan bidang pandang vertikal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | Mendapatkan tinggi bidang tampilan yang diukur dalam inci |
| [getLookAt()](#getLookAt--) | Mendapatkan posisi yang diminati yang dilihat kamera. |
| [getMagnification()](#getMagnification--) | Mendapatkan pembesaran yang digunakan pada kamera ortografik |
| [getName()](#getName--) | Mendapatkan nama. |
| [getNearPlane()](#getNearPlane--) | Mendapatkan jarak bidang dekat frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Mendapatkan tinggi ketika frustum dalam proyeksi ortografis. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProjectionType()](#getProjectionType--) | Mendapatkan tipe proyeksi kamera. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRotationMode()](#getRotationMode--) | Mendapatkan mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getTarget()](#getTarget--) | Mendapatkan target yang dilihat kamera. |
| [getUp()](#getUp--) | Mendapatkan arah atas kamera |
| [getWidth()](#getWidth--) | Mendapatkan lebar bidang tampilan yang diukur dalam inci |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Pindahkan kamera maju menuju arah atau targetnya. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Mengatur mode aperture kamera |
| [setAspect(double value)](#setAspect-double-) | Mengatur rasio aspek frustum |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Mengatur rasio aspek bidang tampilan. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Mengatur arah yang dilihat kamera. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setFarPlane(double value)](#setFarPlane-double-) | Mengatur jarak bidang jauh frustum. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Mengatur bidang pandang kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) atau [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Mengatur bidang pandang horizontal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Mengatur bidang pandang vertikal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | Mengatur tinggi bidang tampilan yang diukur dalam inci |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Mengatur posisi yang diminati yang dilihat kamera. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Mengatur pembesaran yang digunakan pada kamera ortografik |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setNearPlane(double value)](#setNearPlane-double-) | Mengatur jarak bidang dekat frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Mengatur tinggi ketika frustum dalam proyeksi ortografik. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Mengatur tipe proyeksi kamera. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Mengatur mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Mengatur target yang dilihat kamera. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Mengatur arah atas kamera |
| [setWidth(double value)](#setWidth-double-) | Mengatur lebar bidang tampilan yang diukur dalam inci |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera).

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Tipe proyeksi. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Menginisialisasi instance baru dari kelas [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Tipe proyeksi. |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Mendapatkan mode aperture kamera

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Mendapatkan rasio aspek dari frustum

**Returns:**
double - rasio aspek frustum
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Mendapatkan rasio aspek bidang tampilan.

**Returns:**
double - rasio aspek bidang tampilan.
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
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Mendapatkan bidang pandang kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) atau [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
double - bidang pandang kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) atau [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Mendapatkan bidang pandang horizontal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - bidang pandang horizontal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Mendapatkan bidang pandang vertikal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - bidang pandang vertikal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi bidang tampilan yang diukur dalam inci

**Returns:**
double - tinggi bidang tampilan yang diukur dalam inci
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Mendapatkan posisi yang diminati yang dilihat kamera.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Mendapatkan pembesaran yang digunakan pada kamera ortografik

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Mendapatkan tipe proyeksi kamera. Secara default proyeksi perspektif digunakan.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar bidang tampilan yang diukur dalam inci

**Returns:**
double - lebar bidang tampilan yang diukur dalam inci
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


Pindahkan kamera maju menuju arah atau targetnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jarak | double | Berapa lama untuk bergerak maju |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Mengatur mode aperture kamera

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Nilai baru |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Mengatur rasio aspek frustum

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Mengatur rasio aspek bidang tampilan.

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

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Mengatur bidang pandang kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) atau [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Mengatur bidang pandang horizontal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Mengatur bidang pandang vertikal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Mengatur tinggi bidang tampilan yang diukur dalam inci

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

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Mengatur pembesaran yang digunakan pada kamera ortografik

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

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

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Mengatur tipe proyeksi kamera. Secara default proyeksi perspektif digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Nilai baru |

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

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Mengatur lebar bidang tampilan yang diukur dalam inci

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

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

