---
title: "Node"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/node/
---
## Node class

Представляет элемент в графе сцены. Граф сцены — это дерево объектов Node. Службы управления деревом инкапсулированы в этом классе. Обратите внимание, что Aspose.3D SDK не проверяет корректность построенного графа сцены. Ответственность за то, чтобы не создавать циклические графы в иерархии узлов, лежит на вызывающем. Помимо управления деревом, этот класс определяет все свойства, необходимые для описания положения объекта в сцене. Эта информация включает базовые свойства Translation, Rotation и Scaling, а также более продвинутые параметры для точек вращения, ограничений и атрибутов IK‑соединений, таких как жёсткость и демпфирование. При первом создании объект Node является \"empty\" (т.е. это объект без графического представления, содержащий только информацию о позиции). В этом состоянии его можно использовать для представления родительских узлов в структуре дерева, но не более. Обычное использование таких объектов — добавить к ним сущность, которая специализирует узел (см. \"Entity\"). Сущность является отдельным объектом и соединена с Node. Это также означает, что одна и та же сущность может быть общей для нескольких узлов. Camera, Light, Mesh и т.д. являются всеми сущностями и все они наследуются от базового класса Entity.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса Node. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name, entity) | Инициализирует новый экземпляр класса Node. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |
| entity | Entity | Сущность по умолчанию. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(name) | Инициализирует новый экземпляр класса Node. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Имя | Описание |
| --- | --- |
| getAssetInfo() | Информация об активе узла |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Имя | Описание |
| --- | --- |
| setAssetInfo(value) | Информация об активе узла |

 **Result:**



---


### getVisible{#getVisible}

| Имя | Описание |
| --- | --- |
| getVisible() | Получает или задает отображение узла |

 **Result:**



---


### setVisible{#setVisible}

| Имя | Описание |
| --- | --- |
| setVisible(value) | Получает или задает отображение узла |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Имя | Описание |
| --- | --- |
| getChildNodes() | Получает дочерние узлы. Узлы. |

 **Result:**



---


### getEntity{#getEntity}

| Имя | Описание |
| --- | --- |
| getEntity() | Получает или задает первую сущность, прикреплённую к этому узлу; при установке будут очищены другие сущности. Сущность узла. |

 **Result:**



---


### setEntity{#setEntity}

| Имя | Описание |
| --- | --- |
| setEntity(value) | Получает или задает первую сущность, прикреплённую к этому узлу; при установке будут очищены другие сущности. Сущность узла. |

 **Result:**



---


### getExcluded{#getExcluded}

| Имя | Описание |
| --- | --- |
| getExcluded() | Получает или задает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте. |

 **Result:**



---


### setExcluded{#setExcluded}

| Имя | Описание |
| --- | --- |
| setExcluded(value) | Получает или задает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте. |

 **Result:**



---


### getEntities{#getEntities}

| Имя | Описание |
| --- | --- |
| getEntities() | Получает все сущности узла. Сущности узла. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Имя | Описание |
| --- | --- |
| getMetaDatas() | Получает метаданные, определённые в этом узле. Метаданные. |

 **Result:**



---


### getMaterials{#getMaterials}

| Имя | Описание |
| --- | --- |
| getMaterials() | Получает материалы, связанные с этим узлом. Материалы. |

 **Result:**



---


### getMaterial{#getMaterial}

| Имя | Описание |
| --- | --- |
| getMaterial() | Получает или задает первый материал, связанный с этим узлом; при установке будут очищены другие материалы. Материал. |

 **Result:**



---


### setMaterial{#setMaterial}

| Имя | Описание |
| --- | --- |
| setMaterial(value) | Получает или задает первый материал, связанный с этим узлом; при установке будут очищены другие материалы. Материал. |

 **Result:**



---


### getParentNode{#getParentNode}

| Имя | Описание |
| --- | --- |
| getParentNode() | Получает или задает родительский узел. Родительский узел. |

 **Result:**



---


### setParentNode{#setParentNode}

| Имя | Описание |
| --- | --- |
| setParentNode(value) | Получает или задает родительский узел. Родительский узел. |

 **Result:**



---


### getTransform{#getTransform}

| Имя | Описание |
| --- | --- |
| getTransform() | Получает локальное преобразование. Преобразование. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Имя | Описание |
| --- | --- |
| getGlobalTransform() | Получает глобальное преобразование. Глобальное преобразование. |

 **Result:**



