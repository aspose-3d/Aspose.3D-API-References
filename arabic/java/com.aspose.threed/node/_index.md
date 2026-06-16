---
title: "Node"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يمثل عنصرًا في رسم المشهد."
type: docs
weight: 110
url: /ar/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

يمثل عنصرًا في رسم المشهد. رسم المشهد هو شجرة من كائنات Node. خدمات إدارة الشجرة مدمجة في هذه الفئة. لاحظ أن Aspose.3D SDK لا يتحقق من صحة رسم المشهد المُنشأ. تقع مسؤولية المتصل في التأكد من عدم توليد رسومات بيانية دورية في تسلسل العقد. بالإضافة إلى إدارة الشجرة، تُعرّف هذه الفئة جميع الخصائص المطلوبة لوصف موضع الكائن في المشهد. تتضمن هذه المعلومات الخصائص الأساسية Translation و Rotation و Scaling والخيارات المتقدمة للمحاور، والحدود، وخصائص مفاصل IK مثل الصلابة والتخميد. عند إنشائها لأول مرة، يكون كائن Node \"empty\" (أي: هو كائن بدون أي تمثيل رسومي يحتوي فقط على معلومات الموضع). في هذه الحالة، يمكن استخدامه لتمثيل الأبواب في هيكل شجرة العقد ولكن ليس أكثر من ذلك. الاستخدام العادي لهذا النوع من الكائنات هو إضافة كيان يخصص العقدة (انظر \"Entity\"). الكيان هو كائن بحد ذاته ومربوط بـ Node. وهذا يعني أيضًا أن نفس الكيان يمكن مشاركته بين عدة عقد. الكاميرا، الضوء، الشبكة، إلخ... كلها كيانات وجميعها مشتقة من الفئة الأساسية Entity.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Node()](#Node--) | يُنشئ مثيلًا جديدًا من الفئة [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | يُنشئ مثيلًا جديدًا من الفئة [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | يُنشئ مثيلًا جديدًا من الفئة [Node](../../com.aspose.threed/node). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | يتجول عبر جميع العقد التابعة (بما في ذلك العقدة الحالية) ويستدعي الزائر مع العقدة. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | أضف عقدة فرعية إلى هذه العقدة |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | أضف كيانًا إلى العقدة. |
| [createChildNode()](#createChildNode--) | ينشئ عقدة فرعية |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | إنشاء عقدة فرعية جديدة مع الكيان المحدد مرفق |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة، وإرفاق الكيان المحدد ومادة |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | تقييم التحويل العالمي، تضمين التحويل الهندسي أم لا. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAssetInfo()](#getAssetInfo--) | معلومات الأصول لكل عقدة |
| [getBoundingBox()](#getBoundingBox--) | حساب الصندوق المحيط للعقدة |
| [getChild(int index)](#getChild-int-) | يحصل على العقدة الفرعية عند الفهرس المحدد. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | يحصل على العقدة الفرعية بالاسم المحدد |
| [getChildNodes()](#getChildNodes--) | يحصل على العقد الفرعية. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | يحصل على جميع كيانات العقدة. |
| [getEntity()](#getEntity--) | يحصل على أول كيان مرفق بهذه العقدة، إذا تم الضبط، سيتم مسح الكيانات الأخرى. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير. |
| [getGlobalTransform()](#getGlobalTransform--) | يحصل على التحويل العالمي. |
| [getMaterial()](#getMaterial--) | يحصل على أول مادة مرتبطة بهذه العقدة، إذا تم الضبط، سيتم مسح المواد الأخرى |
| [getMaterials()](#getMaterials--) | يحصل على المواد المرتبطة بهذه العقدة. |
| [getMetaDatas()](#getMetaDatas--) | يحصل على البيانات الوصفية المعرفة في هذه العقدة. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getParentNode()](#getParentNode--) | يحصل على العقدة الأصل. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getTransform()](#getTransform--) | يحصل على التحويل المحلي. |
| [getVisible()](#getVisible--) | يحصل على إظهار العقدة |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | فصل كل شيء تحت العقدة وإرفاقه إلى العقدة الحالية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | اختيار عدة كائنات تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | اختيار كائن واحد تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | معلومات الأصول لكل عقدة |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | يضبط أول كيان مرفق بهذه العقدة، إذا تم الضبط، سيتم مسح الكيانات الأخرى. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | يضبط المادة الأولى المرتبطة بهذه العقدة، إذا تم الضبط، سيُمسح باقي المواد |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط العقدة الأصلية. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setVisible(boolean value)](#setVisible-boolean-) | يضبط لإظهار العقدة |
| [toString()](#toString--) | يحصل على تمثيل النص لهذه العقدة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


يُنشئ مثيلًا جديدًا من الفئة [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


يُنشئ مثيلًا جديدًا من الفئة [Node](../../com.aspose.threed/node).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |
| entity | [Entity](../../com.aspose.threed/entity) | الكيان الافتراضي. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


يُنشئ مثيلًا جديدًا من الفئة [Node](../../com.aspose.threed/node).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


يتجول عبر جميع العقد التابعة (بما في ذلك العقدة الحالية) ويستدعي الزائر مع العقدة. يمكن للزائر إيقاف التجول بإرجاع false

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | استدعاء رد النداء للزائر لزيارة العقدة |

**Returns:**
منطقي - true يعني أن الزائر قد كسر التجول. **Example:** الكود التالي يوضح كيفية الحصول على جميع الشبكات من مشهد

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


أضف عقدة فرعية إلى هذه العقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | العقدة الفرعية التي سيتم إرفاقها **Example:** الكود التالي يوضح كيفية الحصول على جميع الشبكات من مشهد |

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


أضف كيانًا إلى العقدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | الكيان الذي سيتم إرفاقه بالعقدة |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


ينشئ عقدة فرعية

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


إنشاء عقدة فرعية جديدة مع الكيان المحدد مرفق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | الكيان الافتراضي المرفق بالعقدة |

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


إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeName | java.lang.String | اسم العقدة الفرعية الجديدة |

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


إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeName | java.lang.String | اسم العقدة الفرعية الجديدة |
| entity | [Entity](../../com.aspose.threed/entity) | الكيان الافتراضي المرفق بالعقدة |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


إنشاء عقدة فرعية جديدة بالاسم المحدد للعقدة، وإرفاق الكيان المحدد ومادة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeName | java.lang.String | اسم العقدة الفرعية الجديدة |
| entity | [Entity](../../com.aspose.threed/entity) | الكيان الافتراضي المرفق بالعقدة |
| material | [Material](../../com.aspose.threed/material) | المادة المرفقة بالعقدة |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


تقييم التحويل العالمي، تضمين التحويل الهندسي أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| withGeometricTransform | boolean | ما إذا كان التحويل الهندسي مطلوبًا. |

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


يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyName | java.lang.String | اسم الخاصية. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


معلومات الأصول لكل عقدة

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


حساب الصندوق المحيط للعقدة

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


يحصل على العقدة الفرعية عند الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | الفهرس. |

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


يحصل على العقدة الفرعية بالاسم المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeName | java.lang.String | اسم العقدة الفرعية للبحث عنه. |

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


يحصل على العقد الفرعية.

**Returns:**
java.util.List<com.aspose.threed.Node> - العقد الفرعية. **Example:** الكود التالي يوضح كيفية تعداد العقدة الفرعية للجذر

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


يحصل على جميع كيانات العقدة.

**Returns:**
java.util.List<com.aspose.threed.Entity> - جميع كيانات العقدة.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


يحصل على أول كيان مرفق بهذه العقدة، إذا تم الضبط، سيتم مسح الكيانات الأخرى.

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


يحصل على ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير.

**Returns:**
منطقي - ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير. **Example:** الكود التالي يوضح كيفية استبعاد العقدة المحددة من التصدير

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


يحصل على التحويل العالمي.

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


يحصل على أول مادة مرتبطة بهذه العقدة، إذا تم الضبط، سيتم مسح المواد الأخرى

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


يحصل على المواد المرتبطة بهذه العقدة.

**Returns:**
java.util.List<com.aspose.threed.Material> - المواد المرتبطة بهذه العقدة.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


يحصل على البيانات الوصفية المعرفة في هذه العقدة.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - البيانات الوصفية المعرفة في هذه العقدة.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


يحصل على العقدة الأصل.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


يحصل على مجموعة جميع الخصائص.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


احصل على قيمة الخاصية المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |

**Returns:**
java.lang.Object - قيمة الخاصية التي تم العثور عليها
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


يحصل على التحويل المحلي.

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


يحصل على إظهار العقدة

**Returns:**
منطقي - لإظهار العقدة **Example:** الكود التالي يوضح كيفية إنشاء عقدة غير مرئية

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


افصل كل شيء تحت العقدة وأرفقه بالعقدة الحالية. **Example:** الكود التالي يوضح كيفية دمج ملفين ثلاثيين الأبعاد في ملف واحد

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| معامل | نوع | الوصف |
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


يزيل خاصية ديناميكية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


إزالة الخاصية المحددة التي تم التعرف عليها بالاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


اختيار عدة كائنات تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | الاستعلام الشبيه بـ XPath |

**Returns:**
java.util.ArrayList<java.lang.Object> - عدة كائنات تطابق استعلام شبيه بـ XPath.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


اختيار كائن واحد تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | الاستعلام الشبيه بـ XPath |

**Returns:**
java.lang.Object - الكائن الموجود بواسطة استعلام شبيه بـ XPath.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


معلومات الأصول لكل عقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | القيمة الجديدة |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


يضبط أول كيان مرفق بهذه العقدة، إذا تم الضبط، سيتم مسح الكيانات الأخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | قيمة جديدة **Example:** يوضح الكود التالي كيفية إنشاء عقدة فرعية جديدة تحت العقدة الجذرية |

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


يضبط ما إذا كان يجب استبعاد هذه العقدة وجميع العقد/الكيانات الفرعية أثناء التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | قيمة جديدة **Example:** يوضح الكود التالي كيفية استبعاد العقدة المحددة من التصدير |

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


يضبط المادة الأولى المرتبطة بهذه العقدة، إذا تم الضبط، سيُمسح باقي المواد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | قيمة جديدة **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


يضبط العقدة الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | القيمة الجديدة |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


يضبط قيمة الخاصية المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |
| القيمة | java.lang.Object | قيمة الخاصية |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


يضبط لإظهار العقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | قيمة جديدة **Example:** يوضح الكود التالي كيفية إنشاء عقدة غير مرئية |

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


يحصل على تمثيل النص لهذه العقدة.

**Returns:**
java.lang.String - تمثيل النص لهذا العقدة لأغراض التصحيح.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

