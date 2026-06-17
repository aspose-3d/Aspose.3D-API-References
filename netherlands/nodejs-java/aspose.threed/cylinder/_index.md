---
title: "Cilinder"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Geparameterde cilinder.  Het kan ook worden gebruikt om de kegel weer te geven wanneer een van radiusTop/radiusBottom nul is.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de Cylinder-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(radius, height) | Initialiseert een nieuw exemplaar van de Cylinder-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| radius | Number | Straal van de boven- en onderkap. |
| height | Number | Hoogte. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Initialiseert een nieuw exemplaar van de Cylinder-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| radiusTop | Number | Straal boven. |
| radiusBottom | Number | Straal onder. |
| height | Number | Hoogte. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Initialiseert een nieuw exemplaar van de Cylinder-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| radiusTop | Number | Straal van de bovenkap van de cilinder. |
| radiusBottom | Number | Straal van de onderkap van de cilinder. |
| height | Number | Hoogte van de cilinder. |
| radialSegments | Number | Radiale segmenten van zowel de boven- als ondercirkel. |
| heightSegments | Number | Hoogtesegmenten. |
| openEnded | boolean | Indien ingesteld op |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Initialiseert een nieuw exemplaar van de Cylinder-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | De naam van dit object |
| radiusTop | Number | Straal van de bovenkap van de cilinder. |
| radiusBottom | Number | Straal van de onderkap van de cilinder. |
| height | Number | Hoogte van de cilinder. |
| radialSegments | Number | Radiale segmenten van zowel de boven- als ondercirkel. |
| heightSegments | Number | Hoogtesegmenten. |
| openEnded | boolean | Indien ingesteld op |
| thetaStart | Number | Theta start. |
| thetaLength | Number | Theta lengte. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Naam | Beschrijving |
| --- | --- |
| getOffsetBottom() | Haalt of stelt de vertices-transformatie-offset van de onderkant in. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Naam | Beschrijving |
| --- | --- |
| setOffsetBottom(value) | Haalt of stelt de vertices-transformatie-offset van de onderkant in. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Naam | Beschrijving |
| --- | --- |
| getOffsetTop() | Haalt of stelt de vertices-transformatie-offset van de bovenkant in. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Naam | Beschrijving |
| --- | --- |
| setOffsetTop(value) | Haalt of stelt de vertices-transformatie-offset van de bovenkant in. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Naam | Beschrijving |
| --- | --- |
| getGenerateFanCylinder() | Geeft of stelt in of de ventilator-stijl cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2PI, anders wordt het model niet gesneden. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Naam | Beschrijving |
| --- | --- |
| setGenerateFanCylinder(value) | Geeft of stelt in of de ventilator-stijl cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2PI, anders wordt het model niet gesneden. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Naam | Beschrijving |
| --- | --- |
| getShearBottom() | Geeft of stelt de schuiftransformatie van de onderkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Naam | Beschrijving |
| --- | --- |
| setShearBottom(value) | Geeft of stelt de schuiftransformatie van de onderkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### getShearTop{#getShearTop}

| Naam | Beschrijving |
| --- | --- |
| getShearTop() | Geeft of stelt de schuiftransformatie van de bovenkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### setShearTop{#setShearTop}

| Naam | Beschrijving |
| --- | --- |
| setShearTop(value) | Geeft of stelt de schuiftransformatie van de bovenkant in, vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Naam | Beschrijving |
| --- | --- |
| getRadiusTop() | Geeft of stelt de straal van de bovenkap van de cilinder in. De straal van de bovenkap. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Naam | Beschrijving |
| --- | --- |
| setRadiusTop(value) | Geeft of stelt de straal van de bovenkap van de cilinder in. De straal van de bovenkap. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Naam | Beschrijving |
| --- | --- |
| getRadiusBottom() | Geeft of stelt de straal van de onderkap van de cilinder in. De straal van de onderkap. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Naam | Beschrijving |
| --- | --- |
| setRadiusBottom(value) | Geeft of stelt de straal van de onderkap van de cilinder in. De straal van de onderkap. |

 **Result:**



---


### getHeight{#getHeight}

| Naam | Beschrijving |
| --- | --- |
| getHeight() | Geeft of stelt de hoogte van de cilinder in. De hoogte. |

 **Result:**



---


### setHeight{#setHeight}

| Naam | Beschrijving |
| --- | --- |
| setHeight(value) | Geeft of stelt de hoogte van de cilinder in. De hoogte. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Naam | Beschrijving |
| --- | --- |
| getRadialSegments() | Geeft of stelt de radiale segmenten in. De radiale segmenten. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Naam | Beschrijving |
| --- | --- |
| setRadialSegments(value) | Geeft of stelt de radiale segmenten in. De radiale segmenten. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Naam | Beschrijving |
| --- | --- |
| getHeightSegments() | Haalt op of stelt de hoogtesegmenten in. De hoogtesegmenten. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Naam | Beschrijving |
| --- | --- |
| setHeightSegments(value) | Haalt op of stelt de hoogtesegmenten in. De hoogtesegmenten. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Naam | Beschrijving |
| --- | --- |
| getOpenEnded() | Geeft of stelt een waarde in die aangeeft of deze Cylinder open eindig is. Standaardwaarde is false. true als open eindig; anders bestaan er boven-/onderkappen. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Naam | Beschrijving |
| --- | --- |
| setOpenEnded(value) | Geeft of stelt een waarde in die aangeeft of deze Cylinder open eindig is. Standaardwaarde is false. true als open eindig; anders bestaan er boven-/onderkappen. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Naam | Beschrijving |
| --- | --- |
| getThetaStart() | Geeft of stelt de theta-start in. Standaardwaarde is 0. De theta-start. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Naam | Beschrijving |
| --- | --- |
| setThetaStart(value) | Geeft of stelt de theta-start in. Standaardwaarde is 0. De theta-start. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Naam | Beschrijving |
| --- | --- |
| getThetaLength() | Geeft of stelt de lengte van de theta in. Standaardwaarde is 2π. De lengte van de theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Naam | Beschrijving |
| --- | --- |
| setThetaLength(value) | Geeft of stelt de lengte van de theta in. Standaardwaarde is 2π. De lengte van de theta. |

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
| toMesh() | Converteer huidig object naar mesh |

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



