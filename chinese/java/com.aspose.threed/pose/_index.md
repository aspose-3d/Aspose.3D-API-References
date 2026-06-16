---
title: "Pose"
second_title: "Aspose.3D for Java API 参考"
description: "姿势用于在几何体蒙皮时存储变换矩阵。"
type: docs
weight: 135
url: /zh/java/com.aspose.threed/pose/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Pose extends A3DObject
```

当几何体进行蒙皮时，姿势用于存储变换矩阵。姿势是一组 [BonePose](../../com.aspose.threed/bonepose)，每个 [BonePose](../../com.aspose.threed/bonepose) 保存骨骼节点的具体变换信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Pose(String name)](#Pose-java.lang.String-) | 初始化 [Pose](../../com.aspose.threed/pose) 类的新实例。 |
| [Pose()](#Pose--) | 初始化 [Pose](../../com.aspose.threed/pose) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addBonePose(Node node, Matrix4 matrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | 为给定的骨骼节点保存姿势变换矩阵。 |
| [addBonePose(Node node, Matrix4 matrix, boolean localMatrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-) | 为给定的骨骼节点保存姿势变换矩阵。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBonePoses()](#getBonePoses--) | 获取所有 [BonePose](../../com.aspose.threed/bonepose)。 |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 获取名称。 |
| [getPoseType()](#getPoseType--) | 获取姿势的类型。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setPoseType(PoseType value)](#setPoseType-com.aspose.threed.PoseType-) | 设置姿势的类型。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pose(String name) {#Pose-java.lang.String-}
```
public Pose(String name)
```


初始化 [Pose](../../com.aspose.threed/pose) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |

### Pose() {#Pose--}
```
public Pose()
```


初始化 [Pose](../../com.aspose.threed/pose) 类的新实例。

### addBonePose(Node node, Matrix4 matrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public void addBonePose(Node node, Matrix4 matrix)
```


为给定的骨骼节点保存姿势变换矩阵。默认使用全局变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 骨骼节点。 |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | 变换矩阵。 |

### addBonePose(Node node, Matrix4 matrix, boolean localMatrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-}
```
public void addBonePose(Node node, Matrix4 matrix, boolean localMatrix)
```


为给定的骨骼节点保存姿势变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 骨骼节点。 |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | 变换矩阵。 |
| `localMatrix` | 布尔 | 如果设置为  true  则表示使用局部矩阵，否则表示使用全局矩阵。 |

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBonePoses() {#getBonePoses--}
```
public List<BonePose> getBonePoses()
```


获取所有 [BonePose](../../com.aspose.threed/bonepose)。

**Returns:**
java.util.List<com.aspose.threed.BonePose> - 全部 [BonePose](../../com.aspose.threed/bonepose)。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getPoseType() {#getPoseType--}
```
public PoseType getPoseType()
```


获取姿势的类型。

**Returns:**
[PoseType](../../com.aspose.threed/posetype) - the type of the pose.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
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


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setPoseType(PoseType value) {#setPoseType-com.aspose.threed.PoseType-}
```
public void setPoseType(PoseType value)
```


设置姿势的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PoseType](../../com.aspose.threed/posetype) | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

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

