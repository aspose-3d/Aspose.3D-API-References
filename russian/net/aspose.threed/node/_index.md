---
title: "Класс Node"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Node. Представляет элемент в графе сцены. Граф сцены — это дерево объектов Node. Службы управления деревом находятся внутри этого класса. Обратите внимание, что Aspose.3D SDK не проверяет корректность построенного графа сцены. Ответственность за то, чтобы не создавать циклические графы в иерархии узлов, лежит на вызывающем. Помимо управления деревом этот класс определяет все свойства, необходимые для описания положения объекта в сцене. Эта информация включает базовые свойства Translation, Rotation и Scaling, а также более продвинутые параметры для точек вращения, ограничений и атрибутов IK‑соединений, таких как жёсткость и демпфирование. При первом создании объект Node пуст, то есть это объект без графического представления, содержащий только информацию о позиции. В этом состоянии его можно использовать для представления родителей в структуре дерева узлов, но не много больше. Обычное использование таких объектов — добавить к ним сущность, которая специализирует узел, см. Entity. Сущность является самостоятельным объектом и связана с Node. Это также означает, что одна и та же сущность может быть общей для нескольких узлов. Camera, Light, Mesh и т.д. — все являются сущностями и все они наследуются от базового класса Entity"
type: docs
weight: 1630
url: /ru/net/aspose.threed/node/
---
## Node class

Представляет элемент в графе сцены. Граф сцены — это дерево объектов Node. Службы управления деревом находятся внутри этого класса. Обратите внимание, что SDK Aspose.3D не проверяет корректность построенного графа сцены. Ответственность за то, чтобы не создавать циклические графы в иерархии узлов, лежит на вызывающем коде. Помимо управления деревом, этот класс определяет все свойства, необходимые для описания позиции объекта в сцене. Эта информация включает базовые свойства Перемещения, Вращения и Масштабирования, а также более продвинутые параметры для точек опоры, ограничений и атрибутов IK‑соединений, таких как жёсткость и демпфирование. При первом создании объект Node является «пустым» (т.е. объектом без графического представления, содержащим только информацию о позиции). В этом состоянии его можно использовать для представления родителей в структуре дерева узлов, но не гораздо больше. Обычное применение таких объектов — добавить к ним сущность, которая специализирует узел (см. "Entity"). Сущность является самостоятельным объектом и соединена с Node. Это также означает, что одна и та же сущность может быть общей для нескольких узлов. Camera, Light, Mesh и т.д. — все являются сущностями и наследуются от базового класса Entity.

```csharp
public class Node : SceneObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Node](node/#constructor)() | Инициализирует новый экземпляр класса `Node`. |
| [Node](node/#constructor_1)(string) | Инициализирует новый экземпляр класса `Node`. |
| [Node](node/#constructor_2)(string, Entity) | Инициализирует новый экземпляр класса `Node`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo/) { get; set; } | Информация об активе для каждого узла |
| [ChildNodes](../../aspose.threed/node/childnodes/) { get; } | Получает дочерние узлы. |
| [Entities](../../aspose.threed/node/entities/) { get; } | Получает все сущности узла. |
| [Entity](../../aspose.threed/node/entity/) { get; set; } | Получает или задает первую сущность, прикреплённую к этому узлу; при установке будут удалены другие сущности. |
| [Excluded](../../aspose.threed/node/excluded/) { get; set; } | Получает или задает, следует ли исключать этот узел и все дочерние узлы/сущности при экспорте. |
| [GlobalTransform](../../aspose.threed/node/globaltransform/) { get; } | Получает глобальное преобразование. |
| [Material](../../aspose.threed/node/material/) { get; set; } | Получает или задает первый материал, связанный с этим узлом; при установке будут удалены другие материалы |
| [Materials](../../aspose.threed/node/materials/) { get; } | Получает материалы, связанные с этим узлом. |
| [MetaDatas](../../aspose.threed/node/metadatas/) { get; } | Получает метаданные, определённые в этом узле. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/node/parentnode/) { get; set; } | Получает или задает родительский узел. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Transform](../../aspose.threed/node/transform/) { get; } | Получает локальное преобразование. |
| [Visible](../../aspose.threed/node/visible/) { get; set; } | Получает или задает отображение узла |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.threed/node/accept/)(NodeVisitor) | Проходит по всем дочерним узлам (включая текущий узел) и вызывает посетителя с узлом. Посетитель может прервать обход, вернув false |
| [AddChildNode](../../aspose.threed/node/addchildnode/)(Node) | Добавить дочерний узел к этому узлу |
| [AddEntity](../../aspose.threed/node/addentity/)(Entity) | Добавить сущность к узлу. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode)() | Создает дочерний узел |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_1)(Entity) | Создать новый дочерний узел с прикрепленной заданной сущностью |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_2)(string) | Создать новый дочерний узел с заданным именем узла |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_3)(string, Entity) | Создать новый дочерний узел с заданным именем узла |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_4)(string, Entity, Material) | Создать новый дочерний узел с заданным именем узла и прикрепить указанную сущность и материал |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform/)(bool) | Вычислить глобальное преобразование, включать геометрическое преобразование или нет. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox/)() | Вычислить ограничивающий прямоугольник узла |
| [GetChild](../../aspose.threed/node/getchild/#getchild)(int) | Получает дочерний узел по указанному индексу. |
| [GetChild](../../aspose.threed/node/getchild/#getchild_1)(string) | Получает дочерний узел с указанным именем |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity/)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [Merge](../../aspose.threed/node/merge/)(Node) | Отсоединить всё под узлом и прикрепить к текущему узлу. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SelectObjects](../../aspose.threed/node/selectobjects/)(string) | Выбрать несколько объектов под текущим узлом, используя синтаксис запросов, похожий на XPath. |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject/)(string) | Выбрать один объект под текущим узлом, используя синтаксис запросов, похожий на XPath. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| override [ToString](../../aspose.threed/node/tostring/)() | Получает строковое представление этого узла. |

### См. также

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


