---
title: VertexElement
second_title: Aspose.3D for Java API 레퍼런스
description: 정점 요소의 기본 클래스입니다.
type: docs
weight: 207
url: /ko/java/com.aspose.threed/vertexelement/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.IIndexedVertexElement](../../com.aspose.threed/iindexedvertexelement)
```
public abstract class VertexElement implements IIndexedVertexElement
```

VertexElement의 기본 클래스입니다. 정점 요소 유형은 VertexElementType으로 식별됩니다. VertexElement는 정점 요소가 기하 표면에 어떻게 매핑되는지와 매핑 정보가 메모리에 어떻게 배열되는지를 설명합니다. VertexElement는 Normals, UVs 또는 기타 종류의 정보를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clear()](#clear--) | 이 VertexElement의 모든 데이터를 지웁니다. |
| [clone(boolean withData)](#clone-boolean-) | 버텍스 요소를 깊게 복제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIndices()](#getIndices--) | 인덱스 데이터를 가져옵니다. |
| [getMappingMode()](#getMappingMode--) | 요소가 어떻게 매핑되는지 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getReferenceMode()](#getReferenceMode--) | 요소가 어떻게 참조되는지 가져옵니다. |
| [getVertexElementType()](#getVertexElementType--) | [VertexElement](../../com.aspose.threed/vertexelement)의 유형을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setIndices(int[] data)](#setIndices-int---) | 인덱스를 로드합니다. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | 요소가 어떻게 매핑되는지 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | 요소가 어떻게 참조되는지 설정합니다. |
| [toString()](#toString--) | 버텍스 요소의 문자열 표현입니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clear() {#clear--}
```
public abstract void clear()
```


이 VertexElement의 모든 데이터를 지웁니다.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


버텍스 요소를 깊게 복제합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| withData | boolean | 직접 배열과 인덱스 배열을 사용하여 버텍스를 복제합니다. |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
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
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


인덱스 데이터를 가져옵니다.

**Returns:**
java.util.List<java.lang.Integer> - 인덱스 데이터
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


요소가 어떻게 매핑되는지 가져옵니다.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


요소가 어떻게 참조되는지 가져옵니다.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


[VertexElement](../../com.aspose.threed/vertexelement)의 유형을 가져옵니다.

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




### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


인덱스를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


요소가 어떻게 매핑되는지 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


요소가 어떻게 참조되는지 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | 새 값 |

### toString() {#toString--}
```
public String toString()
```


버텍스 요소의 문자열 표현입니다.

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

