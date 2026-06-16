---
title: Node
second_title: Referencia de API de Aspose.3D para Java
description: Representa un elemento en el grafo de escena.
type: docs
weight: 110
url: /es/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Representa un elemento en el grafo de escena. Un grafo de escena es un árbol de objetos Node. Los servicios de gestión del árbol están contenidos en esta clase. Tenga en cuenta que el Aspose.3D SDK no verifica la validez del grafo de escena construido. Es responsabilidad del llamador asegurarse de que no genere grafos cíclicos en una jerarquía de nodos. Además de la gestión del árbol, esta clase define todas las propiedades necesarias para describir la posición del objeto en la escena. Esta información incluye las propiedades básicas de Translation, Rotation y Scaling, y las opciones más avanzadas para pivotes, límites y atributos de articulaciones IK, como la rigidez y el amortiguamiento. Cuando se crea por primera vez, el objeto Node está "empty" (es decir, es un objeto sin representación gráfica que solo contiene la información de posición). En este estado, puede usarse para representar padres en la estructura del árbol de nodos pero no mucho más. El uso normal de este tipo de objetos es añadirles una entidad que especialice el nodo (ver la "Entity"). La entidad es un objeto por sí misma y está conectada al Node. Esto también significa que la misma entidad puede compartirse entre varios nodos. Camera, Light, Mesh, etc... son todas entidades y todas derivan de la clase base Entity.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Node()](#Node--) | Inicializa una nueva instancia de la clase [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Inicializa una nueva instancia de la clase [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | Inicializa una nueva instancia de la clase [Node](../../com.aspose.threed/node). |
## Métodos

| Método | Descripción |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Recorre todos los nodos descendientes (incluyendo el nodo actual) y llama al visitante con el nodo. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Agregar un nodo hijo a este nodo |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Agregar una entidad al nodo. |
| [createChildNode()](#createChildNode--) | Crea un nodo hijo |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Crea un nuevo nodo hijo con la entidad dada adjunta |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Crea un nuevo nodo hijo con el nombre de nodo dado |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Crea un nuevo nodo hijo con el nombre de nodo dado |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Crea un nuevo nodo hijo con el nombre de nodo dado y adjunta la entidad especificada y un material |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Evalúa la transformación global, incluye la transformación geométrica o no. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getAssetInfo()](#getAssetInfo--) | Información de recursos por nodo |
| [getBoundingBox()](#getBoundingBox--) | Calcula el cuadro delimitador del nodo |
| [getChild(int index)](#getChild-int-) | Obtiene el nodo hijo en el índice especificado. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Obtiene el nodo hijo con el nombre especificado |
| [getChildNodes()](#getChildNodes--) | Obtiene los nodos hijos. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Obtiene todas las entidades del nodo. |
| [getEntity()](#getEntity--) | Obtiene la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades. |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir este nodo y todos los nodos hijos/entidades durante la exportación. |
| [getGlobalTransform()](#getGlobalTransform--) | Obtiene la transformación global. |
| [getMaterial()](#getMaterial--) | Obtiene el primer material asociado a este nodo; si se establece, se eliminarán los demás materiales |
| [getMaterials()](#getMaterials--) | Obtiene los materiales asociados a este nodo. |
| [getMetaDatas()](#getMetaDatas--) | Obtiene los metadatos definidos en este nodo. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getParentNode()](#getParentNode--) | Obtiene el nodo padre. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getTransform()](#getTransform--) | Obtiene la transformación local. |
| [getVisible()](#getVisible--) | Obtiene para mostrar el nodo |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Desvincula todo bajo el nodo y lo adjunta al nodo actual. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Selecciona múltiples objetos bajo el nodo actual usando sintaxis de consulta similar a XPath. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Selecciona un solo objeto bajo el nodo actual usando sintaxis de consulta similar a XPath. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Información de recursos por nodo |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Establece la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir este nodo y todos los nodos hijos/entidades durante la exportación. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Establece el primer material asociado con este nodo; si se establece, borrará los otros materiales |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el nodo padre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setVisible(boolean value)](#setVisible-boolean-) | Configura para mostrar el nodo |
| [toString()](#toString--) | Obtiene la representación en cadena de este nodo. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Inicializa una nueva instancia de la clase [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Inicializa una nueva instancia de la clase [Node](../../com.aspose.threed/node).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |
| entity | [Entity](../../com.aspose.threed/entity) | Entidad predeterminada. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Inicializa una nueva instancia de la clase [Node](../../com.aspose.threed/node).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Recorre todos los nodos descendientes (incluido el nodo actual) y llama al visitante con el nodo. El visitante puede interrumpir el recorrido devolviendo false

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Función de devolución de llamada del visitante para visitar el nodo |

**Returns:**
boolean - true significa que el visitante ha interrumpido el recorrido. **Example:** El siguiente código muestra cómo obtener todas las mallas de una escena

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


Agregar un nodo hijo a este nodo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | El nodo hijo a adjuntar **Example:** El siguiente código muestra cómo obtener todas las mallas de una escena |

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


Agregar una entidad al nodo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | La entidad a adjuntar al nodo |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Crea un nodo hijo

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


Crea un nuevo nodo hijo con la entidad dada adjunta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Entidad predeterminada adjunta al nodo |

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


Crea un nuevo nodo hijo con el nombre de nodo dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | java.lang.String | El nombre del nuevo nodo hijo |

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


Crea un nuevo nodo hijo con el nombre de nodo dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | java.lang.String | El nombre del nuevo nodo hijo |
| entity | [Entity](../../com.aspose.threed/entity) | Entidad predeterminada adjunta al nodo |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Crea un nuevo nodo hijo con el nombre de nodo dado y adjunta la entidad especificada y un material

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | java.lang.String | El nombre del nuevo nodo hijo |
| entity | [Entity](../../com.aspose.threed/entity) | Entidad predeterminada adjunta al nodo |
| material | [Material](../../com.aspose.threed/material) | El material adjunto al nodo |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Evalúa la transformación global, incluye la transformación geométrica o no.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| withGeometricTransform | boolean | Indica si se necesita la transformación geométrica. |

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


Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | java.lang.String | Nombre de la propiedad. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Información de recursos por nodo

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Calcula el cuadro delimitador del nodo

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Obtiene el nodo hijo en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice. |

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


Obtiene el nodo hijo con el nombre especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeName | java.lang.String | El nombre del hijo a buscar. |

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


Obtiene los nodos hijos.

**Returns:**
java.util.List<com.aspose.threed.Node> - los nodos hijos. **Example:** El siguiente código muestra cómo enumerar el nodo hijo del nodo raíz

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


Obtiene todas las entidades del nodo.

**Returns:**
java.util.List<com.aspose.threed.Entity> - todas las entidades del nodo.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Obtiene la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades.

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


Obtiene si se debe excluir este nodo y todos los nodos hijos/entidades durante la exportación.

**Returns:**
boolean - indica si excluir este nodo y todos los nodos hijos/entidades durante la exportación. **Example:** El siguiente código muestra cómo excluir el nodo especificado de la exportación

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


Obtiene la transformación global.

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


Obtiene el primer material asociado a este nodo; si se establece, se eliminarán los demás materiales

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


Obtiene los materiales asociados a este nodo.

**Returns:**
java.util.List<com.aspose.threed.Material> - los materiales asociados a este nodo.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Obtiene los metadatos definidos en este nodo.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - los metadatos definidos en este nodo.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Obtiene el nodo padre.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtiene la colección de todas las propiedades.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtiene el valor de la propiedad especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |

**Returns:**
java.lang.Object - El valor de la propiedad encontrada
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Obtiene la transformación local.

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


Obtiene para mostrar el nodo

**Returns:**
boolean - para mostrar el nodo **Example:** El siguiente código muestra cómo crear un nodo invisible

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


Desacopla todo lo que está bajo el nodo y lo adjunta al nodo actual. **Example:** El siguiente código muestra cómo combinar dos archivos 3D en un solo archivo

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parámetro | Tipo | Descripción |
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


Elimina una propiedad dinámica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Elimina la propiedad especificada identificada por nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Selecciona múltiples objetos bajo el nodo actual usando sintaxis de consulta similar a XPath.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La consulta similar a XPath |

**Returns:**
java.util.ArrayList<java.lang.Object> - Múltiples objetos coinciden con la consulta tipo XPath.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Selecciona un solo objeto bajo el nodo actual usando sintaxis de consulta similar a XPath.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La consulta similar a XPath |

**Returns:**
java.lang.Object - Objeto localizado mediante la consulta tipo XPath.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Información de recursos por nodo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nuevo valor |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Establece la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Nuevo valor **Example:** El siguiente código muestra cómo crear un nuevo nodo hijo bajo el nodo raíz |

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


Establece si se debe excluir este nodo y todos los nodos hijos/entidades durante la exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Nuevo valor **Example:** El siguiente código muestra cómo excluir un nodo especificado de la exportación |

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


Establece el primer material asociado con este nodo; si se establece, borrará los otros materiales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Nuevo valor **Ejemplo:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Establece el nodo padre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuevo valor |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Establece el valor de la propiedad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |
| valor | java.lang.Object | El valor de la propiedad |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Configura para mostrar el nodo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Nuevo valor **Example:** El siguiente código muestra cómo crear un nodo invisible |

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


Obtiene la representación en cadena de este nodo.

**Returns:**
java.lang.String - La representación en cadena de este nodo para depuración.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

