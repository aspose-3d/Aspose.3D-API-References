---
title: "Vector3"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Un vettore con tre componenti.


## Proprietà

| Nome | Descrizione |
| --- | --- |
| x | Il componente x. |
| y | Il componente y. |
| z | Il componente z. |
| ORIGIN | Ottiene la posizione di origine. L'origine. |
| UNIT_SCALE | Ottiene il vettore di scala unitario. |
| X_AXIS | Ottiene l'asse X. L'asse X. |
| Y_AXIS | Ottiene l'asse Y. L'asse Y. |
| Z_AXIS | Ottiene l'asse Z. L'asse Z. |

## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(x, y, z) | Inizializza una nuova istanza della struct Vector3. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| x | Numero | La coordinata x. |
| y | Numero | La coordinata y. |
| z | Numero | La coordinata z. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(vec) | Inizializza una nuova istanza della struct Vector3. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| vec | FVector3 | La coordinata x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nome | Descrizione |
| --- | --- |
| constructor_overload3(v) | Inizializza una nuova istanza della struct Vector3. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| v | Numero | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nome | Descrizione |
| --- | --- |
| constructor_overload4(vec4) | Inizializza una nuova istanza della struct Vector3. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Nome | Descrizione |
| --- | --- |
| getLength2() | Ottiene il quadrato della lunghezza. La lunghezza2. |

 **Result:**



---


### getLength{#getLength}

| Nome | Descrizione |
| --- | --- |
| getLength() | Ottiene la lunghezza di questo vettore. La lunghezza. |

 **Result:**



---


### equals{#equals}

| Nome | Descrizione |
| --- | --- |
| equals(obj) | Verifica se due vector3 sono uguali |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| obj | Oggetto | L'oggetto da verificare l'uguaglianza. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Nome | Descrizione |
| --- | --- |
| hashCode() | Ottiene il codice hash di Vector3 |

 **Result:**
Numero


---


### dot{#dot}

| Nome | Descrizione |
| --- | --- |
| dot(rhs) | Ottiene il prodotto scalare di due vettori |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rhs | Vector3 | Valore del lato destro. |

 **Result:**
Numero


---


### normalize{#normalize}

| Nome | Descrizione |
| --- | --- |
| normalize() | Normalizza questa istanza. |

 **Result:**
Vector3


---


### sin{#sin}

| Nome | Descrizione |
| --- | --- |
| sin() | Calcola il seno su ogni componente |

 **Result:**
Vector3


---


### cos{#cos}

| Nome | Descrizione |
| --- | --- |
| cos() | Calcola il coseno su ogni componente |

 **Result:**
Vector3


---


### cross{#cross}

| Nome | Descrizione |
| --- | --- |
| cross(rhs) | Prodotto vettoriale di due vettori |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rhs | Vector3 | Valore del lato destro. |

 **Result:**
Vector3


---


### set{#set}

| Nome | Descrizione |
| --- | --- |
| set(newX, newY, newZ) | Imposta i componenti x/y/z in una sola chiamata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| newX | Numero | Il componente x. |
| newY | Numero | Il componente y. |
| newZ | Numero | Il componente z. |

 **Result:**
Vector3


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Restituisce una java.lang.String che rappresenta il Vector3 corrente. |

 **Result:**
Stringa


---


### angleBetween{#angleBetween}

| Nome | Descrizione |
| --- | --- |
| angleBetween(dir, up) | Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| dir | Vector3 | Il vettore di direzione da confrontare |
| up | Vector3 | Il vettore up del piano condiviso delle due direzioni |

 **Result:**
Numero


---


### angleBetween{#angleBetween}

| Nome | Descrizione |
| --- | --- |
| angleBetween(dir) | Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| dir | Vector3 | Il vettore di direzione da confrontare |

 **Result:**
Numero


---


### compareTo{#compareTo}

| Nome | Descrizione |
| --- | --- |
| compareTo(other) | Confronta il vettore corrente con un'altra istanza. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Numero


---



