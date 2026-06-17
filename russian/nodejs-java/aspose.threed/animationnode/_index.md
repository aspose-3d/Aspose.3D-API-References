---
title: "AnimationNode"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D поддерживает иерархию анимации, каждая анимация может состоять из нескольких анимаций и определения ключевых кадров. AnimationNode определяет преобразование значения свойства во времени, например, узел анимации может использоваться для управления преобразованием узла или другими числовыми свойствами объекта A3DObject.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name) | Инициализирует новый экземпляр класса AnimationNode. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Инициализирует новый экземпляр класса AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Имя | Описание |
| --- | --- |
| getBindPoints() | Получает текущие точки привязки свойства |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Имя | Описание |
| --- | --- |
| getSubAnimations() | Получает узлы поданимаций, находящиеся под текущими анимациями |

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


### findBindPoint{#findBindPoint}

| Имя | Описание |
| --- | --- |
| findBindPoint(name) | Находит точку привязки по имени. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя точки привязки для поиска. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Имя | Описание |
| --- | --- |
| getBindPoint(target, propName, create) | Получает точку привязки анимации для указанного свойства. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| target | A3DObject | Для какого объекта создать точку привязки. |
| propName | String | Имя свойства. |
| создать | boolean | Если установлено в |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Имя | Описание |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Получает последовательность ключевых кадров для указанного свойства и канала. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| target | A3DObject | Для какого экземпляра создать последовательность ключевых кадров. |
| propName | String | Имя свойства. |
| channelName | String | Имя канала. |
| создать | boolean | Если установлено в |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Имя | Описание |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Получает последовательность ключевых кадров для указанного свойства. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| target | A3DObject | Для какого экземпляра создать последовательность ключевых кадров. |
| propName | String | Имя свойства. |
| создать | boolean | Если установлено в |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Имя | Описание |
| --- | --- |
| createBindPoint(obj, propName) | Создаёт BindPoint на основе типа данных свойства. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| obj | A3DObject | Объект. |
| propName | String | Имя свойства. |

 **Result:**
BindPoint


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



