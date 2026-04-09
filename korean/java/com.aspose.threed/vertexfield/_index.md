---
title: VertexField
second_title: Aspose.3D for Java API 레퍼런스
description: Vertexs 필드 메모리 레이아웃 설명.
type: docs
weight: 227
url: /ko/java/com.aspose.threed/vertexfield/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public class VertexField implements Comparable<VertexField>
```

정점 필드 메모리 레이아웃 설명입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [compareTo(VertexField other)](#compareTo-com.aspose.threed.VertexField-) | 이 인스턴스를 지정된 객체와 비교하고, 상대적인 값에 대한 표시를 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스와 지정된 객체(또한 [VertexField](../../com.aspose.threed/vertexfield) 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다. |
| [getAlias()](#getAlias--) | 필드 별칭. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | 이 필드의 데이터 유형. |
| [getIndex()](#getIndex--) | 동일한 의미를 가진 정점 레이아웃에서 이 필드의 인덱스. |
| [getOffset()](#getOffset--) | 이 필드의 바이트 단위 오프셋. |
| [getSemantic()](#getSemantic--) | 이 필드의 사용 의미. |
| [getSize()](#getSize--) | 이 필드의 바이트 단위 크기 |
| [hashCode()](#hashCode--) | 이 문자열에 대한 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | [VertexField](../../com.aspose.threed/vertexfield)의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### compareTo(VertexField other) {#compareTo-com.aspose.threed.VertexField-}
```
public int compareTo(VertexField other)
```


이 인스턴스를 지정된 객체와 비교하고, 상대적인 값에 대한 표시를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [VertexField](../../com.aspose.threed/vertexfield) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스와 지정된 객체(또한 [VertexField](../../com.aspose.threed/vertexfield) 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlias() {#getAlias--}
```
public String getAlias()
```


필드 별칭.

**Returns:**
java.lang.String - 필드 별칭.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataType() {#getDataType--}
```
public int getDataType()
```


이 필드의 데이터 유형.

**Returns:**
int - 이 필드의 데이터 유형.
### getIndex() {#getIndex--}
```
public int getIndex()
```


동일한 의미를 가진 정점 레이아웃에서 이 필드의 인덱스.

**Returns:**
int - 동일한 의미를 가진 정점 레이아웃에서 이 필드의 인덱스.
### getOffset() {#getOffset--}
```
public int getOffset()
```


이 필드의 바이트 단위 오프셋.

**Returns:**
int - 이 필드의 바이트 단위 오프셋.
### getSemantic() {#getSemantic--}
```
public VertexFieldSemantic getSemantic()
```


이 필드의 사용 의미.

**Returns:**
[VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) - The usage semantic of this field.
### getSize() {#getSize--}
```
public int getSize()
```


이 필드의 바이트 단위 크기

**Returns:**
int - 이 필드의 바이트 단위 크기
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 문자열에 대한 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드.
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


[VertexField](../../com.aspose.threed/vertexfield)의 문자열 표현을 가져옵니다.

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

