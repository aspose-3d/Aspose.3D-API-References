---
title: "Mesh.Optimize"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Mesh. Оптимизирует использование памяти сеткой, устраняя дублированные контрольные точки"
type: docs
weight: 100
url: /ru/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

Оптимизируйте использование памяти сеткой, устраняя дублированные контрольные точки

```csharp
public Mesh Optimize(bool vertexElements)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexElements | Boolean | Оптимизировать дублированные данные элементов вершин |

### Возвращаемое значение

Новый экземпляр сетки с компактным использованием памяти

## Примеры

Следующий код показывает, как удалить дублированные контрольные точки из неоптимизированной сетки:

```csharp
//Sphere.ToMesh генерирует 117 контрольных точек
var mesh = (new Sphere()).ToMesh();
//После оптимизации осталось только 86 контрольных точек, индексы полигонов также переименованы.
var optimized = mesh.Optimize(true);
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

Оптимизируйте использование памяти сеткой, устраняя дублированные контрольные точки

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexElements | Boolean | Оптимизировать дублированные данные элементов вершин |
| toleranceControlPoint | Single | Допуск для контрольной точки, значение по умолчанию 1e-9 |
| toleranceNormal | Single | Допуск для нормали/касательной/бинормали, значение по умолчанию 1e-9 |
| toleranceUV | Single | Допуск для uv, значение по умолчанию 1e-9 |

### Возвращаемое значение

Новый экземпляр сетки с компактным использованием памяти

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


