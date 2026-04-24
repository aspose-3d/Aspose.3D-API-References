---
title: BonePose
second_title: Aspose.3D for Java API リファレンス
description: 骨ノードの変換行列を含みます
type: docs
weight: 21
url: /ja/java/com.aspose.threed/bonepose/
---

**Inheritance:**
java.lang.Object
```
public class BonePose
```

[BonePose](../../com.aspose.threed/bonepose) は骨ノードの変換行列を含みます
## Constructors

| Constructor | 説明 |
| --- | --- |
| [BonePose()](#BonePose--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | 現在のポーズにおけるノードの変換行列を取得します。 |
| [getNode()](#getNode--) | シーンノードを取得し、スキンされたスケルトンノードを指します。 |
| [hashCode()](#hashCode--) |  |
| [isLocal()](#isLocal--) | ローカル座標で定義されているかを取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLocal(boolean value)](#setLocal-boolean-) | ローカル座標で定義されているかを設定します。 |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | 現在のポーズにおけるノードの変換行列を設定します。 |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | シーンノードを設定し、スキンされたスケルトンノードを指します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BonePose() {#BonePose--}
```
public BonePose()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


現在のポーズにおけるノードの変換行列を取得します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node in current pose.
### getNode() {#getNode--}
```
public Node getNode()
```


シーンノードを取得し、スキンされたスケルトンノードを指します。

**Returns:**
[Node](../../com.aspose.threed/node) - the scene node, points to a skinned skeleton node
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLocal() {#isLocal--}
```
public boolean isLocal()
```


ローカル座標で定義されているかを取得します。

**Returns:**
boolean - 行列がローカル座標で定義されているか
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLocal(boolean value) {#setLocal-boolean-}
```
public void setLocal(boolean value)
```


ローカル座標で定義されているかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


現在のポーズにおけるノードの変換行列を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新しい値 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


シーンノードを設定し、スキンされたスケルトンノードを指します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新しい値 |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

