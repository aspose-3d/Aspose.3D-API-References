---
title: "Класс PolygonBuilder"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.PolygonBuilder. Вспомогательный класс для построения полигонов для Mesh"
type: docs
weight: 610
url: /ru/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Вспомогательный класс для построения полигонов для [`Mesh`](../mesh/)

```csharp
public sealed class PolygonBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | Инициализирует новый экземпляр класса `PolygonBuilder`. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | Добавляет индекс вершины к полигону |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | Начинает добавлять новый полигон |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | Завершает создание полигона |

## Примеры

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

Равно :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Если все индексы готовы к использованию, предпочтительно использовать [`CreatePolygon`](../mesh/createpolygon/), иначе `PolygonBuilder` будет лучшим выбором.

### См. также

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


