---
title: "PolygonModifier"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Verktyg för att modifiera polygoner  @hideconstructor


## Metoder

### triangulate{#triangulate}

| Namn | Beskrivning |
| --- | --- |
| triangulate(scene) | Konvertera alla polygonbaserade mesh till en fullständig triangulär mesh |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| scen | Scene | Scenen att bearbeta |

 **Result:**



---


### triangulate{#triangulate}

| Namn | Beskrivning |
| --- | --- |
| triangulate(mesh) | Konvertera ett polygonbaserat mesh till en fullständig triangulär mesh |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mesh | Mesh | Det ursprungliga icke-triangulära meshet |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Namn | Beskrivning |
| --- | --- |
| mergeMesh(scene) | Konvertera en hel scen till ett enda transformerat mesh. Vertex-element som normal-/texturkoordinater stöds ännu inte |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| scen | Scene | Scenen att slå ihop |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Namn | Beskrivning |
| --- | --- |
| mergeMesh(node) | Konvertera en hel nod till ett enda transformerat mesh. Vertex-element som normal-/texturkoordinater stöds ännu inte |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nod | Nod | Noden att slå ihop |

 **Result:**
Mesh


---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| scale(scene, scale) | Skala alla geometrier (Skala kontrollpunkterna, inte transformationsmatrisen) i denna scen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| scen | Scene | Scenen att skala |
| scale | Vector3 | Skalfaktorn |

 **Result:**
Mesh


---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| scale(node, scale) | Skala alla geometrier (Skala kontrollpunkterna, inte transformationsmatrisen) i denna nod |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nod | Nod | Noden att skala |
| scale | Vector3 | Skalfaktorn |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Namn | Beskrivning |
| --- | --- |
| generateNormal(mesh) | Generera normaldata från Mesh-definitionen |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Namn | Beskrivning |
| --- | --- |
| generateUV(mesh, normals) | Generera UV-data från den givna inmatningsmeshen och den specificerade normaldatan. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mesh | Mesh | Den inmatningsmeshen |
| normaler | VertexElementNormal | Normaldatan |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Namn | Beskrivning |
| --- | --- |
| generateUV(mesh) | Generera UV-data från den givna inmatningsmeshen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mesh | Mesh | Den inmatningsmeshen |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Namn | Beskrivning |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Dela mesh i del-meshar med VertexElementMaterial. Varje del-mesh kommer att använda endast ett material. Utför meshdelning på en nod. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nod | Nod | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Skapa barnnoder för varje del-mesh. |
| removeOldMesh | boolean | Ta bort den gamla meshen efter delning, om denna parameter är falsk, kommer den gamla och den nya meshen att existera samtidigt. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Namn | Beskrivning |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Dela mesh i del-meshar med VertexElementMaterial. Varje del-mesh kommer att använda endast ett material. Utför meshdelning på alla noder i scenen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| scen | Scene | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Namn | Beskrivning |
| --- | --- |
| splitMesh(mesh, policy) | Dela mesh i del-meshar med VertexElementMaterial. Varje del-mesh kommer att använda endast ett material. Den ursprungliga meshen kommer inte att ändras. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Namn | Beskrivning |
| --- | --- |
| buildTangentBinormal(scene) | Detta kommer att skapa tangent och binormal på alla meshar i scenen. Normal är krävd, om normal inte finns på meshen, kommer den också att skapa normaldata från position. UV är också krävt, meshen kommer att ignoreras om ingen UV är definierad. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Namn | Beskrivning |
| --- | --- |
| buildTangentBinormal(mesh) | Det här kommer att skapa tangent och binormal på meshen. Normal krävs; om normal inte finns på meshen kommer den också att skapa normaldata från positionen. UV krävs också, ett undantag kommer att kastas om ingen UV hittas. |

 **Result:**
Mesh[]


---



