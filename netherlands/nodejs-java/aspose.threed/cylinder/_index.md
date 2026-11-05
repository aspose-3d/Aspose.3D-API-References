---
title: "Cylinder"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Geparameterde Cylinder.  Het kan ook worden gebruikt om de kegel weer te geven wanneer een van radiusTop/radiusBottom nul is.


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
| radius | Nummer | Straal van de boven- en onderkap. |
| height | Nummer | Hoogte. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Initialiseert een nieuw exemplaar van de Cylinder-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| radiusTop | Nummer | Bovenste straal. |
| radiusBottom | Nummer | Onderste straal. |
| height | Nummer | Hoogte. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Initialiseert een nieuw exemplaar van de Cylinder-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| radiusTop | Nummer | Straal van de bovenste kap van de cilinder. |
| radiusBottom | Nummer | Straal van de onderste kap van de cilinder. |
| height | Nummer | Hoogte van de cilinder. |
| radialSegments | Nummer | Radiale segmenten van zowel de boven- als ondercirkel.. |
| heightSegments | Nummer | Hoogtesegmenten. |
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
| radiusTop | Nummer | Straal van de bovenste kap van de cilinder. |
| radiusBottom | Nummer | Straal van de onderste kap van de cilinder. |
| height | Nummer | Hoogte van de cilinder. |
| radialSegments | Nummer | Radiale segmenten van zowel de boven- als ondercirkel.. |
| heightSegments | Nummer | Hoogtesegmenten. |
| openEnded | boolean | Indien ingesteld op |
| thetaStart | Nummer | Theta-start. |
| thetaLength | Nummer | Theta lengte. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Naam | Beschrijving |
| --- | --- |
| getOffsetBottom() | Geeft de transformatieverschuiving van de vertices van de onderkant terug of stelt deze in. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Naam | Beschrijving |
| --- | --- |
| setOffsetBottom(value) | Geeft de transformatieverschuiving van de vertices van de onderkant terug of stelt deze in. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Naam | Beschrijving |
| --- | --- |
| getOffsetTop() | Geeft de transformatieverschuiving van de vertices van de bovenkant terug of stelt deze in. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Naam | Beschrijving |
| --- | --- |
| setOffsetTop(value) | Geeft de transformatieverschuiving van de vertices van de bovenkant terug of stelt deze in. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Naam | Beschrijving |
| --- | --- |
| getGenerateFanCylinder() | Geeft aan of een fan-vormige cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2π, anders wordt het model niet gesneden. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Naam | Beschrijving |
| --- | --- |
| setGenerateFanCylinder(value) | Geeft aan of een fan-vormige cilinder moet worden gegenereerd wanneer de ThetaLength kleiner is dan 2π, anders wordt het model niet gesneden. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Naam | Beschrijving |
| --- | --- |
| getShearBottom() | Geeft de schuiftransformatie van de onderkant terug of stelt deze in; de vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Naam | Beschrijving |
| --- | --- |
| setShearBottom(value) | Geeft de schuiftransformatie van de onderkant terug of stelt deze in; de vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### getShearTop{#getShearTop}

| Naam | Beschrijving |
| --- | --- |
| getShearTop() | Geeft de schuiftransformatie van de bovenkant terug of stelt deze in; de vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### setShearTop{#setShearTop}

| Naam | Beschrijving |
| --- | --- |
| setShearTop(value) | Geeft de schuiftransformatie van de bovenkant terug of stelt deze in; de vector slaat de (x-as, z-as) schuifwaarde op die in radialen wordt gemeten, standaardwaarde is (0, 0). |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Naam | Beschrijving |
| --- | --- |
| getRadiusTop() | Geeft de straal van de bovenste kap van de cilinder terug of stelt deze in. De straal van de bovenste kap. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Naam | Beschrijving |
| --- | --- |
| setRadiusTop(value) | Geeft de straal van de bovenste kap van de cilinder terug of stelt deze in. De straal van de bovenste kap. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Naam | Beschrijving |
| --- | --- |
| getRadiusBottom() | Geeft de straal van de onderste kap van de cilinder terug of stelt deze in. De straal van de onderste kap. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Naam | Beschrijving |
| --- | --- |
| setRadiusBottom(value) | Geeft de straal van de onderste kap van de cilinder terug of stelt deze in. De straal van de onderste kap. |

 **Result:**



---


### getHeight{#getHeight}

| Naam | Beschrijving |
| --- | --- |
| getHeight() | Geeft de hoogte van de cilinder terug of stelt deze in. De hoogte. |

 **Result:**



---


### setHeight{#setHeight}

| Naam | Beschrijving |
| --- | --- |
| setHeight(value) | Geeft de hoogte van de cilinder terug of stelt deze in. De hoogte. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Naam | Beschrijving |
| --- | --- |
| getRadialSegments() | Geeft de radiale segmenten terug of stelt deze in. De radiale segmenten. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Naam | Beschrijving |
| --- | --- |
| setRadialSegments(value) | Geeft de radiale segmenten terug of stelt deze in. De radiale segmenten. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Naam | Beschrijving |
| --- | --- |
| getHeightSegments() | Haalt op of stelt de hoogte‑segmenten in. De hoogte‑segmenten. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Naam | Beschrijving |
| --- | --- |
| setHeightSegments(value) | Haalt op of stelt de hoogte‑segmenten in. De hoogte‑segmenten. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Naam | Beschrijving |
| --- | --- |
| getOpenEnded() | Geeft een waarde terug die aangeeft of deze cilinder open eindig is, of stelt deze in. Standaardwaarde is false. Waar true als open eindig; anders bestaan er boven- en onderkappen. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Naam | Beschrijving |
| --- | --- |
| setOpenEnded(value) | Geeft een waarde terug die aangeeft of deze cilinder open eindig is, of stelt deze in. Standaardwaarde is false. Waar true als open eindig; anders bestaan er boven- en onderkappen. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Naam | Beschrijving |
| --- | --- |
| getThetaStart() | Haalt de theta-start op of stelt deze in. De standaardwaarde is 0. De theta-start. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Naam | Beschrijving |
| --- | --- |
| setThetaStart(value) | Haalt de theta-start op of stelt deze in. De standaardwaarde is 0. De theta-start. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Naam | Beschrijving |
| --- | --- |
| getThetaLength() | Haalt de lengte van de theta op of stelt deze in. De standaardwaarde is 2π. De lengte van de theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Naam | Beschrijving |
| --- | --- |
| setThetaLength(value) | Haalt de lengte van de theta op of stelt deze in. De standaardwaarde is 2π. De lengte van de theta. |

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
| toMesh() | Converteer het huidige object naar een mesh |

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



