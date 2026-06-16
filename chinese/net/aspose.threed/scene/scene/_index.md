---
title: "Scene.Scene"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 构造函数。初始化 Scene 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.threed/scene/scene/
---
## Scene() {#constructor}

初始化 [`Scene`](../) 类的新实例。

```csharp
public Scene()
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Entity) {#constructor_1}

初始化 [`Scene`](../) 类的新实例，并将实体附加到新节点。

```csharp
public Scene(Entity entity)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 附加到场景的初始实体 |

## 示例

以下代码展示了如何直接从 [`Entity`](../../entity/) 创建 [`Scene`](../)：

```csharp
var scene = new Scene(new Box());
```

### 另请参见

* class [Entity](../../entity/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Scene, string) {#constructor_2}

初始化 [`Scene`](../) 类的新实例作为子场景。

```csharp
public Scene(Scene parentScene, string name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentScene | 场景 | 父场景。 |
| 名称 | 字符串 | Scene 的名称。 |

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


