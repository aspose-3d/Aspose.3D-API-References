---
title: "TransformBuilder"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

Il TransformBuilder è usato per costruire la matrice di trasformazione mediante una catena di trasformazioni.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(initial, order) | Crea un TransformBuilder con la matrice di trasformazione iniziale e l'ordine di composizione specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| initia | Matrix4 | null |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(order) | Crea un TransformBuilder con la matrice di trasformazione identità iniziale e l'ordine di composizione specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Nome | Descrizione |
| --- | --- |
| getMatrix() | Ottiene o imposta il valore corrente della matrice |

 **Result:**



---


### setMatrix{#setMatrix}

| Nome | Descrizione |
| --- | --- |
| setMatrix(value) | Ottiene o imposta il valore corrente della matrice |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Nome | Descrizione |
| --- | --- |
| getComposeOrder() | Ottiene o imposta l'ordine di composizione della catena. Il valore della proprietà è la costante intera ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Nome | Descrizione |
| --- | --- |
| setComposeOrder(value) | Ottiene o imposta l'ordine di composizione della catena. Il valore della proprietà è la costante intera ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Nome | Descrizione |
| --- | --- |
| compose(m) | Aggiungi o anteponi l'argomento alla matrice interna. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Nome | Descrizione |
| --- | --- |
| append(m) | Aggiungi la nuova matrice di trasformazione alla catena di trasformazione. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Nome | Descrizione |
| --- | --- |
| prepend(m) | Anteponi la nuova matrice di trasformazione alla catena di trasformazione. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Nome | Descrizione |
| --- | --- |
| rearrange(newX, newY, newZ) | Riorganizza la disposizione dell'asse. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| newX | Asse | Asse |
| newY | Asse | Asse |
| newZ | Asse | Asse |

 **Result:**



---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(s) | Collega una matrice di trasformazione di scala con una componente scalata di s |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Numero | null |

 **Result:**



---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(x, y, z) | Collega una matrice di trasformazione di scala |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Numero | null |
|  | Numero | null |
|  | Numero | null |

 **Result:**



---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(s) | Collega una trasformazione di scala |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nome | Descrizione |
| --- | --- |
| rotateDegree(angle, axis) | Collega una trasformazione di rotazione in gradi |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| angle | Numero | L'angolo da ruotare in gradi |
| axis | Vector3 | L'asse da ruotare |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nome | Descrizione |
| --- | --- |
| rotateRadian(angle, axis) | Collega una trasformazione di rotazione in radianti |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| angle | Numero | L'angolo da ruotare in radianti |
| axis | Vector3 | L'asse da ruotare |

 **Result:**



---


### rotate{#rotate}

| Nome | Descrizione |
| --- | --- |
| rotate(q) | Collega una rotazione mediante un quaternione |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Quaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Nome | Descrizione |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Collega una rotazione mediante angoli di Eulero in gradi |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| gradi | Numero | null |
| gradi | Numero | null |
| gradi | Numero | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nome | Descrizione |
| --- | --- |
| rotateEulerRadian(x, y, z) | Concatena una rotazione per angoli di Eulero in radianti |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Numero | null |
|  | Numero | null |
|  | Numero | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nome | Descrizione |
| --- | --- |
| rotateEulerRadian(r) | Concatena una rotazione per angoli di Eulero in radianti |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Nome | Descrizione |
| --- | --- |
| translate(tx, ty, tz) | Concatena una trasformazione di traslazione |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| t | Numero | null |
| t | Numero | null |
| t | Numero | null |

 **Result:**



---


### translate{#translate}

| Nome | Descrizione |
| --- | --- |
| translate(v) | Concatena una trasformazione di traslazione |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Nome | Descrizione |
| --- | --- |
| reset() | Ripristina la trasformazione alla matrice identità |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nome | Descrizione |
| --- | --- |
| rotateDegree(rot, order) | Aggiungi rotazione con ordine specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rot | Vector3 | Rotazione in gradi |
| order | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nome | Descrizione |
| --- | --- |
| rotateRadian(rot, order) | Aggiungi rotazione con ordine specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rot | Vector3 | Rotazione in radianti |
| order | RotationOrder | RotationOrder |

 **Result:**



---



