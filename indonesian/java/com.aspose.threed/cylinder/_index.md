---
title: Cylinder
second_title: Referensi API Aspose.3D untuk Java
description: Silinder berparameter.
type: docs
weight: 40
url: /id/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Parameterized Cylinder. Itu juga dapat digunakan untuk merepresentasikan kerucut ketika salah satu radiusTop/radiusBottom bernilai nol.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Cylinder()](#Cylinder--) | Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCastShadows()](#getCastShadows--) | Mendapatkan apakah geometri ini dapat memancarkan bayangan |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Mendapatkan apakah akan menghasilkan silinder gaya kipas ketika ThetaLength kurang dari 2\*PI, jika tidak model tidak akan dipotong. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi silinder. |
| [getHeightSegments()](#getHeightSegments--) | Mendapatkan segmen tinggi. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getOffsetBottom()](#getOffsetBottom--) | Mendapatkan offset transformasi vertex sisi bawah. |
| [getOffsetTop()](#getOffsetTop--) | Mendapatkan offset transformasi vertex sisi atas. |
| [getOpenEnded()](#getOpenEnded--) | Mendapatkan nilai yang menunjukkan apakah [Cylinder](../../com.aspose.threed/cylinder) ini terbuka di ujung. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRadialSegments()](#getRadialSegments--) | Mendapatkan segmen radial. |
| [getRadiusBottom()](#getRadiusBottom--) | Mendapatkan radius tutup bawah silinder. |
| [getRadiusTop()](#getRadiusTop--) | Mendapatkan radius tutup atas silinder. |
| [getReceiveShadows()](#getReceiveShadows--) | Mendapatkan apakah geometri ini dapat menerima bayangan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getShearBottom()](#getShearBottom--) | Mendapatkan transformasi geser sisi bawah, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |
| [getShearTop()](#getShearTop--) | Mendapatkan transformasi geser sisi atas, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |
| [getThetaLength()](#getThetaLength--) | Mendapatkan panjang theta. |
| [getThetaStart()](#getThetaStart--) | Mendapatkan nilai awal theta. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah geometri ini dapat memancarkan bayangan |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | Mengatur apakah akan menghasilkan silinder gaya kipas ketika ThetaLength kurang dari 2\*PI, jika tidak model tidak akan dipotong. |
| [setHeight(double value)](#setHeight-double-) | Mengatur tinggi silinder. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Mengatur segmen tinggi. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Mengatur offset transformasi vertex sisi bawah. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Mengatur offset transformasi vertex sisi atas. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Mengatur nilai yang menunjukkan apakah [Cylinder](../../com.aspose.threed/cylinder) ini terbuka di ujung. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Mengatur segmen radial. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Mengatur radius tutup bawah silinder. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Mengatur radius tutup atas silinder. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Mengatur apakah geometri ini dapat menerima bayangan. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Mengatur transformasi geser sisi bawah, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Mengatur transformasi geser sisi atas, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |
| [setThetaLength(double value)](#setThetaLength-double-) | Mengatur panjang theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Mengatur awal theta. |
| [toMesh()](#toMesh--) | Konversi objek saat ini ke mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder).

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radius | double | Radius tutup atas dan bawah. |
| tinggi | double | Tinggi. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radiusTop | double | Radius atas. |
| radiusBottom | double | Radius bawah. |
| tinggi | double | Tinggi. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radiusTop | double | Radius tutup atas silinder. |
| radiusBottom | double | Radius tutup bawah silinder. |
| tinggi | double | Tinggi silinder. |
| radialSegments | int | Segmen radial dari kedua lingkaran atas dan bawah.. |
| heightSegments | int | Segmen tinggi. |
| openEnded | boolean | Jika disetel ke  true  silinder tidak akan memiliki tutup bawah/atas.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Menginisialisasi instance baru dari kelas [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek ini |
| radiusTop | double | Radius tutup atas silinder. |
| radiusBottom | double | Radius tutup bawah silinder. |
| tinggi | double | Tinggi silinder. |
| radialSegments | int | Segmen radial dari kedua lingkaran atas dan bawah.. |
| heightSegments | int | Segmen tinggi. |
| openEnded | boolean | Jika disetel ke  true  silinder tidak akan memiliki tutup bawah/atas.. |
| thetaStart | double | Awal Theta. |
| thetaLength | double | Panjang Theta. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Mendapatkan apakah geometri ini dapat memancarkan bayangan

**Returns:**
boolean - apakah geometri ini dapat menghasilkan bayangan
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Mendapatkan apakah akan menghasilkan silinder gaya kipas ketika ThetaLength kurang dari 2\*PI, jika tidak model tidak akan dipotong.

**Returns:**
boolean - apakah akan menghasilkan silinder gaya kipas ketika ThetaLength kurang dari 2\*PI, jika tidak model tidak akan dipotong.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi silinder.

**Returns:**
double - tinggi silinder.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Mendapatkan segmen tinggi.

**Returns:**
int - segmen tinggi.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Mendapatkan offset transformasi vertex sisi bawah.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Mendapatkan offset transformasi vertex sisi atas.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Mendapatkan nilai yang menunjukkan apakah [Cylinder](../../com.aspose.threed/cylinder) ini terbuka di ujung. Nilai default adalah false.

**Returns:**
boolean - nilai yang menunjukkan apakah [Cylinder](../../com.aspose.threed/cylinder) ini terbuka di ujung. Nilai default adalah false.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Mendapatkan segmen radial.

**Returns:**
int - segmen radial.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Mendapatkan radius tutup bawah silinder.

**Returns:**
double - jari-jari tutup bawah silinder.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Mendapatkan radius tutup atas silinder.

**Returns:**
double - jari-jari tutup atas silinder.
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Mendapatkan apakah geometri ini dapat menerima bayangan.

**Returns:**
boolean - apakah geometri ini dapat menerima bayangan.
### getScene() {#getScene--}
```
public Scene getScene()
```


Mendapatkan adegan yang dimiliki objek ini

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Mendapatkan transformasi geser sisi bawah, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Mendapatkan transformasi geser sisi atas, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Mendapatkan panjang theta. Nilai default adalah 2\\u03c0.

**Returns:**
double - panjang theta. Nilai default adalah 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Mendapatkan nilai awal theta. Nilai default adalah 0.

**Returns:**
double - nilai awal theta. Nilai default adalah 0.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Mengatur apakah geometri ini dapat memancarkan bayangan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Mengatur apakah entitas ini akan dikecualikan saat mengekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


Mengatur apakah akan menghasilkan silinder gaya kipas ketika ThetaLength kurang dari 2\*PI, jika tidak model tidak akan dipotong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Mengatur tinggi silinder.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Mengatur segmen tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Mengatur offset transformasi vertex sisi bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Mengatur offset transformasi vertex sisi atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Mengatur nilai yang menunjukkan apakah [Cylinder](../../com.aspose.threed/cylinder) ini terbuka di ujung. Nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Mengatur segmen radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Mengatur radius tutup bawah silinder.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Mengatur radius tutup atas silinder.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Mengatur apakah geometri ini dapat menerima bayangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Mengatur transformasi geser sisi bawah, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Mengatur transformasi geser sisi atas, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Mengatur panjang theta. Nilai default adalah 2\\u03c0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Mengatur nilai awal theta. Nilai default adalah 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Konversi objek saat ini ke mesh

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

