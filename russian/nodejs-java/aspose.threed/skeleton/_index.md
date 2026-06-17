---
title: "Скелет"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

The Skeleton в основном используется CAD‑программами, чтобы помочь дизайнеру управлять преобразованием скелетной структуры; обычно он бесполезен вне CAD‑программ. Чтобы иерархия скелета вела себя как один объект в CAD‑программе, необходимо пометить верхний узел Skeleton как корневой, установив Type в SkeletonType.SKELETON, а все дочерние — в SkeletonType.BONE


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Создаёт новый экземпляр класса Skeleton. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name) | Создаёт новый экземпляр класса Skeleton. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |

 **Result:**



---


### getSize{#getSize}

| Имя | Описание |
| --- | --- |
| getSize() | Получает или задаёт размер узла конечности, используемый в CAD‑программах для представления размера кости. |

 **Result:**



---


### setSize{#setSize}

| Имя | Описание |
| --- | --- |
| setSize(value) | Получает или задаёт размер узла конечности, используемый в CAD‑программах для представления размера кости. |

 **Result:**



---


### getType{#getType}

| Имя | Описание |
| --- | --- |
| getType() | Получает или задаёт тип скелета. Значение свойства — целочисленная константа SkeletonType. Тип скелета. |

 **Result:**



---


### setType{#setType}

| Имя | Описание |
| --- | --- |
| setType(value) | Получает или задаёт тип скелета. Значение свойства — целочисленная константа SkeletonType. Тип скелета. |

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


### getBoundingBox{#getBoundingBox}

| Имя | Описание |
| --- | --- |
| getBoundingBox() | Получает ограничивающий прямоугольник текущей сущности в её системе координат объектного пространства. |

 **Result:**



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



