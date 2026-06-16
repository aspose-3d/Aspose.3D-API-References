---
title: "VertexDeclaration"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

La dichiarazione della struttura di un vertice definito personalizzato


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Nome | Descrizione |
| --- | --- |
| getSealed() | Un VertexDeclaration verrà sigillato quando è stato utilizzato da com.aspose.threed.TriMesh`1 o TriMesh, non sono più consentite modifiche. |

 **Result:**



---


### getCount{#getCount}

| Nome | Descrizione |
| --- | --- |
| getCount() | Ottiene il conteggio di tutti i campi definiti in questo VertexDeclaration |

 **Result:**



---


### getSize{#getSize}

| Nome | Descrizione |
| --- | --- |
| getSize() | La dimensione in byte della struttura del vertice. |

 **Result:**



---


### get{#get}

| Nome | Descrizione |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Nome | Descrizione |
| --- | --- |
| clear() | Cancella tutti i campi. |

 **Result:**



---


### addField{#addField}

| Nome | Descrizione |
| --- | --- |
| addField(dataType, semantic, index, alias) | Aggiungi un nuovo campo del vertice |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| dataType | Numero | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| indice | Numero | L'indice per lo stesso campo semantico, -1 per generazione automatica |
| alias | Stringa | Il nome alias del campo |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Nome | Descrizione |
| --- | --- |
| fromGeometry(geometry, useFloat) | Crea un VertexDeclaration basato sul layout di una Geometry. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| geometria | Geometry | null |
| useFloat | boolean | Usa float invece del tipo double |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Nome | Descrizione |
| --- | --- |
| compareTo(other) | Confronta questa istanza con un oggetto specificato e restituisce un'indicazione dei loro valori relativi. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() |  |

 **Result:**
Stringa


---


### hashCode{#hashCode}

| Nome | Descrizione |
| --- | --- |
| hashCode() |  |

 **Result:**
Numero


---


### equals{#equals}

| Nome | Descrizione |
| --- | --- |
| equals(obj) | Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto VertexDeclaration, hanno lo stesso valore. |

 **Result:**
Numero


---


### iterator{#iterator}

| Nome | Descrizione |
| --- | --- |
| iterator() | Riservato per uso interno. |

 **Result:**
Numero


---



