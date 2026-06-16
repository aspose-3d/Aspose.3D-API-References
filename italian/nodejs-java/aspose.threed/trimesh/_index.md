---
title: "TriMesh"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Un TriMesh contiene dati grezzi che possono essere usati direttamente dalla GPU.  Questa classe è un'utilità per aiutare a costruire una mesh che contiene solo dati per vertice.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(name, declaration) | Inizializza un'istanza di TriMesh |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Il nome di questo TriMesh |
| dichiarazione | VertexDeclaration | La dichiarazione del vertice |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Nome | Descrizione |
| --- | --- |
| getVertexDeclaration() | Il layout del vertice del TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Nome | Descrizione |
| --- | --- |
| getVerticesCount() | Il numero di vertici in questo TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Nome | Descrizione |
| --- | --- |
| getIndicesCount() | Il conteggio degli indici in questo TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Nome | Descrizione |
| --- | --- |
| getUnmergedVerticesCount() | Il conteggio dei vertici non uniti passati da beginVertex() e endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Nome | Descrizione |
| --- | --- |
| getCapacity() | La capacità dei vertici pre-allocati. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Nome | Descrizione |
| --- | --- |
| getVerticesSizeInBytes() | La dimensione totale di tutti i vertici in byte |

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


### fromMesh{#fromMesh}

| Nome | Descrizione |
| --- | --- |
| fromMesh(declaration, mesh) | Crea un TriMesh dall'oggetto mesh fornito con il layout dei vertici specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Nome | Descrizione |
| --- | --- |
| copyFrom(input, vd) | Copia il TriMesh dall'input con un nuovo layout dei vertici |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| input | TriMesh | Il TriMesh di input per la copia |
| vd | VertexDeclaration | La nuova dichiarazione dei vertici del TriMesh di output |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Nome | Descrizione |
| --- | --- |
| fromMesh(mesh, useFloat) | Crea un TriMesh dall'oggetto mesh fornito, la dichiarazione dei vertici è basata sulla struttura del mesh di input. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | Usa il tipo float invece del tipo double per ogni componente dell'elemento del vertice. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Nome | Descrizione |
| --- | --- |
| beginVertex() | Inizia ad aggiungere un vertice |

 **Result:**
Vertice


---


### endVertex{#endVertex}

| Nome | Descrizione |
| --- | --- |
| endVertex() | Fine aggiunta del vertice |

 **Result:**
Vertice


---


### verticesToArray{#verticesToArray}

| Nome | Descrizione |
| --- | --- |
| verticesToArray() | Converti i dati dei vertici in array di byte |

 **Result:**
byte[]


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() |  |

 **Result:**
Stringa


---


### fromRawData{#fromRawData}

| Nome | Descrizione |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Crea TriMesh dai dati grezzi. Il TriMesh restituito non copierà l'array di byte di input per motivi di prestazioni; le modifiche esterne all'array saranno riflesse in questa istanza. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| vd | VertexDeclaration | Dichiarazione del vertice, deve contenere almeno un campo. |
| vertices | byte[] | I dati del vertice di input, la lunghezza minima dei vertici deve essere maggiore o uguale alla dimensione della dichiarazione del vertice. |
| indici | Number[] | Gli indici dei triangoli |
| generateVertexMapping | boolean | Genera |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Nome | Descrizione |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Carica i vertici da byte, la lunghezza dei byte deve essere un multiplo intero della dimensione del vertice. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Nome | Descrizione |
| --- | --- |
| readVector4(idx, field) | Leggi il campo vector4 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con tipo di dato Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Nome | Descrizione |
| --- | --- |
| readFVector4(idx, field) | Leggi il campo vector4 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con tipo di dato Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Nome | Descrizione |
| --- | --- |
| readVector3(idx, field) | Leggi il campo vector3 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con un tipo di dati Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Nome | Descrizione |
| --- | --- |
| readFVector3(idx, field) | Leggi il campo vector3 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con un tipo di dati Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Nome | Descrizione |
| --- | --- |
| readVector2(idx, field) | Leggi il campo vector2 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con un tipo di dati Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Nome | Descrizione |
| --- | --- |
| readFVector2(idx, field) | Leggi il campo vector2 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con un tipo di dati Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Nome | Descrizione |
| --- | --- |
| readDouble(idx, field) | Leggi il campo double |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con un tipo di dati compatibile float/double |

 **Result:**
Numero


---


### readFloat{#readFloat}

| Nome | Descrizione |
| --- | --- |
| readFloat(idx, field) | Leggi il campo float |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| idx | Numero | L'indice del vertice da leggere |
| field | VertexField | Il campo con un tipo di dati compatibile float/double |

 **Result:**
Numero


---


### getBoundingBox{#getBoundingBox}

| Nome | Descrizione |
| --- | --- |
| getBoundingBox() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |

 **Result:**
Numero


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



