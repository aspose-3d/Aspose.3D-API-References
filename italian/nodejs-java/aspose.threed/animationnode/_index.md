---
title: "AnimationNode"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D supporta la gerarchia di animazione, ogni animazione può essere composta da diverse animazioni e dalla definizione dei fotogrammi chiave dell'animazione.  AnimationNode definisce la trasformazione di un valore di proprietà nel tempo, ad esempio, il nodo di animazione può essere usato per controllare la trasformazione di un nodo o altre proprietà numeriche dell'oggetto A3DObject.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe AnimationNode. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Inizializza una nuova istanza della classe AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Nome | Descrizione |
| --- | --- |
| getBindPoints() | Ottiene i punti di binding della proprietà corrente |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Nome | Descrizione |
| --- | --- |
| getSubAnimations() | Ottiene i nodi di sotto-animazione delle animazioni correnti |

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


### findBindPoint{#findBindPoint}

| Nome | Descrizione |
| --- | --- |
| findBindPoint(name) | Trova il punto di binding per nome. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome del punto di binding da trovare. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Nome | Descrizione |
| --- | --- |
| getBindPoint(target, propName, create) | Ottiene il punto di collegamento dell'animazione sulla proprietà specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| target | A3DObject | Su quale oggetto creare il punto di collegamento. |
| propName | Stringa | Il nome della proprietà. |
| crea | boolean | Se impostato a |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Ottiene la sequenza di fotogrammi chiave sulla proprietà e sul canale specificati. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| target | A3DObject | Su quale istanza creare la sequenza di fotogrammi chiave. |
| propName | Stringa | Il nome della proprietà. |
| channelName | Stringa | Il nome del canale. |
| crea | boolean | Se impostato a |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Ottiene la sequenza di fotogrammi chiave sulla proprietà specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| target | A3DObject | Su quale istanza creare la sequenza di fotogrammi chiave. |
| propName | Stringa | Il nome della proprietà. |
| crea | boolean | Se impostato a |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Nome | Descrizione |
| --- | --- |
| createBindPoint(obj, propName) | Crea un BindPoint basato sul tipo di dati della proprietà. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| obj | A3DObject | Object. |
| propName | Stringa | Nome della proprietà. |

 **Result:**
BindPoint


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



