---
title: "Класс NurbsSurface"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.NurbsSurface. NurbsSurface — поверхность, представленная NURBS (неравномерным рациональным базисным сплайном). NurbsSurface определяется двумя NurbsDirectionU и V. Компонент w в контрольной точке используется как вес контрольных точек независимо от того, является ли тип направления двумерным или трехмерным."
type: docs
weight: 540
url: /ru/net/aspose.threed.entities/nurbssurface/
---
## NurbsSurface class

`NurbsSurface` — поверхность, представленная [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline). `NurbsSurface` определяется двумя [`NurbsDirection`](../nurbsdirection/)[`U`](./u/) и [`V`](./v/). Компонент w в контрольной точке используется как вес контрольной точки независимо от того, является ли тип направления двумерным или трехмерным.

```csharp
public class NurbsSurface : Geometry, IMeshConvertible
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NurbsSurface](nurbssurface/#constructor)() | Инициализирует новый экземпляр класса `NurbsSurface`. |
| [NurbsSurface](nurbssurface/#constructor_1)(string) | Инициализирует новый экземпляр класса `NurbsSurface`. |

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
| [U](../../aspose.threed.entities/nurbssurface/u/) { get; } | Получает направление U поверхности NURBS |
| [V](../../aspose.threed.entities/nurbssurface/v/) { get; } | Получает направление V поверхности NURBS |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Получает все элементы вершин |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Получает или задает, видима ли геометрия |

## Методы

| Имя | Описание |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Добавляет существующий элемент вершины к текущей геометрии |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Создаёт [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Создаёт [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения. |
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
| [ToMesh](../../aspose.threed.entities/nurbssurface/tomesh/)() | Преобразует поверхность NURBS в сетку |

### См. также

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


