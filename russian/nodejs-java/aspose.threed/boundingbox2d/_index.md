---
title: "BoundingBox2D"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Осиально-выравненный ограничивающий параллелепипед для Vector2


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
| minimum | Vector2 | Минимальный угол |
| maximum | Vector2 | Максимальный угол |

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


### merge{#merge}

| Имя | Описание |
| --- | --- |
| merge(pt) | Объединяет новую коробку с текущим ограничивающим прямоугольником. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Имя | Описание |
| --- | --- |
| merge(bb) | Объединяет новую коробку с текущим ограничивающим прямоугольником. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Получает строковое представление ограничивающего прямоугольника. |

 **Result:**
String


---



