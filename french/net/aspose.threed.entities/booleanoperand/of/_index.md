---
title: "BooleanOperand.Of"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode BooleanOperand. Construit une instance de BooleanOperand à partir d'un nœud ; une entité valide implémentant IMeshConvertible est requise"
type: docs
weight: 10
url: /fr/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Construit une instance de [`BooleanOperand`](../) à partir d'un nœud, une entité valide implémentant [`IMeshConvertible`](../../imeshconvertible/) est requise

```csharp
public static BooleanOperand Of(Node node)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| node | Node | Une instance de [`Node`](../../../aspose.threed/node/) avec une entité valide implémentant [`IMeshConvertible`](../../imeshconvertible/) |

### Valeur de retour

Une instance de [`BooleanOperand`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Déclenchée lorsque *node* est nul. |
| InvalidOperationException | Déclenchée lorsqu'aucune entité implémentant [`IMeshConvertible`](../../imeshconvertible/) n'est trouvée sous ce nœud |

### Voir aussi

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Construit une instance de [`BooleanOperand`](../) à partir d'une instance brute de [`IMeshConvertible`](../../imeshconvertible/).

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | Entity | Le maillage utilisé comme opérande de l'opération booléenne, il peut être une instance de [`IMeshConvertible`](../../imeshconvertible/) ou de [`HalfSpace`](../../halfspace/) |

### Valeur de retour

Une instance de [`BooleanOperand`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Déclenchée lorsque *mesh* est nul. |

### Voir aussi

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Voir aussi

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


