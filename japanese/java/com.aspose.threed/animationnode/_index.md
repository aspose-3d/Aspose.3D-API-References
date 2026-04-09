---
title: AnimationNode
second_title: Aspose.3D for Java API リファレンス
description: Aspose.3Ds はアニメーション階層をサポートし、各アニメーションは複数のアニメーションとアニメーションのキーフレーム定義で構成できます。
type: docs
weight: 15
url: /ja/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D はアニメーション階層をサポートし、各アニメーションは複数のアニメーションとアニメーションのキーフレーム定義で構成できます。 [AnimationNode](../../com.aspose.threed/animationnode) は時間経過に伴うプロパティ値の変換を定義します。例えば、アニメーションノードはノードの変換や他の [A3DObject](../../com.aspose.threed/a3dobject) オブジェクトの数値プロパティを制御するために使用できます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | [AnimationNode](../../com.aspose.threed/animationnode) クラスの新しいインスタンスを初期化します。 |
| [AnimationNode()](#AnimationNode--) | [AnimationNode](../../com.aspose.threed/animationnode) クラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | プロパティのデータ型に基づいて BindPoint を作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | ターゲットと名前でバインドポイントを検索します。 |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | 指定されたプロパティのアニメーションバインドポイントを取得します。 |
| [getBindPoints()](#getBindPoints--) | 現在のプロパティバインドポイントを取得します |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | 指定されたプロパティのキーフレームシーケンスを取得します。 |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | 指定されたプロパティとチャンネルのキーフレームシーケンスを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getSubAnimations()](#getSubAnimations--) | 現在のアニメーションの下にあるサブアニメーションノードを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


[AnimationNode](../../com.aspose.threed/animationnode) クラスの新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


[AnimationNode](../../com.aspose.threed/animationnode) クラスの新しいインスタンスを初期化します。

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


プロパティのデータ型に基づいて BindPoint を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | オブジェクト。 |
| propName | java.lang.String | プロパティ名。 |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


ターゲットと名前でバインドポイントを検索します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 検索するバインドポイントのターゲット。 |
| name | java.lang.String | 検索するバインドポイントの名前。 |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


指定されたプロパティのアニメーションバインドポイントを取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | バインドポイントを作成する対象オブジェクト。 |
| propName | java.lang.String | プロパティの名前。 |
| 作成 | boolean | true に設定された場合、バインドポイントが存在しない場合は作成します。 |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


現在のプロパティバインドポイントを取得します

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - 現在のプロパティバインドポイント
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


指定されたプロパティのキーフレームシーケンスを取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | キーフレームシーケンスを作成するインスタンス。 |
| propName | java.lang.String | プロパティの名前。 |
| 作成 | boolean | true に設定された場合、シーケンスが存在しない場合は作成します。 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


指定されたプロパティとチャンネルのキーフレームシーケンスを取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | キーフレームシーケンスを作成するインスタンス。 |
| propName | java.lang.String | プロパティの名前。 |
| channelName | java.lang.String | チャンネル名。 |
| 作成 | boolean | true に設定された場合、アニメーションシーケンスが存在しない場合は作成します。 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


現在のアニメーションの下にあるサブアニメーションノードを取得します。

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - 現在のアニメーションの下にあるサブアニメーションノード
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

