---
title: "Scene.Scene"
second_title: "Справочник API Aspose.3D для .NET"
description: "Конструктор Scene. Инициализирует новый экземпляр класса Scene"
type: docs
weight: 10
url: /ru/net/aspose.threed/scene/scene/
---
## Scene() {#constructor}

Инициализирует новый экземпляр класса [`Scene`](../).

```csharp
public Scene()
```

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Entity) {#constructor_1}

Инициализирует новый экземпляр класса [`Scene`](../) с сущностью, прикреплённой к новому узлу.

```csharp
public Scene(Entity entity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Исходная сущность, прикреплённая к сцене. |

## Примеры

Следующий код показывает, как создать [`Scene`](../) напрямую из [`Entity`](../../entity/):

```csharp
var scene = new Scene(new Box());
```

### См. также

* class [Entity](../../entity/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Scene, string) {#constructor_2}

Инициализирует новый экземпляр класса [`Scene`](../) как подсцену.

```csharp
public Scene(Scene parentScene, string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentScene | Сцена | Родительская сцена. |
| name | String | Имя сцены. |

### См. также

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


