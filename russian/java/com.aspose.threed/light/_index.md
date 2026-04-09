---
title: Light
second_title: Справочник API Aspose.3D для Java
description: Свет освещает сцену.
type: docs
weight: 94
url: /ru/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

Свет освещает сцену.

Формула для расчёта общей затухаемости света выглядит так:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Light()](#Light--) | Инициализирует новый экземпляр класса [Light](../../com.aspose.threed/light). |
| [Light(String name)](#Light-java.lang.String-) | Инициализирует новый экземпляр класса [Light](../../com.aspose.threed/light). |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Инициализирует новый экземпляр класса [Light](../../com.aspose.threed/light). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getAspect()](#getAspect--) | Получает соотношение сторон фрустума |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getCastLight()](#getCastLight--) | Получает, может ли текущий экземпляр света освещать другие объекты. |
| [getCastShadows()](#getCastShadows--) | Получает, может ли свет отбрасывать тени на другие объекты. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет света |
| [getConstantAttenuation()](#getConstantAttenuation--) | Получает постоянное затухание для расчёта общей затухаемости света |
| [getDirection()](#getDirection--) | Получает направление, в котором смотрит камера. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getFalloff()](#getFalloff--) | Получает угол конуса затухания (в градусах). |
| [getFarPlane()](#getFarPlane--) | Получает расстояние до дальней плоскости фрустума. |
| [getHotSpot()](#getHotSpot--) | Получает угол конуса горячей зоны (в градусах). |
| [getIntensity()](#getIntensity--) | Получает интенсивность света, значение по умолчанию — 100 |
| [getLightType()](#getLightType--) | Получает тип света |
| [getLinearAttenuation()](#getLinearAttenuation--) | Получает линейное затухание для расчёта общего затухания света |
| [getLookAt()](#getLookAt--) | Получает интересующую позицию, на которую смотрит камера. |
| [getName()](#getName--) | Получает имя. |
| [getNearPlane()](#getNearPlane--) | Получает расстояние до ближней плоскости усечения. |
| [getOrthoHeight()](#getOrthoHeight--) | Получает высоту, когда усечение в ортографической проекции. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Получает квадратичное затухание для расчёта общего затухания света |
| [getRotationMode()](#getRotationMode--) | Получает режим ориентации усечения. Это свойство работает только когда [getTarget](../../com.aspose.threed/frustum\#getTarget) равно null. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getShadowColor()](#getShadowColor--) | Получает цвет тени. |
| [getTarget()](#getTarget--) | Получает цель, на которую смотрит камера. |
| [getUp()](#getUp--) | Получает направление вверх камеры |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setAspect(double value)](#setAspect-double-) | Устанавливает соотношение сторон усечения |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Устанавливает, может ли текущий экземпляр света освещать другие объекты. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Устанавливает, может ли свет отбрасывать тени на другие объекты. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Устанавливает цвет света |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Устанавливает постоянное затухание для расчёта общего затухания света |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Устанавливает направление, в котором смотрит камера. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setFalloff(double value)](#setFalloff-double-) | Устанавливает угол затухания конуса (в градусах). |
| [setFarPlane(double value)](#setFarPlane-double-) | Устанавливает расстояние до дальней плоскости усечения. |
| [setHotSpot(double value)](#setHotSpot-double-) | Устанавливает угол конуса горячей зоны (в градусах). |
| [setIntensity(double value)](#setIntensity-double-) | Устанавливает интенсивность света, значение по умолчанию — 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Устанавливает тип света |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Устанавливает линейное затухание для расчёта общего затухания света |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Устанавливает интересующую позицию, на которую смотрит камера. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setNearPlane(double value)](#setNearPlane-double-) | Устанавливает расстояние ближней плоскости усечения. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Устанавливает высоту при ортографической проекции усечения. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Устанавливает квадратичное затухание для расчёта общего затухания света |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Устанавливает режим ориентации усечения. Это свойство работает только когда [getTarget](../../com.aspose.threed/frustum\#getTarget) равно null. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Устанавливает цвет тени. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Устанавливает цель, на которую смотрит камера. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Устанавливает направление вверх камеры |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Инициализирует новый экземпляр класса [Light](../../com.aspose.threed/light).

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Инициализирует новый экземпляр класса [Light](../../com.aspose.threed/light).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Инициализирует новый экземпляр класса [Light](../../com.aspose.threed/light).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя |
| type | [LightType](../../com.aspose.threed/lighttype) | Тип нового света |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Находит свойство. Оно может быть динамическим свойством (созданным с помощью CreateDynamicProperty/SetProperty) или нативным свойством (определяемым по его имени)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | java.lang.String | Имя свойства. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAspect() {#getAspect--}
```
public double getAspect()
```


Получает соотношение сторон фрустума

**Returns:**
double — соотношение сторон усечения
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Получает, может ли текущий экземпляр света освещать другие объекты.

**Returns:**
boolean — может ли текущий экземпляр света освещать другие объекты.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Получает, может ли свет отбрасывать тени на другие объекты.

**Returns:**
boolean — может ли свет отбрасывать тени на другие объекты.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Получает цвет света

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Получает постоянное затухание для расчёта общей затухаемости света

**Returns:**
double — постоянное затухание для расчёта общего затухания света
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Получает направление, в котором смотрит камера. Изменения этого свойства также влияют на [getLookAt](../../com.aspose.threed/frustum\#getLookAt) и [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Получает ключ рендерера сущности, зарегистрированного в рендерере.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Получает, следует ли исключать эту сущность при экспорте.

**Returns:**
boolean — следует ли исключать эту сущность при экспорте.
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Получает угол конуса затухания (в градусах).

**Returns:**
double — угол конуса падения (в градусах).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Получает расстояние до дальней плоскости фрустума.

**Returns:**
double — расстояние дальней плоскости усечения.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Получает угол конуса горячей зоны (в градусах).

**Returns:**
double — угол конуса горячей зоны (в градусах).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Получает интенсивность света, значение по умолчанию — 100

**Returns:**
double — интенсивность света, значение по умолчанию 100
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Получает тип света

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Получает линейное затухание для расчёта общего затухания света

**Returns:**
double — линейное затухание для расчёта общего затухания света
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Получает интересующую позицию, на которую смотрит камера.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Получает расстояние до ближней плоскости усечения.

**Returns:**
double — расстояние ближней плоскости усечения.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Получает высоту, когда усечение в ортографической проекции.

**Returns:**
double — высота при ортографической проекции усечения.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - все родительские узлы, объект может быть привязан к нескольким родительским узлам для инстанцирования геометрии
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Получает коллекцию всех свойств.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Получить значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |

**Returns:**
java.lang.Object - Значение найденного свойства
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Получает квадратичное затухание для расчёта общего затухания света

**Returns:**
double — квадратичное затухание для расчёта общего затухания света
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Получает режим ориентации усечения. Это свойство работает только когда [getTarget](../../com.aspose.threed/frustum\#getTarget) равно null. Если значение равно [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), направление всегда вычисляется свойством [getLookAt](../../com.aspose.threed/frustum\#getLookAt). В противном случае [getLookAt](../../com.aspose.threed/frustum\#getLookAt) всегда вычисляется через [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Получает сцену, к которой принадлежит этот объект

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Получает цвет тени.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Получает цель, на которую смотрит камера. Если пользователь поддерживает это свойство, оно должно предшествовать свойству [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Получает направление вверх камеры

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Удаляет динамическое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Удалить указанное свойство, определяемое по имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Устанавливает соотношение сторон усечения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Устанавливает, может ли текущий экземпляр света освещать другие объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Устанавливает, может ли свет отбрасывать тени на другие объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Устанавливает цвет света

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Устанавливает постоянное затухание для расчёта общего затухания света

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Устанавливает направление, в котором смотрит камера. Изменения этого свойства также влияют на [getLookAt](../../com.aspose.threed/frustum\#getLookAt) и [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Устанавливает, следует ли исключать эту сущность при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Устанавливает угол затухания конуса (в градусах).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Устанавливает расстояние до дальней плоскости усечения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Устанавливает угол конуса горячей зоны (в градусах).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Устанавливает интенсивность света, значение по умолчанию — 100

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Устанавливает тип света

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Новое значение |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Устанавливает линейное затухание для расчёта общего затухания света

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Устанавливает интересующую позицию, на которую смотрит камера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Устанавливает расстояние ближней плоскости усечения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Устанавливает высоту при ортографической проекции усечения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Новое значение |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Устанавливает значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |
| значение | java.lang.Object | Значение свойства |

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Устанавливает квадратичное затухание для расчёта общего затухания света

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Устанавливает режим ориентации усечения. Это свойство работает только когда [getTarget](../../com.aspose.threed/frustum\#getTarget) равно null. Если значение равно [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), направление всегда вычисляется свойством [getLookAt](../../com.aspose.threed/frustum\#getLookAt). В противном случае [getLookAt](../../com.aspose.threed/frustum\#getLookAt) всегда вычисляется через [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Новое значение |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Устанавливает цвет тени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Устанавливает цель, на которую смотрит камера. Если пользователь поддерживает это свойство, оно должно быть установлено до свойства [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Новое значение |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Устанавливает направление вверх камеры

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

