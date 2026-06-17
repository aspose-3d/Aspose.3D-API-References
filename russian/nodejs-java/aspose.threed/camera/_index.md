---
title: "Camera"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/camera/
---
## Camera class

Камера описывает точку глаза наблюдателя, смотрящего на сцену.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса Camera. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(projectionType) | Инициализирует новый экземпляр класса Camera. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(name) | Инициализирует новый экземпляр класса Camera. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Имя | Описание |
| --- | --- |
| constructor_overload3(name, projectionType) | Инициализирует новый экземпляр класса Camera. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Имя | Описание |
| --- | --- |
| getApertureMode() | Получает или задает режим диафрагмы камеры. Значение свойства — целочисленная константа ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Имя | Описание |
| --- | --- |
| setApertureMode(value) | Получает или задает режим диафрагмы камеры. Значение свойства — целочисленная константа ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Имя | Описание |
| --- | --- |
| getFieldOfView() | Получает или задает поле зрения камеры в градусах; это свойство используется только когда ApertureMode равно ApertureMode.HORIZONTAL или ApertureMode.VERTICAL |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Имя | Описание |
| --- | --- |
| setFieldOfView(value) | Получает или задает поле зрения камеры в градусах; это свойство используется только когда ApertureMode равно ApertureMode.HORIZONTAL или ApertureMode.VERTICAL |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Имя | Описание |
| --- | --- |
| getFieldOfViewX() | Получает или задает горизонтальное поле зрения камеры в градусах; это свойство используется только когда ApertureMode равно ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Имя | Описание |
| --- | --- |
| setFieldOfViewX(value) | Получает или задает горизонтальное поле зрения камеры в градусах; это свойство используется только когда ApertureMode равно ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Имя | Описание |
| --- | --- |
| getFieldOfViewY() | Получает или задает вертикальное поле зрения камеры в градусах; это свойство используется только когда ApertureMode равно ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Имя | Описание |
| --- | --- |
| setFieldOfViewY(value) | Получает или задает вертикальное поле зрения камеры в градусах; это свойство используется только когда ApertureMode равно ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getWidth{#getWidth}

| Имя | Описание |
| --- | --- |
| getWidth() | Получает или задает ширину плоскости просмотра в дюймах |

 **Result:**



---


### setWidth{#setWidth}

| Имя | Описание |
| --- | --- |
| setWidth(value) | Получает или задает ширину плоскости просмотра в дюймах |

 **Result:**



---


### getHeight{#getHeight}

| Имя | Описание |
| --- | --- |
| getHeight() | Получает или задает высоту плоскости просмотра в дюймах |

 **Result:**



---


### setHeight{#setHeight}

| Имя | Описание |
| --- | --- |
| setHeight(value) | Получает или задает высоту плоскости просмотра в дюймах |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Имя | Описание |
| --- | --- |
| getAspectRatio() | Получает или задает соотношение сторон плоскости просмотра. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Имя | Описание |
| --- | --- |
| setAspectRatio(value) | Получает или задает соотношение сторон плоскости просмотра. |

 **Result:**



---


### getMagnification{#getMagnification}

| Имя | Описание |
| --- | --- |
| getMagnification() | Получает или задает увеличение, используемое в ортографической камере |

 **Result:**



---


### setMagnification{#setMagnification}

| Имя | Описание |
| --- | --- |
| setMagnification(value) | Получает или задает увеличение, используемое в ортографической камере |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Имя | Описание |
| --- | --- |
| getProjectionType() | Получает или задает тип проекции камеры. По умолчанию используется перспективная проекция. Значение свойства — целочисленная константа ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Имя | Описание |
| --- | --- |
| setProjectionType(value) | Получает или задает тип проекции камеры. По умолчанию используется перспективная проекция. Значение свойства — целочисленная константа ProjectionType. |

 **Result:**



---


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


### moveForward{#moveForward}

| Имя | Описание |
| --- | --- |
| moveForward(distance) | Переместить камеру вперёд в направлении её взгляда или цели. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| distance | Number | Как долго перемещаться вперёд |

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



