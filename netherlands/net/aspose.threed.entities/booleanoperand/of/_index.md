---
title: "BooleanOperand.Of"
second_title: "Aspose.3D voor .NET API-referentie"
description: "BooleanOperand-methode. Maak een BooleanOperand‑instantie aan vanuit een knoop; een geldige entiteit die IMeshConvertible implementeert, is vereist"
type: docs
weight: 10
url: /nl/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Construeer een [`BooleanOperand`](../) instantie vanuit een knooppunt, een geldige entiteit die [`IMeshConvertible`](../../imeshconvertible/) implementeert is vereist.

```csharp
public static BooleanOperand Of(Node node)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | Node | Een [`Node`](../../../aspose.threed/node/) instantie met een geldige entiteit die [`IMeshConvertible`](../../imeshconvertible/) implementeert. |

### Retourwaarde

Een instantie van [`BooleanOperand`](../).

### Exceptions

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | Wordt opgegooid wanneer *node* null is. |
| InvalidOperationException | Wordt opgegooid wanneer er geen entiteit die [`IMeshConvertible`](../../imeshconvertible/) implementeert onder dit knooppunt wordt gevonden. |

### Zie ook

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Construeer een [`BooleanOperand`](../) instantie vanuit een kale [`IMeshConvertible`](../../imeshconvertible/) instantie.

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | Entity | De mesh die wordt gebruikt als operand van de Booleaanse bewerking, kan een instantie zijn van [`IMeshConvertible`](../../imeshconvertible/) of [`HalfSpace`](../../halfspace/). |

### Retourwaarde

Een instantie van [`BooleanOperand`](../).

### Exceptions

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | Wordt opgegooid wanneer *mesh* null is. |

### Zie ook

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Zie ook

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


