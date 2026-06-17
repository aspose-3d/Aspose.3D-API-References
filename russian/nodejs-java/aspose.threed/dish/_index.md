---
title: "Dish"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/dish/
---
## Dish class

Параметрическая тарелка.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Создать новый экземпляр Dish с радиусом по умолчанию (10) и высотой по умолчанию (5) |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(radius, height) | Создать новый экземпляр Dish с указанными радиусом и высотой |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| radius | Number | Радиус Dish |
| height | Number | Высота Dish |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(name, radius, height, widthSegments, heightSegments) | Создать новый экземпляр Dish с указанными радиусом и высотой |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя Dish |
| radius | Number | Радиус Dish |
| height | Number | Высота Dish |
| widthSegments | Number | Ширина сегмента Dish |
| heightSegments | Number | Сегмент высоты блюда |

 **Result:**



---


### getHeight{#getHeight}

| Имя | Описание |
| --- | --- |
| getHeight() | Высота блюда |

 **Result:**



---


### setHeight{#setHeight}

| Имя | Описание |
| --- | --- |
| setHeight(value) | Высота блюда |

 **Result:**



---


### getRadius{#getRadius}

| Имя | Описание |
| --- | --- |
| getRadius() | Радиус блюда |

 **Result:**



---


### setRadius{#setRadius}

| Имя | Описание |
| --- | --- |
| setRadius(value) | Радиус блюда |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Имя | Описание |
| --- | --- |
| getWidthSegments() | Получает или задает сегменты ширины |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Имя | Описание |
| --- | --- |
| setWidthSegments(value) | Получает или задает сегменты ширины |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Имя | Описание |
| --- | --- |
| getHeightSegments() | Получает или задает сегменты высоты |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Имя | Описание |
| --- | --- |
| setHeightSegments(value) | Получает или задает сегменты высоты |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Имя | Описание |
| --- | --- |
| getCastShadows() | Получает или задает, может ли эта геометрия отбрасывать тень |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Имя | Описание |
| --- | --- |
| setCastShadows(value) | Получает или задает, может ли эта геометрия отбрасывать тень |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Имя | Описание |
| --- | --- |
| getReceiveShadows() | Получает или задает, может ли эта геометрия принимать тень. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Имя | Описание |
| --- | --- |
| setReceiveShadows(value) | Получает или задает, может ли эта геометрия принимать тень. |

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
| toMesh() | Преобразовать текущий объект в сетку |

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



