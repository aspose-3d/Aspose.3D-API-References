---
title: "Matrix4"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

Реализация 4x4 матрицы.


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
| constructor_overload(r0, r1, r2, r3) | Создаёт матрицу из 4 строк. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Инициализирует новый экземпляр структуры Matrix4. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| m00 | Number | M00. |
| m01 | Number | M01. |
| m02 | Number | M02. |
| m03 | Number | M03. |
| m10 | Number | M10. |
| m11 | Number | M11. |
| m12 | Number | M12. |
| m13 | Number | M13. |
| m20 | Number | M20. |
| m21 | Number | M21. |
| m22 | Number | M22. |
| m23 | Number | M23. |
| m30 | Number | M30. |
| m31 | Number | M31. |
| m32 | Number | M32. |
| m33 | Number | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Имя | Описание |
| --- | --- |
| constructor_overload3(m) | Создает Matrix4 из экземпляра FMatrix4 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Имя | Описание |
| --- | --- |
| constructor_overload4(m) | Инициализирует новый экземпляр структуры Matrix4. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Имя | Описание |
| --- | --- |
| getIdentity() | Получает единичную матрицу. Единичная матрица. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Имя | Описание |
| --- | --- |
| getDeterminant() | Получает определитель матрицы. Определитель. |

 **Result:**



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
Matrix4


---


### transpose{#transpose}

| Имя | Описание |
| --- | --- |
| transpose() | Транспонирует этот экземпляр. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Имя | Описание |
| --- | --- |
| normalize() | Нормализует этот экземпляр. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Имя | Описание |
| --- | --- |
| inverse() | Инвертирует этот экземпляр. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Имя | Описание |
| --- | --- |
| setTRS(translation, rotation, scale) | Инициализирует матрицу с перемещением/вращением/масштабом |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| перемещение | Vector3 | Перемещение. |
| вращение | Vector3 | Углы Эйлера для вращения, поля указаны в градусах. |
| масштаб | Vector3 | Масштаб. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Имя | Описание |
| --- | --- |
| toArray() | Преобразует матрицу в массив. |

 **Result:**
Number[]


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Возвращает java.lang.String, представляющий текущий Matrix4. |

 **Result:**
String


---


### translate{#translate}

| Имя | Описание |
| --- | --- |
| translate(t) | Создаёт матрицу, которая перемещает вдоль оси x, оси y и оси z. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| t | Vector3 | Смещение трансляции |

 **Result:**
Matrix4


---


### translate{#translate}

| Имя | Описание |
| --- | --- |
| translate(tx, ty, tz) | Создаёт матрицу, которая перемещает вдоль оси x, оси y и оси z. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| tx | Number | Смещение X-координаты |
| ty | Number | Смещение координаты Y |
| tz | Number | Смещение координаты Z |

 **Result:**
Matrix4


---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(s) | Создаёт матрицу, масштабирующую вдоль оси x, оси y и оси z. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| s | Vector3 | Фабрики масштабирования применяются к оси x, оси y и оси z |

 **Result:**
Matrix4


---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(s) | Создаёт матрицу, масштабирующую вдоль оси x, оси y и оси z. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| s | Number | Фабрики масштабирования применяются ко всем осям |

 **Result:**
Matrix4


---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(sx, sy, sz) | Создаёт матрицу, масштабирующую вдоль оси x, оси y и оси z. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| sx | Number | Фабрики масштабирования применяются к оси x |
| sy | Number | Фабрики масштабирования применяются к оси y |
| sz | Number | Фабрики масштабирования применяются к оси z |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Имя | Описание |
| --- | --- |
| rotateFromEuler(eul) | Создать матрицу вращения из угла Эйлера |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| eul | Vector3 | Вращение в радианах |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Имя | Описание |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Создать матрицу вращения из угла Эйлера |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rx | Number | Вращение вокруг оси x в радианах |
| ry | Number | Вращение вокруг оси y в радианах |
| rz | Number | Вращение вокруг оси z в радианах |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Имя | Описание |
| --- | --- |
| rotate(angle, axis) | Создать матрицу вращения по углу вращения и оси |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| angle | Number | Угол вращения в радианах |
| axis | Vector3 | Ось вращения |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Имя | Описание |
| --- | --- |
| rotate(q) | Создать матрицу вращения из кватерниона |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| q | Кватернион | Кватернион вращения |

 **Result:**
Matrix4


---



