---
title: PolygonModifier
second_title: Справочник по Aspose.3D для .NET API
description: Утилиты для модификации полигонов
type: docs
weight: 560
url: /ru/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Утилиты для модификации полигонов

```csharp
public class PolygonModifier
```

## Методы

| Имя | Описание |
| --- | --- |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal#buildtangentbinormal)(Mesh) | Это создаст касательную и бинормали на сетке. Требуется нормаль. Если нормали не существует в сетке, также будут созданы данные нормали из положения. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal#buildtangentbinormal_1)(Scene) | Это создаст касательную и бинормали на всех мешах сцены Требуется нормаль, если нормаль не существует в меше, также будут созданы данные нормалей из положения. Также требуется UV, меш будет игнорироваться, если нет UV определено. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal)(Mesh) | Генерировать нормальные данные из определения сетки |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv#generateuv)(Mesh) | Генерировать данные UV из заданного входного меша |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv#generateuv_1)(Mesh, VertexElementNormal) | Генерировать UV-данные из заданного входного меша и заданных данных нормалей. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh#mergemesh)(Node) | Преобразование целого узла в единую преобразованную сетку Вершинные элементы, такие как координаты нормали/текстуры, пока не поддерживаются |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh#mergemesh_1)(Scene) | Преобразование всей сцены в единую трансформированную сетку Вершинные элементы, такие как координаты нормали/текстуры, пока не поддерживаются |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale#scale_1)(Node, Vector3) | Масштабировать все геометрии (масштабировать контрольные точки, а не матрицу преобразования) в этом узле |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale#scale)(Scene, Vector3) | Масштабируйте все геометрии (масштабируйте контрольные точки, а не матрицу преобразования) в этой сцене |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh#splitmesh)(Mesh, SplitMeshPolicy) | Разделить сетку на подсетки с помощью[`VertexElementMaterial`](../vertexelementmaterial) . Каждая подсетка будет использовать только один материал. Исходная сетка не будет изменена. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Разделить сетку на подсетки с помощью[`VertexElementMaterial`](../vertexelementmaterial) . Каждая подсетка будет использовать только один материал. Выполнить разделение сетки на всех узлах сцены. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Разделить сетку на подсетки с помощью[`VertexElementMaterial`](../vertexelementmaterial) . Каждая подсетка будет использовать только один материал. Выполнить разделение сетки на узле |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate)(Mesh) | Преобразовать полигональную сетку в полную треугольную сетку |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_5)(Scene) | Преобразование всех полигональных сеток в полные треугольные сетки |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### Смотрите также

* пространство имен [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
