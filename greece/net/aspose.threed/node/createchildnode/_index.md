---
title: "Node.CreateChildNode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Δημιουργεί έναν υποκόμβο."
type: docs
weight: 170
url: /el/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

Δημιουργεί έναν υποκόμβο

```csharp
public Node CreateChildNode()
```

### Τιμή επιστροφής

Ο νέος υποκόμβος.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν νέο υποκόμβο κάτω από τον ριζικό κόμβο.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

Δημιουργεί έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου

```csharp
public Node CreateChildNode(string nodeName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | String | Το όνομα του νέου υποκόμβου |

### Τιμή επιστροφής

Ο νέος υποκόμβος.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν νέο υποκόμβο κάτω από τον ριζικό κόμβο.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

Δημιουργεί έναν νέο υποκόμβο με την δεδομένη οντότητα συνδεδεμένη

```csharp
public Node CreateChildNode(Entity entity)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οντότητα | Οντότητα | Προεπιλεγμένη οντότητα συνδεδεμένη με τον κόμβο |

### Τιμή επιστροφής

Ο νέος υποκόμβος.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν νέο υποκόμβο κάτω από τον ριζικό κόμβο.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### Δείτε επίσης

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

Δημιουργεί έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | String | Το όνομα του νέου υποκόμβου |
| οντότητα | Οντότητα | Προεπιλεγμένη οντότητα συνδεδεμένη με τον κόμβο |

### Τιμή επιστροφής

Ο νέος υποκόμβος.

### Δείτε επίσης

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

Δημιουργεί έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου και συνδέει την καθορισμένη οντότητα και ένα υλικό

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | String | Το όνομα του νέου υποκόμβου |
| οντότητα | Οντότητα | Προεπιλεγμένη οντότητα συνδεδεμένη με τον κόμβο |
| υλικό | Υλικό | Το υλικό συνδεδεμένο με τον κόμβο |

### Τιμή επιστροφής

Ο νέος υποκόμβος.

### Δείτε επίσης

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


