---
title: Pose
second_title: Aspose.3D for Java API リファレンス
description: ジオメトリがスキンされたときに変換行列を保存するためにポーズが使用されます。
type: docs
weight: 135
url: /ja/java/com.aspose.threed/pose/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Pose extends A3DObject
```

The pose is used to store transformation matrix when the geometry is skinned. The pose is a set of [BonePose](../../com.aspose.threed/bonepose), each [BonePose](../../com.aspose.threed/bonepose) saves the concrete transformation information of the bone node.
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Pose(String name)](#Pose-java.lang.String-) | Initializes a new instance of the [Pose](../../com.aspose.threed/pose) class. |
| [Pose()](#Pose--) | Initializes a new instance of the [Pose](../../com.aspose.threed/pose) class. |
## Methods

| Method | 説明 |
| --- | --- |
| [addBonePose(Node node, Matrix4 matrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Saves pose transformation matrix for the given bone node. |
| [addBonePose(Node node, Matrix4 matrix, boolean localMatrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-) | Saves pose transformation matrix for the given bone node. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBonePoses()](#getBonePoses--) | Gets all [BonePose](../../com.aspose.threed/bonepose). |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 名前を取得します。 |
| [getPoseType()](#getPoseType--) | Gets the type of the pose. |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setPoseType(PoseType value)](#setPoseType-com.aspose.threed.PoseType-) | Sets the type of the pose. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pose(String name) {#Pose-java.lang.String-}
```
public Pose(String name)
```


Initializes a new instance of the [Pose](../../com.aspose.threed/pose) class.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |

### Pose() {#Pose--}
```
public Pose()
```


Initializes a new instance of the [Pose](../../com.aspose.threed/pose) class.

### addBonePose(Node node, Matrix4 matrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public void addBonePose(Node node, Matrix4 matrix)
```


指定されたボーンノードのポーズ変換行列を保存します。グローバル変換行列が暗黙的に使用されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | ボーンノード。 |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | 変換行列。 |

### addBonePose(Node node, Matrix4 matrix, boolean localMatrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-}
```
public void addBonePose(Node node, Matrix4 matrix, boolean localMatrix)
```


Saves pose transformation matrix for the given bone node.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | ボーンノード。 |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | 変換行列。 |
| `localMatrix` | boolean | true に設定するとローカル行列を使用することを意味し、そうでなければグローバル行列を使用することを意味します。 |

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty により作成）またはネイティブプロパティ（名前で識別）になる可能性があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| propertyName | java.lang.String | プロパティ名。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBonePoses() {#getBonePoses--}
```
public List<BonePose> getBonePoses()
```


Gets all [BonePose](../../com.aspose.threed/bonepose).

**Returns:**
java.util.List<com.aspose.threed.BonePose> - すべての [BonePose](../../com.aspose.threed/bonepose)。
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


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getPoseType() {#getPoseType--}
```
public PoseType getPoseType()
```


Gets the type of the pose.

**Returns:**
[PoseType](../../com.aspose.threed/posetype) - the type of the pose.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


すべてのプロパティのコレクションを取得します。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


指定されたプロパティの値を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |

**Returns:**
java.lang.Object - 見つかったプロパティの値
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


動的プロパティを削除します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


名前で識別される指定されたプロパティを削除します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setPoseType(PoseType value) {#setPoseType-com.aspose.threed.PoseType-}
```
public void setPoseType(PoseType value)
```


Sets the type of the pose.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [PoseType](../../com.aspose.threed/posetype) | 新しい値 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


指定されたプロパティの値を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |
| 値 | java.lang.Object | プロパティの値 |

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

