---
title: "RevolvedAreaSolid"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Questa classe rappresenta un modello solido ruotando una sezione trasversale fornita da un profilo attorno a un asse.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Nome | Descrizione |
| --- | --- |
| getAngleStart() | Ottiene o imposta l'angolo iniziale della procedura di rotazione, misurato in radianti, valore predefinito è 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Nome | Descrizione |
| --- | --- |
| setAngleStart(value) | Ottiene o imposta l'angolo iniziale della procedura di rotazione, misurato in radianti, valore predefinito è 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Nome | Descrizione |
| --- | --- |
| getAngleEnd() | Ottiene o imposta l'angolo finale della procedura di rotazione, misurato in radianti, valore predefinito è π. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Nome | Descrizione |
| --- | --- |
| setAngleEnd(value) | Ottiene o imposta l'angolo finale della procedura di rotazione, misurato in radianti, valore predefinito è π. |

 **Result:**



---


### getAxis{#getAxis}

| Nome | Descrizione |
| --- | --- |
| getAxis() | Ottiene o imposta la direzione dell'asse, valore predefinito è (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Nome | Descrizione |
| --- | --- |
| setAxis(value) | Ottiene o imposta la direzione dell'asse, valore predefinito è (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Nome | Descrizione |
| --- | --- |
| getOrigin() | Ottiene o imposta il punto di origine della rotazione, valore predefinito è (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Nome | Descrizione |
| --- | --- |
| setOrigin(value) | Ottiene o imposta il punto di origine della rotazione, valore predefinito è (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Nome | Descrizione |
| --- | --- |
| getShape() | Ottiene o imposta il profilo di base usato per la rivoluzione. |

 **Result:**



---


### setShape{#setShape}

| Nome | Descrizione |
| --- | --- |
| setShape(value) | Ottiene o imposta il profilo di base usato per la rivoluzione. |

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
| toMesh() | Converti il RevolvedAreaSolid in una mesh. |

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



