---
title: "Mesh.CreatePolygon"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Mesh. Создаёт новый полигон со всеми вершинами, определёнными в индексах. Чтобы создавать полигон вершина за вершиной, пожалуйста, используйте PolygonBuilder"
type: docs
weight: 60
url: /ru/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

Создает новый полигон со всеми вершинами, определенными в *indices*. Чтобы создавать полигон вершина за вершиной, пожалуйста, используйте [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| индексы | Int32[] | Массив индексов полигона, каждый индекс указывает на контрольную точку, образующую полигон. |
| смещение | Int32 | Смещение первого индекса полигона |
| длина | Int32 | Длина индексов |

## Примеры

Следующий код показывает, как создать новый полигон с индексами контрольных точек.

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

Создает новый полигон со всеми вершинами, определенными в *indices*. Чтобы создавать полигон вершина за вершиной, пожалуйста, используйте [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| индексы | Int32[] | Массив индексов полигона, каждый индекс указывает на контрольную точку, образующую полигон. |

## Примеры

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

Создать полигон с 4 вершинами (четырёхугольник)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| v1 | Int32 | Индекс первой вершины |
| v2 | Int32 | Индекс второй вершины |
| v3 | Int32 | Индекс третьей вершины |
| v4 | Int32 | Индекс четвертой вершины |

## Примеры

Следующий код показывает, как создать новый полигон с индексами контрольных точек.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

Создать полигон с 3 вершинами (треугольник)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| v1 | Int32 | Индекс первой вершины |
| v2 | Int32 | Индекс второй вершины |
| v3 | Int32 | Индекс третьей вершины |

## Примеры

Следующий код показывает, как создать новый полигон с индексами контрольных точек.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### См. также

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


