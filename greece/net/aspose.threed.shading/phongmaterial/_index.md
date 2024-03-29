---
title: PhongMaterial
second_title: Aspose.3D για Αναφορά API .NET
description: Υλικό για το μοντέλο σκίασης blinnphong.
type: docs
weight: 2320
url: /el/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

Υλικό για το μοντέλο σκίασης blinn-phong.

```csharp
public class PhongMaterial : LambertMaterial
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PhongMaterial](phongmaterial/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`PhongMaterial` τάξη. |
| [PhongMaterial](phongmaterial/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία του`PhongMaterial` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα περιβάλλοντος |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Λαμβάνει ή ορίζει το διάχυτο χρώμα |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Λαμβάνει ή ορίζει το εκπεμπόμενο χρώμα |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Παίρνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα ανάκλασης. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor/) { get; set; } | Λαμβάνει ή ορίζει την εξασθένηση του χρώματος ανάκλασης. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess/) { get; set; } | Παίρνει ή ρυθμίζει τη γυαλάδα, ελέγχει το μέγεθος του κατοπτρικού φωτισμού. Ο τύπος του specular: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor/) { get; set; } | Παίρνει ή ορίζει το κατοπτρικό χρώμα. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor/) { get; set; } | Λαμβάνει ή ορίζει τον κατοπτρικό παράγοντα. Ο τύπος του specular: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | Λαμβάνει ή ορίζει τον παράγοντα διαφάνειας. Ο συντελεστής πρέπει να κυμαίνεται μεταξύ 0(0%, πλήρως αδιαφανής) και 1(100%, πλήρως διαφανής) Οποιαδήποτε μη έγκυρη τιμή συντελεστή θα συσφίγγεται. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | Λαμβάνει ή ορίζει το διαφανές χρώμα. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται από το όνομά της) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Βάζει τον απαριθμητή να απαριθμήσει εσωτερικές υποδοχές υφής. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Λαμβάνει την υφή από την καθορισμένη υποδοχή, μπορεί να είναι το όνομα ιδιότητας του υλικού ή η παράμετρος shader name |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Καταργεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Καταργήστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Ορίζει την υφή σε καθορισμένο slot |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Μορφοποιεί αντικείμενο σε string |

### Δείτε επίσης

* class [LambertMaterial](../lambertmaterial/)
* χώρος ονομάτων [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* συνέλευση [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
