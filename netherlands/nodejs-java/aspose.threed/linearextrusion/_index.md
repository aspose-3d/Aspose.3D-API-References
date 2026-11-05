---
title: "LinearExtrusion"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

Lineaire extrusie neemt een 2D-vorm als invoer en breidt de vorm uit in de derde dimensie.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van instantie LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(shape, height) | Constructor van instantie LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Naam | Beschrijving |
| --- | --- |
| getShape() | De basisvorm die geëxtrudeerd moet worden. |

 **Result:**



---


### setShape{#setShape}

| Naam | Beschrijving |
| --- | --- |
| setShape(value) | De basisvorm die geëxtrudeerd moet worden. |

 **Result:**



---


### getDirection{#getDirection}

| Naam | Beschrijving |
| --- | --- |
| getDirection() | De richting van extrusie, standaardwaarde is (0, 0, 1). |

 **Result:**



---


### setDirection{#setDirection}

| Naam | Beschrijving |
| --- | --- |
| setDirection(value) | De richting van extrusie, standaardwaarde is (0, 0, 1). |

 **Result:**



---


### getHeight{#getHeight}

| Naam | Beschrijving |
| --- | --- |
| getHeight() | De hoogte van de geëxtrudeerde geometrie, standaardwaarde is 1.0. |

 **Result:**



---


### setHeight{#setHeight}

| Naam | Beschrijving |
| --- | --- |
| setHeight(value) | De hoogte van de geëxtrudeerde geometrie, standaardwaarde is 1.0. |

 **Result:**



---


### getSlices{#getSlices}

| Naam | Beschrijving |
| --- | --- |
| getSlices() | De slices van de gedraaide geëxtrudeerde geometrie, standaardwaarde is 1. |

 **Result:**



---


### setSlices{#setSlices}

| Naam | Beschrijving |
| --- | --- |
| setSlices(value) | De slices van de gedraaide geëxtrudeerde geometrie, standaardwaarde is 1. |

 **Result:**



---


### getCenter{#getCenter}

| Naam | Beschrijving |
| --- | --- |
| getCenter() | Als deze waarde false is, is het Z-bereik van de lineaire extrusie van 0 tot hoogte; anders is het bereik van -hoogte/2 tot hoogte/2. |

 **Result:**



---


### setCenter{#setCenter}

| Naam | Beschrijving |
| --- | --- |
| setCenter(value) | Als deze waarde false is, is het Z-bereik van de lineaire extrusie van 0 tot hoogte; anders is het bereik van -hoogte/2 tot hoogte/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Naam | Beschrijving |
| --- | --- |
| getTwistOffset() | De offset die wordt gebruikt bij draaien, standaardwaarde is (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Naam | Beschrijving |
| --- | --- |
| setTwistOffset(value) | De offset die wordt gebruikt bij draaien, standaardwaarde is (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Naam | Beschrijving |
| --- | --- |
| getTwist() | Het aantal graden waarover de vorm wordt geëxtrudeerd. |

 **Result:**



---


### setTwist{#setTwist}

| Naam | Beschrijving |
| --- | --- |
| setTwist(value) | Het aantal graden waarover de vorm wordt geëxtrudeerd. |

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


### toMesh{#toMesh}

| Naam | Beschrijving |
| --- | --- |
| toMesh() | Converteer de extrusie naar mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt de begrenzingsvak op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |

 **Result:**
Mesh


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



