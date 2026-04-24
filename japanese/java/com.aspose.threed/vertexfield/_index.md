---
title: VertexField
second_title: Aspose.3D for Java API リファレンス
description: Vertexs フィールドのメモリレイアウトの説明。
type: docs
weight: 227
url: /ja/java/com.aspose.threed/vertexfield/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public class VertexField implements Comparable<VertexField>
```

頂点のフィールドメモリレイアウトの説明。
## Methods

| Method | 説明 |
| --- | --- |
| [compareTo(VertexField other)](#compareTo-com.aspose.threed.VertexField-) | このインスタンスを指定されたオブジェクトと比較し、相対的な値の指標を返します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスと、[VertexField](../../com.aspose.threed/vertexfield) オブジェクトでもある指定されたオブジェクトが同じ値かどうかを判断します。 |
| [getAlias()](#getAlias--) | フィールドのエイリアス。 |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | このフィールドのデータ型。 |
| [getIndex()](#getIndex--) | 同じセマンティクスを持つ頂点レイアウト内におけるこのフィールドのインデックス。 |
| [getOffset()](#getOffset--) | このフィールドのバイト単位のオフセット。 |
| [getSemantic()](#getSemantic--) | このフィールドの使用セマンティクス。 |
| [getSize()](#getSize--) | このフィールドのバイト単位のサイズ |
| [hashCode()](#hashCode--) | この文字列のハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | [VertexField](../../com.aspose.threed/vertexfield) の文字列表現を取得します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### compareTo(VertexField other) {#compareTo-com.aspose.threed.VertexField-}
```
public int compareTo(VertexField other)
```


このインスタンスを指定されたオブジェクトと比較し、相対的な値の指標を返します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| other | [VertexField](../../com.aspose.threed/vertexfield) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスと、[VertexField](../../com.aspose.threed/vertexfield) オブジェクトでもある指定されたオブジェクトが同じ値かどうかを判断します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlias() {#getAlias--}
```
public String getAlias()
```


フィールドのエイリアス。

**Returns:**
java.lang.String - フィールドのエイリアス。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataType() {#getDataType--}
```
public int getDataType()
```


このフィールドのデータ型。

**Returns:**
int - このフィールドのデータ型。
### getIndex() {#getIndex--}
```
public int getIndex()
```


同じセマンティクスを持つ頂点レイアウト内におけるこのフィールドのインデックス。

**Returns:**
int - 同じセマンティクスを持つ頂点レイアウト内におけるこのフィールドのインデックス。
### getOffset() {#getOffset--}
```
public int getOffset()
```


このフィールドのバイト単位のオフセット。

**Returns:**
int - このフィールドのバイト単位のオフセット。
### getSemantic() {#getSemantic--}
```
public VertexFieldSemantic getSemantic()
```


このフィールドの使用セマンティクス。

**Returns:**
[VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) - The usage semantic of this field.
### getSize() {#getSize--}
```
public int getSize()
```


このフィールドのバイト単位のサイズ

**Returns:**
int - このフィールドのバイト単位のサイズ
### hashCode() {#hashCode--}
```
public int hashCode()
```


この文字列のハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


[VertexField](../../com.aspose.threed/vertexfield) の文字列表現を取得します

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

