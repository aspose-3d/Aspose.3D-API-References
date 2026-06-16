---
title: "RevolvedAreaSolid"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Kelas ini merepresentasikan model padat dengan memutar penampang yang disediakan oleh profil sekitar sebuah sumbu.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Nama | Deskripsi |
| --- | --- |
| getAngleStart() | Mendapatkan atau mengatur sudut awal prosedur pemutaran, diukur dalam radian, nilai default adalah 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Nama | Deskripsi |
| --- | --- |
| setAngleStart(value) | Mendapatkan atau mengatur sudut awal prosedur pemutaran, diukur dalam radian, nilai default adalah 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Nama | Deskripsi |
| --- | --- |
| getAngleEnd() | Mendapatkan atau mengatur sudut akhir prosedur pemutaran, diukur dalam radian, nilai default adalah pi. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Nama | Deskripsi |
| --- | --- |
| setAngleEnd(value) | Mendapatkan atau mengatur sudut akhir prosedur pemutaran, diukur dalam radian, nilai default adalah pi. |

 **Result:**



---


### getAxis{#getAxis}

| Nama | Deskripsi |
| --- | --- |
| getAxis() | Mendapatkan atau mengatur arah sumbu, nilai default adalah (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Nama | Deskripsi |
| --- | --- |
| setAxis(value) | Mendapatkan atau mengatur arah sumbu, nilai default adalah (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Nama | Deskripsi |
| --- | --- |
| getOrigin() | Mendapatkan atau mengatur titik asal pemutaran, nilai default adalah (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Nama | Deskripsi |
| --- | --- |
| setOrigin(value) | Mendapatkan atau mengatur titik asal pemutaran, nilai default adalah (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Nama | Deskripsi |
| --- | --- |
| getShape() | Mendapatkan atau mengatur profil dasar yang digunakan untuk memutar. |

 **Result:**



---


### setShape{#setShape}

| Nama | Deskripsi |
| --- | --- |
| setShape(value) | Mendapatkan atau mengatur profil dasar yang digunakan untuk memutar. |

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


### toMesh{#toMesh}

| Nama | Deskripsi |
| --- | --- |
| toMesh() | Konversi RevolvedAreaSolid menjadi mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**
Mesh


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



