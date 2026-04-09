---
title: IVertexBuffer
second_title: Aspose.3D for Java API 레퍼런스
description: 버텍스 버퍼는 렌더링 파이프라인으로 전송될 폴리곤 버텍스 데이터를 보관합니다.
type: docs
weight: 259
url: /ko/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

버텍스 버퍼는 렌더링 파이프라인으로 전송될 폴리곤 버텍스 데이터를 보관합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | 정점 선언을 가져옵니다. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | 정점 데이터를 [TriMesh](../../com.aspose.threed/trimesh)에서 로드합니다. |
| [loadData(Object array)](#loadData-java.lang.Object-) | 배열에서 데이터를 로드합니다. |
| [loadData(long data, int size)](#loadData-long-int-) | 지정된 위치에서 데이터를 로드합니다. |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


정점 선언을 가져옵니다.

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


정점 데이터를 [TriMesh](../../com.aspose.threed/trimesh)에서 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


배열에서 데이터를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 배열 | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


지정된 위치에서 데이터를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | long |  |
| 크기 | int |  |

