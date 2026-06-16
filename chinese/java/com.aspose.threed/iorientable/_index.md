---
title: "IOrientable"
second_title: "Aspose.3D for Java API 参考"
description: "可定向实体应实现此接口。"
type: docs
weight: 246
url: /zh/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

可定向实体应实现此接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 获取实体所看的方向。 |
| [getTarget()](#getTarget--) | 获取实体所看的目标。 |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | 设置实体所看的方向。 |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | 设置实体所看的目标。 |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


获取实体所看的方向。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


获取实体所看的目标。

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


设置实体所看的方向。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


设置实体所看的目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新值 |

