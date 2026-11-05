---
title: "ZShape"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/zshape/
---
## ZShape class

Profilo a forma di Z compatibile con IFC definito dai parametri.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore di ZShape |

 **Result:**



---


### getDepth{#getDepth}

| Nome | Descrizione |
| --- | --- |
| getDepth() | Ottiene o imposta la lunghezza del web. |

 **Result:**



---


### setDepth{#setDepth}

| Nome | Descrizione |
| --- | --- |
| setDepth(value) | Ottiene o imposta la lunghezza del web. |

 **Result:**



---


### getFlangeWidth{#getFlangeWidth}

| Nome | Descrizione |
| --- | --- |
| getFlangeWidth() | Ottiene o imposta la lunghezza della flange. |

 **Result:**



---


### setFlangeWidth{#setFlangeWidth}

| Nome | Descrizione |
| --- | --- |
| setFlangeWidth(value) | Ottiene o imposta la lunghezza della flange. |

 **Result:**



---


### getWebThickness{#getWebThickness}

| Nome | Descrizione |
| --- | --- |
| getWebThickness() | Ottiene o imposta lo spessore della parete. |

 **Result:**



---


### setWebThickness{#setWebThickness}

| Nome | Descrizione |
| --- | --- |
| setWebThickness(value) | Ottiene o imposta lo spessore della parete. |

 **Result:**



---


### getFlangeThickness{#getFlangeThickness}

| Nome | Descrizione |
| --- | --- |
| getFlangeThickness() | Ottiene o imposta lo spessore della flangia. |

 **Result:**



---


### setFlangeThickness{#setFlangeThickness}

| Nome | Descrizione |
| --- | --- |
| setFlangeThickness(value) | Ottiene o imposta lo spessore della flangia. |

 **Result:**



---


### getFilletRadius{#getFilletRadius}

| Nome | Descrizione |
| --- | --- |
| getFilletRadius() | Ottiene o imposta il raggio del raccordo tra la flangia e l'anima. |

 **Result:**



---


### setFilletRadius{#setFilletRadius}

| Nome | Descrizione |
| --- | --- |
| setFilletRadius(value) | Ottiene o imposta il raggio del raccordo tra la flangia e l'anima. |

 **Result:**



---


### getEdgeRadius{#getEdgeRadius}

| Nome | Descrizione |
| --- | --- |
| getEdgeRadius() | Ottiene o imposta il raggio del bordo della flangia. |

 **Result:**



---


### setEdgeRadius{#setEdgeRadius}

| Nome | Descrizione |
| --- | --- |
| setEdgeRadius(value) | Ottiene o imposta il raggio del bordo della flangia. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nome | Descrizione |
| --- | --- |
| getParentNodes() | Ottiene tutti i nodi genitori, un'entità può essere collegata a più nodi genitori per l'instancing della geometria. I nodi. |

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
| getParentNode() | Ottiene o imposta il primo nodo genitore; se impostato il primo nodo genitore, questa entità verrà staccata dagli altri nodi genitori. Il nodo genitore. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nome | Descrizione |
| --- | --- |
| setParentNode(value) | Ottiene o imposta il primo nodo genitore; se impostato il primo nodo genitore, questa entità verrà staccata dagli altri nodi genitori. Il nodo genitore. |

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


### getExtent{#getExtent}

| Nome | Descrizione |
| --- | --- |
| getExtent() | Restituisce l'estensione nelle dimensioni x e y. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Nome | Descrizione |
| --- | --- |
| getEntityRendererKey() | Ottiene la chiave del renderer dell'entità registrata nel renderer |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nome | Descrizione |
| --- | --- |
| getBoundingBox() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |

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



