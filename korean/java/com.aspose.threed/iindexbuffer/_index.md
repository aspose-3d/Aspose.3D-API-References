---
title: IIndexBuffer
second_title: Aspose.3D for Java API 레퍼런스
description: 인덱스 버퍼는 렌더링 파이프라인에서 사용되는 기하학을 설명합니다.
type: docs
weight: 242
url: /ko/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

인덱스 버퍼는 렌더링 파이프라인에서 사용되는 기하학을 설명합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 이 버퍼의 인덱스 수를 가져옵니다. |
| [getIndexDataType()](#getIndexDataType--) | 각 요소의 데이터 유형을 가져옵니다. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | [TriMesh](../../com.aspose.threed/trimesh)에서 인덱스 데이터를 로드합니다 |
| [loadData(int[] indices)](#loadData-int---) | 인덱스 데이터를 로드합니다 |
| [loadData(short[] indices)](#loadData-short---) | 인덱스 데이터를 로드합니다 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


이 버퍼의 인덱스 수를 가져옵니다.

**Returns:**
int - 이 버퍼의 인덱스 수.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


각 요소의 데이터 유형을 가져옵니다.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


[TriMesh](../../com.aspose.threed/trimesh)에서 인덱스 데이터를 로드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


인덱스 데이터를 로드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


인덱스 데이터를 로드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | short[] |  |

