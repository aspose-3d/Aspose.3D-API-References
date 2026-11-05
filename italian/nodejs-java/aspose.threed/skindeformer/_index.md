---
title: "SkinDeformer"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/skindeformer/
---
## SkinDeformer class

Un deformatore di skin contiene più ossa per funzionare, ogni osso mescola una parte della geometria mediante i pesi dei punti di controllo.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe SkinDeformer. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Inizializza una nuova istanza della classe SkinDeformer. |

 **Result:**



---


### getBones{#getBones}

| Nome | Descrizione |
| --- | --- |
| getBones() | Restituisce tutte le ossa che il skin deformer contiene |

 **Result:**



---


### getOwner{#getOwner}

| Nome | Descrizione |
| --- | --- |
| getOwner() | Restituisce la geometria che possiede questo deformatore |

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



