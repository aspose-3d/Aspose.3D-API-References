---
title: Node
second_title: Aspose.3D for Java API Reference
description: Rappresenta un elemento nel grafo della scena.
type: docs
weight: 110
url: /it/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Rappresenta un elemento nel grafo della scena. Un grafo della scena è un albero di oggetti Node. I servizi di gestione dell'albero sono contenuti in questa classe. Nota che l'Aspose.3D SDK non verifica la validità del grafo della scena costruito. È responsabilità del chiamante assicurarsi che non vengano generati grafi ciclici nella gerarchia dei nodi. Oltre alla gestione dell'albero, questa classe definisce tutte le proprietà necessarie a descrivere la posizione dell'oggetto nella scena. Queste informazioni includono le proprietà di base Traslazione, Rotazione e Scala e le opzioni più avanzate per pivot, limiti e attributi delle articolazioni IK come la rigidità e l'ammortizzazione. Quando viene creata per la prima volta, l'oggetto Node è "vuoto" (cioè è un oggetto senza alcuna rappresentazione grafica che contiene solo le informazioni di posizione). In questo stato, può essere usato per rappresentare i genitori nella struttura ad albero dei nodi ma non molto altro. L'uso normale di questo tipo di oggetti è aggiungerli a un'entità che specializzerà il nodo (vedi "Entity"). L'entità è un oggetto a sé stante ed è collegata al Node. Questo significa anche che la stessa entità può essere condivisa tra più nodi. Camera, Light, Mesh, ecc... sono tutte entità e derivano tutte dalla classe base Entity.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Node()](#Node--) | Inizializza una nuova istanza della classe [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Inizializza una nuova istanza della classe [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | Inizializza una nuova istanza della classe [Node](../../com.aspose.threed/node). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Scorre tutti i nodi discendenti (incluso il nodo corrente) e chiama il visitatore con il nodo. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Aggiungi un nodo figlio a questo nodo |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Aggiungi un'entità al nodo. |
| [createChildNode()](#createChildNode--) | Crea un nodo figlio |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Crea un nuovo nodo figlio con l'entità specificata allegata |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Crea un nuovo nodo figlio con il nome del nodo specificato |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Crea un nuovo nodo figlio con il nome del nodo specificato |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Crea un nuovo nodo figlio con il nome del nodo specificato e allega l'entità e un materiale specificati |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Valuta la trasformazione globale, includere o meno la trasformazione geometrica. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getAssetInfo()](#getAssetInfo--) | Informazioni sull'asset per nodo |
| [getBoundingBox()](#getBoundingBox--) | Calcola il bounding box del nodo |
| [getChild(int index)](#getChild-int-) | Ottiene il nodo figlio all'indice specificato. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Ottiene il nodo figlio con il nome specificato |
| [getChildNodes()](#getChildNodes--) | Ottiene i nodi figli. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Ottiene tutte le entità del nodo. |
| [getEntity()](#getEntity--) | Ottiene la prima entità allegata a questo nodo; se impostata, cancellerà le altre entità. |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questo nodo e tutti i nodi/entità figli durante l'esportazione. |
| [getGlobalTransform()](#getGlobalTransform--) | Ottiene la trasformazione globale. |
| [getMaterial()](#getMaterial--) | Ottiene il primo materiale associato a questo nodo; se impostato, cancellerà gli altri materiali |
| [getMaterials()](#getMaterials--) | Ottiene i materiali associati a questo nodo. |
| [getMetaDatas()](#getMetaDatas--) | Ottiene i metadati definiti in questo nodo. |
| [getName()](#getName--) | Ottiene il nome. |
| [getParentNode()](#getParentNode--) | Ottiene il nodo genitore. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getTransform()](#getTransform--) | Ottiene la trasformazione locale. |
| [getVisible()](#getVisible--) | Ottiene se mostrare il nodo |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Stacca tutto sotto il nodo e lo allega al nodo corrente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Seleziona più oggetti sotto il nodo corrente usando una sintassi di query simile a XPath. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Seleziona un singolo oggetto sotto il nodo corrente usando una sintassi di query simile a XPath. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Informazioni sull'asset per nodo |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Imposta la prima entità allegata a questo nodo; se impostata, cancellerà le altre entità. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questo nodo e tutti i nodi/entità figli durante l'esportazione. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Imposta il primo materiale associato a questo nodo; se impostato, cancellerà gli altri materiali |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il nodo genitore. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setVisible(boolean value)](#setVisible-boolean-) | Imposta per mostrare il nodo |
| [toString()](#toString--) | Ottiene la rappresentazione stringa di questo nodo. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Inizializza una nuova istanza della classe [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Inizializza una nuova istanza della classe [Node](../../com.aspose.threed/node).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |
| entity | [Entity](../../com.aspose.threed/entity) | Entità predefinita. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Inizializza una nuova istanza della classe [Node](../../com.aspose.threed/node).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Scorre tutti i nodi discendenti (incluso il nodo corrente) e chiama il visitatore con il nodo. Il visitatore può interrompere l'attraversamento restituendo false

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Callback del visitatore per visitare il nodo |

**Returns:**
boolean - true indica che il visitatore ha interrotto l'attraversamento. **Example:** Il codice seguente mostra come ottenere tutte le mesh da una scena

```
Scene scene = Scene.fromFile("input.fbx");
     List<Mesh> meshes = new ArrayList<Mesh>();
     scene.getRootNode().accept(new NodeVisitor() {
         @Override
         public boolean call(Node node) {
             if(node.Entity instanceof Mesh)
                 meshes.add(((Mesh)node).getEntity());
             //continue searching
             return true;
         }
     });
```
### addChildNode(Node node) {#addChildNode-com.aspose.threed.Node-}
```
public void addChildNode(Node node)
```


Aggiungi un nodo figlio a questo nodo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Il nodo figlio da allegare **Example:** Il codice seguente mostra come ottenere tutte le mesh da una scena |

```
Scene scene = Scene.fromFile("input.fbx");
     var newNode = new Node();
     //add a new node manually
     scene.getRootNode().addChildNode(newNode);
``` |

### addEntity(Entity entity) {#addEntity-com.aspose.threed.Entity-}
```
public void addEntity(Entity entity)
```


Aggiungi un'entità al nodo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità da allegare al nodo |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Crea un nodo figlio

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode();
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### createChildNode(Entity entity) {#createChildNode-com.aspose.threed.Entity-}
```
public Node createChildNode(Entity entity)
```


Crea un nuovo nodo figlio con l'entità specificata allegata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Entità predefinita allegata al nodo |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode(new Box());
     scene.save("output.fbx");
```
### createChildNode(String nodeName) {#createChildNode-java.lang.String-}
```
public Node createChildNode(String nodeName)
```


Crea un nuovo nodo figlio con il nome del nodo specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | java.lang.String | Il nome del nuovo nodo figlio |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### createChildNode(String nodeName, Entity entity) {#createChildNode-java.lang.String-com.aspose.threed.Entity-}
```
public Node createChildNode(String nodeName, Entity entity)
```


Crea un nuovo nodo figlio con il nome del nodo specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | java.lang.String | Il nome del nuovo nodo figlio |
| entity | [Entity](../../com.aspose.threed/entity) | Entità predefinita allegata al nodo |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Crea un nuovo nodo figlio con il nome del nodo specificato e allega l'entità e un materiale specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | java.lang.String | Il nome del nuovo nodo figlio |
| entity | [Entity](../../com.aspose.threed/entity) | Entità predefinita allegata al nodo |
| material | [Material](../../com.aspose.threed/material) | Il materiale allegato al nodo |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Valuta la trasformazione globale, includere o meno la trasformazione geometrica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| withGeometricTransform | boolean | Indica se la trasformazione geometrica è necessaria. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The global transform matrix. **Example:** The following code shows how to read the node's global transform matrix.

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     Matrix4 mat = boxNode.evaluateGlobalTransform(true);
     System.out.printf("The box's global transform matrix is %s", mat);
```
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trova la proprietà. Può essere una proprietà dinamica (creata con CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata per nome).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | java.lang.String | Nome della proprietà. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Informazioni sull'asset per nodo

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Calcola il bounding box del nodo

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Ottiene il nodo figlio all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice. |

**Returns:**
[Node](../../com.aspose.threed/node) - The child. **Example:** The following code shows how to get a child node at specified index.

```
Scene scene = Scene.fromFile("input.fbx");
     var node = scene.getRootNode().getChild(0);
     System.out.printf("The first node of the file is %s", node.getName());
```
### getChild(String nodeName) {#getChild-java.lang.String-}
```
public Node getChild(String nodeName)
```


Ottiene il nodo figlio con il nome specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | java.lang.String | Il nome del figlio da trovare. |

**Returns:**
[Node](../../com.aspose.threed/node) - The child. **Example:** The following code shows how to get a child node with specified name

```
Scene scene = Scene.fromFile("input.fbx");
     var node = scene.getRootNode().getChild("box");
     System.out.printf("The box node's translation is %s", node.getTransform().getTranslation());
```
### getChildNodes() {#getChildNodes--}
```
public List<Node> getChildNodes()
```


Ottiene i nodi figli.

**Returns:**
java.util.List<com.aspose.threed.Node> - i nodi figli. **Example:** Il codice seguente mostra come elencare i nodi figli del nodo radice

```
Scene scene = Scene.fromFile("test.fbx");
     for(var child : scene.getRootNode().getChildNodes())
     {
         //do your business
     }
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntities() {#getEntities--}
```
public List<Entity> getEntities()
```


Ottiene tutte le entità del nodo.

**Returns:**
java.util.List<com.aspose.threed.Entity> - tutte le entità del nodo.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Ottiene la prima entità allegata a questo nodo; se impostata, cancellerà le altre entità.

**Returns:**
[Entity](../../com.aspose.threed/entity) - the first entity attached to this node, if sets, will clear other entities. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Ottiene se escludere questo nodo e tutti i nodi/entità figli durante l'esportazione.

**Returns:**
boolean - indica se escludere questo nodo e tutti i nodi/entità figli durante l'esportazione. **Example:** Il codice seguente mostra come escludere il nodo specificato dall'esportazione

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode("excluded", new Box()).setExcluded(true);
     scene.getRootNode().createChildNode("not excluded", new Box());
     scene.save("output.usdz");
```
### getGlobalTransform() {#getGlobalTransform--}
```
public GlobalTransform getGlobalTransform()
```


Ottiene la trasformazione globale.

**Returns:**
[GlobalTransform](../../com.aspose.threed/globaltransform) - the global transform. **Example:** The following code shows how to read node's global transform

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.printf("The box's position in world coordinate is %s", global.getTranslation());
```
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Ottiene il primo materiale associato a questo nodo; se impostato, cancellerà gli altri materiali

**Returns:**
[Material](../../com.aspose.threed/material) - the first material associated with this node, if sets, will clear other materials **Example:**

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
```
### getMaterials() {#getMaterials--}
```
public List<Material> getMaterials()
```


Ottiene i materiali associati a questo nodo.

**Returns:**
java.util.List<com.aspose.threed.Material> - i materiali associati a questo nodo.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Ottiene i metadati definiti in questo nodo.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - i metadati definiti in questo nodo.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Ottiene il nodo genitore.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Ottiene la collezione di tutte le proprietà.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Ottieni il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |

**Returns:**
java.lang.Object - Il valore della proprietà trovata
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Ottiene la trasformazione locale.

**Returns:**
[Transform](../../com.aspose.threed/transform) - the local transform. **Example:** The following code shows how to change the transform of the node:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Ottiene se mostrare il nodo

**Returns:**
boolean - per mostrare il nodo **Example:** Il codice seguente mostra come creare un nodo invisibile

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("test-node", new Box());
     node.setVisible(false);
     scene.save("output.fbx");
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### merge(Node node) {#merge-com.aspose.threed.Node-}
```
public void merge(Node node)
```


Stacca tutto sotto il nodo e allegalo al nodo corrente. **Example:** Il codice seguente mostra come unire due file 3D in un unico file

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Rimuove una proprietà dinamica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Rimuove la proprietà specificata identificata per nome

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Seleziona più oggetti sotto il nodo corrente usando una sintassi di query simile a XPath.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | La query simile a XPath |

**Returns:**
java.util.ArrayList<java.lang.Object> - Più oggetti corrispondono alla query simile a XPath.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Seleziona un singolo oggetto sotto il nodo corrente usando una sintassi di query simile a XPath.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | La query simile a XPath |

**Returns:**
java.lang.Object - Oggetto individuato dalla query simile a XPath.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Informazioni sull'asset per nodo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nuovo valore |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Imposta la prima entità allegata a questo nodo; se impostata, cancellerà le altre entità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Nuovo valore **Example:** Il codice seguente mostra come creare un nuovo nodo figlio sotto il nodo radice |

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
``` |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Imposta se escludere questo nodo e tutti i nodi/entità figli durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Nuovo valore **Example:** Il codice seguente mostra come escludere il nodo specificato dall'esportazione |

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode("excluded", new Box()).setExcluded(true);
     scene.getRootNode().createChildNode("not excluded", new Box());
     scene.save("output.usdz");
``` |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Imposta il primo materiale associato a questo nodo; se impostato, cancellerà gli altri materiali

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Nuovo valore **Esempio:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Imposta il nodo genitore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuovo valore |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Imposta il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |
| valore | java.lang.Object | Il valore della proprietà |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Imposta per mostrare il nodo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Nuovo valore **Example:** Il codice seguente mostra come creare un nodo invisibile |

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("test-node", new Box());
     node.setVisible(false);
     scene.save("output.fbx");
``` |

### toString() {#toString--}
```
public String toString()
```


Ottiene la rappresentazione stringa di questo nodo.

**Returns:**
java.lang.String - La rappresentazione stringa di questo nodo per il debug.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

