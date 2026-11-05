---
title: "LShape"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/lshape/
---
## LShape class

IFC-compatibel L-vormprofiel dat gedefinieerd is door parameters.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van LShape |

 **Result:**



---


### getDepth{#getDepth}

| Naam | Beschrijving |
| --- | --- |
| getDepth() | Haalt de diepte van het profiel op of stelt deze in. |

 **Result:**



---


### setDepth{#setDepth}

| Naam | Beschrijving |
| --- | --- |
| setDepth(value) | Haalt de diepte van het profiel op of stelt deze in. |

 **Result:**



---


### getWidth{#getWidth}

| Naam | Beschrijving |
| --- | --- |
| getWidth() | Haalt de breedte van het profiel op of stelt deze in. |

 **Result:**



---


### setWidth{#setWidth}

| Naam | Beschrijving |
| --- | --- |
| setWidth(value) | Haalt de breedte van het profiel op of stelt deze in. |

 **Result:**



---


### getThickness{#getThickness}

| Naam | Beschrijving |
| --- | --- |
| getThickness() | Haalt de dikte op of stelt de dikte in van de constante wand. |

 **Result:**



---


### setThickness{#setThickness}

| Naam | Beschrijving |
| --- | --- |
| setThickness(value) | Haalt de dikte op of stelt de dikte in van de constante wand. |

 **Result:**



---


### getFilletRadius{#getFilletRadius}

| Naam | Beschrijving |
| --- | --- |
| getFilletRadius() | Haalt de straal op of stelt de straal in van de afronding. |

 **Result:**



---


### setFilletRadius{#setFilletRadius}

| Naam | Beschrijving |
| --- | --- |
| setFilletRadius(value) | Haalt de straal op of stelt de straal in van de afronding. |

 **Result:**



---


### getEdgeRadius{#getEdgeRadius}

| Naam | Beschrijving |
| --- | --- |
| getEdgeRadius() | Haalt de straal op of stelt de straal in van de rand. |

 **Result:**



---


### setEdgeRadius{#setEdgeRadius}

| Naam | Beschrijving |
| --- | --- |
| setEdgeRadius(value) | Haalt de straal op of stelt de straal in van de rand. |

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


### getExtent{#getExtent}

| Naam | Beschrijving |
| --- | --- |
| getExtent() | Haalt de omvang in x- en y-dimensie op. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Naam | Beschrijving |
| --- | --- |
| getEntityRendererKey() | Haalt de sleutel op van de entiteit‑renderer die is geregistreerd in de renderer |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt de begrenzingsvak op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |

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



