---
title: "AnimationClip"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Il clip di Animazione è una raccolta di animazioni.  La scena può avere uno o più clip di animazione.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe AnimationClip. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |

 **Result:**



---


### getAnimations{#getAnimations}

| Nome | Descrizione |
| --- | --- |
| getAnimations() | Ottiene le animazioni contenute nel clip. I livelli. |

 **Result:**



---


### getDescription{#getDescription}

| Nome | Descrizione |
| --- | --- |
| getDescription() | Ottiene o imposta la descrizione di questo clip di animazione |

 **Result:**



---


### setDescription{#setDescription}

| Nome | Descrizione |
| --- | --- |
| setDescription(value) | Ottiene o imposta la descrizione di questo clip di animazione |

 **Result:**



---


### getStart{#getStart}

| Nome | Descrizione |
| --- | --- |
| getStart() | Ottiene o imposta il tempo in secondi dell'inizio del clip. |

 **Result:**



---


### setStart{#setStart}

| Nome | Descrizione |
| --- | --- |
| setStart(value) | Ottiene o imposta il tempo in secondi dell'inizio del clip. |

 **Result:**



---


### getStop{#getStop}

| Nome | Descrizione |
| --- | --- |
| getStop() | Ottiene o imposta il tempo in secondi della fine del clip. |

 **Result:**



---


### setStop{#setStop}

| Nome | Descrizione |
| --- | --- |
| setStop(value) | Ottiene o imposta il tempo in secondi della fine del clip. |

 **Result:**



---


### getScene{#getScene}

| Nome | Descrizione |
| --- | --- |
| getScene() | Ottiene la scena a cui appartiene questo oggetto |

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


### createAnimationNode{#createAnimationNode}

| Nome | Descrizione |
| --- | --- |
| createAnimationNode(nodeName) | Una funzione abbreviata per creare e registrare il nodo di animazione sul clip corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | Stringa | Nome del nuovo nodo di animazione |

 **Result:**
AnimationNode


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



