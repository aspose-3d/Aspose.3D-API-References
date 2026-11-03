---
title: "Scene.Scene"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Konstruktor. Initialisiert eine neue Instanz der Scene-Klasse"
type: docs
weight: 10
url: /de/net/aspose.threed/scene/scene/
---
## Scene() {#constructor}

Initialisiert eine neue Instanz der [`Scene`](../)-Klasse.

```csharp
public Scene()
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Entity) {#constructor_1}

Initialisiert eine neue Instanz der [`Scene`](../)-Klasse mit einer Entität, die an einen neuen Knoten angehängt ist.

```csharp
public Scene(Entity entity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die anfängliche Entität, die an die Szene angehängt ist |

## Beispiele

Der folgende Code zeigt, wie man ein [`Scene`](../) direkt aus einer [`Entity`](../../entity/) erstellt:

```csharp
var scene = new Scene(new Box());
```

### Siehe auch

* class [Entity](../../entity/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Scene, string) {#constructor_2}

Initialisiert eine neue Instanz der [`Scene`](../)-Klasse als Unterszene.

```csharp
public Scene(Scene parentScene, string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentScene | Scene | Die übergeordnete Szene. |
| name | String | Name der Szene. |

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


