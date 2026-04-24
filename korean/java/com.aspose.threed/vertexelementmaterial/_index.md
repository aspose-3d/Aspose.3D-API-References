---
title: VertexElementMaterial
second_title: Aspose.3D for Java API 레퍼런스
description: 지정된 구성 요소에 대한 재질 인덱스를 정의합니다.
type: docs
weight: 213
url: /ko/java/com.aspose.threed/vertexelementmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementMaterial extends VertexElement
```

지정된 구성 요소에 대한 재질 인덱스를 정의합니다. 노드는 여러 재질을 가질 수 있으며, [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 은(는) 기하학의 다른 부분을 다른 재질로 렌더링하는 데 사용됩니다. **Example:** 다음 코드는 상자의 서로 다른 면에 서로 다른 재질을 할당하는 방법을 보여줍니다.

```
// Create a mesh of box(A box is composed by 6 planes)
             Mesh box = (new Box()).ToMesh();
             // Create a material element on this mesh
             VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
             // And specify different material index for each plane
             mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VertexElementMaterial()](#VertexElementMaterial--) | 새 인스턴스를 초기화합니다. [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clear()](#clear--) | 직접 배열과 인덱스 배열에서 모든 요소를 제거합니다. |
| [clone(boolean withData)](#clone-boolean-) | 버텍스 요소를 깊게 복제합니다. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
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
### VertexElementMaterial() {#VertexElementMaterial--}
```
public VertexElementMaterial()
```


새 인스턴스를 초기화합니다. [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 클래스.

### clear() {#clear--}
```
public void clear()
```


직접 배열과 인덱스 배열에서 모든 요소를 제거합니다.

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
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

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

