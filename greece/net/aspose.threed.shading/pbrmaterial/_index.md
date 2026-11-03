---
title: "Κλάση PbrMaterial"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Shading.PbrMaterial κλάση. Υλικό για φυσική απόδοση βάσει χρώματος albedo/μεταλλικότητας/τραχύτητας."
type: docs
weight: 2550
url: /el/net/aspose.threed.shading/pbrmaterial/
---
## PbrMaterial class

Υλικό για φυσικά βασισμένη απόδοση βασισμένο σε χρώμα αλμπέτο, μεταλλικό και τραχύτητα

```csharp
public class PbrMaterial : Material
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PbrMaterial](pbrmaterial/#constructor)() | Δημιουργήστε μια προεπιλεγμένη παρουσία υλικού PBR |
| [PbrMaterial](pbrmaterial/#constructor_1)(Vector3) | Δημιουργήστε μια προεπιλεγμένη υλική PBR με καθορισμένη τιμή χρώματος albedo. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Albedo](../../aspose.threed.shading/pbrmaterial/albedo/) { get; set; } | Λαμβάνει ή ορίζει το βασικό χρώμα του υλικού |
| [AlbedoTexture](../../aspose.threed.shading/pbrmaterial/albedotexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή για το albedo |
| [EmissiveColor](../../aspose.threed.shading/pbrmaterial/emissivecolor/) { get; set; } | Λαμβάνει ή ορίζει το emissive color. |
| [EmissiveTexture](../../aspose.threed.shading/pbrmaterial/emissivetexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή για εκπεμπόμενο |
| [MetallicFactor](../../aspose.threed.shading/pbrmaterial/metallicfactor/) { get; set; } | Λαμβάνει ή ορίζει τη μεταλλικότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι μέταλλο και η τιμή 0 σημαίνει ότι το υλικό είναι διηλεκτρικό. |
| [MetallicRoughness](../../aspose.threed.shading/pbrmaterial/metallicroughness/) { get; set; } | Λαμβάνει ή ορίζει την υφή για το μεταλλικό (στο κανάλι R) και την τραχύτητα (στο κανάλι G) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [NormalTexture](../../aspose.threed.shading/pbrmaterial/normaltexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή της κανονικής χαρτογράφησης |
| [OcclusionFactor](../../aspose.threed.shading/pbrmaterial/occlusionfactor/) { get; set; } | Λαμβάνει ή ορίζει τον παράγοντα της περιβάλλουσας απόσβεσης |
| [OcclusionTexture](../../aspose.threed.shading/pbrmaterial/occlusiontexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή για την περιβάλλουσα απόσβεση |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [RoughnessFactor](../../aspose.threed.shading/pbrmaterial/roughnessfactor/) { get; set; } | Λαμβάνει ή ορίζει την τραχύτητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι εντελώς τραχύ και η τιμή 0 σημαίνει ότι το υλικό είναι εντελώς λείο. |
| [SpecularTexture](../../aspose.threed.shading/pbrmaterial/speculartexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή για το χρώμα specular |
| [Transparency](../../aspose.threed.shading/pbrmaterial/transparency/) { get; set; } | Λαμβάνει ή ορίζει τον παράγοντα διαφάνειας. Ο παράγοντας πρέπει να κυμαίνεται μεταξύ 0 (0%, πλήρως αδιαφανές) και 1 (100%, πλήρως διαφανές). Οποιαδήποτε μη έγκυρη τιμή παράγοντα θα περιοριστεί. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromMaterial](../../aspose.threed.shading/pbrmaterial/frommaterial/)(Material) | Επιτρέπει τη μετατροπή άλλου υλικού σε PbrMaterial |
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


