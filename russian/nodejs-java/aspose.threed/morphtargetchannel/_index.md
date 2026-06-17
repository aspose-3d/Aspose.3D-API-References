---
title: "MorphTargetChannel"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetChannel используется MorphTargetDeformer для организации целевых геометрий. Некоторые форматы файлов, такие как FBX, поддерживают несколько каналов одновременно. Вес находится в диапазоне от 0 до 1.0, а вес по умолчанию для цели равен 0.0;


## Свойства

| Имя | Описание |
| --- | --- |
| DEFAULT_WEIGHT | Вес по умолчанию для morph target. |

## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name) | Создаёт новый экземпляр класса MorphTargetChannel. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Создаёт новый экземпляр класса MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| Имя | Описание |
| --- | --- |
| getWeights() | Получает полные значения весов целевых геометрий. Полные веса. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Имя | Описание |
| --- | --- |
| getChannelWeight() | Получает или задаёт вес деформера этого канала. Вес находится в диапазоне от 0.0 до 1.0. |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Имя | Описание |
| --- | --- |
| setChannelWeight(value) | Получает или задаёт вес деформера этого канала. Вес находится в диапазоне от 0.0 до 1.0. |

 **Result:**



---


### getTargets{#getTargets}

| Имя | Описание |
| --- | --- |
| getTargets() | Получает все цели, связанные с каналом. |

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


### getWeight{#getWeight}

| Имя | Описание |
| --- | --- |
| getWeight(target) | Получает вес для указанного целевого объекта; если объект не принадлежит этому каналу, возвращается значение по умолчанию 0. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| цель | Форма | null |

 **Result:**
Number


---


### setWeight{#setWeight}

| Имя | Описание |
| --- | --- |
| setWeight(target, weight) | Устанавливает вес для указанного целевого объекта, значение по умолчанию 1, диапазон должен быть от 0 до 1. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| цель | Форма | null |
| вес | Number | null |

 **Result:**
Number


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



