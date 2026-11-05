---
title: "LambertMaterial"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Materiale per il modello di shading Lambert


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe LambertMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe LambertMaterial. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nome | Descrizione |
| --- | --- |
| getEmissiveColor() | Ottiene o imposta il colore emissivo |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nome | Descrizione |
| --- | --- |
| setEmissiveColor(value) | Ottiene o imposta il colore emissivo |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Nome | Descrizione |
| --- | --- |
| getAmbientColor() | Ottiene o imposta il colore ambientale L'esempio: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambientale. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Nome | Descrizione |
| --- | --- |
| setAmbientColor(value) | Ottiene o imposta il colore ambientale L'esempio: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambientale. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Nome | Descrizione |
| --- | --- |
| getDiffuseColor() | Ottiene o imposta il colore diffuso L'esempio: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuso. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Nome | Descrizione |
| --- | --- |
| setDiffuseColor(value) | Ottiene o imposta il colore diffuso L'esempio: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuso. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Nome | Descrizione |
| --- | --- |
| getTransparentColor() | Ottiene o imposta il colore trasparente. L'esempio: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); colore della trasparenza. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Nome | Descrizione |
| --- | --- |
| setTransparentColor(value) | Ottiene o imposta il colore trasparente. L'esempio: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); colore della trasparenza. |

 **Result:**



---


### getTransparency{#getTransparency}

| Nome | Descrizione |
| --- | --- |
| getTransparency() | Ottiene o imposta il fattore di trasparenza. Il fattore deve essere compreso tra 0 (0%, completamente opaco) e 1 (100%, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato. L'esempio: var mat = new LambertMaterial(); mat.Transparency = 0.3; fattore di trasparenza. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nome | Descrizione |
| --- | --- |
| setTransparency(value) | Ottiene o imposta il fattore di trasparenza. Il fattore deve essere compreso tra 0 (0%, completamente opaco) e 1 (100%, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato. L'esempio: var mat = new LambertMaterial(); mat.Transparency = 0.3; fattore di trasparenza. |

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



