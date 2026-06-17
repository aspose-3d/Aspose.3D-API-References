---
title: "PolygonModifier"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Утилиты для модификации полигонов  @hideconstructor


## Методы

### triangulate{#triangulate}

| Имя | Описание |
| --- | --- |
| triangulate(scene) | Преобразовать все полигональные меши в полноценный треугольный меш |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| сцена | Scene | Сцена для обработки |

 **Result:**



---


### triangulate{#triangulate}

| Имя | Описание |
| --- | --- |
| triangulate(mesh) | Преобразовать полигональный меш в полноценный треугольный меш |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| mesh | Сетка | Исходный не-треугольный меш |

 **Result:**
Сетка


---


### mergeMesh{#mergeMesh}

| Имя | Описание |
| --- | --- |
| mergeMesh(scene) | Преобразовать всю сцену в один преобразованный меш. Элементы Vertex, такие как нормали/текстурные координаты, пока не поддерживаются. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| сцена | Scene | Сцена для объединения |

 **Result:**
Сетка


---


### mergeMesh{#mergeMesh}

| Имя | Описание |
| --- | --- |
| mergeMesh(node) | Преобразовать весь узел в один преобразованный меш. Элементы Vertex, такие как нормали/текстурные координаты, пока не поддерживаются. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| node | Node | Узел для объединения |

 **Result:**
Сетка


---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(scene, scale) | Масштабировать все геометрии (масштабировать контрольные точки, а не матрицу преобразования) в этой сцене |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| сцена | Scene | Сцена для масштабирования |
| масштаб | Vector3 | Коэффициент масштабирования |

 **Result:**
Сетка


---


### scale{#scale}

| Имя | Описание |
| --- | --- |
| scale(node, scale) | Масштабировать все геометрии (масштабировать контрольные точки, а не матрицу преобразования) в этом узле |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| node | Node | Узел для масштабирования |
| масштаб | Vector3 | Коэффициент масштабирования |

 **Result:**
Сетка


---


### generateNormal{#generateNormal}

| Имя | Описание |
| --- | --- |
| generateNormal(mesh) | Создать данные нормалей из определения Mesh |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Имя | Описание |
| --- | --- |
| generateUV(mesh, normals) | Создать данные UV из заданной входной сетки и указанных данных нормалей. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| mesh | Сетка | Входная сетка |
| нормали | VertexElementNormal | Данные нормалей |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Имя | Описание |
| --- | --- |
| generateUV(mesh) | Создать данные UV из заданной входной сетки |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| mesh | Сетка | Входная сетка |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Имя | Описание |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Разделить сетку на под‑сетки по VertexElementMaterial. Каждая под‑сетка будет использовать только один материал. Выполнить разделение сетки на узле. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| узел | Node | null |
| политика | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Создать дочерние узлы для каждой под‑сетки. |
| removeOldMesh | boolean | Удалить старую сетку после разделения, если этот параметр ложен, старые и новые сетки будут сосуществовать. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Имя | Описание |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Разделить сетку на под‑сетки по VertexElementMaterial. Каждая под‑сетка будет использовать только один материал. Выполнить разделение сетки на всех узлах сцены. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| scen | Scene | null |
| политика | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Имя | Описание |
| --- | --- |
| splitMesh(mesh, policy) | Разделить сетку на под‑сетки по VertexElementMaterial. Каждая под‑сетка будет использовать только один материал. Исходная сетка не будет изменена. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Имя | Описание |
| --- | --- |
| buildTangentBinormal(scene) | Это создаст tangent и binormal на всех meshes сцены. Normal требуется, если normal отсутствует в mesh, она также будет создана из позиции. UV также требуется, mesh будет игнорироваться, если UV не определён. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Имя | Описание |
| --- | --- |
| buildTangentBinormal(mesh) | Это создаст тангенс и бинормаль на mesh. Normal требуется; если normal отсутствует в mesh, она также будет создана из позиции. UV также требуется, будет выброшено исключение, если UV не найдено. |

 **Result:**
Mesh[]


---



