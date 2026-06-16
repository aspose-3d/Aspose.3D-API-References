---
title: "Vector3"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Vektor dengan tiga komponen.


## Properti

| Nama | Deskripsi |
| --- | --- |
| x | Komponen x. |
| y | Komponen y. |
| z | Komponen z. |
| ORIGIN | Mendapatkan posisi asal. Asal. |
| UNIT_SCALE | Mendapatkan vektor skala unit. |
| X_AXIS | Mendapatkan sumbu X. Sumbu X. |
| Y_AXIS | Mendapatkan sumbu Y. Sumbu Y. |
| Z_AXIS | Mendapatkan sumbu Z. Sumbu Z. |

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
| constructor_overload(x, y, z) | Menginisialisasi instance baru dari struct Vector3. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| x | Angka | Koordinat x. |
| y | Angka | Koordinat y. |
| z | Angka | Koordinat z. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(vec) | Menginisialisasi instance baru dari struct Vector3. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| vec | FVector3 | Koordinat x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload3(v) | Menginisialisasi instance baru dari struct Vector3. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| v | Angka | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload4(vec4) | Menginisialisasi instance baru dari struct Vector3. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Nama | Deskripsi |
| --- | --- |
| getLength2() | Mendapatkan kuadrat dari panjang. length2. |

 **Result:**



---


### getLength{#getLength}

| Nama | Deskripsi |
| --- | --- |
| getLength() | Mendapatkan panjang vektor ini. Panjangnya. |

 **Result:**



---


### equals{#equals}

| Nama | Deskripsi |
| --- | --- |
| equals(obj) | Periksa apakah dua vector3 sama |

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
| hashCode() | Mendapatkan kode hash dari Vector3 |

 **Result:**
Angka


---


### dot{#dot}

| Nama | Deskripsi |
| --- | --- |
| dot(rhs) | Mendapatkan hasil perkalian titik dari dua vektor |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | Vector3 | Nilai sisi kanan. |

 **Result:**
Angka


---


### normalize{#normalize}

| Nama | Deskripsi |
| --- | --- |
| normalize() | Menormalkan instance ini. |

 **Result:**
Vector3


---


### sin{#sin}

| Nama | Deskripsi |
| --- | --- |
| sin() | Menghitung sinus pada setiap komponen |

 **Result:**
Vector3


---


### cos{#cos}

| Nama | Deskripsi |
| --- | --- |
| cos() | Menghitung kosinus pada setiap komponen |

 **Result:**
Vector3


---


### cross{#cross}

| Nama | Deskripsi |
| --- | --- |
| cross(rhs) | Produk silang dari dua vektor |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | Vector3 | Nilai sisi kanan. |

 **Result:**
Vector3


---


### set{#set}

| Nama | Deskripsi |
| --- | --- |
| set(newX, newY, newZ) | Mengatur komponen x/y/z dalam satu panggilan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| newX | Angka | Komponen x. |
| newY | Angka | Komponen y. |
| newZ | Angka | Komponen z. |

 **Result:**
Vector3


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mengembalikan java.lang.String yang mewakili Vector3 saat ini. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| Nama | Deskripsi |
| --- | --- |
| angleBetween(dir, up) | Hitung sudut dalam antara dua arah. Dua arah dapat berupa vektor yang tidak ternormalisasi. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| dir | Vector3 | Vektor arah untuk dibandingkan dengan |
| up | Vector3 | Vektor atas dari bidang bersama dua arah |

 **Result:**
Angka


---


### angleBetween{#angleBetween}

| Nama | Deskripsi |
| --- | --- |
| angleBetween(dir) | Hitung sudut dalam antara dua arah. Dua arah dapat berupa vektor yang tidak ternormalisasi. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| dir | Vector3 | Vektor arah untuk dibandingkan dengan |

 **Result:**
Angka


---


### compareTo{#compareTo}

| Nama | Deskripsi |
| --- | --- |
| compareTo(other) | Bandingkan vektor saat ini dengan instance lain. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Angka


---



