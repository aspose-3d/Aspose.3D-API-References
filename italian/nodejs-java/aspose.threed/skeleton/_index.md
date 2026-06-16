---
title: "Scheletro"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

Lo Skeleton è principalmente usato dal software CAD per aiutare il progettista a manipolare la trasformazione della struttura scheletrica, è solitamente inutile al di fuori dei software CAD. Per far sì che la gerarchia dello scheletro agisca come un unico oggetto nel software CAD, è necessario contrassegnare il nodo Skeleton superiore come radice impostando Type su SkeletonType.SKELETON e tutti i figli su SkeletonType.BONE.


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
| name | Stringa | Nome. |

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



