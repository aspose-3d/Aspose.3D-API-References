---
title: Vector3
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Ein Vektor mit drei Komponenten.


## Properties

| Name | Beschreibung |
| --- | --- |
| x | Die x‑Komponente. |
| y | Die y‑Komponente. |
| z | Die z‑Komponente. |
| ORIGIN | Gets the origin position. The origin. |
| UNIT_SCALE | Gets the unit scale vector. |
| X_AXIS | Gets the X axis. The X axis. |
| Y_AXIS | Gets the Y axis. The Y axis. |
| Z_AXIS | Gets the Z axis. The Z axis. |

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
| constructor_overload(x, y, z) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| x | Number | Die x-Koordinate. |
| y | Number | Die y-Koordinate. |
| z | Number | Die z-Koordinate. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(vec) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| vec | FVector3 | Die x-Koordinate. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(v) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| v | Number | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Name | Beschreibung |
| --- | --- |
| constructor_overload4(vec4) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Name | Beschreibung |
| --- | --- |
| getLength2() | Gibt das Quadrat der Länge zurück. Die length2. |

 **Result:**



---


### getLength{#getLength}

| Name | Beschreibung |
| --- | --- |
| getLength() | Gibt die Länge dieses Vektors zurück. Die length. |

 **Result:**



---


### equals{#equals}

| Name | Beschreibung |
| --- | --- |
| equals(obj) | Prüft, ob zwei Vector3 gleich sind |

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
| hashCode() | Gibt den Hashcode von Vector3 zurück. |

 **Result:**
Number


---


### dot{#dot}

| Name | Beschreibung |
| --- | --- |
| dot(rhs) | Gibt das Skalarprodukt von zwei Vektoren zurück |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rhs | Vector3 | Rechter Handwert. |

 **Result:**
Number


---


### normalize{#normalize}

| Name | Beschreibung |
| --- | --- |
| normalize() | Normalisiert diese Instanz. |

 **Result:**
Vector3


---


### sin{#sin}

| Name | Beschreibung |
| --- | --- |
| sin() | Berechnet den Sinus jeder Komponente. |

 **Result:**
Vector3


---


### cos{#cos}

| Name | Beschreibung |
| --- | --- |
| cos() | Berechnet den Kosinus jeder Komponente |

 **Result:**
Vector3


---


### cross{#cross}

| Name | Beschreibung |
| --- | --- |
| cross(rhs) | Kreuzprodukt von zwei Vektoren |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rhs | Vector3 | Rechter Handwert. |

 **Result:**
Vector3


---


### set{#set}

| Name | Beschreibung |
| --- | --- |
| set(newX, newY, newZ) | Setzt die x/y/z-Komponente in einem Aufruf. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| newX | Number | Die x‑Komponente. |
| newY | Number | Die y‑Komponente. |
| newZ | Number | Die z‑Komponente. |

 **Result:**
Vector3


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt einen java.lang.String zurück, der den aktuellen Vector3 darstellt. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| Name | Beschreibung |
| --- | --- |
| angleBetween(dir, up) | Berechnet den inneren Winkel zwischen zwei Richtungen. Zwei Richtungen können nicht normalisierte Vektoren sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| dir | Vector3 | Der Richtungsvektor zum Vergleich |
| up | Vector3 | Der Aufwärtsvektor der gemeinsamen Ebene der beiden Richtungen |

 **Result:**
Number


---


### angleBetween{#angleBetween}

| Name | Beschreibung |
| --- | --- |
| angleBetween(dir) | Berechnet den inneren Winkel zwischen zwei Richtungen. Zwei Richtungen können nicht normalisierte Vektoren sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| dir | Vector3 | Der Richtungsvektor zum Vergleich |

 **Result:**
Number


---


### compareTo{#compareTo}

| Name | Beschreibung |
| --- | --- |
| compareTo(other) | Vergleicht den aktuellen Vektor mit einer anderen Instanz. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Number


---



