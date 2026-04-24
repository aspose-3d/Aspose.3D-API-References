---
title: StructuralMetadata.ClassType
second_title: Aspose.3D for Java API リファレンス
description: メタデータ内のクラス定義
type: docs
weight: 10
url: /ja/java/com.aspose.threed/structuralmetadata.classtype/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.ClassType
```

メタデータ内のクラス定義
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)](#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--) | クラス定義のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [addProperty(StructuralMetadata.Property property)](#addProperty-com.aspose.threed.StructuralMetadata.Property-) | このクラスに指定されたプロパティを追加する |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, Class<?> type)](#addProperty-java.lang.String-java.lang.Class----) | 指定された型で新しいプロパティを追加する |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | クラスの説明 |
| [getDisplayName()](#getDisplayName--) | UI で表示に使用されるクラス名 |
| [getName()](#getName--) | クラスの一意な名前 |
| [getProperties()](#getProperties--) | このクラスで定義されたプロパティ。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | クラスの説明 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | UI で表示に使用されるクラス名 |
| [toString()](#toString--) | このインスタンスの文字列表現を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties) {#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--}
```
public ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)
```


クラス定義のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | クラスの一意な名前 |
| displayName | java.lang.String | UI で表示に使用されるクラス名 |
| description | java.lang.String | クラスの説明 |
| プロパティ | java.util.ArrayList<com.aspose.threed.StructuralMetadata.Property> | このクラスで定義されたプロパティ |

### addProperty(StructuralMetadata.Property property) {#addProperty-com.aspose.threed.StructuralMetadata.Property-}
```
public void addProperty(StructuralMetadata.Property property)
```


このクラスに指定されたプロパティを追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) |  |

### addProperty(String name, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 配列 | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 配列 | boolean |  |
| カウント | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, Class<?> type) {#addProperty-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, Class<?> type)
```


指定された型で新しいプロパティを追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | プロパティ名 |
| type | java.lang.Class<?> | プロパティのデータ型 |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 配列 | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 配列 | boolean |  |
| カウント | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type, boolean normalized) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type, boolean normalized)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |
| normalized | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |
| normalized | boolean |  |
| カウント | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
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
### getDescription() {#getDescription--}
```
public String getDescription()
```


クラスの説明

**Returns:**
java.lang.String - クラスの説明
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


UI で表示に使用されるクラス名

**Returns:**
java.lang.String - UI で表示に使用されるクラス名
### getName() {#getName--}
```
public String getName()
```


クラスの一意な名前

**Returns:**
java.lang.String - クラスの一意な名前
### getProperties() {#getProperties--}
```
public List<StructuralMetadata.Property> getProperties()
```


このクラスで定義されたプロパティ。

**Returns:**
java.util.List<com.aspose.threed.StructuralMetadata.Property> - このクラスで定義されたプロパティ。
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


クラスの説明

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


UI で表示に使用されるクラス名

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

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

