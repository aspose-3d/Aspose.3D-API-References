---
title: "Plane"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/plane/
---
## Plane class

Piano parametrico.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza di Plane con dimensione predefinita 1x1. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(length, width) | Inizializza una nuova istanza di Plane. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| lunghezza | Numero | Lunghezza del piano. |
| width | Numero | Larghezza del piano. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(name, length, width, lengthSegments, widthSegments) | Inizializza una nuova istanza di Plane. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |
| lunghezza | Numero | Lunghezza del piano. |
| width | Numero | Larghezza del piano. |
| lengthSegments | Numero | Segmenti di lunghezza. |
| widthSegments | Numero | Segmenti di larghezza. |

 **Result:**



---


### getUp{#getUp}

| Nome | Descrizione |
| --- | --- |
| getUp() | Ottiene o imposta il vettore up del piano, il valore predefinito è (0, 1, 0), questo influisce sulla generazione del piano |

 **Result:**



---


### setUp{#setUp}

| Nome | Descrizione |
| --- | --- |
| setUp(value) | Ottiene o imposta il vettore up del piano, il valore predefinito è (0, 1, 0), questo influisce sulla generazione del piano |

 **Result:**



---


### getLength{#getLength}

| Nome | Descrizione |
| --- | --- |
| getLength() | Ottiene o imposta la lunghezza del piano. La lunghezza. |

 **Result:**



---


### setLength{#setLength}

| Nome | Descrizione |
| --- | --- |
| setLength(value) | Ottiene o imposta la lunghezza del piano. La lunghezza. |

 **Result:**



---


### getWidth{#getWidth}

| Nome | Descrizione |
| --- | --- |
| getWidth() | Ottiene o imposta la larghezza del piano. La larghezza. |

 **Result:**



---


### setWidth{#setWidth}

| Nome | Descrizione |
| --- | --- |
| setWidth(value) | Ottiene o imposta la larghezza del piano. La larghezza. |

 **Result:**



---


### getLengthSegments{#getLengthSegments}

| Nome | Descrizione |
| --- | --- |
| getLengthSegments() | Ottiene o imposta i segmenti di lunghezza. I segmenti di lunghezza. |

 **Result:**



---


### setLengthSegments{#setLengthSegments}

| Nome | Descrizione |
| --- | --- |
| setLengthSegments(value) | Ottiene o imposta i segmenti di lunghezza. I segmenti di lunghezza. |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Nome | Descrizione |
| --- | --- |
| getWidthSegments() | Ottiene o imposta i segmenti di larghezza. I segmenti di larghezza. |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Nome | Descrizione |
| --- | --- |
| setWidthSegments(value) | Ottiene o imposta i segmenti di larghezza. I segmenti di larghezza. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nome | Descrizione |
| --- | --- |
| getCastShadows() | Ottiene o imposta se questa geometria può proiettare ombre |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nome | Descrizione |
| --- | --- |
| setCastShadows(value) | Ottiene o imposta se questa geometria può proiettare ombre |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nome | Descrizione |
| --- | --- |
| getReceiveShadows() | Ottiene o imposta se questa geometria può ricevere ombre. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nome | Descrizione |
| --- | --- |
| setReceiveShadows(value) | Ottiene o imposta se questa geometria può ricevere ombre. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nome | Descrizione |
| --- | --- |
| getParentNodes() | Restituisce tutti i nodi genitore, un'entità può essere collegata a più nodi genitore per l'instancing della geometria. I nodi. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nome | Descrizione |
| --- | --- |
| getExcluded() | Ottiene o imposta se escludere questa entità durante l'esportazione. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nome | Descrizione |
| --- | --- |
| setExcluded(value) | Ottiene o imposta se escludere questa entità durante l'esportazione. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nome | Descrizione |
| --- | --- |
| getParentNode() | Ottiene o imposta il primo nodo genitore; se impostato il primo nodo genitore, questa entità verrà staccata dagli altri nodi genitore. Il nodo genitore. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nome | Descrizione |
| --- | --- |
| setParentNode(value) | Ottiene o imposta il primo nodo genitore; se impostato il primo nodo genitore, questa entità verrà staccata dagli altri nodi genitore. Il nodo genitore. |

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


### toMesh{#toMesh}

| Nome | Descrizione |
| --- | --- |
| toMesh() | Converti l'oggetto corrente in mesh |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Nome | Descrizione |
| --- | --- |
| getBoundingBox() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Nome | Descrizione |
| --- | --- |
| getEntityRendererKey() | Ottiene la chiave del renderer dell'entità registrata nel renderer |

 **Result:**
EntityRendererKey


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



