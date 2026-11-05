---
title: "PolygonModifier"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Utility per modificare i poligoni  @hideconstructor


## Metodi

### triangulate{#triangulate}

| Nome | Descrizione |
| --- | --- |
| triangulate(scene) | Converti tutte le mesh basate su poligoni in una mesh a triangoli completa |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scene | Scena | La scena da elaborare |

 **Result:**



---


### triangulate{#triangulate}

| Nome | Descrizione |
| --- | --- |
| triangulate(mesh) | Converti una mesh basata su poligoni in una mesh a triangoli completa |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| mesh | Mesh | La mesh originale non triangolare |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nome | Descrizione |
| --- | --- |
| mergeMesh(scene) | Converti un'intera scena in una singola mesh trasformata. Gli elementi dei vertici come normali/coordinate texture non sono ancora supportati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scene | Scena | La scena da unire |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nome | Descrizione |
| --- | --- |
| mergeMesh(node) | Converti un intero nodo in una singola mesh trasformata. Gli elementi dei vertici come normali/coordinate texture non sono ancora supportati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodo | Nodo | Il nodo da unire |

 **Result:**
Mesh


---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(scene, scale) | Scala tutte le geometrie (Scala i punti di controllo, non la matrice di trasformazione) in questa scena |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scene | Scena | La scena da scalare |
| scala | Vector3 | Il fattore di scala |

 **Result:**
Mesh


---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(node, scale) | Scala tutte le geometrie (Scala i punti di controllo, non la matrice di trasformazione) in questo nodo |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodo | Nodo | Il nodo da scalare |
| scala | Vector3 | Il fattore di scala |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Nome | Descrizione |
| --- | --- |
| generateNormal(mesh) | Genera dati normali dalla definizione della Mesh |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Nome | Descrizione |
| --- | --- |
| generateUV(mesh, normals) | Genera dati UV dalla mesh di input fornita e dai dati normali specificati. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| mesh | Mesh | La mesh di input |
| normali | VertexElementNormal | I dati normali |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Nome | Descrizione |
| --- | --- |
| generateUV(mesh) | Genera dati UV dalla mesh di input fornita |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| mesh | Mesh | La mesh di input |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nome | Descrizione |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Dividi la mesh in sotto-mesh per VertexElementMaterial. Ogni sotto-mesh utilizzerà un solo materiale. Esegui la divisione della mesh su un nodo |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodo | Nodo | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Crea nodi figli per ogni sotto-mesh. |
| removeOldMesh | boolean | Rimuovi la vecchia mesh dopo la divisione, se questo parametro è false, le mesh vecchie e nuove coesisteranno. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nome | Descrizione |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Dividi la mesh in sotto-mesh per VertexElementMaterial. Ogni sotto-mesh utilizzerà un solo materiale. Esegui la divisione della mesh su tutti i nodi della scena. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scen | Scena | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nome | Descrizione |
| --- | --- |
| splitMesh(mesh, policy) | Dividi la mesh in sotto‑mesh per VertexElementMaterial. Ogni sotto‑mesh utilizzerà un solo materiale. La mesh originale non verrà modificata. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nome | Descrizione |
| --- | --- |
| buildTangentBinormal(scene) | Questo creerà tangente e binormale su tutte le mesh della scena. È necessaria la normale; se la normale non esiste sulla mesh, verrà creata anche la dati della normale dalla posizione. È anche necessario UV; la mesh verrà ignorata se non è definito alcun UV. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nome | Descrizione |
| --- | --- |
| buildTangentBinormal(mesh) | Questo creerà tangente e binormale sulla mesh. È necessaria la normale; se la normale non esiste sulla mesh, verrà creata anche la dati della normale dalla posizione. È anche necessario UV; verrà sollevata un'eccezione se non viene trovato alcun UV. |

 **Result:**
Mesh[]


---



