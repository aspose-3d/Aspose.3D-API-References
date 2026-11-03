---
title: "Scene.Scene"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Constructeur de Scene. Initialise une nouvelle instance de la classe Scene"
type: docs
weight: 10
url: /fr/net/aspose.threed/scene/scene/
---
## Scene() {#constructor}

Initialise une nouvelle instance de la classe [`Scene`](../).

```csharp
public Scene()
```

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Entity) {#constructor_1}

Initialise une nouvelle instance de la classe [`Scene`](../) avec une entité attachée à un nouveau nœud.

```csharp
public Scene(Entity entity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité initiale attachée à la scène |

## Exemples

Le code suivant montre comment créer un [`Scene`](../) directement à partir d'un [`Entity`](../../entity/):

```csharp
var scene = new Scene(new Box());
```

### Voir aussi

* class [Entity](../../entity/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Scene, string) {#constructor_2}

Initialise une nouvelle instance de la classe [`Scene`](../) en tant que sous‑scène.

```csharp
public Scene(Scene parentScene, string name)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| parentScene | Scène | La scène parente. |
| nom | String | Nom de la scène. |

### Voir aussi

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


