---
title: Piramida
second_title: Referensi API Aspose.3D untuk Java
description: Piramida berparameter.
type: docs
weight: 142
url: /id/java/com.aspose.threed/pyramid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Pyramid extends Primitive
```

Piramida berparameter.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Pyramid()](#Pyramid--) | Buat instance piramida baru dengan area dasar default (10, 10) dan tinggi default (5) |
| [Pyramid(double xbottom, double ybottom, double height)](#Pyramid-double-double-double-) | Buat instance piramida baru dengan area dasar yang ditentukan |
| [Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-double-double-double-double-double-) | Buat instance piramida baru dengan area dasar, area atas, dan tinggi yang ditentukan. |
| [Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-java.lang.String-double-double-double-double-double-) | Buat instance piramida baru dengan area dasar, area atas, dan tinggi yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBottomArea()](#getBottomArea--) | Luas tutup dasar |
| [getBottomOffset()](#getBottomOffset--) | Offset untuk titik sudut dasar |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCastShadows()](#getCastShadows--) | Mendapatkan apakah geometri ini dapat memancarkan bayangan |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getHeight()](#getHeight--) | Tinggi piramida |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getReceiveShadows()](#getReceiveShadows--) | Mendapatkan apakah geometri ini dapat menerima bayangan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getTopArea()](#getTopArea--) | Luas tutup atas |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setBottomArea(Vector2 value)](#setBottomArea-com.aspose.threed.Vector2-) | Luas tutup dasar |
| [setBottomOffset(Vector3 value)](#setBottomOffset-com.aspose.threed.Vector3-) | Offset untuk titik sudut dasar |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah geometri ini dapat memancarkan bayangan |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setHeight(double value)](#setHeight-double-) | Tinggi piramida |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Mengatur apakah geometri ini dapat menerima bayangan. |
| [setTopArea(Vector2 value)](#setTopArea-com.aspose.threed.Vector2-) | Luas tutup atas |
| [toMesh()](#toMesh--) | Konversi objek saat ini ke mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pyramid() {#Pyramid--}
```
public Pyramid()
```


Buat instance piramida baru dengan area dasar default (10, 10) dan tinggi default (5)

### Pyramid(double xbottom, double ybottom, double height) {#Pyramid-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double height)
```


Buat instance piramida baru dengan area dasar yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xbottom | double | Panjang arah x dari dasar |
| ybottom | double | Panjang arah y dari dasar |
| tinggi | double | Tinggi piramida |

### Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-double-double-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)
```


Buat instance piramida baru dengan area dasar, area atas, dan tinggi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xbottom | double | Panjang arah x dari area dasar |
| ybottom | double | Panjang arah y dari area dasar |
| xtop | double | Panjang arah x dari area atas |
| ytop | double | Panjang arah y dari area atas |
| tinggi | double | Tinggi piramida |

### Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-java.lang.String-double-double-double-double-double-}
```
public Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)
```


Buat instance piramida baru dengan area dasar, area atas, dan tinggi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama piramida |
| xbottom | double | Panjang arah x dari area dasar |
| ybottom | double | Panjang arah y dari area dasar |
| xtop | double | Panjang arah x dari area atas |
| ytop | double | Panjang arah y dari area atas |
| tinggi | double | Tinggi piramida |

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
### getBottomArea() {#getBottomArea--}
```
public Vector2 getBottomArea()
```


Luas tutup dasar

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the bottom cap
### getBottomOffset() {#getBottomOffset--}
```
public Vector3 getBottomOffset()
```


Offset untuk titik sudut dasar

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Offset for bottom vertices
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


Tinggi piramida

**Returns:**
double - Tinggi piramida
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
### getTopArea() {#getTopArea--}
```
public Vector2 getTopArea()
```


Luas tutup atas

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the top cap
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
### setBottomArea(Vector2 value) {#setBottomArea-com.aspose.threed.Vector2-}
```
public void setBottomArea(Vector2 value)
```


Luas tutup dasar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setBottomOffset(Vector3 value) {#setBottomOffset-com.aspose.threed.Vector3-}
```
public void setBottomOffset(Vector3 value)
```


Offset untuk titik sudut dasar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

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


Tinggi piramida

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

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

### setTopArea(Vector2 value) {#setTopArea-com.aspose.threed.Vector2-}
```
public void setTopArea(Vector2 value)
```


Luas tutup atas

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

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

