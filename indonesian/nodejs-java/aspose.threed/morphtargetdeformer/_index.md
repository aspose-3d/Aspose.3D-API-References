---
title: "MorphTargetDeformer"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer menyediakan animasi per-vertex. MorphTargetDeformer mengatur semua target melalui MorphTargetChannel, setiap saluran dapat mengatur banyak target. Penggunaan umum morph target deformer adalah menerapkan ekspresi wajah pada karakter. Detail lebih lanjut dapat ditemukan di https://en.wikipedia.org/wiki/Morph_target_animation


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(name) | Menginisialisasi instance baru dari kelas MorphTargetDeformer. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload() | Menginisialisasi instance baru dari kelas MorphTargetDeformer. |

 **Result:**



---


### getChannels{#getChannels}

| Nama | Deskripsi |
| --- | --- |
| getChannels() | Mendapatkan semua saluran yang terdapat dalam deformer ini |

 **Result:**



---


### getOwner{#getOwner}

| Nama | Deskripsi |
| --- | --- |
| getOwner() | Mengambil geometri yang memiliki deformer ini |

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


### get{#get}

| Nama | Deskripsi |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Nama | Deskripsi |
| --- | --- |
| set(target, value) |  |

 **Result:**



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



