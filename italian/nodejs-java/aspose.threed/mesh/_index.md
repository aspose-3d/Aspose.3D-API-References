---
title: "Mesh"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/mesh/
---
## Mesh class

Una mesh è composta da molti poligoni a n lati.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe Mesh. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe Mesh. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |

 **Result:**



---


### getEdges{#getEdges}

| Nome | Descrizione |
| --- | --- |
| getEdges() | Ottiene i bordi del Mesh. Il bordo è opzionale nel mesh, quindi può essere vuoto. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Nome | Descrizione |
| --- | --- |
| getPolygonCount() | Ottiene il conteggio dei poligoni. Il conteggio dei poligoni. |

 **Result:**



---


### getPolygons{#getPolygons}

| Nome | Descrizione |
| --- | --- |
| getPolygons() | Ottiene la definizione dei poligoni del mesh |

 **Result:**



---


### getVisible{#getVisible}

| Nome | Descrizione |
| --- | --- |
| getVisible() | Ottiene o imposta se la geometria è visibile |

 **Result:**



---


### setVisible{#setVisible}

| Nome | Descrizione |
| --- | --- |
| setVisible(value) | Ottiene o imposta se la geometria è visibile |

 **Result:**



---


### getDeformers{#getDeformers}

| Nome | Descrizione |
| --- | --- |
| getDeformers() | Ottiene tutti i deformatori associati a questa geometria. I deformatori. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nome | Descrizione |
| --- | --- |
| getControlPoints() | Ottiene tutti i punti di controllo |

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


### getVertexElements{#getVertexElements}

| Nome | Descrizione |
| --- | --- |
| getVertexElements() | Ottiene tutti gli elementi dei vertici |

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


### getPolygonSize{#getPolygonSize}

| Nome | Descrizione |
| --- | --- |
| getPolygonSize(index) | Restituisce il numero di vertici del poligono specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| indice | Numero | Indice. |

 **Result:**
Numero


---


### createPolygon{#createPolygon}

| Nome | Descrizione |
| --- | --- |
| createPolygon(indices, offset, length) | Crea un nuovo poligono con tutti i vertici definiti negli indici. Per creare il poligono vertice per vertice, si prega di utilizzare PolygonBuilder. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| indici | Number[] | Array degli indici del poligono, ogni indice punta a un punto di controllo che forma il poligono. |
| offset | Numero | L'offset del primo indice del poligono |
| lunghezza | Numero | La lunghezza degli indici |

 **Result:**
Numero


---


### createPolygon{#createPolygon}

| Nome | Descrizione |
| --- | --- |
| createPolygon(indices) | Crea un nuovo poligono con tutti i vertici definiti negli indici. Per creare il poligono vertice per vertice, si prega di utilizzare PolygonBuilder. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| indici | Number[] | Array degli indici del poligono, ogni indice punta a un punto di controllo che forma il poligono. |

 **Result:**
Numero


---


### createPolygon{#createPolygon}

| Nome | Descrizione |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | Crea un poligono con 4 vertici (quad) |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| v1 | Numero | Indice del primo vertice |
| v2 | Numero | Indice del secondo vertice |
| v3 | Numero | Indice del terzo vertice |
| v4 | Numero | Indice del quarto vertice |

 **Result:**
Numero


---


### createPolygon{#createPolygon}

| Nome | Descrizione |
| --- | --- |
| createPolygon(v1, v2, v3) | Crea un poligono con 3 vertici(triangolo) |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| v1 | Numero | Indice del primo vertice |
| v2 | Numero | Indice del secondo vertice |
| v3 | Numero | Indice del terzo vertice |

 **Result:**
Numero


---


### toMesh{#toMesh}

| Nome | Descrizione |
| --- | --- |
| toMesh() | Ottiene l'istanza Mesh dall'entità corrente. |

 **Result:**
Mesh


---


### getElement{#getElement}

| Nome | Descrizione |
| --- | --- |
| getElement(type) | Ottiene un elemento di vertice con il tipo specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Nome | Descrizione |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Ottiene un'istanza VertexElementUV con il tipo di mappatura texture fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Nome | Descrizione |
| --- | --- |
| createElement(type) | Crea un elemento di vertice con il tipo specificato e lo aggiunge alla geometria. Se il tipo è VertexElementType.UV, verrà creato un VertexElementUV con il tipo di mappatura texture impostato su TextureMapping.DIFFUSE. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Nome | Descrizione |
| --- | --- |
| addElement(element) | Aggiunge un elemento di vertice esistente alla geometria corrente |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| element | VertexElement | L'elemento di vertice da aggiungere |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Nome | Descrizione |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Crea un elemento di vertice con il tipo specificato e lo aggiunge alla geometria. Se il tipo è VertexElementType.UV, verrà creato un VertexElementUV con il tipo di mappatura texture impostato su TextureMapping.DIFFUSE. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Nome | Descrizione |
| --- | --- |
| createElementUV(uvMapping) | Crea un VertexElementUV con il tipo di mappatura della texture fornito. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Nome | Descrizione |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Crea un VertexElementUV con il tipo di mappatura della texture fornito. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Nome | Descrizione |
| --- | --- |
| getBoundingBox() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |

 **Result:**
VertexElementUV


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


### iterator{#iterator}

| Nome | Descrizione |
| --- | --- |
| iterator() | Riservato per uso interno. |

 **Result:**
Property


---



