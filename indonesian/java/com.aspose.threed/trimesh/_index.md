---
title: TriMesh
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah TriMesh berisi data mentah yang dapat digunakan langsung oleh GPU.
type: docs
weight: 194
url: /id/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

Sebuah TriMesh berisi data mentah yang dapat digunakan langsung oleh GPU. Kelas ini adalah utilitas untuk membantu membangun mesh yang hanya berisi data per-vertex. **Example:** Kode berikut menunjukkan cara membuat TriMesh dengan tata letak memori khusus, dan mengekspornya ke file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | Inisialisasi sebuah instance dari [TriMesh](../../com.aspose.threed/trimesh) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | Tambahkan segitiga baru |
| [beginVertex()](#beginVertex--) | Mulai menambahkan vertex |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | Salin [TriMesh](../../com.aspose.threed/trimesh) dari input dengan tata letak vertex baru |
| [endVertex()](#endVertex--) | Selesai menambahkan vertex |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | Buat TriMesh dari objek mesh yang diberikan, deklarasi vertex didasarkan pada struktur mesh input. |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | Buat TriMesh dari objek mesh yang diberikan, deklarasi vertex didasarkan pada struktur mesh input. |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | Buat TriMesh dari objek mesh yang diberikan dengan tata letak vertex yang diberikan. |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | Buat TriMesh dari data mentah |
| [getBoundingBox()](#getBoundingBox--) | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| [getCapacity()](#getCapacity--) | Kapasitas vertex yang telah dialokasikan sebelumnya. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Mendapatkan kunci renderer entitas yang terdaftar di renderer |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah entitas ini akan dikecualikan saat mengekspor. |
| [getIndicesCount()](#getIndicesCount--) | Jumlah indeks dalam [TriMesh](../../com.aspose.threed/trimesh) ini |
| [getIntIndices()](#getIntIndices--) | Konversi indeks ke array integer 32-bit |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk pertama, jika menetapkan node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [getParentNodes()](#getParentNodes--) | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansi geometri |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getShortIndices()](#getShortIndices--) | Konversi indeks ke array integer 16-bit |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | Jumlah vertex yang belum digabung yang diberikan melalui [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) dan [endVertex](../../com.aspose.threed/trimesh\#endVertex). |
| [getVertexDeclaration()](#getVertexDeclaration--) | Tata letak vertex dari [TriMesh](../../com.aspose.threed/trimesh). |
| [getVerticesCount()](#getVerticesCount--) | Jumlah vertex dalam [TriMesh](../../com.aspose.threed/trimesh) ini |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | Ukuran total semua vertex dalam byte |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | Konversi indeks ke array integer 32-bit |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | Konversi indeks ke array integer 16-bit |
| [iterator()](#iterator--) | Dapatkan enumerator untuk mengiterasi [Vertex](../../com.aspose.threed/vertex) |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | Muat vertex dari byte, panjang byte harus merupakan kelipatan bulat dari ukuran vertex. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | Baca bidang double |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | Baca bidang vector2 |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | Baca bidang vector3 |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | Baca bidang vector4 |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | Baca bidang float |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | Baca bidang vector2 |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | Baca bidang vector3 |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | Baca bidang vector4 |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah entitas ini akan dikecualikan saat mengekspor. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan dipisahkan dari node induk lainnya. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [toString()](#toString--) | Mendapatkan representasi string dari [TriMesh](../../com.aspose.threed/trimesh) |
| [verticesToArray()](#verticesToArray--) | Konversi data vertices menjadi array byte |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | Tulis data indeks sebagai integer 16bit ke aliran **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | Tulis data indeks sebagai integer 16bit ke aliran |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | Tulis data indeks sebagai integer 32bit ke aliran **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | Tulis data indeks sebagai integer 32bit ke aliran |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | Tulis data vertices ke aliran yang ditentukan |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | Tulis data vertices ke aliran yang ditentukan |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


Inisialisasi sebuah instance dari [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama dari TriMesh ini |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Deklarasi vertex |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


Tambahkan segitiga baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | int | Indeks vertex pertama |
| b | int | Indeks vertex kedua |
| c | int | Indeks vertex ketiga |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


Mulai menambahkan vertex

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


Salin [TriMesh](../../com.aspose.threed/trimesh) dari input dengan tata letak vertex baru

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | TriMesh input untuk penyalinan |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Deklarasi vertex baru dari TriMesh output |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - A new TriMesh instance with new vertex declaration. **Example:**

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
  vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
  //convert a mesh to TriMesh, the layout is automatically inferred from input mesh
  var oldTriMesh = TriMesh.fromMesh((new Sphere()).toMesh());
  //now create a new TriMesh from old TriMesh, using explicit memory layout defined by vd
  var newTriMesh = TriMesh.copyFrom(oldTriMesh, vd);
```
### endVertex() {#endVertex--}
```
public int endVertex()
```


Selesai menambahkan vertex

**Returns:**
int
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
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


Buat TriMesh dari objek mesh yang diberikan, deklarasi vertex didasarkan pada struktur mesh input.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(Mesh mesh, boolean useFloat) {#fromMesh-com.aspose.threed.Mesh-boolean-}
```
public static TriMesh fromMesh(Mesh mesh, boolean useFloat)
```


Buat TriMesh dari objek mesh yang diberikan, deklarasi vertex didasarkan pada struktur mesh input.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | Gunakan tipe float alih-alih tipe double untuk setiap komponen elemen vertex. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(VertexDeclaration declaration, Mesh mesh) {#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(VertexDeclaration declaration, Mesh mesh)
```


Buat TriMesh dari objek mesh yang diberikan dengan tata letak vertex yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Definisi tipe vertex, atau tata letak memori |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Mesh sumber |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - Instance of TriMesh converted from input mesh with specified vertex's memory layout **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping) {#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-}
```
public static TriMesh fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)
```


Buat TriMesh dari data mentah

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Deklarasi vertex, harus berisi setidaknya satu bidang. |
| vertices | byte[] | Data vertex input, panjang minimum vertex harus lebih besar atau sama dengan ukuran deklarasi vertex |
| indeks | int[] | Indeks segitiga |
| generateVertexMapping | boolean | Hasilkan [Vertex](../../com.aspose.threed/vertex) untuk setiap vertex, yang tidak diperlukan hanya untuk serialisasi/deserialisasi. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) instance that encapsulated the input byte array. **Remarks:** The returned TriMesh will not copy the input byte array for performance, external changes on the array will be reflected to this instance. **Example:** The following code shows how to construct a TriMesh from raw bytes, this is useful when build your own 3D format

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0The string representation,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```
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
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```


Kapasitas vertex yang telah dialokasikan sebelumnya.

**Returns:**
int - Kapasitas vertex yang telah dialokasikan sebelumnya.
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
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


Jumlah indeks dalam [TriMesh](../../com.aspose.threed/trimesh) ini

**Returns:**
int - Jumlah indeks dalam [TriMesh](../../com.aspose.threed/trimesh) ini
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


Konversi indeks ke array integer 32-bit

**Returns:**
int[]
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
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


Konversi indeks ke array integer 16-bit

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


Jumlah vertex yang belum digabung yang diberikan melalui [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) dan [endVertex](../../com.aspose.threed/trimesh\#endVertex).

**Returns:**
int - Jumlah vertex yang belum digabung yang diberikan melalui [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) dan [endVertex](../../com.aspose.threed/trimesh\#endVertex).
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


Tata letak vertex dari [TriMesh](../../com.aspose.threed/trimesh).

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


Jumlah vertex dalam [TriMesh](../../com.aspose.threed/trimesh) ini

**Returns:**
int - Jumlah vertex dalam [TriMesh](../../com.aspose.threed/trimesh) ini
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


Ukuran total semua vertex dalam byte

**Returns:**
int - Total ukuran semua vertex dalam byte
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicesToArray(int[][] result) {#indicesToArray-int-----}
```
public void indicesToArray(int[][] result)
```


Konversi indeks ke array integer 32-bit

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hasil | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


Konversi indeks ke array integer 16-bit

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hasil | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


Dapatkan enumerator untuk mengiterasi [Vertex](../../com.aspose.threed/vertex)

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


Muat vertex dari byte, panjang byte harus merupakan kelipatan bulat dari ukuran vertex. **Contoh:** Kode berikut menunjukkan cara membuat TriMesh kosong dan memuat vertex secara manual dari byte mentah.

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.LoadVerticesFromBytes(vertices);
  triMesh.AddTriangle(0, 1, 2);
```

```
int[] indices = new int[] { 0,  1,  2 };
  byte[] vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.loadVerticesFromBytes(vertices);
  triMesh.addTriangle(0, 1, 2);
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| verticesInBytes | byte[] |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readDouble(int idx, VertexField field) {#readDouble-int-com.aspose.threed.VertexField-}
```
public double readDouble(int idx, VertexField field)
```


Baca bidang double

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data yang kompatibel float/double |

**Returns:**
double - Nilai double dari field vertex yang ditentukan
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


Baca bidang vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data Vector2/FVector2 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


Baca bidang vector3

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data Vector3/FVector3 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


Baca bidang vector4

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data Vector4/FVector4 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


Baca bidang float

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data yang kompatibel float/double |

**Returns:**
float - Nilai float dari field vertex yang ditentukan
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


Baca bidang vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data Vector2/FVector2 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


Baca bidang vector3

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data Vector3/FVector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


Baca bidang vector4

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks vertex yang akan dibaca |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Field dengan tipe data Vector4/FVector4 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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

### toString() {#toString--}
```
public String toString()
```


Mendapatkan representasi string dari [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
java.lang.String - Representasi string
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


Konversi data vertices menjadi array byte

**Returns:**
byte[]
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

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


Tulis data indeks sebagai integer 16bit ke aliran **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


Tulis data indeks sebagai integer 16bit ke aliran

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.OutputStream | **Contoh:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
     var mesh = (new Sphere()).toMesh();    
     var triMesh = TriMesh.fromMesh(mesh);    
     //save it to a stream, 115 vertices * 32bytes per vertex    
     var stream = new ByteArrayOutputStream();    
     triMesh.writeVerticesTo(stream);    
     //save indices as ushort to stream, 504 indices * 2 bytes per index    
     triMesh.write16bIndicesTo(stream);
``` |

### write32bIndicesTo(Stream stream) {#write32bIndicesTo-com.aspose.threed.Stream-}
```
public void write32bIndicesTo(Stream stream)
```


Tulis data indeks sebagai integer 32bit ke aliran **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write32bIndicesTo(s);
      }
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


Tulis data indeks sebagai integer 32bit ke aliran

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.OutputStream | **Contoh:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write32bIndicesTo(stream);
``` |

### writeVerticesTo(Stream stream) {#writeVerticesTo-com.aspose.threed.Stream-}
```
public void writeVerticesTo(Stream stream)
```


Tulis data vertices ke aliran yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | Aliran yang data verteks akan dituliskan ke **Contoh:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
``` |

### writeVerticesTo(OutputStream stream) {#writeVerticesTo-java.io.OutputStream-}
```
public void writeVerticesTo(OutputStream stream)
```


Tulis data vertices ke aliran yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | aliran | java.io.OutputStream | Aliran yang data verteks akan dituliskan ke **Contoh:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write16bIndicesTo(stream);
``` |

