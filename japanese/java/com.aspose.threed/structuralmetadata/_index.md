---
title: StructuralMetadata
second_title: Aspose.3D for Java API リファレンス
description: このクラスは、glTF でのみ使用される EXT_structural_metadata のサポートを提供します。
type: docs
weight: 180
url: /ja/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

このクラスは EXT\_structural\_metadata のサポートを提供し、glTF でのみ使用されます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | 現在のメタデータを指定されたシーンに添付する |
| [createClass(String name)](#createClass-java.lang.String-) | メタクラス型を作成する |
| [createEnum(String name)](#createEnum-java.lang.String-) | 列挙型を作成する |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | 指定されたメタクラス型で新しいプロパティテーブルを作成する |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | 指定されたシーンに関連付けられた [StructuralMetadata](../../com.aspose.threed/structuralmetadata) を取得します。 |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | クラス定義。 |
| [getEnums()](#getEnums--) | 列挙型定義 |
| [getPropertyTables()](#getPropertyTables--) | このメタデータ内のプロパティテーブル。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuralMetadata() {#StructuralMetadata--}
```
public StructuralMetadata()
```


### attach(Scene scene) {#attach-com.aspose.threed.Scene-}
```
public void attach(Scene scene)
```


現在のメタデータを指定されたシーンに添付する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


メタクラス型を作成する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | クラス名 |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


列挙型を作成する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 列挙型の名前 |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


指定されたメタクラス型で新しいプロパティテーブルを作成する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティテーブルの名前 |
| clazz | [ClassType](../../com.aspose.threed/classtype) | 新しいプロパティテーブルのクラス型 |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


指定されたシーンに関連付けられた [StructuralMetadata](../../com.aspose.threed/structuralmetadata) を取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 構造メタデータを検索するシーン |

**Returns:**
[StructuralMetadata](../../com.aspose.threed/structuralmetadata) - A valid instance of [StructuralMetadata](../../com.aspose.threed/structuralmetadata) if its found in the scene, otherwise null returned
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClasses() {#getClasses--}
```
public HashMap<String,StructuralMetadata.ClassType> getClasses()
```


クラス定義。

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - クラス定義。
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


列挙型定義

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - 列挙型定義
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


このメタデータ内のプロパティテーブル。

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - このメタデータ内のプロパティテーブル。
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

