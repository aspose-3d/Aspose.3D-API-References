---
title: Mesh
second_title: Referensi API Aspose.3D untuk Java
description: Mesh terdiri dari banyak poligon ber‑sisi n.
type: docs
weight: 102
url: /id/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Mesh terdiri dari banyak poligon dengan n sisi. **Example:** Untuk menambahkan poligon ke mesh:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Jelajahi semua poligon dalam mesh:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Mesh()](#Mesh--) | Menginisialisasi sebuah instansi baru dari kelas [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | Menginisialisasi sebuah instansi baru dari kelas [Mesh](../../com.aspose.threed/mesh). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Mendapatkan semua deformer dengan tipe deformer yang ditentukan |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Tambahkan titik kontrol baru ke mesh, ini lebih efisien. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Tambahkan titik kontrol baru ke mesh, ini lebih efisien. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Menambahkan elemen vertex yang ada ke geometri saat ini |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Buat poligon dengan 3 titik(segitiga) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Buat poligon dengan 4 titik(kuad) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Membuat poligon baru dengan semua titik yang didefinisikan dalam `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Membuat poligon baru dengan semua titik yang didefinisikan dalam `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Hitung selisih dua mesh |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Lakukan operasi Boolean pada dua mesh |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCastShadows()](#getCastShadows--) | Mendapatkan apakah geometri ini dapat memancarkan bayangan |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Mendapatkan semua titik kontrol |
| [getDeformers()](#getDeformers--) | Mendapatkan semua deformer yang terkait dengan geometri ini. |
| [getEdges()](#getEdges--) | Mendapatkan tepi Mesh. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Mendapatkan elemen vertex dengan tipe yang ditentukan |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getPolygonCount()](#getPolygonCount--) | Mendapatkan jumlah poligon |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Mendapatkan jumlah vertex dari poligon yang ditentukan. |
| [getPolygons()](#getPolygons--) | Mendapatkan definisi poligon dari mesh |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getReceiveShadows()](#getReceiveShadows--) | Mendapatkan apakah geometri ini dapat menerima bayangan. |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Mendapatkan sebuah instance [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan |
| [getVertexElements()](#getVertexElements--) | Mendapatkan semua elemen vertex |
| [getVisible()](#getVisible--) | Mendapatkan apakah geometri terlihat |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Hitung irisan dua mesh |
| [isManifold()](#isManifold--) | Periksa apakah mesh saat ini adalah mesh manifold. |
| [iterator()](#iterator--) | Mendapatkan enumerator untuk setiap poligon dalam. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Mengatur apakah geometri ini dapat memancarkan bayangan |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Mengatur apakah geometri ini dapat menerima bayangan. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mengatur apakah geometri terlihat |
| [toMesh()](#toMesh--) | Mendapatkan instance Mesh dari entitas saat ini. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Kembalikan mesh yang ditriangulasi |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Hitung gabungan dua mesh |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Menginisialisasi sebuah instansi baru dari kelas [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Menginisialisasi sebuah instansi baru dari kelas [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Mendapatkan semua deformer dengan tipe deformer yang ditentukan

**Returns:**
java.util.Collection<T> - koleksi Deformer
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Tambahkan titik kontrol baru ke mesh, ini lebih efisien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | Komponen x dari titik kontrol |
| y | double | Komponen y dari titik kontrol |
| z | double | Komponen z dari titik kontrol |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Tambahkan titik kontrol baru ke mesh, ini lebih efisien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | Komponen x dari titik kontrol |
| y | double | Komponen y dari titik kontrol |
| z | double | Komponen z dari titik kontrol |
| w | double | Komponen w dari titik kontrol |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Menambahkan elemen vertex yang ada ke geometri saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Elemen vertex yang akan ditambahkan |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipe elemen vertex |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipe elemen vertex |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Mode pemetaan default |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Mode referensi default |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Jenis pemetaan tekstur yang akan dibuat |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Membuat sebuah [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Jenis pemetaan tekstur yang akan dibuat |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Mode pemetaan default |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Mode referensi default |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Buat poligon dengan 3 titik(segitiga)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v1 | int | Indeks vertex pertama |
| v2 | int | Indeks vertex kedua |
|  | v3 | int | Indeks vertex ketiga **Example:** Kode berikut menunjukkan cara membuat poligon baru dengan indeks titik kontrol. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Buat poligon dengan 4 titik(kuad)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v1 | int | Indeks vertex pertama |
| v2 | int | Indeks vertex kedua |
| v3 | int | Indeks vertex ketiga |
|  | v4 | int | Indeks vertex keempat **Example:** Kode berikut menunjukkan cara membuat poligon baru dengan indeks titik kontrol. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Membuat poligon baru dengan semua vertex yang didefinisikan dalam `indices`. Untuk membuat poligon vertex per vertex, silakan gunakan [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | indeks | int[] | Array dari indeks poligon, setiap indeks menunjuk ke titik kontrol yang membentuk poligon. **Contoh:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Membuat poligon baru dengan semua vertex yang didefinisikan dalam `indices`. Untuk membuat poligon vertex per vertex, silakan gunakan [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int[] | Array dari indeks poligon, setiap indeks menunjuk ke titik kontrol yang membentuk poligon. |
| offset | int | Offset dari indeks poligon pertama |
|  | panjang | int | Panjang dari indeks **Contoh:** Kode berikut menunjukkan cara membuat poligon baru dengan indeks titik kontrol. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Hitung selisih dua mesh

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Mesh pertama |
| b | [Mesh](../../com.aspose.threed/mesh) | Mesh kedua |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Lakukan operasi Boolean pada dua mesh

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Tipe operasi Boolean. |
| a | [Mesh](../../com.aspose.threed/mesh) | Mesh pertama untuk dioperasikan. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Matriks transformasi dari mesh pertama |
| b | [Mesh](../../com.aspose.threed/mesh) | Mesh kedua untuk dioperasikan |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Matriks transformasi dari mesh kedua |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Mendapatkan semua titik kontrol

**Returns:**
java.util.List<com.aspose.threed.Vector4> - semua titik kontrol
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Mendapatkan semua deformer yang terkait dengan geometri ini.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - semua deformer yang terkait dengan geometri ini.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Mendapatkan tepi dari Mesh. Tepi bersifat opsional dalam mesh, sehingga dapat kosong.

**Returns:**
java.util.List<java.lang.Integer> - tepi dari Mesh. Tepi bersifat opsional dalam mesh, sehingga dapat kosong.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Mendapatkan elemen vertex dengan tipe yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | tipe elemen vertex mana yang akan dicari |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Mendapatkan jumlah poligon

**Returns:**
int - jumlah poligon **Contoh:** Kode berikut menunjukkan cara mendapatkan jumlah poligon mesh.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Mendapatkan jumlah vertex dari poligon yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks. |

**Returns:**
int - Ukuran poligon.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Mendapatkan definisi poligon dari mesh

**Returns:**
java.util.List<int[]> - definisi poligon dari mesh
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
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Mendapatkan sebuah instance [VertexElementUV](../../com.aspose.threed/vertexelementuv) dengan tipe pemetaan tekstur yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Mendapatkan semua elemen vertex

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - semua elemen vertex
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Mendapatkan apakah geometri terlihat

**Returns:**
boolean - jika geometri terlihat
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


Hitung irisan dua mesh

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Mesh pertama |
| b | [Mesh](../../com.aspose.threed/mesh) | Mesh kedua |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Periksa apakah mesh saat ini adalah mesh manifold. Fungsi ini tidak akan menyimpan hasil perhitungan manifold.

**Returns:**
boolean - true jika mesh adalah mesh manifold.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Mendapatkan enumerator untuk setiap poligon dalam.

**Returns:**
java.util.Iterator<int[]> - Enumerator.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexElements | boolean | Optimalkan data elemen vertex yang duplikat |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexElements | boolean | Optimalkan data elemen vertex yang duplikat |
| toleranceControlPoint | float | Toleransi untuk control point, nilai default adalah 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexElements | boolean | Optimalkan data elemen vertex yang duplikat |
| toleranceControlPoint | float | Toleransi untuk control point, nilai default adalah 1e-9 |
| toleranceNormal | float | Toleransi untuk normal/tangent/binormal, nilai default adalah 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexElements | boolean | Optimalkan data elemen vertex yang duplikat |
| toleranceControlPoint | float | Toleransi untuk control point, nilai default adalah 1e-9 |
| toleranceNormal | float | Toleransi untuk normal/tangent/binormal, nilai default adalah 1e-9 |
| toleranceUV | float | Toleransi untuk uv, nilai default adalah 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Optimalkan penggunaan memori mesh dengan menghilangkan titik kontrol yang duplikat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexElements | boolean | Optimalkan data elemen vertex yang duplikat |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Mengatur apakah geometri terlihat

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Mendapatkan instance Mesh dari entitas saat ini.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


Kembalikan mesh yang ditriangulasi

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


Hitung gabungan dua mesh

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Mesh pertama |
| b | [Mesh](../../com.aspose.threed/mesh) | Mesh kedua |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
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

