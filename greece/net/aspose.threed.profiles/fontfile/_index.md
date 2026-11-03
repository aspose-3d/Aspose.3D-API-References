---
title: "Κλάση FontFile"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Profiles.FontFile κλάση. Το αρχείο γραμματοσειράς περιέχει ορισμούς για glyphs, αυτό χρησιμοποιείται για τη δημιουργία προφίλ κειμένου"
type: docs
weight: 1720
url: /el/net/aspose.threed.profiles/fontfile/
---
## FontFile class

Το αρχείο γραμματοσειράς περιέχει ορισμούς για γλύφους, το οποίο χρησιμοποιείται για τη δημιουργία προφίλ κειμένου.

```csharp
public abstract class FontFile : A3DObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | Φορτώστε το FontFile από το όνομα αρχείου |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | Αναλύστε το FontFile από τα bytes |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα 3D πλέγμα από κείμενο χρησιμοποιώντας το καθορισμένο αρχείο γραμματοσειράς.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


