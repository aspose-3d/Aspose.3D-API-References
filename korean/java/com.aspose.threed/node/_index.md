---
title: Node
second_title: Aspose.3D for Java API 레퍼런스
description: 씬 그래프의 요소를 나타냅니다.
type: docs
weight: 110
url: /ko/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

씬 그래프의 요소를 나타냅니다. 씬 그래프는 Node 객체들의 트리입니다. 트리 관리 서비스는 이 클래스에 자체적으로 포함되어 있습니다. Aspose.3D SDK는 구성된 씬 그래프의 유효성을 검사하지 않음을 유의하십시오. 호출자는 노드 계층 구조에서 순환 그래프가 생성되지 않도록 보장할 책임이 있습니다. 트리 관리 외에도, 이 클래스는 씬 내 객체의 위치를 설명하는 데 필요한 모든 속성을 정의합니다. 이 정보에는 기본적인 Translation, Rotation, Scaling 속성과 피벗, 제한, IK 조인트 속성(예: 강성 및 감쇠)과 같은 고급 옵션이 포함됩니다. 처음 생성될 때 Node 객체는 "empty"(즉, 그래픽 표현이 없고 위치 정보만 포함하는 객체)입니다. 이 상태에서는 노드 트리 구조에서 부모를 나타내는 데 사용할 수 있지만 그 이상은 사용할 수 없습니다. 이러한 유형의 객체의 일반적인 사용은 노드를 특수화할 엔터티를 추가하는 것입니다(예: "Entity"를 참조). 엔터티는 자체 객체이며 Node에 연결됩니다. 이는 동일한 엔터티가 여러 노드 간에 공유될 수 있음을 의미합니다. Camera, Light, Mesh 등은 모두 엔터티이며 모두 기본 클래스 Entity에서 파생됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Node()](#Node--) | [Node](../../com.aspose.threed/node) 클래스의 새 인스턴스를 초기화합니다. |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | [Node](../../com.aspose.threed/node) 클래스의 새 인스턴스를 초기화합니다. |
| [Node(String name)](#Node-java.lang.String-) | [Node](../../com.aspose.threed/node) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | 모든 하위 노드(현재 노드 포함)를 순회하며 방문자에게 노드를 전달합니다. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | 이 노드에 자식 노드를 추가합니다. |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | 노드에 엔터티를 추가합니다. |
| [createChildNode()](#createChildNode--) | 자식 노드를 생성합니다 |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | 지정된 엔터티가 연결된 새 자식 노드를 생성합니다 |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | 지정된 노드 이름으로 새 자식 노드를 생성합니다 |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | 지정된 노드 이름으로 새 자식 노드를 생성합니다 |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | 지정된 노드 이름으로 새 자식 노드를 생성하고, 지정된 엔터티와 재료를 연결합니다 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | 전역 변환을 평가하고, 기하학적 변환을 포함할지 여부를 지정합니다. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getAssetInfo()](#getAssetInfo--) | 노드별 자산 정보 |
| [getBoundingBox()](#getBoundingBox--) | 노드의 경계 상자를 계산합니다 |
| [getChild(int index)](#getChild-int-) | 지정된 인덱스의 자식 노드를 가져옵니다. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | 지정된 이름을 가진 자식 노드를 가져옵니다 |
| [getChildNodes()](#getChildNodes--) | 자식 노드들을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | 모든 노드 엔터티를 가져옵니다. |
| [getEntity()](#getEntity--) | 이 노드에 연결된 첫 번째 엔터티를 가져오며, 설정할 경우 다른 엔터티를 모두 삭제합니다. |
| [getExcluded()](#getExcluded--) | 내보내기 시 이 노드와 모든 자식 노드/엔터티를 제외할지 여부를 가져옵니다. |
| [getGlobalTransform()](#getGlobalTransform--) | 전역 변환을 가져옵니다. |
| [getMaterial()](#getMaterial--) | 이 노드와 연결된 첫 번째 재료를 가져오며, 설정할 경우 다른 재료를 모두 삭제합니다. |
| [getMaterials()](#getMaterials--) | 이 노드와 연결된 재료들을 가져옵니다. |
| [getMetaDatas()](#getMetaDatas--) | 이 노드에 정의된 메타 데이터를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getParentNode()](#getParentNode--) | 부모 노드를 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getTransform()](#getTransform--) | 로컬 변환을 가져옵니다. |
| [getVisible()](#getVisible--) | 노드 표시 여부를 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | 노드 아래의 모든 항목을 분리하고 현재 노드에 연결합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | XPath와 유사한 쿼리 구문을 사용하여 현재 노드 아래의 여러 객체를 선택합니다. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | XPath와 유사한 쿼리 구문을 사용하여 현재 노드 아래의 단일 객체를 선택합니다. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | 노드별 자산 정보 |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | 이 노드에 연결된 첫 번째 엔터티를 설정하며, 설정할 경우 다른 엔터티를 모두 삭제합니다. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 내보내기 시 이 노드와 모든 자식 노드/엔터티를 제외할지 여부를 설정합니다 |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | 이 노드와 연결된 첫 번째 재질을 설정합니다. 설정하면 다른 재질이 모두 지워집니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 부모 노드를 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 노드를 표시하도록 설정합니다. |
| [toString()](#toString--) | 이 노드의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


[Node](../../com.aspose.threed/node) 클래스의 새 인스턴스를 초기화합니다.

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


[Node](../../com.aspose.threed/node) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |
| entity | [Entity](../../com.aspose.threed/entity) | 기본 엔터티. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


[Node](../../com.aspose.threed/node) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


현재 노드를 포함한 모든 하위 노드를 순회하면서 방문자에게 노드를 전달합니다. 방문자는 false를 반환하여 순회를 중단할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | 노드를 방문하기 위한 방문자 콜백 |

**Returns:**
boolean - true이면 방문자가 순회를 중단했음을 의미합니다. **Example:** 다음 코드는 씬에서 모든 메쉬를 가져오는 방법을 보여줍니다

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


이 노드에 자식 노드를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | 첨부될 자식 노드 **Example:** 다음 코드는 씬에서 모든 메쉬를 가져오는 방법을 보여줍니다 |

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


노드에 엔터티를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 노드에 첨부될 엔터티 |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


자식 노드를 생성합니다

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


지정된 엔터티가 연결된 새 자식 노드를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | 노드에 기본적으로 첨부된 엔터티 |

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


지정된 노드 이름으로 새 자식 노드를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nodeName | java.lang.String | 새 자식 노드의 이름 |

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


지정된 노드 이름으로 새 자식 노드를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nodeName | java.lang.String | 새 자식 노드의 이름 |
| entity | [Entity](../../com.aspose.threed/entity) | 노드에 기본적으로 첨부된 엔터티 |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


지정된 노드 이름으로 새 자식 노드를 생성하고, 지정된 엔터티와 재료를 연결합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nodeName | java.lang.String | 새 자식 노드의 이름 |
| entity | [Entity](../../com.aspose.threed/entity) | 노드에 기본적으로 첨부된 엔터티 |
| material | [Material](../../com.aspose.threed/material) | 노드에 첨부된 재질 |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


전역 변환을 평가하고, 기하학적 변환을 포함할지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| withGeometricTransform | boolean | 기하학적 변환이 필요한지 여부. |

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


속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성 (Identified by its name)일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String | 속성 이름. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


노드별 자산 정보

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


노드의 경계 상자를 계산합니다

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


지정된 인덱스의 자식 노드를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 인덱스. |

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


지정된 이름을 가진 자식 노드를 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nodeName | java.lang.String | 찾을 자식 이름. |

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


자식 노드들을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Node> - 자식 노드들. **Example:** 다음 코드는 루트 노드의 자식 노드를 열거하는 방법을 보여줍니다

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


모든 노드 엔터티를 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Entity> - 모든 노드 엔터티.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


이 노드에 연결된 첫 번째 엔터티를 가져오며, 설정할 경우 다른 엔터티를 모두 삭제합니다.

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


내보내기 시 이 노드와 모든 자식 노드/엔터티를 제외할지 여부를 가져옵니다.

**Returns:**
boolean - 내보내기 중에 이 노드와 모든 자식 노드/엔터티를 제외할지 여부. **Example:** 다음 코드는 지정된 노드를 내보내기에서 제외하는 방법을 보여줍니다

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


전역 변환을 가져옵니다.

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


이 노드와 연결된 첫 번째 재료를 가져오며, 설정할 경우 다른 재료를 모두 삭제합니다.

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


이 노드와 연결된 재료들을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Material> - 이 노드와 연결된 재질들.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


이 노드에 정의된 메타 데이터를 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - 이 노드에 정의된 메타 데이터.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


부모 노드를 가져옵니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


모든 속성의 컬렉션을 가져옵니다.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


지정된 속성의 값을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 찾은 속성의 값
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


로컬 변환을 가져옵니다.

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


노드 표시 여부를 가져옵니다

**Returns:**
boolean - 노드를 표시할지 여부 **Example:** 다음 코드는 보이지 않는 노드를 만드는 방법을 보여줍니다

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


노드 아래의 모든 것을 분리하고 현재 노드에 첨부합니다. **Example:** 다음 코드는 두 개의 3D 파일을 하나로 병합하는 방법을 보여줍니다

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


동적 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


이름으로 식별되는 지정된 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


XPath와 유사한 쿼리 구문을 사용하여 현재 노드 아래의 여러 객체를 선택합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | java.lang.String | XPath와 유사한 쿼리 |

**Returns:**
java.util.ArrayList<java.lang.Object> - XPath와 유사한 쿼리에 일치하는 여러 객체.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


XPath와 유사한 쿼리 구문을 사용하여 현재 노드 아래의 단일 객체를 선택합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | java.lang.String | XPath와 유사한 쿼리 |

**Returns:**
java.lang.Object - XPath와 유사한 쿼리로 찾은 객체.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


노드별 자산 정보

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | 새 값 |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


이 노드에 연결된 첫 번째 엔터티를 설정하며, 설정할 경우 다른 엔터티를 모두 삭제합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | 새 값 **Example:** 다음 코드는 루트 노드 아래에 새로운 자식 노드를 만드는 방법을 보여줍니다 |

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


내보내기 시 이 노드와 모든 자식 노드/엔터티를 제외할지 여부를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 새 값 **Example:** 다음 코드는 지정된 노드를 내보내기에서 제외하는 방법을 보여줍니다 |

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


이 노드와 연결된 첫 번째 재질을 설정합니다. 설정하면 다른 재질이 모두 지워집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | 새 값 **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


부모 노드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


지정된 속성의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |
| 값 | java.lang.Object | 속성의 값 |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


노드를 표시하도록 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 새 값 **Example:** 다음 코드는 보이지 않는 노드를 만드는 방법을 보여줍니다 |

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


이 노드의 문자열 표현을 가져옵니다.

**Returns:**
java.lang.String - 디버깅을 위한 이 노드의 문자열 표현.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

