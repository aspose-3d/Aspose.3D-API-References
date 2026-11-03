---
title: "Κλάση PolygonBuilder"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.PolygonBuilder. Μια βοηθητική κλάση για τη δημιουργία πολυγώνου για Mesh."
type: docs
weight: 610
url: /el/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Μια βοηθητική κλάση για τη δημιουργία πολυγώνου για [`Mesh`](../mesh/).

```csharp
public sealed class PolygonBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PolygonBuilder`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | Προσθέτει έναν δείκτη κορυφής στο πολύγωνο |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | Ξεκινά να προσθέτει ένα νέο πολύγωνο |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | Ολοκληρώνει τη δημιουργία του πολυγώνου |

## Παραδείγματα

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

Ισούται με :

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

Εάν όλοι οι δείκτες είναι έτοιμοι για χρήση, προτιμάται το [`CreatePolygon`](../mesh/createpolygon/), διαφορετικά το `PolygonBuilder` θα ήταν καλύτερη επιλογή.

### Δείτε επίσης

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


