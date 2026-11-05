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
| scene | Scene | De scène om te verwerken |

 **Result:**



---


### triangulate{#triangulate}

| Naam | Beschrijving |
| --- | --- |
| triangulate(mesh) | Converteer een op polygonen gebaseerde mesh naar een volledige driehoekmesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mesh | Mesh | De oorspronkelijke niet-driehoek mesh |

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
| scene | Scene | De scène om te combineren |

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
| node | Node | De node om te combineren |

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
| scene | Scene | De scène om te schalen |
| schaal | Vector3 | De schaalfactor |

 **Result:**
Mesh


---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(node, scale) | Schaal alle geometrieën (Schaal de controlepunten, niet de transformatie matrix) in dit knooppunt |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| node | Node | Het knooppunt om te schalen |
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
| generateUV(mesh, normals) | Genereer UV-gegevens van de opgegeven invoer-mesh en gespecificeerde normale gegevens. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mesh | Mesh | De invoer-mesh |
| normals | VertexElementNormal | De normale gegevens |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Naam | Beschrijving |
| --- | --- |
| generateUV(mesh) | Genereer UV-gegevens van de opgegeven invoer-mesh |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mesh | Mesh | De invoer-mesh |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Naam | Beschrijving |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Splits mesh in sub-meshes op basis van VertexElementMaterial. Elke sub-mesh zal slechts één materiaal gebruiken. Voer mesh-splitsing uit op een knooppunt. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nod | Node | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Maak kindknooppunten voor elke sub-mesh aan. |
| removeOldMesh | boolean | Verwijder de oude mesh na het splitsen, als deze parameter onwaar is, zullen de oude en nieuwe meshes naast elkaar bestaan. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Naam | Beschrijving |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Splits mesh in sub-meshes op basis van VertexElementMaterial. Elke sub-mesh zal slechts één materiaal gebruiken. Voer mesh-splitsing uit op alle knooppunten van de scène. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| scen | Scene | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Naam | Beschrijving |
| --- | --- |
| splitMesh(mesh, policy) | Splits het mesh in sub-meshes op basis van VertexElementMaterial. Elke sub-mesh gebruikt slechts één materiaal. Het oorspronkelijke mesh wordt niet gewijzigd. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Naam | Beschrijving |
| --- | --- |
| buildTangentBinormal(scene) | Dit maakt tangent- en binormale vectoren aan op alle meshes van de scène. Normaal is vereist; als een normaal niet bestaat op het mesh, wordt de normaaldata ook aangemaakt vanuit de positie. UV is ook vereist; het mesh wordt genegeerd als er geen UV is gedefinieerd. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Naam | Beschrijving |
| --- | --- |
| buildTangentBinormal(mesh) | Dit maakt tangent- en binormale vectoren aan op het mesh. Normaal is vereist; als een normaal niet bestaat op het mesh, wordt de normaaldata ook aangemaakt vanuit de positie. UV is ook vereist; er wordt een uitzondering opgegooid als er geen UV wordt gevonden. |

 **Result:**
Mesh[]


---



