---
title: StructuralMetadata.PropertyTable
second_title: Aspose.3D for Java API リファレンス
description: プロパティテーブル。
type: docs
weight: 14
url: /ja/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

プロパティテーブル。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | プロパティテーブルのコンストラクタです。 |
## Methods

| Method | 説明 |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | プロパティテーブルに新しいプロパティを追加します。 |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | プロパティテーブルに新しいプロパティを追加します。 |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | 現在のプロパティテーブルを指定されたユーザーデータに添付します |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | 指定されたユーザーデータから添付されたプロパティテーブルを抽出します |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | このプロパティテーブルのメタクラスです。 |
| [getName()](#getName--) | プロパティテーブルの名前です。 |
| [getValue(String name)](#getValue-java.lang.String-) | 指定されたプロパティ名の値を取得します |
| [getValues()](#getValues--) | プロパティテーブルの値です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


プロパティテーブルのコンストラクタです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | このテーブルインスタンスの名前です。 |
| mclass | [ClassType](../../com.aspose.threed/classtype) | このプロパティテーブルのメタクラス定義です |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


プロパティテーブルに新しいプロパティを追加します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | どのプロパティに値を追加するか |
| 値 | java.lang.Object | 値の配列 |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


プロパティテーブルに新しいプロパティを追加します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| propName | java.lang.String | どのプロパティに値を追加するか |
| 値 | java.lang.Object | 値の配列 |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


現在のプロパティテーブルを指定されたユーザーデータに添付します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


指定されたユーザーデータから添付されたプロパティテーブルを抽出します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | プロパティテーブルに関連付けられたユーザーデータです |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


このプロパティテーブルのメタクラスです。

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


プロパティテーブルの名前です。

**Returns:**
java.lang.String - プロパティテーブルの名前です。
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


指定されたプロパティ名の値を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティ名 |

**Returns:**
java.lang.Object - プロパティの値、または見つからない場合は null
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


プロパティテーブルの値です。

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - プロパティテーブルの値です。
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

