---
title: "Vector3"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Ein Vektor mit drei Komponenten.


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| x | Die x-Komponente. |
| y | Die y-Komponente. |
| z | Die z-Komponente. |
| ORIGIN | Ermittelt die Ursprungposition. Der Ursprung. |
| UNIT_SCALE | Ermittelt den Einheitsskalierungsvektor. |
| X_AXIS | Ermittelt die X-Achse. Die X-Achse. |
| Y_AXIS | Ermittelt die Y-Achse. Die Y-Achse. |
| Z_AXIS | Gibt die Z-Achse zurück. Die Z-Achse. |

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
| constructor_overload(x, y, z) | Initialisiert eine neue Instanz der Vector3-Struktur. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| x | Zahl | Die x-Koordinate. |
| y | Zahl | Die y-Koordinate. |
| z | Zahl | Die z-Koordinate. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(vec) | Initialisiert eine neue Instanz der Vector3-Struktur. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| vec | FVector3 | Die x-Koordinate. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(v) | Initialisiert eine neue Instanz der Vector3-Struktur. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| v | Zahl | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Name | Beschreibung |
| --- | --- |
| constructor_overload4(vec4) | Initialisiert eine neue Instanz der Vector3-Struktur. |

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
| equals(obj) | Überprüft, ob zwei vector3 gleich sind |

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
| hashCode() | Gibt den Hashcode von Vector3 zurück. |

 **Result:**
Zahl


---


### dot{#dot}

| Name | Beschreibung |
| --- | --- |
| dot(rhs) | Gibt das Skalarprodukt von zwei Vektoren zurück. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rhs | Vector3 | Wert der rechten Seite. |

 **Result:**
Zahl


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
| sin() | Berechnet den Sinus für jede Komponente. |

 **Result:**
Vector3


---


### cos{#cos}

| Name | Beschreibung |
| --- | --- |
| cos() | Berechnet den Kosinus für jede Komponente. |

 **Result:**
Vector3


---


### cross{#cross}

| Name | Beschreibung |
| --- | --- |
| cross(rhs) | Kreuzprodukt von zwei Vektoren. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rhs | Vector3 | Wert der rechten Seite. |

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
| newX | Zahl | Die x-Komponente. |
| newY | Zahl | Die y-Komponente. |
| newZ | Zahl | Die z-Komponente. |

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
| dir | Vector3 | Der Richtungsvektor zum Vergleich. |
| nach oben | Vector3 | Der Aufwärtsvektor der gemeinsamen Ebene der beiden Richtungen |

 **Result:**
Zahl


---


### angleBetween{#angleBetween}

| Name | Beschreibung |
| --- | --- |
| angleBetween(dir) | Berechnet den inneren Winkel zwischen zwei Richtungen. Zwei Richtungen können nicht normalisierte Vektoren sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| dir | Vector3 | Der Richtungsvektor zum Vergleich. |

 **Result:**
Zahl


---


### compareTo{#compareTo}

| Name | Beschreibung |
| --- | --- |
| compareTo(other) | Vergleiche den aktuellen Vektor mit einer anderen Instanz. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Zahl


---



