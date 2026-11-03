---
title: "Κλάση BindPoint"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Animation.BindPoint class. Ένα BindPoint συνήθως δημιουργείται σε μια ιδιότητα αντικειμένου· ορισμένοι τύποι ιδιοτήτων περιέχουν πολλαπλά πεδία στοιχείων, όπως ένα πεδίο Vector3. Το BindPoint θα δημιουργήσει κανάλι για κάθε πεδίο στοιχείου και συνδέει το πεδίο με μία ή περισσότερες εμφανίσεις σειράς καρέ-κλειδιού μέσω των καναλιών."
type: docs
weight: 50
url: /el/net/aspose.threed.animation/bindpoint/
---
## BindPoint class

Ένα `BindPoint` συνήθως δημιουργείται σε μια ιδιότητα αντικειμένου· ορισμένοι τύποι ιδιοτήτων περιέχουν πολλαπλά πεδία στοιχείων (όπως ένα πεδίο Vector3), `BindPoint` θα δημιουργήσει κανάλι για κάθε πεδίο στοιχείου και συνδέει το πεδίο με μία ή περισσότερες εμφανίσεις σειράς καρέ-κλειδιού μέσω των καναλιών.

```csharp
public class BindPoint : A3DObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BindPoint`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | Λαμβάνει το συνολικό αριθμό καναλιών ιδιοτήτων που ορίζονται σε αυτήν τη χαρτογράφηση καμπύλης κίνησης. |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | Λαμβάνει την ιδιότητα που σχετίζεται με το CurveMapping |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | Προσθέτει την καθορισμένη ιδιότητα καναλιού. |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | Προσθέτει την καθορισμένη ιδιότητα καναλιού. |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | Συνδέει τη σειρά καρέ-κλειδιού με το καθορισμένο κανάλι |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | Δημιουργεί μια νέα καμπύλη και τη συνδέει με το πρώτο κανάλι της χαρτογράφησης καμπύλης |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | Λαμβάνει το κανάλι με το δοσμένο όνομα |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | Λαμβάνει την πρώτη σειρά καρέ-κλειδιού στο καθορισμένο κανάλι |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | Αδειάζει τα κανάλια ιδιοτήτων αυτής της χαρτογράφησης καμπύλης κίνησης. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | Μετατρέπει το αντικείμενο σε συμβολοσειρά. |

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


