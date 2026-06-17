---
title: "NurbsDirection"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/nurbsdirection/
---
## NurbsDirection class

3D NurbsSurface имеет два направления: NurbsSurface.U и NurbsSurface.V; NurbsDirection определяет данные для каждого направления. Направление фактически является кривой NURBS, то есть оно также определяется своим порядком (Order), KnotVectors и набором взвешенных контрольных точек (определённых в NurbsSurface).


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Имя | Описание |
| --- | --- |
| getKnotVectors() | Получает вектор узлов, это последовательность параметров, определяющая, где и как контрольные точки влияют на NURBS‑кривую. |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Имя | Описание |
| --- | --- |
| getMultiplicity() | Получает кратность. Кратность. |

 **Result:**



---


### getOrder{#getOrder}

| Имя | Описание |
| --- | --- |
| getOrder() | Получает или задает порядок NURBS-кривой, определяя количество соседних контрольных точек, влияющих на любую точку кривой. |

 **Result:**



---


### setOrder{#setOrder}

| Имя | Описание |
| --- | --- |
| setOrder(value) | Получает или задает порядок NURBS-кривой, определяя количество соседних контрольных точек, влияющих на любую точку кривой. |

 **Result:**



---


### getDivisions{#getDivisions}

| Имя | Описание |
| --- | --- |
| getDivisions() | Получает или задает количество делений между соседними контрольными точками в текущем направлении. Шаг. |

 **Result:**



---


### setDivisions{#setDivisions}

| Имя | Описание |
| --- | --- |
| setDivisions(value) | Получает или задает количество делений между соседними контрольными точками в текущем направлении. Шаг. |

 **Result:**



---


### getType{#getType}

| Имя | Описание |
| --- | --- |
| getType() | Получает или задает тип текущего направления. Значение свойства — целая константа NurbsType. |

 **Result:**



---


### setType{#setType}

| Имя | Описание |
| --- | --- |
| setType(value) | Получает или задает тип текущего направления. Значение свойства — целая константа NurbsType. |

 **Result:**



---


### getCount{#getCount}

| Имя | Описание |
| --- | --- |
| getCount() | Получает или задает количество контрольных точек в текущем направлении. Количество. |

 **Result:**



---


### setCount{#setCount}

| Имя | Описание |
| --- | --- |
| setCount(value) | Получает или задает количество контрольных точек в текущем направлении. Количество. |

 **Result:**



---



