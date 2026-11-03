---
title: "Κλάση License"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.License. Παρέχει μεθόδους για την αδειοδότηση του στοιχείου"
type: docs
weight: 1610
url: /el/net/aspose.threed/license/
---
## License class

Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.

```csharp
public class License
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [License](license/)() | Αρχικοποιεί ένα νέο παράδειγμα αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | Αδειοδοτεί το στοιχείο. |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | Αδειοδοτεί το στοιχείο. |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το καλούμενο assembly, στον φάκελο του entry assembly και, τέλος, στους ενσωματωμένους πόρους του καλούμενου assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

το αρχείο jar του στοιχείου:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Δείτε επίσης

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


