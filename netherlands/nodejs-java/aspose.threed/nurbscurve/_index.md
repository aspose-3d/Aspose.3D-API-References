---
title: "NurbsCurve"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS-curve is een curve die wordt weergegeven door NURBS (Non-uniform rational basis spline). Een NURBS-curve wordt gedefinieerd door zijn Order, een reeks gewogen Geometry.ControlPoints en een KnotVectors. Het w‑component in het controlepunt wordt gebruikt als gewicht van het controlepunt, ongeacht of het een CurveDimension.TWO_DIMENSIONAL of CurveDimension.THREE_DIMENSIONAL is.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de NurbsCurve-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name) | Initialiseert een nieuw exemplaar van de NurbsCurve-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Naam | Beschrijving |
| --- | --- |
| getControlPoints() | Haalt alle controlepunten op |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Naam | Beschrijving |
| --- | --- |
| getMultiplicity() | Haalt de multipliciteit op. De multipliciteit. |

 **Result:**



---


### getOrder{#getOrder}

| Naam | Beschrijving |
| --- | --- |
| getOrder() | Haalt of stelt de orde van een NURBS-curve in, deze definieert het aantal nabije controlepunten die elk punt op de curve beïnvloeden. De orde. |

 **Result:**



---


### setOrder{#setOrder}

| Naam | Beschrijving |
| --- | --- |
| setOrder(value) | Haalt of stelt de orde van een NURBS-curve in, deze definieert het aantal nabije controlepunten die elk punt op de curve beïnvloeden. De orde. |

 **Result:**



---


### getDimension{#getDimension}

| Naam | Beschrijving |
| --- | --- |
| getDimension() | Haalt of stelt de dimensie van de curve in. De waarde van de eigenschap is de CurveDimension integer-constante. Voor een CurveDimension.TWO_DIMENSIONAL-curve wordt de z-component in control point niet gebruikt. |

 **Result:**



---


### setDimension{#setDimension}

| Naam | Beschrijving |
| --- | --- |
| setDimension(value) | Haalt of stelt de dimensie van de curve in. De waarde van de eigenschap is de CurveDimension integer-constante. Voor een CurveDimension.TWO_DIMENSIONAL-curve wordt de z-component in control point niet gebruikt. |

 **Result:**



---


### getCurveType{#getCurveType}

| Naam | Beschrijving |
| --- | --- |
| getCurveType() | Haalt op of stelt het type van de curve in. De waarde van de eigenschap is de NurbsType gehele getal constante. Het type van de curve. |

 **Result:**



---


### setCurveType{#setCurveType}

| Naam | Beschrijving |
| --- | --- |
| setCurveType(value) | Haalt op of stelt het type van de curve in. De waarde van de eigenschap is de NurbsType gehele getal constante. Het type van de curve. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Naam | Beschrijving |
| --- | --- |
| getKnotVectors() | Haalt de knotvector op, dit is een reeks parameterwaarden die bepaalt waar en hoe de controlepunten de NURBS-curve beïnvloeden. |

 **Result:**



---


### getRational{#getRational}

| Naam | Beschrijving |
| --- | --- |
| getRational() | Haalt op of stelt in of het rationaal is, deze waarde geeft aan of deze NurbsCurve een rationele spline of een niet-rationele spline is. Een niet-rationele B-spline is een speciaal geval van rationele B-splines. true als het een rationele spline is; anders is false een niet-rationele spline. |

 **Result:**



---


### setRational{#setRational}

| Naam | Beschrijving |
| --- | --- |
| setRational(value) | Haalt op of stelt in of het rationaal is, deze waarde geeft aan of deze NurbsCurve een rationele spline of een niet-rationele spline is. Een niet-rationele B-spline is een speciaal geval van rationele B-splines. true als het een rationele spline is; anders is false een niet-rationele spline. |

 **Result:**



---


### getColor{#getColor}

| Naam | Beschrijving |
| --- | --- |
| getColor() | Haalt op of stelt de kleur van de lijn in, standaardwaarde is wit(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Naam | Beschrijving |
| --- | --- |
| setColor(value) | Haalt op of stelt de kleur van de lijn in, standaardwaarde is wit(1, 1, 1) |

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


### evaluate{#evaluate}

| Naam | Beschrijving |
| --- | --- |
| evaluate(steps) | Evalueer de NURBS-curve |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| steps | Number | De evaluatiefrequentie tussen twee aangrenzende knots, standaardwaarde is 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Naam | Beschrijving |
| --- | --- |
| evaluateAt(u) | Evalueer het punt van de curve op de opgegeven positie |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| u | Number | De positie in de curve, tussen 0 en 1 |

 **Result:**
Vector4


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



