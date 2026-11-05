---
title: "Materiale"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/material/
---
## Material class

Il materiale definisce i parametri necessari per l'aspetto visivo della geometria.  Aspose.3D fornisce modelli di shading per LambertMaterial, PhongMaterial e ShaderMaterial  @hideconstructor


## Proprietà

| Nome | Descrizione |
| --- | --- |
| MAP_SPECULAR | Usato in setTexture(java.lang.String, com.aspose.threed.TextureBase) per assegnare una mappatura di texture speculare. |
| MAP_DIFFUSE | Usato in setTexture(java.lang.String, com.aspose.threed.TextureBase) per assegnare una mappatura di texture diffusa. |
| MAP_EMISSIVE | Usato in setTexture(java.lang.String, com.aspose.threed.TextureBase) per assegnare una mappatura di texture emissiva. |
| MAP_AMBIENT | Usato in setTexture(java.lang.String, com.aspose.threed.TextureBase) per assegnare una mappatura di texture ambientale. |
| MAP_NORMAL | Usato in setTexture(java.lang.String, com.aspose.threed.TextureBase) per assegnare una mappatura di texture normale. |

## Metodi

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


### getTexture{#getTexture}

| Nome | Descrizione |
| --- | --- |
| getTexture(slotName) | Ottiene la texture dallo slot specificato, può essere il nome della proprietà del materiale o il nome del parametro dello shader |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| slotName | String | Nome slot. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Nome | Descrizione |
| --- | --- |
| setTexture(slotName, texture) | Imposta la texture nello slot specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| slotName | String | Nome slot. |
| texture | TextureBase | Texture. |

 **Result:**
TextureBase


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


### iterator{#iterator}

| Nome | Descrizione |
| --- | --- |
| iterator() | Riservato per uso interno. |

 **Result:**
Proprietà


---



