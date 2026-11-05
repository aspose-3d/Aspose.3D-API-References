---
title: "Mesh"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/mesh/
---
## Mesh class

Ein Mesh besteht aus vielen n-seitigen Polygonen.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Mesh-Klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Mesh-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

 **Result:**



---


### getEdges{#getEdges}

| Name | Beschreibung |
| --- | --- |
| getEdges() | Liest die Kanten des Meshs. Eine Kante ist im Mesh optional, daher kann sie leer sein. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Name | Beschreibung |
| --- | --- |
| getPolygonCount() | Liest die Anzahl der Polygone. Die Polygonanzahl. |

 **Result:**



---


### getPolygons{#getPolygons}

| Name | Beschreibung |
| --- | --- |
| getPolygons() | Liest die Polygondefinition des Meshs |

 **Result:**



---


### getVisible{#getVisible}

| Name | Beschreibung |
| --- | --- |
| getVisible() | Liest oder setzt, ob die Geometrie sichtbar ist |

 **Result:**



---


### setVisible{#setVisible}

| Name | Beschreibung |
| --- | --- |
| setVisible(value) | Liest oder setzt, ob die Geometrie sichtbar ist |

 **Result:**



---


### getDeformers{#getDeformers}

| Name | Beschreibung |
| --- | --- |
| getDeformers() | Liest alle Deformer, die mit dieser Geometrie verknüpft sind. Die Deformer. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Name | Beschreibung |
| --- | --- |
| getControlPoints() | Liest alle Kontrollpunkte |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Name | Beschreibung |
| --- | --- |
| getCastShadows() | Liest oder setzt, ob diese Geometrie Schatten werfen kann |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Name | Beschreibung |
| --- | --- |
| setCastShadows(value) | Liest oder setzt, ob diese Geometrie Schatten werfen kann |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Name | Beschreibung |
| --- | --- |
| getReceiveShadows() | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Name | Beschreibung |
| --- | --- |
| setReceiveShadows(value) | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |

 **Result:**



---


### getVertexElements{#getVertexElements}

| Name | Beschreibung |
| --- | --- |
| getVertexElements() | Liest alle Vertex-Elemente |

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


### getPolygonSize{#getPolygonSize}

| Name | Beschreibung |
| --- | --- |
| getPolygonSize(index) | Liest die Vertex-Anzahl des angegebenen Polygons. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| index | Zahl | Index. |

 **Result:**
Zahl


---


### createPolygon{#createPolygon}

| Name | Beschreibung |
| --- | --- |
| createPolygon(indices, offset, length) | Erstellt ein neues Polygon mit allen in den Indizes definierten Eckpunkten. Um das Polygon Eckpunkt für Eckpunkt zu erstellen, verwenden Sie bitte PolygonBuilder. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| indices | Number[] | Array der Polygon-Indizes, wobei jeder Index auf einen Kontrollpunkt verweist, der das Polygon bildet. |
| offset | Zahl | Der Versatz des ersten Polygon-Index |
| length | Zahl | Die Länge der Indizes |

 **Result:**
Zahl


---


### createPolygon{#createPolygon}

| Name | Beschreibung |
| --- | --- |
| createPolygon(indices) | Erstellt ein neues Polygon mit allen in den Indizes definierten Eckpunkten. Um das Polygon Eckpunkt für Eckpunkt zu erstellen, verwenden Sie bitte PolygonBuilder. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| indices | Number[] | Array der Polygon-Indizes, wobei jeder Index auf einen Kontrollpunkt verweist, der das Polygon bildet. |

 **Result:**
Zahl


---


### createPolygon{#createPolygon}

| Name | Beschreibung |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | Erstelle ein Polygon mit 4 Eckpunkten (Quad) |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| v1 | Zahl | Index des ersten Eckpunkts |
| v2 | Zahl | Index des zweiten Eckpunkts |
| v3 | Zahl | Index des dritten Eckpunkts |
| v4 | Zahl | Index des vierten Eckpunkts |

 **Result:**
Zahl


---


### createPolygon{#createPolygon}

| Name | Beschreibung |
| --- | --- |
| createPolygon(v1, v2, v3) | Erstelle ein Polygon mit 3 Eckpunkten (Dreieck) |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| v1 | Zahl | Index des ersten Eckpunkts |
| v2 | Zahl | Index des zweiten Eckpunkts |
| v3 | Zahl | Index des dritten Eckpunkts |

 **Result:**
Zahl


---


### toMesh{#toMesh}

| Name | Beschreibung |
| --- | --- |
| toMesh() | Liefert die Mesh-Instanz aus dem aktuellen Entity. |

 **Result:**
Mesh


---


### getElement{#getElement}

| Name | Beschreibung |
| --- | --- |
| getElement(type) | Liefert ein Vertex-Element mit dem angegebenen Typ |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Name | Beschreibung |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Gibt eine VertexElementUV-Instanz mit dem angegebenen Texturzuordnungstyp zurück |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Name | Beschreibung |
| --- | --- |
| createElement(type) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es zur Geometrie hinzu. Wenn der Typ VertexElementType.UV ist, wird ein VertexElementUV mit Texturzuordnungstyp zu TextureMapping.DIFFUSE erstellt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Name | Beschreibung |
| --- | --- |
| addElement(element) | Fügt ein vorhandenes Vertex-Element zur aktuellen Geometrie hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| element | VertexElement | Das hinzuzufügende Vertex-Element |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Name | Beschreibung |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es zur Geometrie hinzu. Wenn der Typ VertexElementType.UV ist, wird ein VertexElementUV mit Texturzuordnungstyp zu TextureMapping.DIFFUSE erstellt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Name | Beschreibung |
| --- | --- |
| createElementUV(uvMapping) | Erstellt ein VertexElementUV mit dem angegebenen Texturzuordnungstyp. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Name | Beschreibung |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Erstellt ein VertexElementUV mit dem angegebenen Texturzuordnungstyp. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

 **Result:**
VertexElementUV


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



