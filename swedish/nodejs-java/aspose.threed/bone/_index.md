---
title: "Bone"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/bone/
---
## Bone class

Ett ben definierar delmängden av geometrins kontrollpunkt och definierar blandningsvikt för varje kontrollpunkt.  Bone-objektet kan inte användas direkt, en SkinDeformer-instans används för att deformera geometrin, och SkinDeformer levereras med en uppsättning ben, där varje ben är länkat till en nod.  OBS: En kontrollpunkt i en geometri kan vara bunden till mer än ett ben.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(name) | Initierar en ny instans av Bone-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload() | Initierar en ny instans av Bone-klassen. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Namn | Beskrivning |
| --- | --- |
| getWeightCount() | Hämtar antalet vikter, detta utökas automatiskt av setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Namn | Beskrivning |
| --- | --- |
| getTransform() | Hämtar eller anger transformmatrisen för noden som innehåller benet. |

 **Result:**



---


### setTransform{#setTransform}

| Namn | Beskrivning |
| --- | --- |
| setTransform(value) | Hämtar eller anger transformmatrisen för noden som innehåller benet. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Namn | Beskrivning |
| --- | --- |
| getBoneTransform() | Hämtar eller anger transformmatrisen för benet. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Namn | Beskrivning |
| --- | --- |
| setBoneTransform(value) | Hämtar eller anger transformmatrisen för benet. |

 **Result:**



---


### getNode{#getNode}

| Namn | Beskrivning |
| --- | --- |
| getNode() | Hämtar eller anger noden. Bone‑noden är benet som huden är fäst vid, SkinDeformer kommer att använda bone‑noden för att påverka förskjutningen av kontrollpunkterna. Bone‑noden har vanligtvis ett Skeleton kopplat, men det är inte obligatoriskt. Ett kopplat Skeleton används vanligtvis av DCC‑programvara för att visa skelettet för användaren. |

 **Result:**



---


### setNode{#setNode}

| Namn | Beskrivning |
| --- | --- |
| setNode(value) | Hämtar eller anger noden. Bone‑noden är benet som huden är fäst vid, SkinDeformer kommer att använda bone‑noden för att påverka förskjutningen av kontrollpunkterna. Bone‑noden har vanligtvis ett Skeleton kopplat, men det är inte obligatoriskt. Ett kopplat Skeleton används vanligtvis av DCC‑programvara för att visa skelettet för användaren. |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| Namn | Beskrivning |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Namn | Beskrivning |
| --- | --- |
| getWeight(index) | Hämtar vikten för kontrollpunkten som anges av indexet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| index | Nummer | Kontrollpunktens index |

 **Result:**
Nummer


---


### setWeight{#setWeight}

| Namn | Beskrivning |
| --- | --- |
| setWeight(index, weight) | Anger vikten för kontrollpunkten som anges av indexet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| index | Nummer | Kontrollpunktens index |
| vikt | Nummer | Ny vikt |

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



