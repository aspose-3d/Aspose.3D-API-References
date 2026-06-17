---
title: "Vector3"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

En vektor med tre komponenter.


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| x | x-komponenten. |
| y | y-komponenten. |
| z | z-komponenten. |
| ORIGIN | Hämtar ursprungspositionen. Ursprung. |
| UNIT_SCALE | Hämtar enhetsskalningsvektorn. |
| X_AXIS | Hämtar X-axeln. X-axeln. |
| Y_AXIS | Hämtar Y-axeln. Y-axeln. |
| Z_AXIS | Hämtar Z-axeln. Z-axeln. |

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
| constructor_overload(x, y, z) | Initierar en ny instans av strukturen Vector3. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| x | Nummer | x-koordinaten. |
| y | Nummer | y-koordinaten. |
| z | Nummer | z-koordinaten. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(vec) | Initierar en ny instans av strukturen Vector3. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vec | FVector3 | x-koordinaten. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload3(v) | Initierar en ny instans av strukturen Vector3. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| v | Nummer | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload4(vec4) | Initierar en ny instans av strukturen Vector3. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Namn | Beskrivning |
| --- | --- |
| getLength2() | Hämtar kvadraten av längden. length2. |

 **Result:**



---


### getLength{#getLength}

| Namn | Beskrivning |
| --- | --- |
| getLength() | Hämtar längden på denna vektor. Längden. |

 **Result:**



---


### equals{#equals}

| Namn | Beskrivning |
| --- | --- |
| equals(obj) | Kontrollera om två vector3 är lika |

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
| hashCode() | Hämtar hashkoden för Vector3 |

 **Result:**
Nummer


---


### dot{#dot}

| Namn | Beskrivning |
| --- | --- |
| dot(rhs) | Hämtar skalärprodukten av två vektorer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rhs | Vector3 | Värde för högra sidan. |

 **Result:**
Nummer


---


### normalize{#normalize}

| Namn | Beskrivning |
| --- | --- |
| normalize() | Normaliserar detta objekt. |

 **Result:**
Vector3


---


### sin{#sin}

| Namn | Beskrivning |
| --- | --- |
| sin() | Beräknar sinus för varje komponent |

 **Result:**
Vector3


---


### cos{#cos}

| Namn | Beskrivning |
| --- | --- |
| cos() | Beräknar cosinus för varje komponent |

 **Result:**
Vector3


---


### cross{#cross}

| Namn | Beskrivning |
| --- | --- |
| cross(rhs) | Korsprodukt av två vektorer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rhs | Vector3 | Värde för högra sidan. |

 **Result:**
Vector3


---


### set{#set}

| Namn | Beskrivning |
| --- | --- |
| set(newX, newY, newZ) | Sätter x/y/z-komponenten i ett anrop. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| newX | Nummer | x-komponenten. |
| newY | Nummer | y-komponenten. |
| newZ | Nummer | z-komponenten. |

 **Result:**
Vector3


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Returnerar en java.lang.String som representerar den aktuella Vector3. |

 **Result:**
Sträng


---


### angleBetween{#angleBetween}

| Namn | Beskrivning |
| --- | --- |
| angleBetween(dir, up) | Beräkna den inre vinkeln mellan två riktningar. Två riktningar kan vara icke-normaliserade vektorer. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| dir | Vector3 | Riktningsvektorn att jämföra med |
| up | Vector3 | Uppvektorn för de två riktningarnas gemensamma plan |

 **Result:**
Nummer


---


### angleBetween{#angleBetween}

| Namn | Beskrivning |
| --- | --- |
| angleBetween(dir) | Beräkna den inre vinkeln mellan två riktningar. Två riktningar kan vara icke-normaliserade vektorer. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| dir | Vector3 | Riktningsvektorn att jämföra med |

 **Result:**
Nummer


---


### compareTo{#compareTo}

| Namn | Beskrivning |
| --- | --- |
| compareTo(other) | Jämför den aktuella vektorn med en annan instans. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Nummer


---



