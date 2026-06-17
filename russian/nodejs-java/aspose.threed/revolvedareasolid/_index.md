---
title: "RevolvedAreaSolid"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Этот класс представляет твёрдое тело, вращая поперечное сечение, заданное профилем, вокруг оси.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Имя | Описание |
| --- | --- |
| getAngleStart() | Получает или задает начальный угол вращающей процедуры, измеряется в радианах, значение по умолчанию — 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Имя | Описание |
| --- | --- |
| setAngleStart(value) | Получает или задает начальный угол вращающей процедуры, измеряется в радианах, значение по умолчанию — 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Имя | Описание |
| --- | --- |
| getAngleEnd() | Получает или задает конечный угол вращающей процедуры, измеряется в радианах, значение по умолчанию — π. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Имя | Описание |
| --- | --- |
| setAngleEnd(value) | Получает или задает конечный угол вращающей процедуры, измеряется в радианах, значение по умолчанию — π. |

 **Result:**



---


### getAxis{#getAxis}

| Имя | Описание |
| --- | --- |
| getAxis() | Получает или задает направление оси, значение по умолчанию — (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Имя | Описание |
| --- | --- |
| setAxis(value) | Получает или задает направление оси, значение по умолчанию — (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Имя | Описание |
| --- | --- |
| getOrigin() | Получает или задает точку начала вращения, значение по умолчанию — (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Имя | Описание |
| --- | --- |
| setOrigin(value) | Получает или задает точку начала вращения, значение по умолчанию — (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Имя | Описание |
| --- | --- |
| getShape() | Получает или задает базовый профиль, используемый для вращения. |

 **Result:**



---


### setShape{#setShape}

| Имя | Описание |
| --- | --- |
| setShape(value) | Получает или задает базовый профиль, используемый для вращения. |

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
| toMesh() | Преобразовать RevolvedAreaSolid в сетку. |

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



