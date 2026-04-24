---
title: VertexElementPolygonGroup
second_title: Aspose.3D for Java API リファレンス
description: 指定された成分のポリゴングループを定義し、関連するポリゴンをまとめます。
type: docs
weight: 215
url: /ja/java/com.aspose.threed/vertexelementpolygongroup/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)、[com.aspose.threed.VertexElementIntsTemplate](../../com.aspose.threed/vertexelementintstemplate)
```
public class VertexElementPolygonGroup extends VertexElementIntsTemplate
```

指定された成分のポリゴングループを定義し、関連するポリゴンをまとめます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [VertexElementPolygonGroup()](#VertexElementPolygonGroup--) | [VertexElementPolygonGroup](../../com.aspose.threed/vertexelementpolygongroup) クラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [clear()](#clear--) | direct と index 配列からすべての要素を削除します。 |
| [clone(boolean withData)](#clone-boolean-) | 頂点要素をディープクローンします。 |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementIntsTemplate target)](#copyTo-com.aspose.threed.VertexElementIntsTemplate-) | 指定された要素にデータをコピーします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | 頂点データを取得します。 |
| [getIndices()](#getIndices--) | インデックスデータを取得します。 |
| [getMappingMode()](#getMappingMode--) | 要素のマッピング方法を取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getReferenceMode()](#getReferenceMode--) | 要素の参照方法を取得します。 |
| [getVertexElementType()](#getVertexElementType--) | [VertexElement](../../com.aspose.threed/vertexelement) の型を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(int[] data)](#setData-int---) | データをロードします。 |
| [setIndices(int[] data)](#setIndices-int---) | インデックスをロードします。 |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | 要素のマッピング方法を設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | 要素の参照方法を設定します。 |
| [toString()](#toString--) | 頂点要素の文字列表現です。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementPolygonGroup() {#VertexElementPolygonGroup--}
```
public VertexElementPolygonGroup()
```


[VertexElementPolygonGroup](../../com.aspose.threed/vertexelementpolygongroup) クラスの新しいインスタンスを初期化します。

### clear() {#clear--}
```
public void clear()
```


direct と index 配列からすべての要素を削除します。

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


頂点要素をディープクローンします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| withData | boolean | direct と index 配列で頂点をクローンします。 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### copyTo(VertexElementIntsTemplate target) {#copyTo-com.aspose.threed.VertexElementIntsTemplate-}
```
public void copyTo(VertexElementIntsTemplate target)
```


指定された要素にデータをコピーします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| target | [VertexElementIntsTemplate](../../com.aspose.threed/vertexelementintstemplate) | 対象。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public List<Integer> getData()
```


頂点データを取得します。

**Returns:**
java.util.List<java.lang.Integer> - 頂点データ
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


インデックスデータを取得します。

**Returns:**
java.util.List<java.lang.Integer> - インデックスデータ
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


要素のマッピング方法を取得します。

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


要素の参照方法を取得します。

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


[VertexElement](../../com.aspose.threed/vertexelement) の型を取得します。

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(int[] data) {#setData-int---}
```
public void setData(int[] data)
```


データをロードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| データ | int[] |  |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


インデックスをロードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| データ | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


要素のマッピング方法を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


要素の参照方法を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | 新しい値 |

### toString() {#toString--}
```
public String toString()
```


頂点要素の文字列表現です。

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

