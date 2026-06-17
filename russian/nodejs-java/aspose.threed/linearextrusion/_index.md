---
title: "LinearExtrusion"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

Линейная экструзия принимает 2D-форму в качестве входных данных и расширяет её в третьем измерении.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор экземпляра LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(shape, height) | Конструктор экземпляра LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Имя | Описание |
| --- | --- |
| getShape() | Базовая форма для экструдирования. |

 **Result:**



---


### setShape{#setShape}

| Имя | Описание |
| --- | --- |
| setShape(value) | Базовая форма для экструдирования. |

 **Result:**



---


### getDirection{#getDirection}

| Имя | Описание |
| --- | --- |
| getDirection() | Направление экструдирования, значение по умолчанию — (0, 0, 1) |

 **Result:**



---


### setDirection{#setDirection}

| Имя | Описание |
| --- | --- |
| setDirection(value) | Направление экструдирования, значение по умолчанию — (0, 0, 1) |

 **Result:**



---


### getHeight{#getHeight}

| Имя | Описание |
| --- | --- |
| getHeight() | Высота экструдированной геометрии, значение по умолчанию — 1.0 |

 **Result:**



---


### setHeight{#setHeight}

| Имя | Описание |
| --- | --- |
| setHeight(value) | Высота экструдированной геометрии, значение по умолчанию — 1.0 |

 **Result:**



---


### getSlices{#getSlices}

| Имя | Описание |
| --- | --- |
| getSlices() | Слои скрученной экструдированной геометрии, значение по умолчанию — 1. |

 **Result:**



---


### setSlices{#setSlices}

| Имя | Описание |
| --- | --- |
| setSlices(value) | Слои скрученной экструдированной геометрии, значение по умолчанию — 1. |

 **Result:**



---


### getCenter{#getCenter}

| Имя | Описание |
| --- | --- |
| getCenter() | Если это значение ложно, диапазон Z линейного экструдирования будет от 0 до высоты, иначе диапазон будет от -height/2 до height/2. |

 **Result:**



---


### setCenter{#setCenter}

| Имя | Описание |
| --- | --- |
| setCenter(value) | Если это значение ложно, диапазон Z линейного экструдирования будет от 0 до высоты, иначе диапазон будет от -height/2 до height/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Имя | Описание |
| --- | --- |
| getTwistOffset() | Смещение, используемое при скручивании, значение по умолчанию — (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Имя | Описание |
| --- | --- |
| setTwistOffset(value) | Смещение, используемое при скручивании, значение по умолчанию — (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Имя | Описание |
| --- | --- |
| getTwist() | Количество градусов, на которое форма экструдируется. |

 **Result:**



---


### setTwist{#setTwist}

| Имя | Описание |
| --- | --- |
| setTwist(value) | Количество градусов, на которое форма экструдируется. |

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


### toMesh{#toMesh}

| Имя | Описание |
| --- | --- |
| toMesh() | Преобразовать экструдирование в сетку. |

 **Result:**
Сетка


---


### getBoundingBox{#getBoundingBox}

| Имя | Описание |
| --- | --- |
| getBoundingBox() | Получает ограничивающий прямоугольник текущей сущности в её системе координат объектного пространства. |

 **Result:**
Сетка


---


### getEntityRendererKey{#getEntityRendererKey}

| Имя | Описание |
| --- | --- |
| getEntityRendererKey() | Получает ключ рендерера сущности, зарегистрированного в рендерере. |

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



