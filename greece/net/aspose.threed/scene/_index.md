---
title: "Κλάση Scene"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Scene. Μια σκηνή είναι ένα αντικείμενο ανώτερου επιπέδου που περιέχει τους κόμβους, γεωμετρίες, υλικά, υφές, animation, poses, υποσκηνές κ.λπ. Η σκηνή μπορεί να έχει υποσκηνές και λειτουργεί ως υποστήριξη πολλαπλών εγγράφων σε αρχεία όπως collada/blender/fbx. Η ιεραρχία κόμβων μπορεί να προσπελαστεί μέσω RootNode. Η RootNodeLibrary χρησιμοποιείται για να διατηρεί μια αναφορά σε μη συνδεδεμένα αντικείμενα κατά τη σειριοποίηση, όπως μετα-δεδομένα ή προσαρμοσμένα αντικείμενα, ώστε να μπορεί να χρησιμοποιηθεί ως βιβλιοθήκη."
type: docs
weight: 2500
url: /el/net/aspose.threed/scene/
---
## Scene class

Μια σκηνή είναι ένα αντικείμενο ανώτερου επιπέδου που περιέχει τους κόμβους, γεωμετρίες, υλικά, υφές, animation, poses, υπο-σκηνές κ.λπ. Η σκηνή μπορεί να έχει υπο-σκηνές, λειτουργεί ως υποστήριξη πολλαπλών εγγράφων σε αρχεία όπως collada/blender/fbx. Η ιεραρχία κόμβων μπορεί να προσπελαστεί μέσω [`RootNode`](./rootnode/)[`Library`](./library/). Η Library χρησιμοποιείται για να διατηρεί μια αναφορά σε μη συνδεδεμένα αντικείμενα κατά τη σειριοποίηση (όπως μετα-δεδομένα ή προσαρμοσμένα αντικείμενα) ώστε να μπορεί να χρησιμοποιηθεί ως βιβλιοθήκη.

```csharp
public class Scene : SceneObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Scene](scene/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Scene`. |
| [Scene](scene/#constructor_1)(Entity) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `Scene` με μια οντότητα συνδεδεμένη σε έναν νέο κόμβο. |
| [Scene](scene/#constructor_2)(Scene, string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Scene` ως υπο-σκηνή. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | Λαμβάνει όλα τα [`AnimationClip`](../../aspose.threed.animation/animationclip/) που ορίζονται στη σκηνή. |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | Λαμβάνει ή ορίζει τις πληροφορίες του κορυφαίου στοιχείου |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | Λαμβάνει ή ορίζει το ενεργό [`AnimationClip`](../../aspose.threed.animation/animationclip/) |
| [Library](../../aspose.threed/scene/library/) { get; } | Τα αντικείμενα που δεν χρησιμοποιούνται άμεσα στην ιεραρχία της σκηνής μπορούν να οριστούν στη Βιβλιοθήκη. Αυτό είναι χρήσιμο όταν χρησιμοποιείτε υπο-σκηνές και τοποθετείτε επαναχρησιμοποιήσιμα στοιχεία κάτω από τις υπο-σκηνές. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Poses](../../aspose.threed/scene/poses/) { get; } | Λαμβάνει όλα τα [`Pose`](../pose/) που χρησιμοποιούνται σε αυτή τη σκηνή. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | Λαμβάνει τον ριζικό κόμβο της σκηνής. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | Λαμβάνει όλες τις υπο-σκηνές |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [Clear](../../aspose.threed/scene/clear/)() | Καθαρίζει το περιεχόμενο της σκηνής και επαναφέρει τις προεπιλεγμένες ρυθμίσεις. |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | Μια συντομευμένη συνάρτηση για τη δημιουργία και καταχώριση του [`AnimationClip`](../../aspose.threed.animation/animationclip/). Το πρώτο [`AnimationClip`](../../aspose.threed.animation/animationclip/) θα ανατεθεί στο [`CurrentAnimationClip`](./currentanimationclip/) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | Λαμβάνει ένα ονομαστικό [`AnimationClip`](../../aspose.threed.animation/animationclip/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. Το προεπιλεγμένο μέγεθος εξόδου είναι 1024x768 και η μορφή εξόδου είναι png |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας. |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας. |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | Αποθηκεύει τη σκηνή στο καθορισμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | Λαμβάνει την τρέχουσα έκδοση κυκλοφορίας |

### Δείτε επίσης

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


