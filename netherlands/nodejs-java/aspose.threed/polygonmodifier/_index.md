---
title: "PolygonModifier"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Hulpmiddelen om polygonen te wijzigen  @hideconstructor


## Methoden

### triangulate{#triangulate}

| Naam | Beschrijving |
| --- | --- |
| triangulate(scene) | Converteer alle op polygonen gebaseerde meshes naar een volledige driehoekmesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| scene | Scene | De scène die verwerkt moet worden |

 **Result:**



---


### triangulate{#triangulate}

| Naam | Beschrijving |
| --- | --- |
| triangulate(mesh) | Converteer een op polygonen gebaseerde mesh naar een volledige driehoekmesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mesh | Mesh | De originele niet-driehoekmesh |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Naam | Beschrijving |
| --- | --- |
| mergeMesh(scene) | Converteer een volledige scène naar een enkele getransformeerde mesh. Vertex-elementen zoals normale-/textuurcoördinaten worden nog niet ondersteund. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| scene | Scene | De scène die moet worden samengevoegd |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Naam | Beschrijving |
| --- | --- |
| mergeMesh(node) | Converteer een volledige node naar een enkele getransformeerde mesh. Vertex-elementen zoals normale-/textuurcoördinaten worden nog niet ondersteund. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| node | Node | De node die moet worden samengevoegd |

 **Result:**
Mesh


---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(scene, scale) | Schaal alle geometrieën (Schaal de controlepunten, niet de transformatie-matrix) in deze scène |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| scene | Scene | De scène die geschaald moet worden |
| schaal | Vector3 | De schaalfactor |

 **Result:**
Mesh


---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(node, scale) | Schaal alle geometrieën (Schaal de controlepunten, niet de transformatie-matrix) in deze node |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| node | Node | De node die geschaald moet worden |
| schaal | Vector3 | De schaalfactor |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Naam | Beschrijving |
| --- | --- |
| generateNormal(mesh) | Genereer normale gegevens van Mesh-definitie |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Naam | Beschrijving |
| --- | --- |
| generateUV(mesh, normals) | Genereer UV-gegevens van het opgegeven invoer‑mesh en gespecificeerde normale gegevens. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mesh | Mesh | Het invoer‑mesh |
| normaalvectoren | VertexElementNormal | De normale gegevens |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Naam | Beschrijving |
| --- | --- |
| generateUV(mesh) | Genereer UV-gegevens van het opgegeven invoer‑mesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mesh | Mesh | Het invoer‑mesh |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Naam | Beschrijving |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Splits mesh in sub‑meshes op basis van VertexElementMaterial. Elke sub‑mesh gebruikt slechts één materiaal. Voer mesh‑splitsing uit op een node. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nod | Node | null |
| beleid | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Maak kind‑nodes aan voor elke sub‑mesh. |
| removeOldMesh | boolean | Verwijder het oude mesh na het splitsen; als deze parameter onwaar is, zullen het oude en nieuwe mesh naast elkaar bestaan. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Naam | Beschrijving |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Splits mesh in sub‑meshes op basis van VertexElementMaterial. Elke sub‑mesh gebruikt slechts één materiaal. Voer mesh‑splitsing uit op alle nodes van de scene. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| scen | Scene | null |
| beleid | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Naam | Beschrijving |
| --- | --- |
| splitMesh(mesh, policy) | Splits mesh in sub‑meshes op basis van VertexElementMaterial. Elke sub‑mesh gebruikt slechts één materiaal. Het oorspronkelijke mesh wordt niet gewijzigd. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Naam | Beschrijving |
| --- | --- |
| buildTangentBinormal(scene) | Dit zal tangent en binormaal creëren op alle meshes van de scene. Normaal is vereist; als normaal niet aanwezig is op het mesh, wordt de normale data ook gecreëerd vanuit de positie. UV is ook vereist; het mesh wordt genegeerd als er geen UV is gedefinieerd. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Naam | Beschrijving |
| --- | --- |
| buildTangentBinormal(mesh) | Dit zal tangent en binormaal op het mesh creëren. Normaal is vereist, als normaal niet bestaat op het mesh, wordt ook de normaaldata van de positie gecreëerd. UV is ook vereist, er wordt een uitzondering opgegooid als er geen UV wordt gevonden. |

 **Result:**
Mesh[]


---



