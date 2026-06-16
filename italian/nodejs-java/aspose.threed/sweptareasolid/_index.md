---
title: "SweptAreaSolid"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/sweptareasolid/
---
## SweptAreaSolid class

Un SweptAreaSolid costruisce una geometria spazzolando un profilo lungo una direttrice.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getShape{#getShape}

| Nome | Descrizione |
| --- | --- |
| getShape() | Il profilo di base per costruire la geometria. |

 **Result:**



---


### setShape{#setShape}

| Nome | Descrizione |
| --- | --- |
| setShape(value) | Il profilo di base per costruire la geometria. |

 **Result:**



---


### getDirectrix{#getDirectrix}

| Nome | Descrizione |
| --- | --- |
| getDirectrix() | La direttrice lungo la quale l'area spazzata si muove. |

 **Result:**



---


### setDirectrix{#setDirectrix}

| Nome | Descrizione |
| --- | --- |
| setDirectrix(value) | La direttrice lungo la quale l'area spazzata si muove. |

 **Result:**



---


### getStartPoint{#getStartPoint}

| Nome | Descrizione |
| --- | --- |
| getStartPoint() | Il punto iniziale della direttrice. |

 **Result:**



---


### setStartPoint{#setStartPoint}

| Nome | Descrizione |
| --- | --- |
| setStartPoint(value) | Il punto iniziale della direttrice. |

 **Result:**



---


### getEndPoint{#getEndPoint}

| Nome | Descrizione |
| --- | --- |
| getEndPoint() | Il punto finale della direttrice. |

 **Result:**



---


### setEndPoint{#setEndPoint}

| Nome | Descrizione |
| --- | --- |
| setEndPoint(value) | Il punto finale della direttrice. |

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



