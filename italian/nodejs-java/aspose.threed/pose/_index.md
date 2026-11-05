---
title: "Pose"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/pose/
---
## Pose class

La posa è usata per memorizzare la matrice di trasformazione quando la geometria è skinned.  La posa è un insieme di BonePose, ciascun BonePose salva le informazioni concrete di trasformazione del nodo osso.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Inizializza una nuova istanza della classe Pose. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Inizializza una nuova istanza della classe Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| Nome | Descrizione |
| --- | --- |
| getPoseType() | Ottiene o imposta il tipo della posa. Il valore della proprietà è la costante intera PoseType. Il tipo della posa. |

 **Result:**



---


### setPoseType{#setPoseType}

| Nome | Descrizione |
| --- | --- |
| setPoseType(value) | Ottiene o imposta il tipo della posa. Il valore della proprietà è la costante intera PoseType. Il tipo della posa. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Nome | Descrizione |
| --- | --- |
| getBonePoses() | Ottiene tutti i BonePose. I nodi. |

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


### addBonePose{#addBonePose}

| Nome | Descrizione |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Salva la matrice di trasformazione della posa per il nodo osso fornito. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodo | Nodo | Nodo osso. |
| matrice | Matrix4 | Matrice di trasformazione. |
| localMatrix | boolean | Se impostato a |

 **Result:**



---


### addBonePose{#addBonePose}

| Nome | Descrizione |
| --- | --- |
| addBonePose(node, matrix) | Salva la matrice di trasformazione della posa per il nodo osso fornito. La matrice di trasformazione globale è implicita. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodo | Nodo | Nodo osso. |
| matrice | Matrix4 | Matrice di trasformazione. |

 **Result:**



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



