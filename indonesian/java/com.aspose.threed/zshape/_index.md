---
title: ZShape
second_title: Referensi API Aspose.3D untuk Java
description: Profil bentuk Z yang kompatibel dengan IFC yang didefinisikan oleh parameter.
type: docs
weight: 234
url: /id/java/com.aspose.threed/zshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class ZShape extends ParameterizedProfile
```

Profil bentuk Z yang kompatibel dengan IFC yang didefinisikan oleh parameter.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ZShape()](#ZShape--) | Konstruktor [ZShape](../../com.aspose.threed/zshape) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getClass()](#getClass--) |  |
| [getDepth()](#getDepth--) | Mendapatkan panjang web. |
| [getEdgeRadius()](#getEdgeRadius--) | Mendapatkan jari-jari tepi flange. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getExtent()](#getExtent--) | Mendapatkan rentang pada dimensi x dan y. |
| [getFilletRadius()](#getFilletRadius--) | Mendapatkan jari-jari fillet antara flange dan web. |
| [getFlangeThickness()](#getFlangeThickness--) | Mendapatkan ketebalan flange. |
| [getFlangeWidth()](#getFlangeWidth--) | Mendapatkan panjang flange. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getWebThickness()](#getWebThickness--) | Mendapatkan ketebalan dinding. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setDepth(double value)](#setDepth-double-) | Mengatur panjang web. |
| [setEdgeRadius(double value)](#setEdgeRadius-double-) | Mengatur jari-jari tepi flange. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setFilletRadius(double value)](#setFilletRadius-double-) | Mengatur jari-jari fillet antara flange dan web. |
| [setFlangeThickness(double value)](#setFlangeThickness-double-) | Mengatur ketebalan flange. |
| [setFlangeWidth(double value)](#setFlangeWidth-double-) | Mengatur panjang flange. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setWebThickness(double value)](#setWebThickness-double-) | Mengatur ketebalan dinding. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZShape() {#ZShape--}
```
public ZShape()
```


Konstruktor [ZShape](../../com.aspose.threed/zshape)

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepth() {#getDepth--}
```
public double getDepth()
```


Mendapatkan panjang web.

**Returns:**
double - panjang web.
### getEdgeRadius() {#getEdgeRadius--}
```
public double getEdgeRadius()
```


Mendapatkan jari-jari tepi flange.

**Returns:**
double - jari-jari tepi flange.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Mendapatkan kunci renderer entitas yang terdaftar di renderer

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor.

**Returns:**
boolean - apakah entitas ini akan dikecualikan saat mengekspor.
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


Mendapatkan rentang pada dimensi x dan y.

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getFilletRadius() {#getFilletRadius--}
```
public double getFilletRadius()
```


Mendapatkan jari-jari fillet antara flange dan web.

**Returns:**
double - jari-jari fillet antara flange dan web.
### getFlangeThickness() {#getFlangeThickness--}
```
public double getFlangeThickness()
```


Mendapatkan ketebalan flange.

**Returns:**
double - ketebalan flange.
### getFlangeWidth() {#getFlangeWidth--}
```
public double getFlangeWidth()
```


Mendapatkan panjang flange.

**Returns:**
double - panjang flange.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Mendapatkan adegan yang dimiliki objek ini

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getWebThickness() {#getWebThickness--}
```
public double getWebThickness()
```


Mendapatkan ketebalan dinding.

**Returns:**
double - ketebalan dinding.
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
### setDepth(double value) {#setDepth-double-}
```
public void setDepth(double value)
```


Mengatur panjang web.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setEdgeRadius(double value) {#setEdgeRadius-double-}
```
public void setEdgeRadius(double value)
```


Mengatur jari-jari tepi flange.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Mengatur apakah entitas ini akan dikecualikan saat mengekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setFilletRadius(double value) {#setFilletRadius-double-}
```
public void setFilletRadius(double value)
```


Mengatur jari-jari fillet antara flange dan web.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setFlangeThickness(double value) {#setFlangeThickness-double-}
```
public void setFlangeThickness(double value)
```


Mengatur ketebalan flange.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setFlangeWidth(double value) {#setFlangeWidth-double-}
```
public void setFlangeWidth(double value)
```


Mengatur panjang flange.

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

### setWebThickness(double value) {#setWebThickness-double-}
```
public void setWebThickness(double value)
```


Mengatur ketebalan dinding.

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

