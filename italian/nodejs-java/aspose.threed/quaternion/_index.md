---
title: "Quaternione"
second_title: "Aspose.3D per Node.js via Java API Reference"
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
| x | Il componente x. |
| y | Il componente y. |
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
| w | Numero | componente w del quaternione |
| x | Numero | componente x del quaternione |
| y | Numero | componente y del quaternione |
| z | Numero | componente z del quaternione |

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
| obj | Oggetto | L'oggetto da verificare l'uguaglianza. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Nome | Descrizione |
| --- | --- |
| hashCode() | Restituisce il codice hash del Quaternion |

 **Result:**
Numero


---


### conjugate{#conjugate}

| Nome | Descrizione |
| --- | --- |
| conjugate() | Restituisce un quaternione coniugato del quaternione corrente |

 **Result:**
Quaternione


---


### inverse{#inverse}

| Nome | Descrizione |
| --- | --- |
| inverse() | Restituisce un quaternione inverso del quaternione corrente |

 **Result:**
Quaternione


---


### dot{#dot}

| Nome | Descrizione |
| --- | --- |
| dot(q) | Prodotto dei punti |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| q | Quaternione | Il quaternione |

 **Result:**
Numero


---


### eulerAngles{#eulerAngles}

| Nome | Descrizione |
| --- | --- |
| eulerAngles() | Converte il quaternione in rotazione rappresentata da angoli di Eulero. Tutte le componenti sono in radianti |

 **Result:**
Vector3


---


### normalize{#normalize}

| Nome | Descrizione |
| --- | --- |
| normalize() | Normalizza il quaternione |

 **Result:**
Quaternione


---


### concat{#concat}

| Nome | Descrizione |
| --- | --- |
| concat(rhs) | Concatena due quaternioni |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rh | Quaternione | null |

 **Result:**
Quaternione


---


### fromAngleAxis{#fromAngleAxis}

| Nome | Descrizione |
| --- | --- |
| fromAngleAxis(a, axis) | Crea un quaternione attorno all'asse dato e ruota in senso orario |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| a | Numero | Rotazione in senso orario in radianti |
| asse | Vector3 | Asse |

 **Result:**
Quaternione


---


### fromRotation{#fromRotation}

| Nome | Descrizione |
| --- | --- |
| fromRotation(orig, dest) | Crea un quaternione che ruota dalla direzione originale a quella di destinazione |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| orig | Vector3 | Direzione originale |
| dest | Vector3 | Direzione di destinazione |

 **Result:**
Quaternione


---


### fromEulerAngle{#fromEulerAngle}

| Nome | Descrizione |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Crea un quaternione dall'angolo di Eulero fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| pitch | Numero | pitch in radianti |
| yaw | Numero | Yaw in radianti |
| rotazione | Numero | Rotazione in radianti |

 **Result:**
Quaternione


---


### fromEulerAngle{#fromEulerAngle}

| Nome | Descrizione |
| --- | --- |
| fromEulerAngle(eulerAngle) | Crea un quaternione dall'angolo di Eulero fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| eulerAngle | Vector3 | Angolo di Eulero in radianti |

 **Result:**
Quaternione


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
| toString() | Ottiene la rappresentazione del quaternion in una stringa |

 **Result:**
Stringa


---


### interpolate{#interpolate}

| Nome | Descrizione |
| --- | --- |
| interpolate(t, from, to) | Popola questo quaternion con il valore interpolato tra gli argomenti quaternion forniti per un t compreso tra from e to. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| t | Numero | Il coefficiente da interpolare. |
| from | Quaternione | Quaternion di origine. |
| to | Quaternione | Quaternion di destinazione. |

 **Result:**
Quaternione


---



