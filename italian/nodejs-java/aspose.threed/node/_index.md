---
title: "Nodo"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/node/
---
## Node class

Rappresenta un elemento nel grafo della scena.  Un grafo della scena è un albero di oggetti Node. I servizi di gestione dell'albero sono contenuti in questa classe.  Nota che l'Aspose.3D SDK non verifica la validità del grafo della scena costruito. È responsabilità del chiamante assicurarsi che non vengano generati grafi ciclici nella gerarchia dei nodi.  Oltre alla gestione dell'albero, questa classe definisce tutte le proprietà necessarie per descrivere la posizione dell'oggetto nella scena. Queste informazioni includono le proprietà di base Traslazione, Rotazione e Scala e le opzioni più avanzate per pivot, limiti e attributi delle giunture IK come rigidità e smorzamento.  Quando viene creato per la prima volta, l'oggetto Node è "vuoto" (cioè è un oggetto senza alcuna rappresentazione grafica che contiene solo le informazioni di posizione). In questo stato, può essere usato per rappresentare i genitori nella struttura ad albero dei nodi ma non molto altro. L'uso normale di questo tipo di oggetti è aggiungere loro un'entità che specializzerà il nodo (vedi "Entity").  L'entità è un oggetto a sé stante ed è collegata al Node. Questo significa anche che la stessa entità può essere condivisa tra più nodi. Camera, Light, Mesh, ecc... sono tutte entità e derivano tutte dalla classe base Entity.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe Node. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name, entity) | Inizializza una nuova istanza della classe Node. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |
| entity | Entità | Entità predefinita. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(name) | Inizializza una nuova istanza della classe Node. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nome | Descrizione |
| --- | --- |
| getAssetInfo() | Informazioni sull'asset per nodo |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nome | Descrizione |
| --- | --- |
| setAssetInfo(value) | Informazioni sull'asset per nodo |

 **Result:**



---


### getVisible{#getVisible}

| Nome | Descrizione |
| --- | --- |
| getVisible() | Ottiene o imposta la visualizzazione del nodo |

 **Result:**



---


### setVisible{#setVisible}

| Nome | Descrizione |
| --- | --- |
| setVisible(value) | Ottiene o imposta la visualizzazione del nodo |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Nome | Descrizione |
| --- | --- |
| getChildNodes() | Ottiene i nodi figli. I nodi. |

 **Result:**



---


### getEntity{#getEntity}

| Nome | Descrizione |
| --- | --- |
| getEntity() | Ottiene o imposta la prima entità collegata a questo nodo; se impostata, cancellerà le altre entità. L'entità del nodo. |

 **Result:**



---


### setEntity{#setEntity}

| Nome | Descrizione |
| --- | --- |
| setEntity(value) | Ottiene o imposta la prima entità collegata a questo nodo; se impostata, cancellerà le altre entità. L'entità del nodo. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nome | Descrizione |
| --- | --- |
| getExcluded() | Ottiene o imposta se escludere questo nodo e tutti i nodi/entità figli durante l'esportazione. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nome | Descrizione |
| --- | --- |
| setExcluded(value) | Ottiene o imposta se escludere questo nodo e tutti i nodi/entità figli durante l'esportazione. |

 **Result:**



---


### getEntities{#getEntities}

| Nome | Descrizione |
| --- | --- |
| getEntities() | Ottiene tutte le entità del nodo. Le entità del nodo. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Nome | Descrizione |
| --- | --- |
| getMetaDatas() | Ottiene i metadati definiti in questo nodo. I metadati. |

 **Result:**



---


### getMaterials{#getMaterials}

| Nome | Descrizione |
| --- | --- |
| getMaterials() | Ottiene i materiali associati a questo nodo. I materiali. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nome | Descrizione |
| --- | --- |
| getMaterial() | Ottiene o imposta il primo materiale associato a questo nodo; se impostato, cancellerà gli altri materiali. Il materiale. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nome | Descrizione |
| --- | --- |
| setMaterial(value) | Ottiene o imposta il primo materiale associato a questo nodo; se impostato, cancellerà gli altri materiali. Il materiale. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nome | Descrizione |
| --- | --- |
| getParentNode() | Ottiene o imposta il nodo genitore. Il nodo genitore. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nome | Descrizione |
| --- | --- |
| setParentNode(value) | Ottiene o imposta il nodo genitore. Il nodo genitore. |

 **Result:**



