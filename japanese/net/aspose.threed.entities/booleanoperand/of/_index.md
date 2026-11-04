---
title: "BooleanOperand.Of"
second_title: "Aspose.3D for .NET API リファレンス"
description: "BooleanOperand method. ノードから BooleanOperand インスタンスを構築します。有効なエンティティで IMeshConvertible を実装していることが必要です"
type: docs
weight: 10
url: /ja/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

ノードから[`BooleanOperand`](../)インスタンスを構築します。有効なエンティティで[`IMeshConvertible`](../../imeshconvertible/)が実装されている必要があります。

```csharp
public static BooleanOperand Of(Node node)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| node | Node | 有効なエンティティで[`IMeshConvertible`](../../imeshconvertible/)が実装された[`Node`](../../../aspose.threed/node/)インスタンス |

### 戻り値

[`BooleanOperand`](../)のインスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *node* が null のときにスローされます。 |
| InvalidOperationException | このノードの下で[`IMeshConvertible`](../../imeshconvertible/)が実装されたエンティティが見つからないときにスローされます。 |

### 関連項目

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

裸の[`IMeshConvertible`](../../imeshconvertible/)インスタンスから[`BooleanOperand`](../)インスタンスを構築します。

```csharp
public static BooleanOperand Of(Entity mesh)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mesh | Entity | ブール演算のオペランドとして使用されるメッシュで、[`IMeshConvertible`](../../imeshconvertible/)または[`HalfSpace`](../../halfspace/)のインスタンスにすることができます。 |

### 戻り値

[`BooleanOperand`](../)のインスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *mesh* が null のときにスローされます。 |

### 関連項目

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### 関連項目

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


