---
title: HShape
second_title: Referensi API Aspose.3D untuk Java
description: Memberikan parameter penentu untuk bentuk H atau I.
type: docs
weight: 76
url: /id/java/com.aspose.threed/hshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class HShape extends ParameterizedProfile
```

[HShape](../../com.aspose.threed/hshape) menyediakan parameter penentu untuk bentuk 'H' atau 'I'.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HShape()](#HShape--) | Konstruktor dari [HShape](../../com.aspose.threed/hshape) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBottomFlangeEdgeRadius()](#getBottomFlangeEdgeRadius--) | Mendapatkan radius tepi atas dari flensa bawah. |
| [getBottomFlangeFilletRadius()](#getBottomFlangeFilletRadius--) | Mendapatkan radius fillet antara web dan flange bawah. |
| [getBottomFlangeThickness()](#getBottomFlangeThickness--) | Mendapatkan ketebalan flange H-shape. |
| [getBottomFlangeWidth()](#getBottomFlangeWidth--) | Mendapatkan rentang lebar. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getExtent()](#getExtent--) | Mendapatkan rentang pada dimensi x dan y. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getOverallDepth()](#getOverallDepth--) | Mendapatkan rentang kedalaman. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getTopFlangeEdgeRadius()](#getTopFlangeEdgeRadius--) | Mendapatkan radius tepi bawah flange atas. |
| [getTopFlangeFilletRadius()](#getTopFlangeFilletRadius--) | Mendapatkan radius fillet antara web dan flange atas. |
| [getTopFlangeThickness()](#getTopFlangeThickness--) | Mendapatkan ketebalan flange atas. |
| [getTopFlangeWidth()](#getTopFlangeWidth--) | Mendapatkan lebar flange atas. |
| [getWebThickness()](#getWebThickness--) | Mendapatkan ketebalan web H-shape. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setBottomFlangeEdgeRadius(double value)](#setBottomFlangeEdgeRadius-double-) | Mengatur radius tepi atas flange bawah. |
| [setBottomFlangeFilletRadius(double value)](#setBottomFlangeFilletRadius-double-) | Mengatur radius fillet antara web dan flange bawah. |
| [setBottomFlangeThickness(double value)](#setBottomFlangeThickness-double-) | Mengatur ketebalan flange H-shape. |
| [setBottomFlangeWidth(double value)](#setBottomFlangeWidth-double-) | Mengatur rentang lebar. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setOverallDepth(double value)](#setOverallDepth-double-) | Mengatur rentang kedalaman. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setTopFlangeEdgeRadius(double value)](#setTopFlangeEdgeRadius-double-) | Mengatur radius tepi bawah flange atas. |
| [setTopFlangeFilletRadius(double value)](#setTopFlangeFilletRadius-double-) | Mengatur radius fillet antara web dan flange atas. |
| [setTopFlangeThickness(double value)](#setTopFlangeThickness-double-) | Mengatur ketebalan flange atas. |
| [setTopFlangeWidth(double value)](#setTopFlangeWidth-double-) | Mengatur lebar flange atas. |
| [setWebThickness(double value)](#setWebThickness-double-) | Mengatur ketebalan web H-shape. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HShape() {#HShape--}
```
public HShape()
```


Konstruktor dari [HShape](../../com.aspose.threed/hshape)

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
### getBottomFlangeEdgeRadius() {#getBottomFlangeEdgeRadius--}
```
public double getBottomFlangeEdgeRadius()
```


Mendapatkan radius tepi atas dari flensa bawah.

**Returns:**
double - radius tepi atas flange bawah.
### getBottomFlangeFilletRadius() {#getBottomFlangeFilletRadius--}
```
public double getBottomFlangeFilletRadius()
```


Mendapatkan radius fillet antara web dan flange bawah.

**Returns:**
double - radius fillet antara web dan flange bawah.
### getBottomFlangeThickness() {#getBottomFlangeThickness--}
```
public double getBottomFlangeThickness()
```


Mendapatkan ketebalan flange H-shape.

**Returns:**
double - ketebalan flange H-shape.
### getBottomFlangeWidth() {#getBottomFlangeWidth--}
```
public double getBottomFlangeWidth()
```


Mendapatkan rentang lebar.

**Returns:**
double - rentang lebar.
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
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getOverallDepth() {#getOverallDepth--}
```
public double getOverallDepth()
```


Mendapatkan rentang kedalaman.

**Returns:**
double - rentang kedalaman.
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
### getTopFlangeEdgeRadius() {#getTopFlangeEdgeRadius--}
```
public double getTopFlangeEdgeRadius()
```


Mendapatkan radius tepi bawah flange atas.

**Returns:**
double - radius tepi bawah flange atas.
### getTopFlangeFilletRadius() {#getTopFlangeFilletRadius--}
```
public double getTopFlangeFilletRadius()
```


Mendapatkan radius fillet antara web dan flange atas.

**Returns:**
double - jari-jari fillet antara web dan flange atas.
### getTopFlangeThickness() {#getTopFlangeThickness--}
```
public double getTopFlangeThickness()
```


Mendapatkan ketebalan flange atas.

**Returns:**
double - ketebalan flange atas.
### getTopFlangeWidth() {#getTopFlangeWidth--}
```
public double getTopFlangeWidth()
```


Mendapatkan lebar flange atas.

**Returns:**
double - lebar flange atas.
### getWebThickness() {#getWebThickness--}
```
public double getWebThickness()
```


Mendapatkan ketebalan web H-shape.

**Returns:**
double - ketebalan web dari bentuk H.
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
### setBottomFlangeEdgeRadius(double value) {#setBottomFlangeEdgeRadius-double-}
```
public void setBottomFlangeEdgeRadius(double value)
```


Mengatur radius tepi atas flange bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setBottomFlangeFilletRadius(double value) {#setBottomFlangeFilletRadius-double-}
```
public void setBottomFlangeFilletRadius(double value)
```


Mengatur radius fillet antara web dan flange bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setBottomFlangeThickness(double value) {#setBottomFlangeThickness-double-}
```
public void setBottomFlangeThickness(double value)
```


Mengatur ketebalan flange H-shape.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setBottomFlangeWidth(double value) {#setBottomFlangeWidth-double-}
```
public void setBottomFlangeWidth(double value)
```


Mengatur rentang lebar.

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

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setOverallDepth(double value) {#setOverallDepth-double-}
```
public void setOverallDepth(double value)
```


Mengatur rentang kedalaman.

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

### setTopFlangeEdgeRadius(double value) {#setTopFlangeEdgeRadius-double-}
```
public void setTopFlangeEdgeRadius(double value)
```


Mengatur radius tepi bawah flange atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setTopFlangeFilletRadius(double value) {#setTopFlangeFilletRadius-double-}
```
public void setTopFlangeFilletRadius(double value)
```


Mengatur radius fillet antara web dan flange atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setTopFlangeThickness(double value) {#setTopFlangeThickness-double-}
```
public void setTopFlangeThickness(double value)
```


Mengatur ketebalan flange atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setTopFlangeWidth(double value) {#setTopFlangeWidth-double-}
```
public void setTopFlangeWidth(double value)
```


Mengatur lebar flange atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setWebThickness(double value) {#setWebThickness-double-}
```
public void setWebThickness(double value)
```


Mengatur ketebalan web H-shape.

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

