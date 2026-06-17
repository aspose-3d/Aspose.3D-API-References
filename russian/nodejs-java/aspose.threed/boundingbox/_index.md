---
title: "BoundingBox"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

Осиально-выравненный ограничивающий параллелепипед


## Свойства

| Имя | Описание |
| --- | --- |
| NULL | Нулевой ограничивающий прямоугольник |
| INFINITE | Бесконечный ограничивающий прямоугольник |

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
| constructor_overload(minimum, maximum) | Инициализирует конечный ограничивающий прямоугольник с заданными минимальным и максимальным углом |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| minimum | Vector3 | Минимальный угол |
| maximum | Vector3 | Максимальный угол |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Инициализирует конечный ограничивающий прямоугольник с заданными минимальным и максимальным углом |

 **Result:**



---


### getExtent{#getExtent}

| Имя | Описание |
| --- | --- |
| getExtent() | Получает размер ограничивающего прямоугольника. Значение свойства — целая константа BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Имя | Описание |
| --- | --- |
| getMinimum() | Минимальный угол ограничивающего прямоугольника |

 **Result:**



---


### getMaximum{#getMaximum}

| Имя | Описание |
| --- | --- |
| getMaximum() | Максимальный угол ограничивающего прямоугольника |

 **Result:**



---


### getSize{#getSize}

| Имя | Описание |
| --- | --- |
| getSize() | Размер ограничивающего прямоугольника |

 **Result:**



---


### getCenter{#getCenter}

| Имя | Описание |
| --- | --- |
| getCenter() | Центр ограничивающего прямоугольника. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Имя | Описание |
| --- | --- |
| fromGeometry(geometry) | Создать ограничивающий прямоугольник из заданной геометрии |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| geometr | Геометрия | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Получает строковое представление ограничивающего прямоугольника. |

 **Result:**
String


---


### hashCode{#hashCode}

| Имя | Описание |
| --- | --- |
| hashCode() | Возвращает хеш-код для этого экземпляра |

 **Result:**
Number


---


### equals{#equals}

| Имя | Описание |
| --- | --- |
| equals(obj) | Определяет, равны ли два объекта |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



