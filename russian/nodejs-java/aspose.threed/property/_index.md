---
title: "Property"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/property/
---
## Property class

Класс для хранения пользовательских свойств.  @hideconstructor


## Методы

### getValue{#getValue}

| Имя | Описание |
| --- | --- |
| getValue() | Получает или задает значение. Значение. |

 **Result:**



---


### setValue{#setValue}

| Имя | Описание |
| --- | --- |
| setValue(value) | Получает или задает значение. Значение. |

 **Result:**



---


### setName{#setName}

| Имя | Описание |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Имя | Описание |
| --- | --- |
| getValueType() | Получает тип значения свойства. Тип значения. |

 **Result:**



---


### getProperties{#getProperties}

| Имя | Описание |
| --- | --- |
| getProperties() | Получает коллекцию всех свойств. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Имя | Описание |
| --- | --- |
| getBindPoint(anim, create) | Получает точку привязки свойства в указанном экземпляре анимации. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| anim | AnimationNode | На какой анимации создать точку привязки. |
| создать | boolean | Создайте точку привязки свойства, если она не найдена. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Имя | Описание |
| --- | --- |
| getKeyframeSequence(anim, create) | Получает последовательность ключевых кадров для указанного экземпляра анимации. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| anim | AnimationNode | На какой анимации создать последовательность ключевых кадров. |
| создать | boolean | Создайте последовательность ключевых кадров, если она не найдена. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Возвращает строку, представляющую текущий Property. |

 **Result:**
String


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



