---
title: "Node.Merge"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Methode. Alles unter dem Knoten lösen und an den aktuellen Knoten anhängen"
type: docs
weight: 220
url: /de/net/aspose.threed/node/merge/
---
## Node.Merge method

Lösen Sie alles unter dem Knoten und hängen Sie es an den aktuellen Knoten an.

```csharp
public void Merge(Node node)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten |  |

## Beispiele

Der folgende Code zeigt, wie man zwei 3D-Dateien zu einer Datei zusammenführt

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


