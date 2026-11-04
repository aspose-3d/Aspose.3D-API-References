---
title: "PolygonModifier.SplitMesh"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PolygonModifier. Разделить меш на субмеши по VertexElementMaterial. Каждый субмеш будет использовать только один материал. Выполнить разбиение меша на узле"
type: docs
weight: 70
url: /ru/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Разделить меш на суб‑меши по [`VertexElementMaterial`](../../vertexelementmaterial/). Каждый суб‑меш будет использовать только один материал. Выполнить разбиение меша на узле

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | Узел |  |
| политика | SplitMeshPolicy |  |
| createChildNodes | Boolean | Создать дочерние узлы для каждого sub-mesh. |
| removeOldMesh | Boolean | Удалить старую сетку после разбиения, если этот параметр ложен, старые и новые сетки будут сосуществовать. |

## Примеры

Следующий код показывает, как разделить коробку на подмеши, используя индексы материалов.

```csharp
// Создайте сетку коробки (коробка состоит из 6 плоскостей)
Mesh box = (new Box()).ToMesh();
// Создайте элемент материала на этой сетке
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// И укажите разный индекс материала для каждой плоскости
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Теперь разделите её на 6 подмешей, мы указали 6 разных материалов на каждой плоскости, каждая плоскость станет подмешем.
// Мы использовали политику CloneData, каждая плоскость будет иметь одинаковую информацию о контрольных точках или информацию о вершинах, основанную на контрольных точках.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Теперь разделите её на 2 подмеша, первый меш будет содержать плоскости 0/1/2, а второй меш будет содержать плоскости 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Мы использовали политику CompactData, каждая плоскость будет иметь собственную информацию о контрольных точках или информацию о вершинах, основанную на контрольных точках.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### См. также

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Разделить сетку на подмеши с помощью [`VertexElementMaterial`](../../vertexelementmaterial/). Каждый подмеш будет использовать только один материал. Выполнить разбиение сетки на всех узлах сцены.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сцена | Сцена |  |
| политика | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## Примеры

Следующий код показывает, как разделить коробку на подмеши, используя индексы материалов.

```csharp
// Создайте сетку коробки (коробка состоит из 6 плоскостей)
Mesh box = (new Box()).ToMesh();
// Создайте элемент материала на этой сетке
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// И укажите разный индекс материала для каждой плоскости
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Теперь разделите её на 6 подмешей, мы указали 6 разных материалов на каждой плоскости, каждая плоскость станет подмешем.
// Мы использовали политику CloneData, каждая плоскость будет иметь одинаковую информацию о контрольных точках или информацию о вершинах, основанную на контрольных точках.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Теперь разделите её на 2 подмеша, первый меш будет содержать плоскости 0/1/2, а второй меш будет содержать плоскости 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Мы использовали политику CompactData, каждая плоскость будет иметь собственную информацию о контрольных точках или информацию о вершинах, основанную на контрольных точках.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### См. также

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Разделить сетку на подмеши с помощью [`VertexElementMaterial`](../../vertexelementmaterial/). Каждый подмеш будет использовать только один материал. Исходная сетка не будет изменена.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Возвращаемое значение

Новые разделённые сетки

## Примеры

Следующий код показывает, как разделить коробку на подмеши, используя индексы материалов.

```csharp
// Создайте сетку коробки (коробка состоит из 6 плоскостей)
Mesh box = (new Box()).ToMesh();
// Создайте элемент материала на этой сетке
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// И укажите разный индекс материала для каждой плоскости
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Теперь разделите её на 6 подмешей, мы указали 6 разных материалов на каждой плоскости, каждая плоскость станет подмешем.
// Мы использовали политику CloneData, каждая плоскость будет иметь одинаковую информацию о контрольных точках или информацию о вершинах, основанную на контрольных точках.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Теперь разделите её на 2 подмеша, первый меш будет содержать плоскости 0/1/2, а второй меш будет содержать плоскости 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Мы использовали политику CompactData, каждая плоскость будет иметь собственную информацию о контрольных точках или информацию о вершинах, основанную на контрольных точках.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### См. также

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


