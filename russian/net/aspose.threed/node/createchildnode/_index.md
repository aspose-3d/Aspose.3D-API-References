---
title: "Node.CreateChildNode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Node. Создаёт дочерний узел."
type: docs
weight: 170
url: /ru/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

Создает дочерний узел

```csharp
public Node CreateChildNode()
```

### Возвращаемое значение

Новый дочерний узел.

## Примеры

Следующий код показывает, как создать новый дочерний узел под корневым узлом.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

Создать новый дочерний узел с заданным именем узла

```csharp
public Node CreateChildNode(string nodeName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя нового дочернего узла |

### Возвращаемое значение

Новый дочерний узел.

## Примеры

Следующий код показывает, как создать новый дочерний узел под корневым узлом.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### См. также

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

Создать новый дочерний узел с прикрепленной заданной сущностью

```csharp
public Node CreateChildNode(Entity entity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Стандартная сущность, прикреплённая к узлу |

### Возвращаемое значение

Новый дочерний узел.

## Примеры

Следующий код показывает, как создать новый дочерний узел под корневым узлом.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### См. также

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

Создать новый дочерний узел с заданным именем узла

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя нового дочернего узла |
| сущность | Сущность | Стандартная сущность, прикреплённая к узлу |

### Возвращаемое значение

Новый дочерний узел.

### См. также

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

Создать новый дочерний узел с заданным именем узла и прикрепить указанную сущность и материал

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeName | String | Имя нового дочернего узла |
| сущность | Сущность | Стандартная сущность, прикреплённая к узлу |
| материал | Материал | Материал, прикреплённый к узлу |

### Возвращаемое значение

Новый дочерний узел.

### См. также

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


