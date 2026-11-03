---
title: "Κλάση PhongMaterial"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Shading.PhongMaterial class. Υλικό για το μοντέλο σκίασης blinnphong"
type: docs
weight: 2570
url: /el/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

Υλικό για το μοντέλο σκίασης Blinn-Phong.

```csharp
public class PhongMaterial : LambertMaterial
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PhongMaterial](phongmaterial/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `PhongMaterial`. |
| [PhongMaterial](phongmaterial/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PhongMaterial`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Λαμβάνει ή ορίζει το ambient color. |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Λαμβάνει ή ορίζει το diffuse color. |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Λαμβάνει ή ορίζει το emissive color. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα ανάκλασης. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor/) { get; set; } | Λαμβάνει ή ορίζει την εξασθένιση του χρώματος ανάκλασης. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess/) { get; set; } | Λαμβάνει ή ορίζει τη λάμψη, αυτό ελέγχει το μέγεθος της κατοπτρικής ανάγλυφης. Ο τύπος του κατοπτρικού: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor/) { get; set; } | Λαμβάνει ή ορίζει το κατοπτρικό χρώμα. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor/) { get; set; } | Λαμβάνει ή ορίζει τον κατοπτρικό παράγοντα. Ο τύπος του κατοπτρικού: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | Λαμβάνει ή ορίζει τον παράγοντα διαφάνειας. Ο παράγοντας πρέπει να κυμαίνεται μεταξύ 0 (0%, πλήρως αδιαφανές) και 1 (100%, πλήρως διαφανές). Οποιαδήποτε μη έγκυρη τιμή παράγοντα θα περιοριστεί. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | Λαμβάνει ή ορίζει το διαφανές χρώμα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Λαμβάνει τον enumerator για την απαρίθμηση των εσωτερικών θέσεων texture. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Λαμβάνει τη texture από την καθορισμένη θέση, μπορεί να είναι το όνομα ιδιότητας του material ή το όνομα παραμέτρου του shader. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Ορίζει τη texture στην καθορισμένη θέση. |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Μετατρέπει το αντικείμενο σε συμβολοσειρά. |

### Δείτε επίσης

* class [LambertMaterial](../lambertmaterial/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


