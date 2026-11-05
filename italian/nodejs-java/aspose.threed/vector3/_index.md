---
title: "Vector3"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Un vettore con tre componenti.


## Proprietà

| Nome | Descrizione |
| --- | --- |
| x | La componente x. |
| y | La componente y. |
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
| constructor_overload(x, y, z) | Inizializza una nuova istanza della struttura Vector3. |

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
| constructor_overload2(vec) | Inizializza una nuova istanza della struttura Vector3. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| vec | FVector3 | La coordinata x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nome | Descrizione |
| --- | --- |
| constructor_overload3(v) | Inizializza una nuova istanza della struttura Vector3. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| v | Numero | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nome | Descrizione |
| --- | --- |
| constructor_overload4(vec4) | Inizializza una nuova istanza della struttura Vector3. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Nome | Descrizione |
| --- | --- |
| getLength2() | Restituisce il quadrato della lunghezza. La length2. |

 **Result:**



---


### getLength{#getLength}

| Nome | Descrizione |
| --- | --- |
| getLength() | Restituisce la lunghezza di questo vettore. La lunghezza. |

 **Result:**



---


### equals{#equals}

| Nome | Descrizione |
| --- | --- |
| equals(obj) | Verifica se due vector3 sono uguali |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| obj | Object | L'oggetto per verificare l'uguaglianza. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Nome | Descrizione |
| --- | --- |
| hashCode() | Restituisce il codice hash di Vector3 |

 **Result:**
Numero


---


### dot{#dot}

| Nome | Descrizione |
| --- | --- |
| dot(rhs) | Restituisce il prodotto scalare di due vettori |

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
| set(newX, newY, newZ) | Imposta il componente x/y/z in una sola chiamata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| newX | Numero | La componente x. |
| newY | Numero | La componente y. |
| newZ | Numero | Il componente z. |

 **Result:**
Vector3


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Restituisce un java.lang.String che rappresenta il Vector3 corrente. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| Nome | Descrizione |
| --- | --- |
| angleBetween(dir, up) | Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| dir | Vector3 | Il vettore direzione da confrontare |
| up | Vector3 | Il vettore up del piano condiviso dalle due direzioni |

 **Result:**
Numero


---


### angleBetween{#angleBetween}

| Nome | Descrizione |
| --- | --- |
| angleBetween(dir) | Calcola l'angolo interno tra due direzioni. Le due direzioni possono essere vettori non normalizzati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| dir | Vector3 | Il vettore direzione da confrontare |

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



