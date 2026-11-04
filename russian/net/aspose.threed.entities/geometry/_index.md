---
title: "Класс Geometry"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Geometry. Базовый класс всех визуализируемых геометрических объектов, таких как Mesh, NurbsSurface, Patch и т.д."
type: docs
weight: 410
url: /ru/net/aspose.threed.entities/geometry/
---
## Geometry class

Базовый класс всех визуализируемых геометрических объектов (например, [`Mesh`](../mesh/), [`NurbsSurface`](../nurbssurface/), [`Patch`](../patch/) и т.д.).

Базовый класс `Geometry` поддерживает: **Control point management**, контрольные точки определяют базовую 3D пространственную структуру геометрии, разные типы геометрии имеют разный способ определения конкретных 3D моделей. **Vertex element definition**, элементы вершин добавляют дополнительную информацию, такую как нормали/UV‑координаты/цвета вершин, к геометрии, см. [`VertexElement`](../vertexelement/) для получения более подробной информации.**Object deforming**, [`Deformer`](../../aspose.threed.deformers/deformer/) может быть привязан для анимации формы геометрии.

```csharp
public class Geometry : Entity
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Geometry](geometry/)(string) | Инициализирует новый экземпляр класса `Geometry`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Получает все контрольные точки |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Получает все деформаторы, связанные с этой геометрией. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Получает все элементы вершин |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Получает или задает, видима ли геометрия |

## Методы

| Имя | Описание |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Добавляет существующий элемент вершины к текущей геометрии |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement)(VertexElementType) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement_1)(VertexElementType, MappingMode, ReferenceMode) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv)(TextureMapping) | Создаёт [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv_1)(TextureMapping, MappingMode, ReferenceMode) | Создаёт [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Получает элемент вершины с указанным типом |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Получает экземпляр [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


