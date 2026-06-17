---
title: "Frustum"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/frustum/
---
## Frustum class

De basisklasse van Camera en Light @hideconstructor


## Methoden

### getRotationMode{#getRotationMode}

| Naam | Beschrijving |
| --- | --- |
| getRotationMode() | Haalt op of stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer Target null is. Als de waarde RotationMode.FIXED_TARGET is, wordt de richting altijd berekend door de eigenschap LookAt. Anders wordt LookAt altijd berekend door de Direction. De waarde van de eigenschap is de integer-constante RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Naam | Beschrijving |
| --- | --- |
| setRotationMode(value) | Haalt op of stelt de oriëntatiemodus van de frustum in. Deze eigenschap werkt alleen wanneer Target null is. Als de waarde RotationMode.FIXED_TARGET is, wordt de richting altijd berekend door de eigenschap LookAt. Anders wordt LookAt altijd berekend door de Direction. De waarde van de eigenschap is de integer-constante RotationMode. |

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
| getFarPlane() | Haalt op of stelt de afstand van het verafgelegen vlak van de frustum in. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Naam | Beschrijving |
| --- | --- |
| setFarPlane(value) | Haalt op of stelt de afstand van het verafgelegen vlak van de frustum in. |

 **Result:**



---


### getAspect{#getAspect}

| Naam | Beschrijving |
| --- | --- |
| getAspect() | Haalt op of stelt de beeldverhouding van de frustum in |

 **Result:**



---


### setAspect{#setAspect}

| Naam | Beschrijving |
| --- | --- |
| setAspect(value) | Haalt op of stelt de beeldverhouding van de frustum in |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Naam | Beschrijving |
| --- | --- |
| getOrthoHeight() | Haalt op of stelt de hoogte in wanneer de frustum zich in orthografische projectie bevindt. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Naam | Beschrijving |
| --- | --- |
| setOrthoHeight(value) | Haalt op of stelt de hoogte in wanneer de frustum zich in orthografische projectie bevindt. |

 **Result:**



---


### getUp{#getUp}

| Naam | Beschrijving |
| --- | --- |
| getUp() | Haalt op of stelt de omhoogrichting van de camera in |

 **Result:**



---


### setUp{#setUp}

| Naam | Beschrijving |
| --- | --- |
| setUp(value) | Haalt op of stelt de omhoogrichting van de camera in |

 **Result:**



---


### getLookAt{#getLookAt}

| Naam | Beschrijving |
| --- | --- |
| getLookAt() | Haalt op of stelt de interessante positie in waar de camera naar kijkt. |

 **Result:**



---


### setLookAt{#setLookAt}

| Naam | Beschrijving |
| --- | --- |
| setLookAt(value) | Haalt op of stelt de interessante positie in waar de camera naar kijkt. |

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
| getTarget() | Haalt op of stelt het doel in waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de LookAt property staan. |

 **Result:**



---


### setTarget{#setTarget}

| Naam | Beschrijving |
| --- | --- |
| setTarget(value) | Haalt op of stelt het doel in waar de camera naar kijkt. Als de gebruiker deze eigenschap ondersteunt, moet deze vóór de LookAt property staan. |

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


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Haalt het begrenzingsvak op van de huidige entiteit in zijn objectruimte-coördinatensysteem. |

 **Result:**



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



