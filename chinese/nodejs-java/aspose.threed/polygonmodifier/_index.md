---
title: "PolygonModifier"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

修改多边形的实用工具  @hideconstructor


## 方法

### triangulate{#triangulate}

| 名称 | 描述 |
| --- | --- |
| triangulate(scene) | 将所有基于多边形的网格转换为完整的三角网格 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | Scene | 要处理的场景 |

 **Result:**



---


### triangulate{#triangulate}

| 名称 | 描述 |
| --- | --- |
| triangulate(mesh) | 将基于多边形的网格转换为完整的三角网格 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mesh | Mesh | 原始的非三角网格 |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| 名称 | 描述 |
| --- | --- |
| mergeMesh(scene) | 将整个场景转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | Scene | 要合并的场景 |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| 名称 | 描述 |
| --- | --- |
| mergeMesh(node) | 将整个节点转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 要合并的节点 |

 **Result:**
Mesh


---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(scene, scale) | 在此场景中缩放所有几何体（缩放控制点而非变换矩阵） |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | Scene | 要缩放的场景 |
| 缩放 | Vector3 | 缩放因子 |

 **Result:**
Mesh


---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(node, scale) | 在此节点中缩放所有几何体（缩放控制点而非变换矩阵） |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 要缩放的节点 |
| 缩放 | Vector3 | 缩放因子 |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| 名称 | 描述 |
| --- | --- |
| generateNormal(mesh) | 从 Mesh 定义生成法线数据 |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| 名称 | 描述 |
| --- | --- |
| generateUV(mesh, normals) | 从给定的输入网格和指定的法线数据生成 UV 数据。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mesh | Mesh | 输入网格 |
| 法线 | VertexElementNormal | 法线数据 |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| 名称 | 描述 |
| --- | --- |
| generateUV(mesh) | 从给定的输入网格生成 UV 数据 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mesh | Mesh | 输入网格 |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 名称 | 描述 |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | 按 VertexElementMaterial 将网格拆分为子网格。每个子网格只使用一种材质。在节点上执行网格拆分。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nod | 节点 | null |
| 策略 | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | 为每个子网格创建子节点。 |
| removeOldMesh | boolean | 拆分后移除旧网格，如果此参数为 false，则旧网格和新网格将共存。 |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 名称 | 描述 |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | 按 VertexElementMaterial 将网格拆分为子网格。每个子网格只使用一种材质。在场景的所有节点上执行网格拆分。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| scen | Scene | null |
| 策略 | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 名称 | 描述 |
| --- | --- |
| splitMesh(mesh, policy) | 按 VertexElementMaterial 将网格拆分为子网格。每个子网格只使用一种材质。原始网格不会被更改。 |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| 名称 | 描述 |
| --- | --- |
| buildTangentBinormal(scene) | 这将在场景的所有网格上创建切线和双切线。需要法线，如果网格上不存在法线，它还会根据位置创建法线数据。UV 也是必需的，如果未定义 UV，则该网格将被忽略。 |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| 名称 | 描述 |
| --- | --- |
| buildTangentBinormal(mesh) | 这将在网格上创建切线和副法线。需要法线，如果网格上不存在法线，它还会从位置创建法线数据。还需要 UV，如果未找到 UV 将抛出异常。 |

 **Result:**
Mesh[]


---



