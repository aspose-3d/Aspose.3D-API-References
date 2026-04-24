---
title: IOrientable
second_title: Aspose.3D for Java API リファレンス
description: 向きを持つエンティティはこのインターフェイスを実装しなければなりません。
type: docs
weight: 246
url: /ja/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

向きを持つエンティティはこのインターフェイスを実装しなければなりません。
## Methods

| Method | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | エンティティが向いている方向を取得します。 |
| [getTarget()](#getTarget--) | エンティティが見ている対象を取得します。 |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | エンティティが向く方向を設定します。 |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | エンティティが見ている対象を設定します。 |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


エンティティが向いている方向を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


エンティティが見ている対象を取得します。

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


エンティティが向く方向を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


エンティティが見ている対象を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新しい値 |

