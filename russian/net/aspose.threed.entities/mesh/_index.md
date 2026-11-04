---
title: "Класс Mesh"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Mesh. Сетка состоит из множества n-угольных полигонов"
type: docs
weight: 510
url: /ru/net/aspose.threed.entities/mesh/
---
## Mesh class

Сетка состоит из множества n-угольных полигонов.

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Mesh](mesh/#constructor)() | Инициализирует новый экземпляр класса `Mesh`. |
| [Mesh](mesh/#constructor_4)(string) | Инициализирует новый экземпляр класса `Mesh`. |
| [Mesh](mesh/#constructor_1)(TextureData) | Создать сетку, используя указанную карту высот; если формат пикселей карты высот содержит несколько компонентов, первый (обычно красный) компонент будет использоваться как значение высоты (z). Компоненты x и y контрольной точки являются нормализованными координатами пикселя. |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | Создать сетку, используя указанную карту высот; если формат пикселей карты высот содержит несколько компонентов, первый (обычно красный) компонент будет использоваться как значение высоты (z). Компоненты x и y контрольной точки являются нормализованными координатами пикселя. |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | Создать сетку, используя указанную карту высот; если формат пикселей карты высот содержит несколько компонентов, первый (обычно красный) компонент будет использоваться как значение высоты (z). Компоненты x и y контрольной точки являются нормализованными координатами пикселя. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | Получает все контрольные точки |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | Получает все деформаторы, связанные с этой геометрией. |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | Получает ребра сетки. Ребра являются необязательными в сетке, поэтому могут отсутствовать. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | Получает количество полигонов |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | Получает определение полигонов сетки |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | Получает все элементы вершин |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | Получает или задает, видима ли геометрия |

## Методы

| Имя | Описание |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | Добавляет существующий элемент вершины к текущей геометрии |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | Создаёт [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения. |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | Создаёт [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения. |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | Создаёт новый полигон со всеми вершинами, определёнными в *indices*. Чтобы создавать полигон вершина за вершиной, пожалуйста, используйте [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | Создать полигон с 3 вершинами (треугольник) |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | Создаёт новый полигон со всеми вершинами, определёнными в *indices*. Чтобы создавать полигон вершина за вершиной, пожалуйста, используйте [`PolygonBuilder`](../polygonbuilder/). |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | Создать полигон с 4 вершинами (четырёхугольник) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | Получает элемент вершины с указанным типом |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | Получает перечислитель для каждого внутреннего полигона. |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | Получает количество вершин указанного полигона. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | Получает экземпляр [`VertexElementUV`](../vertexelementuv/) с заданным типом текстурного отображения |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | Проверьте, является ли текущая сетка многообразной. Эта функция не будет кэшировать результат расчёта многообразия. |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | Оптимизируйте использование памяти сеткой, устраняя дублированные контрольные точки |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | Оптимизируйте использование памяти сеткой, устраняя дублированные контрольные точки |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | Получает экземпляр Mesh из текущей сущности. |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | Возвращает триангулированную сетку |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | Вычислить пересечение двух сеток |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | Вычислить объединение двух сеток |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | Вычислить разницу двух сеток |

## Примеры

Чтобы добавить полигон в сетку:

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Пройти через все полигоны в сетке:

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //обрабатывать полигон
}
```

### См. также

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


