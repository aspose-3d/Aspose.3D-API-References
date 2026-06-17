---
title: "MorphTargetChannel"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

En MorphTargetChannel används av MorphTargetDeformer för att organisera målgeometrierna. Vissa filformat som FBX stödjer flera kanaler parallellt. Vikt är mellan 0 och 1.0, och standardvikt för målet är 0.0;


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| DEFAULT_WEIGHT | Standardvikt för morph-mål. |

## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(name) | Initierar en ny instans av MorphTargetChannel-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload() | Initierar en ny instans av MorphTargetChannel-klassen. |

 **Result:**



---


### getWeights{#getWeights}

| Namn | Beskrivning |
| --- | --- |
| getWeights() | Hämtar de fullständiga viktvärdena för målgeometrier. De fullständiga vikterna. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Namn | Beskrivning |
| --- | --- |
| getChannelWeight() | Hämtar eller anger deformatorvikten för den här kanalen. Vikten ligger mellan 0,0 och 1,0. |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Namn | Beskrivning |
| --- | --- |
| setChannelWeight(value) | Hämtar eller anger deformatorvikten för den här kanalen. Vikten ligger mellan 0,0 och 1,0. |

 **Result:**



---


### getTargets{#getTargets}

| Namn | Beskrivning |
| --- | --- |
| getTargets() | Hämtar alla mål som är associerade med kanalen. |

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


### get{#get}

| Namn | Beskrivning |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Namn | Beskrivning |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Namn | Beskrivning |
| --- | --- |
| getWeight(target) | Hämtar vikten för det angivna målet, om målet inte tillhör den här kanalen, returneras standardvärdet 0. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mål | Form | null |

 **Result:**
Nummer


---


### setWeight{#setWeight}

| Namn | Beskrivning |
| --- | --- |
| setWeight(target, weight) | Ställer in vikten för det angivna målet, standardvärdet är 1, intervallet bör ligga mellan 0~1. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mål | Form | null |
| vikt | Nummer | null |

 **Result:**
Nummer


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



