---
title: "RelativeRectangle"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Относительный прямоугольник  Формула между относительным компонентом и абсолютным значением выглядит так:  Scale  (Reference Width) + offset  Поэтому, если мы хотим представить абсолютное значение, оставьте все поля масштабирования нулевыми и вместо этого используйте поля смещения.


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
| constructor_overload(left, top, width, height) | Создать RelativeRectangle |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| лев | Number | null |
| to | Number | null |
| widt | Number | null |
| heigh | Number | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Имя | Описание |
| --- | --- |
| getScaleX() | Относительная координата X |

 **Result:**



---


### setScaleX{#setScaleX}

| Имя | Описание |
| --- | --- |
| setScaleX(value) | Относительная координата X |

 **Result:**



---


### getScaleY{#getScaleY}

| Имя | Описание |
| --- | --- |
| getScaleY() | Относительная координата Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Имя | Описание |
| --- | --- |
| setScaleY(value) | Относительная координата Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Имя | Описание |
| --- | --- |
| getScaleWidth() | Относительная ширина |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Имя | Описание |
| --- | --- |
| setScaleWidth(value) | Относительная ширина |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Имя | Описание |
| --- | --- |
| getScaleHeight() | Относительная высота |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Имя | Описание |
| --- | --- |
| setScaleHeight(value) | Относительная высота |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Имя | Описание |
| --- | --- |
| getOffsetX() | Получает или задает смещение для координаты X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Имя | Описание |
| --- | --- |
| setOffsetX(value) | Получает или задает смещение для координаты X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Имя | Описание |
| --- | --- |
| getOffsetY() | Получает или задает смещение для координаты Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Имя | Описание |
| --- | --- |
| setOffsetY(value) | Получает или задает смещение для координаты Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Имя | Описание |
| --- | --- |
| getOffsetWidth() | Получает или задает смещение для ширины |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Имя | Описание |
| --- | --- |
| setOffsetWidth(value) | Получает или задает смещение для ширины |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Имя | Описание |
| --- | --- |
| getOffsetHeight() | Получает или задает смещение для высоты |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Имя | Описание |
| --- | --- |
| setOffsetHeight(value) | Получает или задает смещение для высоты |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Имя | Описание |
| --- | --- |
| toAbsolute(left, top, width, height) | Преобразовать относительный прямоугольник в абсолютный прямоугольник |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| лево | Number | Левая сторона прямоугольника |
| верх | Number | Верхняя сторона прямоугольника |
| ширина | Number | Ширина прямоугольника |
| height | Number | Высота прямоугольника |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Имя | Описание |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Создать RelativeRectangle со всеми полями смещения, равными нулю, и полями масштаба из заданных параметров. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| масштаб | Number | null |
| масштаб | Number | null |
| scaleWidt | Number | null |
| scaleHeigh | Number | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Преобразует значение этого экземпляра в java.lang.String. |

 **Result:**
RelativeRectangle


---



