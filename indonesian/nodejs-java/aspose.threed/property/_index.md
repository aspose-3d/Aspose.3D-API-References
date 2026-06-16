---
title: "Property"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/property/
---
## Property class

Kelas untuk menampung properti yang didefinisikan pengguna.  @hideconstructor


## Metode

### getValue{#getValue}

| Nama | Deskripsi |
| --- | --- |
| getValue() | Mendapatkan atau mengatur nilai. Nilainya. |

 **Result:**



---


### setValue{#setValue}

| Nama | Deskripsi |
| --- | --- |
| setValue(value) | Mendapatkan atau mengatur nilai. Nilainya. |

 **Result:**



---


### setName{#setName}

| Nama | Deskripsi |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Nama | Deskripsi |
| --- | --- |
| getValueType() | Mendapatkan tipe nilai properti. Tipe nilai tersebut. |

 **Result:**



---


### getProperties{#getProperties}

| Nama | Deskripsi |
| --- | --- |
| getProperties() | Mendapatkan koleksi semua properti. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nama | Deskripsi |
| --- | --- |
| getBindPoint(anim, create) | Mendapatkan titik bind properti pada instance animasi yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| anim | AnimationNode | Pada animasi mana untuk membuat titik ikatan. |
| buat | boolean | Buat titik ikatan properti jika tidak ditemukan. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nama | Deskripsi |
| --- | --- |
| getKeyframeSequence(anim, create) | Mendapatkan urutan keyframe pada instance animasi yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| anim | AnimationNode | Pada animasi mana untuk membuat urutan keyframe. |
| buat | boolean | Buat urutan keyframe jika tidak ditemukan. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mengembalikan string yang mewakili Properti saat ini. |

 **Result:**
String


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



