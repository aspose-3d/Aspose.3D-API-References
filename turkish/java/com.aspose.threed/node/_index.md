---
title: "Node"
second_title: "Aspose.3D for Java API Referansı"
description: "Sahne grafiğinde bir öğeyi temsil eder."
type: docs
weight: 110
url: /tr/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Bir sahne grafiğinde bir öğeyi temsil eder. Bir sahne grafiği, Node nesnelerinden oluşan bir ağaçtır. Ağaç yönetim hizmetleri bu sınıfta kendine özeldir. Aspose.3D SDK'nın oluşturulan sahne grafiğinin geçerliliğini test etmediğini unutmayın. Çağıranın, bir düğüm hiyerarşisinde döngüsel grafikler oluşturmadığından emin olması sorumluluğudur. Ağaç yönetiminin yanı sıra, bu sınıf sahnedeki nesnenin konumunu tanımlamak için gereken tüm özellikleri tanımlar. Bu bilgiler temel Translation, Rotation ve Scaling özelliklerini ve pivotalar, limitler ve IK eklemleri gibi daha gelişmiş seçenekleri, örneğin sertlik ve sönümleme gibi nitelikleri içerir. İlk oluşturulduğunda, Node nesnesi "empty" (yani yalnızca konum bilgisi içeren, grafiksel bir temsili olmayan bir nesnedir). Bu durumda, düğüm ağacı yapısında ebeveynleri temsil etmek için kullanılabilir ancak daha fazlası için değil. Bu tür nesnelerin normal kullanımı, düğümü özelleştirecek bir varlık eklemektir ("Entity" bölümüne bakınız). Varlık, kendisi bir nesnedir ve Node'a bağlanır. Bu aynı zamanda aynı varlığın birden fazla düğüm arasında paylaşılabileceği anlamına gelir. Kamera, Light, Mesh vb. hepsi varlıklardır ve hepsi temel sınıf Entity'den türetilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Node()](#Node--) | Yeni bir [Node](../../com.aspose.threed/node) sınıfı örneği başlatır. |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Yeni bir [Node](../../com.aspose.threed/node) sınıfı örneği başlatır. |
| [Node(String name)](#Node-java.lang.String-) | Yeni bir [Node](../../com.aspose.threed/node) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Tüm alt düğümlerden (mevcut düğüm dahil) geçer ve ziyaretçiyi düğümle çağırır. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Bu düğüme bir alt düğüm ekle |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Düğüm'e bir varlık ekle. |
| [createChildNode()](#createChildNode--) | Bir alt düğüm oluşturur |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Verilen varlık ekli yeni bir alt düğüm oluşturur |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur ve belirtilen varlığı ve bir materyali ekler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Genel dönüşümü değerlendir, geometrik dönüşümü dahil edip etmeyeceğini belirler. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getAssetInfo()](#getAssetInfo--) | Düğüm başına varlık bilgisi |
| [getBoundingBox()](#getBoundingBox--) | Düğümün sınırlayıcı kutusunu hesaplar |
| [getChild(int index)](#getChild-int-) | Belirtilen indeksteki alt düğümü alır. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Belirtilen ada sahip alt düğümü alır |
| [getChildNodes()](#getChildNodes--) | Alt düğümleri alır. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Tüm düğüm varlıklarını alır. |
| [getEntity()](#getEntity--) | Bu düğüme ekli ilk varlığı alır, ayarlanırsa diğer varlıkları temizler. |
| [getExcluded()](#getExcluded--) | Dışa aktarım sırasında bu düğümü ve tüm alt düğümleri/varlıkları hariç tutup tutmayacağını alır. |
| [getGlobalTransform()](#getGlobalTransform--) | Genel dönüşümü alır. |
| [getMaterial()](#getMaterial--) | Bu düğümle ilişkili ilk materyali alır, ayarlanırsa diğer materyalleri temizler. |
| [getMaterials()](#getMaterials--) | Bu düğümle ilişkili materyalleri alır. |
| [getMetaDatas()](#getMetaDatas--) | Bu düğümde tanımlanan meta verileri alır. |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | Üst düğümü alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getTransform()](#getTransform--) | Yerel dönüşümü alır. |
| [getVisible()](#getVisible--) | Düğümün gösterilip gösterilmeyeceğini alır. |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Düğüm altındaki her şeyi ayır ve mevcut düğüme ekle. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | XPath benzeri sorgu sözdizimini kullanarak mevcut düğüm altındaki birden fazla nesneyi seç. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | XPath benzeri sorgu sözdizimini kullanarak mevcut düğüm altındaki tek bir nesneyi seç. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Düğüm başına varlık bilgisi |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Bu düğüme ekli ilk varlığı ayarlar, ayarlanırsa diğer varlıkları temizler. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Dışa aktarım sırasında bu düğümü ve tüm alt düğümleri/varlıkları hariç tutup tutmayacağını ayarlar. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Bu düğümle ilişkili ilk materyali ayarlar, ayarlanırsa diğer materyalleri temizler. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Üst düğümü ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setVisible(boolean value)](#setVisible-boolean-) | Düğümü gösterecek şekilde ayarlar. |
| [toString()](#toString--) | Bu düğümün dize temsili alınır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Yeni bir [Node](../../com.aspose.threed/node) sınıfı örneği başlatır.

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Yeni bir [Node](../../com.aspose.threed/node) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |
| entity | [Entity](../../com.aspose.threed/entity) | Varsayılan varlık. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Yeni bir [Node](../../com.aspose.threed/node) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Tüm alt düğümlerden (geçerli düğüm dahil) geçer ve ziyaretçiyi düğümle birlikte çağırır. Ziyaretçi, false döndürerek yürütmeyi durdurabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Düğümü ziyaret etmek için ziyaretçi geri çağrısı. |

**Returns:**
boolean - true, ziyaretçinin yürütmeyi durdurduğu anlamına gelir. **Example:** Aşağıdaki kod bir sahnedeki tüm ağları nasıl alacağını gösterir

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


Bu düğüme bir alt düğüm ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Eklenecek alt düğüm **Example:** Aşağıdaki kod bir sahnedeki tüm ağları nasıl alacağını gösterir |

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


Düğüm'e bir varlık ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Düğüme eklenecek varlık |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Bir alt düğüm oluşturur

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


Verilen varlık ekli yeni bir alt düğüm oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Düğüme eklenmiş varsayılan varlık |

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


Verilen düğüm adıyla yeni bir alt düğüm oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodeName | java.lang.String | Yeni alt düğümün adı |

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


Verilen düğüm adıyla yeni bir alt düğüm oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodeName | java.lang.String | Yeni alt düğümün adı |
| entity | [Entity](../../com.aspose.threed/entity) | Düğüme eklenmiş varsayılan varlık |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Verilen düğüm adıyla yeni bir alt düğüm oluşturur ve belirtilen varlığı ve bir materyali ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodeName | java.lang.String | Yeni alt düğümün adı |
| entity | [Entity](../../com.aspose.threed/entity) | Düğüme eklenmiş varsayılan varlık |
| material | [Material](../../com.aspose.threed/material) | Düğüme eklenmiş materyal |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Genel dönüşümü değerlendir, geometrik dönüşümü dahil edip etmeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| withGeometricTransform | boolean | Geometrik dönüşümün gerekli olup olmadığı. |

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


Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty) veya native property(Identified by its name) olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyName | java.lang.String | Özellik adı. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Düğüm başına varlık bilgisi

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Düğümün sınırlayıcı kutusunu hesaplar

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Belirtilen indeksteki alt düğümü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | İndeks. |

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


Belirtilen ada sahip alt düğümü alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodeName | java.lang.String | Bulunacak alt düğüm adı. |

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


Alt düğümleri alır.

**Returns:**
java.util.List<com.aspose.threed.Node> - alt düğümler. **Example:** Aşağıdaki kod kök düğümün alt düğümünü nasıl listeleyeceğini gösterir

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


Tüm düğüm varlıklarını alır.

**Returns:**
java.util.List<com.aspose.threed.Entity> - tüm düğüm varlıkları.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Bu düğüme ekli ilk varlığı alır, ayarlanırsa diğer varlıkları temizler.

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


Dışa aktarım sırasında bu düğümü ve tüm alt düğümleri/varlıkları hariç tutup tutmayacağını alır.

**Returns:**
boolean - bu düğümü ve tüm alt düğüm/varlıkları dışa aktarma sırasında hariç tutup tutmayacağını belirler. **Example:** Aşağıdaki kod belirtilen düğümü dışa aktarmadan nasıl hariç tutacağını gösterir

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


Genel dönüşümü alır.

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


Bu düğümle ilişkili ilk materyali alır, ayarlanırsa diğer materyalleri temizler.

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


Bu düğümle ilişkili materyalleri alır.

**Returns:**
java.util.List<com.aspose.threed.Material> - bu düğümle ilişkili materyaller.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Bu düğümde tanımlanan meta verileri alır.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - bu düğümde tanımlanan meta veriler.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Üst düğümü alır.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Tüm özelliklerin koleksiyonunu alır.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Belirtilen özelliğin değerini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |

**Returns:**
java.lang.Object - Bulunan özelliğin değeri
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Yerel dönüşümü alır.

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


Düğümün gösterilip gösterilmeyeceğini alır.

**Returns:**
boolean - düğümü göstermek için. **Example:** Aşağıdaki kod görünmez bir düğümün nasıl oluşturulacağını gösterir

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


Düğüm altındaki her şeyi ayır ve mevcut düğüme ekle. **Example:** Aşağıdaki kod iki 3D dosyasını tek bir dosyada nasıl birleştireceğini gösterir

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parametre | Tür | Açıklama |
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


Dinamik bir özelliği kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


İsimle tanımlanan belirtilen özelliği kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


XPath benzeri sorgu sözdizimini kullanarak mevcut düğüm altındaki birden fazla nesneyi seç.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | XPath benzeri sorgu |

**Returns:**
java.util.ArrayList<java.lang.Object> - XPath benzeri sorguya birden çok nesne eşleşir.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


XPath benzeri sorgu sözdizimini kullanarak mevcut düğüm altındaki tek bir nesneyi seç.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | XPath benzeri sorgu |

**Returns:**
java.lang.Object - XPath benzeri sorgu tarafından bulunan nesne.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Düğüm başına varlık bilgisi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Yeni değer |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Bu düğüme ekli ilk varlığı ayarlar, ayarlanırsa diğer varlıkları temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Yeni değer **Örnek:** Aşağıdaki kod, kök düğümün altında yeni bir alt düğüm nasıl oluşturulacağını gösterir. |

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


Dışa aktarım sırasında bu düğümü ve tüm alt düğümleri/varlıkları hariç tutup tutmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Yeni değer **Örnek:** Aşağıdaki kod, belirtilen düğümün dışa aktarmadan nasıl hariç tutulacağını gösterir. |

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


Bu düğümle ilişkili ilk materyali ayarlar, ayarlanırsa diğer materyalleri temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Yeni değer **Örnek:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Üst düğümü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Yeni değer |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Belirtilen özelliğin değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |
| değer | java.lang.Object | Özelliğin değeri |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Düğümü gösterecek şekilde ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | Yeni değer **Örnek:** Aşağıdaki kod, görünmez bir düğümün nasıl oluşturulacağını gösterir. |

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


Bu düğümün dize temsili alınır.

**Returns:**
java.lang.String - Bu düğümün hata ayıklama için string temsili.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

