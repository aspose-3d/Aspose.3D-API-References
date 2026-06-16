---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Materiale per il rendering fisicamente basato su colore diffuso/speculare/brillantezza


## Proprietà

| Nome | Descrizione |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | La mappa texture per la lucentezza speculare |

## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore di PbrSpecularMaterial |

 **Result:**



---


### getTransparency{#getTransparency}

| Nome | Descrizione |
| --- | --- |
| getTransparency() | Ottiene o imposta il fattore di trasparenza. Il fattore deve essere compreso tra 0(0%, completamente opaco) e 1(100%, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato. Il fattore di trasparenza. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nome | Descrizione |
| --- | --- |
| setTransparency(value) | Ottiene o imposta il fattore di trasparenza. Il fattore deve essere compreso tra 0(0%, completamente opaco) e 1(100%, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato. Il fattore di trasparenza. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Nome | Descrizione |
| --- | --- |
| getNormalTexture() | Ottiene o imposta la texture della mappatura normale |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Nome | Descrizione |
| --- | --- |
| setNormalTexture(value) | Ottiene o imposta la texture della mappatura normale |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Nome | Descrizione |
| --- | --- |
| getSpecularGlossinessTexture() | Ottiene o imposta la texture per il colore speculare, il canale RGB memorizza il colore speculare e il canale A memorizza la lucentezza. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Nome | Descrizione |
| --- | --- |
| setSpecularGlossinessTexture(value) | Ottiene o imposta la texture per il colore speculare, il canale RGB memorizza il colore speculare e il canale A memorizza la lucentezza. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Nome | Descrizione |
| --- | --- |
| getGlossinessFactor() | Ottiene o imposta la lucentezza (levigatezza) del materiale, 1 indica perfettamente liscio e 0 indica perfettamente ruvido, il valore predefinito è 1, l'intervallo è [0, 1] |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Nome | Descrizione |
| --- | --- |
| setGlossinessFactor(value) | Ottiene o imposta la lucentezza (levigatezza) del materiale, 1 indica perfettamente liscio e 0 indica perfettamente ruvido, il valore predefinito è 1, l'intervallo è [0, 1] |

 **Result:**



---


### getSpecular{#getSpecular}

| Nome | Descrizione |
| --- | --- |
| getSpecular() | Ottiene o imposta il colore speculare del materiale, il valore predefinito è (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Nome | Descrizione |
| --- | --- |
| setSpecular(value) | Ottiene o imposta il colore speculare del materiale, il valore predefinito è (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Nome | Descrizione |
| --- | --- |
| getDiffuseTexture() | Ottiene o imposta la texture per diffuse |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Nome | Descrizione |
| --- | --- |
| setDiffuseTexture(value) | Ottiene o imposta la texture per diffuse |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Nome | Descrizione |
| --- | --- |
| getDiffuse() | Ottiene o imposta il colore diffuso del materiale, il valore predefinito è (1, 1, 1) |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Nome | Descrizione |
| --- | --- |
| setDiffuse(value) | Ottiene o imposta il colore diffuso del materiale, il valore predefinito è (1, 1, 1) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Nome | Descrizione |
| --- | --- |
| getEmissiveTexture() | Ottiene o imposta la texture per l'emissivo |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Nome | Descrizione |
| --- | --- |
| setEmissiveTexture(value) | Ottiene o imposta la texture per l'emissivo |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nome | Descrizione |
| --- | --- |
| getEmissiveColor() | Ottiene o imposta il colore emissivo, il valore predefinito è (0, 0, 0) |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nome | Descrizione |
| --- | --- |
| setEmissiveColor(value) | Ottiene o imposta il colore emissivo, il valore predefinito è (0, 0, 0) |

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



