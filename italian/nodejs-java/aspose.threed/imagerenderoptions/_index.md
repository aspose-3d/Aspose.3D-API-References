---
title: "ImageRenderOptions"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/imagerenderoptions/
---
## ImageRenderOptions class

Opzioni per Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) e  Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions)


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza un'istanza di ImageRenderOptions |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Nome | Descrizione |
| --- | --- |
| getBackgroundColor() | Il colore di sfondo del risultato del rendering. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Nome | Descrizione |
| --- | --- |
| setBackgroundColor(value) | Il colore di sfondo del risultato del rendering. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Nome | Descrizione |
| --- | --- |
| getAssetDirectories() | Directory che memorizzano risorse esterne (come texture) |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Nome | Descrizione |
| --- | --- |
| getEnableShadows() | Ottiene o imposta se renderizzare le ombre. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Nome | Descrizione |
| --- | --- |
| setEnableShadows(value) | Ottiene o imposta se renderizzare le ombre. |

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



