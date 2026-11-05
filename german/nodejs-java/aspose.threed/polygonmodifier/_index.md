---
title: "PolygonModifier"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Hilfsprogramme zum Ändern von Polygonen  @hideconstructor


## Methoden

### triangulate{#triangulate}

| Name | Beschreibung |
| --- | --- |
| triangulate(scene) | Konvertiere alle polygonbasierten Meshes in ein vollständiges Dreiecks-Mesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Szene | Szene | Die zu verarbeitende Szene |

 **Result:**



---


### triangulate{#triangulate}

| Name | Beschreibung |
| --- | --- |
| triangulate(mesh) | Konvertiere ein polygonbasiertes Mesh in ein vollständiges Dreiecks-Mesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mesh | Mesh | Das ursprüngliche Nicht-Dreiecks-Mesh |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Name | Beschreibung |
| --- | --- |
| mergeMesh(scene) | Konvertiere eine gesamte Szene in ein einzelnes transformiertes Mesh. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Szene | Szene | Die Szene zum Zusammenführen |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Name | Beschreibung |
| --- | --- |
| mergeMesh(node) | Konvertiere einen gesamten Knoten in ein einzelnes transformiertes Mesh. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Der Knoten zum Zusammenführen |

 **Result:**
Mesh


---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(scene, scale) | Skaliere alle Geometrien (Skaliere die Kontrollpunkte, nicht die Transformationsmatrix) in dieser Szene |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Szene | Szene | Die Szene zum Skalieren |
| Skalierung | Vector3 | Der Skalierungsfaktor |

 **Result:**
Mesh


---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(node, scale) | Skaliere alle Geometrien (Skaliere die Kontrollpunkte, nicht die Transformationsmatrix) in diesem Knoten |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Der Knoten zum Skalieren |
| Skalierung | Vector3 | Der Skalierungsfaktor |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Name | Beschreibung |
| --- | --- |
| generateNormal(mesh) | Generiere Normaldaten aus der Mesh-Definition |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Name | Beschreibung |
| --- | --- |
| generateUV(mesh, normals) | Generiere UV-Daten aus dem angegebenen Eingabe-Mesh und den spezifizierten Normaldaten. |

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
| generateUV(mesh) | Generiere UV-Daten aus dem angegebenen Eingabemesh |

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
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Teile das Mesh anhand von VertexElementMaterial in Teil-Meshes auf. Jeder Teil-Mesh verwendet nur ein Material. Führe das Mesh-Splitting an einem Knoten durch. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nod | Knoten | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Erstelle Kindknoten für jedes Teil-Mesh. |
| removeOldMesh | boolean | Entferne das alte Mesh nach dem Split, wenn dieser Parameter false ist, existieren das alte und das neue Mesh gleichzeitig. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Name | Beschreibung |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Teile das Mesh anhand von VertexElementMaterial in Teil-Meshes auf. Jeder Teil-Mesh verwendet nur ein Material. Führe das Mesh-Splitting an allen Knoten der Szene durch. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| scen | Szene | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Name | Beschreibung |
| --- | --- |
| splitMesh(mesh, policy) | Teile das Mesh anhand von VertexElementMaterial in Teil-Meshes auf. Jeder Teil-Mesh verwendet nur ein Material. Das ursprüngliche Mesh wird nicht verändert. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Name | Beschreibung |
| --- | --- |
| buildTangentBinormal(scene) | Dies erstellt Tangenten und Binormale für alle Meshes der Szene. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden die Normaldaten aus der Position erstellt. UV ist ebenfalls erforderlich, das Mesh wird ignoriert, wenn keine UV definiert ist. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Name | Beschreibung |
| --- | --- |
| buildTangentBinormal(mesh) | Dies erstellt Tangenten und Binormale für das Mesh. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden die Normaldaten aus der Position erstellt. UV ist ebenfalls erforderlich, es wird eine Ausnahme ausgelöst, wenn keine UV gefunden wird. |

 **Result:**
Mesh[]


---



