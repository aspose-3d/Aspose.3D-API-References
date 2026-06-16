---
title: "BindPoint"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

BindPoint biasanya dibuat pada properti sebuah objek, beberapa tipe properti berisi beberapa bidang komponen (seperti bidang Vector3),  BindPoint akan menghasilkan saluran untuk setiap bidang komponen dan menghubungkan bidang tersebut ke satu atau lebih instance urutan keyframe melalui saluran.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(scene, prop) | Menginisialisasi instance baru dari kelas BindPoint. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| scene | Scene | Adegan yang berisi animasi. |
| prop | Property | Properti. |

 **Result:**



---


### getProperty{#getProperty}

| Nama | Deskripsi |
| --- | --- |
| getProperty() | Mendapatkan properti yang terkait dengan CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Nama | Deskripsi |
| --- | --- |
| setProperty(value) | Mendapatkan properti yang terkait dengan CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Nama | Deskripsi |
| --- | --- |
| getChannelsCount() | Mendapatkan total jumlah saluran properti yang didefinisikan dalam pemetaan kurva animasi ini. |

 **Result:**
Angka


---


### getName{#getName}

| Nama | Deskripsi |
| --- | --- |
| getName() | Mendapatkan atau mengatur nama. Nama. |

 **Result:**
Angka


---


### setName{#setName}

| Nama | Deskripsi |
| --- | --- |
| setName(value) | Mendapatkan atau mengatur nama. Nama. |

 **Result:**
Angka


---


### getProperties{#getProperties}

| Nama | Deskripsi |
| --- | --- |
| getProperties() | Mendapatkan koleksi semua properti. |

 **Result:**
Angka


---


### get{#get}

| Nama | Deskripsi |
| --- | --- |
| get(channelName) |  |

 **Result:**
Angka


---


### getKeyframeSequence{#getKeyframeSequence}

| Nama | Deskripsi |
| --- | --- |
| getKeyframeSequence(channelName) | Mendapatkan urutan keyframe pertama dalam saluran yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | String | Nama saluran yang akan dicari |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Nama | Deskripsi |
| --- | --- |
| getKeyframeSequences(channelName) | Mendapatkan semua urutan keyframe dalam saluran yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | String | Nama saluran yang akan dicari |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Nama | Deskripsi |
| --- | --- |
| createKeyframeSequence(name) | Membuat kurva baru dan menghubungkannya ke saluran pertama dari pemetaan kurva |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama urutan baru. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Nama | Deskripsi |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Mengikat urutan keyframe ke saluran yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | String | Saluran mana yang akan diikat oleh urutan keyframe |
| urutan | KeyframeSequence | Urutan keyframe yang akan diikat |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Nama | Deskripsi |
| --- | --- |
| getChannel(channelName) | Mendapatkan saluran berdasarkan nama yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| channelName | String | Nama saluran yang akan dicari |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Nama | Deskripsi |
| --- | --- |
| addChannel(name, value) | Menambahkan properti saluran yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |
| value | Object | Nilai. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Nama | Deskripsi |
| --- | --- |
| addChannel(name, type, value) | Menambahkan properti saluran yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |
| tipe | Kelas | Tipe. |
| value | Object | Nilai. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Nama | Deskripsi |
| --- | --- |
| resetChannels() | Mengosongkan saluran properti dari pemetaan kurva animasi ini. |

 **Result:**
boolean


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Memformat objek menjadi string |

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



