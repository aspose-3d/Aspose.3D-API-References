---
title: "LinearExtrusion"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

L'estrusione lineare prende una forma 2D in input ed estende la forma nella terza dimensione.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore dell'istanza LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(shape, height) | Costruttore dell'istanza LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Nome | Descrizione |
| --- | --- |
| getShape() | La forma base da estrudere. |

 **Result:**



---


### setShape{#setShape}

| Nome | Descrizione |
| --- | --- |
| setShape(value) | La forma base da estrudere. |

 **Result:**



---


### getDirection{#getDirection}

| Nome | Descrizione |
| --- | --- |
| getDirection() | La direzione dell'estrusione, il valore predefinito è (0, 0, 1) |

 **Result:**



---


### setDirection{#setDirection}

| Nome | Descrizione |
| --- | --- |
| setDirection(value) | La direzione dell'estrusione, il valore predefinito è (0, 0, 1) |

 **Result:**



---


### getHeight{#getHeight}

| Nome | Descrizione |
| --- | --- |
| getHeight() | L'altezza della geometria estrusa, il valore predefinito è 1.0 |

 **Result:**



---


### setHeight{#setHeight}

| Nome | Descrizione |
| --- | --- |
| setHeight(value) | L'altezza della geometria estrusa, il valore predefinito è 1.0 |

 **Result:**



---


### getSlices{#getSlices}

| Nome | Descrizione |
| --- | --- |
| getSlices() | Le sezioni della geometria estrusa e attorcigliata, il valore predefinito è 1. |

 **Result:**



---


### setSlices{#setSlices}

| Nome | Descrizione |
| --- | --- |
| setSlices(value) | Le sezioni della geometria estrusa e attorcigliata, il valore predefinito è 1. |

 **Result:**



---


### getCenter{#getCenter}

| Nome | Descrizione |
| --- | --- |
| getCenter() | Se questo valore è false, l'intervallo Z dell'estrusione lineare è da 0 a altezza, altrimenti l'intervallo è da -altezza/2 a altezza/2. |

 **Result:**



---


### setCenter{#setCenter}

| Nome | Descrizione |
| --- | --- |
| setCenter(value) | Se questo valore è false, l'intervallo Z dell'estrusione lineare è da 0 a altezza, altrimenti l'intervallo è da -altezza/2 a altezza/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Nome | Descrizione |
| --- | --- |
| getTwistOffset() | L'offset utilizzato nella torsione, il valore predefinito è (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Nome | Descrizione |
| --- | --- |
| setTwistOffset(value) | L'offset utilizzato nella torsione, il valore predefinito è (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Nome | Descrizione |
| --- | --- |
| getTwist() | Il numero di gradi attraverso i quali la forma è estrusa. |

 **Result:**



---


### setTwist{#setTwist}

| Nome | Descrizione |
| --- | --- |
| setTwist(value) | Il numero di gradi attraverso i quali la forma è estrusa. |

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


### toMesh{#toMesh}

| Nome | Descrizione |
| --- | --- |
| toMesh() | Converti l'estrusione in mesh. |

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



