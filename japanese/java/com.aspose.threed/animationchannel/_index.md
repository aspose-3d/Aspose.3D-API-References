---
title: AnimationChannel
second_title: Aspose.3D for Java API リファレンス
description: チャネルはプロパティのコンポーネントフィールドをキーフレームシーケンスの集合にマッピングします。
type: docs
weight: 13
url: /ja/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

チャネルはプロパティのコンポーネントフィールドをキーフレームシーケンスの集合にマッピングします。
## Methods

| Method | 説明 |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | 指定された値で新しいキー フレームを作成します |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | 指定された値で新しいキー フレームを作成します |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBindPoint()](#getBindPoint--) | この曲線を所有するプロパティ バインド ポイントを取得します |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | コンポーネントフィールドの型を取得します。 |
| [getDefaultValue()](#getDefaultValue--) | チャネルの Default 値を取得します。 |
| [getKeyFrames()](#getKeyFrames--) | この曲線のキー フレームを取得します。 |
| [getKeyframeSequence()](#getKeyframeSequence--) | このチャネル内の関連キーフレームシーケンスを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getPostBehavior()](#getPostBehavior--) | 最後のキー フレームの後にサンプリングされた値がどうなるかを示すポスト ビヘイビアを取得します。 |
| [getPreBehavior()](#getPreBehavior--) | 最初のキーの前にサンプリングされた値がどうなるかを示すプリ ビヘイビアを取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | すべてのキー フレームを走査する列挙子を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [reset()](#reset--) | すべてのキー フレームを削除し、ポスト/プリ ビヘイビアをリセットします。 |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | チャネルの Default 値を設定します。 |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | このチャネル内の関連キーフレームシーケンスを取得します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


指定された値で新しいキー フレームを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 時間 | double | 時間位置（秒で測定） |
| 値 | float | この時間位置の値 |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


指定された値で新しいキー フレームを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 時間 | double | 時間位置（秒で測定） |
| 値 | float | この時間位置の値 |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | このキー フレームの補間タイプ |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


この曲線を所有するプロパティ バインド ポイントを取得します

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


コンポーネントフィールドの型を取得します。

**Returns:**
java.lang.Class<?> - コンポーネントフィールドの型
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


チャネルの Default 値を取得します。チャネルに接続されたキーフレームシーケンスがない場合、アニメーション評価時にデフォルト値が使用されます。実際のシナリオ: アニメーションがノードの x 座標のみをアニメートし、y と z が変更されない場合、完全な平行移動評価時にデフォルト値が使用されます。

**Returns:**
java.lang.Object - チャネルの Default 値。チャネルにキーフレームシーケンスが接続されていない場合、アニメーション評価時にデフォルト値が使用されます。実際のシナリオ: アニメーションがノードの x 座標のみをアニメートし、y と z が変更されない場合、完全な平行移動評価時にデフォルト値が使用されます。
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


この曲線のキー フレームを取得します。

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - この曲線のキー フレーム。
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


このチャネル内の関連キーフレームシーケンスを取得します。

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


最後のキー フレームの後にサンプリングされた値がどうなるかを示すポスト ビヘイビアを取得します。

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


最初のキーの前にサンプリングされた値がどうなるかを示すプリ ビヘイビアを取得します。

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


すべてのキー フレームを走査する列挙子を取得します。

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


すべてのキー フレームを削除し、ポスト/プリ ビヘイビアをリセットします。

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


チャネルの Default 値を設定します。チャネルにキーフレームシーケンスが接続されていない場合、アニメーション評価時にデフォルト値が使用されます。実際のシナリオ: アニメーションがノードの x 座標のみをアニメートし、y と z が変更されない場合、完全な平行移動評価時にデフォルト値が使用されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object | 新しい値 |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


このチャネル内の関連キーフレームシーケンスを取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | 新しい値 |

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

