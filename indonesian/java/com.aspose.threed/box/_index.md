---
title: Box
second_title: Referensi API Aspose.3D untuk Java
description: Kotak.
type: docs
weight: 26
url: /id/java/com.aspose.threed/box/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Box extends Primitive
```

Kotak.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Box()](#Box--) | Menginisialisasi instance baru dari kelas [Box](../../com.aspose.threed/box). |
| [Box(double length, double width, double height)](#Box-double-double-double-) | Menginisialisasi instance baru dari kelas [Box](../../com.aspose.threed/box). |
| [Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments)](#Box-java.lang.String-double-double-double-int-int-int-) | Menginisialisasi instance baru dari kelas [Box](../../com.aspose.threed/box). |
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
| [getHeight()](#getHeight--) | Mendapatkan tinggi kotak yang sejajar pada sumbu y. |
| [getHeightSegments()](#getHeightSegments--) | mendapatkan atau mengatur segmen tinggi. |
| [getLength()](#getLength--) | Mendapatkan panjang kotak yang sejajar pada sumbu z. |
| [getLengthSegments()](#getLengthSegments--) | Mendapatkan segmen panjang. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getReceiveShadows()](#getReceiveShadows--) | Mendapatkan apakah geometri ini dapat menerima bayangan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getWidth()](#getWidth--) | Mendapatkan lebar kotak yang sejajar pada sumbu x. |
| [getWidthSegments()](#getWidthSegments--) | Mendapatkan segmen lebar |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah geometri ini dapat memancarkan bayangan |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setHeight(double value)](#setHeight-double-) | Mengatur tinggi kotak yang sejajar pada sumbu y. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | mendapatkan atau mengatur segmen tinggi. |
| [setLength(double value)](#setLength-double-) | Mengatur panjang kotak yang sejajar pada sumbu z. |
| [setLengthSegments(int value)](#setLengthSegments-int-) | Mengatur segmen panjang. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Mengatur apakah geometri ini dapat menerima bayangan. |
| [setWidth(double value)](#setWidth-double-) | Mengatur lebar kotak yang sejajar pada sumbu x. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Mengatur segmen lebar |
| [toMesh()](#toMesh--) | Konversi objek saat ini ke mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Box() {#Box--}
```
public Box()
```


Menginisialisasi instance baru dari kelas [Box](../../com.aspose.threed/box).

### Box(double length, double width, double height) {#Box-double-double-double-}
```
public Box(double length, double width, double height)
```


Menginisialisasi instance baru dari kelas [Box](../../com.aspose.threed/box).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| panjang | double | Panjang kotak yang sejajar pada sumbu z. |
| lebar | double | Lebar kotak yang sejajar pada sumbu x. |
| tinggi | double | Tinggi kotak yang sejajar pada sumbu y. |

### Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments) {#Box-java.lang.String-double-double-double-int-int-int-}
```
public Box(String name, double length, double width, double height, int lengthSegments, int widthSegments, int heightSegments)
```


Menginisialisasi instance baru dari kelas [Box](../../com.aspose.threed/box).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama kotak. |
| panjang | double | Panjang kotak yang sejajar pada sumbu z. |
| lebar | double | Lebar kotak yang sejajar pada sumbu x. |
| tinggi | double | Tinggi kotak yang sejajar pada sumbu y. |
| lengthSegments | int | Segmen panjang. |
| widthSegments | int | Segmen lebar. |
| heightSegments | int | Segmen tinggi. |

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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi kotak yang sejajar pada sumbu y.

**Returns:**
double - tinggi kotak yang sejajar pada sumbu y.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


mendapatkan atau mengatur segmen tinggi.

**Returns:**
int - mendapatkan atau mengatur segmen tinggi.
### getLength() {#getLength--}
```
public double getLength()
```


Mendapatkan panjang kotak yang sejajar pada sumbu z.

**Returns:**
double - panjang kotak yang sejajar pada sumbu z.
### getLengthSegments() {#getLengthSegments--}
```
public int getLengthSegments()
```


Mendapatkan segmen panjang.

**Returns:**
int - segmen panjang.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar kotak yang sejajar pada sumbu x.

**Returns:**
double - lebar kotak yang sejajar pada sumbu x.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Mendapatkan segmen lebar

**Returns:**
int - segmen lebar
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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Mengatur tinggi kotak yang sejajar pada sumbu y.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


mendapatkan atau mengatur segmen tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setLength(double value) {#setLength-double-}
```
public void setLength(double value)
```


Mengatur panjang kotak yang sejajar pada sumbu z.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setLengthSegments(int value) {#setLengthSegments-int-}
```
public void setLengthSegments(int value)
```


Mengatur segmen panjang.

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Mengatur apakah geometri ini dapat menerima bayangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Mengatur lebar kotak yang sejajar pada sumbu x.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Mengatur segmen lebar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

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

