---
title: StructuralMetadata.Property
second_title: Aspose.3D for Java API 레퍼런스
description: 메타 데이터 클래스에서의 속성 정의
type: docs
weight: 13
url: /ko/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

메타데이터 클래스의 속성 정의
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | 메타데이터 속성의 생성자 |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | 메타데이터 속성의 생성자 |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | 메타데이터 속성의 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 고정 크기 배열의 데이터 개수. |
| [getDescription()](#getDescription--) | 속성에 대한 설명 |
| [getDisplayName()](#getDisplayName--) | UI에서 표시하기 위해 사용되는 속성 이름. |
| [getEnumType()](#getEnumType--) | 열거형 타입 |
| [getName()](#getName--) | 속성의 고유 이름 |
| [getNormalized()](#getNormalized--) | 데이터가 정규화되었는지 여부. |
| [getType()](#getType--) | 속성의 데이터 타입 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | 고정 크기 배열의 데이터 개수. |
| [setDescription(String value)](#setDescription-java.lang.String-) | 속성에 대한 설명 |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | UI에서 표시하기 위해 사용되는 속성 이름. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | 열거형 타입 |
| [setNormalized(boolean value)](#setNormalized-boolean-) | 데이터가 정규화되었는지 여부. |
| [toString()](#toString--) | 이 인스턴스의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


메타데이터 속성의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 속성의 고유 이름 |
| displayName | java.lang.String | UI에서 표시하기 위해 사용되는 속성 이름. |
| description | java.lang.String | 속성에 대한 설명 |
| type | java.lang.Class<?> | 속성의 데이터 타입 |
| normalized | boolean | 데이터가 정규화되었는지 여부 |
| 갯수 | java.lang.Integer | 고정 크기 배열의 데이터 개수 |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


메타데이터 속성의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 속성의 고유 이름 |
| displayName | java.lang.String | UI에서 표시하기 위해 사용되는 속성 이름. |
| description | java.lang.String | 속성에 대한 설명 |
| type | [EnumType](../../com.aspose.threed/enumtype) | 속성의 데이터 타입 |
| 배열 | boolean | 각 속성 값이 배열인지 스칼라인지 여부 |
| 갯수 | java.lang.Integer | 고정 크기 배열의 데이터 개수 |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


메타데이터 속성의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 속성의 고유 이름 |
| type | java.lang.Class<?> | 속성의 데이터 타입 |

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
### getCount() {#getCount--}
```
public Integer getCount()
```


고정 크기 배열의 데이터 개수.

**Returns:**
java.lang.Integer - 고정 크기 배열의 데이터 개수.
### getDescription() {#getDescription--}
```
public String getDescription()
```


속성에 대한 설명

**Returns:**
java.lang.String - 속성에 대한 설명
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


UI에서 표시하기 위해 사용되는 속성 이름.

**Returns:**
java.lang.String - UI에서 표시하기 위해 사용되는 속성 이름.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


열거형 타입

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


속성의 고유 이름

**Returns:**
java.lang.String - 속성의 고유 이름
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


데이터가 정규화되었는지 여부.

**Returns:**
boolean - 데이터가 정규화되었는지 여부.
### getType() {#getType--}
```
public Class<?> getType()
```


속성의 데이터 타입

**Returns:**
java.lang.Class<?> - 속성의 데이터 유형
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


고정 크기 배열의 데이터 개수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer | 새 값 |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


속성에 대한 설명

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


UI에서 표시하기 위해 사용되는 속성 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


열거형 타입

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | 새 값 |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


데이터가 정규화되었는지 여부.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

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

