---
title: "TriMesh.FromMesh"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TriMesh. Создать TriMesh из заданного объекта mesh с указанной раскладкой вершин"
type: docs
weight: 30
url: /ru/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

Создать TriMesh из заданного объекта сетки с указанной разметкой вершин.

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| объявление | VertexDeclaration | Определение типа Vertex, или расположение в памяти |
| mesh | Сетка | Исходный mesh |

### Возвращаемое значение

Экземпляр TriMesh, преобразованный из входного mesh с указанным расположением памяти вершин

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

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

Создать TriMesh из заданного объекта сетки, объявление вершин основано на структуре входной сетки.

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | Сетка |  |
| useFloat | Boolean | Использовать тип float вместо double для каждого компонента элемента вершины. |

### Возвращаемое значение

Сгенерированный [`TriMesh`](../) из данного [`Mesh`](../../mesh/)

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

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


