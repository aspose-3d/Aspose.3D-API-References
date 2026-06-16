---
title: "Telecamera"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/camera/
---
## Camera class

La telecamera descrive il punto di vista dell'osservatore che guarda la scena.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe Camera. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(projectionType) | Inizializza una nuova istanza della classe Camera. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(name) | Inizializza una nuova istanza della classe Camera. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nome | Descrizione |
| --- | --- |
| constructor_overload3(name, projectionType) | Inizializza una nuova istanza della classe Camera. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Nome | Descrizione |
| --- | --- |
| getApertureMode() | Ottiene o imposta la modalità di apertura della fotocamera. Il valore della proprietà è la costante intera ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Nome | Descrizione |
| --- | --- |
| setApertureMode(value) | Ottiene o imposta la modalità di apertura della fotocamera. Il valore della proprietà è la costante intera ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Nome | Descrizione |
| --- | --- |
| getFieldOfView() | Ottiene o imposta il campo visivo della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è ApertureMode.HORIZONTAL o ApertureMode.VERTICAL. |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Nome | Descrizione |
| --- | --- |
| setFieldOfView(value) | Ottiene o imposta il campo visivo della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è ApertureMode.HORIZONTAL o ApertureMode.VERTICAL. |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Nome | Descrizione |
| --- | --- |
| getFieldOfViewX() | Ottiene o imposta il campo visivo orizzontale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Nome | Descrizione |
| --- | --- |
| setFieldOfViewX(value) | Ottiene o imposta il campo visivo orizzontale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Nome | Descrizione |
| --- | --- |
| getFieldOfViewY() | Ottiene o imposta il campo visivo verticale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Nome | Descrizione |
| --- | --- |
| setFieldOfViewY(value) | Ottiene o imposta il campo visivo verticale della fotocamera in gradi, questa proprietà è usata solo quando ApertureMode è ApertureMode.HORIZ_AND_VERT. |

 **Result:**



---


### getWidth{#getWidth}

| Nome | Descrizione |
| --- | --- |
| getWidth() | Ottiene o imposta la larghezza del piano di visualizzazione misurata in pollici. |

 **Result:**



---


### setWidth{#setWidth}

| Nome | Descrizione |
| --- | --- |
| setWidth(value) | Ottiene o imposta la larghezza del piano di visualizzazione misurata in pollici. |

 **Result:**



---


### getHeight{#getHeight}

| Nome | Descrizione |
| --- | --- |
| getHeight() | Ottiene o imposta l'altezza del piano di visualizzazione misurata in pollici. |

 **Result:**



---


### setHeight{#setHeight}

| Nome | Descrizione |
| --- | --- |
| setHeight(value) | Ottiene o imposta l'altezza del piano di visualizzazione misurata in pollici. |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Nome | Descrizione |
| --- | --- |
| getAspectRatio() | Ottiene o imposta il rapporto d'aspetto del piano di visualizzazione. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Nome | Descrizione |
| --- | --- |
| setAspectRatio(value) | Ottiene o imposta il rapporto d'aspetto del piano di visualizzazione. |

 **Result:**



---


### getMagnification{#getMagnification}

| Nome | Descrizione |
| --- | --- |
| getMagnification() | Ottiene o imposta l'ingrandimento usato nella fotocamera ortografica. |

 **Result:**



---


### setMagnification{#setMagnification}

| Nome | Descrizione |
| --- | --- |
| setMagnification(value) | Ottiene o imposta l'ingrandimento usato nella fotocamera ortografica. |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Nome | Descrizione |
| --- | --- |
| getProjectionType() | Ottiene o imposta il tipo di proiezione della fotocamera. Per impostazione predefinita viene utilizzata la proiezione prospettica. Il valore della proprietà è la costante intera ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Nome | Descrizione |
| --- | --- |
| setProjectionType(value) | Ottiene o imposta il tipo di proiezione della fotocamera. Per impostazione predefinita viene utilizzata la proiezione prospettica. Il valore della proprietà è la costante intera ProjectionType. |

 **Result:**



---


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


### moveForward{#moveForward}

| Nome | Descrizione |
| --- | --- |
| moveForward(distance) | Sposta la fotocamera in avanti verso la sua direzione o il suo bersaglio. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| distanza | Numero | Quanto tempo spostarsi in avanti |

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



