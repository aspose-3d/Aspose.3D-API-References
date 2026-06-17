---
title: "KeyframeSequence"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

Sekvensen av nyckelramar beskriver transformationen av ett samplat värde över tid.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(name) | Initierar en ny instans av klassen KeyframeSequence. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload() | Initierar en ny instans av klassen KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Namn | Beskrivning |
| --- | --- |
| getBindPoint() | Hämtar egenskapsbindningspunkten som äger denna kurva |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Namn | Beskrivning |
| --- | --- |
| getKeyFrames() | Hämtar nyckelramarna för denna kurva. Nycklarna. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Namn | Beskrivning |
| --- | --- |
| getPostBehavior() | Hämtar postbeteendet som anger vad det samplade värdet ska vara efter den sista nyckelramen. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Namn | Beskrivning |
| --- | --- |
| getPreBehavior() | Hämtar förbeteendet som anger vad det samplade värdet ska vara innan den första nyckeln. |

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


### add{#add}

| Namn | Beskrivning |
| --- | --- |
| add(time, value) | Skapa en ny nyckelram med angivet värde |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| tid | Nummer | Tidsposition (uppmätt i sekunder) |
| värde | Nummer | Värdet vid denna tidsposition |

 **Result:**



---


### add{#add}

| Namn | Beskrivning |
| --- | --- |
| add(time, value, interpolation) | Skapa en ny nyckelram med angivet värde |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| tid | Nummer | Tidsposition (uppmätt i sekunder) |
| värde | Nummer | Värdet vid denna tidsposition |
| interpolering | Interpolering | Interpolering |

 **Result:**



---


### reset{#reset}

| Namn | Beskrivning |
| --- | --- |
| reset() | Tar bort alla nyckelramar och återställer post-/pre‑beteenden. |

 **Result:**



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


### iterator{#iterator}

| Namn | Beskrivning |
| --- | --- |
| iterator() | Reserverad för internt bruk. |

 **Result:**
Property


---



