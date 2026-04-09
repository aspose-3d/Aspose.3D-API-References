---
title: MorphTargetDeformer
second_title: Aspose.3D for Java API リファレンス
description: MorphTargetDeformer は頂点単位のアニメーションを提供します。
type: docs
weight: 108
url: /ja/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)、[com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer は頂点ごとのアニメーションを提供します。MorphTargetDeformer はすべてのターゲットを [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) を介して整理し、各チャンネルは複数のターゲットを管理できます。モーフターゲットデフォーマーの一般的な使用例は、キャラクターに表情を適用することです。詳細は https://en.wikipedia.org/wiki/Morph\_target\_animation を参照してください。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | 新しい [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) クラスのインスタンスを初期化します。 |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | 新しい [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) クラスのインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | 指定されたジオメトリの重みを取得します。これは、チャンネルにアクセスせずにターゲットの重みを変更する簡易的な方法です。 |
| [getChannels()](#getChannels--) | このデフォーマーに含まれるすべてのチャンネルを取得します。 |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 名前を取得します。 |
| [getOwner()](#getOwner--) | このデフォーマーを所有するジオメトリを取得します |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | 指定されたジオメトリの重みを設定します。これは、チャンネルにアクセスせずにターゲットの重みを変更する簡易的な方法です。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


新しい [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前。 |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


新しい [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) クラスのインスタンスを初期化します。

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


指定されたジオメトリの重みを取得します。これは、チャンネルにアクセスせずにターゲットの重みを変更する簡易的な方法です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 対象ジオメトリ |

**Returns:**
double - ウェイト
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


このデフォーマーに含まれるすべてのチャンネルを取得します。

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - このデフォーマーに含まれるすべてのチャンネル
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
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


このデフォーマーを所有するジオメトリを取得します

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


指定されたジオメトリの重みを設定します。これは、チャンネルにアクセスせずにターゲットの重みを変更する簡易的な方法です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 対象ジオメトリ |
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

