---
title: BooleanOperand.Of
second_title: Aspose.3D for .NET API 参考手册
description: BooleanOperand 方法。构造一个 BooleanOperand 实例，需要从节点提供一个实现了 IMeshConvertible 的有效实体
type: docs
weight: 10
url: /zh/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

构造一个 [`BooleanOperand`](../) 实例，需要从节点提供一个实现了 [`IMeshConvertible`](../../imeshconvertible/) 的有效实体

```csharp
public static BooleanOperand Of(Node node)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | Node | 一个具有实现了 [`IMeshConvertible`](../../imeshconvertible/) 的有效实体的 [`Node`](../../../aspose.threed/node/) 实例 |

### 返回值

一个 [`BooleanOperand`](../) 实例

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *node* 为 null 时抛出。 |
| InvalidOperationException | 当在此节点下未找到实现了 [`IMeshConvertible`](../../imeshconvertible/) 的实体时抛出 |

### 另请参见

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

从一个裸露的 [`IMeshConvertible`](../../imeshconvertible/) 实例构造一个 [`BooleanOperand`](../) 实例。

```csharp
public static BooleanOperand Of(Entity mesh)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | Entity | 用作布尔运算操作数的网格，它可以是 [`IMeshConvertible`](../../imeshconvertible/) 或 [`HalfSpace`](../../halfspace/) 的实例 |

### 返回值

一个 [`BooleanOperand`](../) 实例

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *mesh* 为 null 时抛出。 |

### 另请参见

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### 另请参见

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


