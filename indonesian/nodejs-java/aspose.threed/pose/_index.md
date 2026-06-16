---
title: "Pose"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/pose/
---
## Pose class

Pose digunakan untuk menyimpan matriks transformasi ketika geometri di‑skin. Pose adalah sekumpulan BonePose, masing‑masing BonePose menyimpan informasi transformasi konkret dari node tulang.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(name) | Menginisialisasi instance baru dari kelas Pose. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload() | Menginisialisasi instance baru dari kelas Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| Nama | Deskripsi |
| --- | --- |
| getPoseType() | Mendapatkan atau mengatur tipe pose. Nilai properti adalah konstanta integer PoseType. Tipe pose. |

 **Result:**



---


### setPoseType{#setPoseType}

| Nama | Deskripsi |
| --- | --- |
| setPoseType(value) | Mendapatkan atau mengatur tipe pose. Nilai properti adalah konstanta integer PoseType. Tipe pose. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Nama | Deskripsi |
| --- | --- |
| getBonePoses() | Mendapatkan semua BonePose. Node-node. |

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


### addBonePose{#addBonePose}

| Nama | Deskripsi |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Menyimpan matriks transformasi pose untuk node tulang yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Node Tulang. |
| matrix | Matrix4 | Matriks transformasi. |
| localMatrix | boolean | Jika disetel ke |

 **Result:**



---


### addBonePose{#addBonePose}

| Nama | Deskripsi |
| --- | --- |
| addBonePose(node, matrix) | Menyimpan matriks transformasi pose untuk node tulang yang diberikan. Matriks transformasi global diasumsikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Node Tulang. |
| matrix | Matrix4 | Matriks transformasi. |

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