---


### getScene{#getScene}

| Имя | Описание |
| --- | --- |
| getScene() | Получает сцену, к которой принадлежит этот объект. |

 **Result:**



---


### getName{#getName}

| Имя | Описание |
| --- | --- |
| getName() | Получает или задает имя. Имя. |

 **Result:**



---


### setName{#setName}

| Имя | Описание |
| --- | --- |
| setName(value) | Получает или задает имя. Имя. |

 **Result:**



---


### getProperties{#getProperties}

| Имя | Описание |
| --- | --- |
| getProperties() | Получает коллекцию всех свойств. |

 **Result:**



---


### createChildNode{#createChildNode}

| Имя | Описание |
| --- | --- |
| createChildNode() | Создает дочерний узел |

 **Result:**
Node


---


### merge{#merge}

| Имя | Описание |
| --- | --- |
| merge(node) | Отсоединить всё под узлом и присоединить к текущему узлу. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| узел | Node | null |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Имя | Описание |
| --- | --- |
| createChildNode(nodeName) | Создать новый дочерний узел с заданным именем узла |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя нового дочернего узла |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Имя | Описание |
| --- | --- |
| createChildNode(entity) | Создать новый дочерний узел с присоединённой заданной сущностью |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| entity | Entity | Сущность по умолчанию, присоединённая к узлу |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Имя | Описание |
| --- | --- |
| createChildNode(nodeName, entity) | Создать новый дочерний узел с заданным именем узла |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя нового дочернего узла |
| entity | Entity | Сущность по умолчанию, присоединённая к узлу |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Имя | Описание |
| --- | --- |
| createChildNode(nodeName, entity, material) | Создать новый дочерний узел с заданным именем узла и присоединить указанную сущность и материал |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя нового дочернего узла |
| entity | Entity | Сущность по умолчанию, присоединённая к узлу |
| material | Материал | Материал, присоединённый к узлу |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Имя | Описание |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Вычислить глобальное преобразование, включать геометрическое преобразование или нет. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| withGeometricTransform | boolean | Нужно ли геометрическое преобразование. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Имя | Описание |
| --- | --- |
| getChild(index) | Получает дочерний узел по указанному индексу. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| индекс | Number | Индекс. |

 **Result:**
Node


---


### getChild{#getChild}

| Имя | Описание |
| --- | --- |
| getChild(nodeName) | Получает дочерний узел с указанным именем |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя дочернего узла для поиска. |

 **Result:**
Node


---


### accept{#accept}

| Имя | Описание |
| --- | --- |
| accept(visitor) | Проходит через все дочерние узлы (включая текущий узел) и вызывает посетителя с узлом. Посетитель может прервать обход, вернув false. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| visitor | NodeVisitor | Обратный вызов посетителя для посещения узла |

 **Result:**
boolean


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Получает строковое представление этого узла. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| Имя | Описание |
| --- | --- |
| getBoundingBox() | Вычисляет ограничивающий прямоугольник узла |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Имя | Описание |
| --- | --- |
| addEntity(entity) | Добавляет сущность к узлу. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| entity | Entity | Сущность, которую нужно присоединить к узлу |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Имя | Описание |
| --- | --- |
| addChildNode(node) | Добавляет дочерний узел к этому узлу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| node | Node | Дочерний узел, который будет присоединён |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Имя | Описание |
| --- | --- |
| selectSingleObject(path) | Выбирает один объект под текущим узлом, используя синтаксис запросов, похожий на XPath. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| Имя | Описание |
| --- | --- |
| selectObjects(path) | Выбирает несколько объектов под текущим узлом, используя синтаксис запросов, похожий на XPath. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| pat | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удаляет динамическое свойство. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | Property | Какое свойство удалить |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удалить указанное свойство, определённое по имени |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Имя | Описание |
| --- | --- |
| getProperty(property) | Получить значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |

 **Result:**
Object


---


### setProperty{#setProperty}

| Имя | Описание |
| --- | --- |
| setProperty(property, value) | Устанавливает значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |
| value | Object | Значение свойства |

 **Result:**
Object


---


### findProperty{#findProperty}

| Имя | Описание |
| --- | --- |
| findProperty(propertyName) | Находит свойство. Это может быть динамическое свойство (Created by CreateDynamicProperty/SetProperty) или нативное свойство (Identified by its name) |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propertyName | String | Имя свойства. |

 **Result:**
Property


---



