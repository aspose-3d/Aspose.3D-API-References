---
title: PdfRenderMode
second_title: Aspose.3D for Java API Reference
description: Η λειτουργία απόδοσης καθορίζει το στυλ με το οποίο αποδίδεται το 3D έργο τέχνης.
type: docs
weight: 289
url: /el/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

Η λειτουργία απόδοσης καθορίζει το στυλ με το οποίο αποδίδεται το 3D έργο τέχνης.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Εμφανίζει τις άκρες του πλαισίου περιβάλλοντος κάθε κόμβου, ευθυγραμμισμένες με τους άξονες του τοπικού χώρου συντεταγμένων για εκείνο τον κόμβο. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Εμφανίζει τις άκρες με ένα ενιαίο χρώμα, αν και αφαιρεί τις άκρες που είναι αντίστροφες και τις κρυμμένες άκρες. |
| [ILLUSTRATION](#ILLUSTRATION) | Εμφανίζει τις άκρες σιλουέτας με τις επιφάνειες, αφαιρεί τις κρυμμένες γραμμές. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Εμφανίζει τις άκρες σιλουέτας με φωτισμένες και υφασμένες επιφάνειες και έναν πρόσθετο εκπεμπτικό όρο για την αφαίρεση των κακώς φωτισμένων περιοχών του έργου. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Εμφανίζει μόνο κορυφές, αν και χρησιμοποιεί το χρώμα τους και εφαρμόζει φωτισμό. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Εμφανίζει μόνο άκρες, αν και παρεμβάλλει το χρώμα τους μεταξύ των δύο κορυφών τους και εφαρμόζει φωτισμό. |
| [SOLID](#SOLID) | Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Εμφανίζει τις άκρες σιλουέτας με φωτισμένες και υφασμένες επιφάνειες, αφαιρεί τις κρυμμένες γραμμές. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα (τρίγωνα) με άκρες ενιαίου χρώματος πάνω τους. |
| [TRANSPARENT](#TRANSPARENT) | Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα (τρίγωνα) με πρόσθετο επίπεδο διαφάνειας. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Εμφανίζει τις όψεις των πλαισίων περιβάλλοντος κάθε κόμβου, ευθυγραμμισμένες με τους άξονες του τοπικού χώρου συντεταγμένων για εκείνο τον κόμβο, με πρόσθετο επίπεδο διαφάνειας. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Εμφανίζει τις άκρες και τις όψεις των πλαισίων περιβάλλοντος κάθε κόμβου, ευθυγραμμισμένες με τους άξονες του τοπικού χώρου συντεταγμένων για εκείνο τον κόμβο, με πρόσθετο επίπεδο διαφάνειας. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα (τρίγωνα) με πρόσθετο επίπεδο διαφάνειας, με άκρες αδιαπραγμάτευτου ενιαίου χρώματος πάνω τους. |
| [VERTICES](#VERTICES) | Εμφανίζει μόνο κορυφές με ένα ενιαίο χρώμα. |
| [WIREFRAME](#WIREFRAME) | Εμφανίζει μόνο άκρες με ένα ενιαίο χρώμα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Εμφανίζει τις άκρες του πλαισίου περιβάλλοντος κάθε κόμβου, ευθυγραμμισμένες με τους άξονες του τοπικού χώρου συντεταγμένων για εκείνο τον κόμβο.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Εμφανίζει τις άκρες με ένα ενιαίο χρώμα, αν και αφαιρεί τις άκρες που είναι αντίστροφες και τις κρυμμένες άκρες.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Εμφανίζει τις άκρες σιλουέτας με τις επιφάνειες, αφαιρεί τις κρυμμένες γραμμές.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Εμφανίζει τις άκρες σιλουέτας με φωτισμένες και υφασμένες επιφάνειες και έναν πρόσθετο εκπεμπτικό όρο για την αφαίρεση των κακώς φωτισμένων περιοχών του έργου.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Εμφανίζει μόνο κορυφές, αν και χρησιμοποιεί το χρώμα τους και εφαρμόζει φωτισμό.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Εμφανίζει μόνο άκρες, αν και παρεμβάλλει το χρώμα τους μεταξύ των δύο κορυφών τους και εφαρμόζει φωτισμό.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Εμφανίζει τις άκρες σιλουέτας με φωτισμένες και υφασμένες επιφάνειες, αφαιρεί τις κρυμμένες γραμμές.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα (τρίγωνα) με άκρες ενιαίου χρώματος πάνω τους.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα (τρίγωνα) με πρόσθετο επίπεδο διαφάνειας.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Εμφανίζει τις όψεις των πλαισίων περιβάλλοντος κάθε κόμβου, ευθυγραμμισμένες με τους άξονες του τοπικού χώρου συντεταγμένων για εκείνο τον κόμβο, με πρόσθετο επίπεδο διαφάνειας.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Εμφανίζει τις άκρες και τις όψεις των πλαισίων περιβάλλοντος κάθε κόμβου, ευθυγραμμισμένες με τους άξονες του τοπικού χώρου συντεταγμένων για εκείνο τον κόμβο, με πρόσθετο επίπεδο διαφάνειας.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Εμφανίζει υφασμένα και φωτισμένα γεωμετρικά σχήματα (τρίγωνα) με πρόσθετο επίπεδο διαφάνειας, με άκρες αδιαπραγμάτευτου ενιαίου χρώματος πάνω τους.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Εμφανίζει μόνο κορυφές με ένα ενιαίο χρώμα.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Εμφανίζει μόνο άκρες με ένα ενιαίο χρώμα.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

