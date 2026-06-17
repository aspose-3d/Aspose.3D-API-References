---
title: "Pose"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/pose/
---
## Pose class

Posen används för att lagra transformationsmatrisen när geometrin är skinad. Posen är en uppsättning BonePose, där varje BonePose sparar den konkreta transformationsinformationen för ben-noden.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(name) | Initierar en ny instans av klassen Pose. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload() | Initierar en ny instans av klassen Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| Namn | Beskrivning |
| --- | --- |
| getPoseType() | Hämtar eller anger typen av posen. Värdet på egenskapen är PoseType heltalskonstant. Typen av posen. |

 **Result:**



---


### setPoseType{#setPoseType}

| Namn | Beskrivning |
| --- | --- |
| setPoseType(value) | Hämtar eller anger typen av posen. Värdet på egenskapen är PoseType heltalskonstant. Typen av posen. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Namn | Beskrivning |
| --- | --- |
| getBonePoses() | Hämtar alla BonePose. Noderna. |

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


### addBonePose{#addBonePose}

| Namn | Beskrivning |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Sparar posens transformationsmatris för den angivna bennoden. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nod | Nod | Bennod. |
| matrix | Matrix4 | Transformationsmatris. |
| localMatrix | boolean | Om inställt på |

 **Result:**



---


### addBonePose{#addBonePose}

| Namn | Beskrivning |
| --- | --- |
| addBonePose(node, matrix) | Sparar posens transformationsmatris för den angivna benknuten. Global transformationsmatris antas. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nod | Nod | Bennod. |
| matrix | Matrix4 | Transformationsmatris. |

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



