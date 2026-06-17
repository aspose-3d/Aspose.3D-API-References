---
title: "Quaternion"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion wordt meestal gebruikt om rotatie uit te voeren in computergraphics.


## Properties

| Naam | Beschrijving |
| --- | --- |
| w | De w component. |
| x | De x-component. |
| y | De y-component. |
| z | De z-component. |
| IDENTITY | De Identity quaternion. |

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
| constructor_overload(w, x, y, z) | Initialiseert een nieuw exemplaar van de Quaternion-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| w | Number | w-component van de quaternion |
| x | Number | x-component van de quaternion |
| y | Number | y-component van de quaternion |
| z | Number | z-component van de quaternion |

 **Result:**



---


### getLength{#getLength}

| Naam | Beschrijving |
| --- | --- |
| getLength() | Geeft de lengte van de quaternion terug |

 **Result:**



---


### equals{#equals}

| Naam | Beschrijving |
| --- | --- |
| equals(obj) | Controleer of twee quaternionen gelijk zijn |

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
| hashCode() | Haalt de hashcode van Quaternion op |

 **Result:**
Number


---


### conjugate{#conjugate}

| Naam | Beschrijving |
| --- | --- |
| conjugate() | Retourneert een geconjugeerde quaternion van de huidige quaternion |

 **Result:**
Quaternion


---


### inverse{#inverse}

| Naam | Beschrijving |
| --- | --- |
| inverse() | Retourneert een inverse quaternion van de huidige quaternion |

 **Result:**
Quaternion


---


### dot{#dot}

| Naam | Beschrijving |
| --- | --- |
| dot(q) | Dotproduct |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| q | Quaternion | De quaternion |

 **Result:**
Number


---


### eulerAngles{#eulerAngles}

| Naam | Beschrijving |
| --- | --- |
| eulerAngles() | Converteert quaternion naar rotatie weergegeven door Euler‑hoeken. Alle componenten zijn in radialen |

 **Result:**
Vector3


---


### normalize{#normalize}

| Naam | Beschrijving |
| --- | --- |
| normalize() | Normaliseer de quaternion |

 **Result:**
Quaternion


---


### concat{#concat}

| Naam | Beschrijving |
| --- | --- |
| concat(rhs) | Voeg twee quaternionen samen |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rh | Quaternion | null |

 **Result:**
Quaternion


---


### fromAngleAxis{#fromAngleAxis}

| Naam | Beschrijving |
| --- | --- |
| fromAngleAxis(a, axis) | Maakt een quaternion rond de gegeven as en roteert met de klok mee |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| a | Number | Rotatie met de klok mee in radialen |
| as | Vector3 | As |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Naam | Beschrijving |
| --- | --- |
| fromRotation(orig, dest) | Maakt een quaternion die roteert van de oorspronkelijke naar de bestemmingsrichting |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| orig | Vector3 | Oorspronkelijke richting |
| dest | Vector3 | Bestemmingsrichting |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Naam | Beschrijving |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Maakt een quaternion van de gegeven Euler‑hoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| pitch | Number | Pitch in radialen |
| yaw | Number | Yaw in radialen |
| rol | Number | Rol in radialen |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Naam | Beschrijving |
| --- | --- |
| fromEulerAngle(eulerAngle) | Maakt een quaternion van de gegeven Euler‑hoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eulerAngle | Vector3 | Eulerhoek in radialen |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Naam | Beschrijving |
| --- | --- |
| toMatrix() | Converteer de rotatie die wordt gepresenteerd door een quaternion naar een transformatiematrix. |

 **Result:**
Matrix4


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Haalt de representatie van een quaternion op als string |

 **Result:**
String


---


### interpolate{#interpolate}

| Naam | Beschrijving |
| --- | --- |
| interpolate(t, from, to) | Vult dit quaternion met de geïnterpoleerde waarde tussen de opgegeven quaternion-argumenten voor een t tussen from en to. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| t | Number | De coëfficiënt om te interpoleren. |
| from | Quaternion | Bron quaternion. |
| to | Quaternion | Doel quaternion. |

 **Result:**
Quaternion


---



