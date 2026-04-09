---
title: Camera
second_title: Справочник API Aspose.3D для Java
description: Камера описывает точку зрения наблюдателя, смотрящего на сцену.
type: docs
weight: 28
url: /ru/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

Камера описывает точку зрения наблюдателя, смотрящего на сцену.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Camera()](#Camera--) | Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera). |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera). |
| [Camera(String name)](#Camera-java.lang.String-) | Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera). |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getApertureMode()](#getApertureMode--) | Получает режим диафрагмы камеры |
| [getAspect()](#getAspect--) | Получает соотношение сторон фрустума |
| [getAspectRatio()](#getAspectRatio--) | Получает соотношение сторон плоскости просмотра. |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Получает направление, в котором смотрит камера. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getFarPlane()](#getFarPlane--) | Получает расстояние до дальней плоскости фрустума. |
| [getFieldOfView()](#getFieldOfView--) | Получает поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) или [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | Получает горизонтальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | Получает вертикальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | Получает высоту плоскости просмотра в дюймах |
| [getLookAt()](#getLookAt--) | Получает интересующую позицию, на которую смотрит камера. |
| [getMagnification()](#getMagnification--) | Получает увеличение, используемое в ортографической камере |
| [getName()](#getName--) | Получает имя. |
| [getNearPlane()](#getNearPlane--) | Получает расстояние до ближней плоскости усечения. |
| [getOrthoHeight()](#getOrthoHeight--) | Получает высоту, когда усечение в ортографической проекции. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProjectionType()](#getProjectionType--) | Получает тип проекции камеры. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getRotationMode()](#getRotationMode--) | Получает режим ориентации усечения. Это свойство работает только когда [getTarget](../../com.aspose.threed/frustum\#getTarget) равно null. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getTarget()](#getTarget--) | Получает цель, на которую смотрит камера. |
| [getUp()](#getUp--) | Получает направление вверх камеры |
| [getWidth()](#getWidth--) | Получает ширину плоскости просмотра в дюймах |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Переместить камеру вперёд в её направлении или к цели. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Устанавливает режим диафрагмы камеры |
| [setAspect(double value)](#setAspect-double-) | Устанавливает соотношение сторон усечения |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Устанавливает соотношение сторон плоскости просмотра. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Устанавливает направление, в котором смотрит камера. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setFarPlane(double value)](#setFarPlane-double-) | Устанавливает расстояние до дальней плоскости усечения. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Устанавливает поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) или [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Устанавливает горизонтальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Устанавливает вертикальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | Устанавливает высоту плоскости просмотра в дюймах |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Устанавливает интересующую позицию, на которую смотрит камера. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Устанавливает увеличение, используемое в ортографической камере |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setNearPlane(double value)](#setNearPlane-double-) | Устанавливает расстояние ближней плоскости усечения. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Устанавливает высоту при ортографической проекции усечения. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Устанавливает тип проекции камеры. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Устанавливает режим ориентации усечения. Это свойство работает только когда [getTarget](../../com.aspose.threed/frustum\#getTarget) равно null. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Устанавливает цель, на которую смотрит камера. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Устанавливает направление вверх камеры |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину плоскости просмотра в дюймах |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera).

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Тип проекции. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Инициализирует новый экземпляр класса [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Тип проекции. |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Получает режим диафрагмы камеры

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Получает соотношение сторон фрустума

**Returns:**
double — соотношение сторон усечения
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Получает соотношение сторон плоскости просмотра.

**Returns:**
double - соотношение сторон плоскости просмотра.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Получает расстояние до дальней плоскости фрустума.

**Returns:**
double — расстояние дальней плоскости усечения.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Получает поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) или [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
double - поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) или [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Получает горизонтальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - горизонтальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Получает вертикальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - вертикальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает высоту плоскости просмотра в дюймах

**Returns:**
double - высота плоскости просмотра в дюймах
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Получает интересующую позицию, на которую смотрит камера.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Получает увеличение, используемое в ортографической камере

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Получает тип проекции камеры. По умолчанию используется перспективная проекция.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает ширину плоскости просмотра в дюймах

**Returns:**
double - ширина плоскости просмотра, измеренная в дюймах
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


Переместить камеру вперёд в её направлении или к цели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| расстояние | double | Как долго двигаться вперёд |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Устанавливает режим диафрагмы камеры

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Новое значение |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Устанавливает соотношение сторон усечения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Устанавливает соотношение сторон плоскости просмотра.

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Устанавливает расстояние до дальней плоскости усечения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Устанавливает поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) или [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Устанавливает горизонтальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Устанавливает вертикальное поле зрения камеры в градусах, это свойство используется только когда ApertureMode является [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Устанавливает высоту плоскости просмотра в дюймах

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

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Устанавливает увеличение, используемое в ортографической камере

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

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

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Устанавливает тип проекции камеры. По умолчанию используется перспективная проекция.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Новое значение |

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Устанавливает режим ориентации усечения. Это свойство работает только когда [getTarget](../../com.aspose.threed/frustum\#getTarget) равно null. Если значение равно [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), направление всегда вычисляется свойством [getLookAt](../../com.aspose.threed/frustum\#getLookAt). В противном случае [getLookAt](../../com.aspose.threed/frustum\#getLookAt) всегда вычисляется через [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Новое значение |

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

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает ширину плоскости просмотра в дюймах

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

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

