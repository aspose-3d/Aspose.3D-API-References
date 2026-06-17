---
title: "PolygonModifier"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

폴리곤을 수정하기 위한 유틸리티  @hideconstructor


## 메서드

### triangulate{#triangulate}

| 이름 | 설명 |
| --- | --- |
| triangulate(scene) | 폴리곤 기반 메쉬를 모두 전체 삼각형 메쉬로 변환합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| scene | Scene | 처리할 씬 |

 **Result:**



---


### triangulate{#triangulate}

| 이름 | 설명 |
| --- | --- |
| triangulate(mesh) | 폴리곤 기반 메쉬를 전체 삼각형 메쉬로 변환합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| mesh | Mesh | 원본 비삼각형 메쉬 |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| 이름 | 설명 |
| --- | --- |
| mergeMesh(scene) | 전체 씬을 단일 변환 메쉬로 변환합니다. 노멀/텍스처 좌표와 같은 정점 요소는 아직 지원되지 않습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| scene | Scene | 병합할 씬 |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| 이름 | 설명 |
| --- | --- |
| mergeMesh(node) | 전체 노드를 단일 변환 메쉬로 변환합니다. 노멀/텍스처 좌표와 같은 정점 요소는 아직 지원되지 않습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| node | Node | 병합할 노드 |

 **Result:**
Mesh


---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(scene, scale) | 이 씬의 모든 기하학을 스케일합니다(제어점을 스케일하고 변환 행렬은 스케일하지 않음). |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| scene | Scene | 스케일할 씬 |
| 스케일 | Vector3 | 스케일 팩터 |

 **Result:**
Mesh


---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(node, scale) | 이 노드의 모든 기하학을 스케일합니다(제어점을 스케일하고 변환 행렬은 스케일하지 않음). |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| node | Node | 스케일할 노드 |
| 스케일 | Vector3 | 스케일 팩터 |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| 이름 | 설명 |
| --- | --- |
| generateNormal(mesh) | Mesh 정의에서 노멀 데이터를 생성합니다 |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| 이름 | 설명 |
| --- | --- |
| generateUV(mesh, normals) | 주어진 입력 Mesh와 지정된 노멀 데이터를 사용하여 UV 데이터를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| mesh | Mesh | 입력 Mesh |
| 노멀 | VertexElementNormal | 노멀 데이터 |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| 이름 | 설명 |
| --- | --- |
| generateUV(mesh) | 주어진 입력 Mesh에서 UV 데이터를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| mesh | Mesh | 입력 Mesh |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 이름 | 설명 |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | VertexElementMaterial에 따라 Mesh를 서브 Mesh로 분할합니다. 각 서브 Mesh는 하나의 재질만 사용합니다. 노드에서 Mesh 분할을 수행합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nod | Node | null |
| 정책 | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | 각 서브 Mesh에 대한 자식 노드를 생성합니다. |
| removeOldMesh | boolean | 분할 후 기존 Mesh를 제거합니다. 이 매개변수가 false이면 기존 Mesh와 새로운 Mesh가 동시에 존재합니다. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 이름 | 설명 |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | VertexElementMaterial에 따라 Mesh를 서브 Mesh로 분할합니다. 각 서브 Mesh는 하나의 재질만 사용합니다. 씬의 모든 노드에서 Mesh 분할을 수행합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 씬 | Scene | null |
| 정책 | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 이름 | 설명 |
| --- | --- |
| splitMesh(mesh, policy) | VertexElementMaterial에 따라 Mesh를 서브 Mesh로 분할합니다. 각 서브 Mesh는 하나의 재질만 사용합니다. 원본 Mesh는 변경되지 않습니다. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| 이름 | 설명 |
| --- | --- |
| buildTangentBinormal(scene) | 이 기능은 씬의 모든 Mesh에 접선(tangent)과 바이노멀(binormal)을 생성합니다. 노멀은 필수이며, Mesh에 노멀 데이터가 없을 경우 위치 정보를 사용하여 노멀 데이터를 생성합니다. UV도 필수이며, UV가 정의되지 않은 경우 해당 Mesh는 무시됩니다. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| 이름 | 설명 |
| --- | --- |
| buildTangentBinormal(mesh) | 이것은 메시에서 탄젠트와 바이노멀을 생성합니다. 노멀은 필요하며, 메시에 노멀 데이터가 없을 경우 위치에서 노멀 데이터를 생성합니다. UV도 필요하며, UV가 없을 경우 예외가 발생합니다. |

 **Result:**
Mesh[]


---



