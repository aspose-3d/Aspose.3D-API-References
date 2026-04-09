---
title: PolygonBuilder
second_title: Aspose.3D for Java API 레퍼런스
description: 예제를 위한 폴리곤을 구축하는 도우미 클래스
type: docs
weight: 133
url: /ko/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

[Mesh](../../com.aspose.threed/mesh)에 대한 다각형을 만들기 위한 도우미 클래스 **Example:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

다음과 동일:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

모든 인덱스를 사용할 수 있으면 [Mesh](../../com.aspose.threed/mesh)를 권장하고, 그렇지 않으면 [PolygonBuilder](../../com.aspose.threed/polygonbuilder)가 더 나은 선택입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | [PolygonBuilder](../../com.aspose.threed/polygonbuilder) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | 다각형에 정점 인덱스를 추가합니다 |
| [begin()](#begin--) | 새 다각형 추가를 시작합니다 |
| [end()](#end--) | 다각형 생성을 완료합니다 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


[PolygonBuilder](../../com.aspose.threed/polygonbuilder) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 다각형을 만들 메시를 지정합니다. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


다각형에 정점 인덱스를 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |

### begin() {#begin--}
```
public void begin()
```


새 다각형 추가를 시작합니다

### end() {#end--}
```
public void end()
```


다각형 생성을 완료합니다

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

