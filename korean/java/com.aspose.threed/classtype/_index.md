---
title: StructuralMetadata.ClassType
second_title: Aspose.3D for Java API 레퍼런스
description: 메타데이터의 클래스 정의
type: docs
weight: 10
url: /ko/java/com.aspose.threed/structuralmetadata.classtype/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.ClassType
```

메타데이터의 클래스 정의
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)](#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--) | 클래스 정의의 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addProperty(StructuralMetadata.Property property)](#addProperty-com.aspose.threed.StructuralMetadata.Property-) | 이 클래스에 지정된 속성을 추가합니다 |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, Class<?> type)](#addProperty-java.lang.String-java.lang.Class----) | 지정된 유형으로 새 속성을 추가합니다 |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 클래스 설명 |
| [getDisplayName()](#getDisplayName--) | UI에서 표시하기 위해 사용되는 클래스 이름 |
| [getName()](#getName--) | 클래스의 고유 이름 |
| [getProperties()](#getProperties--) | 이 클래스에 정의된 속성들. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | 클래스 설명 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | UI에서 표시하기 위해 사용되는 클래스 이름 |
| [toString()](#toString--) | 이 인스턴스의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties) {#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--}
```
public ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)
```


클래스 정의의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 클래스의 고유 이름 |
| displayName | java.lang.String | UI에서 표시하기 위해 사용되는 클래스 이름 |
| description | java.lang.String | 클래스 설명 |
| 속성 | java.util.ArrayList<com.aspose.threed.StructuralMetadata.Property> | 이 클래스에 정의된 속성들 |

### addProperty(StructuralMetadata.Property property) {#addProperty-com.aspose.threed.StructuralMetadata.Property-}
```
public void addProperty(StructuralMetadata.Property property)
```


이 클래스에 지정된 속성을 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) |  |

### addProperty(String name, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 배열 | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 배열 | boolean |  |
| 갯수 | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, Class<?> type) {#addProperty-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, Class<?> type)
```


지정된 유형으로 새 속성을 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 속성 이름 |
| type | java.lang.Class<?> | 속성 데이터 유형 |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 배열 | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| 배열 | boolean |  |
| 갯수 | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |
| normalized | boolean |  |
| 갯수 | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


클래스 설명

**Returns:**
java.lang.String - 클래스 설명
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


UI에서 표시하기 위해 사용되는 클래스 이름

**Returns:**
java.lang.String - UI에서 표시하기 위해 사용되는 클래스 이름
### getName() {#getName--}
```
public String getName()
```


클래스의 고유 이름

**Returns:**
java.lang.String - 클래스의 고유 이름
### getProperties() {#getProperties--}
```
public List<StructuralMetadata.Property> getProperties()
```


이 클래스에 정의된 속성들.

**Returns:**
java.util.List<com.aspose.threed.StructuralMetadata.Property> - 이 클래스에 정의된 속성들.
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


클래스 설명

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


UI에서 표시하기 위해 사용되는 클래스 이름

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### toString() {#toString--}
```
public String toString()
```


이 인스턴스의 문자열 표현을 가져옵니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

