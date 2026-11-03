---
title: "Κλάση Material"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Shading.Material class. Το υλικό ορίζει τις παραμέτρους που απαιτούνται για την οπτική εμφάνιση της γεωμετρίας. Το Aspose.3D παρέχει μοντέλο σκίασης για LambertMaterial, PhongMaterial και ShaderMaterial"
type: docs
weight: 2540
url: /el/net/aspose.threed.shading/material/
---
## Material class

Το υλικό ορίζει τις παραμέτρους που απαιτούνται για την οπτική εμφάνιση της γεωμετρίας. Το Aspose.3D παρέχει μοντέλο σκίασης για [`LambertMaterial`](../lambertmaterial/), [`PhongMaterial`](../phongmaterial/) και [`ShaderMaterial`](../shadermaterial/)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

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
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | Χρησιμοποιείται στο [`SetTexture`](./settexture/) για την ανάθεση μιας ατμοσφαιρικής χαρτογράφησης υφής. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | Χρησιμοποιείται στο [`SetTexture`](./settexture/) για την ανάθεση μιας διάχυτης απεικόνισης υφής. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | Χρησιμοποιείται στο [`SetTexture`](./settexture/) για την ανάθεση μιας εκπεμπόμενης απεικόνισης υφής. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | Χρησιμοποιείται στο [`SetTexture`](./settexture/) για την ανάθεση μιας κανονικής απεικόνισης υφής. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | Χρησιμοποιείται στο [`SetTexture`](./settexture/) για την ανάθεση μιας specular απεικόνισης υφής. |

## Παραδείγματα

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


