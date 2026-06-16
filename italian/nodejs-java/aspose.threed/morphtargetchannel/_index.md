---
title: "MorphTargetChannel"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Un MorphTargetChannel è usato da MorphTargetDeformer per organizzare le geometrie target.  Alcuni formati di file come FBX supportano più canali in parallelo.  Il peso è compreso tra 0 e 1.0, e il peso predefinito per il target è 0.0;


## Proprietà

| Nome | Descrizione |
| --- | --- |
| DEFAULT_WEIGHT | Peso predefinito per il morph target. |

## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe MorphTargetChannel. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Inizializza una nuova istanza della classe MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| Nome | Descrizione |
| --- | --- |
| getWeights() | Ottiene i valori completi del peso delle geometrie target. I pesi completi. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Nome | Descrizione |
| --- | --- |
| getChannelWeight() | Ottiene o imposta il peso del deformatore di questo canale. Il peso è compreso tra 0.0 e 1.0 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Nome | Descrizione |
| --- | --- |
| setChannelWeight(value) | Ottiene o imposta il peso del deformatore di questo canale. Il peso è compreso tra 0.0 e 1.0 |

 **Result:**



---


### getTargets{#getTargets}

| Nome | Descrizione |
| --- | --- |
| getTargets() | Ottiene tutti i target associati al canale. |

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


### getWeight{#getWeight}

| Nome | Descrizione |
| --- | --- |
| getWeight(target) | Restituisce il peso per il target specificato; se il target non appartiene a questo canale, viene restituito il valore predefinito 0. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| obiettivo | Forma | null |

 **Result:**
Numero


---


### setWeight{#setWeight}

| Nome | Descrizione |
| --- | --- |
| setWeight(target, weight) | Imposta il peso per il target specificato, il valore predefinito è 1, l'intervallo deve essere compreso tra 0 e 1. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| obiettivo | Forma | null |
| pesare | Numero | null |

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



