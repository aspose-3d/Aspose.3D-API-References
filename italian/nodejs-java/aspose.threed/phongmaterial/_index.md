---
title: "PhongMaterial"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/phongmaterial/
---
## PhongMaterial class

Materiale per il modello di shading Blinn-Phong.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe PhongMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe PhongMaterial. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |

 **Result:**



---


### getSpecularColor{#getSpecularColor}

| Nome | Descrizione |
| --- | --- |
| getSpecularColor() | Ottiene o imposta il colore speculare. |

 **Result:**



---


### setSpecularColor{#setSpecularColor}

| Nome | Descrizione |
| --- | --- |
| setSpecularColor(value) | Ottiene o imposta il colore speculare. |

 **Result:**



---


### getSpecularFactor{#getSpecularFactor}

| Nome | Descrizione |
| --- | --- |
| getSpecularFactor() | Ottiene o imposta il fattore speculare. La formula dello speculare: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### setSpecularFactor{#setSpecularFactor}

| Nome | Descrizione |
| --- | --- |
| setSpecularFactor(value) | Ottiene o imposta il fattore speculare. La formula dello speculare: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### getShininess{#getShininess}

| Nome | Descrizione |
| --- | --- |
| getShininess() | Ottiene o imposta la brillantezza, controlla la dimensione dell'evidenziazione speculare. La formula dello speculare: SpecularColor SpecularFactor (N dot H) ^ Shininess La brillantezza. |

 **Result:**



---


### setShininess{#setShininess}

| Nome | Descrizione |
| --- | --- |
| setShininess(value) | Ottiene o imposta la brillantezza, controlla la dimensione dell'evidenziazione speculare. La formula dello speculare: SpecularColor SpecularFactor (N dot H) ^ Shininess La brillantezza. |

 **Result:**



---


### getReflectionColor{#getReflectionColor}

| Nome | Descrizione |
| --- | --- |
| getReflectionColor() | Ottiene o imposta il colore di riflessione. La riflessione. |

 **Result:**



---


### setReflectionColor{#setReflectionColor}

| Nome | Descrizione |
| --- | --- |
| setReflectionColor(value) | Ottiene o imposta il colore di riflessione. La riflessione. |

 **Result:**



---


### getReflectionFactor{#getReflectionFactor}

| Nome | Descrizione |
| --- | --- |
| getReflectionFactor() | Ottiene o imposta l'attenuazione del colore di riflessione. Il fattore di riflessione. |

 **Result:**



---


### setReflectionFactor{#setReflectionFactor}

| Nome | Descrizione |
| --- | --- |
| setReflectionFactor(value) | Ottiene o imposta l'attenuazione del colore di riflessione. Il fattore di riflessione. |

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
| getAmbientColor() | Ottiene o imposta il colore ambientale L'esempio: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Nome | Descrizione |
| --- | --- |
| setAmbientColor(value) | Ottiene o imposta il colore ambientale L'esempio: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Nome | Descrizione |
| --- | --- |
| getDiffuseColor() | Ottiene o imposta il colore diffuso. Esempio: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuso. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Nome | Descrizione |
| --- | --- |
| setDiffuseColor(value) | Ottiene o imposta il colore diffuso. Esempio: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuso. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Nome | Descrizione |
| --- | --- |
| getTransparentColor() | Ottiene o imposta il colore trasparente. Esempio: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); colore del trasparente. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Nome | Descrizione |
| --- | --- |
| setTransparentColor(value) | Ottiene o imposta il colore trasparente. Esempio: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); colore del trasparente. |

 **Result:**



---


### getTransparency{#getTransparency}

| Nome | Descrizione |
| --- | --- |
| getTransparency() | Ottiene o imposta il fattore di trasparenza. Il fattore deve essere compreso tra 0 (0%, completamente opaco) e 1 (100%, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato. Esempio: var mat = new LambertMaterial(); mat.Transparency = 0.3; fattore di trasparenza. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nome | Descrizione |
| --- | --- |
| setTransparency(value) | Ottiene o imposta il fattore di trasparenza. Il fattore deve essere compreso tra 0 (0%, completamente opaco) e 1 (100%, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato. Esempio: var mat = new LambertMaterial(); mat.Transparency = 0.3; fattore di trasparenza. |

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



