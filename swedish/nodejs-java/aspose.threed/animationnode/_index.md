---
title: "AnimationNode"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D stödjer animationshierarki, varje animation kan bestå av flera animationer och animationens nyckelramdefinition.  AnimationNode definierar transformationen av ett egenskapsvärde över tid, till exempel kan en animationsnod användas för att kontrollera en nods transformation eller andra numeriska egenskaper hos ett A3DObject-objekt.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(name) | Initierar en ny instans av klassen AnimationNode. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload() | Initierar en ny instans av klassen AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Namn | Beskrivning |
| --- | --- |
| getBindPoints() | Hämtar de aktuella bindningspunkterna |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Namn | Beskrivning |
| --- | --- |
| getSubAnimations() | Hämtar delanimationsnoderna under aktuella animationer |

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


### findBindPoint{#findBindPoint}

| Namn | Beskrivning |
| --- | --- |
| findBindPoint(name) | Hittar bindningspunkten efter namn. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namnet på bindningspunkten att hitta. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Namn | Beskrivning |
| --- | --- |
| getBindPoint(target, propName, create) | Hämtar animationsbindningspunkten för given egenskap. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mål | A3DObject | På vilket objekt bindningspunkten ska skapas. |
| propName | Sträng | Egenskapens namn. |
| skapa | boolean | Om inställt på |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Namn | Beskrivning |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Hämtar nyckelbildssekvensen för given egenskap och kanal. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mål | A3DObject | På vilken instans nyckelbildssekvensen ska skapas. |
| propName | Sträng | Egenskapens namn. |
| channelName | Sträng | Kanalens namn. |
| skapa | boolean | Om inställt på |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Namn | Beskrivning |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Hämtar nyckelbildssekvensen för given egenskap. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mål | A3DObject | På vilken instans nyckelbildssekvensen ska skapas. |
| propName | Sträng | Egenskapens namn. |
| skapa | boolean | Om inställt på |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Namn | Beskrivning |
| --- | --- |
| createBindPoint(obj, propName) | Skapar en BindPoint baserat på egenskapens datatyp. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| obj | A3DObject | Objekt. |
| propName | Sträng | Egenskapsnamn. |

 **Result:**
BindPoint


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



