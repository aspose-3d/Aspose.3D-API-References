---
title: "Κλάση Transform"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Transform class. Ένα transform περιέχει πληροφορίες που επιτρέπουν πρόσβαση σε αντικείμενα translate/scale/rotation ή transform matrix με ελάχιστο κόστος. Αυτό χρησιμοποιείται από το local transform."
type: docs
weight: 2650
url: /el/net/aspose.threed/transform/
---
## Transform class

Ένας μετασχηματισμός περιέχει πληροφορίες που επιτρέπουν την πρόσβαση στη μετάφραση/κλιμάκωση/περιστροφή του αντικειμένου ή στον πίνακα μετασχηματισμού με ελάχιστο κόστος. Αυτό χρησιμοποιείται από τον τοπικό μετασχηματισμό.

```csharp
public class Transform : A3DObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | Λαμβάνει ή ορίζει την περιστροφή που αναπαρίσταται σε γωνίες Euler, μετρημένες σε μοίρες |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | Λαμβάνει ή ορίζει την γεωμετρική περιστροφή Euler (μετρημένη σε μοίρες). Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν. |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | Λαμβάνει ή ορίζει τη γεωμετρική κλιμάκωση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν. |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | Λαμβάνει ή ορίζει τη γεωμετρική μετάφραση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | Λαμβάνει ή ορίζει την μετα-περιστροφή που αναπαρίσταται σε μοίρες |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | Λαμβάνει ή ορίζει την προ-περιστροφή που αναπαρίσταται σε μοίρες |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | Λαμβάνει ή ορίζει την περιστροφή που αναπαρίσταται σε quaternion. |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | Λαμβάνει ή ορίζει τη μετατόπιση περιστροφής |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | Λαμβάνει ή ορίζει τον άξονα περιστροφής |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | Λαμβάνει ή ορίζει την κλιμάκωση |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | Λαμβάνει ή ορίζει τη μετατόπιση κλιμάκωσης |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | Λαμβάνει ή ορίζει τον άξονα κλιμάκωσης |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | Λαμβάνει ή ορίζει τη μετάφραση |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | Ορίζει τις γωνίες Euler σε μοίρες του τρέχοντος transform. |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | Ορίζει τη γεωμετρική περιστροφή Euler (μετρημένη σε μοίρες). Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν. |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | Ορίζει τη γεωμετρική κλιμάκωση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν. |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | Ορίζει τη γεωμετρική μετάφραση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν. |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | Ορίζει την μετα-περιστροφή που αναπαρίσταται σε μοίρες |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | Ορίζει την προ-περιστροφή που αναπαρίσταται σε μοίρες |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | Ορίζει την περιστροφή (ως συνιστώσες quaternion) του τρέχοντος transform. |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | Ορίζει την κλίμακα του τρέχοντος μετασχηματισμού. |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | Ορίζει τη μετάφραση του τρέχοντος μετασχηματισμού. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε τον μετασχηματισμό του κόμβου:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Τοποθετήστε το κουτί στο (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Δείτε επίσης

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


