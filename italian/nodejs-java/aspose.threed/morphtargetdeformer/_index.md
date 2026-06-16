---
title: "MorphTargetDeformer"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer fornisce animazione per vertice.  MorphTargetDeformer organizza tutti i target tramite MorphTargetChannel, ogni canale può organizzare più target.  Un uso comune del deformatore di morph target è applicare espressioni facciali a un personaggio.  Maggiori dettagli sono disponibili su https://en.wikipedia.org/wiki/Morph_target_animation


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe MorphTargetDeformer. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Inizializza una nuova istanza della classe MorphTargetDeformer. |

 **Result:**



---


### getChannels{#getChannels}

| Nome | Descrizione |
| --- | --- |
| getChannels() | Ottiene tutti i canali contenuti in questo deformer |

 **Result:**



---


### getOwner{#getOwner}

| Nome | Descrizione |
| --- | --- |
| getOwner() | Restituisce la geometria che possiede questo deformatore. |

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
| get(target) |  |

 **Result:**



---


### set{#set}

| Nome | Descrizione |
| --- | --- |
| set(target, value) |  |

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



