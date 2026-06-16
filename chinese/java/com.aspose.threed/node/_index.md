---
title: "Node"
second_title: "Aspose.3D for Java API 参考"
description: "表示场景图中的一个元素。"
type: docs
weight: 110
url: /zh/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

表示场景图中的一个元素。场景图是由 Node 对象组成的树。树的管理服务封装在此类中。请注意，Aspose.3D SDK 不会验证构建的场景图的有效性。调用者有责任确保不会在节点层次结构中生成循环图。除了树管理之外，此类还定义了描述对象在场景中位置所需的所有属性。这些信息包括基本的平移、旋转和缩放属性，以及用于枢轴、限制和 IK 关节属性（如刚度和阻尼）的更高级选项。首次创建时，Node 对象是"empty"（即：它是一个没有任何图形表示，仅包含位置信息的对象）。在此状态下，它可用于表示节点树结构中的父节点，但功能有限。此类对象的常规用法是为其添加一个实体以专门化节点（参见"Entity"）。实体本身是一个对象，并与 Node 关联。这也意味着同一实体可以在多个节点之间共享。Camera、Light、Mesh 等都是实体，并且它们都派生自基类 Entity。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Node()](#Node--) | 初始化一个新的 [Node](../../com.aspose.threed/node) 类实例。 |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | 初始化一个新的 [Node](../../com.aspose.threed/node) 类实例。 |
| [Node(String name)](#Node-java.lang.String-) | 初始化一个新的 [Node](../../com.aspose.threed/node) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | 遍历所有后代节点（包括当前节点），并使用该节点调用访问者。 |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | 向此节点添加子节点 |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | 向节点添加实体。 |
| [createChildNode()](#createChildNode--) | 创建子节点 |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | 创建一个附加了给定实体的新子节点 |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | 使用给定节点名称创建一个新子节点 |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | 使用给定节点名称创建一个新子节点 |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | 使用给定的节点名称创建一个新子节点，并附加指定的实体和材质 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | 评估全局变换，是否包括几何变换。 |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getAssetInfo()](#getAssetInfo--) | 每个节点的资源信息 |
| [getBoundingBox()](#getBoundingBox--) | 计算节点的包围盒 |
| [getChild(int index)](#getChild-int-) | 获取指定索引处的子节点。 |
| [getChild(String nodeName)](#getChild-java.lang.String-) | 获取具有指定名称的子节点 |
| [getChildNodes()](#getChildNodes--) | 获取子节点集合。 |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | 获取所有节点实体。 |
| [getEntity()](#getEntity--) | 获取附加到此节点的第一个实体，如果设置，将清除其他实体。 |
| [getExcluded()](#getExcluded--) | 获取在导出时是否排除此节点及其所有子节点/实体。 |
| [getGlobalTransform()](#getGlobalTransform--) | 获取全局变换。 |
| [getMaterial()](#getMaterial--) | 获取与此节点关联的第一个材质，如果设置，将清除其他材质 |
| [getMaterials()](#getMaterials--) | 获取与此节点关联的材质。 |
| [getMetaDatas()](#getMetaDatas--) | 获取此节点中定义的元数据。 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取父节点。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getTransform()](#getTransform--) | 获取局部变换。 |
| [getVisible()](#getVisible--) | 获取是否显示节点 |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | 分离节点下的所有内容并将其附加到当前节点。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | 使用类似 XPath 的查询语法选择当前节点下的多个对象。 |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | 使用类似 XPath 的查询语法选择当前节点下的单个对象。 |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | 每个节点的资源信息 |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | 设置附加到此节点的第一个实体，如果设置，将清除其他实体。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出时是否排除此节点及其所有子节点/实体。 |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | 设置此节点关联的第一个材质，如果设置，将清除其他材质 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置父节点。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setVisible(boolean value)](#setVisible-boolean-) | 设置显示节点。 |
| [toString()](#toString--) | 获取此节点的字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


初始化一个新的 [Node](../../com.aspose.threed/node) 类实例。

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


初始化一个新的 [Node](../../com.aspose.threed/node) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |
| entity | [Entity](../../com.aspose.threed/entity) | 默认实体。 |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


初始化一个新的 [Node](../../com.aspose.threed/node) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


遍历所有后代节点（包括当前节点），并将访问者调用到该节点。访问者可以通过返回 false 来中断遍历。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | 访问者回调以访问节点 |

**Returns:**
boolean - true 表示访问者已中断遍历。**示例：** 以下代码展示了如何从场景中获取所有网格。

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


向此节点添加子节点

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | 要附加的子节点 **示例：** 以下代码展示了如何从场景中获取所有网格。 |

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


向节点添加实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 要附加到节点的实体 |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


创建子节点

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


创建一个附加了给定实体的新子节点

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 默认附加到节点的实体 |

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


使用给定节点名称创建一个新子节点

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | java.lang.String | 新子节点的名称 |

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


使用给定节点名称创建一个新子节点

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | java.lang.String | 新子节点的名称 |
| entity | [Entity](../../com.aspose.threed/entity) | 默认附加到节点的实体 |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


使用给定的节点名称创建一个新子节点，并附加指定的实体和材质

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | java.lang.String | 新子节点的名称 |
| entity | [Entity](../../com.aspose.threed/entity) | 默认附加到节点的实体 |
| material | [Material](../../com.aspose.threed/material) | 附加到节点的材质 |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


评估全局变换，是否包括几何变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| withGeometricTransform | 布尔 | 是否需要几何变换。 |

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


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


每个节点的资源信息

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


计算节点的包围盒

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


获取指定索引处的子节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 索引。 |

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


获取具有指定名称的子节点

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | java.lang.String | 要查找的子节点名称。 |

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


获取子节点集合。

**Returns:**
java.util.List<com.aspose.threed.Node> - 子节点列表。**示例：** 以下代码展示了如何枚举根节点的子节点。

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


获取所有节点实体。

**Returns:**
java.util.List<com.aspose.threed.Entity> - 所有节点实体。
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


获取附加到此节点的第一个实体，如果设置，将清除其他实体。

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


获取在导出时是否排除此节点及其所有子节点/实体。

**Returns:**
boolean - 是否在导出时排除此节点及其所有子节点/实体。**示例：** 以下代码展示了如何在导出时排除指定节点。

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


获取全局变换。

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


获取与此节点关联的第一个材质，如果设置，将清除其他材质

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


获取与此节点关联的材质。

**Returns:**
java.util.List<com.aspose.threed.Material> - 与此节点关联的材质。
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


获取此节点中定义的元数据。

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - 此节点中定义的元数据。
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


获取父节点。

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


获取局部变换。

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


获取是否显示节点

**Returns:**
boolean - 是否显示节点。**示例：** 以下代码展示了如何创建一个不可见节点。

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


分离节点下的所有内容并将其附加到当前节点。**示例：** 以下代码展示了如何将两个 3D 文件合并为一个文件。

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| 参数 | 类型 | 描述 |
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


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


使用类似 XPath 的查询语法选择当前节点下的多个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 类似 XPath 的查询 |

**Returns:**
java.util.ArrayList<java.lang.Object> - 多个对象匹配 XPath 类查询。
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


使用类似 XPath 的查询语法选择当前节点下的单个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 类似 XPath 的查询 |

**Returns:**
java.lang.Object - 通过 XPath 类查询定位的对象。
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


每个节点的资源信息

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | 新值 |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


设置附加到此节点的第一个实体，如果设置，将清除其他实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | 新值 **Example:** 以下代码展示了如何在根节点下创建一个新的子节点 |

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


设置在导出时是否排除此节点及其所有子节点/实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | 布尔 | 新值 **Example:** 以下代码展示了如何从导出中排除指定节点 |

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


设置此节点关联的第一个材质，如果设置，将清除其他材质

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | 新值 **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


设置父节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


设置显示节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | 布尔 | 新值 **Example:** 以下代码展示了如何创建一个不可见节点 |

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


获取此节点的字符串表示。

**Returns:**
java.lang.String - 用于调试的此节点的字符串表示。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

