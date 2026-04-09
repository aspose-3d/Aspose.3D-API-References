---
title: VertexDeclaration
second_title: Aspose.3D for Java API リファレンス
description: カスタム定義された頂点構造体の宣言
type: docs
weight: 206
url: /ja/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

カスタム定義された頂点構造の宣言
## Constructors

| Constructor | 説明 |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | 新しい頂点フィールドを追加する |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | 新しい頂点フィールドを追加する |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | 新しい頂点フィールドを追加する |
| [clear()](#clear--) | すべてのフィールドをクリアする。 |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | このインスタンスを指定されたオブジェクトと比較し、相対的な値の指標を返します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスと、指定されたオブジェクト（これも [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) オブジェクトである必要があります）が同じ値かどうかを判断します。 |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | [Geometry](../../com.aspose.threed/geometry) のレイアウトに基づいて [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) を作成します。 |
| [get(int index)](#get-int-) | インデックスで [VertexField](../../com.aspose.threed/vertexfield) を取得します |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | この [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) で定義されたすべてのフィールドの数を取得します |
| [getSealed()](#getSealed--) | [TriMesh](../../com.aspose.threed/trimesg) に使用されたとき、[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) はシールドされ、これ以上の変更は許可されません。 |
| [getSize()](#getSize--) | 頂点構造体のバイト単位のサイズ。 |
| [hashCode()](#hashCode--) | この文字列のハッシュコードを返します。 |
| [iterator()](#iterator--) | このインスタンス内のすべての頂点フィールドを走査する列挙子を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) の文字列表現 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


新しい頂点フィールドを追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| dataType | int | 頂点フィールドのデータ型 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | このフィールドは何に使用されますか |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


新しい頂点フィールドを追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| dataType | int | 頂点フィールドのデータ型 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | このフィールドは何に使用されますか |
| インデックス | int | 同一フィールドのセマンティックのインデックス、-1 は自動生成です |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


新しい頂点フィールドを追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| dataType | int | 頂点フィールドのデータ型 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | このフィールドは何に使用されますか |
| インデックス | int | 同一フィールドのセマンティックのインデックス、-1 は自動生成です |
| エイリアス | java.lang.String | フィールドのエイリアス名 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


すべてのフィールドをクリアする。

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


このインスタンスを指定されたオブジェクトと比較し、相対的な値の指標を返します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスと、指定されたオブジェクト（これも [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) オブジェクトである必要があります）が同じ値かどうかを判断します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


[Geometry](../../com.aspose.threed/geometry) のレイアウトに基づいて [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | double 型の代わりに float を使用します |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


インデックスで [VertexField](../../com.aspose.threed/vertexfield) を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


この [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) で定義されたすべてのフィールドの数を取得します

**Returns:**
int - この [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) で定義されたすべてのフィールドの数
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


[TriMesh](../../com.aspose.threed/trimesg) に使用されたとき、[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) はシールドされ、これ以上の変更は許可されません。

**Returns:**
boolean - [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) は [TriMesh](../../com.aspose.threed/trimesh) に使用されるとシールされ、これ以上の変更は許可されません。
### getSize() {#getSize--}
```
public int getSize()
```


頂点構造体のバイト単位のサイズ。

**Returns:**
int - 頂点構造体のサイズ（バイト単位）です。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この文字列のハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


このインスタンス内のすべての頂点フィールドを走査する列挙子を取得します。

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - 列挙子
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


[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) の文字列表現

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

