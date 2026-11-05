---
title: "Skeleton"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

Lo scheletro è principalmente usato dal software CAD per aiutare il designer a manipolare la trasformazione della struttura scheletrica, è solitamente inutile al di fuori dei software CAD.  Per far sì che la gerarchia dello scheletro agisca come un unico oggetto nel software CAD, è necessario contrassegnare il nodo Skeleton superiore come radice impostando Type su SkeletonType.SKELETON,  e tutti i figli su SkeletonType.BONE


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe Skeleton. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe Skeleton. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome. |

 **Result:**



---


### getSize{#getSize}

| Nome | Descrizione |
| --- | --- |
| getSize() | Ottiene o imposta la dimensione del nodo dell'arto utilizzata nel software CAD per rappresentare la dimensione dell'osso. |

 **Result:**



---


### setSize{#setSize}

| Nome | Descrizione |
| --- | --- |
| setSize(value) | Ottiene o imposta la dimensione del nodo dell'arto utilizzata nel software CAD per rappresentare la dimensione dell'osso. |

 **Result:**



---


### getType{#getType}

| Nome | Descrizione |
| --- | --- |
| getType() | Ottiene o imposta il tipo dello scheletro. Il valore della proprietà è la costante intera SkeletonType. Il tipo dello scheletro. |

 **Result:**



---


### setType{#setType}

| Nome | Descrizione |
| --- | --- |
| setType(value) | Ottiene o imposta il tipo dello scheletro. Il valore della proprietà è la costante intera SkeletonType. Il tipo dello scheletro. |

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


### getBoundingBox{#getBoundingBox}

| Nome | Descrizione |
| --- | --- |
| getBoundingBox() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |

 **Result:**



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



