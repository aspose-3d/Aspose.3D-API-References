---
title: "Matrix4"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

Implementasi matriks 4x4.


## Properti

| Nama | Deskripsi |
| --- | --- |
| m00 | m00. |
| m01 | m01. |
| m02 | m02. |
| m03 | m03. |
| m10 | m10. |
| m11 | m11. |
| m12 | m12. |
| m13 | m13. |
| m20 | m20. |
| m21 | m21. |
| m22 | m22. |
| m23 | m23. |
| m30 | m30. |
| m31 | m31. |
| m32 | m32. |
| m33 | m33. |

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
| constructor_overload(r0, r1, r2, r3) | Membuat matriks dari 4 baris. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Menginisialisasi sebuah instance baru dari struct Matrix4. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| m00 | Angka | M00. |
| m01 | Angka | M01. |
| m02 | Angka | M02. |
| m03 | Angka | M03. |
| m10 | Angka | M10. |
| m11 | Angka | M11. |
| m12 | Angka | M12. |
| m13 | Angka | M13. |
| m20 | Angka | M20. |
| m21 | Angka | M21. |
| m22 | Angka | M22. |
| m23 | Angka | M23. |
| m30 | Angka | M30. |
| m31 | Angka | M31. |
| m32 | Angka | M32. |
| m33 | Angka | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload3(m) | Membuat Matrix4 dari sebuah instance FMatrix4 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload4(m) | Menginisialisasi sebuah instance baru dari struct Matrix4. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Nama | Deskripsi |
| --- | --- |
| getIdentity() | Mendapatkan matriks identitas. Identitas. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Nama | Deskripsi |
| --- | --- |
| getDeterminant() | Mendapatkan determinan matriks. Determinan. |

 **Result:**



---


### concatenate{#concatenate}

| Nama | Deskripsi |
| --- | --- |
| concatenate(m2) | Menggabungkan dua matriks |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| Nama | Deskripsi |
| --- | --- |
| transpose() | Mentransposisi instance ini. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Nama | Deskripsi |
| --- | --- |
| normalize() | Menormalkan instance ini. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Nama | Deskripsi |
| --- | --- |
| inverse() | Membalikkan instance ini. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Nama | Deskripsi |
| --- | --- |
| setTRS(translation, rotation, scale) | Menginisialisasi matriks dengan translasi/rotasi/skala |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| translasi | Vector3 | Translasi. |
| rotasi | Vector3 | Sudut Euler untuk rotasi, bidang berada dalam derajat. |
| skala | Vector3 | Skala. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Nama | Deskripsi |
| --- | --- |
| toArray() | Mengonversi matriks ke array. |

 **Result:**
Number[]


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mengembalikan java.lang.String yang mewakili Matrix4 saat ini. |

 **Result:**
String


---


### translate{#translate}

| Nama | Deskripsi |
| --- | --- |
| translate(t) | Membuat matriks yang mentranslasi sepanjang sumbu x, sumbu y, dan sumbu z |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| t | Vector3 | Offset translasi |

 **Result:**
Matrix4


---


### translate{#translate}

| Nama | Deskripsi |
| --- | --- |
| translate(tx, ty, tz) | Membuat matriks yang mentranslasi sepanjang sumbu x, sumbu y, dan sumbu z |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| tx | Angka | Offset koordinat X |
| ty | Angka | Offset koordinat Y |
| tz | Angka | Offset koordinat Z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(s) | Membuat matriks yang memperbesar sepanjang sumbu x, sumbu y, dan sumbu z. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| s | Vector3 | Fabrik skala berlaku pada sumbu x, sumbu y, dan sumbu z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(s) | Membuat matriks yang memperbesar sepanjang sumbu x, sumbu y, dan sumbu z. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| s | Angka | Fabrik skala berlaku pada semua sumbu |

 **Result:**
Matrix4


---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(sx, sy, sz) | Membuat matriks yang memperbesar sepanjang sumbu x, sumbu y, dan sumbu z. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| sx | Angka | Fabrik skala berlaku pada sumbu x |
| sy | Angka | Fabrik skala berlaku pada sumbu y |
| sz | Angka | Fabrik skala berlaku pada sumbu z |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nama | Deskripsi |
| --- | --- |
| rotateFromEuler(eul) | Buat matriks rotasi dari sudut Euler |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| eul | Vector3 | Rotasi dalam radian |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nama | Deskripsi |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Buat matriks rotasi dari sudut Euler |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rx | Angka | Rotasi pada sumbu x dalam radian |
| ry | Angka | Rotasi pada sumbu y dalam radian |
| rz | Angka | Rotasi pada sumbu z dalam radian |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nama | Deskripsi |
| --- | --- |
| rotate(angle, axis) | Buat matriks rotasi dengan sudut rotasi dan sumbu |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | Angka | Sudut rotasi dalam radian |
| sumbu | Vector3 | Sumbu rotasi |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nama | Deskripsi |
| --- | --- |
| rotate(q) | Buat matriks rotasi dari quaternion |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| q | Quaternion | Quaternion rotasi |

 **Result:**
Matrix4


---



