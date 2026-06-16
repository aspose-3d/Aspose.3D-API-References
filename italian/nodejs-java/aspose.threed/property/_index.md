---
title: "Property"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/property/
---
## Property class

Classe per contenere proprietà definite dall'utente.  @hideconstructor


## Metodi

### getValue{#getValue}

| Nome | Descrizione |
| --- | --- |
| getValue() | Ottiene o imposta il valore. Il valore. |

 **Result:**



---


### setValue{#setValue}

| Nome | Descrizione |
| --- | --- |
| setValue(value) | Ottiene o imposta il valore. Il valore. |

 **Result:**



---


### setName{#setName}

| Nome | Descrizione |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Nome | Descrizione |
| --- | --- |
| getValueType() | Ottiene il tipo del valore della proprietà. Il tipo del valore. |

 **Result:**



---


### getProperties{#getProperties}

| Nome | Descrizione |
| --- | --- |
| getProperties() | Ottiene la collezione di tutte le proprietà. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nome | Descrizione |
| --- | --- |
| getBindPoint(anim, create) | Ottiene il punto di binding della proprietà sull'istanza di animazione specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| anim | AnimationNode | Su quale animazione creare il punto di collegamento. |
| crea | boolean | Crea il punto di collegamento della proprietà se non viene trovato. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| getKeyframeSequence(anim, create) | Ottiene la sequenza di fotogrammi chiave sull'istanza di animazione specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| anim | AnimationNode | Su quale animazione creare la sequenza di fotogrammi chiave. |
| crea | boolean | Crea la sequenza di fotogrammi chiave se non viene trovata. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Restituisce una stringa che rappresenta la proprietà corrente. |

 **Result:**
Stringa


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



