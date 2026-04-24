---
title: Watermark
second_title: Aspose.3D for Java API Reference
description: Εργαλείο για κωδικοποίηση/αποκωδικοποίηση τυφλού υδατογραφήματος σε/από ένα πλέγμα.
type: docs
weight: 230
url: /el/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Εργαλείο για κωδικοποίηση/αποκωδικοποίηση τυφλού υδατογραφήματος σε/από ένα πλέγμα. **Remarks:** Και τα [Watermark](../../com.aspose.threed/watermark) και τα [Watermark](../../com.aspose.threed/watermark) θα εκτελέσουν έλεγχο άδειας. Η χρήση δοκιμής θα προκαλέσει εξαίρεση, μπορείτε να χρησιμοποιήσετε [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) για να καταστείλετε την εξαίρεση, αλλά δεν θα αφαιρέσει τον περιορισμό εδώ. Απαιτείται έγκυρη άδεια για τη χρήση αυτών των λειτουργιών χωρίς περιορισμούς. **Example:** Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα τυφλό υδατογράφημα σε ένα πλέγμα και να το αποκωδικοποιήσετε.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Κωδικοποίηση κειμένου στο τυφλό υδατογράφημα του πλέγματος. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Κωδικοποίηση κειμένου στο τυφλό υδατογράφημα του πλέγματος. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Κωδικοποίηση κειμένου στο τυφλό υδατογράφημα του πλέγματος. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeWatermark(Mesh input) {#decodeWatermark-com.aspose.threed.Mesh-}
```
public static String decodeWatermark(Mesh input)
```


Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Το πλέγμα για εξαγωγή υδατογραφήματος |

**Returns:**
java.lang.String - Τυφλό υδατογράφημα ή null εάν δεν αποκωδικοποιηθεί κανένα υδατογράφημα.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Το πλέγμα για εξαγωγή υδατογραφήματος |
| password | java.lang.String | Ο κωδικός πρόσβασης για αποκρυπτογράφηση του υδατογραφήματος |

**Returns:**
java.lang.String - Τυφλό υδατογράφημα ή null εάν δεν αποκωδικοποιηθεί κανένα υδατογράφημα.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Κωδικοποίηση κειμένου στο τυφλό υδατογράφημα του πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| κείμενο | java.lang.String | Κείμενο για κωδικοποίηση στο πλέγμα |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password)
```


Κωδικοποίηση κειμένου στο τυφλό υδατογράφημα του πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| κείμενο | java.lang.String | Κείμενο για κωδικοποίηση στο πλέγμα |
| password | java.lang.String | Κωδικός πρόσβασης για προστασία του υδατογραφήματος, είναι προαιρετικός |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password, boolean permanent) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password, boolean permanent)
```


Κωδικοποίηση κειμένου στο τυφλό υδατογράφημα του πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Πλέγμα για κωδικοποίηση τυφλού υδατογραφήματος |
| κείμενο | java.lang.String | Κείμενο για κωδικοποίηση στο πλέγμα |
| password | java.lang.String | Κωδικός πρόσβασης για προστασία του υδατογραφήματος, είναι προαιρετικός |
| μόνιμο | boolean | Το μόνιμο υδατογράφημα δεν θα αντικατασταθεί ή αφαιρεθεί. |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

