---
title: "Patch"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/patch/
---
## Patch class

Een Patch is een parametrisch modelleringsoppervlak, vergelijkbaar met NurbsSurface, het wordt ook gedefinieerd door twee PatchDirection, de U en V. Maar het verschil tussen Patch en NurbsSurface is dat de PatchDirection-curve een van PatchDirectionType.BEZIER, PatchDirectionType.QUADRATIC_BEZIER, PatchDirectionType.BASIS_SPLINE, PatchDirectionType.CARDINAL_SPLINE en PatchDirectionType.LINEAR kan zijn.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de Patch‑klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de Patch‑klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### getU{#getU}

| Naam | Beschrijving |
| --- | --- |
| getU() | Haalt de u‑richting op. |

 **Result:**



---


### getV{#getV}

| Naam | Beschrijving |
| --- | --- |
| getV() | Haalt de v‑richting op. De v. |

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
| getCastShadows() | Haalt op of stelt in of deze geometrie schaduwen kan werpen |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Naam | Beschrijving |
| --- | --- |
| setCastShadows(value) | Haalt op of stelt in of deze geometrie schaduwen kan werpen |

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
| getParentNode() | Haalt op of stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. De bovenliggende knoop. |

 **Result:**



---


### setParentNode{#setParentNode}

| Naam | Beschrijving |
| --- | --- |
| setParentNode(value) | Haalt op of stelt de eerste bovenliggende knoop in; als de eerste bovenliggende knoop wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knopen. De bovenliggende knoop. |

 **Result:**



---


### getScene{#getScene}

| Naam | Beschrijving |
| --- | --- |
| getScene() | Haalt de scène op waartoe dit object behoort. |

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
| getProperties() | Haalt de collectie van alle eigenschappen op. |

 **Result:**



---


### getElement{#getElement}

| Naam | Beschrijving |
| --- | --- |
| getElement(type) | Haalt een vertex‑element op met het opgegeven type. |

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
| getVertexElementOfUV(textureMapping) | Haalt een VertexElementUV‑instantie op met het opgegeven texture‑mapping‑type. |

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
| createElement(type) | Maakt een vertex‑element met het opgegeven type aan en voegt het toe aan de geometrie. Als het type VertexElementType.UV is, wordt een VertexElementUV met texture‑mapping‑type TextureMapping.DIFFUSE aangemaakt. |

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
| addElement(element) | Voegt een bestaand vertex‑element toe aan de huidige geometrie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| element | VertexElement | Het toe te voegen vertex‑element. |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Naam | Beschrijving |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Maakt een vertex‑element met het opgegeven type aan en voegt het toe aan de geometrie. Als het type VertexElementType.UV is, wordt een VertexElementUV met texture‑mapping‑type TextureMapping.DIFFUSE aangemaakt. |

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
| getBoundingBox() | Haalt het begrenzingsvak op van de huidige entiteit in zijn objectruimte-coördinatensysteem. |

 **Result:**
VertexElementUV


---


### getEntityRendererKey{#getEntityRendererKey}

| Naam | Beschrijving |
| --- | --- |
| getEntityRendererKey() | Haalt de sleutel op van de entiteit-renderer die is geregistreerd in de renderer. |

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
| eigenschap | Eigenschap | Welke eigenschap moet worden verwijderd |

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
| propert | String | null |

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
| eigenschap | String | Naam van eigenschap |

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
| eigenschap | String | Naam van eigenschap |
| value | Object | De waarde van de eigenschap |

 **Result:**
Object


---


### findProperty{#findProperty}

| Naam | Beschrijving |
| --- | --- |
| findProperty(propertyName) | Zoekt de eigenschap. Het kan een dynamische eigenschap (Gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap(Geadresseerd aan de hand van zijn naam) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propertyName | String | Naam van eigenschap. |

 **Result:**
Eigenschap


---



