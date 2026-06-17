---
title: "TransformBuilder"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilder используется для построения матрицы преобразования цепочкой трансформаций.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(initial, order) | Создать TransformBuilder с начальной матрицей преобразования и указанным порядком композиции |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| initia | Matrix4 | null |
| порядок | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(order) | Создать TransformBuilder с начальной единичной матрицей преобразования и указанным порядком композиции |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| порядок | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Имя | Описание |
| --- | --- |
| getMatrix() | Получает или задает текущее значение матрицы |

 **Result:**



---


### setMatrix{#setMatrix}

| Имя | Описание |
| --- | --- |
| setMatrix(value) | Получает или задает текущее значение матрицы |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Имя | Описание |
| --- | --- |
| getComposeOrder() | Получает или задает порядок композиции цепочки. Значение свойства — целочисленная константа ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Имя | Описание |
| --- | --- |
| setComposeOrder(value) | Получает или задает порядок композиции цепочки. Значение свойства — целочисленная константа ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Имя | Описание |
| --- | --- |
| compose(m) | Добавить или предварить аргумент к внутренней матрице. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Имя | Описание |
| --- | --- |
| append(m) | Добавить новую матрицу преобразования в цепочку трансформаций. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Имя | Описание |
| --- | --- |
| prepend(m) | Добавьте новую матрицу преобразования в цепочку преобразований. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Имя | Описание |
| --- | --- |
| rearrange(newX, newY, newZ) | Переставьте расположение оси. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| newX | Ось | Ось |
| newY | Ось | Ось |
| newZ | Ось | Ось |

 **Result:**



---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(s) | Свяжите матрицу масштабирования с компонентом, масштабированным на s |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(x, y, z) | Свяжите матрицу масштабирования |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(s) | Свяжите трансформ масштабирования |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Имя | Описание |
| --- | --- |
| rotateDegree(angle, axis) | Свяжите вращательный трансформ в градусах |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| angle | Number | Угол вращения в градусах |
| axis | Vector3 | Ось вращения |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Имя | Описание |
| --- | --- |
| rotateRadian(angle, axis) | Свяжите вращательный трансформ в радианах |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| angle | Number | Угол вращения в радианах |
| axis | Vector3 | Ось вращения |

 **Result:**



---


### rotate{#rotate}

| Имя | Описание |
| --- | --- |
| rotate(q) | Свяжите вращение с помощью кватерниона |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Кватернион | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Имя | Описание |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Свяжите вращение по углам Эйлера в градусах |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| град | Number | null |
| град | Number | null |
| град | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Имя | Описание |
| --- | --- |
| rotateEulerRadian(x, y, z) | Свяжите вращение по углам Эйлера в радианах |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Имя | Описание |
| --- | --- |
| rotateEulerRadian(r) | Свяжите вращение по углам Эйлера в радианах |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Имя | Описание |
| --- | --- |
| translate(tx, ty, tz) | Свяжите трансформ перемещения |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**



---


### translate{#translate}

| Имя | Описание |
| --- | --- |
| translate(v) | Свяжите трансформ перемещения |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Имя | Описание |
| --- | --- |
| reset() | Сбросьте трансформ к единичной матрице |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Имя | Описание |
| --- | --- |
| rotateDegree(rot, order) | Добавить вращение с указанным порядком |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rot | Vector3 | Вращение в градусах |
| порядок | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Имя | Описание |
| --- | --- |
| rotateRadian(rot, order) | Добавить вращение с указанным порядком |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rot | Vector3 | Вращение в радианах |
| порядок | RotationOrder | RotationOrder |

 **Result:**



---



