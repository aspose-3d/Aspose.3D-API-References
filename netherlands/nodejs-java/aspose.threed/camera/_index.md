---
title: "Camera"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/camera/
---
## Camera class

De camera beschrijft het oogpunt van de kijker die naar de scène kijkt.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuwe instantie van de Camera-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(projectionType) | Initialiseert een nieuwe instantie van de Camera-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(name) | Initialiseert een nieuwe instantie van de Camera-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload3(name, projectionType) | Initialiseert een nieuwe instantie van de Camera-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Naam | Beschrijving |
| --- | --- |
| getApertureMode() | Haalt de diafragmamodus van de camera op of stelt deze in. De waarde van de eigenschap is een geheel getal constant van ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Naam | Beschrijving |
| --- | --- |
| setApertureMode(value) | Haalt de diafragmamodus van de camera op of stelt deze in. De waarde van de eigenschap is een geheel getal constant van ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Naam | Beschrijving |
| --- | --- |
| getFieldOfView() | Haalt het gezichtsveld van de camera op in graden of stelt dit in; deze eigenschap wordt alleen gebruikt wanneer ApertureMode gelijk is aan ApertureMode.HORIZONTAL of ApertureMode.VERTICAL. |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Naam | Beschrijving |
| --- | --- |
| setFieldOfView(value) | Haalt het gezichtsveld van de camera op in graden of stelt dit in; deze eigenschap wordt alleen gebruikt wanneer ApertureMode gelijk is aan ApertureMode.HORIZONTAL of ApertureMode.VERTICAL. |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Naam | Beschrijving |
| --- | --- |
| getFieldOfViewX() | Haalt het horizontale gezichtsveld van de camera op in graden of stelt dit in; deze eigenschap wordt alleen gebruikt wanneer ApertureMode gelijk is aan ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Naam | Beschrijving |
| --- | --- |
| setFieldOfViewX(value) | Haalt het horizontale gezichtsveld van de camera op in graden of stelt dit in; deze eigenschap wordt alleen gebruikt wanneer ApertureMode gelijk is aan ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Naam | Beschrijving |
| --- | --- |
| getFieldOfViewY() | Haalt het verticale gezichtsveld van de camera op in graden of stelt dit in; deze eigenschap wordt alleen gebruikt wanneer ApertureMode gelijk is aan ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Naam | Beschrijving |
| --- | --- |
| setFieldOfViewY(value) | Haalt het verticale gezichtsveld van de camera op in graden of stelt dit in; deze eigenschap wordt alleen gebruikt wanneer ApertureMode gelijk is aan ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### getWidth{#getWidth}

| Naam | Beschrijving |
| --- | --- |
| getWidth() | Haalt de breedte van het kijkvlak op in inches of stelt deze in. |

 **Result:**



---


### setWidth{#setWidth}

| Naam | Beschrijving |
| --- | --- |
| setWidth(value) | Haalt de breedte van het kijkvlak op in inches of stelt deze in. |

 **Result:**



---


### getHeight{#getHeight}

| Naam | Beschrijving |
| --- | --- |
| getHeight() | Haalt de hoogte van het kijkvlak op in inches of stelt deze in. |

 **Result:**



---


### setHeight{#setHeight}

| Naam | Beschrijving |
| --- | --- |
| setHeight(value) | Haalt de hoogte van het kijkvlak op in inches of stelt deze in. |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Naam | Beschrijving |
| --- | --- |
| getAspectRatio() | Haalt op of stelt de beeldvlak-aspectverhouding in. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Naam | Beschrijving |
| --- | --- |
| setAspectRatio(value) | Haalt op of stelt de beeldvlak-aspectverhouding in. |

 **Result:**



---


### getMagnification{#getMagnification}

| Naam | Beschrijving |
| --- | --- |
| getMagnification() | Haalt op of stelt de vergroting in die wordt gebruikt in een orthografische camera. |

 **Result:**



---


### setMagnification{#setMagnification}

