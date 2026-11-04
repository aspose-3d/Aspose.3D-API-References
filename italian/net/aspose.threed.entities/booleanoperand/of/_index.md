---
title: "BooleanOperand.Of"
second_title: "Riferimento API Aspose.3D per .NET"
description: "metodo BooleanOperand. Costruisce un'istanza di BooleanOperand da un nodo; è richiesto un'entità valida che implementi IMeshConvertible"
type: docs
weight: 10
url: /it/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Costruisci un'istanza di [`BooleanOperand`](../) da un nodo, è richiesta un'entità valida che implementi [`IMeshConvertible`](../../imeshconvertible/)

```csharp
public static BooleanOperand Of(Node node)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | Node | Un'istanza di [`Node`](../../../aspose.threed/node/) con un'entità valida che implementa [`IMeshConvertible`](../../imeshconvertible/) |

### Valore di ritorno

Un'istanza di [`BooleanOperand`](../)

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *node* è nullo. |
| InvalidOperationException | Generato quando non è stata trovata alcuna entità che implementa [`IMeshConvertible`](../../imeshconvertible/) sotto questo nodo |

### Vedi anche

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Costruisci un'istanza di [`BooleanOperand`](../) da una semplice istanza di [`IMeshConvertible`](../../imeshconvertible/).

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | Entity | La mesh usata come operando dell'operazione booleana, può essere un'istanza di [`IMeshConvertible`](../../imeshconvertible/) o di [`HalfSpace`](../../halfspace/) |

### Valore di ritorno

Un'istanza di [`BooleanOperand`](../)

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *mesh* è nullo. |

### Vedi anche

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Vedi anche

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


