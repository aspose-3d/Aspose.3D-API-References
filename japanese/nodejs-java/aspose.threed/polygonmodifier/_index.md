---
title: "PolygonModifier"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

ポリゴンを変更するユーティリティ  @hideconstructor


## メソッド

### triangulate{#triangulate}

| 名前 | 説明 |
| --- | --- |
| triangulate(scene) | すべてのポリゴンベースのメッシュを完全な三角形メッシュに変換します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シーン | Scene | 処理対象のシーン |

 **Result:**



---


### triangulate{#triangulate}

| 名前 | 説明 |
| --- | --- |
| triangulate(mesh) | ポリゴンベースのメッシュを完全な三角形メッシュに変換します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| メッシュ | Mesh | 元の非三角形メッシュ |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| 名前 | 説明 |
| --- | --- |
| mergeMesh(scene) | シーン全体を単一の変換済みメッシュに変換します。法線やテクスチャ座標などの頂点要素はまだサポートされていません |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シーン | Scene | マージ対象のシーン |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| 名前 | 説明 |
| --- | --- |
| mergeMesh(node) | ノード全体を単一の変換済みメッシュに変換します。法線やテクスチャ座標などの頂点要素はまだサポートされていません |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ノード | ノード | マージ対象のノード |

 **Result:**
Mesh


---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(scene, scale) | このシーン内のすべてのジオメトリをスケールします（変換行列ではなく制御点をスケールします） |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シーン | Scene | スケール対象のシーン |
| スケール | Vector3 | スケール係数 |

 **Result:**
Mesh


---


### scale{#scale}

| 名前 | 説明 |
| --- | --- |
| scale(node, scale) | このノード内のすべてのジオメトリをスケールします（変換行列ではなく制御点をスケールします） |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ノード | ノード | スケール対象のノード |
| スケール | Vector3 | スケール係数 |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| 名前 | 説明 |
| --- | --- |
| generateNormal(mesh) | Mesh 定義から法線データを生成する |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| 名前 | 説明 |
| --- | --- |
| generateUV(mesh, normals) | 指定された入力メッシュと指定された法線データから UV データを生成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| メッシュ | Mesh | 入力メッシュ |
| 法線 | VertexElementNormal | 法線データ |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| 名前 | 説明 |
| --- | --- |
| generateUV(mesh) | 指定された入力メッシュから UV データを生成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| メッシュ | Mesh | 入力メッシュ |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 名前 | 説明 |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | VertexElementMaterial によってメッシュをサブメッシュに分割します。各サブメッシュは 1 つのマテリアルのみを使用します。ノード上でメッシュ分割を実行します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| nod | ノード | null |
| ポリシー | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | 各サブメッシュに対して子ノードを作成します。 |
| removeOldMesh | boolean | 分割後に古いメッシュを削除します。このパラメーターが false の場合、古いメッシュと新しいメッシュが共存します。 |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 名前 | 説明 |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | VertexElementMaterial によってメッシュをサブメッシュに分割します。各サブメッシュは 1 つのマテリアルのみを使用します。シーン内のすべてのノードでメッシュ分割を実行します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シーン | Scene | null |
| ポリシー | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| 名前 | 説明 |
| --- | --- |
| splitMesh(mesh, policy) | VertexElementMaterial によってメッシュをサブメッシュに分割します。各サブメッシュは 1 つのマテリアルのみを使用します。元のメッシュは変更されません。 |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| 名前 | 説明 |
| --- | --- |
| buildTangentBinormal(scene) | シーン内のすべてのメッシュにタンジェントとバイノーマルを作成します。法線が必要で、メッシュに法線が存在しない場合は、位置情報から法線データも作成します。UV も必要で、UV が定義されていないメッシュは無視されます。 |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| 名前 | 説明 |
| --- | --- |
| buildTangentBinormal(mesh) | これにより、メッシュ上にタンジェントとバイノーマルが作成されます。法線が必要で、メッシュに法線が存在しない場合は、位置から法線データも作成されます。UVも必要で、UVが見つからない場合は例外がスローされます。 |

 **Result:**
Mesh[]


---



