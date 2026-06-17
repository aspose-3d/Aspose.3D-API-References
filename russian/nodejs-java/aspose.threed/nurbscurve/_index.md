---
title: "NurbsCurve"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

Кривая NURBS — это кривая, представляемая NURBS (Non-uniform rational basis spline). Кривая NURBS определяется её порядком (Order), набором взвешенных Geometry.ControlPoints и KnotVectors. Компонент w в контрольной точке используется как вес контрольной точки, независимо от того, является ли она CurveDimension.TWO_DIMENSIONAL или CurveDimension.THREE_DIMENSIONAL.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name) | Инициализирует новый экземпляр класса NurbsCurve. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Имя | Описание |
| --- | --- |
| getControlPoints() | Получает все контрольные точки |

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
| getOrder() | Получает или задает порядок NURBS‑кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой. Порядок. |

 **Result:**



---


### setOrder{#setOrder}

| Имя | Описание |
| --- | --- |
| setOrder(value) | Получает или задает порядок NURBS‑кривой, он определяет количество соседних контрольных точек, влияющих на любую точку кривой. Порядок. |

 **Result:**



---


### getDimension{#getDimension}

| Имя | Описание |
| --- | --- |
| getDimension() | Получает или задает размерность кривой. Значение свойства — целочисленная константа CurveDimension. Для кривой CurveDimension.TWO_DIMENSIONAL компонент z в контрольной точке не используется. |

 **Result:**



---


### setDimension{#setDimension}

| Имя | Описание |
| --- | --- |
| setDimension(value) | Получает или задает размерность кривой. Значение свойства — целочисленная константа CurveDimension. Для кривой CurveDimension.TWO_DIMENSIONAL компонент z в контрольной точке не используется. |

 **Result:**



---


### getCurveType{#getCurveType}

| Имя | Описание |
| --- | --- |
| getCurveType() | Получает или задает тип кривой. Значение свойства — целочисленная константа NurbsType. Тип кривой. |

 **Result:**



---


### setCurveType{#setCurveType}

| Имя | Описание |
| --- | --- |
| setCurveType(value) | Получает или задает тип кривой. Значение свойства — целочисленная константа NurbsType. Тип кривой. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Имя | Описание |
| --- | --- |
| getKnotVectors() | Получает вектор узлов, это последовательность параметров, определяющая, где и как контрольные точки влияют на NURBS‑кривую. |

 **Result:**



---


### getRational{#getRational}

| Имя | Описание |
| --- | --- |
| getRational() | Получает или задает, является ли кривая рациональной; это значение указывает, является ли данный NurbsCurve рациональным сплайном или нерациональным сплайном. Не‑рациональный B‑сплайн является частным случаем рациональных B‑сплайнов. true, если это рациональный сплайн; иначе false — нерациональный сплайн. |

 **Result:**



---


### setRational{#setRational}

| Имя | Описание |
| --- | --- |
| setRational(value) | Получает или задает, является ли кривая рациональной; это значение указывает, является ли данный NurbsCurve рациональным сплайном или нерациональным сплайном. Не‑рациональный B‑сплайн является частным случаем рациональных B‑сплайнов. true, если это рациональный сплайн; иначе false — нерациональный сплайн. |

 **Result:**



---


### getColor{#getColor}

| Имя | Описание |
| --- | --- |
| getColor() | Получает или задает цвет линии, значение по умолчанию — белый (1, 1, 1). |

 **Result:**



---


### setColor{#setColor}

| Имя | Описание |
| --- | --- |
| setColor(value) | Получает или задает цвет линии, значение по умолчанию — белый (1, 1, 1). |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Имя | Описание |
| --- | --- |
| getParentNodes() | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. Узлы. |

 **Result:**



---


### getExcluded{#getExcluded}

| Имя | Описание |
| --- | --- |
| getExcluded() | Получает или задает, следует ли исключать эту сущность при экспорте. |

 **Result:**



---


### setExcluded{#setExcluded}

| Имя | Описание |
| --- | --- |
| setExcluded(value) | Получает или задает, следует ли исключать эту сущность при экспорте. |

 **Result:**



---


### getParentNode{#getParentNode}

| Имя | Описание |
| --- | --- |
| getParentNode() | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от других родительских узлов. Родительский узел. |

 **Result:**



---


### setParentNode{#setParentNode}

| Имя | Описание |
| --- | --- |
| setParentNode(value) | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от других родительских узлов. Родительский узел. |

 **Result:**



---


### getScene{#getScene}

| Имя | Описание |
| --- | --- |
| getScene() | Получает сцену, к которой принадлежит этот объект. |

 **Result:**



---


### getName{#getName}

| Имя | Описание |
| --- | --- |
| getName() | Получает или задает имя. Имя. |

 **Result:**



---


### setName{#setName}

| Имя | Описание |
| --- | --- |
| setName(value) | Получает или задает имя. Имя. |

 **Result:**



---


### getProperties{#getProperties}

| Имя | Описание |
| --- | --- |
| getProperties() | Получает коллекцию всех свойств. |

 **Result:**



---


### evaluate{#evaluate}

| Имя | Описание |
| --- | --- |
| evaluate(steps) | Вычислить NURBS‑кривую |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| steps | Number | Частота вычисления между двумя соседними узлами, значение по умолчанию — 20. |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Имя | Описание |
| --- | --- |
| evaluateAt(u) | Вычислить точку кривой в указанной позиции. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| u | Number | Позиция на кривой, от 0 до 1. |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| Имя | Описание |
| --- | --- |
| getEntityRendererKey() | Получает ключ рендерера сущности, зарегистрированного в рендерере. |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Имя | Описание |
| --- | --- |
| getBoundingBox() | Получает ограничивающий прямоугольник текущей сущности в её системе координат объектного пространства. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удаляет динамическое свойство. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | Property | Какое свойство удалить |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удалить указанное свойство, определённое по имени |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Имя | Описание |
| --- | --- |
| getProperty(property) | Получить значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |

 **Result:**
Object


---


### setProperty{#setProperty}

| Имя | Описание |
| --- | --- |
| setProperty(property, value) | Устанавливает значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |
| value | Object | Значение свойства |

 **Result:**
Object


---


### findProperty{#findProperty}

| Имя | Описание |
| --- | --- |
| findProperty(propertyName) | Находит свойство. Это может быть динамическое свойство (Created by CreateDynamicProperty/SetProperty) или нативное свойство (Identified by its name) |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propertyName | String | Имя свойства. |

 **Result:**
Property


---



