---
title: "BoundingBox2D"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Kotak pembatas yang sejajar sumbu untuk Vector2


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
| minimum | Vector2 | Sudut minimum |
| maximum | Vector2 | Sudut maksimum |

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


### merge{#merge}

| Nama | Deskripsi |
| --- | --- |
| merge(pt) | Menggabungkan kotak baru ke dalam bounding box saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Nama | Deskripsi |
| --- | --- |
| merge(bb) | Menggabungkan kotak baru ke dalam bounding box saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mendapatkan representasi string dari kotak pembatas. |

 **Result:**
String


---



