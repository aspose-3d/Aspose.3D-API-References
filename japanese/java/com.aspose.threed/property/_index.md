---
title: StructuralMetadata.Property
second_title: Aspose.3D for Java API リファレンス
description: メタデータクラスのプロパティ定義
type: docs
weight: 13
url: /ja/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

メタデータのクラスにおけるプロパティ定義
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | メタデータのプロパティのコンストラクタ |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | メタデータのプロパティのコンストラクタ |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | メタデータのプロパティのコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 固定サイズ配列のデータ数。 |
| [getDescription()](#getDescription--) | プロパティの説明 |
| [getDisplayName()](#getDisplayName--) | UI で表示するために使用されるプロパティの名前。 |
| [getEnumType()](#getEnumType--) | 列挙型 |
| [getName()](#getName--) | プロパティの一意な名前 |
| [getNormalized()](#getNormalized--) | データが正規化されているか。 |
| [getType()](#getType--) | プロパティのデータ型 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | 固定サイズ配列のデータ数。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | プロパティの説明 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | UI で表示するために使用されるプロパティの名前。 |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | 列挙型 |
| [setNormalized(boolean value)](#setNormalized-boolean-) | データが正規化されているか。 |
| [toString()](#toString--) | このインスタンスの文字列表現を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


メタデータのプロパティのコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの一意な名前 |
| displayName | java.lang.String | UI で表示するために使用されるプロパティの名前。 |
| description | java.lang.String | プロパティの説明 |
| type | java.lang.Class<?> | プロパティのデータ型 |
| normalized | boolean | データが正規化されているか |
| カウント | java.lang.Integer | 固定サイズ配列のデータ数 |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


メタデータのプロパティのコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの一意な名前 |
| displayName | java.lang.String | UI で表示するために使用されるプロパティの名前。 |
| description | java.lang.String | プロパティの説明 |
| type | [EnumType](../../com.aspose.threed/enumtype) | プロパティのデータ型 |
| 配列 | boolean | 各プロパティ値が配列かスカラーか |
| カウント | java.lang.Integer | 固定サイズ配列のデータ数 |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


メタデータのプロパティのコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティの一意な名前 |
| type | java.lang.Class<?> | プロパティのデータ型 |

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
### getCount() {#getCount--}
```
public Integer getCount()
```


固定サイズ配列のデータ数。

**Returns:**
java.lang.Integer - 固定サイズ配列のデータ数。
### getDescription() {#getDescription--}
```
public String getDescription()
```


プロパティの説明

**Returns:**
java.lang.String - プロパティの説明
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


UI で表示するために使用されるプロパティの名前。

**Returns:**
java.lang.String - UIで表現に使用されるプロパティの名前。
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


列挙型

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


プロパティの一意な名前

**Returns:**
java.lang.String - プロパティの一意な名前
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


データが正規化されているか。

**Returns:**
boolean - データが正規化されているか。
### getType() {#getType--}
```
public Class<?> getType()
```


プロパティのデータ型

**Returns:**
java.lang.Class<?> - プロパティのデータ型
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


固定サイズ配列のデータ数。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer | 新しい値 |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


プロパティの説明

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


UI で表示するために使用されるプロパティの名前。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


列挙型

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | 新しい値 |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


データが正規化されているか。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### toString() {#toString--}
```
public String toString()
```


このインスタンスの文字列表現を取得します。

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

