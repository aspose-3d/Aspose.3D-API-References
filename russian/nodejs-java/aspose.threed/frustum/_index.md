---
title: "Фрустум"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/frustum/
---
## Frustum class

Базовый класс для Camera и Light  @hideconstructor


## Методы

### getRotationMode{#getRotationMode}

| Имя | Описание |
| --- | --- |
| getRotationMode() | Получает или задает режим ориентации усечения. Это свойство работает только когда Target равен null. Если значение равно RotationMode.FIXED_TARGET, направление всегда вычисляется свойством LookAt. В противном случае LookAt всегда вычисляется свойством Direction. Значение свойства — целочисленная константа RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Имя | Описание |
| --- | --- |
| setRotationMode(value) | Получает или задает режим ориентации усечения. Это свойство работает только когда Target равен null. Если значение равно RotationMode.FIXED_TARGET, направление всегда вычисляется свойством LookAt. В противном случае LookAt всегда вычисляется свойством Direction. Значение свойства — целочисленная константа RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Имя | Описание |
| --- | --- |
| getNearPlane() | Получает или задает расстояние до ближней плоскости усечения. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Имя | Описание |
| --- | --- |
| setNearPlane(value) | Получает или задает расстояние до ближней плоскости усечения. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Имя | Описание |
| --- | --- |
| getFarPlane() | Получает или задает расстояние до дальней плоскости усечения. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Имя | Описание |
| --- | --- |
| setFarPlane(value) | Получает или задает расстояние до дальней плоскости усечения. |

 **Result:**



---


### getAspect{#getAspect}

| Имя | Описание |
| --- | --- |
| getAspect() | Получает или задает соотношение сторон усечения |

 **Result:**



---


### setAspect{#setAspect}

| Имя | Описание |
| --- | --- |
| setAspect(value) | Получает или задает соотношение сторон усечения |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Имя | Описание |
| --- | --- |
| getOrthoHeight() | Получает или задает высоту, когда усечение находится в ортографической проекции. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Имя | Описание |
| --- | --- |
| setOrthoHeight(value) | Получает или задает высоту, когда усечение находится в ортографической проекции. |

 **Result:**



---


### getUp{#getUp}

| Имя | Описание |
| --- | --- |
| getUp() | Получает или задает направление вверх камеры |

 **Result:**



---


### setUp{#setUp}

| Имя | Описание |
| --- | --- |
| setUp(value) | Получает или задает направление вверх камеры |

 **Result:**



---


### getLookAt{#getLookAt}

| Имя | Описание |
| --- | --- |
| getLookAt() | Получает или задает интересующую позицию, на которую смотрит камера. |

 **Result:**



---


### setLookAt{#setLookAt}

| Имя | Описание |
| --- | --- |
| setLookAt(value) | Получает или задает интересующую позицию, на которую смотрит камера. |

 **Result:**



---


### getDirection{#getDirection}

| Имя | Описание |
| --- | --- |
| getDirection() | Получает или задает направление, в котором смотрит камера. Изменения этого свойства также влияют на LookAt и Target. |

 **Result:**



---


### setDirection{#setDirection}

| Имя | Описание |
| --- | --- |
| setDirection(value) | Получает или задает направление, в котором смотрит камера. Изменения этого свойства также влияют на LookAt и Target. |

 **Result:**



---


### getTarget{#getTarget}

| Имя | Описание |
| --- | --- |
| getTarget() | Получает или задает цель, на которую смотрит камера. Если пользователь поддерживает это свойство, оно должно быть установлено до свойства LookAt. |

 **Result:**



---


### setTarget{#setTarget}

| Имя | Описание |
| --- | --- |
| setTarget(value) | Получает или задает цель, на которую смотрит камера. Если пользователь поддерживает это свойство, оно должно быть установлено до свойства LookAt. |

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



