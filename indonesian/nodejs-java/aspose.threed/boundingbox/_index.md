---
title: "BoundingBox"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

Kotak pembatas yang sejajar sumbu


## Properti

| Nama | Deskripsi |
| --- | --- |
| NULL | Bounding box null |
| INFINITE | Bounding box tak terbatas |

## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(minimum, maximum) | Inisialisasi bounding box terbatas dengan sudut minimum dan maksimum yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| minimum | Vector3 | Sudut minimum |
| maximum | Vector3 | Sudut maksimum |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Inisialisasi bounding box terbatas dengan sudut minimum dan maksimum yang diberikan |

 **Result:**



---


### getExtent{#getExtent}

| Nama | Deskripsi |
| --- | --- |
| getExtent() | Mengambil ukuran bounding box. Nilai properti ini adalah konstanta integer BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Nama | Deskripsi |
| --- | --- |
| getMinimum() | Sudut minimum dari bounding box |

 **Result:**



---


### getMaximum{#getMaximum}

| Nama | Deskripsi |
| --- | --- |
| getMaximum() | Sudut maksimum dari bounding box |

 **Result:**



---


### getSize{#getSize}

| Nama | Deskripsi |
| --- | --- |
| getSize() | Ukuran kotak pembatas |

 **Result:**



---


### getCenter{#getCenter}

| Nama | Deskripsi |
| --- | --- |
| getCenter() | Pusat kotak pembatas. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Nama | Deskripsi |
| --- | --- |
| fromGeometry(geometry) | Bangun kotak pembatas dari geometri yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| geometr | Geometri | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mendapatkan representasi string dari kotak pembatas. |

 **Result:**
String


---


### hashCode{#hashCode}

| Nama | Deskripsi |
| --- | --- |
| hashCode() | Mengembalikan kode hash untuk instance ini |

 **Result:**
Angka


---


### equals{#equals}

| Nama | Deskripsi |
| --- | --- |
| equals(obj) | Menentukan apakah dua objek sama |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



