---
title: "Κλάση AnimationNode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Animation.AnimationNode. Το Aspose.3Ds υποστηρίζει ιεραρχία animation, κάθε animation μπορεί να αποτελείται από πολλαπλά animations και ορισμό keyframe animation. Το AnimationNode ορίζει τον μετασχηματισμό μιας τιμής ιδιότητας στο χρόνο, για παράδειγμα το animation node μπορεί να χρησιμοποιηθεί για τον έλεγχο του μετασχηματισμού ενός node ή άλλων αριθμητικών ιδιοτήτων αντικειμένων A3DObject."
type: docs
weight: 40
url: /el/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Το Aspose.3D υποστηρίζει ιεραρχία animation, κάθε animation μπορεί να αποτελείται από πολλαπλά animations και τον ορισμό key-frame του animation. `AnimationNode` ορίζει τον μετασχηματισμό μιας τιμής ιδιότητας στο χρόνο, για παράδειγμα, το animation node μπορεί να χρησιμοποιηθεί για τον έλεγχο του μετασχηματισμού ενός node ή άλλων αριθμητικών ιδιοτήτων του αντικειμένου [`A3DObject`](../../aspose.threed/a3dobject/).

```csharp
public class AnimationNode : A3DObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `AnimationNode`. |
| [AnimationNode](animationnode/#constructor_1)(string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `AnimationNode`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | Λαμβάνει τα τρέχοντα bind points της ιδιότητας. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | Λαμβάνει τους υπο-κόμβους animation κάτω από τα τρέχοντα animations. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | Δημιουργεί ένα BindPoint βάσει του τύπου δεδομένων της ιδιότητας. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | Βρίσκει το bind point με βάση τον στόχο και το όνομα. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | Λαμβάνει το animation bind point στην καθορισμένη ιδιότητα. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | Λαμβάνει τη σειρά καρέ-κλειδιού στην καθορισμένη ιδιότητα. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | Λαμβάνει τη σειρά καρέ-κλειδιού στην καθορισμένη ιδιότητα και στο κανάλι. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


