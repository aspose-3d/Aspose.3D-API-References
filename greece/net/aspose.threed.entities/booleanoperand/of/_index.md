---
title: "BooleanOperand.Of"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος BooleanOperand. Δημιουργεί μια παρουσία BooleanOperand από έναν κόμβο, απαιτείται μια έγκυρη οντότητα που υλοποιεί το IMeshConvertible"
type: docs
weight: 10
url: /el/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

Δημιουργεί μια παρουσία [`BooleanOperand`](../) από έναν κόμβο, απαιτείται μια έγκυρη οντότητα που υλοποιεί το [`IMeshConvertible`](../../imeshconvertible/)

```csharp
public static BooleanOperand Of(Node node)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | Node | Μια παρουσία [`Node`](../../../aspose.threed/node/) με μια έγκυρη οντότητα που υλοποιεί το [`IMeshConvertible`](../../imeshconvertible/) |

### Τιμή επιστροφής

Μια παρουσία του [`BooleanOperand`](../)

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εγείρεται όταν το *node* είναι null. |
| InvalidOperationException | Εγείρεται όταν δεν βρεθεί καμία οντότητα που υλοποιεί το [`IMeshConvertible`](../../imeshconvertible/) κάτω από αυτόν τον κόμβο |

### Δείτε επίσης

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

Δημιουργεί μια παρουσία [`BooleanOperand`](../) από μια ακατέργαστη παρουσία [`IMeshConvertible`](../../imeshconvertible/).

```csharp
public static BooleanOperand Of(Entity mesh)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | Entity | Το πλέγμα που χρησιμοποιείται ως τελεστή της Boolean λειτουργίας, μπορεί να είναι μια παρουσία του [`IMeshConvertible`](../../imeshconvertible/) ή του [`HalfSpace`](../../halfspace/) |

### Τιμή επιστροφής

Μια παρουσία του [`BooleanOperand`](../)

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εγείρεται όταν το *mesh* είναι null. |

### Δείτε επίσης

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### Δείτε επίσης

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


