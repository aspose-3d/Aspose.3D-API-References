---
title: "BindPoint"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Un BindPoint viene solitamente creato su una proprietà di un oggetto, alcuni tipi di proprietà contengono più campi componenti (come un campo Vector3),  BindPoint genererà un canale per ogni campo componente e collega il campo a una o più istanze di sequenza di fotogrammi chiave attraverso i canali.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(scene, prop) | Inizializza una nuova istanza della classe BindPoint. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scena | Scene | La scena che contiene l'animazione. |
| prop | Property | Proprietà. |

 **Result:**



---


### getProperty{#getProperty}

| Nome | Descrizione |
| --- | --- |
| getProperty() | Ottiene la proprietà associata a CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Nome | Descrizione |
| --- | --- |
| setProperty(value) | Ottiene la proprietà associata a CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Nome | Descrizione |
| --- | --- |
| getChannelsCount() | Ottiene il numero totale di canali di proprietà definiti in questa mappatura di curve di animazione. |

 **Result:**
Numero


---


### getName{#getName}

| Nome | Descrizione |
| --- | --- |
| getName() | Ottiene o imposta il nome. Il nome. |

 **Result:**
Numero


---


### setName{#setName}

| Nome | Descrizione |
| --- | --- |
| setName(value) | Ottiene o imposta il nome. Il nome. |

 **Result:**
Numero


---


### getProperties{#getProperties}

| Nome | Descrizione |
| --- | --- |
| getProperties() | Ottiene la collezione di tutte le proprietà. |

 **Result:**
Numero


---


### get{#get}

| Nome | Descrizione |
| --- | --- |
| get(channelName) |  |

 **Result:**
Numero


---


### getKeyframeSequence{#getKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| getKeyframeSequence(channelName) | Restituisce la prima sequenza di fotogrammi chiave nel canale specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| channelName | Stringa | Il nome del canale da trovare |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Nome | Descrizione |
| --- | --- |
| getKeyframeSequences(channelName) | Restituisce tutte le sequenze di fotogrammi chiave nel canale specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| channelName | Stringa | Il nome del canale da trovare |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| createKeyframeSequence(name) | Crea una nuova curva e la collega al primo canale della mappatura della curva |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Il nome della nuova sequenza. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Associa la sequenza di fotogrammi chiave al canale specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| channelName | Stringa | Quale canale verrà associato alla sequenza di fotogrammi chiave |
| sequenza | KeyframeSequence | La sequenza di fotogrammi chiave da associare |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Nome | Descrizione |
| --- | --- |
| getChannel(channelName) | Restituisce il canale per il nome fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| channelName | Stringa | Il nome del canale da trovare |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Nome | Descrizione |
| --- | --- |
| addChannel(name, value) | Aggiunge la proprietà del canale specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |
| valore | Oggetto | Valore. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Nome | Descrizione |
| --- | --- |
| addChannel(name, type, value) | Aggiunge la proprietà del canale specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |
| type | Classe | Tipo. |
| valore | Oggetto | Valore. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Nome | Descrizione |
| --- | --- |
| resetChannels() | Svuota i canali di proprietà di questa mappatura della curva di animazione. |

 **Result:**
boolean


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Formatta l'oggetto in stringa |

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



