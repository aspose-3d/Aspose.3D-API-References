---
title: PolygonModifier
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Hilfsprogramme zum Modifizieren von Polygonen  @hideconstructor


## Methoden

### triangulate{#triangulate}

| Name | Beschreibung |
| --- | --- |
| triangulate(scene) | Konvertiere alle polygonbasierten Meshes in ein vollständiges Dreiecks-Mesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| scene | Szene | Die zu verarbeitende Szene |

 **Result:**



---


### triangulate{#triangulate}

| Name | Beschreibung |
| --- | --- |
| triangulate(mesh) | Konvertiere ein polygonbasiertes Mesh in ein vollständiges Dreiecks-Mesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mesh | Mesh | Das ursprüngliche Nicht-Dreieck-Mesh |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Name | Beschreibung |
| --- | --- |
| mergeMesh(scene) | Konvertiere eine gesamte Szene in ein einzelnes transformiertes Mesh. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| scene | Szene | Die zusammenzufügende Szene |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Name | Beschreibung |
| --- | --- |
| mergeMesh(node) | Konvertiere einen gesamten Knoten in ein einzelnes transformiertes Mesh. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| node | Node | Der zu zusammenzufügenden Knoten |

 **Result:**
Mesh


---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(scene, scale) | Skaliere alle Geometrien(Skaliere die Kontrollpunkte, nicht die Transformationsmatrix) in dieser Szene |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| scene | Szene | Die zu skalierende Szene |
| Skalierung | Vector3 | Der Skalierungsfaktor |

 **Result:**
Mesh


---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(node, scale) | Skaliere alle Geometrien(Skaliere die Kontrollpunkte, nicht die Transformationsmatrix) in diesem Knoten |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| node | Node | Der zu skalierende Knoten |
| Skalierung | Vector3 | Der Skalierungsfaktor |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Name | Beschreibung |
| --- | --- |
| generateNormal(mesh) | Normaldaten aus Mesh-Definition erzeugen |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Name | Beschreibung |
| --- | --- |
| generateUV(mesh, normals) | UV-Daten aus dem angegebenen Eingabemesh und den angegebenen Normaldaten erzeugen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mesh | Mesh | Das Eingabe-Mesh |
| Normalen | VertexElementNormal | Die Normaldaten |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Name | Beschreibung |
| --- | --- |
| generateUV(mesh) | UV-Daten aus dem angegebenen Eingabemesh erzeugen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mesh | Mesh | Das Eingabe-Mesh |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Name | Beschreibung |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Teile das Mesh in Unter-Meshes nach VertexElementMaterial. Jeder Unter-Mesh verwendet nur ein Material. Führe das Mesh-Splitting an einem Knoten aus. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nod | Node | null |
| Richtlinie | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Erstelle Kindknoten für jeden Teil-Mesh. |
| removeOldMesh | boolean | Entferne das alte Mesh nach dem Split, wenn dieser Parameter false ist, existieren das alte und das neue Mesh gleichzeitig. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Name | Beschreibung |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Teile das Mesh in Unter-Meshes nach VertexElementMaterial. Jeder Unter-Mesh verwendet nur ein Material. Führe das Mesh-Splitting an allen Knoten der Szene aus. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Szene | Szene | null |
| Richtlinie | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Name | Beschreibung |
| --- | --- |
| splitMesh(mesh, policy) | Teile das Mesh in Unter-Meshes nach VertexElementMaterial. Jeder Unter-Mesh verwendet nur ein Material. Das ursprüngliche Mesh wird nicht geändert. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Name | Beschreibung |
| --- | --- |
| buildTangentBinormal(scene) | Dies erzeugt Tangenten und Binormale in allen Meshes der Szene. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden sie ebenfalls aus den Positionen erzeugt. UVs sind ebenfalls erforderlich, das Mesh wird ignoriert, wenn keine UV definiert ist. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Name | Beschreibung |
| --- | --- |
| buildTangentBinormal(mesh) | Dies erzeugt Tangenten und Binormale im Mesh. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden sie ebenfalls aus den Positionen erzeugt. UVs sind ebenfalls erforderlich, es wird eine Ausnahme ausgelöst, wenn keine UV gefunden wird. |

 **Result:**
Mesh[]


---



