---
title: "MorphTargetDeformer"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer предоставляет анимацию на уровне вершин. MorphTargetDeformer организует все цели через MorphTargetChannel, каждый канал может содержать несколько целей. Распространённое применение morph target deformer — применение мимики к персонажу. Подробнее можно узнать по ссылке https://en.wikipedia.org/wiki/Morph_target_animation


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name) | Инициализирует новый экземпляр класса MorphTargetDeformer. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Инициализирует новый экземпляр класса MorphTargetDeformer. |

 **Result:**



---


### getChannels{#getChannels}

| Имя | Описание |
| --- | --- |
| getChannels() | Получает все каналы, содержащиеся в этом деформере |

 **Result:**



---


### getOwner{#getOwner}

| Имя | Описание |
| --- | --- |
| getOwner() | Получает геометрию, которой принадлежит этот деформатор |

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


### get{#get}

| Имя | Описание |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Имя | Описание |
| --- | --- |
| set(target, value) |  |

 **Result:**



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



