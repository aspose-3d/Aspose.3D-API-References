---
title: "AnimationClip"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Klip Animasi adalah kumpulan animasi.  Adegan dapat memiliki satu atau lebih klip animasi.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name) | Menginisialisasi instance baru dari kelas AnimationClip. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |

 **Result:**



---


### getAnimations{#getAnimations}

| Nama | Deskripsi |
| --- | --- |
| getAnimations() | Mendapatkan animasi yang terdapat di dalam klip. Lapisan-lapisan. |

 **Result:**



---


### getDescription{#getDescription}

| Nama | Deskripsi |
| --- | --- |
| getDescription() | Mendapatkan atau mengatur deskripsi klip animasi ini |

 **Result:**



---


### setDescription{#setDescription}

| Nama | Deskripsi |
| --- | --- |
| setDescription(value) | Mendapatkan atau mengatur deskripsi klip animasi ini |

 **Result:**



---


### getStart{#getStart}

| Nama | Deskripsi |
| --- | --- |
| getStart() | Mendapatkan atau mengatur waktu dalam detik pada awal klip. |

 **Result:**



---


### setStart{#setStart}

| Nama | Deskripsi |
| --- | --- |
| setStart(value) | Mendapatkan atau mengatur waktu dalam detik pada awal klip. |

 **Result:**



---


### getStop{#getStop}

| Nama | Deskripsi |
| --- | --- |
| getStop() | Mendapatkan atau mengatur waktu dalam detik pada akhir klip. |

 **Result:**



---


### setStop{#setStop}

| Nama | Deskripsi |
| --- | --- |
| setStop(value) | Mendapatkan atau mengatur waktu dalam detik pada akhir klip. |

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


### createAnimationNode{#createAnimationNode}

| Nama | Deskripsi |
| --- | --- |
| createAnimationNode(nodeName) | Fungsi singkat untuk membuat dan mendaftarkan node animasi pada klip saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | String | Nama node animasi baru |

 **Result:**
AnimationNode


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



