---
title: "Pose"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/pose/
---
## Pose class

Позa используется для хранения матрицы преобразования, когда геометрия скинится. Позa представляет собой набор BonePose, каждый BonePose сохраняет конкретную информацию о преобразовании узла кости.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name) | Инициализирует новый экземпляр класса Pose. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Инициализирует новый экземпляр класса Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| Имя | Описание |
| --- | --- |
| getPoseType() | Получает или задает тип позы. Значение свойства — целочисленная константа PoseType. Тип позы. |

 **Result:**



---


### setPoseType{#setPoseType}

| Имя | Описание |
| --- | --- |
| setPoseType(value) | Получает или задает тип позы. Значение свойства — целочисленная константа PoseType. Тип позы. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Имя | Описание |
| --- | --- |
| getBonePoses() | Получает все BonePose. Узлы. |

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


### addBonePose{#addBonePose}

| Имя | Описание |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Сохраняет матрицу преобразования позы для указанного костного узла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| node | Node | Костный узел. |
| matrix | Matrix4 | Матрица преобразования. |
| localMatrix | boolean | Если установлено в |

 **Result:**



---


### addBonePose{#addBonePose}

| Имя | Описание |
| --- | --- |
| addBonePose(node, matrix) | Сохраняет матрицу трансформации позы для указанного узла кости. Глобальная матрица трансформации подразумевается. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| node | Node | Костный узел. |
| matrix | Matrix4 | Матрица преобразования. |

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



