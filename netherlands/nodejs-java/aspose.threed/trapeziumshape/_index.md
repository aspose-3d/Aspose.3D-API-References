---
title: "TrapeziumShape"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/trapeziumshape/
---
## TrapeziumShape class

IFC‑compatibele trapeziumvorm gedefinieerd door parameters.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van TrapeziumShape |

 **Result:**



---


### getBottomXDim{#getBottomXDim}

| Naam | Beschrijving |
| --- | --- |
| getBottomXDim() | Haalt de omvang van de onderlijn op of stelt deze in, gemeten langs de x-as. |

 **Result:**



---


### setBottomXDim{#setBottomXDim}

| Naam | Beschrijving |
| --- | --- |
| setBottomXDim(value) | Haalt de omvang van de onderlijn op of stelt deze in, gemeten langs de x-as. |

 **Result:**



---


### getTopXDim{#getTopXDim}

| Naam | Beschrijving |
| --- | --- |
| getTopXDim() | Haalt op of stelt de omvang van de bovenste lijn in die langs de x-as wordt gemeten. |

 **Result:**



---


### setTopXDim{#setTopXDim}

| Naam | Beschrijving |
| --- | --- |
| setTopXDim(value) | Haalt op of stelt de omvang van de bovenste lijn in die langs de x-as wordt gemeten. |

 **Result:**



---


### getYDim{#getYDim}

| Naam | Beschrijving |
| --- | --- |
| getYDim() | Haalt op of stelt de afstand tussen de boven- en onderlijn in die langs de y-as wordt gemeten. |

 **Result:**



---


### setYDim{#setYDim}

| Naam | Beschrijving |
| --- | --- |
| setYDim(value) | Haalt op of stelt de afstand tussen de boven- en onderlijn in die langs de y-as wordt gemeten. |

 **Result:**



---


### getTopXOffset{#getTopXOffset}

| Naam | Beschrijving |
| --- | --- |
| getTopXOffset() | Haalt op of stelt de offset vanaf het begin van de bovenste lijn naar de onderlijn in. |

 **Result:**



---


### setTopXOffset{#setTopXOffset}

| Naam | Beschrijving |
| --- | --- |
| setTopXOffset(value) | Haalt op of stelt de offset vanaf het begin van de bovenste lijn naar de onderlijn in. |

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



