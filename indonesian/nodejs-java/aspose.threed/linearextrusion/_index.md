---
title: "LinearExtrusion"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

Ekstrusi linear mengambil bentuk 2D sebagai input dan memperluas bentuk tersebut ke dimensi ketiga.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Konstruktor dari instance LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(shape, height) | Konstruktor dari instance LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Nama | Deskripsi |
| --- | --- |
| getShape() | Bentuk dasar yang akan diekstrusi. |

 **Result:**



---


### setShape{#setShape}

| Nama | Deskripsi |
| --- | --- |
| setShape(value) | Bentuk dasar yang akan diekstrusi. |

 **Result:**



---


### getDirection{#getDirection}

| Nama | Deskripsi |
| --- | --- |
| getDirection() | Arah ekstrusi, nilai default adalah (0, 0, 1) |

 **Result:**



---


### setDirection{#setDirection}

| Nama | Deskripsi |
| --- | --- |
| setDirection(value) | Arah ekstrusi, nilai default adalah (0, 0, 1) |

 **Result:**



---


### getHeight{#getHeight}

| Nama | Deskripsi |
| --- | --- |
| getHeight() | Tinggi geometri yang diekstrusi, nilai default adalah 1.0 |

 **Result:**



---


### setHeight{#setHeight}

| Nama | Deskripsi |
| --- | --- |
| setHeight(value) | Tinggi geometri yang diekstrusi, nilai default adalah 1.0 |

 **Result:**



---


### getSlices{#getSlices}

| Nama | Deskripsi |
| --- | --- |
| getSlices() | Irisan dari geometri ekstrusi berputar, nilai default adalah 1. |

 **Result:**



---


### setSlices{#setSlices}

| Nama | Deskripsi |
| --- | --- |
| setSlices(value) | Irisan dari geometri ekstrusi berputar, nilai default adalah 1. |

 **Result:**



---


### getCenter{#getCenter}

| Nama | Deskripsi |
| --- | --- |
| getCenter() | Jika nilai ini false, rentang Z ekstrusi linear adalah dari 0 hingga tinggi, jika tidak rentang adalah dari -tinggi/2 hingga tinggi/2. |

 **Result:**



---


### setCenter{#setCenter}

| Nama | Deskripsi |
| --- | --- |
| setCenter(value) | Jika nilai ini false, rentang Z ekstrusi linear adalah dari 0 hingga tinggi, jika tidak rentang adalah dari -tinggi/2 hingga tinggi/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Nama | Deskripsi |
| --- | --- |
| getTwistOffset() | Offset yang digunakan dalam pemutaran, nilai default adalah (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Nama | Deskripsi |
| --- | --- |
| setTwistOffset(value) | Offset yang digunakan dalam pemutaran, nilai default adalah (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Nama | Deskripsi |
| --- | --- |
| getTwist() | Jumlah derajat yang dilalui oleh bentuk selama ekstrusi. |

 **Result:**



---


### setTwist{#setTwist}

| Nama | Deskripsi |
| --- | --- |
| setTwist(value) | Jumlah derajat yang dilalui oleh bentuk selama ekstrusi. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nama | Deskripsi |
| --- | --- |
| getParentNodes() | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansiasi geometri. Node-node tersebut. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nama | Deskripsi |
| --- | --- |
| getExcluded() | Mendapatkan atau mengatur apakah entitas ini harus dikecualikan selama ekspor. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nama | Deskripsi |
| --- | --- |
| setExcluded(value) | Mendapatkan atau mengatur apakah entitas ini harus dikecualikan selama ekspor. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nama | Deskripsi |
| --- | --- |
| getParentNode() | Mendapatkan atau mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. Node induk. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nama | Deskripsi |
| --- | --- |
| setParentNode(value) | Mendapatkan atau mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. Node induk. |

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


### toMesh{#toMesh}

| Nama | Deskripsi |
| --- | --- |
| toMesh() | Konversi ekstrusi menjadi mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Nama | Deskripsi |
| --- | --- |
| getEntityRendererKey() | Mendapatkan kunci renderer entitas yang terdaftar di renderer |

 **Result:**
EntityRendererKey


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



