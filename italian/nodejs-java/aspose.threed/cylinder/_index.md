---
title: "Cylinder"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Cilindro parametrizzato. Può anche essere usato per rappresentare il cono quando uno dei valori radiusTop/radiusBottom è zero.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(radius, height) | Inizializza una nuova istanza della classe Cylinder. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| raggio | Numero | Raggio del cappuccio superiore e inferiore. |
| height | Numero | Altezza. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Inizializza una nuova istanza della classe Cylinder. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| radiusTop | Numero | Raggio superiore. |
| radiusBottom | Numero | Raggio inferiore. |
| height | Numero | Altezza. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nome | Descrizione |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Inizializza una nuova istanza della classe Cylinder. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| radiusTop | Numero | Raggio del cappuccio superiore del cilindro. |
| radiusBottom | Numero | Raggio del cappuccio inferiore del cilindro. |
| height | Numero | Altezza del cilindro. |
| radialSegments | Numero | Segmenti radiali di entrambi i cerchi superiore e inferiore.. |
| heightSegments | Numero | Segmenti di altezza. |
| openEnded | boolean | Se impostato a |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nome | Descrizione |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Inizializza una nuova istanza della classe Cylinder. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Il nome di questo oggetto |
| radiusTop | Numero | Raggio del cappuccio superiore del cilindro. |
| radiusBottom | Numero | Raggio del cappuccio inferiore del cilindro. |
| height | Numero | Altezza del cilindro. |
| radialSegments | Numero | Segmenti radiali di entrambi i cerchi superiore e inferiore.. |
| heightSegments | Numero | Segmenti di altezza. |
| openEnded | boolean | Se impostato a |
| thetaStart | Numero | Inizio theta. |
| thetaLength | Numero | Lunghezza theta. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Nome | Descrizione |
| --- | --- |
| getOffsetBottom() | Ottiene o imposta l'offset di trasformazione dei vertici del lato inferiore. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Nome | Descrizione |
| --- | --- |
| setOffsetBottom(value) | Ottiene o imposta l'offset di trasformazione dei vertici del lato inferiore. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Nome | Descrizione |
| --- | --- |
| getOffsetTop() | Ottiene o imposta l'offset di trasformazione dei vertici del lato superiore. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Nome | Descrizione |
| --- | --- |
| setOffsetTop(value) | Ottiene o imposta l'offset di trasformazione dei vertici del lato superiore. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Nome | Descrizione |
| --- | --- |
| getGenerateFanCylinder() | Ottiene o imposta se generare il cilindro a ventaglio quando ThetaLength è inferiore a 2PI, altrimenti il modello non verrà tagliato. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Nome | Descrizione |
| --- | --- |
| setGenerateFanCylinder(value) | Ottiene o imposta se generare il cilindro a ventaglio quando ThetaLength è inferiore a 2PI, altrimenti il modello non verrà tagliato. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Nome | Descrizione |
| --- | --- |
| getShearBottom() | Ottiene o imposta la trasformazione di taglio del lato inferiore; il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0). |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Nome | Descrizione |
| --- | --- |
| setShearBottom(value) | Ottiene o imposta la trasformazione di taglio del lato inferiore; il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0). |

 **Result:**



---


### getShearTop{#getShearTop}

| Nome | Descrizione |
| --- | --- |
| getShearTop() | Ottiene o imposta la trasformazione di taglio del lato superiore; il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0). |

 **Result:**



---


### setShearTop{#setShearTop}

| Nome | Descrizione |
| --- | --- |
| setShearTop(value) | Ottiene o imposta la trasformazione di taglio del lato superiore; il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0). |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Nome | Descrizione |
| --- | --- |
| getRadiusTop() | Ottiene o imposta il raggio della copertura superiore del cilindro. Il raggio della copertura superiore. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Nome | Descrizione |
| --- | --- |
| setRadiusTop(value) | Ottiene o imposta il raggio della copertura superiore del cilindro. Il raggio della copertura superiore. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Nome | Descrizione |
| --- | --- |
| getRadiusBottom() | Ottiene o imposta il raggio della copertura inferiore del cilindro. Il raggio della copertura inferiore. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Nome | Descrizione |
| --- | --- |
| setRadiusBottom(value) | Ottiene o imposta il raggio della copertura inferiore del cilindro. Il raggio della copertura inferiore. |

 **Result:**



---


### getHeight{#getHeight}

| Nome | Descrizione |
| --- | --- |
| getHeight() | Ottiene o imposta l'altezza del cilindro. L'altezza. |

 **Result:**



---


### setHeight{#setHeight}

| Nome | Descrizione |
| --- | --- |
| setHeight(value) | Ottiene o imposta l'altezza del cilindro. L'altezza. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Nome | Descrizione |
| --- | --- |
| getRadialSegments() | Ottiene o imposta i segmenti radiali. I segmenti radiali. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Nome | Descrizione |
| --- | --- |
| setRadialSegments(value) | Ottiene o imposta i segmenti radiali. I segmenti radiali. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Nome | Descrizione |
| --- | --- |
| getHeightSegments() | Ottiene o imposta i segmenti di altezza. I segmenti di altezza. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Nome | Descrizione |
| --- | --- |
| setHeightSegments(value) | Ottiene o imposta i segmenti di altezza. I segmenti di altezza. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Nome | Descrizione |
| --- | --- |
| getOpenEnded() | Ottiene o imposta un valore che indica se questo cilindro è aperto. Il valore predefinito è false. true se è aperto; altrimenti, le coperture superiore/inferiore esistono. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Nome | Descrizione |
| --- | --- |
| setOpenEnded(value) | Ottiene o imposta un valore che indica se questo cilindro è aperto. Il valore predefinito è false. true se è aperto; altrimenti, le coperture superiore/inferiore esistono. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Nome | Descrizione |
| --- | --- |
| getThetaStart() | Ottiene o imposta l'inizio theta. Il valore predefinito è 0. L'inizio theta. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Nome | Descrizione |
| --- | --- |
| setThetaStart(value) | Ottiene o imposta l'inizio theta. Il valore predefinito è 0. L'inizio theta. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Nome | Descrizione |
| --- | --- |
| getThetaLength() | Ottiene o imposta la lunghezza di theta. Il valore predefinito è 2π. La lunghezza di theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Nome | Descrizione |
| --- | --- |
| setThetaLength(value) | Ottiene o imposta la lunghezza di theta. Il valore predefinito è 2π. La lunghezza di theta. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nome | Descrizione |
| --- | --- |
| getCastShadows() | Ottiene o imposta se questa geometria può proiettare ombre |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nome | Descrizione |
| --- | --- |
| setCastShadows(value) | Ottiene o imposta se questa geometria può proiettare ombre |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nome | Descrizione |
| --- | --- |
| getReceiveShadows() | Ottiene o imposta se questa geometria può ricevere ombre. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nome | Descrizione |
| --- | --- |
| setReceiveShadows(value) | Ottiene o imposta se questa geometria può ricevere ombre. |

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



