---
title: "BooleanOperand.Of"
second_title: "Aspose.3D för .NET API‑referens"
description: "BooleanOperand metod. Skapa en BooleanOperand-instans från en nod, ett giltigt objekt som implementerar IMeshConvertible krävs"
type: docs
weight: 10
url: /sv/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Skapa en [`BooleanOperand`](../)-instans från en nod, ett giltigt objekt som implementerar [`IMeshConvertible`](../../imeshconvertible/) krävs

```csharp
public static BooleanOperand Of(Node node)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | Node | En [`Node`](../../../aspose.threed/node/)-instans med ett giltigt objekt som implementerar [`IMeshConvertible`](../../imeshconvertible/) |

### Returvärde

En instans av [`BooleanOperand`](../)

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Utlöst när *node* är null. |
| InvalidOperationException | Utlöst när ingen entitet som implementerar [`IMeshConvertible`](../../imeshconvertible/) hittas under denna nod |

### Se även

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Skapa en [`BooleanOperand`](../)-instans från en rå [`IMeshConvertible`](../../imeshconvertible/)-instans.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | Entity | Det mesh som används som operand för en Boolean-operation, den kan vara en instans av [`IMeshConvertible`](../../imeshconvertible/) eller [`HalfSpace`](../../halfspace/) |

### Returvärde

En instans av [`BooleanOperand`](../)

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Utlöst när *mesh* är null. |

### Se även

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Se även

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


