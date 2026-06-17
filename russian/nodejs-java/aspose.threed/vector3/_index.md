---
title: "Vector3"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Вектор с тремя компонентами.


## Свойства

| Имя | Описание |
| --- | --- |
| x | Компонент x. |
| y | Компонент y. |
| z | Компонент z. |
| ORIGIN | Получает позицию начала. Начало. |
| UNIT_SCALE | Получает вектор единичного масштаба. |
| X_AXIS | Получает ось X. Ось X. |
| Y_AXIS | Получает ось Y. Ось Y. |
| Z_AXIS | Получает ось Z. Ось Z. |

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
| constructor_overload(x, y, z) | Инициализирует новый экземпляр структуры Vector3. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| x | Number | Координата x. |
| y | Number | Координата y. |
| z | Number | Координата z. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(vec) | Инициализирует новый экземпляр структуры Vector3. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| vec | FVector3 | Координата x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Имя | Описание |
| --- | --- |
| constructor_overload3(v) | Инициализирует новый экземпляр структуры Vector3. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| v | Number | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Имя | Описание |
| --- | --- |
| constructor_overload4(vec4) | Инициализирует новый экземпляр структуры Vector3. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Имя | Описание |
| --- | --- |
| getLength2() | Получает квадрат длины. Длина2. |

 **Result:**



---


### getLength{#getLength}

| Имя | Описание |
| --- | --- |
| getLength() | Получает длину этого вектора. Длина. |

 **Result:**



---


### equals{#equals}

| Имя | Описание |
| --- | --- |
| equals(obj) | Проверьте, равны ли два vector3 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| obj | Object | Объект для проверки равенства. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Имя | Описание |
| --- | --- |
| hashCode() | Получает хеш-код Vector3 |

 **Result:**
Number


---


### dot{#dot}

| Имя | Описание |
| --- | --- |
| dot(rhs) | Получает скалярное произведение двух векторов |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rhs | Vector3 | Значение правой части. |

 **Result:**
Number


---


### normalize{#normalize}

| Имя | Описание |
| --- | --- |
| normalize() | Нормализует этот экземпляр. |

 **Result:**
Vector3


---


### sin{#sin}

| Имя | Описание |
| --- | --- |
| sin() | Вычисляет синус для каждого компонента |

 **Result:**
Vector3


---


### cos{#cos}

| Имя | Описание |
| --- | --- |
| cos() | Вычисляет косинус для каждого компонента |

 **Result:**
Vector3


---


### cross{#cross}

| Имя | Описание |
| --- | --- |
| cross(rhs) | Векторное произведение двух векторов |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rhs | Vector3 | Значение правой части. |

 **Result:**
Vector3


---


### set{#set}

| Имя | Описание |
| --- | --- |
| set(newX, newY, newZ) | Устанавливает компоненты x/y/z одним вызовом. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| newX | Number | Компонент x. |
| newY | Number | Компонент y. |
| newZ | Number | Компонент z. |

 **Result:**
Vector3


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Возвращает java.lang.String, представляющий текущий Vector3. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| Имя | Описание |
| --- | --- |
| angleBetween(dir, up) | Вычисляет внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| dir | Vector3 | Вектор направления для сравнения. |
| up | Vector3 | Вектор вверх общей плоскости двух направлений. |

 **Result:**
Number


---


### angleBetween{#angleBetween}

| Имя | Описание |
| --- | --- |
| angleBetween(dir) | Вычисляет внутренний угол между двумя направлениями. Два направления могут быть ненормализованными векторами. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| dir | Vector3 | Вектор направления для сравнения. |

 **Result:**
Number


---


### compareTo{#compareTo}

| Имя | Описание |
| --- | --- |
| compareTo(other) | Сравнивает текущий вектор с другим экземпляром. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Number


---



