---
title: "KeyframeSequence"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Последовательность ключевых кадров, описывающая преобразование выбранного значения во времени.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name) | Инициализирует новый экземпляр класса KeyframeSequence. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Инициализирует новый экземпляр класса KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Имя | Описание |
| --- | --- |
| getBindPoint() | Получает точку привязки свойства, которой принадлежит эта кривая. |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Имя | Описание |
| --- | --- |
| getKeyFrames() | Получает ключевые кадры этой кривой. Ключи. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Имя | Описание |
| --- | --- |
| getPostBehavior() | Получает пост‑поведение, указывающее, каким должно быть выборочное значение после последнего ключевого кадра. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Имя | Описание |
| --- | --- |
| getPreBehavior() | Получает пре‑поведение, указывающее, каким должно быть выборочное значение до первого ключа. |

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


### add{#add}

| Имя | Описание |
| --- | --- |
| add(time, value) | Создать новый ключевой кадр с указанным значением |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| время | Number | Позиция времени (измеряется в секундах) |
| value | Number | Значение в этой позиции времени |

 **Result:**



---


### add{#add}

| Имя | Описание |
| --- | --- |
| add(time, value, interpolation) | Создать новый ключевой кадр с указанным значением |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| время | Number | Позиция времени (измеряется в секундах) |
| value | Number | Значение в этой позиции времени |
| интерполяция | Интерполяция | Интерполяция |

 **Result:**



---


### reset{#reset}

| Имя | Описание |
| --- | --- |
| reset() | Удаляет все ключевые кадры и сбрасывает поведения post/pre. |

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


### iterator{#iterator}

| Имя | Описание |
| --- | --- |
| iterator() | Зарезервировано для внутреннего использования. |

 **Result:**
Property


---



