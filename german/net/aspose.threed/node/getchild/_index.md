---
title: "Node.GetChild"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Methode. Gibt den Kindknoten am angegebenen Index zurück"
type: docs
weight: 200
url: /de/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

Liefert den untergeordneten Node am angegebenen Index.

```csharp
public Node GetChild(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index. |

### Rückgabewert

Das Kind.

## Beispiele

Der folgende Code zeigt, wie man einen Kindknoten am angegebenen Index erhält.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

Liefert den untergeordneten Node mit dem angegebenen Namen.

```csharp
public Node GetChild(string nodeName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der zu findende Kindname. |

### Rückgabewert

Das Kind.

## Beispiele

Der folgende Code zeigt, wie man einen Kindknoten mit angegebenem Namen erhält.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


