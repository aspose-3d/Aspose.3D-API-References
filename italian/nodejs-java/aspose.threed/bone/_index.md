---
title: "Bone"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/bone/
---
## Bone class

Un bone definisce il sottoinsieme dei punti di controllo della geometria e il peso di fusione definito per ogni punto di controllo.  L'oggetto Bone non può essere usato direttamente, un'istanza di SkinDeformer è usata per deformare la geometria, e SkinDeformer viene fornito con un insieme di bones, ciascun bone collegato a un nodo.  NOTA: Un punto di controllo di una geometria può essere associato a più di un Bones.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe Bone. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |

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
| getWeightCount() | Ottiene il conteggio dei pesi, questo è automaticamente esteso da setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Nome | Descrizione |
| --- | --- |
| getTransform() | Ottiene o imposta la matrice di trasformazione del nodo che contiene l'osso. |

 **Result:**



---


### setTransform{#setTransform}

| Nome | Descrizione |
| --- | --- |
| setTransform(value) | Ottiene o imposta la matrice di trasformazione del nodo che contiene l'osso. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Nome | Descrizione |
| --- | --- |
| getBoneTransform() | Ottiene o imposta la matrice di trasformazione dell'osso. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Nome | Descrizione |
| --- | --- |
| setBoneTransform(value) | Ottiene o imposta la matrice di trasformazione dell'osso. |

 **Result:**



---


### getNode{#getNode}

| Nome | Descrizione |
| --- | --- |
| getNode() | Ottiene o imposta il nodo. Il bone node è l'osso a cui è attaccata la pelle, lo SkinDeformer utilizzerà il bone node per influenzare lo spostamento dei punti di controllo. Il bone node di solito ha uno Skeleton allegato, ma non è obbligatorio. Lo Skeleton allegato è solitamente usato dal software DCC per mostrare lo scheletro all'utente. |

 **Result:**



---


### setNode{#setNode}

| Nome | Descrizione |
| --- | --- |
| setNode(value) | Ottiene o imposta il nodo. Il bone node è l'osso a cui è attaccata la pelle, lo SkinDeformer utilizzerà il bone node per influenzare lo spostamento dei punti di controllo. Il bone node di solito ha uno Skeleton allegato, ma non è obbligatorio. Lo Skeleton allegato è solitamente usato dal software DCC per mostrare lo scheletro all'utente. |

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
| indice | Numero | Indice del punto di controllo |

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
| indice | Numero | Indice del punto di controllo |
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



