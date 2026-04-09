---
title: Node
second_title: Aspose.3D for Java API Reference
description: सीन ग्राफ़ में एक तत्व का प्रतिनिधित्व करता है।
type: docs
weight: 110
url: /hi/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

सीन ग्राफ़ में एक तत्व का प्रतिनिधित्व करता है। सीन ग्राफ़ Node वस्तुओं का एक वृक्ष है। वृक्ष प्रबंधन सेवाएँ इस वर्ग में स्वयं समाहित हैं। ध्यान दें कि Aspose.3D SDK निर्मित सीन ग्राफ़ की वैधता का परीक्षण नहीं करता है। यह कॉलर की जिम्मेदारी है कि वह सुनिश्चित करे कि नोड पदानुक्रम में चक्रीय ग्राफ़ न बनें। वृक्ष प्रबंधन के अलावा, यह वर्ग वस्तु की स्थिति का वर्णन करने के लिए आवश्यक सभी गुणों को परिभाषित करता है। इस जानकारी में मूल Translation, Rotation और Scaling गुण तथा पिवट, सीमाएँ और IK जॉइंट्स के उन्नत विकल्प शामिल हैं, जैसे कठोरता और डैम्पिंग। जब पहली बार बनाया जाता है, तो Node वस्तु "empty" (अर्थात् यह एक ऐसी वस्तु है जिसमें कोई ग्राफिकल प्रतिनिधित्व नहीं है और केवल स्थिति जानकारी होती है) होती है। इस स्थिति में, इसे नोड ट्री संरचना में पैरेंट को दर्शाने के लिए उपयोग किया जा सकता है, लेकिन अधिक नहीं। इस प्रकार की वस्तुओं का सामान्य उपयोग उन्हें एक entity जोड़ना है जो नोड को विशेष बनाता है ("Entity" देखें)। entity स्वयं में एक वस्तु है और Node से जुड़ी होती है। इसका मतलब यह भी है कि वही entity कई नोड्स के बीच साझा की जा सकती है। Camera, Light, Mesh आदि सभी entity हैं और सभी बेस क्लास Entity से व्युत्पन्न हैं।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Node()](#Node--) | [Node](../../com.aspose.threed/node) वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | [Node](../../com.aspose.threed/node) वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Node(String name)](#Node-java.lang.String-) | [Node](../../com.aspose.threed/node) वर्ग का एक नया उदाहरण आरंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | सभी वंशज नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और नोड के साथ विज़िटर को कॉल करता है। |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | इस नोड में एक चाइल्ड नोड जोड़ें |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | नोड में एक entity जोड़ें। |
| [createChildNode()](#createChildNode--) | एक child node बनाता है |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | दिए गए entity को संलग्न करके एक नया child node बनाएं |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | दिए गए node नाम के साथ एक नया child node बनाएं |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | दिए गए node नाम के साथ एक नया child node बनाएं |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | दिए गए node नाम के साथ एक नया child node बनाएं, और निर्दिष्ट entity और एक material संलग्न करें |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | global transform का मूल्यांकन करें, geometric transform को शामिल करें या नहीं. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAssetInfo()](#getAssetInfo--) | प्रति-node asset जानकारी |
| [getBoundingBox()](#getBoundingBox--) | node का bounding box गणना करें |
| [getChild(int index)](#getChild-int-) | निर्दिष्ट index पर child node प्राप्त करता है. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | निर्दिष्ट नाम वाले child node को प्राप्त करता है |
| [getChildNodes()](#getChildNodes--) | children nodes को प्राप्त करता है. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | सभी node entities को प्राप्त करता है. |
| [getEntity()](#getEntity--) | इस node से संलग्न पहला entity प्राप्त करता है, यदि सेट किया गया, तो अन्य entities को साफ़ कर देगा. |
| [getExcluded()](#getExcluded--) | एक्सपोर्ट करते समय इस node और सभी child nodes/entities को बाहर रखने की स्थिति प्राप्त करता है. |
| [getGlobalTransform()](#getGlobalTransform--) | global transform को प्राप्त करता है. |
| [getMaterial()](#getMaterial--) | इस node से जुड़ा पहला material प्राप्त करता है, यदि सेट किया गया, तो अन्य materials को साफ़ कर देगा |
| [getMaterials()](#getMaterials--) | इस node से जुड़े materials को प्राप्त करता है. |
| [getMetaDatas()](#getMetaDatas--) | इस node में परिभाषित meta data को प्राप्त करता है. |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | parent node को प्राप्त करता है. |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getTransform()](#getTransform--) | local transform को प्राप्त करता है. |
| [getVisible()](#getVisible--) | node को दिखाने के लिए प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | node के तहत सभी चीज़ों को अलग करें और उन्हें वर्तमान node से संलग्न करें. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | XPath-like query syntax का उपयोग करके वर्तमान node के तहत कई objects चुनें. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | XPath-like query syntax का उपयोग करके वर्तमान node के तहत एकल object चुनें. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | प्रति-node asset जानकारी |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | इस node से संलग्न पहला entity सेट करता है, यदि सेट किया गया, तो अन्य entities को साफ़ कर देगा. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | एक्सपोर्ट करते समय इस node और सभी child nodes/entities को बाहर रखने की स्थिति सेट करता है. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | इस नोड से जुड़ी पहली सामग्री सेट करता है, यदि सेट किया जाता है, तो अन्य सामग्री साफ़ हो जाएँगी |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पैरेंट नोड सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setVisible(boolean value)](#setVisible-boolean-) | नोड को दिखाने के लिए सेट करता है। |
| [toString()](#toString--) | इस नोड का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


[Node](../../com.aspose.threed/node) वर्ग का एक नया उदाहरण आरंभ करता है।

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


[Node](../../com.aspose.threed/node) वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |
| entity | [Entity](../../com.aspose.threed/entity) | डिफ़ॉल्ट एंटिटी। |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


[Node](../../com.aspose.threed/node) वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


सभी उत्तराधिकारी नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और विज़िटर को नोड के साथ कॉल करता है। विज़िटर false लौटाकर वॉक-थ्रू को रोक सकता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | नोड को विज़िट करने के लिए विज़िटर कॉलबैक। |

**Returns:**
boolean - true का मतलब है कि विज़िटर ने वॉक-थ्रू को तोड़ दिया है। **Example:** निम्नलिखित कोड दिखाता है कि सीन से सभी मेष कैसे प्राप्त करें

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


इस नोड में एक चाइल्ड नोड जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | जुड़ने वाला चाइल्ड नोड **Example:** निम्नलिखित कोड दिखाता है कि सीन से सभी मेष कैसे प्राप्त करें |

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


नोड में एक entity जोड़ें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | नोड से जुड़ने वाली एंटिटी |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


एक child node बनाता है

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


दिए गए entity को संलग्न करके एक नया child node बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | डिफ़ॉल्ट एंटिटी नोड से जुड़ी हुई |

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


दिए गए node नाम के साथ एक नया child node बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | नए चाइल्ड नोड का नाम |

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


दिए गए node नाम के साथ एक नया child node बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | नए चाइल्ड नोड का नाम |
| entity | [Entity](../../com.aspose.threed/entity) | डिफ़ॉल्ट एंटिटी नोड से जुड़ी हुई |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


दिए गए node नाम के साथ एक नया child node बनाएं, और निर्दिष्ट entity और एक material संलग्न करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | नए चाइल्ड नोड का नाम |
| entity | [Entity](../../com.aspose.threed/entity) | डिफ़ॉल्ट एंटिटी नोड से जुड़ी हुई |
| material | [Material](../../com.aspose.threed/material) | नोड से जुड़ी हुई सामग्री |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


global transform का मूल्यांकन करें, geometric transform को शामिल करें या नहीं.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| withGeometricTransform | boolean | क्या ज्यामितीय ट्रांसफ़ॉर्म की आवश्यकता है। |

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


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


प्रति-node asset जानकारी

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


node का bounding box गणना करें

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


निर्दिष्ट index पर child node प्राप्त करता है.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | सूचकांक। |

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


निर्दिष्ट नाम वाले child node को प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | खोजने के लिए चाइल्ड नाम। |

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


children nodes को प्राप्त करता है.

**Returns:**
java.util.List<com.aspose.threed.Node> - चाइल्ड नोड्स। **Example:** निम्नलिखित कोड दिखाता है कि रूट नोड के चाइल्ड नोड को कैसे एने्यूमरेट करें

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


सभी node entities को प्राप्त करता है.

**Returns:**
java.util.List<com.aspose.threed.Entity> - सभी नोड एंटिटीज़।
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


इस node से संलग्न पहला entity प्राप्त करता है, यदि सेट किया गया, तो अन्य entities को साफ़ कर देगा.

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


एक्सपोर्ट करते समय इस node और सभी child nodes/entities को बाहर रखने की स्थिति प्राप्त करता है.

**Returns:**
boolean - निर्यात के दौरान इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखने के लिए। **Example:** निम्नलिखित कोड दिखाता है कि निर्यात से निर्दिष्ट नोड को कैसे बाहर रखें

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


global transform को प्राप्त करता है.

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


इस node से जुड़ा पहला material प्राप्त करता है, यदि सेट किया गया, तो अन्य materials को साफ़ कर देगा

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


इस node से जुड़े materials को प्राप्त करता है.

**Returns:**
java.util.List<com.aspose.threed.Material> - इस नोड से जुड़ी सामग्री।
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


इस node में परिभाषित meta data को प्राप्त करता है.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - इस नोड में परिभाषित मेटा डेटा।
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


parent node को प्राप्त करता है.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है।

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getScene() {#getScene--}
```
public Scene getScene()
```


उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


local transform को प्राप्त करता है.

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


node को दिखाने के लिए प्राप्त करता है

**Returns:**
boolean - नोड को दिखाने के लिए। **Example:** निम्नलिखित कोड दिखाता है कि एक अदृश्य नोड कैसे बनाया जाए

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


नोड के नीचे की सभी चीज़ों को डिटैच करें और उन्हें वर्तमान नोड से जोड़ें। **Example:** निम्नलिखित कोड दिखाता है कि दो 3D फ़ाइलों को एक फ़ाइल में कैसे मर्ज किया जाए

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parameter | Type | विवरण |
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


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


XPath-like query syntax का उपयोग करके वर्तमान node के तहत कई objects चुनें.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| path | java.lang.String | XPath जैसी क्वेरी |

**Returns:**
java.util.ArrayList<java.lang.Object> - कई ऑब्जेक्ट XPath-समतुल्य क्वेरी से मेल खाते हैं।
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


XPath-like query syntax का उपयोग करके वर्तमान node के तहत एकल object चुनें.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| path | java.lang.String | XPath जैसी क्वेरी |

**Returns:**
java.lang.Object - XPath-समतुल्य क्वेरी द्वारा पाए गए ऑब्जेक्ट।
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


प्रति-node asset जानकारी

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | नया मान |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


इस node से संलग्न पहला entity सेट करता है, यदि सेट किया गया, तो अन्य entities को साफ़ कर देगा.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | नई मान **Example:** निम्नलिखित कोड दिखाता है कि रूट नोड के तहत नया चाइल्ड नोड कैसे बनाएं |

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


एक्सपोर्ट करते समय इस node और सभी child nodes/entities को बाहर रखने की स्थिति सेट करता है.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | नई मान **Example:** निम्नलिखित कोड दिखाता है कि निर्यात से निर्दिष्ट नोड को कैसे बाहर रखें |

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


इस नोड से जुड़ी पहली सामग्री सेट करता है, यदि सेट किया जाता है, तो अन्य सामग्री साफ़ हो जाएँगी

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | नई मान **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


पैरेंट नोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


नोड को दिखाने के लिए सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | नई मान **Example:** निम्नलिखित कोड दिखाता है कि अदृश्य नोड कैसे बनाएं |

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


इस नोड का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है।

**Returns:**
java.lang.String - डिबगिंग के लिए इस नोड का स्ट्रिंग प्रतिनिधित्व।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

