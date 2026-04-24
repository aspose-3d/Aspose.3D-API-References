---
title: Σκηνή
second_title: Aspose.3D for Java API Reference
description: 
type: docs
weight: 161
url: /el/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Scene](../../com.aspose.threed/scene) με μια οντότητα συνδεδεμένη σε έναν νέο κόμβο. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Scene](../../com.aspose.threed/scene) ως υπο-σκηνή. |
| [Scene()](#Scene--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Scene](../../com.aspose.threed/scene). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [VERSION](#VERSION) | Λαμβάνει την τρέχουσα έκδοση κυκλοφορίας |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clear()](#clear--) | Καθαρίζει το περιεχόμενο της σκηνής και επαναφέρει τις προεπιλεγμένες ρυθμίσεις. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Μια συντομευμένη λειτουργία για τη δημιουργία και καταχώριση του [AnimationClip](../../com.aspose.threed/animationclip) Το πρώτο [AnimationClip](../../com.aspose.threed/animationclip) θα εκχωρηθεί στο [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Λαμβάνει ένα [AnimationClip](../../com.aspose.threed/animationclip) με όνομα |
| [getAnimationClips()](#getAnimationClips--) | Λαμβάνει όλα τα [AnimationClip](../../com.aspose.threed/animationclip) που ορίζονται στη σκηνή. |
| [getAssetInfo()](#getAssetInfo--) | Λαμβάνει τις πληροφορίες του ανώτερου επιπέδου περιουσιακού στοιχείου |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Λαμβάνει το ενεργό [AnimationClip](../../com.aspose.threed/animationclip) |
| [getLibrary()](#getLibrary--) | Τα αντικείμενα που δεν χρησιμοποιούνται άμεσα στην ιεραρχία της σκηνής μπορούν να οριστούν στη Βιβλιοθήκη. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getPoses()](#getPoses--) | Λαμβάνει όλες τις [Pose](../../com.aspose.threed/pose) που χρησιμοποιούνται σε αυτή τη σκηνή. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getRootNode()](#getRootNode--) | Λαμβάνει τον ριζικό κόμβο της σκηνής. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getSubScenes()](#getSubScenes--) | Λαμβάνει όλες τις υπο-σκηνές |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O. |
| [open(String fileName)](#open-java.lang.String-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(String fileName)](#save-java.lang.String-) | Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Ορίζει τις πληροφορίες του περιουσιακού στοιχείου ανώτερου επιπέδου. |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Ορίζει το ενεργό [AnimationClip](../../com.aspose.threed/animationclip) |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Scene](../../com.aspose.threed/scene) με μια οντότητα συνδεδεμένη σε έναν νέο κόμβο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | Η αρχική οντότητα που συνδέεται με τη σκηνή **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα [getScene](../../com.aspose.threed/scene\#getScene) απευθείας από ένα [Entity](../../com.aspose.threed/entity): |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Scene](../../com.aspose.threed/scene) ως υπο-σκηνή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | Η γονική σκηνή. |
| name | java.lang.String | Το όνομα της σκηνής. |

### Scene() {#Scene--}
```
public Scene()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Λαμβάνει την τρέχουσα έκδοση κυκλοφορίας

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει το περιεχόμενο της σκηνής και επαναφέρει τις προεπιλεγμένες ρυθμίσεις.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Μια συντομευμένη λειτουργία για τη δημιουργία και καταχώριση του [AnimationClip](../../com.aspose.threed/animationclip) Το πρώτο [AnimationClip](../../com.aspose.threed/animationclip) θα εκχωρηθεί στο [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα του Animation clip |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε με CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Προσδιορίζεται με το όνομά της)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | java.lang.String | Όνομα ιδιότητας. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή με πηγή διακριτικού ακύρωσης |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή με πηγή διακριτικού ακύρωσης |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή με επιλογές φόρτωσης |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε μια σκηνή από μια ροή με επιλογές φόρτωσης |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


Λαμβάνει ένα [AnimationClip](../../com.aspose.threed/animationclip) με όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα του [AnimationClip](../../com.aspose.threed/animationclip) για αναζήτηση |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Λαμβάνει όλα τα [AnimationClip](../../com.aspose.threed/animationclip) που ορίζονται στη σκηνή.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - όλα τα [AnimationClip](../../com.aspose.threed/animationclip) που ορίζονται στη σκηνή.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Λαμβάνει τις πληροφορίες του ανώτερου επιπέδου περιουσιακού στοιχείου

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


Λαμβάνει το ενεργό [AnimationClip](../../com.aspose.threed/animationclip)

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Τα αντικείμενα που δεν χρησιμοποιούνται άμεσα στην ιεραρχία της σκηνής μπορούν να οριστούν στη Βιβλιοθήκη. Αυτό είναι χρήσιμο όταν χρησιμοποιείτε υπο-σκηνές και τοποθετείτε επαναχρησιμοποιήσιμα στοιχεία κάτω από υπο-σκηνές.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Τα αντικείμενα που δεν χρησιμοποιούνται άμεσα στην ιεραρχία της σκηνής μπορούν να οριστούν στη Βιβλιοθήκη. Αυτό είναι χρήσιμο όταν χρησιμοποιείτε υπο-σκηνές και τοποθετείτε επαναχρησιμοποιήσιμα στοιχεία κάτω από υπο-σκηνές.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Λαμβάνει όλες τις [Pose](../../com.aspose.threed/pose) που χρησιμοποιούνται σε αυτή τη σκηνή.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - όλα τα [Pose](../../com.aspose.threed/pose) που χρησιμοποιούνται σε αυτή τη σκηνή.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Λαμβάνει τη συλλογή όλων των ιδιοτήτων.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Λάβετε την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |

**Returns:**
java.lang.Object - Η τιμή της ευρεθείσας ιδιότητας
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Λαμβάνει τον ριζικό κόμβο της σκηνής.

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Λαμβάνει όλες τις υπο-σκηνές

**Returns:**
java.util.List<com.aspose.threed.Scene> - όλες οι υπο-σκηνές
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ροή |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ροή με διακριτικό ακύρωσης |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφή αρχείου. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ροή |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ροή |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Περισσότερη λεπτομερής διαμόρφωση για το άνοιγμα της ροής. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ροή με επιπλέον επιλογές φόρτωσης |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο ρεύμα χρησιμοποιώντας την καθορισμένη διαμόρφωση I/O.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε μια σκηνή από ροή με επιπλέον επιλογές φόρτωσης |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφότυπο αρχείου. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Ανοίγει τη σκηνή από το δοσμένο μονοπάτι χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Πιο λεπτομερής διαμόρφωση για το άνοιγμα της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία φόρτωσης |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Αφαιρεί μια δυναμική ιδιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Στόχος του αποδοθέντος αποτελέσματος |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Στόχος του αποδοθέντος αποτελέσματος |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Η επιλογή για προσαρμογή ορισμένων εσωτερικών ρυθμίσεων. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Αποδώστε τη σκηνή σε εξωτερικό αρχείο από την δεδομένη προοπτική κάμερας. Το προεπιλεγμένο μέγεθος εξόδου είναι 1024x768 και η μορφή εξόδου είναι png

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| fileName | java.lang.String | Το όνομα αρχείου του αρχείου εξόδου |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| fileName | java.lang.String | Το όνομα αρχείου του αρχείου εξόδου |
| size | [Vector2](../../com.aspose.threed/vector2) | Το μέγεθος της τελικής αποδοθείσας εικόνας |
| format | java.lang.String | Η μορφή εικόνας του αρχείου εξόδου |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Από ποια προοπτική κάμερας να αποδοθεί η σκηνή |
| fileName | java.lang.String | Το όνομα αρχείου του αρχείου εξόδου |
| size | [Vector2](../../com.aspose.threed/vector2) | Το μέγεθος της τελικής αποδοθείσας εικόνας |
| format | java.lang.String | Η μορφή εικόνας του αρχείου εξόδου |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Η επιλογή για προσαρμογή ορισμένων εσωτερικών ρυθμίσεων. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφή. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφή. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Περισσότερη λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Περισσότερη λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφή. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφή. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία αποθήκευσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Περισσότερη λεπτομερής διαμόρφωση για την αποθήκευση της ροής. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


Αποθηκεύει τη σκηνή σε ρεύμα χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή εισόδου, ο χρήστης είναι υπεύθυνος για το κλείσιμο της ροής. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Περισσότερη λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία αποθήκευσης **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφή. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Μορφή. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Περισσότερη λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Αποθηκεύει τη σκηνή στην καθορισμένη διαδρομή χρησιμοποιώντας το καθορισμένο μορφότυπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Περισσότερη λεπτομερής διαμόρφωση για την αποθήκευση της ροής. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Διακριτικό ακύρωσης για την εργασία αποθήκευσης |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Ορίζει τις πληροφορίες του περιουσιακού στοιχείου ανώτερου επιπέδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Νέα τιμή **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να διαβάσετε τις πληροφορίες της εφαρμογής από ένα αρχείο FBX: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


Ορίζει το ενεργό [AnimationClip](../../com.aspose.threed/animationclip)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ορίζει την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |
| τιμή | java.lang.Object | Η τιμή της ιδιότητας |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

