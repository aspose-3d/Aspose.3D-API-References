---
title: "Mesh"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/mesh/
---
## Mesh class

Een mesh bestaat uit vele n-zijdige polygonen.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuwe instantie van de Mesh-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuwe instantie van de Mesh-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### getEdges{#getEdges}

| Naam | Beschrijving |
| --- | --- |
| getEdges() | Haalt de randen van de Mesh op. Een rand is optioneel in een mesh, dus deze kan leeg zijn. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Naam | Beschrijving |
| --- | --- |
| getPolygonCount() | Haalt het aantal polygonen op. Het polygonenaantal. |

 **Result:**



---


### getPolygons{#getPolygons}

| Naam | Beschrijving |
| --- | --- |
| getPolygons() | Haalt de definitie van de polygonen van de mesh op |

 **Result:**



---


### getVisible{#getVisible}

| Naam | Beschrijving |
| --- | --- |
| getVisible() | Haalt op of stelt in of de geometrie zichtbaar is |

 **Result:**



---


### setVisible{#setVisible}

| Naam | Beschrijving |
| --- | --- |
| setVisible(value) | Haalt op of stelt in of de geometrie zichtbaar is |

 **Result:**



---


### getDeformers{#getDeformers}

| Naam | Beschrijving |
| --- | --- |
| getDeformers() | Haalt alle deformers op die aan deze geometrie zijn gekoppeld. De deformers. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Naam | Beschrijving |
| --- | --- |
| getControlPoints() | Haalt alle controlepunten op |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Naam | Beschrijving |
| --- | --- |
| getCastShadows() | Haalt op of stelt in of deze geometrie schaduw kan werpen |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Naam | Beschrijving |
| --- | --- |
| setCastShadows(value) | Haalt op of stelt in of deze geometrie schaduw kan werpen |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Naam | Beschrijving |
| --- | --- |
| getReceiveShadows() | Haalt op of stelt in of deze geometrie schaduwen kan ontvangen. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Naam | Beschrijving |
| --- | --- |
| setReceiveShadows(value) | Haalt op of stelt in of deze geometrie schaduwen kan ontvangen. |

 **Result:**



---


### getVertexElements{#getVertexElements}

| Naam | Beschrijving |
| --- | --- |
| getVertexElements() | Haalt alle vertex-elementen op |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Naam | Beschrijving |
| --- | --- |
| getParentNodes() | Haalt alle bovenliggende knooppunten op, een entiteit kan aan meerdere bovenliggende knooppunten worden gekoppeld voor geometrie‑instantiatie. De knooppunten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Naam | Beschrijving |
| --- | --- |
| getExcluded() | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |

 **Result:**



---


### setExcluded{#setExcluded}

| Naam | Beschrijving |
| --- | --- |
| setExcluded(value) | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |

 **Result:**



---


### getParentNode{#getParentNode}

| Naam | Beschrijving |
| --- | --- |
| getParentNode() | Haalt op of stelt het eerste bovenliggende knooppunt in, als het eerste bovenliggende knooppunt wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knooppunten. Het bovenliggende knooppunt. |

 **Result:**



---


### setParentNode{#setParentNode}

| Naam | Beschrijving |
| --- | --- |
| setParentNode(value) | Haalt op of stelt het eerste bovenliggende knooppunt in, als het eerste bovenliggende knooppunt wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knooppunten. Het bovenliggende knooppunt. |

 **Result:**



---


### getScene{#getScene}

| Naam | Beschrijving |
| --- | --- |
| getScene() | Haalt de scène op waartoe dit object behoort |

 **Result:**



---


### getName{#getName}

| Naam | Beschrijving |
| --- | --- |
| getName() | Haalt de naam op of stelt deze in. De naam. |

 **Result:**



---


### setName{#setName}

| Naam | Beschrijving |
| --- | --- |
| setName(value) | Haalt de naam op of stelt deze in. De naam. |

 **Result:**



---


### getProperties{#getProperties}

| Naam | Beschrijving |
| --- | --- |
| getProperties() | Haalt de verzameling van alle eigenschappen op. |

 **Result:**



---


### getPolygonSize{#getPolygonSize}

