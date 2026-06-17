---
title: "AnimationClip"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Клип анимации представляет собой набор анимаций. Сцена может содержать один или несколько клипов анимации.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name) | Инициализирует новый экземпляр класса AnimationClip. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

 **Result:**



---


### getAnimations{#getAnimations}

| Имя | Описание |
| --- | --- |
| getAnimations() | Получает анимации, содержащиеся в клипе. Слои. |

 **Result:**



---


### getDescription{#getDescription}

| Имя | Описание |
| --- | --- |
| getDescription() | Получает или задает описание этого анимационного клипа |

 **Result:**



---


### setDescription{#setDescription}

| Имя | Описание |
| --- | --- |
| setDescription(value) | Получает или задает описание этого анимационного клипа |

 **Result:**



---


### getStart{#getStart}

| Имя | Описание |
| --- | --- |
| getStart() | Получает или задает время в секундах начала клипа. |

 **Result:**



---


### setStart{#setStart}

| Имя | Описание |
| --- | --- |
| setStart(value) | Получает или задает время в секундах начала клипа. |

 **Result:**



---


### getStop{#getStop}

| Имя | Описание |
| --- | --- |
| getStop() | Получает или задает время в секундах окончания клипа. |

 **Result:**



---


### setStop{#setStop}

| Имя | Описание |
| --- | --- |
| setStop(value) | Получает или задает время в секундах окончания клипа. |

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


### createAnimationNode{#createAnimationNode}

| Имя | Описание |
| --- | --- |
| createAnimationNode(nodeName) | Сокращённая функция для создания и регистрации узла анимации в текущем клипе. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя нового узла анимации |

 **Result:**
AnimationNode


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



