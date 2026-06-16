---
title: "Kerangka"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

Skeleton terutama digunakan oleh perangkat lunak CAD untuk membantu desainer memanipulasi transformasi struktur rangka, biasanya tidak berguna di luar perangkat lunak CAD.  Untuk membuat hierarki rangka berperilaku seperti satu objek dalam perangkat lunak CAD, perlu menandai node Skeleton teratas sebagai root dengan mengatur Type ke SkeletonType.SKELETON, dan semua anak diatur ke SkeletonType.BONE


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas Skeleton. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name) | Menginisialisasi instance baru dari kelas Skeleton. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### getSize{#getSize}

| Nama | Deskripsi |
| --- | --- |
| getSize() | Mendapatkan atau mengatur ukuran node anggota yang digunakan dalam perangkat lunak CAD untuk merepresentasikan ukuran tulang. |

 **Result:**



---


### setSize{#setSize}

| Nama | Deskripsi |
| --- | --- |
| setSize(value) | Mendapatkan atau mengatur ukuran node anggota yang digunakan dalam perangkat lunak CAD untuk merepresentasikan ukuran tulang. |

 **Result:**



---


### getType{#getType}

| Nama | Deskripsi |
| --- | --- |
| getType() | Mendapatkan atau mengatur tipe kerangka. Nilai properti adalah konstanta integer SkeletonType. Tipe kerangka. |

 **Result:**



---


### setType{#setType}

| Nama | Deskripsi |
| --- | --- |
| setType(value) | Mendapatkan atau mengatur tipe kerangka. Nilai properti adalah konstanta integer SkeletonType. Tipe kerangka. |

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


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**



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



