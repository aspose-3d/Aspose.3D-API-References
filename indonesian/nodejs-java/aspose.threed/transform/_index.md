---
title: "Transformasi"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/transform/
---
## Transform class

Transform berisi informasi yang memungkinkan akses ke translasi/skala/rotasi objek atau matriks transformasi dengan biaya minimal.  Ini digunakan oleh transformasi lokal.  @hideconstructor


## Metode

### getGeometricTranslation{#getGeometricTranslation}

| Nama | Deskripsi |
| --- | --- |
| getGeometricTranslation() | Mendapatkan atau mengatur translasi geometrik. Transformasi geometrik hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometrik ke tipe file yang tidak mendukungnya. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Nama | Deskripsi |
| --- | --- |
| setGeometricTranslation(value) | Mendapatkan atau mengatur translasi geometrik. Transformasi geometrik hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometrik ke tipe file yang tidak mendukungnya. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Nama | Deskripsi |
| --- | --- |
| getGeometricScaling() | Mendapatkan atau mengatur skala geometrik. Transformasi geometrik hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometrik ke tipe file yang tidak mendukungnya. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nama | Deskripsi |
| --- | --- |
| setGeometricScaling(value) | Mendapatkan atau mengatur skala geometrik. Transformasi geometrik hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometrik ke tipe file yang tidak mendukungnya. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Nama | Deskripsi |
| --- | --- |
| getGeometricRotation() | Mendapatkan atau mengatur rotasi Euler geometrik (diukur dalam derajat). Transformasi geometrik hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometrik ke tipe file yang tidak mendukungnya. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nama | Deskripsi |
| --- | --- |
| setGeometricRotation(value) | Mendapatkan atau mengatur rotasi Euler geometrik (diukur dalam derajat). Transformasi geometrik hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Transformasi ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometrik ke tipe file yang tidak mendukungnya. |

 **Result:**



---


### getTranslation{#getTranslation}

| Nama | Deskripsi |
| --- | --- |
| getTranslation() | Mendapatkan atau mengatur translasi |

 **Result:**



---


### setTranslation{#setTranslation}

| Nama | Deskripsi |
| --- | --- |
| setTranslation(value) | Mendapatkan atau mengatur translasi |

 **Result:**



---


### getScale{#getScale}

| Nama | Deskripsi |
| --- | --- |
| getScale() | Mendapatkan atau mengatur skala |

 **Result:**



---


### setScale{#setScale}

| Nama | Deskripsi |
| --- | --- |
| setScale(value) | Mendapatkan atau mengatur skala |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Nama | Deskripsi |
| --- | --- |
| getPreRotation() | Mendapatkan atau mengatur pra-rotasi yang direpresentasikan dalam derajat |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Nama | Deskripsi |
| --- | --- |
| setPreRotation(value) | Mendapatkan atau mengatur pra-rotasi yang direpresentasikan dalam derajat |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Nama | Deskripsi |
| --- | --- |
| getPostRotation() | Mendapatkan atau mengatur pasca-rotasi yang direpresentasikan dalam derajat |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Nama | Deskripsi |
| --- | --- |
| setPostRotation(value) | Mendapatkan atau mengatur pasca-rotasi yang direpresentasikan dalam derajat |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Nama | Deskripsi |
| --- | --- |
| getEulerAngles() | Mendapatkan atau mengatur rotasi yang direpresentasikan dalam sudut Euler, diukur dalam derajat |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Nama | Deskripsi |
| --- | --- |
| setEulerAngles(value) | Mendapatkan atau mengatur rotasi yang direpresentasikan dalam sudut Euler, diukur dalam derajat |

 **Result:**



---


### getRotation{#getRotation}

| Nama | Deskripsi |
| --- | --- |
| getRotation() | Mendapatkan atau mengatur rotasi yang direpresentasikan dalam kuaternion. |

 **Result:**



---


### setRotation{#setRotation}

| Nama | Deskripsi |
| --- | --- |
| setRotation(value) | Mendapatkan atau mengatur rotasi yang direpresentasikan dalam kuaternion. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Nama | Deskripsi |
| --- | --- |
| getTransformMatrix() | Mendapatkan atau mengatur matriks transformasi. Penetapan pada ini akan mengatur ulang Translation, Scale, dan Rotation, sementara GeometricRotation, GeometricScaling, dan GeometricTranslation tidak akan terpengaruh. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Nama | Deskripsi |
| --- | --- |
| setTransformMatrix(value) | Mendapatkan atau mengatur matriks transformasi. Penetapan pada ini akan mengatur ulang Translation, Scale, dan Rotation, sementara GeometricRotation, GeometricScaling, dan GeometricTranslation tidak akan terpengaruh. |

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


### setGeometricTranslation{#setGeometricTranslation}

| Nama | Deskripsi |
| --- | --- |
| setGeometricTranslation(x, y, z) | Mengatur translasi geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke jenis file yang tidak mendukungnya. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nama | Deskripsi |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Mengatur skala geometris. Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke jenis file yang tidak mendukungnya. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nama | Deskripsi |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Mengatur rotasi Euler geometris (diukur dalam derajat). Transformasi geometris hanya memengaruhi entitas yang terlampir dan tidak memengaruhi node anak. Ini akan digabungkan sebagai transformasi lokal ketika Anda mengekspor transformasi geometris ke jenis file yang tidak mendukungnya. |

 **Result:**



---


### setTranslation{#setTranslation}

| Nama | Deskripsi |
| --- | --- |
| setTranslation(tx, ty, tz) | Mengatur translasi transformasi saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| t | Angka | null |
| t | Angka | null |
| t | Angka | null |

 **Result:**
Transformasi


---


### setScale{#setScale}

| Nama | Deskripsi |
| --- | --- |
| setScale(sx, sy, sz) | Mengatur skala transformasi saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| s | Angka | null |
| s | Angka | null |
| s | Angka | null |

 **Result:**
Transformasi


---


### setEulerAngles{#setEulerAngles}

| Nama | Deskripsi |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Mengatur sudut Euler dalam derajat dari transformasi saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| r | Angka | null |
| r | Angka | null |
| r | Angka | null |

 **Result:**
Transformasi


---


### setRotation{#setRotation}

| Nama | Deskripsi |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Mengatur rotasi (sebagai komponen kuaternion) dari transformasi saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| r | Angka | null |
| r | Angka | null |
| r | Angka | null |
| r | Angka | null |

 **Result:**
Transformasi


---


### setPreRotation{#setPreRotation}

| Nama | Deskripsi |
| --- | --- |
| setPreRotation(rx, ry, rz) | Mengatur pra-rotasi yang direpresentasikan dalam derajat |

 **Result:**
Transformasi


---


### setPostRotation{#setPostRotation}

| Nama | Deskripsi |
| --- | --- |
| setPostRotation(rx, ry, rz) | Mengatur pasca-rotasi yang direpresentasikan dalam derajat |

 **Result:**
Transformasi


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



