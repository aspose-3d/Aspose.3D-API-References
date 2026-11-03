---
title: "BooleanOperand.Of"
second_title: "Aspose.3D für .NET API-Referenz"
description: "BooleanOperand-Methode. Erstellt eine BooleanOperand-Instanz aus einem Knoten; ein gültiges Entity, das IMeshConvertible implementiert, ist erforderlich"
type: docs
weight: 10
url: /de/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Erstelle eine [`BooleanOperand`](../)-Instanz aus einem Knoten, ein gültiges Entity, das [`IMeshConvertible`](../../imeshconvertible/) implementiert, ist erforderlich

```csharp
public static BooleanOperand Of(Node node)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | Node | Eine [`Node`](../../../aspose.threed/node/)-Instanz mit einem gültigen Entity, das [`IMeshConvertible`](../../imeshconvertible/) implementiert |

### Rückgabewert

Eine Instanz von [`BooleanOperand`](../)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *node* null ist. |
| InvalidOperationException | Wird ausgelöst, wenn unter diesem Knoten kein Entity gefunden wird, das [`IMeshConvertible`](../../imeshconvertible/) implementiert |

### Siehe auch

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Erstellen Sie eine [`BooleanOperand`](../)-Instanz aus einer nackten [`IMeshConvertible`](../../imeshconvertible/)-Instanz.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mesh | Entity | Das Mesh, das als Operand der Booleschen Operation verwendet wird, kann eine Instanz von [`IMeshConvertible`](../../imeshconvertible/) oder [`HalfSpace`](../../halfspace/) sein. |

### Rückgabewert

Eine Instanz von [`BooleanOperand`](../)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *mesh* null ist. |

### Siehe auch

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Siehe auch

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


