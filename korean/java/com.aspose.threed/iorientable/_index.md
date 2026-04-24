---
title: IOrientable
second_title: Aspose.3D for Java API 레퍼런스
description: 방향을 지정할 수 있는 엔티티는 이 인터페이스를 구현해야 합니다.
type: docs
weight: 246
url: /ko/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

방향을 지정할 수 있는 엔티티는 이 인터페이스를 구현해야 합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 엔티티가 바라보고 있는 방향을 가져옵니다. |
| [getTarget()](#getTarget--) | 엔티티가 바라보고 있는 대상을 가져옵니다. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | 엔티티가 바라보고 있는 방향을 설정합니다. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | 엔티티가 바라보고 있는 대상을 설정합니다. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


엔티티가 바라보고 있는 방향을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


엔티티가 바라보고 있는 대상을 가져옵니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


엔티티가 바라보고 있는 방향을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


엔티티가 바라보고 있는 대상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

