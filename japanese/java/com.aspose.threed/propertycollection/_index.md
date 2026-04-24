---
title: PropertyCollection
second_title: Aspose.3D for Java API リファレンス
description: プロパティのコレクション
type: docs
weight: 140
url: /ja/java/com.aspose.threed/propertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class PropertyCollection implements Iterable<Property>
```

プロパティのコレクション
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String property)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [get(int idx)](#get-int-) | インデックスでプロパティを取得します。 |
| [get(String property)](#get-java.lang.String-) | プロパティ名でプロパティの値を取得します。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 動的プロパティを削除します。 |
| [set(String property, Object value)](#set-java.lang.String-java.lang.Object-) | プロパティ名でプロパティの値を設定します。 |
| [size()](#size--) | 宣言されたプロパティの数を取得します。 |
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
### findProperty(String property) {#findProperty-java.lang.String-}
```
public Property findProperty(String property)
```


プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty により作成）またはネイティブプロパティ（名前で識別）になる可能性があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(int idx) {#get-int-}
```
public Property get(int idx)
```


インデックスでプロパティを取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | プロパティの0ベースインデックス |

**Returns:**
[Property](../../com.aspose.threed/property) - the property by index.
### get(String property) {#get-java.lang.String-}
```
public Object get(String property)
```


プロパティ名でプロパティの値を取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティの名前 |

**Returns:**
java.lang.Object - プロパティの値
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<Property> iterator()
```


コレクションを反復する列挙子を返します。

**Returns:**
java.util.Iterator<com.aspose.threed.Property>
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


動的プロパティを削除します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### set(String property, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String property, Object value)
```


プロパティ名でプロパティの値を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティの名前 |
| 値 | java.lang.Object | 新しい値 |

### size() {#size--}
```
public int size()
```


宣言されたプロパティの数を取得します。

**Returns:**
int - 宣言されたプロパティの数。
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

