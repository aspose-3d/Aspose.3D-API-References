---
title: "Light"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/light/
---
## Light class

Ljuset lyser upp scenen. Formeln för att beräkna den totala dämpningen av ljuset är:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av Light-klassen. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(name) | Initierar en ny instans av Light-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(name, type) | Initierar en ny instans av Light-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |
| typ | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Namn | Beskrivning |
| --- | --- |
| getColor() | Hämtar eller anger ljusets färg |

 **Result:**



---


### setColor{#setColor}

| Namn | Beskrivning |
| --- | --- |
| setColor(value) | Hämtar eller anger ljusets färg |

 **Result:**



---


### getLightType{#getLightType}

| Namn | Beskrivning |
| --- | --- |
| getLightType() | Hämtar eller anger ljusets typ. Värdet på egenskapen är en heltalskonstant av typen LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Namn | Beskrivning |
| --- | --- |
| setLightType(value) | Hämtar eller anger ljusets typ. Värdet på egenskapen är en heltalskonstant av typen LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Namn | Beskrivning |
| --- | --- |
| getCastLight() | Hämtar eller anger om den aktuella ljusinstansen kan belysa andra objekt. |

 **Result:**



---


### setCastLight{#setCastLight}

| Namn | Beskrivning |
| --- | --- |
| setCastLight(value) | Hämtar eller anger om den aktuella ljusinstansen kan belysa andra objekt. |

 **Result:**



---


### getIntensity{#getIntensity}

| Namn | Beskrivning |
| --- | --- |
| getIntensity() | Hämtar eller anger ljusets intensitet, standardvärdet är 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Namn | Beskrivning |
| --- | --- |
| setIntensity(value) | Hämtar eller anger ljusets intensitet, standardvärdet är 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Namn | Beskrivning |
| --- | --- |
| getHotSpot() | Hämtar eller anger hot spot-konvinkeln (i grader). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Namn | Beskrivning |
| --- | --- |
| setHotSpot(value) | Hämtar eller anger hot spot-konvinkeln (i grader). |

 **Result:**



---


### getFalloff{#getFalloff}

| Namn | Beskrivning |
| --- | --- |
| getFalloff() | Hämtar eller anger falloff-konvinkeln (i grader). |

 **Result:**



---


### setFalloff{#setFalloff}

| Namn | Beskrivning |
| --- | --- |
| setFalloff(value) | Hämtar eller anger falloff-konvinkeln (i grader). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Namn | Beskrivning |
| --- | --- |
| getConstantAttenuation() | Hämtar eller anger den konstanta dämpningen för att beräkna den totala dämpningen av ljuset |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Namn | Beskrivning |
| --- | --- |
| setConstantAttenuation(value) | Hämtar eller anger den konstanta dämpningen för att beräkna den totala dämpningen av ljuset |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Namn | Beskrivning |
| --- | --- |
| getLinearAttenuation() | Hämtar eller anger den linjära dämpningen för att beräkna den totala dämpningen av ljuset |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Namn | Beskrivning |
| --- | --- |
| setLinearAttenuation(value) | Hämtar eller anger den linjära dämpningen för att beräkna den totala dämpningen av ljuset |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Namn | Beskrivning |
| --- | --- |
| getQuadraticAttenuation() | Hämtar eller anger den kvadratiska dämpningen för att beräkna den totala dämpningen av ljuset |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Namn | Beskrivning |
| --- | --- |
| setQuadraticAttenuation(value) | Hämtar eller anger den kvadratiska dämpningen för att beräkna den totala dämpningen av ljuset |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Namn | Beskrivning |
| --- | --- |
| getCastShadows() | Hämtar eller anger om ljuset kan kasta skuggor på andra objekt. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Namn | Beskrivning |
| --- | --- |
| setCastShadows(value) | Hämtar eller anger om ljuset kan kasta skuggor på andra objekt. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Namn | Beskrivning |
| --- | --- |
| getShadowColor() | Hämtar eller anger skuggans färg. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Namn | Beskrivning |
| --- | --- |
| setShadowColor(value) | Hämtar eller anger skuggans färg. |

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



