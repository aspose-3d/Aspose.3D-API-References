---
title: IOrientable
second_title: Справочник API Aspose.3D для Java
description: Ориентируемые сущности должны реализовать этот интерфейс.
type: docs
weight: 246
url: /ru/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Ориентируемые сущности должны реализовать этот интерфейс.
## Методы

| Метод | Описание |
| --- | --- |
| [getDirection()](#getDirection--) | Получает направление, в котором смотрит объект. |
| [getTarget()](#getTarget--) | Получает цель, на которую смотрит объект. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Устанавливает направление, в котором смотрит объект. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Устанавливает цель, на которую смотрит объект. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Получает направление, в котором смотрит объект.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Получает цель, на которую смотрит объект.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Устанавливает направление, в котором смотрит объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Устанавливает цель, на которую смотрит объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Новое значение |

