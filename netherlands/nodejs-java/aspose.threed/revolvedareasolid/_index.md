---
title: "RevolvedAreaSolid"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Deze klasse vertegenwoordigt een solide model door een doorsnede, geleverd door een profiel, rond een as te draaien.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Naam | Beschrijving |
| --- | --- |
| getAngleStart() | Haalt op of stelt de starthoek van de roterende procedure in, gemeten in radialen, standaardwaarde is 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Naam | Beschrijving |
| --- | --- |
| setAngleStart(value) | Haalt op of stelt de starthoek van de roterende procedure in, gemeten in radialen, standaardwaarde is 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Naam | Beschrijving |
| --- | --- |
| getAngleEnd() | Haalt op of stelt de eindhoek van de roterende procedure in, gemeten in radialen, standaardwaarde is pi. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Naam | Beschrijving |
| --- | --- |
| setAngleEnd(value) | Haalt op of stelt de eindhoek van de roterende procedure in, gemeten in radialen, standaardwaarde is pi. |

 **Result:**



---


### getAxis{#getAxis}

| Naam | Beschrijving |
| --- | --- |
| getAxis() | Haalt op of stelt de asrichting in, standaardwaarde is (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Naam | Beschrijving |
| --- | --- |
| setAxis(value) | Haalt op of stelt de asrichting in, standaardwaarde is (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Naam | Beschrijving |
| --- | --- |
| getOrigin() | Haalt op of stelt het oorsprongspunt van de rotatie in, standaardwaarde is (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Naam | Beschrijving |
| --- | --- |
| setOrigin(value) | Haalt op of stelt het oorsprongspunt van de rotatie in, standaardwaarde is (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Naam | Beschrijving |
| --- | --- |
| getShape() | Haalt op of stelt het basisprofiel in dat wordt gebruikt voor de rotatie. |

 **Result:**



---


### setShape{#setShape}

| Naam | Beschrijving |
| --- | --- |
| setShape(value) | Haalt op of stelt het basisprofiel in dat wordt gebruikt voor de rotatie. |

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


### toMesh{#toMesh}

| Naam | Beschrijving |
| --- | --- |
| toMesh() | Converteer de RevolvedAreaSolid naar een mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt het begrenzingsvak op van de huidige entiteit in zijn objectruimte-coördinatensysteem. |

 **Result:**
Mesh


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



