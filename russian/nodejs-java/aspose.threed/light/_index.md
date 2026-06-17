---
title: "Light"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/light/
---
## Light class

Свет освещает сцену.  Формула для расчёта общей затухания света выглядит так:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса Light. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name) | Инициализирует новый экземпляр класса Light. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(name, type) | Инициализирует новый экземпляр класса Light. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Имя | Описание |
| --- | --- |
| getColor() | Получает или задает цвет света |

 **Result:**



---


### setColor{#setColor}

| Имя | Описание |
| --- | --- |
| setColor(value) | Получает или задает цвет света |

 **Result:**



---


### getLightType{#getLightType}

| Имя | Описание |
| --- | --- |
| getLightType() | Получает или задает тип света. Значение свойства — целочисленная константа LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Имя | Описание |
| --- | --- |
| setLightType(value) | Получает или задает тип света. Значение свойства — целочисленная константа LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Имя | Описание |
| --- | --- |
| getCastLight() | Получает или задает, может ли текущий экземпляр света освещать другие объекты. |

 **Result:**



---


### setCastLight{#setCastLight}

| Имя | Описание |
| --- | --- |
| setCastLight(value) | Получает или задает, может ли текущий экземпляр света освещать другие объекты. |

 **Result:**



---


### getIntensity{#getIntensity}

| Имя | Описание |
| --- | --- |
| getIntensity() | Получает или задает интенсивность света, значение по умолчанию — 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Имя | Описание |
| --- | --- |
| setIntensity(value) | Получает или задает интенсивность света, значение по умолчанию — 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Имя | Описание |
| --- | --- |
| getHotSpot() | Получает или задает угол конуса горячей точки (в градусах). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Имя | Описание |
| --- | --- |
| setHotSpot(value) | Получает или задает угол конуса горячей точки (в градусах). |

 **Result:**



---


### getFalloff{#getFalloff}

| Имя | Описание |
| --- | --- |
| getFalloff() | Получает или задает угол конуса затухания (в градусах). |

 **Result:**



---


### setFalloff{#setFalloff}

| Имя | Описание |
| --- | --- |
| setFalloff(value) | Получает или задает угол конуса затухания (в градусах). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Имя | Описание |
| --- | --- |
| getConstantAttenuation() | Получает или задает постоянное затухание для расчёта общего затухания света |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Имя | Описание |
| --- | --- |
| setConstantAttenuation(value) | Получает или задает постоянное затухание для расчёта общего затухания света |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Имя | Описание |
| --- | --- |
| getLinearAttenuation() | Получает или задает линейное затухание для расчёта общего затухания света |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Имя | Описание |
| --- | --- |
| setLinearAttenuation(value) | Получает или задает линейное затухание для расчёта общего затухания света |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Имя | Описание |
| --- | --- |
| getQuadraticAttenuation() | Получает или задает квадратичное затухание для расчёта общего затухания света |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Имя | Описание |
| --- | --- |
| setQuadraticAttenuation(value) | Получает или задает квадратичное затухание для расчёта общего затухания света |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Имя | Описание |
| --- | --- |
| getCastShadows() | Получает или задает, может ли свет отбрасывать тени на другие объекты. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Имя | Описание |
| --- | --- |
| setCastShadows(value) | Получает или задает, может ли свет отбрасывать тени на другие объекты. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Имя | Описание |
| --- | --- |
| getShadowColor() | Получает или задает цвет тени. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Имя | Описание |
| --- | --- |
| setShadowColor(value) | Получает или задает цвет тени. |

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



