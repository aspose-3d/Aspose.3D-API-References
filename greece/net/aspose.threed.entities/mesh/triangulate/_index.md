---
title: "Mesh.Triangulate"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Mesh. Επιστρέφει το τριγωνοποιημένο πλέγμα"
type: docs
weight: 120
url: /el/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Επιστρέφει τριγωνοποιημένο πλέγμα

```csharp
public Mesh Triangulate()
```

### Τιμή επιστροφής

Τρέχον πλέγμα εάν το τρέχον πλέγμα είναι ήδη τριγωνοποιημένο, διαφορετικά θα υπολογιστεί και θα επιστραφεί ένα νέο τριγωνοποιημένο πλέγμα

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να τριγωνοποιήσετε ένα πλέγμα:

```csharp
//Το επίπεδο πλέγμα έχει μόνο ένα πολύγωνο με 4 σημεία ελέγχου
var mesh = (new Plane()).ToMesh();
//Μετά την τριγωνοποίηση, το νέο ορθογώνιο του πλέγματος θα γίνει 2 τρίγωνα.
var triangulated = mesh.Triangulate();
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


