---
title: "MorphTargetChannel"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetChannel digunakan oleh MorphTargetDeformer untuk mengatur geometri target. Beberapa format file seperti FBX mendukung banyak saluran secara paralel. Bobot berada di antara 0 dan 1.0, dan bobot default untuk target adalah 0.0;


## Properti

| Nama | Deskripsi |
| --- | --- |
| DEFAULT_WEIGHT | Berat default untuk morph target. |

## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(name) | Menginisialisasi instance baru dari kelas MorphTargetChannel. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload() | Menginisialisasi instance baru dari kelas MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| Nama | Deskripsi |
| --- | --- |
| getWeights() | Mendapatkan nilai berat penuh dari geometri target. Berat penuh. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Nama | Deskripsi |
| --- | --- |
| getChannelWeight() | Mendapatkan atau mengatur berat deformer dari saluran ini. Berat berada di antara 0.0 dan 1.0 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Nama | Deskripsi |
| --- | --- |
| setChannelWeight(value) | Mendapatkan atau mengatur berat deformer dari saluran ini. Berat berada di antara 0.0 dan 1.0 |

 **Result:**



---


### getTargets{#getTargets}

| Nama | Deskripsi |
| --- | --- |
| getTargets() | Mendapatkan semua target yang terkait dengan saluran. |

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


### getWeight{#getWeight}

| Nama | Deskripsi |
| --- | --- |
| getWeight(target) | Mendapatkan bobot untuk target yang ditentukan, jika target tidak termasuk dalam saluran ini, nilai default 0 dikembalikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| targe | Bentuk | null |

 **Result:**
Angka


---


### setWeight{#setWeight}

| Nama | Deskripsi |
| --- | --- |
| setWeight(target, weight) | Menetapkan bobot untuk target yang ditentukan, nilai default adalah 1, rentang harus antara 0~1 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| targe | Bentuk | null |
| menimbang | Angka | null |

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



