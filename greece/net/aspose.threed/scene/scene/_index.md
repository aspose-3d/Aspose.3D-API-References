---
title: "Scene.Scene"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κατασκευαστής Scene. Δημιουργεί ένα νέο στιγμιότυπο της κλάσης Scene"
type: docs
weight: 10
url: /el/net/aspose.threed/scene/scene/
---
## Scene() {#constructor}

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [`Scene`](../).

```csharp
public Scene()
```

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Entity) {#constructor_1}

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [`Scene`](../) με μια οντότητα συνδεδεμένη σε έναν νέο κόμβο.

```csharp
public Scene(Entity entity)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Η αρχική οντότητα που συνδέθηκε στη σκηνή |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα [`Scene`](../) απευθείας από ένα [`Entity`](../../entity/):

```csharp
var scene = new Scene(new Box());
```

### Δείτε επίσης

* class [Entity](../../entity/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Scene, string) {#constructor_2}

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [`Scene`](../) ως υπο-σκηνή.

```csharp
public Scene(Scene parentScene, string name)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parentScene | Σκηνή | Η γονική σκηνή. |
| όνομα | String | Το όνομα της σκηνής. |

### Δείτε επίσης

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


