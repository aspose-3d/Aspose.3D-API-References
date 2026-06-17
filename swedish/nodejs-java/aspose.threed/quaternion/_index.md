---
title: "Kvaternion"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion används vanligtvis för att utföra rotation i datorgrafik.


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| w | w-komponenten. |
| x | x-komponenten. |
| y | y-komponenten. |
| z | z-komponenten. |
| IDENTITY | Identitetskvaternionen. |

## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(w, x, y, z) | Initierar en ny instans av Quaternion-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| w | Nummer | w-komponent av kvaternionen |
| x | Nummer | x-komponent av kvaternionen |
| y | Nummer | y-komponent av kvaternionen |
| z | Nummer | z-komponent av kvaternionen |

 **Result:**



---


### getLength{#getLength}

| Namn | Beskrivning |
| --- | --- |
| getLength() | Hämtar längden på kvaternionen |

 **Result:**



---


### equals{#equals}

| Namn | Beskrivning |
| --- | --- |
| equals(obj) | Kontrollera om två kvaternioner är lika |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| obj | Objekt | Objektet för att kontrollera likhet. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Namn | Beskrivning |
| --- | --- |
| hashCode() | Hämtar hashkoden för Quaternion |

 **Result:**
Nummer


---


### conjugate{#conjugate}

| Namn | Beskrivning |
| --- | --- |
| conjugate() | Returnerar en konjugerad kvaternion av den aktuella kvaternionen |

 **Result:**
Kvaternion


---


### inverse{#inverse}

| Namn | Beskrivning |
| --- | --- |
| inverse() | Returnerar en invers kvaternion av den aktuella kvaternionen |

 **Result:**
Kvaternion


---


### dot{#dot}

| Namn | Beskrivning |
| --- | --- |
| dot(q) | Punktprodukt |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| q | Kvaternion | Kvaternionen |

 **Result:**
Nummer


---


### eulerAngles{#eulerAngles}

| Namn | Beskrivning |
| --- | --- |
| eulerAngles() | Konverterar kvaternion till rotation representerad av Eulervinklar. Alla komponenter är i radian |

 **Result:**
Vector3


---


### normalize{#normalize}

| Namn | Beskrivning |
| --- | --- |
| normalize() | Normalisera kvaternionen |

 **Result:**
Kvaternion


---


### concat{#concat}

| Namn | Beskrivning |
| --- | --- |
| concat(rhs) | Konkatenera två kvaternioner |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rh | Kvaternion | null |

 **Result:**
Kvaternion


---


### fromAngleAxis{#fromAngleAxis}

| Namn | Beskrivning |
| --- | --- |
| fromAngleAxis(a, axis) | Skapar en kvaternion kring given axel och roterar medurs |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| a | Nummer | Medurs rotation i radian |
| axel | Vector3 | Axel |

 **Result:**
Kvaternion


---


### fromRotation{#fromRotation}

| Namn | Beskrivning |
| --- | --- |
| fromRotation(orig, dest) | Skapar en kvaternion som roterar från ursprunglig till destinationsriktning |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| orig | Vector3 | Ursprunglig riktning |
| dest | Vector3 | Destinationsriktning |

 **Result:**
Kvaternion


---


### fromEulerAngle{#fromEulerAngle}

| Namn | Beskrivning |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Skapar kvaternion från given Eulervinkel |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| pitch | Nummer | Pitch i radian |
| yaw | Nummer | Yaw i radian |
| rulla | Nummer | Rullning i radian |

 **Result:**
Kvaternion


---


### fromEulerAngle{#fromEulerAngle}

| Namn | Beskrivning |
| --- | --- |
| fromEulerAngle(eulerAngle) | Skapar kvaternion från given Eulervinkel |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| eulerAngle | Vector3 | Euler-vinkel i radian |

 **Result:**
Kvaternion


---


### toMatrix{#toMatrix}

| Namn | Beskrivning |
| --- | --- |
| toMatrix() | Konvertera rotationen som presenteras av kvaternion till transformationsmatris. |

 **Result:**
Matrix4


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Hämtar representationen av kvaternion som sträng |

 **Result:**
Sträng


---


### interpolate{#interpolate}

| Namn | Beskrivning |
| --- | --- |
| interpolate(t, from, to) | Fyller denna kvaternion med det interpolerade värdet mellan de givna kvaternionargumenten för ett t mellan från och till. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| t | Nummer | Koeficienten för interpolation. |
| from | Kvaternion | Källkvaternion. |
| to | Kvaternion | Målkvaternion. |

 **Result:**
Kvaternion


---



