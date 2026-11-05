---
title: "TriMesh"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Ein TriMesh enthält Rohdaten, die direkt von der GPU verwendet werden können.  Diese Klasse ist ein Hilfswerkzeug zum Erstellen eines Meshes, das nur per-Vertex-Daten enthält.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| Konstruktor(name, declaration) | Initialisiere eine Instanz von TriMesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der Name dieses TriMesh |
| Deklaration | VertexDeclaration | Die Deklaration des Vertex |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Name | Beschreibung |
| --- | --- |
| getVertexDeclaration() | Das Vertex-Layout des TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Name | Beschreibung |
| --- | --- |
| getVerticesCount() | Die Anzahl der Vertices in diesem TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Name | Beschreibung |
| --- | --- |
| getIndicesCount() | Die Anzahl der Indizes in diesem TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Name | Beschreibung |
| --- | --- |
| getUnmergedVerticesCount() | Die Anzahl der nicht zusammengeführten Vertices, die durch beginVertex() und endVertex() übergeben wurden. |

 **Result:**



---


### getCapacity{#getCapacity}

| Name | Beschreibung |
| --- | --- |
| getCapacity() | Die Kapazität vorab zugewiesener Vertices. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Name | Beschreibung |
| --- | --- |
| getVerticesSizeInBytes() | Die Gesamtgröße aller Scheitelpunkte in Bytes |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Name | Beschreibung |
| --- | --- |
| getParentNodes() | Gibt alle übergeordneten Knoten zurück, ein Entity kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. Die Knoten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Name | Beschreibung |
| --- | --- |
| getExcluded() | Liest oder setzt, ob dieses Entity beim Exportieren ausgeschlossen werden soll. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Liest oder setzt, ob dieses Entity beim Exportieren ausgeschlossen werden soll. |

 **Result:**



---


### getParentNode{#getParentNode}

| Name | Beschreibung |
| --- | --- |
| getParentNode() | Liest oder setzt den ersten übergeordneten Knoten, wenn der erste übergeordnete Knoten gesetzt ist, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### setParentNode{#setParentNode}

| Name | Beschreibung |
| --- | --- |
| setParentNode(value) | Liest oder setzt den ersten übergeordneten Knoten, wenn der erste übergeordnete Knoten gesetzt ist, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### getScene{#getScene}

| Name | Beschreibung |
| --- | --- |
| getScene() | Ruft die Szene ab, zu der dieses Objekt gehört |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Ruft die Sammlung aller Eigenschaften ab. |

 **Result:**



---


### fromMesh{#fromMesh}

| Name | Beschreibung |
| --- | --- |
| fromMesh(declaration, mesh) | Erstelle ein TriMesh aus dem angegebenen Mesh-Objekt mit dem angegebenen Scheitelpunkt-Layout. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Name | Beschreibung |
| --- | --- |
| copyFrom(input, vd) | Kopiere das TriMesh von input mit neuem Scheitelpunkt-Layout |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | TriMesh | Das input TriMesh zum Kopieren |
| vd | VertexDeclaration | Die neue Scheitelpunkt-Deklaration des Ausgabe‑TriMesh |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Name | Beschreibung |
| --- | --- |
| fromMesh(mesh, useFloat) | Erstelle ein TriMesh aus dem angegebenen Mesh-Objekt, die Scheitelpunkt-Deklaration basiert auf der Struktur des Eingabe‑Mesh. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | Verwende den float‑Typ anstelle des double‑Typs für jedes Scheitelpunkt-Element. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Name | Beschreibung |
| --- | --- |
| beginVertex() | Beginne das Hinzufügen eines Scheitelpunkts |

 **Result:**
Vertex


---


### endVertex{#endVertex}

| Name | Beschreibung |
| --- | --- |
| endVertex() | Beende das Hinzufügen eines Scheitelpunkts |

 **Result:**
Vertex


---


### verticesToArray{#verticesToArray}

| Name | Beschreibung |
| --- | --- |
| verticesToArray() | Konvertiere die Scheitelpunktdaten in ein Byte‑Array |

 **Result:**
byte[]


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| Name | Beschreibung |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Erstelle TriMesh aus Rohdaten. Das zurückgegebene TriMesh kopiert das Eingabe‑Byte‑Array aus Leistungsgründen nicht; externe Änderungen am Array werden in dieser Instanz widergespiegelt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| vd | VertexDeclaration | Vertex-Deklaration muss mindestens ein Feld enthalten. |
| Scheitelpunkte | byte[] | Die Eingabe‑Vertex‑Daten, die minimale Länge der Vertices muss größer oder gleich der Größe der Vertex-Deklaration sein. |
| indices | Number[] | Die Dreieck-Indizes |
| generateVertexMapping | boolean | Generieren |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Name | Beschreibung |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Lade Vertices aus Bytes, die Länge der Bytes muss ein ganzzahliges Vielfaches der Vertex‑Größe sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Name | Beschreibung |
| --- | --- |
| readVector4(idx, field) | Lese das Vector4‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit dem Datentyp Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Name | Beschreibung |
| --- | --- |
| readFVector4(idx, field) | Lese das Vector4‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit dem Datentyp Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Name | Beschreibung |
| --- | --- |
| readVector3(idx, field) | Lese das Vector3‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit dem Datentyp Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Name | Beschreibung |
| --- | --- |
| readFVector3(idx, field) | Lese das Vector3‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit dem Datentyp Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Name | Beschreibung |
| --- | --- |
| readVector2(idx, field) | Lese das Vector2‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit dem Datentyp Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Name | Beschreibung |
| --- | --- |
| readFVector2(idx, field) | Lese das Vector2‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit dem Datentyp Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Name | Beschreibung |
| --- | --- |
| readDouble(idx, field) | Lese das double-Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit einem float/double-kompatiblen Datentyp |

 **Result:**
Zahl


---


### readFloat{#readFloat}

| Name | Beschreibung |
| --- | --- |
| readFloat(idx, field) | Lese das float-Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Zahl | Der Index des zu lesenden Vertex |
| field | VertexField | Das Feld mit einem float/double-kompatiblen Datentyp |

 **Result:**
Zahl


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

 **Result:**
Zahl


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Ruft den Schlüssel des im Renderer registrierten Entity-Renderers ab. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt eine dynamische Eigenschaft. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | Eigenschaft | Welche Eigenschaft entfernt werden soll |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt die angegebene Eigenschaft, die durch den Namen identifiziert wird. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Name | Beschreibung |
| --- | --- |
| getProperty(property) | Rufe den Wert der angegebenen Eigenschaft ab. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| value | Objekt | Der Wert der Eigenschaft |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Eigenschaft


---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für die interne Verwendung reserviert. |

 **Result:**
Eigenschaft


---



