---
title: "PolygonModifier"
second_title: "Aspose.3D per Node.js via Java API Reference"
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
| triangulate(scene) | Converti tutte le mesh basate su poligoni in una mesh completa di triangoli |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scena | Scene | La scena da elaborare |

 **Result:**



---


### triangulate{#triangulate}

| Nome | Descrizione |
| --- | --- |
| triangulate(mesh) | Converti una mesh basata su poligoni in una mesh completa di triangoli |

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
| mergeMesh(scene) | Converti un'intera scena in una singola mesh trasformata. Gli elementi dei vertici, come le normali/coordinate di texture, non sono ancora supportati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scena | Scene | La scena da unire |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nome | Descrizione |
| --- | --- |
| mergeMesh(node) | Converti un intero nodo in una singola mesh trasformata. Gli elementi dei vertici, come le normali/coordinate di texture, non sono ancora supportati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| node | Nodo | Il nodo da unire |

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
| scena | Scene | La scena da scalare |
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
| node | Nodo | Il nodo da scalare |
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
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Dividi la mesh in sotto-mesh per VertexElementMaterial. Ogni sotto-mesh utilizzerà un solo materiale. Esegui lo split della mesh su un nodo |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nod | Nodo | null |
| politica | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Crea nodi figlio per ogni sotto-mesh. |
| removeOldMesh | boolean | Rimuovi la mesh vecchia dopo lo split; se questo parametro è false, le mesh vecchia e nuova coesisteranno. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nome | Descrizione |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Dividi la mesh in sotto-mesh per VertexElementMaterial. Ogni sotto-mesh utilizzerà un solo materiale. Esegui lo split della mesh su tutti i nodi della scena. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scena | Scene | null |
| politica | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nome | Descrizione |
| --- | --- |
| splitMesh(mesh, policy) | Dividi la mesh in sotto-mesh per VertexElementMaterial. Ogni sotto-mesh utilizzerà un solo materiale. La mesh originale non verrà modificata. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nome | Descrizione |
| --- | --- |
| buildTangentBinormal(scene) | Questo creerà tangente e binormale su tutte le mesh della scena. È necessaria la normale; se la normale non esiste sulla mesh, verranno creati anche i dati normali dalla posizione. È anche necessaria la UV; la mesh verrà ignorata se non è definita alcuna UV. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nome | Descrizione |
| --- | --- |
| buildTangentBinormal(mesh) | Questo creerà tangente e binormale sulla mesh, la normale è necessaria; se la normale non esiste sulla mesh, verrà anche creata la dati della normale dalla posizione. Le UV sono anch'esse necessarie, verrà sollevata un'eccezione se non vengono trovate UV. |

 **Result:**
Mesh[]


---



