---
title: "Quaternion"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion biasanya digunakan untuk melakukan rotasi dalam grafika komputer.


## Properti

| Nama | Deskripsi |
| --- | --- |
| w | Komponen w. |
| x | Komponen x. |
| y | Komponen y. |
| z | Komponen z. |
| IDENTITY | Quaternion Identitas. |

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
| constructor_overload(w, x, y, z) | Menginisialisasi sebuah instance baru dari kelas Quaternion. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| w | Angka | komponen w dari quaternion |
| x | Angka | komponen x dari quaternion |
| y | Angka | komponen y dari quaternion |
| z | Angka | komponen z dari quaternion |

 **Result:**



---


### getLength{#getLength}

| Nama | Deskripsi |
| --- | --- |
| getLength() | Mendapatkan panjang quaternion |

 **Result:**



---


### equals{#equals}

| Nama | Deskripsi |
| --- | --- |
| equals(obj) | Periksa apakah dua quaternion sama |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| obj | Object | Objek untuk memeriksa kesamaan. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Nama | Deskripsi |
| --- | --- |
| hashCode() | Mendapatkan kode hash dari Quaternion |

 **Result:**
Angka


---


### conjugate{#conjugate}

| Nama | Deskripsi |
| --- | --- |
| conjugate() | Mengembalikan quaternion konjugat dari quaternion saat ini |

 **Result:**
Quaternion


---


### inverse{#inverse}

| Nama | Deskripsi |
| --- | --- |
| inverse() | Mengembalikan quaternion invers dari quaternion saat ini |

 **Result:**
Quaternion


---


### dot{#dot}

| Nama | Deskripsi |
| --- | --- |
| dot(q) | Produk dot |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| q | Quaternion | Quaternion |

 **Result:**
Angka


---


### eulerAngles{#eulerAngles}

| Nama | Deskripsi |
| --- | --- |
| eulerAngles() | Mengonversi quaternion menjadi rotasi yang direpresentasikan oleh sudut Euler Semua komponen dalam radian |

 **Result:**
Vector3


---


### normalize{#normalize}

| Nama | Deskripsi |
| --- | --- |
| normalize() | Normalisasi quaternion |

 **Result:**
Quaternion


---


### concat{#concat}

| Nama | Deskripsi |
| --- | --- |
| concat(rhs) | Menggabungkan dua quaternion |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rh | Quaternion | null |

 **Result:**
Quaternion


---


### fromAngleAxis{#fromAngleAxis}

| Nama | Deskripsi |
| --- | --- |
| fromAngleAxis(a, axis) | Membuat quaternion di sekitar sumbu yang diberikan dan memutar searah jarum jam |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| a | Angka | Rotasi searah jarum jam dalam radian |
| sumbu | Vector3 | Sumbu |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Nama | Deskripsi |
| --- | --- |
| fromRotation(orig, dest) | Membuat quaternion yang berputar dari arah asli ke arah tujuan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| orig | Vector3 | Arah asli |
| dest | Vector3 | Arah tujuan |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Nama | Deskripsi |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Membuat quaternion dari sudut Euler yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| pitch | Angka | Pitch dalam radian |
| yaw | Angka | Yaw dalam radian |
| gulung | Angka | Gulung dalam radian |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Nama | Deskripsi |
| --- | --- |
| fromEulerAngle(eulerAngle) | Membuat quaternion dari sudut Euler yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| eulerAngle | Vector3 | Sudut Euler dalam radian |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Nama | Deskripsi |
| --- | --- |
| toMatrix() | Konversi rotasi yang disajikan oleh quaternion menjadi matriks transformasi. |

 **Result:**
Matrix4


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mendapatkan representasi quaternion dalam string |

 **Result:**
String


---


### interpolate{#interpolate}

| Nama | Deskripsi |
| --- | --- |
| interpolate(t, from, to) | Mengisi quaternion ini dengan nilai interpolasi antara argumen quaternion yang diberikan untuk t antara from dan to. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| t | Angka | Koefisien untuk interpolasi. |
| from | Quaternion | Quaternion sumber. |
| to | Quaternion | Quaternion target. |

 **Result:**
Quaternion


---



