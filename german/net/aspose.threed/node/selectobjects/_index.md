---
title: "Node.SelectObjects"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Methode. Wählt mehrere Objekte unter dem aktuellen Node mit einer XPath-ähnlichen Abfragesyntax aus."
type: docs
weight: 230
url: /de/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

Wählen Sie mehrere Objekte unter dem aktuellen Knoten mit einer XPath-ähnlichen Abfragesyntax aus.

```csharp
public List<object> SelectObjects(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Die XPath‑ähnliche Abfrage |

### Rückgabewert

Mehrere Objekte entsprechen der XPath-ähnlichen Abfrage.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | ParseException wird ausgelöst, wenn der Pfad eine fehlerhafte Abfrage enthält. |

## Beispiele

Wählt einen einzelnen Knoten mittels XPath‑ähnlichem Ausdruck aus

```csharp
//Erstelle eine Szene zum Testen
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//Wählt Objekte aus, die den Typ Kamera haben oder deren Name 'light' ist, egal wo sie sich befinden.
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


