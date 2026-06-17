---
title: "AnimationClip"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Animationsklippet är en samling animationer.  Scenen kan ha ett eller flera animationsklipp.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av klassen AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(name) | Initierar en ny instans av klassen AnimationClip. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### getAnimations{#getAnimations}

| Namn | Beskrivning |
| --- | --- |
| getAnimations() | Hämtar animationerna som finns i klippet. Lagerna. |

 **Result:**



---


### getDescription{#getDescription}

| Namn | Beskrivning |
| --- | --- |
| getDescription() | Hämtar eller anger beskrivningen av detta animationsklipp |

 **Result:**



---


### setDescription{#setDescription}

| Namn | Beskrivning |
| --- | --- |
| setDescription(value) | Hämtar eller anger beskrivningen av detta animationsklipp |

 **Result:**



---


### getStart{#getStart}

| Namn | Beskrivning |
| --- | --- |
| getStart() | Hämtar eller anger tiden i sekunder för början av klippet. |

 **Result:**



---


### setStart{#setStart}

| Namn | Beskrivning |
| --- | --- |
| setStart(value) | Hämtar eller anger tiden i sekunder för början av klippet. |

 **Result:**



---


### getStop{#getStop}

| Namn | Beskrivning |
| --- | --- |
| getStop() | Hämtar eller anger tiden i sekunder för slutet av klippet. |

 **Result:**



---


### setStop{#setStop}

| Namn | Beskrivning |
| --- | --- |
| setStop(value) | Hämtar eller anger tiden i sekunder för slutet av klippet. |

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


### createAnimationNode{#createAnimationNode}

| Namn | Beskrivning |
| --- | --- |
| createAnimationNode(nodeName) | En förkortad funktion för att skapa och registrera animationsnoden på det aktuella klippet. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | Sträng | Nytt namn för animationsnoden |

 **Result:**
AnimationNode


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



