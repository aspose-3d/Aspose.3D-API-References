---
title: "PolygonModifier"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Utilitas untuk memodifikasi poligon  @hideconstructor


## Metode

### triangulate{#triangulate}

| Nama | Deskripsi |
| --- | --- |
| triangulate(scene) | Mengonversi semua mesh berbasis poligon menjadi mesh segitiga penuh |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| scene | Scene | Adegan yang akan diproses |

 **Result:**



---


### triangulate{#triangulate}

| Nama | Deskripsi |
| --- | --- |
| triangulate(mesh) | Mengonversi mesh berbasis poligon menjadi mesh segitiga penuh |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | Mesh | Mesh non-segitiga asli |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nama | Deskripsi |
| --- | --- |
| mergeMesh(scene) | Mengonversi seluruh adegan menjadi satu mesh yang ditransformasi; elemen Vertex seperti koordinat normal/tekstur belum didukung. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| scene | Scene | Adegan yang akan digabungkan |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nama | Deskripsi |
| --- | --- |
| mergeMesh(node) | Mengonversi seluruh node menjadi satu mesh yang ditransformasi; elemen Vertex seperti koordinat normal/tekstur belum didukung. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Node yang akan digabungkan |

 **Result:**
Mesh


---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(scene, scale) | Skala semua geometri (Skala titik kontrol, bukan matriks transformasi) dalam adegan ini |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| scene | Scene | Adegan yang akan diskalakan |
| skala | Vector3 | Faktor skala |

 **Result:**
Mesh


---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(node, scale) | Skala semua geometri (Skala titik kontrol, bukan matriks transformasi) dalam node ini |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Node yang akan diskalakan |
| skala | Vector3 | Faktor skala |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Nama | Deskripsi |
| --- | --- |
| generateNormal(mesh) | Hasilkan data normal dari definisi Mesh |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Nama | Deskripsi |
| --- | --- |
| generateUV(mesh, normals) | Hasilkan data UV dari mesh input yang diberikan dan data normal yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | Mesh | Mesh input |
| normals | VertexElementNormal | Data normal |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Nama | Deskripsi |
| --- | --- |
| generateUV(mesh) | Hasilkan data UV dari mesh input yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | Mesh | Mesh input |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nama | Deskripsi |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Pisahkan mesh menjadi sub-mesh berdasarkan VertexElementMaterial. Setiap sub-mesh akan menggunakan hanya satu material. Lakukan pemisahan mesh pada sebuah node |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nod | Node | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Buat node anak untuk setiap sub-mesh. |
| removeOldMesh | boolean | Hapus mesh lama setelah pemisahan, jika parameter ini false, mesh lama dan baru akan tetap ada bersamaan. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nama | Deskripsi |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Pisahkan mesh menjadi sub-mesh berdasarkan VertexElementMaterial. Setiap sub-mesh akan menggunakan hanya satu material. Lakukan pemisahan mesh pada semua node dalam scene. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| scen | Scene | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nama | Deskripsi |
| --- | --- |
| splitMesh(mesh, policy) | Pisahkan mesh menjadi sub-mesh berdasarkan VertexElementMaterial. Setiap sub-mesh akan menggunakan hanya satu material. Mesh asli tidak akan diubah. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nama | Deskripsi |
| --- | --- |
| buildTangentBinormal(scene) | Ini akan membuat tangent dan binormal pada semua mesh dalam scene. Normal diperlukan, jika normal tidak ada pada mesh, maka juga akan dibuat data normal dari posisi. UV juga diperlukan, mesh akan diabaikan jika tidak ada UV yang didefinisikan. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nama | Deskripsi |
| --- | --- |
| buildTangentBinormal(mesh) | Ini akan membuat tangent dan binormal pada mesh. Normal diperlukan, jika normal tidak ada pada mesh, ia juga akan membuat data normal dari posisi. UV juga diperlukan, sebuah pengecualian akan dilempar jika tidak ada UV yang ditemukan. |

 **Result:**
Mesh[]


---



