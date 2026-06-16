---
title: "Τεταρτοδικό"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Το Quaternion χρησιμοποιείται συνήθως για την εκτέλεση περιστροφής στην υπολογιστική γραφική.


## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| w | Το στοιχείο w. |
| x | Το στοιχείο x. |
| y | Το στοιχείο y. |
| z | Το στοιχείο z. |
| IDENTITY | Το μοναδιαίο quaternion. |

## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(w, x, y, z) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Quaternion. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| w | Αριθμός | συστατικό w του quaternion |
| x | Αριθμός | συστατικό x του quaternion |
| y | Αριθμός | συστατικό y του quaternion |
| z | Αριθμός | συστατικό z του quaternion |

 **Result:**



---


### getLength{#getLength}

| Όνομα | Περιγραφή |
| --- | --- |
| getLength() | Επιστρέφει το μήκος του quaternion |

 **Result:**



---


### equals{#equals}

| Όνομα | Περιγραφή |
| --- | --- |
| equals(obj) | Ελέγχει αν δύο quaternions είναι ίσα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | Αντικείμενο | Το αντικείμενο για έλεγχο ισότητας. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Όνομα | Περιγραφή |
| --- | --- |
| hashCode() | Επιστρέφει τον κωδικό κατακερματισμού του Quaternion |

 **Result:**
Αριθμός


---


### conjugate{#conjugate}

| Όνομα | Περιγραφή |
| --- | --- |
| conjugate() | Επιστρέφει ένα συζυγές quaternion του τρέχοντος quaternion |

 **Result:**
Τεταρτοδικό


---


### inverse{#inverse}

| Όνομα | Περιγραφή |
| --- | --- |
| inverse() | Επιστρέφει ένα αντίστροφο quaternion του τρέχοντος quaternion |

 **Result:**
Τεταρτοδικό


---


### dot{#dot}

| Όνομα | Περιγραφή |
| --- | --- |
| dot(q) | Προϊόν σημείων |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| q | Τεταρτοδικό | Το quaternion |

 **Result:**
Αριθμός


---


### eulerAngles{#eulerAngles}

| Όνομα | Περιγραφή |
| --- | --- |
| eulerAngles() | Μετατρέπει το quaternion σε περιστροφή που αναπαρίσταται από γωνίες Euler. Όλα τα συστατικά είναι σε ακτίνια |

 **Result:**
Vector3


---


### normalize{#normalize}

| Όνομα | Περιγραφή |
| --- | --- |
| normalize() | Κανονικοποίηση του quaternion |

 **Result:**
Τεταρτοδικό


---


### concat{#concat}

| Όνομα | Περιγραφή |
| --- | --- |
| concat(rhs) | Συνένωση δύο quaternion |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rh | Τεταρτοδικό | null |

 **Result:**
Τεταρτοδικό


---


### fromAngleAxis{#fromAngleAxis}

| Όνομα | Περιγραφή |
| --- | --- |
| fromAngleAxis(a, axis) | Δημιουργεί ένα quaternion γύρω από τον δοσμένο άξονα και περιστρέφει δεξιόστροφα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | Αριθμός | Δεξιόστροφη περιστροφή σε ακτίνια |
| άξονας | Vector3 | Άξονας |

 **Result:**
Τεταρτοδικό


---


### fromRotation{#fromRotation}

| Όνομα | Περιγραφή |
| --- | --- |
| fromRotation(orig, dest) | Δημιουργεί ένα quaternion που περιστρέφεται από την αρχική προς την προορισμένη κατεύθυνση |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| orig | Vector3 | Αρχική κατεύθυνση |
| dest | Vector3 | Κατεύθυνση προορισμού |

 **Result:**
Τεταρτοδικό


---


### fromEulerAngle{#fromEulerAngle}

| Όνομα | Περιγραφή |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Δημιουργεί quaternion από τη δεδομένη γωνία Euler |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pitch | Αριθμός | Pitch σε ακτίνια |
| yaw | Αριθμός | Yaw σε ακτίνια |
| κύλιση | Αριθμός | Κύλιση σε ακτίνια |

 **Result:**
Τεταρτοδικό


---


### fromEulerAngle{#fromEulerAngle}

| Όνομα | Περιγραφή |
| --- | --- |
| fromEulerAngle(eulerAngle) | Δημιουργεί quaternion από τη δεδομένη γωνία Euler |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| eulerAngle | Vector3 | Γωνία Euler σε ακτίνια |

 **Result:**
Τεταρτοδικό


---


### toMatrix{#toMatrix}

| Όνομα | Περιγραφή |
| --- | --- |
| toMatrix() | Μετατρέψτε την περιστροφή που παρουσιάζεται από το quaternion σε πίνακα μετασχηματισμού. |

 **Result:**
Matrix4


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Λαμβάνει την αναπαράσταση του quaternion σε συμβολοσειρά. |

 **Result:**
String


---


### interpolate{#interpolate}

| Όνομα | Περιγραφή |
| --- | --- |
| interpolate(t, from, to) | Γεμίζει αυτό το quaternion με την παρεμβαλλόμενη τιμή μεταξύ των δοθέντων ορισμάτων quaternion για ένα t μεταξύ from και to. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| t | Αριθμός | Ο συντελεστής για παρεμβολή. |
| from | Τεταρτοδικό | Πηγή quaternion. |
| to | Τεταρτοδικό | Στόχος quaternion. |

 **Result:**
Τεταρτοδικό


---



