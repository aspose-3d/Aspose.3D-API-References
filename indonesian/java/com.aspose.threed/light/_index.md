---
title: Light
second_title: Referensi API Aspose.3D untuk Java
description: Cahaya menerangi adegan.
type: docs
weight: 94
url: /id/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

Cahaya menerangi adegan.

Rumus untuk menghitung atenuasi total cahaya adalah:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Light()](#Light--) | Menginisialisasi sebuah instance baru dari kelas [Light](../../com.aspose.threed/light). |
| [Light(String name)](#Light-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [Light](../../com.aspose.threed/light). |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Menginisialisasi sebuah instance baru dari kelas [Light](../../com.aspose.threed/light). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAspect()](#getAspect--) | Mendapatkan rasio aspek dari frustum |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCastLight()](#getCastLight--) | Mendapatkan apakah instance cahaya saat ini dapat menerangi objek lain. |
| [getCastShadows()](#getCastShadows--) | Mendapatkan apakah cahaya dapat menghasilkan bayangan pada objek lain. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Mendapatkan warna cahaya |
| [getConstantAttenuation()](#getConstantAttenuation--) | Mendapatkan atenuasi konstan untuk menghitung atenuasi total cahaya |
| [getDirection()](#getDirection--) | Mendapatkan arah yang dilihat kamera. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getFalloff()](#getFalloff--) | Mendapatkan sudut kerucut penurunan (dalam derajat). |
| [getFarPlane()](#getFarPlane--) | Mendapatkan jarak bidang jauh frustum. |
| [getHotSpot()](#getHotSpot--) | Mendapatkan sudut kerucut titik panas(in derajat). |
| [getIntensity()](#getIntensity--) | Mendapatkan intensitas cahaya, nilai default adalah 100 |
| [getLightType()](#getLightType--) | Mendapatkan tipe cahaya |
| [getLinearAttenuation()](#getLinearAttenuation--) | Mendapatkan atenuasi linear untuk menghitung total atenuasi cahaya |
| [getLookAt()](#getLookAt--) | Mendapatkan posisi yang diminati yang dilihat kamera. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getNearPlane()](#getNearPlane--) | Mendapatkan jarak bidang dekat frustum. |
| [getOrthoHeight()](#getOrthoHeight--) | Mendapatkan tinggi ketika frustum dalam proyeksi ortografis. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Mendapatkan atenuasi kuadratik untuk menghitung total atenuasi cahaya |
| [getRotationMode()](#getRotationMode--) | Mendapatkan mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getShadowColor()](#getShadowColor--) | Mendapatkan warna bayangan. |
| [getTarget()](#getTarget--) | Mendapatkan target yang dilihat kamera. |
| [getUp()](#getUp--) | Mendapatkan arah atas kamera |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAspect(double value)](#setAspect-double-) | Mengatur rasio aspek frustum |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Mengatur apakah instance cahaya saat ini dapat menerangi objek lain. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah cahaya dapat menghasilkan bayangan pada objek lain. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Mengatur warna cahaya |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Mengatur atenuasi konstan untuk menghitung total atenuasi cahaya |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Mengatur arah yang dilihat kamera. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setFalloff(double value)](#setFalloff-double-) | Mengatur sudut kerucut penurunan (dalam derajat). |
| [setFarPlane(double value)](#setFarPlane-double-) | Mengatur jarak bidang jauh frustum. |
| [setHotSpot(double value)](#setHotSpot-double-) | Mengatur sudut kerucut titik panas(in derajat). |
| [setIntensity(double value)](#setIntensity-double-) | Mengatur intensitas cahaya, nilai default adalah 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Mengatur tipe cahaya |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Mengatur atenuasi linear untuk menghitung total atenuasi cahaya |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Mengatur posisi yang diminati yang dilihat kamera. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setNearPlane(double value)](#setNearPlane-double-) | Mengatur jarak bidang dekat frustum. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Mengatur tinggi ketika frustum dalam proyeksi ortografik. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Mengatur atenuasi kuadratik untuk menghitung total atenuasi cahaya |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Mengatur mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Mengatur warna bayangan. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Mengatur target yang dilihat kamera. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Mengatur arah atas kamera |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Menginisialisasi sebuah instance baru dari kelas [Light](../../com.aspose.threed/light).

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Menginisialisasi sebuah instance baru dari kelas [Light](../../com.aspose.threed/light).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Menginisialisasi sebuah instance baru dari kelas [Light](../../com.aspose.threed/light).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama |
| type | [LightType](../../com.aspose.threed/lighttype) | Tipe cahaya baru |

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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Mendapatkan apakah instance cahaya saat ini dapat menerangi objek lain.

**Returns:**
boolean - apakah instance cahaya saat ini dapat menerangi objek lain.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Mendapatkan apakah cahaya dapat menghasilkan bayangan pada objek lain.

**Returns:**
boolean - apakah cahaya dapat menghasilkan bayangan pada objek lain.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Mendapatkan warna cahaya

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Mendapatkan atenuasi konstan untuk menghitung atenuasi total cahaya

**Returns:**
double - atenuasi konstan untuk menghitung total atenuasi cahaya
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Mendapatkan sudut kerucut penurunan (dalam derajat).

**Returns:**
double - sudut kerucut penurunan (dalam derajat).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Mendapatkan jarak bidang jauh frustum.

**Returns:**
double - jarak bidang jauh frustum.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Mendapatkan sudut kerucut titik panas(in derajat).

**Returns:**
double - sudut kerucut titik panas (dalam derajat).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Mendapatkan intensitas cahaya, nilai default adalah 100

**Returns:**
double - intensitas cahaya, nilai default adalah 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Mendapatkan tipe cahaya

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Mendapatkan atenuasi linear untuk menghitung total atenuasi cahaya

**Returns:**
double - atenuasi linear untuk menghitung total atenuasi cahaya
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Mendapatkan atenuasi kuadratik untuk menghitung total atenuasi cahaya

**Returns:**
double - atenuasi kuadratik untuk menghitung total atenuasi cahaya
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
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Mendapatkan warna bayangan.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
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

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Mengatur apakah instance cahaya saat ini dapat menerangi objek lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Mengatur apakah cahaya dapat menghasilkan bayangan pada objek lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Mengatur warna cahaya

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Mengatur atenuasi konstan untuk menghitung total atenuasi cahaya

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Mengatur sudut kerucut penurunan (dalam derajat).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Mengatur jarak bidang jauh frustum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Mengatur sudut kerucut titik panas(in derajat).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Mengatur intensitas cahaya, nilai default adalah 100

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Mengatur tipe cahaya

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Nilai baru |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Mengatur atenuasi linear untuk menghitung total atenuasi cahaya

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Mengatur atenuasi kuadratik untuk menghitung total atenuasi cahaya

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Mengatur mode orientasi frustum Properti ini hanya berfungsi ketika [getTarget](../../com.aspose.threed/frustum\#getTarget) bernilai null. Jika nilai adalah [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), arah selalu dihitung oleh properti [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Jika tidak, [getLookAt](../../com.aspose.threed/frustum\#getLookAt) selalu dihitung oleh [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Nilai baru |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Mengatur warna bayangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

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

