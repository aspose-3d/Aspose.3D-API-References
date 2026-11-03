---
title: "IOConfig.LookupPaths"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα IOConfig. Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικά αρχεία· οι διαδρομές αναζήτησης επιτρέπουν στο Aspose.3D να εντοπίζει εξωτερικά αρχεία για φόρτωση"
type: docs
weight: 50
url: /el/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση.

```csharp
public List<string> LookupPaths { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να καθορίσετε χειροκίνητα τις υφές αναζήτησης, ώστε ο εισαγωγέας να μπορεί να τις βρει

```csharp
var opt = new ObjLoadOptions();
//Καθορίστε τις διαδρομές αναζήτησης, ώστε οι υφές να εντοπιστούν.
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### Δείτε επίσης

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


