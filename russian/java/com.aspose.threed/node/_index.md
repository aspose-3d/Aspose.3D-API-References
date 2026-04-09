---
title: Node
second_title: Справочник API Aspose.3D для Java
description: Представляет элемент в графе сцены.
type: docs
weight: 110
url: /ru/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Представляет элемент в графе сцены. Граф сцены — это дерево объектов Node. Сервисы управления деревом находятся внутри этого класса. Обратите внимание, что Aspose.3D SDK не проверяет корректность построенного графа сцены. Ответственность за то, чтобы не создавать циклические графы в иерархии узлов, лежит на вызывающем коде. Помимо управления деревом, этот класс определяет все свойства, необходимые для описания положения объекта в сцене. Эта информация включает базовые свойства Translation, Rotation и Scaling, а также более продвинутые параметры для точек вращения, ограничений и атрибутов суставов IK, таких как жёсткость и демпфирование. При первом создании объект Node является "empty" (т.е.: это объект без графического представления, содержащий только информацию о позиции). В этом состоянии его можно использовать для представления родителей в структуре дерева узлов, но не более. Обычное использование таких объектов — добавить к ним сущность, которая специализирует узел (см. "Entity"). Сущность является самостоятельным объектом и соединена с Node. Это также означает, что одна и та же сущность может быть общей для нескольких узлов. Camera, Light, Mesh и т.д. — все являются сущностями и наследуются от базового класса Entity.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Node()](#Node--) | Инициализирует новый экземпляр класса [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Инициализирует новый экземпляр класса [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | Инициализирует новый экземпляр класса [Node](../../com.aspose.threed/node). |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Проходит по всем дочерним узлам (включая текущий узел) и вызывает посетителя с узлом. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Добавить дочерний узел к этому узлу |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Добавить сущность к узлу. |
| [createChildNode()](#createChildNode--) | Создает дочерний узел |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Создать новый дочерний узел с прикреплённой заданной сущностью |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Создать новый дочерний узел с заданным именем узла |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Создать новый дочерний узел с заданным именем узла |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Создать новый дочерний узел с заданным именем узла и прикрепить указанную сущность и материал |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Вычислить глобальное преобразование, включать геометрическое преобразование или нет. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getAssetInfo()](#getAssetInfo--) | Информация об активе для каждого узла |
| [getBoundingBox()](#getBoundingBox--) | Вычислить ограничивающий прямоугольник узла |
| [getChild(int index)](#getChild-int-) | Получает дочерний узел по указанному индексу. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Получает дочерний узел с указанным именем |
| [getChildNodes()](#getChildNodes--) | Получает дочерние узлы. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Получает все сущности узла. |
| [getEntity()](#getEntity--) | Получает первую сущность, прикреплённую к этому узлу; если установить, будут удалены другие сущности. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте. |
| [getGlobalTransform()](#getGlobalTransform--) | Получает глобальное преобразование. |
| [getMaterial()](#getMaterial--) | Получает первый материал, связанный с этим узлом; если установить, будут удалены другие материалы. |
| [getMaterials()](#getMaterials--) | Получает материалы, связанные с этим узлом. |
| [getMetaDatas()](#getMetaDatas--) | Получает метаданные, определённые в этом узле. |
| [getName()](#getName--) | Получает имя. |
| [getParentNode()](#getParentNode--) | Получает родительский узел. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getTransform()](#getTransform--) | Получает локальное преобразование. |
| [getVisible()](#getVisible--) | Получает отображение узла |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Отсоединить всё под узлом и прикрепить к текущему узлу. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Выбрать несколько объектов под текущим узлом, используя синтаксис запросов, похожий на XPath. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Выбрать один объект под текущим узлом, используя синтаксис запросов, похожий на XPath. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Информация об активе для каждого узла |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Устанавливает первую сущность, прикреплённую к этому узлу; если установить, будут удалены другие сущности. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Устанавливает первый материал, связанный с этим узлом; если устанавливается, остальные материалы будут очищены |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает родительский узел. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setVisible(boolean value)](#setVisible-boolean-) | Устанавливает отображение узла. |
| [toString()](#toString--) | Получает строковое представление этого узла. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Инициализирует новый экземпляр класса [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Инициализирует новый экземпляр класса [Node](../../com.aspose.threed/node).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |
| entity | [Entity](../../com.aspose.threed/entity) | Сущность по умолчанию. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Инициализирует новый экземпляр класса [Node](../../com.aspose.threed/node).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Проходит по всем дочерним узлам (включая текущий узел) и вызывает посетителя с узлом. Посетитель может прервать обход, вернув false

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Обратный вызов посетителя для посещения узла |

**Returns:**
boolean - true означает, что посетитель прервал обход. **Example:** Следующий код показывает, как получить все сетки из сцены

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


Добавить дочерний узел к этому узлу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Дочерний узел, который будет присоединён **Example:** Следующий код показывает, как получить все сетки из сцены |

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


Добавить сущность к узлу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Сущность, которая будет присоединена к узлу |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Создает дочерний узел

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


Создать новый дочерний узел с прикреплённой заданной сущностью

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Сущность по умолчанию, присоединённая к узлу |

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


Создать новый дочерний узел с заданным именем узла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | java.lang.String | Имя нового дочернего узла |

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


Создать новый дочерний узел с заданным именем узла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | java.lang.String | Имя нового дочернего узла |
| entity | [Entity](../../com.aspose.threed/entity) | Сущность по умолчанию, присоединённая к узлу |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Создать новый дочерний узел с заданным именем узла и прикрепить указанную сущность и материал

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | java.lang.String | Имя нового дочернего узла |
| entity | [Entity](../../com.aspose.threed/entity) | Сущность по умолчанию, присоединённая к узлу |
| material | [Material](../../com.aspose.threed/material) | Материал, присоединённый к узлу |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Вычислить глобальное преобразование, включать геометрическое преобразование или нет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| withGeometricTransform | boolean | Нужна ли геометрическая трансформация. |

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


Находит свойство. Оно может быть динамическим свойством (созданным с помощью CreateDynamicProperty/SetProperty) или нативным свойством (определяемым по его имени)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | java.lang.String | Имя свойства. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Информация об активе для каждого узла

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Вычислить ограничивающий прямоугольник узла

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Получает дочерний узел по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс. |

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


Получает дочерний узел с указанным именем

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | java.lang.String | Имя дочернего узла для поиска. |

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


Получает дочерние узлы.

**Returns:**
java.util.List<com.aspose.threed.Node> - дочерние узлы. **Example:** Следующий код показывает, как перечислить дочерний узел корневого узла

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


Получает все сущности узла.

**Returns:**
java.util.List<com.aspose.threed.Entity> - все сущности узла.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Получает первую сущность, прикреплённую к этому узлу; если установить, будут удалены другие сущности.

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


Получает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте.

**Returns:**
boolean - следует ли исключить этот узел и все дочерние узлы/сущности при экспорте. **Example:** Следующий код показывает, как исключить указанный узел из экспорта

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


Получает глобальное преобразование.

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


Получает первый материал, связанный с этим узлом; если установить, будут удалены другие материалы.

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


Получает материалы, связанные с этим узлом.

**Returns:**
java.util.List<com.aspose.threed.Material> - материалы, связанные с этим узлом.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Получает метаданные, определённые в этом узле.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - метаданные, определённые в этом узле.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Получает родительский узел.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Получает коллекцию всех свойств.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Получить значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |

**Returns:**
java.lang.Object - Значение найденного свойства
### getScene() {#getScene--}
```
public Scene getScene()
```


Получает сцену, к которой принадлежит этот объект

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Получает локальное преобразование.

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


Получает отображение узла

**Returns:**
boolean - отображать узел **Example:** Следующий код показывает, как создать невидимый узел

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


Отсоединить всё под узлом и присоединить к текущему узлу. **Example:** Следующий код показывает, как объединить два 3D‑файла в один файл

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Параметр | Тип | Описание |
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


Удаляет динамическое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Удалить указанное свойство, определяемое по имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Выбрать несколько объектов под текущим узлом, используя синтаксис запросов, похожий на XPath.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | java.lang.String | XPath‑подобный запрос |

**Returns:**
java.util.ArrayList<java.lang.Object> - Несколько объектов соответствуют запросу, похожему на XPath.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Выбрать один объект под текущим узлом, используя синтаксис запросов, похожий на XPath.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | java.lang.String | XPath‑подобный запрос |

**Returns:**
java.lang.Object - Объект, найденный запросом, похожим на XPath.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Информация об активе для каждого узла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Новое значение |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Устанавливает первую сущность, прикреплённую к этому узлу; если установить, будут удалены другие сущности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Новое значение **Пример:** Следующий код показывает, как создать новый дочерний узел под корневым узлом |

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


Устанавливает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | Новое значение **Пример:** Следующий код показывает, как исключить указанный узел из экспорта |

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


Устанавливает первый материал, связанный с этим узлом; если устанавливается, остальные материалы будут очищены

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Новое значение **Пример:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Устанавливает родительский узел.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Новое значение |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Устанавливает значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |
| значение | java.lang.Object | Значение свойства |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Устанавливает отображение узла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | Новое значение **Пример:** Следующий код показывает, как создать невидимый узел |

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


Получает строковое представление этого узла.

**Returns:**
java.lang.String - Строковое представление этого узла для отладки.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

