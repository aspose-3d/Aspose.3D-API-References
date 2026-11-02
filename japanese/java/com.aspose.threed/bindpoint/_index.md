---
title: "BindPoint"
second_title: "Aspose.3D for Java API リファレンス"
description: "通常、オブジェクトのプロパティ上に作成されます。いくつかのプロパティタイプは複数のコンポーネントフィールド（例: Vector3 フィールド）を含み、各コンポーネントフィールドごとにチャンネルが生成され、フィールドはチャンネルを介して1つまたは複数のキーフレームシーケンスインスタンスに接続されます。"
type: docs
weight: 19
url: /ja/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

通常、[BindPoint](../../com.aspose.threed/bindpoint) はオブジェクトのプロパティ上に作成されます。いくつかのプロパティタイプは複数のコンポーネントフィールド（例: Vector3 フィールド）を含み、[BindPoint](../../com.aspose.threed/bindpoint) は各コンポーネントフィールドごとにチャンネルを生成し、フィールドをチャンネルを介して1つまたは複数のキーフレームシーケンスインスタンスに接続します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | 新しい [BindPoint](../../com.aspose.threed/bindpoint) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | 指定されたチャンネルプロパティを追加します。 |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | 指定されたチャンネルプロパティを追加します。 |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | キーフレームシーケンスを指定されたチャンネルにバインドします。 |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | 新しい曲線を作成し、曲線マッピングの最初のチャンネルに接続します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [get(String channelName)](#get-java.lang.String-) | 指定された名前でチャンネルを取得します。 |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | 指定された名前でチャンネルを取得します。 |
| [getChannelsCount()](#getChannelsCount--) | このアニメーション曲線マッピングで定義されたプロパティチャンネルの総数を取得します。 |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | 指定されたチャンネル内の最初のキーフレームシーケンスを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty()](#getProperty--) | CurveMapping に関連付けられたプロパティを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 指定された名前で識別されるプロパティを削除します |
| [resetChannels()](#resetChannels--) | このアニメーション曲線マッピングのプロパティチャンネルを空にします。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | CurveMapping に関連付けられたプロパティを取得します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) | オブジェクトを文字列に変換します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


新しい [BindPoint](../../com.aspose.threed/bindpoint) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | アニメーションを含むシーンです。 |
| prop | [Property](../../com.aspose.threed/property) | プロパティ。 |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


指定されたチャンネルプロパティを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | 名前。 |
| type | java.lang.Class<?> | タイプ。 |
| 値 | java.lang.Object | 値。 |

**Returns:**
boolean - チャンネルが追加された場合は true、そうでない場合は false。
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


指定されたチャンネルプロパティを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | 名前。 |
| 値 | java.lang.Object | 値。 |

**Returns:**
boolean - チャンネルが追加された場合は true、そうでない場合は false。
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


キーフレームシーケンスを指定されたチャンネルにバインドします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelName | java.lang.String | キーフレームシーケンスがバインドされるチャンネルはどれか。 |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | バインドするキーフレームシーケンス。 |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


新しい曲線を作成し、曲線マッピングの最初のチャンネルに接続します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | 新しいシーケンスの名前です。 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| propertyName | java.lang.String | プロパティ名。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


指定された名前でチャンネルを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelName | java.lang.String | チャンネル名。 |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


指定された名前でチャンネルを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelName | java.lang.String | 検索するチャンネル名。 |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


このアニメーション曲線マッピングで定義されたプロパティチャンネルの総数を取得します。

**Returns:**
int - チャネル数。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


指定されたチャンネル内の最初のキーフレームシーケンスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelName | java.lang.String | 検索するチャンネル名。 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前。
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


すべてのプロパティのコレクションを取得します。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty() {#getProperty--}
```
public Property getProperty()
```


CurveMapping に関連付けられたプロパティを取得します。

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


指定されたプロパティの値を取得します

**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 削除するプロパティはどれですか |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


指定された名前で識別されるプロパティを削除します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 削除するプロパティはどれですか |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


このアニメーション曲線マッピングのプロパティチャンネルを空にします。

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


CurveMapping に関連付けられたプロパティを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | 新しい値 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


指定されたプロパティの値を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |
| 値 | java.lang.Object | プロパティの値 |

### toString() {#toString--}
```
public String toString()
```


オブジェクトを文字列に変換します

**Returns:**
java.lang.String - オブジェクト文字列
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