---


### getTransform{#getTransform}

| Nome | Descrizione |
| --- | --- |
| getTransform() | Ottiene la trasformazione locale. La trasformazione. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Nome | Descrizione |
| --- | --- |
| getGlobalTransform() | Ottiene la trasformazione globale. La trasformazione globale. |

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


### createChildNode{#createChildNode}

| Nome | Descrizione |
| --- | --- |
| createChildNode() | Crea un nodo figlio |

 **Result:**
Nodo


---


### merge{#merge}

| Nome | Descrizione |
| --- | --- |
| merge(node) | Stacca tutto sotto il nodo e li collega al nodo corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nod | Nodo | null |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nome | Descrizione |
| --- | --- |
| createChildNode(nodeName) | Crea un nuovo nodo figlio con il nome del nodo fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | Stringa | Il nome del nuovo nodo figlio |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nome | Descrizione |
| --- | --- |
| createChildNode(entity) | Crea un nuovo nodo figlio con l'entità fornita allegata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entity | Entità | Entità predefinita allegata al nodo |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nome | Descrizione |
| --- | --- |
| createChildNode(nodeName, entity) | Crea un nuovo nodo figlio con il nome del nodo fornito |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | Stringa | Il nome del nuovo nodo figlio |
| entity | Entità | Entità predefinita allegata al nodo |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nome | Descrizione |
| --- | --- |
| createChildNode(nodeName, entity, material) | Crea un nuovo nodo figlio con il nome del nodo fornito e collega l'entità specificata e un materiale |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | Stringa | Il nome del nuovo nodo figlio |
| entity | Entità | Entità predefinita allegata al nodo |
| material | Materiale | Il materiale allegato al nodo |

 **Result:**
Nodo


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Nome | Descrizione |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Valuta la trasformazione globale, includere o meno la trasformazione geometrica. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| withGeometricTransform | boolean | Indica se la trasformazione geometrica è necessaria. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Nome | Descrizione |
| --- | --- |
| getChild(index) | Restituisce il nodo figlio all'indice specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| indice | Numero | Indice. |

 **Result:**
Nodo


---


### getChild{#getChild}

| Nome | Descrizione |
| --- | --- |
| getChild(nodeName) | Restituisce il nodo figlio con il nome specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | Stringa | Il nome del nodo figlio da trovare. |

 **Result:**
Nodo


---


### accept{#accept}

| Nome | Descrizione |
| --- | --- |
| accept(visitor) | Scorre tutti i nodi discendenti (incluso il nodo corrente) e chiama il visitatore con il nodo. Il visitatore può interrompere l'attraversamento restituendo false |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| visitor | NodeVisitor | Callback del visitatore per visitare il nodo |

 **Result:**
boolean


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Restituisce la rappresentazione stringa di questo nodo. |

 **Result:**
Stringa


---


### getBoundingBox{#getBoundingBox}

| Nome | Descrizione |
| --- | --- |
| getBoundingBox() | Calcola il riquadro di delimitazione del nodo |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Nome | Descrizione |
| --- | --- |
| addEntity(entity) | Aggiunge un'entità al nodo. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| entity | Entità | L'entità da allegare al nodo |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Nome | Descrizione |
| --- | --- |
| addChildNode(node) | Aggiunge un nodo figlio a questo nodo |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| node | Nodo | Il nodo figlio da allegare |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Nome | Descrizione |
| --- | --- |
| selectSingleObject(path) | Seleziona un singolo oggetto sotto il nodo corrente usando una sintassi di query simile a XPath. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| pat | Stringa | null |

 **Result:**
Oggetto


---


### selectObjects{#selectObjects}

| Nome | Descrizione |
| --- | --- |
| selectObjects(path) | Seleziona più oggetti sotto il nodo corrente usando una sintassi di query simile a XPath. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| pat | Stringa | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



