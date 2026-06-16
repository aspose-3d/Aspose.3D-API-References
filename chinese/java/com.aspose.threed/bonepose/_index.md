---
title: "BonePose"
second_title: "Aspose.3D for Java API 参考"
description: "该对象包含骨骼节点的变换矩阵"
type: docs
weight: 21
url: /zh/java/com.aspose.threed/bonepose/
---

**Inheritance:**
java.lang.Object
```
public class BonePose
```

该 [BonePose](../../com.aspose.threed/bonepose) 包含骨骼节点的变换矩阵
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BonePose()](#BonePose--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | 获取当前姿势下节点的变换矩阵。 |
| [getNode()](#getNode--) | 获取场景节点，指向一个蒙皮骨架节点。 |
| [hashCode()](#hashCode--) |  |
| [isLocal()](#isLocal--) | 获取矩阵是否在局部坐标系中定义。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLocal(boolean value)](#setLocal-boolean-) | 设置矩阵是否在局部坐标系中定义。 |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | 设置当前姿势下节点的变换矩阵。 |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | 设置场景节点，指向一个蒙皮骨架节点。 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


获取当前姿势下节点的变换矩阵。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node in current pose.
### getNode() {#getNode--}
```
public Node getNode()
```


获取场景节点，指向一个蒙皮骨架节点。

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


获取矩阵是否在局部坐标系中定义。

**Returns:**
boolean - 矩阵是否在局部坐标系中定义。
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


设置矩阵是否在局部坐标系中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


设置当前姿势下节点的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新值 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


设置场景节点，指向一个蒙皮骨架节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新值 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

