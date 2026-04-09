---
title: Torus
second_title: Referensi API Aspose.3D untuk Java
description: Torus berparameter.
type: docs
weight: 189
url: /id/java/com.aspose.threed/torus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Torus extends Primitive
```

Torus berparameter.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Torus()](#Torus--) | Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus). |
| [Torus(double radius, double tube)](#Torus-double-double-) | Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus). |
| [Torus(double radius, double tube, double arc)](#Torus-double-double-double-) | Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus). |
| [Torus(String name, double radius, double tube, int radialSegments, int tubularSegments, double arc)](#Torus-java.lang.String-double-double-int-int-double-) | Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getArc()](#getArc--) | Mendapatkan busur. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCastShadows()](#getCastShadows--) | Mendapatkan apakah geometri ini dapat memancarkan bayangan |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRadialSegments()](#getRadialSegments--) | Mendapatkan segmen radial. |
| [getRadius()](#getRadius--) | Mendapatkan radius torus. |
| [getReceiveShadows()](#getReceiveShadows--) | Mendapatkan apakah geometri ini dapat menerima bayangan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getTube()](#getTube--) | Mendapatkan radius tabung. |
| [getTubularSegments()](#getTubularSegments--) | Mendapatkan segmen tubular. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setArc(double value)](#setArc-double-) | Mengatur busur. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah geometri ini dapat memancarkan bayangan |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Mengatur segmen radial. |
| [setRadius(double value)](#setRadius-double-) | Mengatur radius torus. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Mengatur apakah geometri ini dapat menerima bayangan. |
| [setTube(double value)](#setTube-double-) | Mengatur radius tabung. |
| [setTubularSegments(int value)](#setTubularSegments-int-) | Mengatur segmen tubular. |
| [toMesh()](#toMesh--) | Konversi objek saat ini ke mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Torus() {#Torus--}
```
public Torus()
```


Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus).

### Torus(double radius, double tube) {#Torus-double-double-}
```
public Torus(double radius, double tube)
```


Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radius | double | Radius torus. |
| tabung | double | Radius tabung torus. |

### Torus(double radius, double tube, double arc) {#Torus-double-double-double-}
```
public Torus(double radius, double tube, double arc)
```


Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radius | double | Radius torus. |
| tabung | double | Radius tabung torus. |
| busur | double | Busur. |

### Torus(String name, double radius, double tube, int radialSegments, int tubularSegments, double arc) {#Torus-java.lang.String-double-double-int-int-double-}
```
public Torus(String name, double radius, double tube, int radialSegments, int tubularSegments, double arc)
```


Menginisialisasi instance baru dari kelas [Torus](../../com.aspose.threed/torus).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |
| radius | double | Radius torus. |
| tabung | double | Radius tabung torus. |
| radialSegments | int | Segmen radial. |
| tubularSegments | int | Segmen tubular. |
| busur | double | Busur. |

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
### getArc() {#getArc--}
```
public double getArc()
```


Mendapatkan busur.

**Returns:**
double - busur.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Mendapatkan segmen radial.

**Returns:**
int - segmen radial.
### getRadius() {#getRadius--}
```
public double getRadius()
```


Mendapatkan radius torus.

**Returns:**
double - jari-jari torus.
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
### getTube() {#getTube--}
```
public double getTube()
```


Mendapatkan radius tabung.

**Returns:**
double - jari-jari tabung.
### getTubularSegments() {#getTubularSegments--}
```
public int getTubularSegments()
```


Mendapatkan segmen tubular.

**Returns:**
int - segmen tubular.
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
### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


Mengatur busur.

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Mengatur segmen radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setRadius(double value) {#setRadius-double-}
```
public void setRadius(double value)
```


Mengatur radius torus.

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

### setTube(double value) {#setTube-double-}
```
public void setTube(double value)
```


Mengatur radius tabung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setTubularSegments(int value) {#setTubularSegments-int-}
```
public void setTubularSegments(int value)
```


Mengatur segmen tubular.

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

