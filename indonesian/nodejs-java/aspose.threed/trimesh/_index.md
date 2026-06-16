---
title: "TriMesh"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

TriMesh berisi data mentah yang dapat digunakan langsung oleh GPU.  Kelas ini adalah utilitas untuk membantu membangun mesh yang hanya berisi data per-vertex.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(name, declaration) | Inisialisasi sebuah instance dari TriMesh |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama dari TriMesh ini |
| deklarasi | VertexDeclaration | Deklarasi vertex |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Nama | Deskripsi |
| --- | --- |
| getVertexDeclaration() | Tata letak vertex dari TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Nama | Deskripsi |
| --- | --- |
| getVerticesCount() | Jumlah vertex dalam TriMesh ini |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Nama | Deskripsi |
| --- | --- |
| getIndicesCount() | Jumlah indeks dalam TriMesh ini |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Nama | Deskripsi |
| --- | --- |
| getUnmergedVerticesCount() | Jumlah vertex yang belum digabung yang diberikan melalui beginVertex() dan endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Nama | Deskripsi |
| --- | --- |
| getCapacity() | Kapasitas vertex yang telah dialokasikan sebelumnya. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Nama | Deskripsi |
| --- | --- |
| getVerticesSizeInBytes() | Ukuran total semua vertex dalam byte |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nama | Deskripsi |
| --- | --- |
| getParentNodes() | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansiasi geometri. Node-node tersebut. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nama | Deskripsi |
| --- | --- |
| getExcluded() | Mendapatkan atau mengatur apakah entitas ini harus dikecualikan selama ekspor. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nama | Deskripsi |
| --- | --- |
| setExcluded(value) | Mendapatkan atau mengatur apakah entitas ini harus dikecualikan selama ekspor. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nama | Deskripsi |
| --- | --- |
| getParentNode() | Mendapatkan atau mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. Node induk. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nama | Deskripsi |
| --- | --- |
| setParentNode(value) | Mendapatkan atau mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. Node induk. |

 **Result:**



---


### getScene{#getScene}

| Nama | Deskripsi |
| --- | --- |
| getScene() | Mendapatkan adegan yang dimiliki objek ini |

 **Result:**



---


### getName{#getName}

| Nama | Deskripsi |
| --- | --- |
| getName() | Mendapatkan atau mengatur nama. Nama. |

 **Result:**



---


### setName{#setName}

| Nama | Deskripsi |
| --- | --- |
| setName(value) | Mendapatkan atau mengatur nama. Nama. |

 **Result:**



---


### getProperties{#getProperties}

| Nama | Deskripsi |
| --- | --- |
| getProperties() | Mendapatkan koleksi semua properti. |

 **Result:**



---


### fromMesh{#fromMesh}

| Nama | Deskripsi |
| --- | --- |
| fromMesh(declaration, mesh) | Buat TriMesh dari objek mesh yang diberikan dengan tata letak vertex yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Nama | Deskripsi |
| --- | --- |
| copyFrom(input, vd) | Salin TriMesh dari input dengan tata letak vertex baru |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| input | TriMesh | TriMesh input untuk penyalinan. |
| vd | VertexDeclaration | Deklarasi vertex baru dari TriMesh output. |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Nama | Deskripsi |
| --- | --- |
| fromMesh(mesh, useFloat) | Buat TriMesh dari objek mesh yang diberikan, deklarasi vertex didasarkan pada struktur mesh input. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | Gunakan tipe float alih-alih tipe double untuk setiap komponen elemen vertex. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Nama | Deskripsi |
| --- | --- |
| beginVertex() | Mulai menambahkan vertex |

 **Result:**
Vertex


---


### endVertex{#endVertex}

| Nama | Deskripsi |
| --- | --- |
| endVertex() | Akhiri penambahan vertex |

 **Result:**
Vertex


---


### verticesToArray{#verticesToArray}

| Nama | Deskripsi |
| --- | --- |
| verticesToArray() | Konversi data vertices ke array byte |

 **Result:**
byte[]


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| Nama | Deskripsi |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Buat TriMesh dari data mentah TriMesh yang dikembalikan tidak akan menyalin array byte input untuk kinerja, perubahan eksternal pada array akan tercermin pada instance ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| vd | VertexDeclaration | Deklarasi vertex, harus berisi setidaknya satu field. |
| vertices | byte[] | Data vertex input, panjang minimum vertices harus lebih besar atau sama dengan ukuran deklarasi vertex. |
| indeks | Number[] | Indeks segitiga |
| generateVertexMapping | boolean | Hasilkan |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Nama | Deskripsi |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Muat vertices dari byte, panjang byte harus merupakan kelipatan bulat dari ukuran vertex. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Nama | Deskripsi |
| --- | --- |
| readVector4(idx, field) | Baca field vector4 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Field dengan tipe data Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Nama | Deskripsi |
| --- | --- |
| readFVector4(idx, field) | Baca field vector4 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Field dengan tipe data Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Nama | Deskripsi |
| --- | --- |
| readVector3(idx, field) | Baca field vector3 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Bidang dengan tipe data Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Nama | Deskripsi |
| --- | --- |
| readFVector3(idx, field) | Baca field vector3 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Bidang dengan tipe data Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Nama | Deskripsi |
| --- | --- |
| readVector2(idx, field) | Baca bidang vector2 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Bidang dengan tipe data Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Nama | Deskripsi |
| --- | --- |
| readFVector2(idx, field) | Baca bidang vector2 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Bidang dengan tipe data Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Nama | Deskripsi |
| --- | --- |
| readDouble(idx, field) | Baca bidang double |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Bidang dengan tipe data yang kompatibel dengan float/double |

 **Result:**
Angka


---


### readFloat{#readFloat}

| Nama | Deskripsi |
| --- | --- |
| readFloat(idx, field) | Baca bidang float |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| idx | Angka | Indeks vertex yang akan dibaca |
| field | VertexField | Bidang dengan tipe data yang kompatibel dengan float/double |

 **Result:**
Angka


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**
Angka


---


### getEntityRendererKey{#getEntityRendererKey}

| Nama | Deskripsi |
| --- | --- |
| getEntityRendererKey() | Mendapatkan kunci renderer entitas yang terdaftar di renderer |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Nama | Deskripsi |
| --- | --- |
| removeProperty(property) | Menghapus properti dinamis. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | Property | Properti mana yang akan dihapus |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nama | Deskripsi |
| --- | --- |
| removeProperty(property) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nama | Deskripsi |
| --- | --- |
| getProperty(property) | Dapatkan nilai properti yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | String | Nama properti |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nama | Deskripsi |
| --- | --- |
| setProperty(property, value) | Menetapkan nilai properti yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | String | Nama properti |
| value | Object | Nilai properti |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nama | Deskripsi |
| --- | --- |
| findProperty(propertyName) | Menemukan properti. Bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti native (Diidentifikasi berdasarkan namanya) |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | String | Nama properti. |

 **Result:**
Property


---


### iterator{#iterator}

| Nama | Deskripsi |
| --- | --- |
| iterator() | Dipesan untuk penggunaan internal. |

 **Result:**
Property


---



