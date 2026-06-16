---
title: "TrapeziumShape"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/trapeziumshape/
---
## TrapeziumShape class

Forma a Trapezio compatibile IFC definita da parametri.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore di TrapeziumShape |

 **Result:**



---


### getBottomXDim{#getBottomXDim}

| Nome | Descrizione |
| --- | --- |
| getBottomXDim() | Ottiene o imposta l'estensione della linea inferiore misurata lungo l'asse x. |

 **Result:**



---


### setBottomXDim{#setBottomXDim}

| Nome | Descrizione |
| --- | --- |
| setBottomXDim(value) | Ottiene o imposta l'estensione della linea inferiore misurata lungo l'asse x. |

 **Result:**



---


### getTopXDim{#getTopXDim}

| Nome | Descrizione |
| --- | --- |
| getTopXDim() | Ottiene o imposta l'estensione della linea superiore misurata lungo l'asse x. |

 **Result:**



---


### setTopXDim{#setTopXDim}

| Nome | Descrizione |
| --- | --- |
| setTopXDim(value) | Ottiene o imposta l'estensione della linea superiore misurata lungo l'asse x. |

 **Result:**



---


### getYDim{#getYDim}

| Nome | Descrizione |
| --- | --- |
| getYDim() | Ottiene o imposta la distanza tra le linee superiore e inferiore misurata lungo l'asse y. |

 **Result:**



---


### setYDim{#setYDim}

| Nome | Descrizione |
| --- | --- |
| setYDim(value) | Ottiene o imposta la distanza tra le linee superiore e inferiore misurata lungo l'asse y. |

 **Result:**



---


### getTopXOffset{#getTopXOffset}

| Nome | Descrizione |
| --- | --- |
| getTopXOffset() | Ottiene o imposta lo scostamento dall'inizio della linea superiore alla linea inferiore. |

 **Result:**



---


### setTopXOffset{#setTopXOffset}

| Nome | Descrizione |
| --- | --- |
| setTopXOffset(value) | Ottiene o imposta lo scostamento dall'inizio della linea superiore alla linea inferiore. |

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



