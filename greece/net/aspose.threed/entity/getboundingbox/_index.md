---
title: "Entity.GetBoundingBox"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Entity μέθοδος. Λαμβάνει το πλαίσιο περιγράμματος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της"
type: docs
weight: 50
url: /el/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της.

```csharp
public BoundingBox GetBoundingBox()
```

### Τιμή επιστροφής

το πλαίσιο περιγράμματος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να υπολογίσετε το πλαίσιο περιγράμματος ενός σχήματος

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### Δείτε επίσης

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)


