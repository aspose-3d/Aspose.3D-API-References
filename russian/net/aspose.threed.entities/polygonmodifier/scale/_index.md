---
title: "PolygonModifier.Scale"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PolygonModifier. Масштабировать все геометрии. Масштабировать контрольные точки, а не матрицу преобразования в этой сцене."
type: docs
weight: 60
url: /ru/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

Масштабировать все геометрии (масштабировать контрольные точки, а не матрицу преобразования) в этой сцене

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сцена | Сцена | Сцена для масштабирования |
| масштаб | Vector3 | Коэффициент масштабирования |

## Примеры

Следующий код показывает, как масштабировать все геометрии в сцене в 10 раз.

```csharp
//Загрузить тестовый файл для масштабирования
var scene = Scene.FromFile("input.fbx");
//масштабировать все геометрии в 10 раз.
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### См. также

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

Масштабировать все геометрии (масштабировать контрольные точки, а не матрицу преобразования) в этом узле

```csharp
public static void Scale(Node node, Vector3 scale)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | Узел | Узел для масштабирования |
| масштаб | Vector3 | Коэффициент масштабирования |

## Примеры

Следующий код показывает, как масштабировать все геометрии в сцене в 10 раз.

```csharp
//Загрузить тестовый файл для масштабирования
var scene = Scene.FromFile("input.fbx");
//масштабировать все геометрии в 10 раз.
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### См. также

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


