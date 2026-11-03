---
title: "Διεπαφή ITextureUnit"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Render.ITextureUnit διεπαφή. Το ITextureUnit αντιπροσωπεύει μια υφή στη μνήμη που μοιράζεται μεταξύ GPU και CPU και μπορεί να δειγματοληπτεί από το shader, όπου η Texture αντιπροσωπεύει μόνο μια αναφορά σε εξωτερικό αρχείο. Περισσότερες λεπτομέρειες μπορούν να βρεθούν https//en.wikipedia.org/wiki/Texture_mapping_unit"
type: docs
weight: 2170
url: /el/net/aspose.threed.render/itextureunit/
---
## ITextureUnit interface

`ITextureUnit` αντιπροσωπεύει μια υφή στη μνήμη που μοιράζεται μεταξύ GPU και CPU και μπορεί να δειγματοληπτεί από το shader, όπου η [`Texture`](../../aspose.threed.shading/texture/) αντιπροσωπεύει μόνο μια αναφορά σε εξωτερικό αρχείο. Περισσότερες λεπτομέρειες μπορούν να βρεθούν https://en.wikipedia.org/wiki/Texture_mapping_unit

```csharp
public interface ITextureUnit : IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Depth](../../aspose.threed.render/itextureunit/depth/) { get; } | Επιστρέφει το ύψος αυτής της υφής, για μη-3D υφή είναι πάντα 1. |
| [Height](../../aspose.threed.render/itextureunit/height/) { get; } | Επιστρέφει το ύψος αυτής της υφής. |
| [Magnification](../../aspose.threed.render/itextureunit/magnification/) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία φίλτρου για μεγέθυνση. |
| [Minification](../../aspose.threed.render/itextureunit/minification/) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία φίλτρου για σμίκρυνση. |
| [Mipmap](../../aspose.threed.render/itextureunit/mipmap/) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία φίλτρου για mipmap. |
| [Scale](../../aspose.threed.render/itextureunit/scale/) { get; set; } | Επιστρέφει ή ορίζει την κλίμακα της συντεταγμένης UV. |
| [Scroll](../../aspose.threed.render/itextureunit/scroll/) { get; set; } | Επιστρέφει ή ορίζει την κύλιση της συντεταγμένης UV. |
| [Type](../../aspose.threed.render/itextureunit/type/) { get; } | Επιστρέφει τον τύπο αυτής της μονάδας υφής. |
| [UWrap](../../aspose.threed.render/itextureunit/uwrap/) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη U της υφής. |
| [VWrap](../../aspose.threed.render/itextureunit/vwrap/) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη V της υφής. |
| [Width](../../aspose.threed.render/itextureunit/width/) { get; } | Επιστρέφει το πλάτος αυτής της υφής. |
| [WWrap](../../aspose.threed.render/itextureunit/wwrap/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία περιτύλιξης για τη συντεταγμένη W της υφής. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


