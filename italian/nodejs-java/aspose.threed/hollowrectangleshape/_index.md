---
title: "HollowRectangleShape"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/hollowrectangleshape/
---
## HollowRectangleShape class

Forma rettangolare cava compatibile IFC con angoli arrotondati interni/esterni.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getWallThickness{#getWallThickness}

| Nome | Descrizione |
| --- | --- |
| getWallThickness() | Lo spessore tra il contorno del rettangolo e il foro interno |

 **Result:**



---


### setWallThickness{#setWallThickness}

| Nome | Descrizione |
| --- | --- |
| setWallThickness(value) | Lo spessore tra il contorno del rettangolo e il foro interno |

 **Result:**



---


### getInnerFilletRadius{#getInnerFilletRadius}

| Nome | Descrizione |
| --- | --- |
| getInnerFilletRadius() | Il raggio di smussatura interno del rettangolo interno. |

 **Result:**



---


### setInnerFilletRadius{#setInnerFilletRadius}

| Nome | Descrizione |
| --- | --- |
| setInnerFilletRadius(value) | Il raggio di smussatura interno del rettangolo interno. |

 **Result:**



---


### getRoundingRadius{#getRoundingRadius}

| Nome | Descrizione |
| --- | --- |
| getRoundingRadius() | Ottiene o imposta il raggio degli archi circolari di tutti e quattro gli angoli, misurato in gradi. Il valore predefinito è 0.0 |

 **Result:**



---


### setRoundingRadius{#setRoundingRadius}

| Nome | Descrizione |
| --- | --- |
| setRoundingRadius(value) | Ottiene o imposta il raggio degli archi circolari di tutti e quattro gli angoli, misurato in gradi. Il valore predefinito è 0.0 |

 **Result:**



---


### getXDim{#getXDim}

| Nome | Descrizione |
| --- | --- |
| getXDim() | Ottiene o imposta l'estensione del rettangolo nella direzione dell'asse x. Il valore predefinito è 2.0 |

 **Result:**



---


### setXDim{#setXDim}

| Nome | Descrizione |
| --- | --- |
| setXDim(value) | Ottiene o imposta l'estensione del rettangolo nella direzione dell'asse x. Il valore predefinito è 2.0 |

 **Result:**



---


### getYDim{#getYDim}

| Nome | Descrizione |
| --- | --- |
| getYDim() | Ottiene o imposta l'estensione del rettangolo nella direzione dell'asse y. Il valore predefinito è 2.0 |

 **Result:**



---


### setYDim{#setYDim}

| Nome | Descrizione |
| --- | --- |
| setYDim(value) | Ottiene o imposta l'estensione del rettangolo nella direzione dell'asse y. Il valore predefinito è 2.0 |

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



