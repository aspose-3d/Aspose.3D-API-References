---
title: "CShape"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/cshape/
---
## CShape class

IFC-compatibel C-shape-profiel dat gedefinieerd is door parameters. De centrale positie van het profiel bevindt zich in het midden van de begrenzingsdoos.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van CShape |

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


### getGirth{#getGirth}

| Naam | Beschrijving |
| --- | --- |
| getGirth() | Haalt de lengte van de omtrek op of stelt deze in. |

 **Result:**



---


### setGirth{#setGirth}

| Naam | Beschrijving |
| --- | --- |
| setGirth(value) | Haalt de lengte van de omtrek op of stelt deze in. |

 **Result:**



---


### getWallThickness{#getWallThickness}

| Naam | Beschrijving |
| --- | --- |
| getWallThickness() | Haalt de dikte van de wand op of stelt deze in. |

 **Result:**



---


### setWallThickness{#setWallThickness}

| Naam | Beschrijving |
| --- | --- |
| setWallThickness(value) | Haalt de dikte van de wand op of stelt deze in. |

 **Result:**



---


### getInternalFilletRadius{#getInternalFilletRadius}

| Naam | Beschrijving |
| --- | --- |
| getInternalFilletRadius() | Haalt de interne afrondingsstraal op of stelt deze in. |

 **Result:**



---


### setInternalFilletRadius{#setInternalFilletRadius}

| Naam | Beschrijving |
| --- | --- |
| setInternalFilletRadius(value) | Haalt de interne afrondingsstraal op of stelt deze in. |

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


### getExtent{#getExtent}

| Naam | Beschrijving |
| --- | --- |
| getExtent() | Geeft de omvang in de x- en y-dimensie terug |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Naam | Beschrijving |
| --- | --- |
| getEntityRendererKey() | Haalt de sleutel op van de entiteit-renderer die is geregistreerd in de renderer. |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt het begrenzingsvak op van de huidige entiteit in zijn objectruimte-coördinatensysteem. |

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



