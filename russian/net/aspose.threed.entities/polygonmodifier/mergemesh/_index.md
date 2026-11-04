---
title: "PolygonModifier.MergeMesh"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PolygonModifier. Преобразовать всю сцену в одну трансформированную сетку. Элементы вершины, такие как нормали/текстурные координаты, пока не поддерживаются."
type: docs
weight: 50
url: /ru/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

Преобразовать всю сцену в одну трансформированную Mesh. Элементы вершины, такие как нормали/текстурные координаты, пока не поддерживаются.

```csharp
public static Mesh MergeMesh(Scene scene)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сцена | Сцена | Сцена для объединения |

### Возвращаемое значение

Объединённая сетка

## Примеры

Следующий код показывает, как объединить все объекты из сцены в один меш.

```csharp
//Входной файл может содержать несколько объектов
var scene = Scene.FromFile("input.fbx");
//теперь объедините их в одну сетку
Mesh merged = PolygonModifier.MergeMesh(scene);
//затем сохраняем его в файл, содержащий только одну сетку
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### См. также

* class [Mesh](../../mesh/)
* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(IList&lt;Node&gt;) {#mergemesh_2}

```csharp
public static Mesh MergeMesh(IList<Node> nodes)
```

### См. также

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

Преобразовать весь узел в одну трансформированную Mesh. Элементы вершины, такие как нормали/текстурные координаты, пока не поддерживаются.

```csharp
public static Mesh MergeMesh(Node node)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | Узел | Узел для объединения |

### Возвращаемое значение

Объединённая сетка

## Примеры

Следующий код показывает, как объединить все объекты из узлов в одну сетку.

```csharp
//Входной файл может содержать несколько объектов
var scene = Scene.FromFile("input.fbx");
//теперь объедините их в одну сетку
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//затем сохраняем его в файл, содержащий только одну сетку
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### См. также

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


