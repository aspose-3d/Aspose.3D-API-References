---
title: "ShaderMaterial"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Un materiale shader consente di descrivere il materiale tramite un motore di rendering esterno o un linguaggio shader.  ShaderMaterial utilizza ShaderTechnique per descrivere i dettagli concreti del rendering,  e quello più adatto verrà usato in base alla piattaforma di rendering finale.  Ad esempio, la tua istanza di ShaderMaterial può avere due tecniche, una definita in HLSL e un'altra definita in GLSL.  Su piattaforme non Windows, dovrebbe essere usato GLSL invece di HLSL


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe ShaderMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe ShaderMaterial. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |

 **Result:**



---


### getTechniques{#getTechniques}

| Nome | Descrizione |
| --- | --- |
| getTechniques() | Restituisce tutte le tecniche disponibili definite in questo materiale. |

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


### getTexture{#getTexture}

| Nome | Descrizione |
| --- | --- |
| getTexture(slotName) | Ottiene la texture dallo slot specificato, può essere il nome della proprietà del materiale o il nome del parametro dello shader |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| slotName | Stringa | Nome slot. |

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
| slotName | Stringa | Nome slot. |
| texture | TextureBase | Texture. |

 **Result:**
TextureBase


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


### iterator{#iterator}

| Nome | Descrizione |
| --- | --- |
| iterator() | Riservato per uso interno. |

 **Result:**
Property


---



