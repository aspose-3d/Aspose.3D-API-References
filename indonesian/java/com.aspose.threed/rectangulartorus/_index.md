---
title: RectangularTorus
second_title: Referensi API Aspose.3D untuk Java
description: Torus persegi panjang berparameter.
type: docs
weight: 146
url: /id/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

Torus persegi panjang berparameter.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | Konstruktor dari [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | Konstruktor dari [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAngleStart()](#getAngleStart--) | Sudut awal busur, diukur dalam radian. |
| [getArc()](#getArc--) | Sudut total busur, diukur dalam radian. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCastShadows()](#getCastShadows--) | Mendapatkan apakah geometri ini dapat memancarkan bayangan |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getHeight()](#getHeight--) | Tinggi torus persegi panjang. |
| [getInnerRadius()](#getInnerRadius--) | Radius dalam torus persegi panjang, nilai default adalah 17 |
| [getName()](#getName--) | Mendapatkan nama. |
| [getOuterRadius()](#getOuterRadius--) | Radius luar torus persegi panjang, nilai default adalah 20 |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRadialSegments()](#getRadialSegments--) | Segmen radial, nilai default adalah 10 |
| [getReceiveShadows()](#getReceiveShadows--) | Mendapatkan apakah geometri ini dapat menerima bayangan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setAngleStart(double value)](#setAngleStart-double-) | Sudut awal busur, diukur dalam radian. |
| [setArc(double value)](#setArc-double-) | Sudut total busur, diukur dalam radian. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah geometri ini dapat memancarkan bayangan |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setHeight(double value)](#setHeight-double-) | Tinggi torus persegi panjang. |
| [setInnerRadius(double value)](#setInnerRadius-double-) | Radius dalam torus persegi panjang, nilai default adalah 17 |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setOuterRadius(double value)](#setOuterRadius-double-) | Radius luar torus persegi panjang, nilai default adalah 20 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Segmen radial, nilai default adalah 10 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Mengatur apakah geometri ini dapat menerima bayangan. |
| [toMesh()](#toMesh--) | Konversi primitif ini ke [Mesh](../../com.aspose.threed/mesh) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


Konstruktor dari [RectangularTorus](../../com.aspose.threed/rectangulartorus)

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


Konstruktor dari [RectangularTorus](../../com.aspose.threed/rectangulartorus)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


Sudut awal busur, diukur dalam radian. Nilai default adalah 0

**Returns:**
double - Sudut awal busur, diukur dalam radian. Nilai default adalah 0
### getArc() {#getArc--}
```
public double getArc()
```


Total sudut busur, diukur dalam radian. Nilai default adalah PI

**Returns:**
double - Total sudut busur, diukur dalam radian. Nilai default adalah PI
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


Tinggi torus persegi panjang. Nilai default adalah 20

**Returns:**
double - Tinggi torus persegi panjang. Nilai default adalah 20
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


Radius dalam torus persegi panjang, nilai default adalah 17

**Returns:**
double - Jari-jari dalam torus persegi panjang. Nilai default adalah 17
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


Radius luar torus persegi panjang, nilai default adalah 20

**Returns:**
double - Jari-jari luar torus persegi panjang. Nilai default adalah 20
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


Segmen radial, nilai default adalah 10

**Returns:**
int - Segmen radial, nilai default adalah 10
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
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


Sudut awal busur, diukur dalam radian. Nilai default adalah 0

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


Total sudut busur, diukur dalam radian. Nilai default adalah PI

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

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


Tinggi torus persegi panjang. Nilai default adalah 20

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


Radius dalam torus persegi panjang, nilai default adalah 17

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

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


Radius luar torus persegi panjang, nilai default adalah 20

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Segmen radial, nilai default adalah 10

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Mengatur apakah geometri ini dapat menerima bayangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Konversi primitif ini ke [Mesh](../../com.aspose.threed/mesh)

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

