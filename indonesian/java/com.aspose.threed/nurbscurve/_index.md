---
title: NurbsCurve
second_title: Referensi API Aspose.3D untuk Java
description: Kurva NURBS adalah kurva yang direpresentasikan oleh NURBSNon-uniform rational basis spline. Sebuah kurva NURBS didefinisikan oleh sekumpulan titik kontrol berbobot dan ... Komponen w pada titik kontrol digunakan sebagai bobot titik kontrol, apa pun itu ... atau
type: docs
weight: 112
url: /id/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Menginisialisasi instance baru dari kelas [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Menginisialisasi instance baru dari kelas [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Evaluasi kurva NURBS |
| [evaluate(int steps)](#evaluate-int-) | Evaluasi kurva NURBS |
| [evaluateAt(double u)](#evaluateAt-double-) | Evaluasi titik kurva pada posisi yang ditentukan |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Mendapatkan warna garis, nilai default adalah putih(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Mendapatkan semua titik kontrol |
| [getCurveType()](#getCurveType--) | Mendapatkan tipe kurva. |
| [getDegree()](#getDegree--) | Mendapatkan derajat kurva NURBS, derajat didefinisikan sebagai Order - 1 |
| [getDimension()](#getDimension--) | Mendapatkan dimensi kurva. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getKnotVectors()](#getKnotVectors--) | Mendapatkan vektor knot, yaitu urutan nilai parameter yang menentukan di mana dan bagaimana titik kontrol memengaruhi kurva NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Mendapatkan multiplikitas. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getOrder()](#getOrder--) | Mendapatkan order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getRational()](#getRational--) | Mendapatkan apakah bersifat rasional, nilai ini menunjukkan apakah [NurbsCurve](../../com.aspose.threed/nurbscurve) ini merupakan spline rasional atau non-rasional. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Mengatur warna garis, nilai default adalah putih(1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Mengatur tipe kurva. |
| [setDegree(int value)](#setDegree-int-) | Mengatur derajat kurva NURBS, derajat didefinisikan sebagai Order - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Mengatur dimensi kurva. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setOrder(int value)](#setOrder-int-) | Mengatur order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setRational(boolean value)](#setRational-boolean-) | Mengatur apakah bersifat rasional, nilai ini menunjukkan apakah [NurbsCurve](../../com.aspose.threed/nurbscurve) ini merupakan spline rasional atau non-rasional. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Menginisialisasi instance baru dari kelas [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Menginisialisasi instance baru dari kelas [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Evaluasi kurva NURBS

**Returns:**
com.aspose.threed.Vector4[] - Titik-titik pada kurva
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Evaluasi kurva NURBS

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| langkah | int | Frekuensi evaluasi antara dua knot tetangga, nilai default adalah 20 |

**Returns:**
com.aspose.threed.Vector4[] - Titik-titik pada kurva
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Evaluasi titik kurva pada posisi yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| u | double | Posisi pada kurva, antara 0 dan 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Mendapatkan warna garis, nilai default adalah putih(1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Mendapatkan semua titik kontrol

**Returns:**
java.util.List<com.aspose.threed.Vector4> - semua titik kontrol
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Mendapatkan tipe kurva.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Mendapatkan derajat kurva NURBS, derajat didefinisikan sebagai Order - 1

**Returns:**
int - derajat kurva NURBS, derajat didefinisikan sebagai Order - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Mendapatkan dimensi kurva.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
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
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Mendapatkan vektor knot, yaitu urutan nilai parameter yang menentukan di mana dan bagaimana titik kontrol memengaruhi kurva NURBS.

**Returns:**
java.util.List<java.lang.Double> - vektor knot, yaitu urutan nilai parameter yang menentukan di mana dan bagaimana titik kontrol memengaruhi kurva NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Mendapatkan multiplikitas.

**Returns:**
java.util.List<java.lang.Integer> - multiplikasi.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Mendapatkan order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva.

**Returns:**
int - urutan kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva.
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
### getRational() {#getRational--}
```
public boolean getRational()
```


Mendapatkan apakah itu rasional, nilai ini menunjukkan apakah [NurbsCurve](../../com.aspose.threed/nurbscurve) ini merupakan spline rasional atau spline non-rasional. B-spline non-rasional adalah kasus khusus dari B-spline rasional.

**Returns:**
boolean - apakah itu rasional, nilai ini menunjukkan apakah [NurbsCurve](../../com.aspose.threed/nurbscurve) ini merupakan spline rasional atau spline non-rasional. B-spline non-rasional adalah kasus khusus dari B-spline rasional.
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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Mengatur warna garis, nilai default adalah putih(1, 1, 1)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Mengatur tipe kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nilai baru |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Mengatur derajat kurva NURBS, derajat didefinisikan sebagai Order - 1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Mengatur dimensi kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Nilai baru **Remarks:** Untuk kurva [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL), komponen z pada titik kontrol tidak digunakan. |

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

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Mengatur order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Mengatur apakah itu rasional, nilai ini menunjukkan apakah [NurbsCurve](../../com.aspose.threed/nurbscurve) ini merupakan spline rasional atau spline non-rasional. B-spline non-rasional adalah kasus khusus dari B-spline rasional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

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

