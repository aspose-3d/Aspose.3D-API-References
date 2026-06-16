---
title: "AnimationNode"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D mendukung hierarki animasi, setiap animasi dapat terdiri dari beberapa animasi dan definisi key-frame animasi.  AnimationNode mendefinisikan transformasi nilai properti seiring waktu, misalnya, node animasi dapat digunakan untuk mengontrol transformasi node atau properti numerik objek A3DObject lainnya.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(name) | Menginisialisasi instance baru dari kelas AnimationNode. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload() | Menginisialisasi instance baru dari kelas AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Nama | Deskripsi |
| --- | --- |
| getBindPoints() | Mendapatkan titik bind properti saat ini |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Nama | Deskripsi |
| --- | --- |
| getSubAnimations() | Mendapatkan node sub-animasi di bawah animasi saat ini |

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


### findBindPoint{#findBindPoint}

| Nama | Deskripsi |
| --- | --- |
| findBindPoint(name) | Menemukan bind point berdasarkan nama. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama bind point yang akan dicari. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Nama | Deskripsi |
| --- | --- |
| getBindPoint(target, propName, create) | Mendapatkan bind point animasi pada properti yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| target | A3DObject | Pada objek mana untuk membuat bind point. |
| propName | String | Nama properti. |
| buat | boolean | Jika disetel ke |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nama | Deskripsi |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Mendapatkan urutan keyframe pada properti dan saluran yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| target | A3DObject | Pada instance mana untuk membuat urutan keyframe. |
| propName | String | Nama properti. |
| channelName | String | Nama saluran. |
| buat | boolean | Jika disetel ke |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Nama | Deskripsi |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Mendapatkan urutan keyframe pada properti yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| target | A3DObject | Pada instance mana untuk membuat urutan keyframe. |
| propName | String | Nama properti. |
| buat | boolean | Jika disetel ke |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Nama | Deskripsi |
| --- | --- |
| createBindPoint(obj, propName) | Membuat BindPoint berdasarkan tipe data properti. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| obj | A3DObject | Objek. |
| propName | String | Nama properti. |

 **Result:**
BindPoint


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



