---
title: "PointCloud"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/pointcloud/
---
## PointCloud class

Il cloud di punti non contiene informazioni di topologia ma solo i punti di controllo e gli elementi dei vertici.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name) | Costruttore di PointCloud |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Il nome di questa entità |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload() | Costruttore di PointCloud |

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
| getCastShadows() | Ottiene o imposta se questa geometria può proiettare ombra |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nome | Descrizione |
| --- | --- |
| setCastShadows(value) | Ottiene o imposta se questa geometria può proiettare ombra |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nome | Descrizione |
| --- | --- |
| getReceiveShadows() | Ottiene o imposta se questa geometria può ricevere ombra. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nome | Descrizione |
| --- | --- |
| setReceiveShadows(value) | Ottiene o imposta se questa geometria può ricevere ombra. |

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


### getEntityRendererKey{#getEntityRendererKey}

| Nome | Descrizione |
| --- | --- |
| getEntityRendererKey() | Ottiene la chiave del renderer dell'entità registrata nel renderer |

 **Result:**
EntityRendererKey


---


### fromGeometry{#fromGeometry}

| Nome | Descrizione |
| --- | --- |
| fromGeometry(g) | Crea una nuova istanza di PointCloud da un oggetto geometria |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Geometry | null |

 **Result:**
PointCloud


---


### fromGeometry{#fromGeometry}

| Nome | Descrizione |
| --- | --- |
| fromGeometry(g, density) | Crea una nuova istanza di point cloud da un oggetto geometria. La densità è il numero di punti per triangolo unitario (il triangolo unitario è il triangolo con la massima area superficiale della mesh) |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| g | Geometry | Istanza di Mesh o altra geometria |
| density | Numero | Numero di punti per triangolo unitario |

 **Result:**
PointCloud


---


### getElement{#getElement}

| Nome | Descrizione |
| --- | --- |
| getElement(type) | Ottiene un elemento vertice con il tipo specificato |

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
| createElement(type) | Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria. Se il tipo è VertexElementType.UV, verrà creato un VertexElementUV con il tipo di mappatura texture impostato a TextureMapping.DIFFUSE. |

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
| addElement(element) | Aggiunge un elemento vertice esistente alla geometria corrente |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| element | VertexElement | L'elemento vertice da aggiungere |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Nome | Descrizione |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria. Se il tipo è VertexElementType.UV, verrà creato un VertexElementUV con il tipo di mappatura texture impostato a TextureMapping.DIFFUSE. |

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
| createElementUV(uvMapping) | Crea un VertexElementUV con il tipo di mappatura della texture specificato. |

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
| createElementUV(uvMapping, mappingMode, referenceMode) | Crea un VertexElementUV con il tipo di mappatura della texture specificato. |

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



