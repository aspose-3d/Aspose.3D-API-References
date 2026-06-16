---
title: "TShape"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/tshape/
---
## TShape class

Forma a T compatibile IFC definita da parametri.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore di TShape |

 **Result:**



---


### getDepth{#getDepth}

| Nome | Descrizione |
| --- | --- |
| getDepth() | Restituisce o imposta la lunghezza del web. |

 **Result:**



---


### setDepth{#setDepth}

| Nome | Descrizione |
| --- | --- |
| setDepth(value) | Restituisce o imposta la lunghezza del web. |

 **Result:**



---


### getFlangeWidth{#getFlangeWidth}

| Nome | Descrizione |
| --- | --- |
| getFlangeWidth() | Restituisce o imposta la lunghezza della flangia. |

 **Result:**



---


### setFlangeWidth{#setFlangeWidth}

| Nome | Descrizione |
| --- | --- |
| setFlangeWidth(value) | Restituisce o imposta la lunghezza della flangia. |

 **Result:**



---


### getWebThickness{#getWebThickness}

| Nome | Descrizione |
| --- | --- |
| getWebThickness() | Restituisce o imposta lo spessore della parete del web. |

 **Result:**



---


### setWebThickness{#setWebThickness}

| Nome | Descrizione |
| --- | --- |
| setWebThickness(value) | Restituisce o imposta lo spessore della parete del web. |

 **Result:**



---


### getFlangeThickness{#getFlangeThickness}

| Nome | Descrizione |
| --- | --- |
| getFlangeThickness() | Restituisce o imposta lo spessore della parete della flangia. |

 **Result:**



---


### setFlangeThickness{#setFlangeThickness}

| Nome | Descrizione |
| --- | --- |
| setFlangeThickness(value) | Restituisce o imposta lo spessore della parete della flangia. |

 **Result:**



---


### getFilletRadius{#getFilletRadius}

| Nome | Descrizione |
| --- | --- |
| getFilletRadius() | Ottiene o imposta il raggio del smusso tra l'anima e la flangia. |

 **Result:**



---


### setFilletRadius{#setFilletRadius}

| Nome | Descrizione |
| --- | --- |
| setFilletRadius(value) | Ottiene o imposta il raggio del smusso tra l'anima e la flangia. |

 **Result:**



---


### getFlangeEdgeRadius{#getFlangeEdgeRadius}

| Nome | Descrizione |
| --- | --- |
| getFlangeEdgeRadius() | Ottiene o imposta il raggio del bordo della flangia. |

 **Result:**



---


### setFlangeEdgeRadius{#setFlangeEdgeRadius}

| Nome | Descrizione |
| --- | --- |
| setFlangeEdgeRadius(value) | Ottiene o imposta il raggio del bordo della flangia. |

 **Result:**



---


### getWebEdgeRadius{#getWebEdgeRadius}

| Nome | Descrizione |
| --- | --- |
| getWebEdgeRadius() | Ottiene o imposta il raggio del bordo dell'anima. |

 **Result:**



---


### setWebEdgeRadius{#setWebEdgeRadius}

| Nome | Descrizione |
| --- | --- |
| setWebEdgeRadius(value) | Ottiene o imposta il raggio del bordo dell'anima. |

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



