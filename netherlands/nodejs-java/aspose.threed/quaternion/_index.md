---
title: "Quaternion"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion wordt meestal gebruikt om rotatie uit te voeren in computergraphics.


## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| w | De w-component. |
| x | De x-component. |
| y | De y-component. |
| z | De z-component. |
| IDENTITY | Het identiteitsquaternion. |

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
| w | Nummer | w-component van het quaternion |
| x | Nummer | x-component van het quaternion |
| y | Nummer | y-component van het quaternion |
| z | Nummer | z-component van het quaternion |

 **Result:**



---


### getLength{#getLength}

| Naam | Beschrijving |
| --- | --- |
| getLength() | Geeft de lengte van het quaternion terug |

 **Result:**



---


### equals{#equals}

| Naam | Beschrijving |
| --- | --- |
| equals(obj) | Controleer of twee quaternions gelijk zijn |

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
| hashCode() | Haalt de hashcode op van Quaternion |

 **Result:**
Nummer


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
Nummer


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
| concat(rhs) | Voeg twee quaternions samen |

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
| fromAngleAxis(a, axis) | Creëert een quaternion rond de gegeven as en roteert met de klok mee |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| a | Nummer | Rotatie met de klok mee in radialen |
| axis | Vector3 | As |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Naam | Beschrijving |
| --- | --- |
| fromRotation(orig, dest) | Creëert een quaternion die roteert van de oorspronkelijke naar de bestemmingsrichting |

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
| fromEulerAngle(pitch, yaw, roll) | Maakt quaternion van gegeven Euler-hoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| pitch | Nummer | Pitch in radialen |
| yaw | Nummer | Yaw in radialen |
| roll | Nummer | Roll in radialen |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Naam | Beschrijving |
| --- | --- |
| fromEulerAngle(eulerAngle) | Maakt quaternion van gegeven Euler-hoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eulerAngle | Vector3 | Euler-hoek in radialen |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Naam | Beschrijving |
| --- | --- |
| toMatrix() | Converteer de rotatie die door de quaternion wordt gepresenteerd naar een transformatiesmatrix. |

 **Result:**
Matrix4


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Verkrijgt de representatie van de quaternion als string |

 **Result:**
String


---


### interpolate{#interpolate}

| Naam | Beschrijving |
| --- | --- |
| interpolate(t, from, to) | Vult deze quaternion met de geïnterpoleerde waarde tussen de gegeven quaternion-argumenten voor een t tussen from en to. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| t | Nummer | De coëfficiënt om te interpoleren. |
| from | Quaternion | Bron quaternion. |
| to | Quaternion | Doel quaternion. |

 **Result:**
Quaternion


---



