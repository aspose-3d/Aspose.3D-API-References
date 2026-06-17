---
title: "Vector3"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Een vector met drie componenten.


## Properties

| Naam | Beschrijving |
| --- | --- |
| x | De x-component. |
| y | De y-component. |
| z | De z-component. |
| ORIGIN | Haalt de oorsprongpositie op. De oorsprong. |
| UNIT_SCALE | Haalt de eenheidschaalvector op. |
| X_AXIS | Haalt de X-as op. De X-as. |
| Y_AXIS | Haalt de Y-as op. De Y-as. |
| Z_AXIS | Haalt de Z-as op. De Z-as. |

## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(x, y, z) | Initialiseert een nieuw exemplaar van de Vector3-structuur. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| x | Number | De x-coördinaat. |
| y | Number | De y-coördinaat. |
| z | Number | De z-coördinaat. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(vec) | Initialiseert een nieuw exemplaar van de Vector3-structuur. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| vec | FVector3 | De x-coördinaat. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload3(v) | Initialiseert een nieuw exemplaar van de Vector3-structuur. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| v | Number | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload4(vec4) | Initialiseert een nieuw exemplaar van de Vector3-structuur. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Naam | Beschrijving |
| --- | --- |
| getLength2() | Haalt het kwadraat van de lengte op. De length2. |

 **Result:**



---


### getLength{#getLength}

| Naam | Beschrijving |
| --- | --- |
| getLength() | Haalt de lengte van deze vector op. De lengte. |

 **Result:**



---


### equals{#equals}

| Naam | Beschrijving |
| --- | --- |
| equals(obj) | Controleer of twee vector3 gelijk zijn |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| obj | Object | Het object om gelijkheid te controleren. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Naam | Beschrijving |
| --- | --- |
| hashCode() | Haalt de hashcode van Vector3 op |

 **Result:**
Number


---


### dot{#dot}

| Naam | Beschrijving |
| --- | --- |
| dot(rhs) | Haalt het inproduct van twee vectoren op |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rhs | Vector3 | Waarde van de rechterkant. |

 **Result:**
Number


---


### normalize{#normalize}

| Naam | Beschrijving |
| --- | --- |
| normalize() | Normaliseert deze instantie. |

 **Result:**
Vector3


---


### sin{#sin}

| Naam | Beschrijving |
| --- | --- |
| sin() | Berekent de sinus voor elk component |

 **Result:**
Vector3


---


### cos{#cos}

| Naam | Beschrijving |
| --- | --- |
| cos() | Berekent de cosinus voor elk component |

 **Result:**
Vector3


---


### cross{#cross}

| Naam | Beschrijving |
| --- | --- |
| cross(rhs) | Kruisproduct van twee vectoren |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rhs | Vector3 | Waarde van de rechterkant. |

 **Result:**
Vector3


---


### set{#set}

| Naam | Beschrijving |
| --- | --- |
| set(newX, newY, newZ) | Stelt de x/y/z-component in één oproep in. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| newX | Number | De x-component. |
| newY | Number | De y-component. |
| newZ | Number | De z-component. |

 **Result:**
Vector3


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Retourneert een java.lang.String die de huidige Vector3 vertegenwoordigt. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| Naam | Beschrijving |
| --- | --- |
| angleBetween(dir, up) | Bereken de binnenhoek tussen twee richtingen. Twee richtingen kunnen niet-genormaliseerde vectoren zijn. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| dir | Vector3 | De richtingsvector om mee te vergelijken |
| up | Vector3 | De up-vector van het gedeelde vlak van de twee richtingen |

 **Result:**
Number


---


### angleBetween{#angleBetween}

| Naam | Beschrijving |
| --- | --- |
| angleBetween(dir) | Bereken de binnenhoek tussen twee richtingen. Twee richtingen kunnen niet-genormaliseerde vectoren zijn. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| dir | Vector3 | De richtingsvector om mee te vergelijken |

 **Result:**
Number


---


### compareTo{#compareTo}

| Naam | Beschrijving |
| --- | --- |
| compareTo(other) | Vergelijk de huidige vector met een andere instantie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Number


---



