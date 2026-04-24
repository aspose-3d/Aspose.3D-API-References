---
title: Node
second_title: Aspose.3D for Java API-referens
description: Representerar ett element i scengrafen.
type: docs
weight: 110
url: /sv/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Representerar ett element i scengrafen. En scengraf är ett träd av Node‑objekt. Trädhanteringstjänsterna är självständiga i denna klass. Observera att Aspose.3D SDK inte testar giltigheten för den konstruerade scengrafen. Det är anroparens ansvar att säkerställa att den inte genererar cykliska grafer i en nodhierarki. Förutom trädhanteringen definierar denna klass alla egenskaper som krävs för att beskriva objektets position i scenen. Denna information inkluderar de grundläggande egenskaperna Translation, Rotation och Scaling samt mer avancerade alternativ för pivoter, begränsningar och IK‑ledattribut såsom styvhet och dämpning. När den först skapas är Node‑objektet "tomt" (dvs. ett objekt utan någon grafisk representation som endast innehåller positionsinformation). I detta tillstånd kan det användas för att representera föräldrar i nodträdet men inte mycket mer. Den normala användningen av denna typ av objekt är att lägga till dem en entity som specialiserar noden (se "Entity"). Entiteten är ett eget objekt och är kopplat till Node. Detta innebär också att samma entitet kan delas mellan flera noder. Kamera, Light, Mesh osv... är alla entiteter och de är alla härledda från basklassen Entity.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Node()](#Node--) | Initierar en ny instans av klassen [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Initierar en ny instans av klassen [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | Initierar en ny instans av klassen [Node](../../com.aspose.threed/node). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Går igenom alla efterföljande noder (inklusive den aktuella noden) och anropar besökaren med noden. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Lägg till en barnnod till denna nod |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Lägg till en entity till noden. |
| [createChildNode()](#createChildNode--) | Skapar en barnnod |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Skapa en ny barnnod med angiven entitet bifogad |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Skapa en ny barnnod med angivet nodnamn |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Skapa en ny barnnod med angivet nodnamn |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Skapa en ny barnnod med angivet nodnamn och bifoga specificerad entitet och ett material |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Utvärdera den globala transformen, inkludera den geometriska transformen eller inte. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getAssetInfo()](#getAssetInfo--) | Tillgångsinformation per nod |
| [getBoundingBox()](#getBoundingBox--) | Beräkna nodens omgivningsbox |
| [getChild(int index)](#getChild-int-) | Hämtar barnnoden på angivet index. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Hämtar barnnoden med det angivna namnet |
| [getChildNodes()](#getChildNodes--) | Hämtar barnnoderna. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Hämtar alla nodentiteter. |
| [getEntity()](#getEntity--) | Hämtar den första entiteten som är bifogad till denna nod, om den sätts rensas andra entiteter. |
| [getExcluded()](#getExcluded--) | Hämtar om denna nod och alla barnnoder/entiteter ska exkluderas vid export. |
| [getGlobalTransform()](#getGlobalTransform--) | Hämtar den globala transformen. |
| [getMaterial()](#getMaterial--) | Hämtar det första materialet som är associerat med denna nod, om den sätts rensas andra material |
| [getMaterials()](#getMaterials--) | Hämtar materialen som är associerade med denna nod. |
| [getMetaDatas()](#getMetaDatas--) | Hämtar metadata som definierats i denna nod. |
| [getName()](#getName--) | Hämtar namnet. |
| [getParentNode()](#getParentNode--) | Hämtar föräldranoden. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [getTransform()](#getTransform--) | Hämtar den lokala transformen. |
| [getVisible()](#getVisible--) | Hämtar för att visa noden |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Koppla bort allt under noden och bifoga dem till den aktuella noden. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Välj flera objekt under den aktuella noden med XPath-liknande frågesyntax. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Välj ett enskilt objekt under den aktuella noden med XPath-liknande frågesyntax. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Tillgångsinformation per nod |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Sätter den första entiteten som är bifogad till denna nod, om den sätts rensas andra entiteter. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Sätter om denna nod och alla barnnoder/entiteter ska exkluderas vid export. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Ställer in det första materialet som är associerat med denna nod; om det ställs in, rensas andra material. |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ställer in föräldranoden. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setVisible(boolean value)](#setVisible-boolean-) | Ställer in att visa noden. |
| [toString()](#toString--) | Hämtar nodens strängrepresentation. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Initierar en ny instans av klassen [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Initierar en ny instans av klassen [Node](../../com.aspose.threed/node).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn. |
| entity | [Entity](../../com.aspose.threed/entity) | Standardentity. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Initierar en ny instans av klassen [Node](../../com.aspose.threed/node).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Går igenom alla underordnade noder (inklusive den aktuella noden) och anropar besökaren med noden. Besökaren kan avbryta genomgången genom att returnera false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Besöksåteruppringning för att besöka noden. |

**Returns:**
boolean - true betyder att besökaren har avbrutit genomgången. **Exempel:** Följande kod visar hur man hämtar alla meshar från en scen

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


Lägg till en barnnod till denna nod

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Barnnoden som ska fästas **Exempel:** Följande kod visar hur man hämtar alla meshar från en scen |

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


Lägg till en entity till noden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Entiteten som ska fästas på noden. |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Skapar en barnnod

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


Skapa en ny barnnod med angiven entitet bifogad

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Standardentity fäst vid noden. |

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


Skapa en ny barnnod med angivet nodnamn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | java.lang.String | Det nya barnnodens namn. |

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


Skapa en ny barnnod med angivet nodnamn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | java.lang.String | Det nya barnnodens namn. |
| entity | [Entity](../../com.aspose.threed/entity) | Standardentity fäst vid noden. |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Skapa en ny barnnod med angivet nodnamn och bifoga specificerad entitet och ett material

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | java.lang.String | Det nya barnnodens namn. |
| entity | [Entity](../../com.aspose.threed/entity) | Standardentity fäst vid noden. |
| material | [Material](../../com.aspose.threed/material) | Materialet som är fäst vid noden. |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Utvärdera den globala transformen, inkludera den geometriska transformen eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| withGeometricTransform | boolean | Om den geometriska transformen behövs. |

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


Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String | Egenskapsnamn. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Tillgångsinformation per nod

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Beräkna nodens omgivningsbox

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Hämtar barnnoden på angivet index.

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar barnnoden med det angivna namnet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | java.lang.String | Barnnamnet att hitta. |

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


Hämtar barnnoderna.

**Returns:**
java.util.List<com.aspose.threed.Node> - barnnoderna. **Exempel:** Följande kod visar hur man enumererar barnnoder för rot noden

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


Hämtar alla nodentiteter.

**Returns:**
java.util.List<com.aspose.threed.Entity> - alla nodentityer.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Hämtar den första entiteten som är bifogad till denna nod, om den sätts rensas andra entiteter.

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


Hämtar om denna nod och alla barnnoder/entiteter ska exkluderas vid export.

**Returns:**
boolean - om denna nod och alla barnnoder/entityer ska exkluderas vid export. **Exempel:** Följande kod visar hur man exkluderar en specificerad nod från export

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


Hämtar den globala transformen.

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


Hämtar det första materialet som är associerat med denna nod, om den sätts rensas andra material

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


Hämtar materialen som är associerade med denna nod.

**Returns:**
java.util.List<com.aspose.threed.Material> - materialen som är associerade med denna nod.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Hämtar metadata som definierats i denna nod.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - metadata som definieras i denna nod.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Hämtar föräldranoden.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Hämta värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Värdet på den hittade egenskapen
### getScene() {#getScene--}
```
public Scene getScene()
```


Hämtar scenen som detta objekt tillhör

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Hämtar den lokala transformen.

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


Hämtar för att visa noden

**Returns:**
boolean - för att visa noden **Exempel:** Följande kod visar hur man skapar en osynlig nod

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


Koppla loss allt under noden och fäst dem på den aktuella noden. **Exempel:** Följande kod visar hur man slår ihop två 3D-filer till en fil

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Tar bort en dynamisk egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Ta bort den angivna egenskapen identifierad med namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Välj flera objekt under den aktuella noden med XPath-liknande frågesyntax.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | XPath-liknande frågan |

**Returns:**
java.util.ArrayList<java.lang.Object> - Flera objekt matchar XPath-liknande frågan.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Välj ett enskilt objekt under den aktuella noden med XPath-liknande frågesyntax.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | XPath-liknande frågan |

**Returns:**
java.lang.Object - Objekt som hittades av XPath-liknande frågan.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Tillgångsinformation per nod

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nytt värde |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Sätter den första entiteten som är bifogad till denna nod, om den sätts rensas andra entiteter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Nytt värde **Example:** Följande kod visar hur man skapar en ny barnnod under rotknuten |

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


Sätter om denna nod och alla barnnoder/entiteter ska exkluderas vid export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Nytt värde **Example:** Följande kod visar hur man exkluderar en specificerad nod från export |

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


Ställer in det första materialet som är associerat med denna nod; om det ställs in, rensas andra material.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Nytt värde **Exempel:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Ställer in föräldranoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nytt värde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ställer in värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |
| värde | java.lang.Object | Värdet på egenskapen |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Ställer in att visa noden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | Nytt värde **Example:** Följande kod visar hur man skapar en osynlig nod |

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


Hämtar nodens strängrepresentation.

**Returns:**
java.lang.String - Strängrepresentationen av denna nod för felsökning.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

