---
title: VertexDeclaration
second_title: Aspose.3D for Java API 레퍼런스
description: 사용자 정의 정점 구조의 선언
type: docs
weight: 206
url: /ko/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

사용자 정의 정점 구조의 선언
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | 새 정점 필드를 추가합니다 |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | 새 정점 필드를 추가합니다 |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | 새 정점 필드를 추가합니다 |
| [clear()](#clear--) | 모든 필드를 지웁니다. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | 이 인스턴스를 지정된 객체와 비교하고, 상대적인 값에 대한 표시를 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스와 지정된 객체(또한 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | [Geometry](../../com.aspose.threed/geometry)의 레이아웃을 기반으로 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)을 생성합니다. |
| [get(int index)](#get-int-) | 인덱스로 [VertexField](../../com.aspose.threed/vertexfield)을 가져옵니다 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 이 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)에서 정의된 모든 필드의 개수를 가져옵니다 |
| [getSealed()](#getSealed--) | [TriMesh](../../com.aspose.threed/trimesh)에 의해 사용된 후 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)은 봉인되며, 더 이상 수정이 허용되지 않습니다. |
| [getSize()](#getSize--) | 정점 구조의 바이트 단위 크기. |
| [hashCode()](#hashCode--) | 이 문자열에 대한 해시 코드를 반환합니다. |
| [iterator()](#iterator--) | 이 인스턴스의 모든 정점 필드를 순회하는 열거자를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)의 문자열 표현 |
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


새 정점 필드를 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataType | int | 정점 필드의 데이터 유형 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | 이 필드는 어떻게 사용됩니까 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


새 정점 필드를 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataType | int | 정점 필드의 데이터 유형 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | 이 필드는 어떻게 사용됩니까 |
| 인덱스 | int | 동일 필드 의미에 대한 인덱스, 자동 생성은 -1 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


새 정점 필드를 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataType | int | 정점 필드의 데이터 유형 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | 이 필드는 어떻게 사용됩니까 |
| 인덱스 | int | 동일 필드 의미에 대한 인덱스, 자동 생성은 -1 |
| 별칭 | java.lang.String | 필드의 별칭 이름 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


모든 필드를 지웁니다.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


이 인스턴스를 지정된 객체와 비교하고, 상대적인 값에 대한 표시를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스와 지정된 객체(또한 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


[Geometry](../../com.aspose.threed/geometry)의 레이아웃을 기반으로 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | double 타입 대신 float 사용 |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


인덱스로 [VertexField](../../com.aspose.threed/vertexfield)을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |

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


이 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)에서 정의된 모든 필드의 개수를 가져옵니다

**Returns:**
int - 이 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)에서 정의된 모든 필드의 개수
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


[TriMesh](../../com.aspose.threed/trimesh)에 의해 사용된 후 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)은 봉인되며, 더 이상 수정이 허용되지 않습니다.

**Returns:**
boolean - [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)은 [TriMesh](../../com.aspose.threed/trimesh)에 사용되면 봉인되며, 더 이상 수정할 수 없습니다.
### getSize() {#getSize--}
```
public int getSize()
```


정점 구조의 바이트 단위 크기.

**Returns:**
int - 정점 구조체의 바이트 단위 크기.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 문자열에 대한 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


이 인스턴스의 모든 정점 필드를 순회하는 열거자를 가져옵니다.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - 열거자
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


[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)의 문자열 표현

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

