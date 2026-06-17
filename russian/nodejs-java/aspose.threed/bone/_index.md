---
title: "Bone"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/bone/
---
## Bone class

Кость определяет подмножество контрольных точек геометрии и задаёт вес смешивания для каждой контрольной точки. Объект Bone нельзя использовать напрямую, для деформации геометрии используется экземпляр SkinDeformer, который поставляется с набором костей, каждая кость привязана к узлу. ПРИМЕЧАНИЕ: Контрольная точка геометрии может быть привязана к более чем одной кости.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name) | Инициализирует новый экземпляр класса Bone. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Инициализирует новый экземпляр класса Bone. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Имя | Описание |
| --- | --- |
| getWeightCount() | Получает количество весов, которое автоматически расширяется методом setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Имя | Описание |
| --- | --- |
| getTransform() | Получает или задает матрицу преобразования узла, содержащего bone. |

 **Result:**



---


### setTransform{#setTransform}

| Имя | Описание |
| --- | --- |
| setTransform(value) | Получает или задает матрицу преобразования узла, содержащего bone. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Имя | Описание |
| --- | --- |
| getBoneTransform() | Получает или задает матрицу преобразования кости. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Имя | Описание |
| --- | --- |
| setBoneTransform(value) | Получает или задает матрицу преобразования кости. |

 **Result:**



---


### getNode{#getNode}

| Имя | Описание |
| --- | --- |
| getNode() | Получает или задает узел. Узел кости — это кость, к которой прикреплена кожа, SkinDeformer будет использовать узел кости для влияния на смещение контрольных точек. Узел кости обычно имеет прикреплённый Skeleton, но это не обязательно. Прикреплённый Skeleton обычно используется программным обеспечением DCC для отображения скелета пользователю. |

 **Result:**



---


### setNode{#setNode}

| Имя | Описание |
| --- | --- |
| setNode(value) | Получает или задает узел. Узел кости — это кость, к которой прикреплена кожа, SkinDeformer будет использовать узел кости для влияния на смещение контрольных точек. Узел кости обычно имеет прикреплённый Skeleton, но это не обязательно. Прикреплённый Skeleton обычно используется программным обеспечением DCC для отображения скелета пользователю. |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| Имя | Описание |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Имя | Описание |
| --- | --- |
| getWeight(index) | Получает вес для контрольной точки, указанной индексом |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| индекс | Number | Индекс контрольной точки |

 **Result:**
Number


---


### setWeight{#setWeight}

| Имя | Описание |
| --- | --- |
| setWeight(index, weight) | Задает вес для контрольной точки, указанной индексом |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| индекс | Number | Индекс контрольной точки |
| вес | Number | Новый вес |

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



