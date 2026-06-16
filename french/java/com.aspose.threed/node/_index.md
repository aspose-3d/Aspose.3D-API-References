---
title: "Node"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Représente un élément dans le graphe de la scène."
type: docs
weight: 110
url: /fr/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Représente un élément du graphe de scène. Un graphe de scène est un arbre d'objets Node. Les services de gestion d'arbre sont autonomes dans cette classe. Notez que le Aspose.3D SDK ne teste pas la validité du graphe de scène construit. Il incombe à l'appelant de s'assurer qu'il ne génère pas de graphes cycliques dans une hiérarchie de nœuds. En plus de la gestion d'arbre, cette classe définit toutes les propriétés requises pour décrire la position de l'objet dans la scène. Ces informations incluent les propriétés de base de Translation, Rotation et Échelle ainsi que les options avancées pour les pivots, limites et attributs des articulations IK tels que la raideur et l'amortissement. Lorsqu'il est créé pour la première fois, l'objet Node est "vide" (c.-à-d. il s'agit d'un objet sans représentation graphique qui ne contient que les informations de position). Dans cet état, il peut être utilisé pour représenter des parents dans la structure d'arbre de nœuds mais pas bien plus. L'utilisation normale de ce type d'objets consiste à leur ajouter une Entity qui spécialisera le nœud (voir la "Entity"). L'Entity est un objet en soi et est connectée au Node. Cela signifie également que la même Entity peut être partagée entre plusieurs nœuds. Caméra, Lumière, Maillage, etc. sont toutes des Entity et elles dérivent toutes de la classe de base Entity.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Node()](#Node--) | Initialise une nouvelle instance de la classe [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Initialise une nouvelle instance de la classe [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | Initialise une nouvelle instance de la classe [Node](../../com.aspose.threed/node). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Parcourt tous les nœuds descendants (y compris le nœud actuel) et appelle le visiteur avec le nœud. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Ajouter un nœud enfant à ce nœud |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Ajouter une Entity au nœud. |
| [createChildNode()](#createChildNode--) | Crée un nœud enfant |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Crée un nouveau nœud enfant avec l'entité donnée attachée |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Crée un nouveau nœud enfant avec le nom de nœud donné |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Crée un nouveau nœud enfant avec le nom de nœud donné |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Crée un nouveau nœud enfant avec le nom de nœud donné, et attache l'entité spécifiée ainsi qu'un matériau |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Évalue la transformation globale, inclut ou non la transformation géométrique. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAssetInfo()](#getAssetInfo--) | Informations d'actif par nœud |
| [getBoundingBox()](#getBoundingBox--) | Calcule la boîte englobante du nœud |
| [getChild(int index)](#getChild-int-) | Obtient le nœud enfant à l'index spécifié. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Obtient le nœud enfant avec le nom spécifié |
| [getChildNodes()](#getChildNodes--) | Obtient les nœuds enfants. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Obtient toutes les entités du nœud. |
| [getEntity()](#getEntity--) | Obtient la première entité attachée à ce nœud, si définie, effacera les autres entités. |
| [getExcluded()](#getExcluded--) | Obtient si ce nœud et tous les nœuds enfants/entités doivent être exclus lors de l'exportation. |
| [getGlobalTransform()](#getGlobalTransform--) | Obtient la transformation globale. |
| [getMaterial()](#getMaterial--) | Obtient le premier matériau associé à ce nœud, si défini, effacera les autres matériaux |
| [getMaterials()](#getMaterials--) | Obtient les matériaux associés à ce nœud. |
| [getMetaDatas()](#getMetaDatas--) | Obtient les métadonnées définies dans ce nœud. |
| [getName()](#getName--) | Obtient le nom. |
| [getParentNode()](#getParentNode--) | Obtient le nœud parent. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getTransform()](#getTransform--) | Obtient la transformation locale. |
| [getVisible()](#getVisible--) | Obtient l'affichage du nœud |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Détache tout sous le nœud et les attache au nœud actuel. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Sélectionne plusieurs objets sous le nœud actuel en utilisant une syntaxe de requête de type XPath. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Sélectionne un seul objet sous le nœud actuel en utilisant une syntaxe de requête de type XPath. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Informations d'actif par nœud |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Définit la première entité attachée à ce nœud, si définie, effacera les autres entités. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si ce nœud et tous les nœuds enfants/entités doivent être exclus lors de l'exportation. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Définit le premier matériau associé à ce nœud, si défini, effacera les autres matériaux |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le nœud parent. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setVisible(boolean value)](#setVisible-boolean-) | Définit l'affichage du nœud |
| [toString()](#toString--) | Obtient la représentation sous forme de chaîne de ce nœud. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Initialise une nouvelle instance de la classe [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Initialise une nouvelle instance de la classe [Node](../../com.aspose.threed/node).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |
| entity | [Entity](../../com.aspose.threed/entity) | Entité par défaut. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Initialise une nouvelle instance de la classe [Node](../../com.aspose.threed/node).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Parcourt tous les nœuds descendants (y compris le nœud actuel) et appelle le visiteur avec le nœud. Le visiteur peut interrompre le parcours en renvoyant false

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Rappel du visiteur pour visiter le nœud |

**Returns:**
booléen - true signifie que le visiteur a interrompu le parcours. **Example:** Le code suivant montre comment obtenir tous les maillages d'une scène

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


Ajouter un nœud enfant à ce nœud

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Le nœud enfant à attacher **Example:** Le code suivant montre comment obtenir tous les maillages d'une scène |

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


Ajouter une Entity au nœud.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entité à attacher au nœud |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Crée un nœud enfant

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


Crée un nouveau nœud enfant avec l'entité donnée attachée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Entité par défaut attachée au nœud |

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


Crée un nouveau nœud enfant avec le nom de nœud donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | java.lang.String | Le nom du nouveau nœud enfant |

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


Crée un nouveau nœud enfant avec le nom de nœud donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | java.lang.String | Le nom du nouveau nœud enfant |
| entity | [Entity](../../com.aspose.threed/entity) | Entité par défaut attachée au nœud |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Crée un nouveau nœud enfant avec le nom de nœud donné, et attache l'entité spécifiée ainsi qu'un matériau

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | java.lang.String | Le nom du nouveau nœud enfant |
| entity | [Entity](../../com.aspose.threed/entity) | Entité par défaut attachée au nœud |
| material | [Material](../../com.aspose.threed/material) | Le matériau attaché au nœud |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Évalue la transformation globale, inclut ou non la transformation géométrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| withGeometricTransform | boolean | Indique si la transformation géométrique est nécessaire. |

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


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Informations d'actif par nœud

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Calcule la boîte englobante du nœud

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Obtient le nœud enfant à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
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


Obtient le nœud enfant avec le nom spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | java.lang.String | Le nom de l'enfant à rechercher. |

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


Obtient les nœuds enfants.

**Returns:**
java.util.List<com.aspose.threed.Node> - les nœuds enfants. **Example:** Le code suivant montre comment énumérer les nœuds enfants du nœud racine

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


Obtient toutes les entités du nœud.

**Returns:**
java.util.List<com.aspose.threed.Entity> - toutes les entités du nœud.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Obtient la première entité attachée à ce nœud, si définie, effacera les autres entités.

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


Obtient si ce nœud et tous les nœuds enfants/entités doivent être exclus lors de l'exportation.

**Returns:**
booléen - indique s'il faut exclure ce nœud ainsi que tous les nœuds enfants et entités lors de l'exportation. **Example:** Le code suivant montre comment exclure le nœud spécifié de l'exportation

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


Obtient la transformation globale.

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


Obtient le premier matériau associé à ce nœud, si défini, effacera les autres matériaux

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


Obtient les matériaux associés à ce nœud.

**Returns:**
java.util.List<com.aspose.threed.Material> - les matériaux associés à ce nœud.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Obtient les métadonnées définies dans ce nœud.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - les métadonnées définies dans ce nœud.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Obtient le nœud parent.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Obtient la transformation locale.

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


Obtient l'affichage du nœud

**Returns:**
booléen - pour afficher le nœud **Example:** Le code suivant montre comment créer un nœud invisible

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


Détache tout ce qui se trouve sous le nœud et les attache au nœud actuel. **Example:** Le code suivant montre comment fusionner deux fichiers 3D en un seul fichier

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Paramètre | Type | Description |
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


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Sélectionne plusieurs objets sous le nœud actuel en utilisant une syntaxe de requête de type XPath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | La requête de type XPath |

**Returns:**
java.util.ArrayList<java.lang.Object> - Plusieurs objets correspondent à la requête de type XPath.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Sélectionne un seul objet sous le nœud actuel en utilisant une syntaxe de requête de type XPath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | La requête de type XPath |

**Returns:**
java.lang.Object - Objet situé par la requête de type XPath.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Informations d'actif par nœud

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nouvelle valeur |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Définit la première entité attachée à ce nœud, si définie, effacera les autres entités.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Nouvelle valeur **Exemple:** Le code suivant montre comment créer un nouveau nœud enfant sous le nœud racine |

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


Définit si ce nœud et tous les nœuds enfants/entités doivent être exclus lors de l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Nouvelle valeur **Exemple:** Le code suivant montre comment exclure un nœud spécifié de l'exportation |

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


Définit le premier matériau associé à ce nœud, si défini, effacera les autres matériaux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Nouvelle valeur **Exemple:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Définit le nœud parent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Définit l'affichage du nœud

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Nouvelle valeur **Exemple:** Le code suivant montre comment créer un nœud invisible |

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


Obtient la représentation sous forme de chaîne de ce nœud.

**Returns:**
java.lang.String - La représentation sous forme de chaîne de ce nœud pour le débogage.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

