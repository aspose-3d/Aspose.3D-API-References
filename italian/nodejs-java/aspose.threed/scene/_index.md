---
title: "Scena"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/scene/
---
## Scene class

Una scena è un oggetto di livello superiore che contiene i nodi, le geometrie, i materiali, le texture, l'animazione, le pose, le sotto-scene, ecc.  La scena può avere sotto-scene, funge da supporto multi-documento in file come collada/blender/fbx.  La gerarchia dei nodi è accessibile tramite RootNodeLibrary, che viene utilizzata per mantenere un riferimento agli oggetti non allegati durante la serializzazione (come metadati o oggetti personalizzati) in modo da poterla usare come libreria.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe Scena. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(entity) | Inizializza una nuova istanza della classe Scena con un'entità collegata a un nuovo nodo. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entità | Entità | L'entità iniziale che è collegata alla scena |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(parentScene, name) | Inizializza una nuova istanza della classe Scena come sotto-scena. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| parentScene | Scena | La scena genitore. |
| name | String | Nome della scena. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nome | Descrizione |
| --- | --- |
| constructor_overload3(fileName) | Inizializza una nuova istanza della classe Scena e apre immediatamente il file. Questo è un costruttore obsoleto, si prega di utilizzare #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome del file da aprire. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Nome | Descrizione |
| --- | --- |
| getSubScenes() | Restituisce tutte le sotto-scene |

 **Result:**



---


### getLibrary{#getLibrary}

| Nome | Descrizione |
| --- | --- |
| getLibrary() | Gli oggetti che non sono utilizzati direttamente nella gerarchia della scena possono essere definiti nella Library. Questo è utile quando si utilizzano sotto-scene e si inseriscono componenti riutilizzabili sotto le sotto-scene. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Nome | Descrizione |
| --- | --- |
| getAnimationClips() | Restituisce tutti gli AnimationClip definiti nella scena. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Nome | Descrizione |
| --- | --- |
| getCurrentAnimationClip() | Restituisce o imposta l'AnimationClip attivo |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Nome | Descrizione |
| --- | --- |
| setCurrentAnimationClip(value) | Restituisce o imposta l'AnimationClip attivo |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nome | Descrizione |
| --- | --- |
| getAssetInfo() | Restituisce o imposta le informazioni dell'asset di livello superiore. Le informazioni del documento. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nome | Descrizione |
| --- | --- |
| setAssetInfo(value) | Restituisce o imposta le informazioni dell'asset di livello superiore. Le informazioni del documento. |

 **Result:**



---


### getPoses{#getPoses}

| Nome | Descrizione |
| --- | --- |
| getPoses() | Restituisce tutti i Pose utilizzati in questa scena. I pose. |

 **Result:**



---


### getRootNode{#getRootNode}

| Nome | Descrizione |
| --- | --- |
| getRootNode() | Restituisce il nodo radice della scena. Il nodo radice. |

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


### getAnimationClip{#getAnimationClip}

| Nome | Descrizione |
| --- | --- |
| getAnimationClip(name) | Restituisce un AnimationClip con nome |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Il |

 **Result:**
AnimationClip


---


### clear{#clear}

| Nome | Descrizione |
| --- | --- |
| clear() | Cancella il contenuto della scena e ripristina le impostazioni predefinite. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Nome | Descrizione |
| --- | --- |
| createAnimationClip(name) | Una funzione abbreviata per creare e registrare l'AnimationClip. Il primo AnimationClip sarà assegnato al CurrentAnimationClip |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome dell'Animation clip |

 **Result:**
AnimationClip


---


### open{#open}

| Nome | Descrizione |
| --- | --- |
| open(fileName, options) | Apre la scena dal percorso fornito usando il formato file specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome file. |
| opzioni | LoadOptions | Configurazione più dettagliata per aprire lo stream. |

 **Result:**
AnimationClip


---


### open{#open}

| Nome | Descrizione |
| --- | --- |
| open(fileName) | Apre la scena dal percorso fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome file. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Nome | Descrizione |
| --- | --- |
| fromFile(fileName) | Apre la scena dal percorso fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome file. |

 **Result:**
AnimationClip


---


### save{#save}

| Nome | Descrizione |
| --- | --- |
| save(fileName) | Salva la scena nel percorso specificato usando il formato file specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome file. |

 **Result:**
AnimationClip


---


### save{#save}

| Nome | Descrizione |
| --- | --- |
| save(fileName, format) | Salva la scena nel percorso specificato usando il formato file specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome file. |
| format | FileFormat | Formato. |

 **Result:**
AnimationClip


---


### save{#save}

| Nome | Descrizione |
| --- | --- |
| save(fileName, options) | Salva la scena nel percorso specificato usando il formato file specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome file. |
| opzioni | SaveOptions | Configurazione più dettagliata per salvare lo stream. |

 **Result:**
AnimationClip


---


### render{#render}

| Nome | Descrizione |
| --- | --- |
| render(camera, fileName) | Renderizza la scena in un file esterno dalla prospettiva della camera specificata. La dimensione di output predefinita è 1024x768 e il formato di output è png |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| camera | Camera | Da quale prospettiva della camera renderizzare la scena |
| fileName | String | Il nome del file di output |

 **Result:**
AnimationClip


---


### render{#render}

| Nome | Descrizione |
| --- | --- |
| render(camera, fileName, size, format) | Renderizza la scena in un file esterno dalla prospettiva della telecamera fornita. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| camera | Camera | Da quale prospettiva della camera renderizzare la scena |
| fileName | String | Il nome del file di output |
| dimensione | Vector2 | La dimensione dell'immagine finale renderizzata |
| format | String | Il formato immagine del file di output |

 **Result:**
AnimationClip


---


### render{#render}

| Nome | Descrizione |
| --- | --- |
| render(camera, fileName, size, format, options) | Renderizza la scena in un file esterno dalla prospettiva della telecamera fornita. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| camera | Camera | Da quale prospettiva della camera renderizzare la scena |
| fileName | String | Il nome del file di output |
| dimensione | Vector2 | La dimensione dell'immagine finale renderizzata |
| format | String | Il formato immagine del file di output |
| opzioni | ImageRenderOptions | L'opzione per personalizzare alcune impostazioni interne. |

 **Result:**
AnimationClip


---


### render{#render}

| Nome | Descrizione |
| --- | --- |
| render(camera, bitmap) | Renderizza la scena in un bitmap dalla prospettiva della telecamera fornita. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| camera | Camera | Da quale prospettiva della camera renderizzare la scena |
| bitmap | TextureData | Destinazione del risultato renderizzato |

 **Result:**
AnimationClip


---


### render{#render}

| Nome | Descrizione |
| --- | --- |
| render(camera, bitmap, options) | Renderizza la scena in un bitmap dalla prospettiva della telecamera fornita. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| camera | Camera | Da quale prospettiva della camera renderizzare la scena |
| bitmap | TextureData | Destinazione del risultato renderizzato |
| opzioni | ImageRenderOptions | L'opzione per personalizzare alcune impostazioni interne. |

 **Result:**
AnimationClip


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



