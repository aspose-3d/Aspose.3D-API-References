---
title: "EndPoint"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/endpoint/
---
## EndPoint class

Конечная точка для обрезки кривой, может быть значением параметра или декартовой точкой.


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
| constructor_overload(point) | Создаёт объект EndPoint из декартовой точки. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| точка | Vector3 | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(v) | Создаёт объект EndPoint из реального параметра. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### isCartesianPoint{#isCartesianPoint}

| Имя | Описание |
| --- | --- |
| isCartesianPoint() | Является ли конечная точка декартовой точкой? |

 **Result:**



---


### getAsPoint{#getAsPoint}

| Имя | Описание |
| --- | --- |
| getAsPoint() | Получает конечную точку как декартову точку или бросает исключение. |

 **Result:**



---


### getAsValue{#getAsValue}

| Имя | Описание |
| --- | --- |
| getAsValue() | Получает конечную точку как реальный параметр или бросает исключение. |

 **Result:**



---


### fromDegree{#fromDegree}

| Имя | Описание |
| --- | --- |
| fromDegree(degree) | Создаёт конечную точку, измеренную в градусах. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| град | Number | null |

 **Result:**
EndPoint


---


### fromRadian{#fromRadian}

| Имя | Описание |
| --- | --- |
| fromRadian(degree) | Создаёт конечную точку, измеренную в радианах. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| град | Number | null |

 **Result:**
EndPoint


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Возвращает строковое представление текущей конечной точки. |

 **Result:**
String


---



