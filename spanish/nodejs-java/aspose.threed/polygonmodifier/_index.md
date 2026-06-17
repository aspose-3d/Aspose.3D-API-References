---
title: "PolygonModifier"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Utilidades para modificar polígonos  @hideconstructor


## Métodos

### triangulate{#triangulate}

| Nombre | Descripción |
| --- | --- |
| triangulate(scene) | Convierte todas las mallas basadas en polígonos en una malla completa de triángulos |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| escena | Scene | La escena a procesar |

 **Result:**



---


### triangulate{#triangulate}

| Nombre | Descripción |
| --- | --- |
| triangulate(mesh) | Convierte una malla basada en polígonos en una malla completa de triángulos |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| mesh | Malla | La malla original que no es de triángulos |

 **Result:**
Malla


---


### mergeMesh{#mergeMesh}

| Nombre | Descripción |
| --- | --- |
| mergeMesh(scene) | Convierte una escena completa en una única malla transformada. Los elementos de vértice como normales/coordenadas de textura aún no son compatibles |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| escena | Scene | La escena a combinar |

 **Result:**
Malla


---


### mergeMesh{#mergeMesh}

| Nombre | Descripción |
| --- | --- |
| mergeMesh(node) | Convierte un nodo completo en una única malla transformada. Los elementos de vértice como normales/coordenadas de textura aún no son compatibles |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | El nodo a combinar |

 **Result:**
Malla


---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| scale(scene, scale) | Escala todas las geometrías (Escala los puntos de control, no la matriz de transformación) en esta escena |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| escena | Scene | La escena a escalar |
| escala | Vector3 | El factor de escala |

 **Result:**
Malla


---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| scale(node, scale) | Escala todas las geometrías (Escala los puntos de control, no la matriz de transformación) en este nodo |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | El nodo a escalar |
| escala | Vector3 | El factor de escala |

 **Result:**
Malla


---


### generateNormal{#generateNormal}

| Nombre | Descripción |
| --- | --- |
| generateNormal(mesh) | Generar datos normales a partir de la definición de Mesh |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Nombre | Descripción |
| --- | --- |
| generateUV(mesh, normals) | Generar datos UV a partir de la mesh de entrada proporcionada y los datos normales especificados. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| mesh | Malla | La mesh de entrada |
| normales | VertexElementNormal | Los datos normales |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Nombre | Descripción |
| --- | --- |
| generateUV(mesh) | Generar datos UV a partir de la mesh de entrada proporcionada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| mesh | Malla | La mesh de entrada |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nombre | Descripción |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Dividir la mesh en sub-meshes por VertexElementMaterial. Cada sub-mesh usará solo un material. Realizar la división de la mesh en un nodo. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| asentir | Nodo | null |
| política | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Crear nodos hijos para cada sub-mesh. |
| removeOldMesh | boolean | Eliminar la mesh antigua después de la división; si este parámetro es falso, la mesh antigua y la nueva coexistirán. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nombre | Descripción |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Dividir la mesh en sub-meshes por VertexElementMaterial. Cada sub-mesh usará solo un material. Realizar la división de la mesh en todos los nodos de la escena. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| scen | Scene | null |
| política | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nombre | Descripción |
| --- | --- |
| splitMesh(mesh, policy) | Dividir la mesh en sub-meshes por VertexElementMaterial. Cada sub-mesh usará solo un material. La mesh original no será modificada. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nombre | Descripción |
| --- | --- |
| buildTangentBinormal(scene) | Esto creará tangente y binormal en todas las meshes de la escena. Se requiere normal; si la normal no existe en la mesh, también se crearán los datos de normal a partir de la posición. También se requiere UV; la mesh será ignorada si no se define UV. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nombre | Descripción |
| --- | --- |
| buildTangentBinormal(mesh) | Esto creará tangente y binormal en la malla. Se requiere la normal; si la normal no existe en la malla, también se creará la información de la normal a partir de la posición. UV también es necesario, se lanzará una excepción si no se encuentra UV. |

 **Result:**
Mesh[]


---



