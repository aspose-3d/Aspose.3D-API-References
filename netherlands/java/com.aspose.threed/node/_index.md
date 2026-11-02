---
title: "Node"
second_title: "Aspose.3D voor Java API-referentie"
description: "Stelt een element in de scenegrafiek voor."
type: docs
weight: 110
url: /nl/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Stelt een element in de scenegrafiek voor. Een scenegrafiek is een boom van Node-objecten. De boom-beheerdiensten zijn zelfvoorzienend in deze klasse. Let op: de Aspose.3D SDK test de geldigheid van de geconstrueerde scenegrafiek niet. Het is de verantwoordelijkheid van de aanroeper om ervoor te zorgen dat er geen cyclische grafieken in een node-hiërarchie worden gegenereerd. Naast het boombeheer definieert deze klasse alle eigenschappen die nodig zijn om de positie van het object in de scène te beschrijven. Deze informatie omvat de basis-eigenschappen Translation, Rotation en Scaling en de meer geavanceerde opties voor pivots, limieten en IK-gewricht-attributen zoals stijfheid en demping. Wanneer het voor het eerst wordt aangemaakt, is het Node-object "leeg" (d.w.z.: het is een object zonder enige grafische weergave dat alleen de positie-informatie bevat). In deze toestand kan het worden gebruikt om ouders in de node-boomstructuur te vertegenwoordigen, maar niet veel meer. Het normale gebruik van dit type objecten is om er een entity aan toe te voegen die de node specialiseert (zie de "Entity"). De entity is een object op zich en is verbonden met de Node. Dit betekent ook dat dezelfde entity kan worden gedeeld door meerdere nodes. Camera, Light, Mesh, enz... zijn allemaal entities en ze zijn allemaal afgeleid van de basisklasse Entity.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Node()](#Node--) | Initialiseert een nieuw exemplaar van de [Node](../../com.aspose.threed/node) klasse. |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Initialiseert een nieuw exemplaar van de [Node](../../com.aspose.threed/node) klasse. |
| [Node(String name)](#Node-java.lang.String-) | Initialiseert een nieuw exemplaar van de [Node](../../com.aspose.threed/node) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Doorloopt alle afstammende nodes (inclusief de huidige node) en roept de bezoeker aan met de node. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Voeg een kindnode toe aan deze node |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Voeg een entity toe aan de node. |
| [createChildNode()](#createChildNode--) | Creëert een kindknooppunt |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Maak een nieuw kindknooppunt met de opgegeven entiteit gekoppeld |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam, en koppel de gespecificeerde entiteit en een materiaal |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Evalueer de globale transformatie, al dan niet de geometrische transformatie opnemen. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getAssetInfo()](#getAssetInfo--) | Per-knooppunt activainformatie |
| [getBoundingBox()](#getBoundingBox--) | Bereken de omhullende doos van het knooppunt |
| [getChild(int index)](#getChild-int-) | Haalt het kindknooppunt op op de opgegeven index. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Haalt het kindknooppunt op met de opgegeven naam |
| [getChildNodes()](#getChildNodes--) | Haalt de kindknooppunten op. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Haalt alle knooppunteenities op. |
| [getEntity()](#getEntity--) | Haalt de eerste entiteit op die aan dit knooppunt is gekoppeld; indien ingesteld, worden andere entiteiten gewist. |
| [getExcluded()](#getExcluded--) | Haalt op of dit knooppunt en alle kindknooppunten/entiteiten moeten worden uitgesloten tijdens exporteren. |
| [getGlobalTransform()](#getGlobalTransform--) | Haalt de globale transformatie op. |
| [getMaterial()](#getMaterial--) | Haalt het eerste materiaal op dat aan dit knooppunt is gekoppeld; indien ingesteld, worden andere materialen gewist. |
| [getMaterials()](#getMaterials--) | Haalt de materialen op die aan dit knooppunt zijn gekoppeld. |
| [getMetaDatas()](#getMetaDatas--) | Haalt de metagegevens op die in dit knooppunt zijn gedefinieerd. |
| [getName()](#getName--) | Haalt de naam op. |
| [getParentNode()](#getParentNode--) | Haalt het bovenliggende knooppunt op. |
| [getProperties()](#getProperties--) | Haalt de collectie van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde van de opgegeven eigenschap op. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort. |
| [getTransform()](#getTransform--) | Haalt de lokale transformatie op. |
| [getVisible()](#getVisible--) | Haalt op om het knooppunt te tonen. |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Ontkoppel alles onder het knooppunt en koppel het aan het huidige knooppunt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam. |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Selecteer meerdere objecten onder het huidige knooppunt met XPath-achtige querysyntaxis. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Selecteer een enkel object onder het huidige knooppunt met XPath-achtige querysyntaxis. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Per-knooppunt activainformatie |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Stelt de eerste entiteit in die aan dit knooppunt is gekoppeld; indien ingesteld, worden andere entiteiten gewist. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Stelt in of dit knooppunt en alle kindknooppunten/entiteiten moeten worden uitgesloten tijdens exporteren. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Stelt het eerste materiaal in dat aan dit knooppunt is gekoppeld; indien ingesteld, worden andere materialen gewist |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Stelt het bovenliggende knooppunt in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde van de opgegeven eigenschap in. |
| [setVisible(boolean value)](#setVisible-boolean-) | Stelt in om het knooppunt te tonen |
| [toString()](#toString--) | Haalt de tekenreeksrepresentatie van dit knooppunt op. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Initialiseert een nieuw exemplaar van de [Node](../../com.aspose.threed/node) klasse.

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Initialiseert een nieuw exemplaar van de [Node](../../com.aspose.threed/node) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |
| entity | [Entity](../../com.aspose.threed/entity) | Standaard entiteit. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Initialiseert een nieuw exemplaar van de [Node](../../com.aspose.threed/node) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Doorloopt alle afstammelingen knooppunten (inclusief het huidige knooppunt) en roept de Visitor aan met het knooppunt. Visitor kan de doorloop onderbreken door false te retourneren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Visitor callback om het knooppunt te bezoeken |

**Returns:**
boolean - true betekent dat de visitor de doorloop heeft onderbroken. **Example:** De volgende code laat zien hoe alle meshes uit een scène worden opgehaald

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


Voeg een kindnode toe aan deze node

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Het kindknooppunt dat moet worden gekoppeld **Example:** De volgende code laat zien hoe alle meshes uit een scène worden opgehaald |

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


Voeg een entity toe aan de node.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | De entiteit die aan het knooppunt moet worden gekoppeld |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Creëert een kindknooppunt

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


Maak een nieuw kindknooppunt met de opgegeven entiteit gekoppeld

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Standaard entiteit gekoppeld aan het knooppunt |

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


Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeName | java.lang.String | De naam van het nieuwe kindknooppunt |

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


Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeName | java.lang.String | De naam van het nieuwe kindknooppunt |
| entity | [Entity](../../com.aspose.threed/entity) | Standaard entiteit gekoppeld aan het knooppunt |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam, en koppel de gespecificeerde entiteit en een materiaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeName | java.lang.String | De naam van het nieuwe kindknooppunt |
| entity | [Entity](../../com.aspose.threed/entity) | Standaard entiteit gekoppeld aan het knooppunt |
| material | [Material](../../com.aspose.threed/material) | Het materiaal gekoppeld aan het knooppunt |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Evalueer de globale transformatie, al dan niet de geometrische transformatie opnemen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| withGeometricTransform | boolean | Of de geometrische transformatie nodig is. |

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


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String | Naam van de eigenschap. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Per-knooppunt activainformatie

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Bereken de omhullende doos van het knooppunt

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Haalt het kindknooppunt op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index. |

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


Haalt het kindknooppunt op met de opgegeven naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeName | java.lang.String | De te vinden kindnaam. |

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


Haalt de kindknooppunten op.

**Returns:**
java.util.List<com.aspose.threed.Node> - de kindknooppunten. **Example:** De volgende code laat zien hoe kindknooppunten van het rootknooppunt worden opgesomd

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


Haalt alle knooppunteenities op.

**Returns:**
java.util.List<com.aspose.threed.Entity> - alle knooppuntentiteiten.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Haalt de eerste entiteit op die aan dit knooppunt is gekoppeld; indien ingesteld, worden andere entiteiten gewist.

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


Haalt op of dit knooppunt en alle kindknooppunten/entiteiten moeten worden uitgesloten tijdens exporteren.

**Returns:**
boolean - of dit knooppunt en alle kindknooppunten/entiteiten moeten worden uitgesloten tijdens exporteren. **Example:** De volgende code laat zien hoe een specifiek knooppunt wordt uitgesloten bij exporteren

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


Haalt de globale transformatie op.

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


Haalt het eerste materiaal op dat aan dit knooppunt is gekoppeld; indien ingesteld, worden andere materialen gewist.

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


Haalt de materialen op die aan dit knooppunt zijn gekoppeld.

**Returns:**
java.util.List<com.aspose.threed.Material> - de materialen die aan dit knooppunt zijn gekoppeld.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Haalt de metagegevens op die in dit knooppunt zijn gedefinieerd.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - de metagegevens die in dit knooppunt zijn gedefinieerd.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Haalt het bovenliggende knooppunt op.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Haalt de collectie van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde van de opgegeven eigenschap op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van de eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getScene() {#getScene--}
```
public Scene getScene()
```


Haalt de scène op waartoe dit object behoort.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Haalt de lokale transformatie op.

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


Haalt op om het knooppunt te tonen.

**Returns:**
boolean - om het knooppunt weer te geven **Example:** De volgende code laat zien hoe een onzichtbaar knooppunt wordt gemaakt

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


Ontkoppel alles onder het knooppunt en koppel het aan het huidige knooppunt. **Example:** De volgende code laat zien hoe twee 3D-bestanden worden samengevoegd tot één bestand

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijder de opgegeven eigenschap geïdentificeerd op naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Selecteer meerdere objecten onder het huidige knooppunt met XPath-achtige querysyntaxis.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | De XPath-achtige query |

**Returns:**
java.util.ArrayList<java.lang.Object> - Meerdere objecten komen overeen met de XPath-achtige query.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Selecteer een enkel object onder het huidige knooppunt met XPath-achtige querysyntaxis.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | De XPath-achtige query |

**Returns:**
java.lang.Object - Object gevonden door de XPath-achtige query.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Per-knooppunt activainformatie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nieuwe waarde |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Stelt de eerste entiteit in die aan dit knooppunt is gekoppeld; indien ingesteld, worden andere entiteiten gewist.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Nieuwe waarde **Voorbeeld:** De volgende code laat zien hoe je een nieuw kindknooppunt onder het rootknooppunt maakt |

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


Stelt in of dit knooppunt en alle kindknooppunten/entiteiten moeten worden uitgesloten tijdens exporteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Nieuwe waarde **Voorbeeld:** De volgende code laat zien hoe je een opgegeven knooppunt uitsluit van exporteren |

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


Stelt het eerste materiaal in dat aan dit knooppunt is gekoppeld; indien ingesteld, worden andere materialen gewist

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Nieuwe waarde **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Stelt het bovenliggende knooppunt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Stelt de waarde van de opgegeven eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van de eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Stelt in om het knooppunt te tonen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | Nieuwe waarde **Voorbeeld:** De volgende code laat zien hoe je een onzichtbaar knooppunt maakt |

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


Haalt de tekenreeksrepresentatie van dit knooppunt op.

**Returns:**
java.lang.String - De tekenreeksrepresentatie van dit knooppunt voor debugging.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