| Naam | Beschrijving |
| --- | --- |
| setMagnification(value) | Haalt op of stelt de vergroting in die wordt gebruikt in een orthografische camera. |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Naam | Beschrijving |
| --- | --- |
| getProjectionType() | Haalt op of stelt het projectietype van de camera in. Standaard wordt de perspectiefprojectie gebruikt. De waarde van de eigenschap is de gehele constante ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Naam | Beschrijving |
| --- | --- |
| setProjectionType(value) | Haalt op of stelt het projectietype van de camera in. Standaard wordt de perspectiefprojectie gebruikt. De waarde van de eigenschap is de gehele constante ProjectionType. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Naam | Beschrijving |
| --- | --- |
| getRotationMode() | Haalt op of stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer de Target null is. Als de waarde RotationMode.FIXED_TARGET is, wordt de richting altijd berekend door de eigenschap LookAt. Anders wordt de LookAt altijd berekend door de Direction. De waarde van de eigenschap is een integer-constante van RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Naam | Beschrijving |
| --- | --- |
| setRotationMode(value) | Haalt op of stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer de Target null is. Als de waarde RotationMode.FIXED_TARGET is, wordt de richting altijd berekend door de eigenschap LookAt. Anders wordt de LookAt altijd berekend door de Direction. De waarde van de eigenschap is een integer-constante van RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Naam | Beschrijving |
| --- | --- |
| getNearPlane() | Haalt op of stelt de afstand van het nabijvlak van de frustum in. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Naam | Beschrijving |
| --- | --- |
| setNearPlane(value) | Haalt op of stelt de afstand van het nabijvlak van de frustum in. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Naam | Beschrijving |
| --- | --- |
| getFarPlane() | Haalt op of stelt de afstand van het verafvlak van de frustum in. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Naam | Beschrijving |
| --- | --- |
| setFarPlane(value) | Haalt op of stelt de afstand van het verafvlak van de frustum in. |

 **Result:**



---


### getAspect{#getAspect}

| Naam | Beschrijving |
| --- | --- |
| getAspect() | Haalt op of stelt de beeldverhouding van de frustum in. |

 **Result:**



---


### setAspect{#setAspect}

| Naam | Beschrijving |
| --- | --- |
| setAspect(value) | Haalt op of stelt de beeldverhouding van de frustum in. |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Naam | Beschrijving |
| --- | --- |
| getOrthoHeight() | Haalt op of stelt de hoogte in wanneer de frustum in orthografische projectie staat. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Naam | Beschrijving |
| --- | --- |
| setOrthoHeight(value) | Haalt op of stelt de hoogte in wanneer de frustum in orthografische projectie staat. |

 **Result:**



---


### getUp{#getUp}

| Naam | Beschrijving |
| --- | --- |
| getUp() | Haalt op of stelt de opwaartse richting van de camera in. |

 **Result:**



---


### setUp{#setUp}

| Naam | Beschrijving |
| --- | --- |
| setUp(value) | Haalt op of stelt de opwaartse richting van de camera in. |

 **Result:**



---


### getLookAt{#getLookAt}

| Naam | Beschrijving |
| --- | --- |
| getLookAt() | Haalt op of stelt de gewenste positie in waar de camera naar kijkt. |

 **Result:**



---


### setLookAt{#setLookAt}

| Naam | Beschrijving |
| --- | --- |
| setLookAt(value) | Haalt op of stelt de gewenste positie in waar de camera naar kijkt. |

 **Result:**



---


### getDirection{#getDirection}

| Naam | Beschrijving |
| --- | --- |
| getDirection() | Haalt op of stelt de richting in waar de camera naar kijkt. Wijzigingen aan deze eigenschap hebben ook invloed op LookAt en Target. |

 **Result:**



---


### setDirection{#setDirection}

| Naam | Beschrijving |
| --- | --- |
| setDirection(value) | Haalt op of stelt de richting in waar de camera naar kijkt. Wijzigingen aan deze eigenschap hebben ook invloed op LookAt en Target. |

 **Result:**



---


### getTarget{#getTarget}

| Naam | Beschrijving |
| --- | --- |
| getTarget() | Haalt op of stelt het doel in waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de LookAt‑eigenschap worden ingesteld. |

 **Result:**



---


### setTarget{#setTarget}

| Naam | Beschrijving |
| --- | --- |
| setTarget(value) | Haalt op of stelt het doel in waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de LookAt‑eigenschap worden ingesteld. |

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


### moveForward{#moveForward}

| Naam | Beschrijving |
| --- | --- |
| moveForward(distance) | Verplaats de camera naar voren in de richting van zijn oriëntatie of doel. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| afstand | Nummer | Hoe ver naar voren te bewegen |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt de begrenzingsvak op van de huidige entiteit in zijn objectruimte‑coördinatensysteem. |

 **Result:**



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



