---
title: "BindPoint"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Un BindPoint viene solitamente creato su una proprietà di un oggetto, alcuni tipi di proprietà contengono più campi componenti (come un campo Vector3),  BindPoint genererà un canale per ogni campo componente e collegherà il campo a una o più istanze di sequenza di fotogrammi chiave attraverso i canali.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(scene, prop) | Inizializza una nuova istanza della classe BindPoint. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scene | Scena | La scena che contiene l'animazione. |
| prop | Proprietà | Proprietà. |

 **Result:**



---


### getProperty{#getProperty}

| Nome | Descrizione |
| --- | --- |
| getProperty() | Restituisce la proprietà associata a CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Nome | Descrizione |
| --- | --- |
| setProperty(value) | Restituisce la proprietà associata a CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Nome | Descrizione |
| --- | --- |
| getChannelsCount() | Restituisce il numero totale di canali di proprietà definiti in questa mappatura di curve di animazione. |

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
| getKeyframeSequence(channelName) | Restituisce la prima sequenza di keyframe nel canale specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| channelName | String | Il nome del canale da trovare |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Nome | Descrizione |
| --- | --- |
| getKeyframeSequences(channelName) | Restituisce tutte le sequenze di keyframe nel canale specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| channelName | String | Il nome del canale da trovare |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| createKeyframeSequence(name) | Crea una nuova curva e la collega al primo canale della mappatura delle curve |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Il nome della nuova sequenza. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Nome | Descrizione |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Collega la sequenza di keyframe al canale specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| channelName | String | Quale canale verrà associato alla sequenza di keyframe |
| sequenza | KeyframeSequence | La sequenza di keyframe da collegare |

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
| channelName | String | Il nome del canale da trovare |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Nome | Descrizione |
| --- | --- |
| addChannel(name, value) | Aggiunge la proprietà di canale specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome. |
| valore | Object | Valore. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Nome | Descrizione |
| --- | --- |
| addChannel(name, type, value) | Aggiunge la proprietà di canale specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome. |
| type | Classe | Tipo. |
| valore | Object | Valore. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Nome | Descrizione |
| --- | --- |
| resetChannels() | Svuota la proprietà channels di questa mappatura della curva di animazione. |

 **Result:**
boolean


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Formatta l'oggetto in stringa |

 **Result:**
String


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



