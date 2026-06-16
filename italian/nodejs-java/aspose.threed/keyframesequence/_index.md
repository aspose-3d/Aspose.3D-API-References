---
title: "KeyframeSequence"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

La sequenza di key-frame, descrive la trasformazione di un valore campionato nel tempo.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe KeyframeSequence. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Inizializza una nuova istanza della classe KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nome | Descrizione |
| --- | --- |
| getBindPoint() | Ottiene il punto di bind della proprietà che possiede questa curva |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Nome | Descrizione |
| --- | --- |
| getKeyFrames() | Ottiene i fotogrammi chiave di questa curva. Le chiavi. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Nome | Descrizione |
| --- | --- |
| getPostBehavior() | Ottiene il comportamento post che indica quale valore campionato dovrebbe essere dopo l'ultimo fotogramma chiave. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Nome | Descrizione |
| --- | --- |
| getPreBehavior() | Ottiene il comportamento pre che indica quale valore campionato dovrebbe essere prima del primo fotogramma. |

 **Result:**



---


### getName{#getName}

| Nome | Descrizione |
| --- | --- |
| getName() | Ottiene o imposta il nome. Il nome. |

 **Result:**



---


### setName{#setName}

| Nome | Descrizione |
| --- | --- |
| setName(value) | Ottiene o imposta il nome. Il nome. |

 **Result:**



---


### getProperties{#getProperties}

| Nome | Descrizione |
| --- | --- |
| getProperties() | Ottiene la collezione di tutte le proprietà. |

 **Result:**



---


### add{#add}

| Nome | Descrizione |
| --- | --- |
| add(time, value) | Crea un nuovo fotogramma chiave con il valore specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| time | Numero | Posizione temporale (misurata in secondi) |
| valore | Numero | Il valore in questa posizione temporale |

 **Result:**



---


### add{#add}

| Nome | Descrizione |
| --- | --- |
| add(time, value, interpolation) | Crea un nuovo fotogramma chiave con il valore specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| time | Numero | Posizione temporale (misurata in secondi) |
| valore | Numero | Il valore in questa posizione temporale |
| interpolation | Interpolazione | Interpolazione |

 **Result:**



---


### reset{#reset}

| Nome | Descrizione |
| --- | --- |
| reset() | Rimuove tutti i fotogrammi chiave e ripristina i comportamenti post/pre. |

 **Result:**



---


### removeProperty{#removeProperty}

| Nome | Descrizione |
| --- | --- |
| removeProperty(property) | Rimuove una proprietà dinamica. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| property | Property | Quale proprietà rimuovere |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nome | Descrizione |
| --- | --- |
| removeProperty(property) | Rimuovi la proprietà specificata identificata per nome |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| propert | Stringa | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nome | Descrizione |
| --- | --- |
| getProperty(property) | Ottieni il valore della proprietà specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| property | Stringa | Nome della proprietà |

 **Result:**
Oggetto


---


### setProperty{#setProperty}

| Nome | Descrizione |
| --- | --- |
| setProperty(property, value) | Imposta il valore della proprietà specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| property | Stringa | Nome della proprietà |
| valore | Oggetto | Il valore della proprietà |

 **Result:**
Oggetto


---


### findProperty{#findProperty}

| Nome | Descrizione |
| --- | --- |
| findProperty(propertyName) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal suo nome) |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | Stringa | Nome della proprietà. |

 **Result:**
Property


---


### iterator{#iterator}

| Nome | Descrizione |
| --- | --- |
| iterator() | Riservato per uso interno. |

 **Result:**
Property


---