| Naam | Beschrijving |
| --- | --- |
| getPolygonSize(index) | Haalt het aantal vertices op van de opgegeven polygon. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| index | Nummer | Index. |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Naam | Beschrijving |
| --- | --- |
| createPolygon(indices, offset, length) | Maakt een nieuwe polygon met alle vertices gedefinieerd in indices. Om een polygon vertex voor vertex te maken, gebruik alstublieft PolygonBuilder. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| indices | Number[] | Array van de polygon-indices, elke index wijst naar een controlepunt dat de polygon vormt. |
| offset | Nummer | De offset van de eerste polygon-index |
| length | Nummer | De lengte van de indices |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Naam | Beschrijving |
| --- | --- |
| createPolygon(indices) | Maakt een nieuwe polygon met alle vertices gedefinieerd in indices. Om een polygon vertex voor vertex te maken, gebruik alstublieft PolygonBuilder. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| indices | Number[] | Array van de polygon-indices, elke index wijst naar een controlepunt dat de polygon vormt. |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Naam | Beschrijving |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | Maak een polygon met 4 vertices (quad) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| v1 | Nummer | Index van de eerste vertex |
| v2 | Nummer | Index van de tweede vertex |
| v3 | Nummer | Index van de derde vertex |
| v4 | Nummer | Index van de vierde vertex |

 **Result:**
Nummer


---


### createPolygon{#createPolygon}

| Naam | Beschrijving |
| --- | --- |
| createPolygon(v1, v2, v3) | Maak een polygon met 3 vertices(driehoek) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| v1 | Nummer | Index van de eerste vertex |
| v2 | Nummer | Index van de tweede vertex |
| v3 | Nummer | Index van de derde vertex |

 **Result:**
Nummer


---


### toMesh{#toMesh}

| Naam | Beschrijving |
| --- | --- |
| toMesh() | Haalt de Mesh‑instantie op van de huidige entiteit. |

 **Result:**
Mesh


---


### getElement{#getElement}

| Naam | Beschrijving |
| --- | --- |
| getElement(type) | Haalt een vertex‑element op met opgegeven type |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Naam | Beschrijving |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Haalt een VertexElementUV‑instantie op met gegeven texture‑mapping type |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Naam | Beschrijving |
| --- | --- |
| createElement(type) | Maakt een vertex‑element met opgegeven type en voegt het toe aan de geometrie. Als type VertexElementType.UV is, wordt een VertexElementUV met texture‑mapping type naar TextureMapping.DIFFUSE aangemaakt. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Naam | Beschrijving |
| --- | --- |
| addElement(element) | Voegt een bestaand vertex‑element toe aan de huidige geometrie |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| element | VertexElement | Het vertex‑element om toe te voegen |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Naam | Beschrijving |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Maakt een vertex‑element met opgegeven type en voegt het toe aan de geometrie. Als type VertexElementType.UV is, wordt een VertexElementUV met texture‑mapping type naar TextureMapping.DIFFUSE aangemaakt. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Naam | Beschrijving |
| --- | --- |
| createElementUV(uvMapping) | Maakt een VertexElementUV met het opgegeven textuurmappingtype. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Naam | Beschrijving |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Maakt een VertexElementUV met het opgegeven textuurmappingtype. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt de begrenzingsvak op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |

 **Result:**
VertexElementUV


---


### getEntityRendererKey{#getEntityRendererKey}

| Naam | Beschrijving |
| --- | --- |
| getEntityRendererKey() | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Naam | Beschrijving |
| --- | --- |
| removeProperty(property) | Verwijdert een dynamische eigenschap. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| property | Eigenschap | Welke eigenschap moet worden verwijderd |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Naam | Beschrijving |
| --- | --- |
| removeProperty(property) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Naam | Beschrijving |
| --- | --- |
| getProperty(property) | Haal de waarde van de opgegeven eigenschap op |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| property | String | Naam van eigenschap |

 **Result:**
Object


---


### setProperty{#setProperty}

| Naam | Beschrijving |
| --- | --- |
| setProperty(property, value) | Stelt de waarde van de opgegeven eigenschap in |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| property | String | Naam van eigenschap |
| waarde | Object | De waarde van de eigenschap |

 **Result:**
Object


---


### findProperty{#findProperty}

| Naam | Beschrijving |
| --- | --- |
| findProperty(propertyName) | Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (Created by CreateDynamicProperty/SetProperty) of een native eigenschap (Identified by its name) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propertyName | String | Naam van eigenschap. |

 **Result:**
Eigenschap


---


### iterator{#iterator}

| Naam | Beschrijving |
| --- | --- |
| iterator() | Gereserveerd voor intern gebruik. |

 **Result:**
Eigenschap


---



