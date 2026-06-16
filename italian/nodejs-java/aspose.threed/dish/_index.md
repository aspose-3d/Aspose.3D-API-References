---
title: "Dish"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/dish/
---
## Dish class

Piatto parametrizzato.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Crea una nuova istanza di Dish con raggio predefinito (10) e altezza predefinita (5) |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(radius, height) | Crea una nuova istanza di Dish con raggio e altezza specificati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| raggio | Numero | Il raggio del dish |
| height | Numero | L'altezza del dish |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(name, radius, height, widthSegments, heightSegments) | Crea una nuova istanza di Dish con raggio e altezza specificati |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Il nome del dish |
| raggio | Numero | Il raggio del dish |
| height | Numero | L'altezza del dish |
| widthSegments | Numero | Il segmento di larghezza del dish |
| heightSegments | Numero | Il segmento di altezza del piatto |

 **Result:**



---


### getHeight{#getHeight}

| Nome | Descrizione |
| --- | --- |
| getHeight() | Altezza del piatto |

 **Result:**



---


### setHeight{#setHeight}

| Nome | Descrizione |
| --- | --- |
| setHeight(value) | Altezza del piatto |

 **Result:**



---


### getRadius{#getRadius}

| Nome | Descrizione |
| --- | --- |
| getRadius() | Raggio del piatto |

 **Result:**



---


### setRadius{#setRadius}

| Nome | Descrizione |
| --- | --- |
| setRadius(value) | Raggio del piatto |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Nome | Descrizione |
| --- | --- |
| getWidthSegments() | Ottiene o imposta i segmenti di larghezza |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Nome | Descrizione |
| --- | --- |
| setWidthSegments(value) | Ottiene o imposta i segmenti di larghezza |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Nome | Descrizione |
| --- | --- |
| getHeightSegments() | Ottiene o imposta i segmenti di altezza |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Nome | Descrizione |
| --- | --- |
| setHeightSegments(value) | Ottiene o imposta i segmenti di altezza |

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



