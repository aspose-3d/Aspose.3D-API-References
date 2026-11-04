---
title: "Класс TriMeshT"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.TriMesh1T. Обобщённая версия TriMesh для пользовательского статически определённого типа вершины."
type: docs
weight: 800
url: /ru/net/aspose.threed.entities/trimesh-1/
---
## TriMesh&lt;T&gt; class

Обобщённая версия [`TriMesh`](../trimesh/) для статически определённого типа вершины пользователя.

```csharp
public class TriMesh<T> : TriMesh
    where T : struct
```

| Параметр | Описание |
| --- | --- |
| T |  |

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TriMesh](trimesh/)(string) | Инициализировать экземпляр [`TriMesh`](../trimesh/) |

## Свойства

| Имя | Описание |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | Ёмкость предварительно выделенных вершин. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | Количество индексов в этом [`TriMesh`](../trimesh/) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | Количество неслитых вершин, переданных через [`BeginVertex`](../trimesh/beginvertex/) и [`EndVertex`](../trimesh/endvertex/). |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | Размещение вершин в [`TriMesh`](../trimesh/). |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | Количество вершин в этом [`TriMesh`](../trimesh/) |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | Общий размер всех вершин в байтах |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromMesh](../../aspose.threed.entities/trimesh-1/frommesh/)(Mesh) | Создаёт TriMesh из заданного объекта сетки с автоматически сгенерированным расположением вершин. |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | Добавить новый треугольник |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | Начать добавление вершины |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | Завершить добавление вершины |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | Получить перечислитель для перечисления [`Vertex`](../../aspose.threed.utilities/vertex/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/)(out ushort[]) |  |
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
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | Получает строковое представление [`TriMesh`](../trimesh/) |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | Преобразовать данные вершин в массив байтов |
| [VerticesToTypedArray](../../aspose.threed.entities/trimesh-1/verticestotypedarray/)() | Преобразует данные вершин в типизированный массив |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | Записать данные индексов как 16‑битные целые в поток |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | Запишите данные индексов как 32‑битное целое в поток |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | Запишите данные вершин в указанный поток |

### См. также

* class [TriMesh](../trimesh/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


