---
title: "Bone"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/bone/
---
## Bone class

Bone mendefinisikan subset titik kontrol geometri, dan menentukan bobot blend untuk setiap titik kontrol.  Objek Bone tidak dapat digunakan secara langsung, sebuah instance SkinDeformer digunakan untuk mendistorsi geometri, dan SkinDeformer dilengkapi dengan sekumpulan bone, masing-masing bone terhubung ke sebuah node.  CATATAN: Sebuah titik kontrol geometri dapat terikat ke lebih dari satu Bone.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(name) | Menginisialisasi instance baru dari kelas Bone. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload() | Menginisialisasi instance baru dari kelas Bone. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Nama | Deskripsi |
| --- | --- |
| getWeightCount() | Mendapatkan jumlah bobot, ini secara otomatis diperluas oleh setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Nama | Deskripsi |
| --- | --- |
| getTransform() | Mendapatkan atau mengatur matriks transformasi dari node yang berisi tulang. |

 **Result:**



---


### setTransform{#setTransform}

| Nama | Deskripsi |
| --- | --- |
| setTransform(value) | Mendapatkan atau mengatur matriks transformasi dari node yang berisi tulang. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Nama | Deskripsi |
| --- | --- |
| getBoneTransform() | Mendapatkan atau mengatur matriks transformasi dari tulang. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Nama | Deskripsi |
| --- | --- |
| setBoneTransform(value) | Mendapatkan atau mengatur matriks transformasi dari tulang. |

 **Result:**



---


### getNode{#getNode}

| Nama | Deskripsi |
| --- | --- |
| getNode() | Mendapatkan atau mengatur node. Node tulang adalah tulang yang terhubung dengan kulit, SkinDeformer akan menggunakan node tulang untuk memengaruhi perpindahan titik kontrol. Node tulang biasanya memiliki Skeleton yang terpasang, tetapi tidak diwajibkan. Skeleton yang terpasang biasanya digunakan oleh perangkat lunak DCC untuk menampilkan skeleton kepada pengguna. |

 **Result:**



---


### setNode{#setNode}

| Nama | Deskripsi |
| --- | --- |
| setNode(value) | Mendapatkan atau mengatur node. Node tulang adalah tulang yang terhubung dengan kulit, SkinDeformer akan menggunakan node tulang untuk memengaruhi perpindahan titik kontrol. Node tulang biasanya memiliki Skeleton yang terpasang, tetapi tidak diwajibkan. Skeleton yang terpasang biasanya digunakan oleh perangkat lunak DCC untuk menampilkan skeleton kepada pengguna. |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| Nama | Deskripsi |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Nama | Deskripsi |
| --- | --- |
| getWeight(index) | Mendapatkan bobot untuk titik kontrol yang ditentukan oleh indeks |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | Angka | Indeks titik kontrol |

 **Result:**
Angka


---


### setWeight{#setWeight}

| Nama | Deskripsi |
| --- | --- |
| setWeight(index, weight) | Mengatur bobot untuk titik kontrol yang ditentukan oleh indeks |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | Angka | Indeks titik kontrol |
| berat | Angka | Berat baru |

 **Result:**
Angka


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



