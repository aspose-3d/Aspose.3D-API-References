---
title: "Kamera"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/camera/
---
## Camera class

Kameran beskriver betraktarens ögonpunkt när denne tittar på scenen.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av klassen Camera. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(projectionType) | Initierar en ny instans av klassen Camera. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(name) | Initierar en ny instans av klassen Camera. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload3(name, projectionType) | Initierar en ny instans av klassen Camera. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Namn | Beskrivning |
| --- | --- |
| getApertureMode() | Hämtar eller anger kamerans bländarläge. Värdet på egenskapen är heltalskonstanten ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Namn | Beskrivning |
| --- | --- |
| setApertureMode(value) | Hämtar eller anger kamerans bländarläge. Värdet på egenskapen är heltalskonstanten ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Namn | Beskrivning |
| --- | --- |
| getFieldOfView() | Hämtar eller anger kamerans synfält i grader, den här egenskapen används endast när ApertureMode är ApertureMode.HORIZONTAL eller ApertureMode.VERTICAL |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Namn | Beskrivning |
| --- | --- |
| setFieldOfView(value) | Hämtar eller anger kamerans synfält i grader, den här egenskapen används endast när ApertureMode är ApertureMode.HORIZONTAL eller ApertureMode.VERTICAL |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Namn | Beskrivning |
| --- | --- |
| getFieldOfViewX() | Hämtar eller anger kamerans horisontella synfält i grader, den här egenskapen används endast när ApertureMode är ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Namn | Beskrivning |
| --- | --- |
| setFieldOfViewX(value) | Hämtar eller anger kamerans horisontella synfält i grader, den här egenskapen används endast när ApertureMode är ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Namn | Beskrivning |
| --- | --- |
| getFieldOfViewY() | Hämtar eller anger kamerans vertikala synfält i grader, den här egenskapen används endast när ApertureMode är ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Namn | Beskrivning |
| --- | --- |
| setFieldOfViewY(value) | Hämtar eller anger kamerans vertikala synfält i grader, den här egenskapen används endast när ApertureMode är ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getWidth{#getWidth}

| Namn | Beskrivning |
| --- | --- |
| getWidth() | Hämtar eller anger vyplanens bredd i tum |

 **Result:**



---


### setWidth{#setWidth}

| Namn | Beskrivning |
| --- | --- |
| setWidth(value) | Hämtar eller anger vyplanens bredd i tum |

 **Result:**



---


### getHeight{#getHeight}

| Namn | Beskrivning |
| --- | --- |
| getHeight() | Hämtar eller anger vyplanens höjd i tum |

 **Result:**



---


### setHeight{#setHeight}

| Namn | Beskrivning |
| --- | --- |
| setHeight(value) | Hämtar eller anger vyplanens höjd i tum |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Namn | Beskrivning |
| --- | --- |
| getAspectRatio() | Hämtar eller anger vyplanens bildförhållande. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Namn | Beskrivning |
| --- | --- |
| setAspectRatio(value) | Hämtar eller anger vyplanens bildförhållande. |

 **Result:**



---


### getMagnification{#getMagnification}

| Namn | Beskrivning |
| --- | --- |
| getMagnification() | Hämtar eller anger förstoring som används i en ortografisk kamera. |

 **Result:**



---


### setMagnification{#setMagnification}

| Namn | Beskrivning |
| --- | --- |
| setMagnification(value) | Hämtar eller anger förstoring som används i en ortografisk kamera. |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Namn | Beskrivning |
| --- | --- |
| getProjectionType() | Hämtar eller anger kamerans projektionstyp. Som standard används perspektivprojektion. Värdet på egenskapen är heltalskonstanten ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Namn | Beskrivning |
| --- | --- |
| setProjectionType(value) | Hämtar eller anger kamerans projektionstyp. Som standard används perspektivprojektion. Värdet på egenskapen är heltalskonstanten ProjectionType. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Namn | Beskrivning |
| --- | --- |
| getRotationMode() | Hämtar eller anger frustumens orienteringsläge. Denna egenskap fungerar endast när Target är null. Om värdet är RotationMode.FIXED_TARGET beräknas riktningen alltid av egenskapen LookAt. Annars beräknas LookAt alltid av Direction. Värdet för egenskapen är heltalskonstanten RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Namn | Beskrivning |
| --- | --- |
| setRotationMode(value) | Hämtar eller anger frustumens orienteringsläge. Denna egenskap fungerar endast när Target är null. Om värdet är RotationMode.FIXED_TARGET beräknas riktningen alltid av egenskapen LookAt. Annars beräknas LookAt alltid av Direction. Värdet för egenskapen är heltalskonstanten RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Namn | Beskrivning |
| --- | --- |
| getNearPlane() | Hämtar eller anger frustumens närplanavstånd. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Namn | Beskrivning |
| --- | --- |
| setNearPlane(value) | Hämtar eller anger frustumens närplanavstånd. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Namn | Beskrivning |
| --- | --- |
| getFarPlane() | Hämtar eller anger frustumets avstånd till den fjärrplanen. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Namn | Beskrivning |
| --- | --- |
| setFarPlane(value) | Hämtar eller anger frustumets avstånd till den fjärrplanen. |

 **Result:**



---


### getAspect{#getAspect}

| Namn | Beskrivning |
| --- | --- |
| getAspect() | Hämtar eller anger bildförhållandet för frustumen |

 **Result:**



---


### setAspect{#setAspect}

| Namn | Beskrivning |
| --- | --- |
| setAspect(value) | Hämtar eller anger bildförhållandet för frustumen |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Namn | Beskrivning |
| --- | --- |
| getOrthoHeight() | Hämtar eller anger höjden när frustumen är i ortografisk projektion. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Namn | Beskrivning |
| --- | --- |
| setOrthoHeight(value) | Hämtar eller anger höjden när frustumen är i ortografisk projektion. |

 **Result:**



---


### getUp{#getUp}

| Namn | Beskrivning |
| --- | --- |
| getUp() | Hämtar eller anger kamerans uppåtriktning |

 **Result:**



---


### setUp{#setUp}

| Namn | Beskrivning |
| --- | --- |
| setUp(value) | Hämtar eller anger kamerans uppåtriktning |

 **Result:**



---


### getLookAt{#getLookAt}

| Namn | Beskrivning |
| --- | --- |
| getLookAt() | Hämtar eller anger den intressanta positionen som kameran tittar på. |

 **Result:**



---


### setLookAt{#setLookAt}

| Namn | Beskrivning |
| --- | --- |
| setLookAt(value) | Hämtar eller anger den intressanta positionen som kameran tittar på. |

 **Result:**



---


### getDirection{#getDirection}

| Namn | Beskrivning |
| --- | --- |
| getDirection() | Hämtar eller anger den riktning som kameran tittar mot. Ändringar av denna egenskap påverkar också LookAt och Target. |

 **Result:**



---


### setDirection{#setDirection}

| Namn | Beskrivning |
| --- | --- |
| setDirection(value) | Hämtar eller anger den riktning som kameran tittar mot. Ändringar av denna egenskap påverkar också LookAt och Target. |

 **Result:**



---


### getTarget{#getTarget}

| Namn | Beskrivning |
| --- | --- |
| getTarget() | Hämtar eller anger målet som kameran tittar på. Om användaren stöder denna egenskap bör den vara före LookAt-egenskapen. |

 **Result:**



---


### setTarget{#setTarget}

| Namn | Beskrivning |
| --- | --- |
| setTarget(value) | Hämtar eller anger målet som kameran tittar på. Om användaren stöder denna egenskap bör den vara före LookAt-egenskapen. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Namn | Beskrivning |
| --- | --- |
| getParentNodes() | Hämtar alla föräldranoder, en entitet kan fästas vid flera föräldranoder för geometri‑instansering. Noderna. |

 **Result:**



---


### getExcluded{#getExcluded}

| Namn | Beskrivning |
| --- | --- |
| getExcluded() | Hämtar eller anger om denna enhet ska exkluderas vid export. |

 **Result:**



---


### setExcluded{#setExcluded}

| Namn | Beskrivning |
| --- | --- |
| setExcluded(value) | Hämtar eller anger om denna enhet ska exkluderas vid export. |

 **Result:**



---


### getParentNode{#getParentNode}

| Namn | Beskrivning |
| --- | --- |
| getParentNode() | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer denna enhet att frikopplas från andra föräldranoder. Föräldranoden. |

 **Result:**



---


### setParentNode{#setParentNode}

| Namn | Beskrivning |
| --- | --- |
| setParentNode(value) | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer denna enhet att frikopplas från andra föräldranoder. Föräldranoden. |

 **Result:**



---


### getScene{#getScene}

| Namn | Beskrivning |
| --- | --- |
| getScene() | Hämtar scenen som detta objekt tillhör |

 **Result:**



---


### getName{#getName}

| Namn | Beskrivning |
| --- | --- |
| getName() | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### setName{#setName}

| Namn | Beskrivning |
| --- | --- |
| setName(value) | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### getProperties{#getProperties}

| Namn | Beskrivning |
| --- | --- |
| getProperties() | Hämtar samlingen av alla egenskaper. |

 **Result:**



---


### moveForward{#moveForward}

| Namn | Beskrivning |
| --- | --- |
| moveForward(distance) | Flytta kameran framåt i dess riktning eller mot målet. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| distance | Nummer | Hur långt ska den flyttas framåt |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Namn | Beskrivning |
| --- | --- |
| getBoundingBox() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrums koordinatsystem. |

 **Result:**



---


### getEntityRendererKey{#getEntityRendererKey}

| Namn | Beskrivning |
| --- | --- |
| getEntityRendererKey() | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Tar bort en dynamisk egenskap. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Property | Vilken egenskap som ska tas bort |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Ta bort den angivna egenskapen som identifieras med namn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propert | Sträng | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Namn | Beskrivning |
| --- | --- |
| getProperty(property) | Hämta värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Namn | Beskrivning |
| --- | --- |
| setProperty(property, value) | Sätter värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |
| värde | Objekt | Värdet för egenskapen |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Namn | Beskrivning |
| --- | --- |
| findProperty(propertyName) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad av dess namn) |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | Sträng | Egenskapsnamn. |

 **Result:**
Property


---



