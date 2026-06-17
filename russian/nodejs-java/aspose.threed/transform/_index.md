---
title: "Трансформ"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/transform/
---
## Transform class

Трансформ содержит информацию, позволяющую получить доступ к перемещению/масштабированию/вращению объекта или матрице преобразования с минимальными затратами.  Это используется локальным трансформом.  @hideconstructor


## Методы

### getGeometricTranslation{#getGeometricTranslation}

| Имя | Описание |
| --- | --- |
| getGeometricTranslation() | Получает или задает геометрический перенос. Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые не поддерживают его, оно будет объединено как локальное преобразование. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Имя | Описание |
| --- | --- |
| setGeometricTranslation(value) | Получает или задает геометрический перенос. Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые не поддерживают его, оно будет объединено как локальное преобразование. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Имя | Описание |
| --- | --- |
| getGeometricScaling() | Получает или задает геометрическое масштабирование. Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые не поддерживают его, оно будет объединено как локальное преобразование. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Имя | Описание |
| --- | --- |
| setGeometricScaling(value) | Получает или задает геометрическое масштабирование. Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые не поддерживают его, оно будет объединено как локальное преобразование. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Имя | Описание |
| --- | --- |
| getGeometricRotation() | Получает или задает геометрическое вращение Эйлера (измеряется в градусах). Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые не поддерживают его, оно будет объединено как локальное преобразование. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Имя | Описание |
| --- | --- |
| setGeometricRotation(value) | Получает или задает геометрическое вращение Эйлера (измеряется в градусах). Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые не поддерживают его, оно будет объединено как локальное преобразование. |

 **Result:**



---


### getTranslation{#getTranslation}

| Имя | Описание |
| --- | --- |
| getTranslation() | Получает или задает трансляцию |

 **Result:**



---


### setTranslation{#setTranslation}

| Имя | Описание |
| --- | --- |
| setTranslation(value) | Получает или задает трансляцию |

 **Result:**



---


### getScale{#getScale}

| Имя | Описание |
| --- | --- |
| getScale() | Получает или задает масштаб |

 **Result:**



---


### setScale{#setScale}

| Имя | Описание |
| --- | --- |
| setScale(value) | Получает или задает масштаб |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Имя | Описание |
| --- | --- |
| getPreRotation() | Получает или задает предварительное вращение, представленное в градусах |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Имя | Описание |
| --- | --- |
| setPreRotation(value) | Получает или задает предварительное вращение, представленное в градусах |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Имя | Описание |
| --- | --- |
| getPostRotation() | Получает или задает последующее вращение, представленное в градусах |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Имя | Описание |
| --- | --- |
| setPostRotation(value) | Получает или задает последующее вращение, представленное в градусах |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Имя | Описание |
| --- | --- |
| getEulerAngles() | Получает или задает вращение, представленное углами Эйлера, измеряемое в градусах |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Имя | Описание |
| --- | --- |
| setEulerAngles(value) | Получает или задает вращение, представленное углами Эйлера, измеряемое в градусах |

 **Result:**



---


### getRotation{#getRotation}

| Имя | Описание |
| --- | --- |
| getRotation() | Получает или задает вращение, представленное кватернионом. |

 **Result:**



---


### setRotation{#setRotation}

| Имя | Описание |
| --- | --- |
| setRotation(value) | Получает или задает вращение, представленное кватернионом. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Имя | Описание |
| --- | --- |
| getTransformMatrix() | Получает или задает матрицу преобразования. Присвоение этому свойству сбросит Translation, Scale и Rotation, при этом GeometricRotation, GeometricScaling и GeometricTranslation не будут затронуты. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Имя | Описание |
| --- | --- |
| setTransformMatrix(value) | Получает или задает матрицу преобразования. Присвоение этому свойству сбросит Translation, Scale и Rotation, при этом GeometricRotation, GeometricScaling и GeometricTranslation не будут затронуты. |

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


### setGeometricTranslation{#setGeometricTranslation}

| Имя | Описание |
| --- | --- |
| setGeometricTranslation(x, y, z) | Задает геометрическую трансляцию. Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. Оно будет объединено как локальное преобразование при экспорте геометрического преобразования в типы файлов, которые его не поддерживают. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Имя | Описание |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Задает геометрическое масштабирование. Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. Оно будет объединено как локальное преобразование при экспорте геометрического преобразования в типы файлов, которые его не поддерживают. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Имя | Описание |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Задает геометрическое вращение Эйлера (измеряется в градусах). Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. Оно будет объединено как локальное преобразование при экспорте геометрического преобразования в типы файлов, которые его не поддерживают. |

 **Result:**



---


### setTranslation{#setTranslation}

| Имя | Описание |
| --- | --- |
| setTranslation(tx, ty, tz) | Задает трансляцию текущего преобразования. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**
Трансформ


---


### setScale{#setScale}

| Имя | Описание |
| --- | --- |
| setScale(sx, sy, sz) | Задает масштаб текущего преобразования. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| s | Number | null |
| s | Number | null |
| s | Number | null |

 **Result:**
Трансформ


---


### setEulerAngles{#setEulerAngles}

| Имя | Описание |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Устанавливает углы Эйлера в градусах текущего преобразования. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| r | Number | null |
| r | Number | null |
| r | Number | null |

 **Result:**
Трансформ


---


### setRotation{#setRotation}

| Имя | Описание |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Устанавливает вращение (как компоненты кватерниона) текущего преобразования. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| r | Number | null |
| r | Number | null |
| r | Number | null |
| r | Number | null |

 **Result:**
Трансформ


---


### setPreRotation{#setPreRotation}

| Имя | Описание |
| --- | --- |
| setPreRotation(rx, ry, rz) | Устанавливает предварительное вращение, представленное в градусах |

 **Result:**
Трансформ


---


### setPostRotation{#setPostRotation}

| Имя | Описание |
| --- | --- |
| setPostRotation(rx, ry, rz) | Устанавливает последующее вращение, представленное в градусах |

 **Result:**
Трансформ


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



