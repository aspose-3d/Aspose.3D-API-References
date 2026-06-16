---
title: "PushConstant"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Utilitas untuk menyediakan data ke shader melalui push constant.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Konstruktor dari PushConstant |

 **Result:**



---


### write{#write}

| Nama | Deskripsi |
| --- | --- |
| write(mat) | Tulis matriks ke konstanta |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| mat | FMatrix4 | Matriks yang akan ditulis |

 **Result:**



---


### write{#write}

| Nama | Deskripsi |
| --- | --- |
| write(n) | Tulis nilai int ke konstanta |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Angka | null |

 **Result:**



---


### write{#write}

| Nama | Deskripsi |
| --- | --- |
| write(f) | Tulis nilai float ke konstanta |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Angka | null |

 **Result:**



---


### write{#write}

| Nama | Deskripsi |
| --- | --- |
| write(vec) | Tulis vektor 4-komponen ke konstanta |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Nama | Deskripsi |
| --- | --- |
| write(vec) | Tulis vektor 3-komponen ke konstanta |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Nama | Deskripsi |
| --- | --- |
| write(x, y, z, w) | Tulis vektor 4-komponen ke konstanta |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
|  | Angka | null |
|  | Angka | null |
|  | Angka | null |
|  | Angka | null |

 **Result:**



---


### commit{#commit}

| Nama | Deskripsi |
| --- | --- |
| commit(stage, commandList) | Komit data yang dipersiapkan ke pipeline grafis. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| stage | Angka | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



