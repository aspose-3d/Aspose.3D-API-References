---
title: MorphTargetChannel
second_title: Aspose.3D for Java API リファレンス
description: MorphTargetChannel は  によってターゲットジオメトリを整理するために使用されます。
type: docs
weight: 107
url: /ja/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

[MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) によって MorphTargetChannel がターゲットジオメトリを整理するために使用されます。FBX のような一部のファイル形式は複数のチャネルを同時にサポートします。**備考:** 重みは 0 から 1.0 の間で、ターゲットのデフォルトの重みは 0.0 です。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) クラスの新しいインスタンスを初期化します。 |
| [MorphTargetChannel()](#MorphTargetChannel--) | [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | モーフターゲットのデフォルトウェイト。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | 指定されたジオメトリのウェイトを取得します |
| [getChannelWeight()](#getChannelWeight--) | このチャネルのデフォーマーウェイトを取得します。 |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 名前を取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getTargets()](#getTargets--) | チャネルに関連付けられたすべてのターゲットを取得します。 |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | 指定されたターゲットのウェイトを取得します。ターゲットがこのチャネルに属さない場合、デフォルト値0が返されます。 |
| [getWeights()](#getWeights--) | ターゲットジオメトリの完全なウェイト値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | 指定されたジオメトリのウェイトを設定します |
| [setChannelWeight(double value)](#setChannelWeight-double-) | このチャネルのデフォーマーウェイトを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | 指定されたターゲットのウェイトを設定します。デフォルト値は1で、範囲は0〜1の間である必要があります。 |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | 指定されたターゲットのウェイトを設定します。デフォルト値は1で、範囲は0〜1の間である必要があります。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


[MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) クラスの新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前。 |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


[MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) クラスの新しいインスタンスを初期化します。

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


モーフターゲットのデフォルトウェイト。

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


指定されたジオメトリのウェイトを取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | ターゲットジオメトリ。 |

**Returns:**
double - ウェイト
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


このチャネルのデフォーマーウェイトを取得します。ウェイトは0.0から1.0の間です。

**Returns:**
double - このチャネルのデフォーマーウェイト。ウェイトは0.0から1.0の間です。
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


チャネルに関連付けられたすべてのターゲットを取得します。

**Returns:**
java.util.List<com.aspose.threed.Shape> - チャネルに関連付けられたすべてのターゲット。
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


指定されたターゲットのウェイトを取得します。ターゲットがこのチャネルに属さない場合、デフォルト値0が返されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


ターゲットジオメトリの完全なウェイト値を取得します。

**Returns:**
java.util.List<java.lang.Double> - ターゲットジオメトリの完全なウェイト値。
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


指定されたジオメトリのウェイトを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | ターゲットジオメトリ。 |
| 値 | double | 新しい値 |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


このチャネルのデフォーマーウェイトを設定します。ウェイトは0.0から1.0の間です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


指定されたターゲットのウェイトを設定します。デフォルト値は1で、範囲は0〜1の間である必要があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


指定されたターゲットのウェイトを設定します。デフォルト値は1で、範囲は0〜1の間である必要があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| 重み | double |  |

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

