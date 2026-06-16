---
title: "TransformBuilder"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilder digunakan untuk membangun matriks transformasi melalui rangkaian transformasi.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(initial, order) | Membuat TransformBuilder dengan matriks transformasi awal dan urutan komposisi yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| initia | Matrix4 | null |
| urutan | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(order) | Membuat TransformBuilder dengan matriks transformasi identitas awal dan urutan komposisi yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| urutan | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Nama | Deskripsi |
| --- | --- |
| getMatrix() | Mendapatkan atau mengatur nilai matriks saat ini. |

 **Result:**



---


### setMatrix{#setMatrix}

| Nama | Deskripsi |
| --- | --- |
| setMatrix(value) | Mendapatkan atau mengatur nilai matriks saat ini. |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Nama | Deskripsi |
| --- | --- |
| getComposeOrder() | Mendapatkan atau mengatur urutan komposisi rantai. Nilai properti ini adalah konstanta integer ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Nama | Deskripsi |
| --- | --- |
| setComposeOrder(value) | Mendapatkan atau mengatur urutan komposisi rantai. Nilai properti ini adalah konstanta integer ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Nama | Deskripsi |
| --- | --- |
| compose(m) | Tambahkan atau sisipkan argumen ke matriks internal. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Nama | Deskripsi |
| --- | --- |
| append(m) | Tambahkan matriks transformasi baru ke rantai transformasi. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Nama | Deskripsi |
| --- | --- |
| prepend(m) | Tambahkan matriks transformasi baru ke rantai transformasi. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Nama | Deskripsi |
| --- | --- |
| rearrange(newX, newY, newZ) | Atur ulang tata letak sumbu. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| newX | Sumbu | Sumbu |
| newY | Sumbu | Sumbu |
| newZ | Sumbu | Sumbu |

 **Result:**



---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(s) | Rantai matriks transformasi skala dengan komponen yang diskalakan oleh s |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Angka | null |

 **Result:**



---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(x, y, z) | Rantai matriks transformasi skala |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Angka | null |
|  | Angka | null |
|  | Angka | null |

 **Result:**



---


### scale{#scale}

| Nama | Deskripsi |
| --- | --- |
| scale(s) | Rantai transformasi skala |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nama | Deskripsi |
| --- | --- |
| rotateDegree(angle, axis) | Rantai transformasi rotasi dalam derajat |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | Angka | Sudut untuk memutar dalam derajat |
| sumbu | Vector3 | Sumbu untuk memutar |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nama | Deskripsi |
| --- | --- |
| rotateRadian(angle, axis) | Rantai transformasi rotasi dalam radian |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | Angka | Sudut untuk memutar dalam radian |
| sumbu | Vector3 | Sumbu untuk memutar |

 **Result:**



---


### rotate{#rotate}

| Nama | Deskripsi |
| --- | --- |
| rotate(q) | Rantai rotasi dengan quaternion |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Quaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Nama | Deskripsi |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Rantai rotasi dengan sudut Euler dalam derajat |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| deg | Angka | null |
| deg | Angka | null |
| deg | Angka | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nama | Deskripsi |
| --- | --- |
| rotateEulerRadian(x, y, z) | Rantai rotasi dengan sudut Euler dalam radian |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Angka | null |
|  | Angka | null |
|  | Angka | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nama | Deskripsi |
| --- | --- |
| rotateEulerRadian(r) | Rantai rotasi dengan sudut Euler dalam radian |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Nama | Deskripsi |
| --- | --- |
| translate(tx, ty, tz) | Rantai transformasi translasi |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| t | Angka | null |
| t | Angka | null |
| t | Angka | null |

 **Result:**



---


### translate{#translate}

| Nama | Deskripsi |
| --- | --- |
| translate(v) | Rantai transformasi translasi |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Nama | Deskripsi |
| --- | --- |
| reset() | Setel ulang transformasi ke matriks identitas |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nama | Deskripsi |
| --- | --- |
| rotateDegree(rot, order) | Tambahkan rotasi dengan urutan yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rot | Vector3 | Rotasi dalam derajat |
| urutan | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nama | Deskripsi |
| --- | --- |
| rotateRadian(rot, order) | Tambahkan rotasi dengan urutan yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rot | Vector3 | Rotasi dalam radian |
| urutan | RotationOrder | RotationOrder |

 **Result:**



---



