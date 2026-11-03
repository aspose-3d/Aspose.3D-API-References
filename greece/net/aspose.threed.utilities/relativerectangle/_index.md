---
title: "Δομή RelativeRectangle"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Δομή Aspose.ThreeD.Utilities.RelativeRectangle. Σχετικό ορθογώνιο. Ο τύπος μεταξύ σχετικού στοιχείου και απόλυτης τιμής είναι Scale  Reference Width  offset. Έτσι, αν θέλουμε να αντιπροσωπεύει μια απόλυτη τιμή, αφήστε όλα τα πεδία κλίμακας μηδέν και χρησιμοποιήστε τα πεδία offset αντί αυτού."
type: docs
weight: 2830
url: /el/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Σχετικό ορθογώνιο. Ο τύπος μεταξύ του σχετικού στοιχείου και της απόλυτης τιμής είναι: Scale * (Reference Width) + offset. Έτσι, αν θέλουμε να αντιπροσωπεύει μια απόλυτη τιμή, αφήστε όλα τα πεδία κλίμακας στο μηδέν και χρησιμοποιήστε τα πεδία offset αντί αυτού.

```csharp
public struct RelativeRectangle
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | Δημιουργία ενός `RelativeRectangle` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | Λαμβάνει ή ορίζει το offset για το ύψος |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | Λαμβάνει ή ορίζει το offset για το πλάτος |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | Λαμβάνει ή ορίζει το offset για τη συντεταγμένη X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | Λαμβάνει ή ορίζει το offset για τη συντεταγμένη Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | Σχετικό ύψος |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | Σχετικό πλάτος |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | Σχετική συντεταγμένη X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | Σχετική συντεταγμένη Y |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | Δημιουργήστε ένα `RelativeRectangle` με όλα τα πεδία offset μηδέν και τα πεδία κλίμακας από τις δοσμένες παραμέτρους. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | Μετατρέψτε το σχετικό ορθογώνιο σε απόλυτο ορθογώνιο |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | Μετατρέπει την τιμή αυτού του αντικειμένου σε String. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


