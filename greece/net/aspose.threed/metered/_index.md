---
title: "Κλάση Metered"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Metered κλάση. Παρέχει μεθόδους για τον ορισμό του κλειδιού metered"
type: docs
weight: 1620
url: /el/net/aspose.threed/metered/
---
## Metered class

Παρέχει μεθόδους για τον ορισμό κλειδιού μέτρησης.

```csharp
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered/)() | Αρχικοποιεί ένα νέο παράδειγμα αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey/)(string, string) | Ορίζει το δημόσιο και ιδιωτικό κλειδί metered. Εάν αγοράσετε άδεια metered, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί, κανονικά, αυτό είναι αρκετό. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση δεδομένων κατανάλωσης και υπερβαίνει τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτήν την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit/)() | Λαμβάνει πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity/)() | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το μετρημένο δημόσιο και ιδιωτικό κλειδί

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

το αρχείο jar του στοιχείου:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Δείτε επίσης

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


