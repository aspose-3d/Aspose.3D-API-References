---
title: "Line"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/line/
---
## Line class

Een polyline is een pad gedefinieerd door een reeks punten met Geometry.ControlPoints, en verbonden door Segments,  wat betekent dat het ook een reeks verbonden lijnsegmenten kan zijn.  De lijn is meestal een lineair object, wat betekent dat het niet kan worden gebruikt om een curve weer te geven; om een curve weer te geven, wordt NurbsCurve gebruikt.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuwe instantie van de Line-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuwe instantie van de Line-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Naam | Beschrijving |
| --- | --- |
| getControlPoints() | Haalt alle controlepunten op |

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


### getSegments{#getSegments}

| Naam | Beschrijving |
| --- | --- |
| getSegments() | Haalt de segmenten van de lijn op |

 **Result:**



---


### getColor{#getColor}

| Naam | Beschrijving |
| --- | --- |
| getColor() | Geeft de kleur van de lijn terug of stelt deze in, standaardwaarde is wit(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Naam | Beschrijving |
| --- | --- |
| setColor(value) | Geeft de kleur van de lijn terug of stelt deze in, standaardwaarde is wit(1, 1, 1) |

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


### fromPoints{#fromPoints}

| Naam | Beschrijving |
| --- | --- |
| fromPoints(points) | Construeer een Line‑instantie vanuit een set punten. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| punt | Vector3[] | null |

 **Result:**
Line


---


### makeDefaultIndices{#makeDefaultIndices}

| Naam | Beschrijving |
| --- | --- |
| makeDefaultIndices() | Genereer de reeks 0,1,2,3....Geometry.ControlPoints.Length-1 naar Segments zodat de ControlPoints als één lijn kunnen worden gebruikt. |

 **Result:**
Line


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



