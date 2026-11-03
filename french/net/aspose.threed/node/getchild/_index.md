---
title: "Node.GetChild"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Obtient le nœud enfant à l'index spécifié"
type: docs
weight: 200
url: /fr/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

Obtient le nœud enfant à l'index spécifié.

```csharp
public Node GetChild(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index. |

### Valeur de retour

L'enfant.

## Exemples

Le code suivant montre comment obtenir un nœud enfant à l'index spécifié.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

Obtient le nœud enfant avec le nom spécifié

```csharp
public Node GetChild(string nodeName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom de l'enfant à trouver. |

### Valeur de retour

L'enfant.

## Exemples

Le code suivant montre comment obtenir un nœud enfant avec le nom spécifié

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


