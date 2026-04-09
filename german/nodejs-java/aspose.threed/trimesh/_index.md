---
title: TriMesh
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Ein **TriMesh** enthält Rohdaten, die direkt von der GPU verwendet werden können.  Diese Klasse ist ein Hilfswerkzeug, um ein Mesh zu erstellen, das nur Vertex-Daten enthält.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name, declaration) | Initialisiere eine Instanz von TriMesh |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Der Name dieses TriMesh |
| declaration | VertexDeclaration | Die Deklaration des Vertex |

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
| getVerticesCount() | Die Anzahl der Scheitelpunkte in diesem TriMesh |

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
| getUnmergedVerticesCount() | Die Anzahl der nicht zusammengeführten Scheitelpunkte, die durch beginVertex() und endVertex() übergeben wurden. |

 **Result:**



---


### getCapacity{#getCapacity}

| Name | Beschreibung |
| --- | --- |
| getCapacity() | Die Kapazität der vorab zugewiesenen Scheitelpunkte. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Name | Beschreibung |
| --- | --- |
| getVerticesSizeInBytes() | Die Gesamtabmessung aller Scheitelpunkte in Bytes |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Name | Beschreibung |
| --- | --- |
| getParentNodes() | Gibt alle übergeordneten Knoten zurück, ein Entity kann für Geometrie-Instanziierung an mehrere übergeordnete Knoten angehängt werden. Die Knoten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Name | Beschreibung |
| --- | --- |
| getExcluded() | Gibt an oder legt fest, ob dieses Entity beim Exportieren ausgeschlossen wird. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Gibt an oder legt fest, ob dieses Entity beim Exportieren ausgeschlossen wird. |

 **Result:**



---


### getParentNode{#getParentNode}

| Name | Beschreibung |
| --- | --- |
| getParentNode() | Gibt den ersten übergeordneten Knoten zurück oder legt ihn fest; wenn der erste übergeordnete Knoten gesetzt wird, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### setParentNode{#setParentNode}

| Name | Beschreibung |
| --- | --- |
| setParentNode(value) | Gibt den ersten übergeordneten Knoten zurück oder legt ihn fest; wenn der erste übergeordnete Knoten gesetzt wird, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### getScene{#getScene}

| Name | Beschreibung |
| --- | --- |
| getScene() | Liefert die Szene, zu der dieses Objekt gehört |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Liefert die Sammlung aller Eigenschaften. |

 **Result:**



---


### fromMesh{#fromMesh}

| Name | Beschreibung |
| --- | --- |
| fromMesh(declaration, mesh) | Erstellen Sie ein TriMesh aus dem angegebenen Mesh-Objekt mit dem angegebenen Scheitelpunktlayout. |

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
| copyFrom(input, vd) | Kopiere das TriMesh von input mit neuem Vertex-Layout |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| input | TriMesh | Das Eingabe‑TriMesh zum Kopieren |
| vd | VertexDeclaration | Die neue Vertex-Deklaration des Ausgabe‑TriMesh |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Name | Beschreibung |
| --- | --- |
| fromMesh(mesh, useFloat) | Erstellen Sie ein TriMesh aus dem angegebenen Mesh-Objekt, wobei die Scheitelpunktdeklaration auf der Struktur des Eingabemeshes basiert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | Verwende den Float‑Typ anstelle des Double‑Typs für jedes Vertex‑Element‑Komponente. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Name | Beschreibung |
| --- | --- |
| beginVertex() | Beginnen Sie mit dem Hinzufügen von Scheitelpunkten |

 **Result:**
Vertex


---


### endVertex{#endVertex}

| Name | Beschreibung |
| --- | --- |
| endVertex() | Beenden Sie das Hinzufügen von Scheitelpunkten |

 **Result:**
Vertex


---


### verticesToArray{#verticesToArray}

| Name | Beschreibung |
| --- | --- |
| verticesToArray() | Konvertiere die Vertex-Daten in ein Byte‑Array |

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
| vd | VertexDeclaration | Scheitelpunkt-Deklaration, muss mindestens ein Feld enthalten. |
| Scheitelpunkte | byte[] | Die Eingabe-Scheitelpunktdaten, die minimale Länge der Scheitelpunkte muss größer oder gleich der Größe der Scheitelpunktdeklaration sein |
| Indizes | Number[] | Die Dreiecksindizes |
| generateVertexMapping | boolean | Erzeugen |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Name | Beschreibung |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Laden Sie Scheitelpunkte aus Bytes, die Länge der Bytes muss ein ganzzahliges Vielfaches der Scheitelpunktgröße sein. |

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
| readVector4(idx, field) | Lese das vector4-Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit dem Datentyp Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Name | Beschreibung |
| --- | --- |
| readFVector4(idx, field) | Lese das vector4-Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit dem Datentyp Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Name | Beschreibung |
| --- | --- |
| readVector3(idx, field) | Lesen Sie das Vector3‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit dem Datentyp Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Name | Beschreibung |
| --- | --- |
| readFVector3(idx, field) | Lesen Sie das Vector3‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit dem Datentyp Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Name | Beschreibung |
| --- | --- |
| readVector2(idx, field) | Lesen Sie das Vector2‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit dem Datentyp Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Name | Beschreibung |
| --- | --- |
| readFVector2(idx, field) | Lesen Sie das Vector2‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit dem Datentyp Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Name | Beschreibung |
| --- | --- |
| readDouble(idx, field) | Lesen Sie das Double‑Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit einem float/double-kompatiblen Datentyp |

 **Result:**
Number


---


### readFloat{#readFloat}

| Name | Beschreibung |
| --- | --- |
| readFloat(idx, field) | Lese das float-Feld |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| idx | Number | Der Index des zu lesenden Scheitelpunkts |
| Feld | VertexField | Das Feld mit einem float/double-kompatiblen Datentyp |

 **Result:**
Number


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Liefert die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |

 **Result:**
Number


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Liefert den Schlüssel des Entitäts-Renderers, der im Renderer registriert ist |

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
| Eigenschaft | Property | Welche Eigenschaft zu entfernen ist |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entferne die angegebene Eigenschaft, die durch ihren Namen identifiziert wird |

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
| getProperty(property) | Liefere den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Object


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| Wert | Object | Der Wert der Eigenschaft |

 **Result:**
Object


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Property


---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für den internen Gebrauch reserviert. |

 **Result:**
Property


---



