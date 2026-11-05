---
title: "Quaternion"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion wird üblicherweise verwendet, um Rotationen in der Computergrafik durchzuführen.


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| w | Die w-Komponente. |
| x | Die x-Komponente. |
| y | Die y-Komponente. |
| z | Die z-Komponente. |
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
| constructor_overload(w, x, y, z) | Initialisiert eine neue Instanz der Quaternion-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| w | Zahl | w-Komponente des Quaternion |
| x | Zahl | x-Komponente des Quaternion |
| y | Zahl | y-Komponente des Quaternion |
| z | Zahl | z-Komponente des Quaternion |

 **Result:**



---


### getLength{#getLength}

| Name | Beschreibung |
| --- | --- |
| getLength() | Ermittelt die Länge des Quaternion |

 **Result:**



---


### equals{#equals}

| Name | Beschreibung |
| --- | --- |
| equals(obj) | Prüft, ob zwei Quaternionen gleich sind |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| obj | Objekt | Das Objekt, um die Gleichheit zu prüfen. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Name | Beschreibung |
| --- | --- |
| hashCode() | Ermittelt den Hashcode des Quaternion |

 **Result:**
Zahl


---


### conjugate{#conjugate}

| Name | Beschreibung |
| --- | --- |
| conjugate() | Gibt ein konjugiertes Quaternion des aktuellen Quaternion zurück |

 **Result:**
Quaternion


---


### inverse{#inverse}

| Name | Beschreibung |
| --- | --- |
| inverse() | Gibt ein inverses Quaternion des aktuellen Quaternion zurück |

 **Result:**
Quaternion


---


### dot{#dot}

| Name | Beschreibung |
| --- | --- |
| dot(q) | Punktprodukt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| q | Quaternion | Das Quaternion |

 **Result:**
Zahl


---


### eulerAngles{#eulerAngles}

| Name | Beschreibung |
| --- | --- |
| eulerAngles() | Konvertiert das Quaternion zu einer Rotation, die durch Euler-Winkel dargestellt wird. Alle Komponenten sind im Bogenmaß. |

 **Result:**
Vector3


---


### normalize{#normalize}

| Name | Beschreibung |
| --- | --- |
| normalize() | Quaternion normalisieren |

 **Result:**
Quaternion


---


### concat{#concat}

| Name | Beschreibung |
| --- | --- |
| concat(rhs) | Zwei Quaternionen verketten |

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
| fromAngleAxis(a, axis) | Erstellt ein Quaternion um die gegebene Achse und rotiert im Uhrzeigersinn |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| a | Zahl | Uhrzeigersinn-Rotation im Bogenmaß |
| Achse | Vector3 | Achse |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Name | Beschreibung |
| --- | --- |
| fromRotation(orig, dest) | Erstellt ein Quaternion, das von der ursprünglichen zur Zielrichtung rotiert |

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
| fromEulerAngle(pitch, yaw, roll) | Erstellt ein Quaternion aus dem angegebenen Eulerwinkel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| pitch | Zahl | Pitch im Bogenmaß |
| yaw | Zahl | Yaw im Bogenmaß |
| roll | Zahl | Roll im Bogenmaß |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Name | Beschreibung |
| --- | --- |
| fromEulerAngle(eulerAngle) | Erstellt ein Quaternion aus dem angegebenen Eulerwinkel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| eulerAngle | Vector3 | Eulerwinkel im Bogenmaß |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Name | Beschreibung |
| --- | --- |
| toMatrix() | Konvertiere die durch ein Quaternion dargestellte Rotation in eine Transformationsmatrix. |

 **Result:**
Matrix4


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt die Darstellung des Quaternions als Zeichenkette zurück |

 **Result:**
String


---


### interpolate{#interpolate}

| Name | Beschreibung |
| --- | --- |
| interpolate(t, from, to) | Füllt dieses Quaternion mit dem interpolierten Wert zwischen den angegebenen Quaternion-Argumenten für ein t zwischen from und to. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| t | Zahl | Der Koeffizient zum Interpolieren. |
| from | Quaternion | Quell-Quaternion. |
| to | Quaternion | Ziel-Quaternion. |

 **Result:**
Quaternion


---



