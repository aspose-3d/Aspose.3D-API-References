---
title: "Κλάση ShaderMaterial"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Shading.ShaderMaterial class. Ένα shader material επιτρέπει την περιγραφή του υλικού από εξωτερική μηχανή απόδοσης ή γλώσσα σκίασης. ShaderMaterial χρησιμοποιεί ShaderTechnique για την περιγραφή των συγκεκριμένων λεπτομερειών απόδοσης και το πιο κατάλληλο θα χρησιμοποιηθεί ανάλογα με την τελική πλατφόρμα απόδοσης. Για παράδειγμα, η παρουσία σας ShaderMaterial μπορεί να έχει δύο τεχνικές, η μία ορίζεται από HLSL και η άλλη ορίζεται από GLSL. Σε πλατφόρμα nonwindow το GLSL θα πρέπει να χρησιμοποιηθεί αντί για HLSL."
type: docs
weight: 2580
url: /el/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Ένα shader material επιτρέπει την περιγραφή του υλικού από εξωτερική μηχανή απόδοσης ή γλώσσα σκίασης. `ShaderMaterial` χρησιμοποιεί [`ShaderTechnique`](../shadertechnique/) για την περιγραφή των συγκεκριμένων λεπτομερειών απόδοσης, και το πιο κατάλληλο θα χρησιμοποιηθεί ανάλογα με την τελική πλατφόρμα απόδοσης. Για παράδειγμα, η παρουσία σας `ShaderMaterial` μπορεί να έχει δύο τεχνικές, η μία ορίζεται από HLSL και η άλλη ορίζεται από GLSL. Σε πλατφόρμα non-window το GLSL θα πρέπει να χρησιμοποιηθεί αντί για HLSL.

```csharp
public class ShaderMaterial : Material
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `ShaderMaterial`. |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ShaderMaterial`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | Λαμβάνει όλες τις διαθέσιμες τεχνικές που ορίζονται σε αυτό το υλικό. |

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

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


