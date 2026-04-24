---
title: Quaternion
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion wird üblicherweise verwendet, um Rotationen in der Computergrafik durchzuführen.


## Properties

| Name | Beschreibung |
| --- | --- |
| w | Die w‑Komponente. |
| x | Die x‑Komponente. |
| y | Die y‑Komponente. |
| z | Die z‑Komponente. |
| IDENTITY | Der Identitäts-Quaternion. |

## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(w, x, y, z) | Initialisiert eine neue Instanz der Quaternion‑Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| w | Number | w‑Komponente des Quaternion |
| x | Number | x‑Komponente des Quaternion |
| y | Number | y‑Komponente des Quaternion |
| z | Number | z‑Komponente des Quaternion |

 **Result:**



---


### getLength{#getLength}

| Name | Beschreibung |
| --- | --- |
| getLength() | Gibt die Länge des Quaternion zurück |

 **Result:**



---


### equals{#equals}

| Name | Beschreibung |
| --- | --- |
| equals(obj) | Prüft, ob zwei Quaternionen gleich sind |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| obj | Object | Das Objekt zum Prüfen der Gleichheit. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Name | Beschreibung |
| --- | --- |
| hashCode() | Gibt den Hashcode des Quaternion zurück |

 **Result:**
Number


---


### conjugate{#conjugate}

| Name | Beschreibung |
| --- | --- |
| conjugate() | Gibt einen konjugierten Quaternion des aktuellen Quaternion zurück |

 **Result:**
Quaternion


---


### inverse{#inverse}

| Name | Beschreibung |
| --- | --- |
| inverse() | Gibt einen inversen Quaternion des aktuellen Quaternion zurück |

 **Result:**
Quaternion


---


### dot{#dot}

| Name | Beschreibung |
| --- | --- |
| dot(q) | Skalarprodukt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| q | Quaternion | Das Quaternion |

 **Result:**
Number


---


### eulerAngles{#eulerAngles}

| Name | Beschreibung |
| --- | --- |
| eulerAngles() | Konvertiert den Quaternion in eine Rotation, die durch Euler-Winkel dargestellt wird. Alle Komponenten sind in Radiant. |

 **Result:**
Vector3


---


### normalize{#normalize}

| Name | Beschreibung |
| --- | --- |
| normalize() | Normalisiert den Quaternion |

 **Result:**
Quaternion


---


### concat{#concat}

| Name | Beschreibung |
| --- | --- |
| concat(rhs) | Verkettet zwei Quaternionen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rh | Quaternion | null |

 **Result:**
Quaternion


---


### fromAngleAxis{#fromAngleAxis}

| Name | Beschreibung |
| --- | --- |
| fromAngleAxis(a, axis) | Erstellt einen Quaternion um die gegebene Achse und rotiert im Uhrzeigersinn |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| a | Number | Uhrzeigersinn‑Drehung in Radiant |
| axis | Vector3 | Achse |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Name | Beschreibung |
| --- | --- |
| fromRotation(orig, dest) | Erstellt einen Quaternion, der von der ursprünglichen zur Zielrichtung rotiert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| orig | Vector3 | Ursprüngliche Richtung |
| dest | Vector3 | Zielrichtung |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Name | Beschreibung |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Erstellt einen Quaternion aus dem gegebenen Euler-Winkel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Neigung | Number | Neigung in Radiant |
| Gier | Number | Gier in Radiant |
| Roll | Number | Roll in Radiant |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Name | Beschreibung |
| --- | --- |
| fromEulerAngle(eulerAngle) | Erstellt einen Quaternion aus dem gegebenen Euler-Winkel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| eulerAngle | Vector3 | Euler‑Winkel in Radiant |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Name | Beschreibung |
| --- | --- |
| toMatrix() | Konvertiert die durch den Quaternion dargestellte Rotation in eine Transformationsmatrix. |

 **Result:**
Matrix4


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt die Darstellung des Quaternion als Zeichenkette zurück |

 **Result:**
String


---


### interpolate{#interpolate}

| Name | Beschreibung |
| --- | --- |
| interpolate(t, from, to) | Füllt diesen Quaternion mit dem interpolierten Wert zwischen den angegebenen Quaternion-Argumenten für ein t zwischen von und bis. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| t | Number | Der Koeffizient zum Interpolieren. |
| from | Quaternion | Quell‑Quaternion. |
| to | Quaternion | Ziel‑Quaternion. |

 **Result:**
Quaternion


---



