---
title: "Quaternion"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Il quaternione è solitamente usato per eseguire rotazioni nella grafica computerizzata.


## Proprietà

| Nome | Descrizione |
| --- | --- |
| w | Il componente w. |
| x | La componente x. |
| y | La componente y. |
| z | Il componente z. |
| IDENTITY | Il quaternione di identità. |

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
| constructor_overload(w, x, y, z) | Inizializza una nuova istanza della classe Quaternion. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| w | Numero | Componente w del quaternione |
| x | Numero | Componente x del quaternione |
| y | Numero | Componente y del quaternione |
| z | Numero | Componente z del quaternione |

 **Result:**



---


### getLength{#getLength}

| Nome | Descrizione |
| --- | --- |
| getLength() | Restituisce la lunghezza del quaternione |

 **Result:**



---


### equals{#equals}

| Nome | Descrizione |
| --- | --- |
| equals(obj) | Verifica se due quaternioni sono uguali |

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
| hashCode() | Ottiene il codice hash del Quaternion |

 **Result:**
Numero


---


### conjugate{#conjugate}

| Nome | Descrizione |
| --- | --- |
| conjugate() | Restituisce un quaternion coniugato del quaternion corrente |

 **Result:**
Quaternion


---


### inverse{#inverse}

| Nome | Descrizione |
| --- | --- |
| inverse() | Restituisce un quaternion inverso del quaternion corrente |

 **Result:**
Quaternion


---


### dot{#dot}

| Nome | Descrizione |
| --- | --- |
| dot(q) | Prodotto scalare |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| q | Quaternion | Il quaternion |

 **Result:**
Numero


---


### eulerAngles{#eulerAngles}

| Nome | Descrizione |
| --- | --- |
| eulerAngles() | Converte il quaternion in rotazione rappresentata da angoli di Eulero. Tutte le componenti sono in radianti |

 **Result:**
Vector3


---


### normalize{#normalize}

| Nome | Descrizione |
| --- | --- |
| normalize() | Normalizza il quaternion |

 **Result:**
Quaternion


---


### concat{#concat}

| Nome | Descrizione |
| --- | --- |
| concat(rhs) | Concatena due quaternioni |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rh | Quaternion | null |

 **Result:**
Quaternion


---


### fromAngleAxis{#fromAngleAxis}

| Nome | Descrizione |
| --- | --- |
| fromAngleAxis(a, axis) | Crea un quaternion attorno all'asse fornito e ruota in senso orario |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| a | Numero | Rotazione in senso orario in radianti |
| axis | Vector3 | Asse |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Nome | Descrizione |
| --- | --- |
| fromRotation(orig, dest) | Crea un quaternion che ruota dalla direzione originale a quella di destinazione |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| orig | Vector3 | Direzione originale |
| dest | Vector3 | Direzione di destinazione |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Nome | Descrizione |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Crea un quaternion dall'angolo di Eulero fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| inclinazione | Numero | Inclinazione in radianti |
| imbardata | Numero | Imbardata in radianti |
| rollio | Numero | Rollio in radianti |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Nome | Descrizione |
| --- | --- |
| fromEulerAngle(eulerAngle) | Crea un quaternion dall'angolo di Eulero fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| eulerAngle | Vector3 | Angolo di Eulero in radianti |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Nome | Descrizione |
| --- | --- |
| toMatrix() | Converti la rotazione presentata dal quaternion in una matrice di trasformazione. |

 **Result:**
Matrix4


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Ottiene la rappresentazione del quaternion in stringa |

 **Result:**
String


---


### interpolate{#interpolate}

| Nome | Descrizione |
| --- | --- |
| interpolate(t, from, to) | Popola questo quaternion con il valore interpolato tra gli argomenti quaternion forniti per un t compreso tra from e to. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| t | Numero | Il coefficiente da interpolare. |
| da | Quaternion | Quaternion di origine. |
| a | Quaternion | Quaternion di destinazione. |

 **Result:**
Quaternion


---



