---
title: 変換
second_title: Aspose.3D for Java API リファレンス
description: 変換は、オブジェクトの平行移動/スケール/回転または変換行列へのアクセスを最小コストで可能にする情報を含みます。これはローカル変換で使用されます。
type: docs
weight: 190
url: /ja/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

変換は、オブジェクトの平行移動/スケール/回転または変換行列へのアクセスを最小コストで可能にする情報を含みます。これはローカル変換で使用されます。 **Example:** 以下のコードはノードの変換を変更する方法を示しています。

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | オイラー角（度）で表された回転を取得します |
| [getGeometricRotation()](#getGeometricRotation--) | 幾何学的なオイラー回転（度単位）を取得します。 |
| [getGeometricScaling()](#getGeometricScaling--) | 幾何学的なスケーリングを取得します。 |
| [getGeometricTranslation()](#getGeometricTranslation--) | 幾何学的な平行移動を取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getPostRotation()](#getPostRotation--) | 度で表されたポストローテーションを取得します |
| [getPreRotation()](#getPreRotation--) | 度で表されたプリローテーションを取得します |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getRotation()](#getRotation--) | クォータニオンで表された回転を取得します。 |
| [getRotationOffset()](#getRotationOffset--) | 回転オフセットを取得します |
| [getRotationPivot()](#getRotationPivot--) | 回転ピボットを取得します |
| [getScaling()](#getScaling--) | スケーリングを取得します |
| [getScalingOffset()](#getScalingOffset--) | スケーリングオフセットを取得します |
| [getScalingPivot()](#getScalingPivot--) | スケーリングピボットを取得します |
| [getTransformMatrix()](#getTransformMatrix--) | 変換行列を取得します。 |
| [getTranslation()](#getTranslation--) | 平行移動を取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | 回転をオイラー角（度）で設定します |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | 現在の変換のオイラー角を度単位で設定します。 |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | ジオメトリックオイラー回転を設定します（単位は度）。 |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | ジオメトリックオイラー回転を設定します（単位は度）。 |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | ジオメトリックスケーリングを設定します。 |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | ジオメトリックスケーリングを設定します。 |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | ジオメトリック平行移動を設定します。 |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | ジオメトリック平行移動を設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | ポストローテーションを度単位で設定します。 |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | ポストローテーションを度単位で設定します **例:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | プリローテーションを度単位で設定します。 |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | プリローテーションを度単位で設定します **例:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | クォータニオンで表現された回転を設定します。 |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | 現在の変換の回転（クォータニオン成分として）を設定します。 |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | 回転オフセットを設定します。 |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | 回転ピボットを設定します。 |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | 現在の変換のスケールを設定します。 |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | スケーリングを設定します。 |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | スケーリングオフセットを設定します。 |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | スケーリングピボットを設定します。 |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | 変換行列を設定します。 |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | 平行移動を設定します。 |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | 現在の変換の平行移動を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


オイラー角（度）で表された回転を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
```
### getGeometricRotation() {#getGeometricRotation--}
```
public Vector3 getGeometricRotation()
```


ジオメトリックオイラー回転（度単位）を取得します。ジオメトリック変換は、アタッチされたエンティティのみに影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリック変換をエクスポートする際には、ローカル変換としてマージされます。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


ジオメトリスケーリングを取得します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric scaling. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
```
### getGeometricTranslation() {#getGeometricTranslation--}
```
public Vector3 getGeometricTranslation()
```


ジオメトリ平行移動を取得します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric translation. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
```
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


度で表されたポストローテーションを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
```
### getPreRotation() {#getPreRotation--}
```
public Vector3 getPreRotation()
```


度で表されたプリローテーションを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
```
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
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


クォータニオンで表された回転を取得します。

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
```
### getRotationOffset() {#getRotationOffset--}
```
public Vector3 getRotationOffset()
```


回転オフセットを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


回転ピボットを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


スケーリングを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling **Example:**

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
```
### getScalingOffset() {#getScalingOffset--}
```
public Vector3 getScalingOffset()
```


スケーリングオフセットを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


スケーリングピボットを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


変換行列を取得します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Remarks:** Assign on this will reset the [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) and [getRotation](../../com.aspose.threed/transform\#getRotation), the [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) and [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) will not be affected. **Example:**

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


平行移動を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
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
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


回転をオイラー角（度）で設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


現在の変換のオイラー角（度）を設定します。**Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricRotation(Vector3 value) {#setGeometricRotation-com.aspose.threed.Vector3-}
```
public void setGeometricRotation(Vector3 value)
```


ジオメトリオイラーローテーション（度単位）を設定します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


ジオメトリオイラーローテーション（度単位）を設定します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。**Example:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricScaling(Vector3 value) {#setGeometricScaling-com.aspose.threed.Vector3-}
```
public void setGeometricScaling(Vector3 value)
```


ジオメトリスケーリングを設定します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


ジオメトリスケーリングを設定します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。**Example:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricTranslation(Vector3 value) {#setGeometricTranslation-com.aspose.threed.Vector3-}
```
public void setGeometricTranslation(Vector3 value)
```


ジオメトリ平行移動を設定します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


ジオメトリ平行移動を設定します。ジオメトリ変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式にジオメトリ変換をエクスポートする際、ローカル変換としてマージされます。**Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


ポストローテーションを度単位で設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


ポストローテーションを度単位で設定します **例:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setPreRotation(Vector3 value) {#setPreRotation-com.aspose.threed.Vector3-}
```
public void setPreRotation(Vector3 value)
```


プリローテーションを度単位で設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


プリローテーションを度単位で設定します **例:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


クォータニオンで表現された回転を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


現在の変換の回転（クォータニオン成分）を設定します。**Example:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rw | double |  |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setRotationOffset(Vector3 value) {#setRotationOffset-com.aspose.threed.Vector3-}
```
public void setRotationOffset(Vector3 value)
```


回転オフセットを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


回転ピボットを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


現在の変換のスケールを設定します。**Example:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setScaling(Vector3 value) {#setScaling-com.aspose.threed.Vector3-}
```
public void setScaling(Vector3 value)
```


スケーリングを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


スケーリングオフセットを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


スケーリングピボットを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


変換行列を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | 新しい値 **Remarks:** これに代入すると、[getTranslation](../../com.aspose.threed/transform\#getTranslation)、[getScaling](../../com.aspose.threed/transform\#getScaling)、[getRotation](../../com.aspose.threed/transform\#getRotation) がリセットされ、[getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation)、[getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling)、[getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) は影響を受けません。**Example:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


平行移動を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


現在の変換の平行移動を設定します。**Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

