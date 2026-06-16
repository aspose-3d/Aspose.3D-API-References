---
title: "KeyframeSequence"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Urutan key-frame, yang menggambarkan transformasi nilai yang disampel seiring waktu.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(name) | Menginisialisasi instance baru dari kelas KeyframeSequence. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload() | Menginisialisasi instance baru dari kelas KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nama | Deskripsi |
| --- | --- |
| getBindPoint() | Mendapatkan titik ikatan properti yang memiliki kurva ini |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Nama | Deskripsi |
| --- | --- |
| getKeyFrames() | Mendapatkan frame kunci dari kurva ini. Kuncinya. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Nama | Deskripsi |
| --- | --- |
| getPostBehavior() | Mendapatkan perilaku pasca yang menunjukkan nilai yang diambil sampelnya setelah frame kunci terakhir. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Nama | Deskripsi |
| --- | --- |
| getPreBehavior() | Mendapatkan perilaku pra yang menunjukkan nilai yang diambil sampelnya sebelum frame kunci pertama. |

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


### add{#add}

| Nama | Deskripsi |
| --- | --- |
| add(time, value) | Buat bingkai kunci baru dengan nilai yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| waktu | Angka | Posisi waktu (diukur dalam detik) |
| value | Angka | Nilai pada posisi waktu ini |

 **Result:**



---


### add{#add}

| Nama | Deskripsi |
| --- | --- |
| add(time, value, interpolation) | Buat bingkai kunci baru dengan nilai yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| waktu | Angka | Posisi waktu (diukur dalam detik) |
| value | Angka | Nilai pada posisi waktu ini |
| interpolasi | Interpolasi | Interpolasi |

 **Result:**



---


### reset{#reset}

| Nama | Deskripsi |
| --- | --- |
| reset() | Menghapus semua bingkai kunci dan mengatur ulang perilaku post/pre. |

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


### iterator{#iterator}

| Nama | Deskripsi |
| --- | --- |
| iterator() | Dipesan untuk penggunaan internal. |

 **Result:**
Property


---



