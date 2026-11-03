---
title: "Κλάση Texture"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Shading.Texture κλάση. Αυτή η κλάση ορίζει την υφή από εξωτερικό αρχείο"
type: docs
weight: 2600
url: /el/net/aspose.threed.shading/texture/
---
## Texture class

Αυτή η κλάση ορίζει την υφή από ένα εξωτερικό αρχείο.

```csharp
public class Texture : TextureBase
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Texture](texture/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Texture`. |
| [Texture](texture/#constructor_1)(string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Texture`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη τιμή άλφα της υφής. Αυτό είναι έγκυρο όταν το [`AlphaSource`](../texturebase/alphasource/) είναι PixelAlpha. Η προεπιλεγμένη τιμή είναι 1.0, το έγκυρο εύρος τιμών είναι μεταξύ 0 και 1 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Λαμβάνει ή ορίζει αν η υφή ορίζει το κανάλι άλφα. Η προεπιλεγμένη τιμή είναι None |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | Λαμβάνει ή ορίζει το δυαδικό περιεχόμενο της υφής. Το ενσωματωμένο περιεχόμενο υφής είναι προαιρετικό, ο χρήστης πρέπει να φορτώσει την υφή από εξωτερικό αρχείο εάν λείπει. |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | Λαμβάνει ή ορίζει αν το mipmap είναι ενεργοποιημένο για αυτήν την υφή |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | Λαμβάνει ή ορίζει το συσχετισμένο αρχείο υφής. |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | Λαμβάνει ή ορίζει το φίλτρο για μεγέθυνση. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | Λαμβάνει ή ορίζει το φίλτρο για ελαχιστοποίηση. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | Λαμβάνει ή ορίζει το φίλτρο για δειγματοληψία επιπέδου mip. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | Λαμβάνει ή ορίζει την περιστροφή της υφής |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | Λαμβάνει ή ορίζει την κλίμακα UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | Λαμβάνει ή ορίζει τη μετάφραση UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | Λαμβάνει ή ορίζει τις λειτουργίες περιτύλιξης της υφής στο U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | Λαμβάνει ή ορίζει τις λειτουργίες περιτύλιξης της υφής στο V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | Λαμβάνει ή ορίζει τις λειτουργίες περιτύλιξης της υφής στο W. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | Ορίζει την περιστροφή UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | Ορίζει την κλίμακα UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | Ορίζει τη μετάφραση UV. |

### Δείτε επίσης

* class [TextureBase](../texturebase/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


