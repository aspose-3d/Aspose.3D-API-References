---
title: "Light"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/light/
---
## Light class

La luce illumina la scena.  La formula per calcolare l'attenuazione totale della luce è:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe Light. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe Light. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(name, type) | Inizializza una nuova istanza della classe Light. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Nome | Descrizione |
| --- | --- |
| getColor() | Ottiene o imposta il colore della luce |

 **Result:**



---


### setColor{#setColor}

| Nome | Descrizione |
| --- | --- |
| setColor(value) | Ottiene o imposta il colore della luce |

 **Result:**



---


### getLightType{#getLightType}

| Nome | Descrizione |
| --- | --- |
| getLightType() | Ottiene o imposta il tipo della luce. Il valore della proprietà è la costante intera LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Nome | Descrizione |
| --- | --- |
| setLightType(value) | Ottiene o imposta il tipo della luce. Il valore della proprietà è la costante intera LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Nome | Descrizione |
| --- | --- |
| getCastLight() | Ottiene o imposta se l'istanza corrente della luce può illuminare altri oggetti. |

 **Result:**



---


### setCastLight{#setCastLight}

| Nome | Descrizione |
| --- | --- |
| setCastLight(value) | Ottiene o imposta se l'istanza corrente della luce può illuminare altri oggetti. |

 **Result:**



---


### getIntensity{#getIntensity}

| Nome | Descrizione |
| --- | --- |
| getIntensity() | Ottiene o imposta l'intensità della luce, il valore predefinito è 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Nome | Descrizione |
| --- | --- |
| setIntensity(value) | Ottiene o imposta l'intensità della luce, il valore predefinito è 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Nome | Descrizione |
| --- | --- |
| getHotSpot() | Ottiene o imposta l'angolo del cono del punto caldo(in gradi). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Nome | Descrizione |
| --- | --- |
| setHotSpot(value) | Ottiene o imposta l'angolo del cono del punto caldo(in gradi). |

 **Result:**



---


### getFalloff{#getFalloff}

| Nome | Descrizione |
| --- | --- |
| getFalloff() | Ottiene o imposta l'angolo del cono di attenuazione (in gradi). |

 **Result:**



---


### setFalloff{#setFalloff}

| Nome | Descrizione |
| --- | --- |
| setFalloff(value) | Ottiene o imposta l'angolo del cono di attenuazione (in gradi). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Nome | Descrizione |
| --- | --- |
| getConstantAttenuation() | Ottiene o imposta l'attenuazione costante per calcolare l'attenuazione totale della luce |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Nome | Descrizione |
| --- | --- |
| setConstantAttenuation(value) | Ottiene o imposta l'attenuazione costante per calcolare l'attenuazione totale della luce |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Nome | Descrizione |
| --- | --- |
| getLinearAttenuation() | Ottiene o imposta l'attenuazione lineare per calcolare l'attenuazione totale della luce |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Nome | Descrizione |
| --- | --- |
| setLinearAttenuation(value) | Ottiene o imposta l'attenuazione lineare per calcolare l'attenuazione totale della luce |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Nome | Descrizione |
| --- | --- |
| getQuadraticAttenuation() | Ottiene o imposta l'attenuazione quadratica per calcolare l'attenuazione totale della luce |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Nome | Descrizione |
| --- | --- |
| setQuadraticAttenuation(value) | Ottiene o imposta l'attenuazione quadratica per calcolare l'attenuazione totale della luce |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nome | Descrizione |
| --- | --- |
| getCastShadows() | Ottiene o imposta se la luce può proiettare ombre su altri oggetti. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nome | Descrizione |
| --- | --- |
| setCastShadows(value) | Ottiene o imposta se la luce può proiettare ombre su altri oggetti. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Nome | Descrizione |
| --- | --- |
| getShadowColor() | Ottiene o imposta il colore dell'ombra. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Nome | Descrizione |
| --- | --- |
| setShadowColor(value) | Ottiene o imposta il colore dell'ombra. |

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



