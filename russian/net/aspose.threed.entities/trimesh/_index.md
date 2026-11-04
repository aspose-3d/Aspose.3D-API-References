---
title: "Класс TriMesh"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.TriMesh. TriMesh содержит необработанные данные, которые могут использоваться GPU напрямую. Этот класс — утилита, помогающая создавать сетку, содержащую только данные для каждой вершины."
type: docs
weight: 790
url: /ru/net/aspose.threed.entities/trimesh/
---
## TriMesh class

TriMesh содержит необработанные данные, которые могут использоваться GPU напрямую. Этот класс — утилита, помогающая создавать сетку, содержащую только данные для каждой вершины.

```csharp
public class TriMesh : Entity, IEnumerable<Vertex>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TriMesh](trimesh/)(string, VertexDeclaration) | Инициализировать экземпляр `TriMesh` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | Ёмкость предварительно выделенных вершин. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | Количество индексов в этом `TriMesh` |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | Количество неслитых вершин, переданных через [`BeginVertex`](./beginvertex/) и [`EndVertex`](./endvertex/). |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | Разметка вершин `TriMesh`. |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | Количество вершин в этом `TriMesh` |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | Общий размер всех вершин в байтах |

## Методы

| Имя | Описание |
| --- | --- |
| static [CopyFrom](../../aspose.threed.entities/trimesh/copyfrom/)(TriMesh, VertexDeclaration) | Скопировать `TriMesh` из входных данных с новой разметкой вершин |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh)(Mesh, bool) | Создать TriMesh из заданного объекта сетки, объявление вершин основано на структуре входной сетки. |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh_1)(VertexDeclaration, Mesh) | Создать TriMesh из заданного объекта сетки с указанной разметкой вершин. |
| static [FromRawData](../../aspose.threed.entities/trimesh/fromrawdata/)(VertexDeclaration, byte[], int[], bool) | Создать TriMesh из необработанных данных |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | Добавить новый треугольник |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | Начать добавление вершины |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | Завершить добавление вершины |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | Получить перечислитель для перечисления [`Vertex`](../../aspose.threed.utilities/vertex/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray_1)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | Загрузить вершины из байтов, длина байтов должна быть целым кратным размеру вершины. |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | Прочитать поле типа double |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | Прочитать поле типа float |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | Прочитать поле vector2 |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | Прочитать поле vector3 |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | Прочитать поле vector4 |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | Прочитать поле vector2 |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | Прочитать поле vector3 |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | Прочитать поле vector4 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | Получает строковое представление `TriMesh` |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | Преобразовать данные вершин в массив байтов |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | Записать данные индексов как 16‑битные целые в поток |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | Запишите данные индексов как 32‑битное целое в поток |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | Запишите данные вершин в указанный поток |

## Примеры

Следующий код показывает, как создать TriMesh с пользовательским расположением памяти и экспортировать его в файл.

```csharp
//Определите объявление вершины как {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Преобразуйте сетку в три‑меш, используя указанное расположение памяти
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//Сохраните его в поток, 115 вершин * 32 байта на вершину
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //Сохраните индексы как ushort в поток, 504 индекса * 2 байта на индекс
    triMesh.Write16bIndicesTo(stream);
}
```

### См. также

* class [Entity](../../aspose.threed/entity/)
* class [Vertex](../../aspose.threed.utilities/vertex/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


