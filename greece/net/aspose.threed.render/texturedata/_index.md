---
title: "Κλάση TextureData"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Render.TextureData κλάση. Αυτή η κλάση περιέχει τα ακατέργαστα δεδομένα και τον ορισμό μορφής μιας υφής"
type: docs
weight: 2460
url: /el/net/aspose.threed.render/texturedata/
---
## TextureData class

Αυτή η κλάση περιέχει τα ακατέργαστα δεδομένα και τον ορισμό μορφής μιας υφής.

```csharp
public class TextureData : A3DObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TextureData](texturedata/#constructor)() | Κατασκευαστής του `TextureData` |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | Δημιουργεί ένα νέο `TextureData` και εκχωρεί δεδομένα εικονοστοιχείου. |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | Κατασκευαστής του `TextureData` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | Αριθμός byte ενός εικονοστοιχείου |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | Ακατέργαστα byte δεδομένων εικονοστοιχείου |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | Αριθμός κάθετων εικονοστοιχείων |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | Η μορφή του εικονοστοιχείου |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | Αριθμός byte μιας γραμμής σάρωσης. |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | Αριθμός οριζόντιων εικονοστοιχείων |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | Φόρτωση υφής από αρχείο |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | Φόρτωση υφής από ροή |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | Αντιστοίχηση όλων των εικονοστοιχείων για ανάγνωση/εγγραφή |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | Αντιστοίχηση όλων των εικονοστοιχείων για ανάγνωση/εγγραφή σε δεδομένη μορφή εικονοστοιχείου |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | Αντιστοίχηση εικονοστοιχείων που προσδιορίζονται από ορθογώνιο για ανάγνωση/εγγραφή σε δεδομένη μορφή εικονοστοιχείου |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | Αποθήκευση δεδομένων υφής σε αρχείο εικόνας |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | Αποθήκευση δεδομένων υφής σε καθορισμένη μορφή εικόνας |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | Αποθήκευση δεδομένων υφής σε αρχείο εικόνας |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | Μετασχηματισμός διάταξης εικονοστοιχείου σε νέα μορφή εικονοστοιχείου. |

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


