---
title: AnimationClip
second_title: Aspose.3D for Java API リファレンス
description: アニメーションクリップはアニメーションのコレクションです。
type: docs
weight: 14
url: /ja/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)、[com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

Animation clip はアニメーションのコレクションです。シーンは 1 つ以上のアニメーションクリップを持つことができます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | [AnimationClip](../../com.aspose.threed/animationclip) クラスの新しいインスタンスを初期化します。 |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | [AnimationClip](../../com.aspose.threed/animationclip) クラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | 現在のクリップ上でアニメーションノードを作成し登録するためのショートハンド関数です。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getAnimations()](#getAnimations--) | クリップ内に含まれるアニメーションを取得します。 |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | このアニメーションクリップの説明を取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getStart()](#getStart--) | クリップの開始時刻（秒）を取得します。 |
| [getStop()](#getStop--) | クリップの終了時刻（秒）を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setDescription(String value)](#setDescription-java.lang.String-) | このアニメーションクリップの説明を設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setStart(double value)](#setStart-double-) | クリップの開始時刻を秒単位で設定します。 |
| [setStop(double value)](#setStop-double-) | クリップの終了時刻を秒単位で設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


[AnimationClip](../../com.aspose.threed/animationclip) クラスの新しいインスタンスを初期化します。

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


[AnimationClip](../../com.aspose.threed/animationclip) クラスの新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


現在のクリップ上でアニメーションノードを作成し登録するためのショートハンド関数です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| nodeName | java.lang.String | 新しいアニメーションノードの名前 |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
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
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


クリップ内に含まれるアニメーションを取得します。

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - クリップ内に含まれるアニメーション。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


このアニメーションクリップの説明を取得します。

**Returns:**
java.lang.String - このアニメーションクリップの説明
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
### getScene() {#getScene--}
```
public Scene getScene()
```


このオブジェクトが属するシーンを取得します

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


クリップの開始時刻（秒）を取得します。

**Returns:**
double - クリップの開始時刻（秒）
### getStop() {#getStop--}
```
public double getStop()
```


クリップの終了時刻（秒）を取得します。

**Returns:**
double - クリップの終了時刻（秒）
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
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


このアニメーションクリップの説明を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

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

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


クリップの開始時刻を秒単位で設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


クリップの終了時刻を秒単位で設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

