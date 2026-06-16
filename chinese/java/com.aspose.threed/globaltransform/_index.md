---
title: "GlobalTransform"
second_title: "Aspose.3D for Java API 参考"
description: "全局变换类似于，但它是不可变的，同时表示最终评估的变换。"
type: docs
weight: 72
url: /zh/java/com.aspose.threed/globaltransform/
---

**Inheritance:**
java.lang.Object
```
public class GlobalTransform
```

全局变换类似于 [Transform](../../com.aspose.threed/transform)，但它是不可变的，同时表示最终评估的变换。评估全局变换时使用右手坐标系 **示例：** 以下代码展示了如何读取节点的全局变换

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.print("The box's position in world coordinate is %s", global.getTranslation());
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | 获取以欧拉角表示的旋转，单位为度 |
| [getRotation()](#getRotation--) | 获取以四元数表示的旋转。 |
| [getScale()](#getScale--) | 获取缩放 |
| [getTransformMatrix()](#getTransformMatrix--) | 获取变换矩阵。 |
| [getTranslation()](#getTranslation--) | 获取平移 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getEulerAngles() {#getEulerAngles--}
```
public Vector3 getEulerAngles()
```


获取以欧拉角表示的旋转，单位为度

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("EulerAngles = %s", tr.getEulerAngles());
```
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


获取以四元数表示的旋转。

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Rotation = %s", tr.getRotation());
```
### getScale() {#getScale--}
```
public Vector3 getScale()
```


获取缩放

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scale **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Scale = %s", tr.getScale());
```
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


获取变换矩阵。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Matrix = %s", tr.getTransformMatrix());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


获取平移

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Scene scene = Scene.fromFile("test.fbx");
     var tr = scene.getRootNode().getGlobalTransform();
     System.out.printf("Translation = %s", tr.getTranslation());
```
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

