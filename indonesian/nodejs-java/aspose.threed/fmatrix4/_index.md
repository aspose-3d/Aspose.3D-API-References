---
title: "FMatrix4"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Matrix 4x4 dengan semua komponen bertipe float


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
| IDENTITY | Matriks identitas |

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
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Inisialisasi instance FMatrix4 |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| m0 | Angka | null |
| m0 | Angka | null |
| m0 | Angka | null |
| m0 | Angka | null |
| m1 | Angka | null |
| m1 | Angka | null |
| m1 | Angka | null |
| m1 | Angka | null |
| m2 | Angka | null |
| m2 | Angka | null |
| m2 | Angka | null |
| m2 | Angka | null |
| m3 | Angka | null |
| m3 | Angka | null |
| m3 | Angka | null |
| m3 | Angka | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(mat) | Inisialisasi instance FMatrix4 dari instance Matrix4. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Membuat matriks dari 4 baris. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Nama | Deskripsi |
| --- | --- |
| concatenate(m2) | Menggabungkan dua matriks |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


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
FMatrix4


---


### transpose{#transpose}

| Nama | Deskripsi |
| --- | --- |
| transpose() | Mentransposisi instance ini. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Nama | Deskripsi |
| --- | --- |
| inverse() | Hitung matriks invers dari instance saat ini. |

 **Result:**
FMatrix4


---



