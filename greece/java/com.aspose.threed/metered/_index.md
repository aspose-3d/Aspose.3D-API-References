---
title: Μετρημένο
second_title: Aspose.3D for Java API Reference
description: Παρέχει μεθόδους για ορισμό κλειδιού με μέτρηση.
type: docs
weight: 103
url: /el/java/com.aspose.threed/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για ορισμό κλειδιού με μέτρηση.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) | Αρχικοποιεί ένα νέο αντικείμενο αυτής της κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Λαμβάνει το πιστωτικό κατανάλωσης |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
```


Αρχικοποιεί ένα νέο αντικείμενο αυτής της κλάσης.

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
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Λαμβάνει το πιστωτικό κατανάλωσης

**Returns:**
double - ποσότητα κατανάλωσης
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Λαμβάνει το μέγεθος αρχείου κατανάλωσης

**Returns:**
double - ποσότητα κατανάλωσης
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




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί. Εάν αγοράσετε άδεια μετρημένης χρήσης, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί, συνήθως αυτό είναι αρκετό. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση των δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτήν την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | java.lang.String | δημόσιο κλειδί |
| privateKey | java.lang.String | ιδιωτικό κλειδί |

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

