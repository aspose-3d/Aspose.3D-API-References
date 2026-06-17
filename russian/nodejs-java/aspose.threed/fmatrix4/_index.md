---
title: "FMatrix4"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Матрица 4x4, все компоненты в типе float


## Свойства

| Имя | Описание |
| --- | --- |
| m00 | Элемент m00. |
| m01 | Элемент m01. |
| m02 | Элемент m02. |
| m03 | Элемент m03. |
| m10 | Элемент m10. |
| m11 | Элемент m11. |
| m12 | Эта m12. |
| m13 | Эта m13. |
| m20 | Эта m20. |
| m21 | Эта m21. |
| m22 | Эта m22. |
| m23 | Эта m23. |
| m30 | Эта m30. |
| m31 | Эта m31. |
| m32 | Эта m32. |
| m33 | Эта m33. |
| IDENTITY | Эта единичная матрица |

## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Инициализировать экземпляр FMatrix4 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| m0 | Number | null |
| m0 | Number | null |
| m0 | Number | null |
| m0 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m3 | Number | null |
| m3 | Number | null |
| m3 | Number | null |
| m3 | Number | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(mat) | Инициализировать экземпляр FMatrix4 из экземпляра Matrix4. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Имя | Описание |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Создаёт матрицу из 4 строк. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Имя | Описание |
| --- | --- |
| concatenate(m2) | Объединяет две матрицы |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Имя | Описание |
| --- | --- |
| concatenate(m2) | Объединяет две матрицы |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Имя | Описание |
| --- | --- |
| transpose() | Транспонирует этот экземпляр. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Имя | Описание |
| --- | --- |
| inverse() | Вычисляет обратную матрицу текущего экземпляра. |

 **Result:**
FMatrix4


---



