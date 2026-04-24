---
title: ボーン
second_title: Aspose.3D for Java API リファレンス
description: ボーンは、ジオメトリの制御点のサブセットを定義し、各制御点のブレンドウェイトを定義します。
type: docs
weight: 20
url: /ja/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

ボーンは、ジオメトリの制御点のサブセットを定義し、各制御点のブレンドウェイトを定義します。 [Bone](../../com.aspose.threed/bone) オブジェクトは直接使用できず、[SkinDeformer](../../com.aspose.threed/skindeformer) インスタンスを使用してジオメトリを変形させ、[SkinDeformer](../../com.aspose.threed/skindeformer) には複数のボーンがセットされており、各ボーンはノードにリンクされています。NOTE: ジオメトリの制御点は複数のボーンにバインドできる場合があります。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | [Bone](../../com.aspose.threed/bone) クラスの新しいインスタンスを初期化します。 |
| [Bone()](#Bone--) | [Bone](../../com.aspose.threed/bone) クラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [get(int index)](#get-int-) | 指定された制御点のブレンドウェイトを取得します |
| [getBoneTransform()](#getBoneTransform--) | ボーンの変換行列を取得します。 |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | ボーンのリンクモードは、階層構造内でボーンが親ボーンに接続またはリンクされる方法を指します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getNode()](#getNode--) | ノードを取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getTransform()](#getTransform--) | ボーンを含むノードの変換行列を取得します。 |
| [getWeight(int index)](#getWeight-int-) | インデックスで指定された制御点の重みを取得します |
| [getWeightCount()](#getWeightCount--) | 重みの数を取得します。この数は [setWeight](../../com.aspose.threed/bone\#setWeight) によって自動的に拡張されます |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [set(int index, double value)](#set-int-double-) | 指定された制御点のブレンド重みを設定します |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | ボーンの変換行列を設定します。 |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | ボーンのリンクモードは、階層構造内でボーンが親ボーンに接続またはリンクされる方法を指します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | ノードを設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | ボーンを含むノードの変換行列を設定します。 |
| [setWeight(int index, double weight)](#setWeight-int-double-) | インデックスで指定された制御点の重みを設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


[Bone](../../com.aspose.threed/bone) クラスの新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前。 |

### Bone() {#Bone--}
```
public Bone()
```


[Bone](../../com.aspose.threed/bone) クラスの新しいインスタンスを初期化します。

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
### get(int index) {#get-int-}
```
public double get(int index)
```


指定された制御点のブレンドウェイトを取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int | 重みのインデックス |

**Returns:**
double - 重み
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


ボーンの変換行列を取得します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


ボーンのリンクモードは、階層構造内でボーンが親ボーンに接続またはリンクされる方法を指します。

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getNode() {#getNode--}
```
public Node getNode()
```


ノードを取得します。ボーンノードはスキンが接続されるボーンで、[SkinDeformer](../../com.aspose.threed/skindeformer) はボーンノードを使用して制御点の変位に影響を与えます。ボーンノードには通常 [Skeleton](../../com.aspose.threed/skeleton) が添付されていますが、必須ではありません。添付された [Skeleton](../../com.aspose.threed/skeleton) は、通常 DCC ソフトウェアがユーザーにスケルトンを表示するために使用されます。

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


ボーンを含むノードの変換行列を取得します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


インデックスで指定された制御点の重みを取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int | 制御点のインデックス |

**Returns:**
double - 指定インデックスの重み、またはインデックスが無効な場合は 0
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


重みの数を取得します。この数は [setWeight](../../com.aspose.threed/bone\#setWeight) によって自動的に拡張されます

**Returns:**
int - 重みの数、これは [setWeight](../../com.aspose.threed/bone\#setWeight) によって自動的に拡張されます
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


指定された制御点のブレンド重みを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int | 重みのインデックス |
| 値 | double | 新しい値 |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


ボーンの変換行列を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新しい値 |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


ボーンのリンクモードは、階層構造内でボーンが親ボーンに接続またはリンクされる方法を指します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


ノードを設定します。ボーンノードはスキンが接続されるボーンで、[SkinDeformer](../../com.aspose.threed/skindeformer) はボーンノードを使用して制御点の変位に影響を与えます。ボーンノードには通常 [Skeleton](../../com.aspose.threed/skeleton) が添付されていますが、必須ではありません。添付された [Skeleton](../../com.aspose.threed/skeleton) は、通常 DCC ソフトウェアがユーザーにスケルトンを表示するために使用されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新しい値 |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


ボーンを含むノードの変換行列を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 新しい値 |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


インデックスで指定された制御点の重みを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int | 制御点のインデックス |
| 重み | double | 新しい重み |

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

