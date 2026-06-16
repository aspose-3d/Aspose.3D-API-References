---
title: "Frustum"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/frustum/
---
## Frustum class

La classe base di Camera e Light  @hideconstructor


## Metodi

### getRotationMode{#getRotationMode}

| Nome | Descrizione |
| --- | --- |
| getRotationMode() | Ottiene o imposta la modalità di orientamento del frustum. Questa proprietà funziona solo quando il Target è nullo. Se il valore è RotationMode.FIXED_TARGET, la direzione è sempre calcolata dalla proprietà LookAt. Altrimenti LookAt è sempre calcolata dalla Direction. Il valore della proprietà è la costante intera RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Nome | Descrizione |
| --- | --- |
| setRotationMode(value) | Ottiene o imposta la modalità di orientamento del frustum. Questa proprietà funziona solo quando il Target è nullo. Se il valore è RotationMode.FIXED_TARGET, la direzione è sempre calcolata dalla proprietà LookAt. Altrimenti LookAt è sempre calcolata dalla Direction. Il valore della proprietà è la costante intera RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Nome | Descrizione |
| --- | --- |
| getNearPlane() | Ottiene o imposta la distanza del piano vicino del frustum. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Nome | Descrizione |
| --- | --- |
| setNearPlane(value) | Ottiene o imposta la distanza del piano vicino del frustum. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Nome | Descrizione |
| --- | --- |
| getFarPlane() | Ottiene o imposta la distanza del piano lontano del frustum. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Nome | Descrizione |
| --- | --- |
| setFarPlane(value) | Ottiene o imposta la distanza del piano lontano del frustum. |

 **Result:**



---


### getAspect{#getAspect}

| Nome | Descrizione |
| --- | --- |
| getAspect() | Ottiene o imposta il rapporto d'aspetto del frustum |

 **Result:**



---


### setAspect{#setAspect}

| Nome | Descrizione |
| --- | --- |
| setAspect(value) | Ottiene o imposta il rapporto d'aspetto del frustum |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Nome | Descrizione |
| --- | --- |
| getOrthoHeight() | Ottiene o imposta l'altezza quando il frustum è in proiezione ortografica. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Nome | Descrizione |
| --- | --- |
| setOrthoHeight(value) | Ottiene o imposta l'altezza quando il frustum è in proiezione ortografica. |

 **Result:**



---


### getUp{#getUp}

| Nome | Descrizione |
| --- | --- |
| getUp() | Ottiene o imposta la direzione verso l'alto della fotocamera |

 **Result:**



---


### setUp{#setUp}

| Nome | Descrizione |
| --- | --- |
| setUp(value) | Ottiene o imposta la direzione verso l'alto della fotocamera |

 **Result:**



---


### getLookAt{#getLookAt}

| Nome | Descrizione |
| --- | --- |
| getLookAt() | Ottiene o imposta la posizione di interesse verso cui la fotocamera è rivolta. |

 **Result:**



---


### setLookAt{#setLookAt}

| Nome | Descrizione |
| --- | --- |
| setLookAt(value) | Ottiene o imposta la posizione di interesse verso cui la fotocamera è rivolta. |

 **Result:**



---


### getDirection{#getDirection}

| Nome | Descrizione |
| --- | --- |
| getDirection() | Ottiene o imposta la direzione verso cui la fotocamera è rivolta. Le modifiche a questa proprietà influenzeranno anche LookAt e Target. |

 **Result:**



---


### setDirection{#setDirection}

| Nome | Descrizione |
| --- | --- |
| setDirection(value) | Ottiene o imposta la direzione verso cui la fotocamera è rivolta. Le modifiche a questa proprietà influenzeranno anche LookAt e Target. |

 **Result:**



---


### getTarget{#getTarget}

| Nome | Descrizione |
| --- | --- |
| getTarget() | Ottiene o imposta il bersaglio verso cui la fotocamera è rivolta. Se l'utente supporta questa proprietà, dovrebbe essere impostata prima della proprietà LookAt. |

 **Result:**



---


### setTarget{#setTarget}

| Nome | Descrizione |
| --- | --- |
| setTarget(value) | Ottiene o imposta il bersaglio verso cui la fotocamera è rivolta. Se l'utente supporta questa proprietà, dovrebbe essere impostata prima della proprietà LookAt. |

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



