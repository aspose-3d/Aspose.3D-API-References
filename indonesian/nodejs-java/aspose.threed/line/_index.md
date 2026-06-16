---
title: "Line"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/line/
---
## Line class

Polyline adalah jalur yang didefinisikan oleh sekumpulan titik dengan Geometry.ControlPoints, dan terhubung oleh Segments, yang berarti juga dapat berupa sekumpulan segmen garis yang terhubung. Garis biasanya merupakan objek linear, yang berarti tidak dapat digunakan untuk merepresentasikan kurva; untuk merepresentasikan kurva, gunakan NurbsCurve.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi sebuah instance baru dari kelas Line. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name) | Menginisialisasi sebuah instance baru dari kelas Line. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nama | Deskripsi |
| --- | --- |
| getControlPoints() | Mendapatkan semua titik kontrol |

 **Result:**



---


### getVisible{#getVisible}

| Nama | Deskripsi |
| --- | --- |
| getVisible() | Mendapatkan atau mengatur apakah geometri terlihat |

 **Result:**



---


### setVisible{#setVisible}

| Nama | Deskripsi |
| --- | --- |
| setVisible(value) | Mendapatkan atau mengatur apakah geometri terlihat |

 **Result:**



---


### getSegments{#getSegments}

| Nama | Deskripsi |
| --- | --- |
| getSegments() | Mendapatkan segmen-segmen garis |

 **Result:**



---


### getColor{#getColor}

| Nama | Deskripsi |
| --- | --- |
| getColor() | Mendapatkan atau mengatur warna garis, nilai default adalah putih(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Nama | Deskripsi |
| --- | --- |
| setColor(value) | Mendapatkan atau mengatur warna garis, nilai default adalah putih(1, 1, 1) |

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


### fromPoints{#fromPoints}

| Nama | Deskripsi |
| --- | --- |
| fromPoints(points) | Membuat instance Line dari sekumpulan titik. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| point | Vector3[] | null |

 **Result:**
Line


---


### makeDefaultIndices{#makeDefaultIndices}

| Nama | Deskripsi |
| --- | --- |
| makeDefaultIndices() | Hasilkan urutan 0,1,2,3....Geometry.ControlPoints.Length-1 ke Segments sehingga ControlPoints dapat digunakan sebagai satu baris |

 **Result:**
Line


---


### getEntityRendererKey{#getEntityRendererKey}

| Nama | Deskripsi |
| --- | --- |
| getEntityRendererKey() | Mendapatkan kunci renderer entitas yang terdaftar di renderer |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

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



