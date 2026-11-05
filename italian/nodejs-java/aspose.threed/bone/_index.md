---
title: "Bone"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/bone/
---
## Bone class

Un osso definisce il sottoinsieme dei punti di controllo della geometria e il peso di fusione per ciascun punto di controllo.  L'oggetto Bone non può essere usato direttamente, un'istanza di SkinDeformer è utilizzata per deformare la geometria, e SkinDeformer include un insieme di ossa, ciascuna osso collegata a un nodo.  NOTA: Un punto di controllo di una geometria può essere associato a più di un osso.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe Bone. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Inizializza una nuova istanza della classe Bone. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Nome | Descrizione |
| --- | --- |
| getWeightCount() | Restituisce il conteggio dei pesi, questo viene esteso automaticamente da setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Nome | Descrizione |
| --- | --- |
| getTransform() | Ottiene o imposta la matrice di trasformazione del nodo che contiene il bone. |

 **Result:**



---


### setTransform{#setTransform}

| Nome | Descrizione |
| --- | --- |
| setTransform(value) | Ottiene o imposta la matrice di trasformazione del nodo che contiene il bone. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Nome | Descrizione |
| --- | --- |
| getBoneTransform() | Ottiene o imposta la matrice di trasformazione del bone. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Nome | Descrizione |
| --- | --- |
| setBoneTransform(value) | Ottiene o imposta la matrice di trasformazione del bone. |

 **Result:**



---


### getNode{#getNode}

| Nome | Descrizione |
| --- | --- |
| getNode() | Ottiene o imposta il nodo. Il nodo bone è il bone a cui è attaccata la pelle, il SkinDeformer utilizzerà il nodo bone per influenzare lo spostamento dei punti di controllo. Il nodo bone solitamente ha uno Skeleton allegato, ma non è obbligatorio. Lo Skeleton allegato è solitamente usato dal software DCC per mostrare lo skeleton all'utente. |

 **Result:**



---


### setNode{#setNode}

| Nome | Descrizione |
| --- | --- |
| setNode(value) | Ottiene o imposta il nodo. Il nodo bone è il bone a cui è attaccata la pelle, il SkinDeformer utilizzerà il nodo bone per influenzare lo spostamento dei punti di controllo. Il nodo bone solitamente ha uno Skeleton allegato, ma non è obbligatorio. Lo Skeleton allegato è solitamente usato dal software DCC per mostrare lo skeleton all'utente. |

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


### get{#get}

| Nome | Descrizione |
| --- | --- |
| get(index) |  |

 **Result:**



---


### set{#set}

| Nome | Descrizione |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Nome | Descrizione |
| --- | --- |
| getWeight(index) | Ottiene il peso per il punto di controllo specificato dall'indice |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| index | Numero | Indice del punto di controllo |

 **Result:**
Numero


---


### setWeight{#setWeight}

| Nome | Descrizione |
| --- | --- |
| setWeight(index, weight) | Imposta il peso per il punto di controllo specificato dall'indice |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| index | Numero | Indice del punto di controllo |
| peso | Numero | Nuovo peso |

 **Result:**
Numero


---


### removeProperty{#removeProperty}

| Nome | Descrizione |
| --- | --- |
| removeProperty(property) | Rimuove una proprietà dinamica. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | Proprietà | Quale proprietà rimuovere |

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
| propert | String | null |

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
| proprietà | String | Nome della proprietà |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nome | Descrizione |
| --- | --- |
| setProperty(property, value) | Imposta il valore della proprietà specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | String | Nome della proprietà |
| valore | Object | Il valore della proprietà |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nome | Descrizione |
| --- | --- |
| findProperty(propertyName) | Trova la proprietà. Può essere una proprietà dinamica (Creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (Identificata per il suo nome) |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | String | Nome della proprietà. |

 **Result:**
Proprietà


---



