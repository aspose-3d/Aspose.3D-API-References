---
title: "Node"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "सीन ग्राफ़ में एक तत्व का प्रतिनिधित्व करता है।"
type: docs
weight: 110
url: /hi/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

सीन ग्राफ़ में एक तत्व का प्रतिनिधित्व करता है। एक सीन ग्राफ़ Node वस्तुओं का पेड़ है। पेड़ प्रबंधन सेवाएँ इस क्लास में ही समाहित हैं। ध्यान दें कि Aspose.3D SDK निर्मित सीन ग्राफ़ की वैधता की जाँच नहीं करता है। यह कॉलर की जिम्मेदारी है कि वह सुनिश्चित करे कि नोड पदानुक्रम में चक्रीय ग्राफ़ न बनें। पेड़ प्रबंधन के अलावा, यह क्लास वस्तु की सीन में स्थिति वर्णन करने के लिए आवश्यक सभी गुणों को परिभाषित करती है। इस जानकारी में बुनियादी ट्रांसलेशन, रोटेशन और स्केलिंग गुण तथा पिवट, लिमिट और IK जॉइंट्स के गुण जैसे कठोरता और डैम्पिंग जैसी उन्नत विकल्प शामिल हैं। जब पहली बार बनाया जाता है, Node वस्तु "खाली" होती है (अर्थात् यह एक ऐसी वस्तु है जिसमें कोई ग्राफिकल प्रतिनिधित्व नहीं है और केवल स्थिति जानकारी होती है)। इस स्थिति में, इसे नोड ट्री संरचना में पैरेंट को दर्शाने के लिए उपयोग किया जा सकता है, पर अधिक नहीं। इस प्रकार की वस्तुओं का सामान्य उपयोग उन्हें एक एंटिटी जोड़ना है जो नोड को विशेष बनाती है ("Entity" देखें)। एंटिटी स्वयं में एक वस्तु है और Node से जुड़ी होती है। इसका अर्थ यह भी है कि वही एंटिटी कई नोड्स में साझा की जा सकती है। Camera, Light, Mesh आदि सभी एंटिटी हैं और सभी बेस क्लास Entity से व्युत्पन्न हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Node()](#Node--) | [Node](../../com.aspose.threed/node) क्लास का नया उदाहरण आरंभ करता है। |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | [Node](../../com.aspose.threed/node) क्लास का नया उदाहरण आरंभ करता है। |
| [Node(String name)](#Node-java.lang.String-) | [Node](../../com.aspose.threed/node) क्लास का नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | सभी अवनति नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और विज़िटर को नोड के साथ कॉल करता है। |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | इस नोड में एक चाइल्ड नोड जोड़ें |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | नोड में एक एंटिटी जोड़ें। |
| [createChildNode()](#createChildNode--) | एक चाइल्ड नोड बनाता है |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | दिए गए एंटिटी संलग्न के साथ एक नया चाइल्ड नोड बनाएं |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं, और निर्दिष्ट एंटिटी और एक मैटेरियल संलग्न करें |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करें, ज्यामितीय ट्रांसफ़ॉर्म शामिल करें या नहीं। |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAssetInfo()](#getAssetInfo--) | प्रति-नोड एसेट जानकारी |
| [getBoundingBox()](#getBoundingBox--) | नोड का बाउंडिंग बॉक्स गणना करें |
| [getChild(int index)](#getChild-int-) | निर्दिष्ट इंडेक्स पर चाइल्ड नोड प्राप्त करता है। |
| [getChild(String nodeName)](#getChild-java.lang.String-) | निर्दिष्ट नाम वाले चाइल्ड नोड को प्राप्त करता है |
| [getChildNodes()](#getChildNodes--) | चाइल्ड नोड्स को प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | सभी नोड एंटिटीज़ को प्राप्त करता है। |
| [getEntity()](#getEntity--) | इस नोड से जुड़ी पहली एंटिटी को प्राप्त करता है, यदि सेट किया गया है तो अन्य एंटिटीज़ को साफ़ कर देगा। |
| [getExcluded()](#getExcluded--) | एक्सपोर्ट करते समय इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखने की स्थिति प्राप्त करता है। |
| [getGlobalTransform()](#getGlobalTransform--) | ग्लोबल ट्रांसफ़ॉर्म प्राप्त करता है। |
| [getMaterial()](#getMaterial--) | इस नोड से जुड़ा पहला मैटेरियल प्राप्त करता है, यदि सेट किया गया है तो अन्य मैटेरियल्स को साफ़ कर देगा |
| [getMaterials()](#getMaterials--) | इस नोड से जुड़े मैटेरियल्स को प्राप्त करता है। |
| [getMetaDatas()](#getMetaDatas--) | इस नोड में परिभाषित मेटा डेटा को प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पैरेंट नोड को प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getScene()](#getScene--) | इस ऑब्जेक्ट से संबंधित सीन प्राप्त करता है |
| [getTransform()](#getTransform--) | लोकल ट्रांसफ़ॉर्म प्राप्त करता है। |
| [getVisible()](#getVisible--) | नोड को दिखाने के लिए प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | नोड के नीचे की सभी चीज़ों को डिटैच करें और उन्हें वर्तमान नोड से संलग्न करें। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | XPath-समतुल्य क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के तहत कई ऑब्जेक्ट्स चुनें। |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | XPath-समतुल्य क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के तहत एकल ऑब्जेक्ट चुनें। |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | प्रति-नोड एसेट जानकारी |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | इस नोड से जुड़ी पहली एंटिटी सेट करता है, यदि सेट किया गया है तो अन्य एंटिटीज़ को साफ़ कर देगा। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | एक्सपोर्ट करते समय इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखने की स्थिति सेट करता है। |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | इस नोड से जुड़ी पहली सामग्री सेट करता है, यदि सेट किया जाता है तो अन्य सामग्री साफ़ हो जाएगी। |
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


[Node](../../com.aspose.threed/node) क्लास का नया उदाहरण आरंभ करता है।

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


[Node](../../com.aspose.threed/node) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | नाम। |
| entity | [Entity](../../com.aspose.threed/entity) | डिफ़ॉल्ट एंटिटी। |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


[Node](../../com.aspose.threed/node) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | नाम। |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


सभी वंशज नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और नोड के साथ विज़िटर को कॉल करता है। विज़िटर false लौटाकर वॉक-थ्रू को रोक सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | नोड को विज़िट करने के लिए विज़िटर कॉलबैक। |

**Returns:**
बूलियन - true का मतलब है कि विज़िटर ने वॉक-थ्रू को तोड़ दिया है। **उदाहरण:** निम्नलिखित कोड दिखाता है कि सीन से सभी मेष कैसे प्राप्त करें।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | संलग्न किए जाने वाले चाइल्ड नोड **उदाहरण:** निम्नलिखित कोड दिखाता है कि सीन से सभी मेष कैसे प्राप्त करें। |

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


नोड में एक एंटिटी जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | नोड से जुड़ने वाली एंटिटी। |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


एक चाइल्ड नोड बनाता है

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


दिए गए एंटिटी संलग्न के साथ एक नया चाइल्ड नोड बनाएं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | नोड से जुड़ी डिफ़ॉल्ट एंटिटी। |

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


दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | नए चाइल्ड नोड का नाम। |

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


दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | नए चाइल्ड नोड का नाम। |
| entity | [Entity](../../com.aspose.threed/entity) | नोड से जुड़ी डिफ़ॉल्ट एंटिटी। |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं, और निर्दिष्ट एंटिटी और एक मैटेरियल संलग्न करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | नए चाइल्ड नोड का नाम। |
| entity | [Entity](../../com.aspose.threed/entity) | नोड से जुड़ी डिफ़ॉल्ट एंटिटी। |
| material | [Material](../../com.aspose.threed/material) | नोड से जुड़ी सामग्री। |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करें, ज्यामितीय ट्रांसफ़ॉर्म शामिल करें या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


प्रति-नोड एसेट जानकारी

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


नोड का बाउंडिंग बॉक्स गणना करें

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


निर्दिष्ट इंडेक्स पर चाइल्ड नोड प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


निर्दिष्ट नाम वाले चाइल्ड नोड को प्राप्त करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nodeName | java.lang.String | खोजने के लिए चाइल्ड का नाम। |

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


चाइल्ड नोड्स को प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.Node> - चाइल्ड नोड्स। **उदाहरण:** निम्नलिखित कोड दिखाता है कि रूट नोड के चाइल्ड नोड को कैसे सूचीबद्ध करें।

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


सभी नोड एंटिटीज़ को प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.Entity> - सभी नोड एंटिटीज़।
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


इस नोड से जुड़ी पहली एंटिटी को प्राप्त करता है, यदि सेट किया गया है तो अन्य एंटिटीज़ को साफ़ कर देगा।

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


एक्सपोर्ट करते समय इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखने की स्थिति प्राप्त करता है।

**Returns:**
बूलियन - निर्यात के दौरान इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखने के लिए। **उदाहरण:** निम्नलिखित कोड दिखाता है कि निर्यात से निर्दिष्ट नोड को कैसे बाहर रखा जाए।

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


ग्लोबल ट्रांसफ़ॉर्म प्राप्त करता है।

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


इस नोड से जुड़ा पहला मैटेरियल प्राप्त करता है, यदि सेट किया गया है तो अन्य मैटेरियल्स को साफ़ कर देगा

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


इस नोड से जुड़े मैटेरियल्स को प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.Material> - इस नोड से जुड़ी सामग्री।
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


इस नोड में परिभाषित मेटा डेटा को प्राप्त करता है।

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


पैरेंट नोड को प्राप्त करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getScene() {#getScene--}
```
public Scene getScene()
```


इस ऑब्जेक्ट से संबंधित सीन प्राप्त करता है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


लोकल ट्रांसफ़ॉर्म प्राप्त करता है।

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


नोड को दिखाने के लिए प्राप्त करता है

**Returns:**
बूलियन - नोड को दिखाने के लिए **उदाहरण:** निम्नलिखित कोड दिखाता है कि एक अदृश्य नोड कैसे बनाया जाए।

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


नोड के नीचे की सभी चीज़ों को अलग करें और उन्हें वर्तमान नोड से संलग्न करें। **उदाहरण:** निम्नलिखित कोड दिखाता है कि दो 3D फ़ाइलों को एक फ़ाइल में कैसे मिलाया जाए।

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


XPath-समतुल्य क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के तहत कई ऑब्जेक्ट्स चुनें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पथ | java.lang.String | XPath जैसी क्वेरी। |

**Returns:**
java.util.ArrayList<java.lang.Object> - कई ऑब्जेक्ट XPath-जैसे क्वेरी से मेल खाते हैं।
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


XPath-समतुल्य क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के तहत एकल ऑब्जेक्ट चुनें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पथ | java.lang.String | XPath जैसी क्वेरी। |

**Returns:**
java.lang.Object - ऑब्जेक्ट XPath-जैसे क्वेरी द्वारा स्थित किया गया है।
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


प्रति-नोड एसेट जानकारी

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | नया मान |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


इस नोड से जुड़ी पहली एंटिटी सेट करता है, यदि सेट किया गया है तो अन्य एंटिटीज़ को साफ़ कर देगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | नया मान **Example:** निम्नलिखित कोड दिखाता है कि रूट नोड के तहत नया चाइल्ड नोड कैसे बनाया जाए |

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


एक्सपोर्ट करते समय इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखने की स्थिति सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | नया मान **Example:** निम्नलिखित कोड दिखाता है कि निर्यात से निर्दिष्ट नोड को कैसे बाहर रखा जाए |

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


इस नोड से जुड़ी पहली सामग्री सेट करता है, यदि सेट किया जाता है तो अन्य सामग्री साफ़ हो जाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | नया मान **Example:** |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


पैरेंट नोड सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


नोड को दिखाने के लिए सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | नया मान **Example:** निम्नलिखित कोड दिखाता है कि एक अदृश्य नोड कैसे बनाया जाए |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

