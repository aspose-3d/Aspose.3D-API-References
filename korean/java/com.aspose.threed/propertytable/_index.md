---
title: StructuralMetadata.PropertyTable
second_title: Aspose.3D for Java API 레퍼런스
description: 속성 테이블.
type: docs
weight: 14
url: /ko/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

속성 테이블.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | 속성 테이블의 생성자입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | 속성 테이블에 새 속성을 추가합니다. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | 속성 테이블에 새 속성을 추가합니다. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | 현재 속성 테이블을 지정된 사용자 데이터에 연결합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | 지정된 사용자 데이터에서 연결된 속성 테이블을 추출합니다. |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | 이 속성 테이블의 메타 클래스입니다. |
| [getName()](#getName--) | 속성 테이블의 이름입니다. |
| [getValue(String name)](#getValue-java.lang.String-) | 지정된 속성 이름의 값을 가져옵니다. |
| [getValues()](#getValues--) | 속성 테이블의 값들입니다. |
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


속성 테이블의 생성자입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이 테이블 인스턴스의 이름입니다. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | 이 속성 테이블의 메타 클래스 정의입니다. |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


속성 테이블에 새 속성을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | 값과 함께 추가할 속성 |
| 값 | java.lang.Object | 값 배열 |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


속성 테이블에 새 속성을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propName | java.lang.String | 값과 함께 추가할 속성 |
| 값 | java.lang.Object | 값 배열 |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


현재 속성 테이블을 지정된 사용자 데이터에 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


지정된 사용자 데이터에서 연결된 속성 테이블을 추출합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | 속성 테이블과 연결된 사용자 데이터 |

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


이 속성 테이블의 메타 클래스입니다.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


속성 테이블의 이름입니다.

**Returns:**
java.lang.String - 속성 테이블의 이름.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


지정된 속성 이름의 값을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 속성 값 또는 찾을 수 없을 경우 null
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


속성 테이블의 값들입니다.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - 속성 테이블의 값들.
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

