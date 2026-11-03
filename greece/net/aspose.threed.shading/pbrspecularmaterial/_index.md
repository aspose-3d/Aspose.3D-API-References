---
title: "Κλάση PbrSpecularMaterial"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Shading.PbrSpecularMaterial class. Υλικό για φυσικά-βασισμένη απόδοση με βάση το διαχυτικό χρώμα, το αντανακλαστικό και τη γυαλάδα."
type: docs
weight: 2560
url: /el/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Υλικό για φυσικά βασισμένη απόδοση βασισμένο σε διαχυτικό χρώμα, κατοπτρικό και γυαλάδα

```csharp
public class PbrSpecularMaterial : Material
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | Κατασκευαστής του `PbrSpecularMaterial` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | Λαμβάνει ή ορίζει το διαχυτικό χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή για διασπορά |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | Λαμβάνει ή ορίζει το εκπεμπόμενο χρώμα, η προεπιλεγμένη τιμή είναι (0, 0, 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή για εκπεμπόμενο |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | Λαμβάνει ή ορίζει τη γυαλάδα (ομαλότητα) του υλικού, το 1 σημαίνει απόλυτα ομαλό και το 0 σημαίνει απόλυτα τραχύ, η προεπιλεγμένη τιμή είναι 1, το εύρος είναι [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή της κανονικής χαρτογράφησης |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | Λαμβάνει ή ορίζει το κατοπτρικό χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1). |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | Λαμβάνει ή ορίζει την υφή για το κατοπτρικό χρώμα, το κανάλι RGB αποθηκεύει το κατοπτρικό χρώμα και το κανάλι A αποθηκεύει τη γυαλάδα. |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | Λαμβάνει ή ορίζει τον παράγοντα διαφάνειας. Ο παράγοντας πρέπει να κυμαίνεται μεταξύ 0 (0%, πλήρως αδιαφανές) και 1 (100%, πλήρως διαφανές). Οποιαδήποτε μη έγκυρη τιμή παράγοντα θα περιοριστεί. |

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

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | Ο χάρτης υφής για την γυαλάδα του κατοπτρικού |

### Δείτε επίσης

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


