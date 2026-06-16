---
title: "KeyFrame"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Ένα key frame ορίζεται κυρίως από χρόνο και τιμή, για ορισμένους τύπους παρεμβολής, η εφαπτομένη/τάση/προδιάθεση/συνέχεια χρησιμοποιούνται επίσης για τον υπολογισμό της τελικής δειγματοληπτικής τιμής. Οι δειγματοληπτικές τιμές σε θέση χρόνου χωρίς key-frame παρεμβάλλονται από τα key-frames μεταξύ του προηγούμενου και του επόμενου key-frame. Η τιμή πριν/μετά το πρώτο/τελευταίο key-frame υπολογίζεται από την Extrapolation class.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(curve, time) | Δημιουργία νέου key frame στην καθορισμένη καμπύλη |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| curve | KeyframeSequence | Η καμπύλη στην οποία το key frame θα δημιουργηθεί |
| time | Αριθμός | Η χρονική θέση του key frame |

 **Result:**



---


### getTime{#getTime}

| Όνομα | Περιγραφή |
| --- | --- |
| getTime() | Λαμβάνει ή ορίζει τη χρονική θέση του key frame list.data[index], μετρημένη σε δευτερόλεπτα. Ο χρόνος. |

 **Result:**



---


### setTime{#setTime}

| Όνομα | Περιγραφή |
| --- | --- |
| setTime(value) | Λαμβάνει ή ορίζει τη χρονική θέση του key frame list.data[index], μετρημένη σε δευτερόλεπτα. Ο χρόνος. |

 **Result:**



---


### getValue{#getValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getValue() | Λαμβάνει ή ορίζει την τιμή του key-frame. Η τιμή. |

 **Result:**



---


### setValue{#setValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setValue(value) | Λαμβάνει ή ορίζει την τιμή του key-frame. Η τιμή. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Όνομα | Περιγραφή |
| --- | --- |
| getInterpolation() | Λαμβάνει ή ορίζει τον τύπο παρεμβολής του key, το list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η δειγματοληπτική τιμή. Η τιμή της ιδιότητας είναι η ακέραια σταθερά Interpolation. Η παρεμβολή. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Όνομα | Περιγραφή |
| --- | --- |
| setInterpolation(value) | Λαμβάνει ή ορίζει τον τύπο παρεμβολής του key, το list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η δειγματοληπτική τιμή. Η τιμή της ιδιότητας είναι η ακέραια σταθερά Interpolation. Η παρεμβολή. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Όνομα | Περιγραφή |
| --- | --- |
| getTangentWeightMode() | Λαμβάνει ή ορίζει τη λειτουργία βάρους εφαπτομένης του key. Η έξοδος εφαπτομένη ή η επόμενη εσωτερική εφαπτομένη μπορεί να προσαρμοστεί επιλέγοντας το σωστό WeightedMode. Η τιμή της ιδιότητας είναι η ακέραια σταθερά WeightedMode. Η λειτουργία βάρους εφαπτομένης. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Όνομα | Περιγραφή |
| --- | --- |
| setTangentWeightMode(value) | Λαμβάνει ή ορίζει τη λειτουργία βάρους εφαπτομένης του key. Η έξοδος εφαπτομένη ή η επόμενη εσωτερική εφαπτομένη μπορεί να προσαρμοστεί επιλέγοντας το σωστό WeightedMode. Η τιμή της ιδιότητας είναι η ακέραια σταθερά WeightedMode. Η λειτουργία βάρους εφαπτομένης. |

 **Result:**



---


### getStepMode{#getStepMode}

| Όνομα | Περιγραφή |
| --- | --- |
| getStepMode() | Λαμβάνει ή ορίζει τη λειτουργία βήματος του key. Εάν ο τύπος παρεμβολής είναι Interpolation.CONSTANT, το list.data[index] αποφασίζει ποια τιμή του key-frame θα χρησιμοποιηθεί κατά την παρεμβολή. Ένα StepMode.PREVIOUS_VALUE σημαίνει ότι θα χρησιμοποιηθεί η τιμή του αριστερού key-frame. Ένα StepMode.NEXT_VALUE σημαίνει ότι θα χρησιμοποιηθεί η τιμή του επόμενου δεξιού key-frame. Η τιμή της ιδιότητας είναι η ακέραια σταθερά StepMode. Η λειτουργία βήματος. |

 **Result:**



---


### setStepMode{#setStepMode}

| Όνομα | Περιγραφή |
| --- | --- |
| setStepMode(value) | Λαμβάνει ή ορίζει τη λειτουργία βήματος του key. Εάν ο τύπος παρεμβολής είναι Interpolation.CONSTANT, το list.data[index] αποφασίζει ποια τιμή του key-frame θα χρησιμοποιηθεί κατά την παρεμβολή. Ένα StepMode.PREVIOUS_VALUE σημαίνει ότι θα χρησιμοποιηθεί η τιμή του αριστερού key-frame. Ένα StepMode.NEXT_VALUE σημαίνει ότι θα χρησιμοποιηθεί η τιμή του επόμενου δεξιού key-frame. Η τιμή της ιδιότητας είναι η ακέραια σταθερά StepMode. Η λειτουργία βήματος. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| getNextInTangent() | Λαμβάνει ή ορίζει την επόμενη εσωτερική (αριστερή) εφαπτομένη σε αυτό το key frame. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| setNextInTangent(value) | Λαμβάνει ή ορίζει την επόμενη εσωτερική (αριστερή) εφαπτομένη σε αυτό το key frame. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| getOutTangent() | Λαμβάνει ή ορίζει την έξοδο (δεξιά) εφαπτομένη σε αυτό το key frame. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| setOutTangent(value) | Λαμβάνει ή ορίζει την έξοδο (δεξιά) εφαπτομένη σε αυτό το key frame. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getOutWeight() | Λαμβάνει ή ορίζει το έξοδο (δεξιά) βάρος σε αυτό το key frame. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setOutWeight(value) | Λαμβάνει ή ορίζει το έξοδο (δεξιά) βάρος σε αυτό το key frame. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getNextInWeight() | Λαμβάνει ή ορίζει το επόμενο βάρος in(left) σε αυτό το πλαίσιο κλειδιού. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setNextInWeight(value) | Λαμβάνει ή ορίζει το επόμενο βάρος in(left) σε αυτό το πλαίσιο κλειδιού. |

 **Result:**



---


### getTension{#getTension}

| Όνομα | Περιγραφή |
| --- | --- |
| getTension() | Λαμβάνει ή ορίζει την τάση που χρησιμοποιείται στην TCB spline |

 **Result:**



---


### setTension{#setTension}

| Όνομα | Περιγραφή |
| --- | --- |
| setTension(value) | Λαμβάνει ή ορίζει την τάση που χρησιμοποιείται στην TCB spline |

 **Result:**



---


### getContinuity{#getContinuity}

| Όνομα | Περιγραφή |
| --- | --- |
| getContinuity() | Λαμβάνει ή ορίζει τη συνέχεια που χρησιμοποιείται στην TCB spline |

 **Result:**



---


### setContinuity{#setContinuity}

| Όνομα | Περιγραφή |
| --- | --- |
| setContinuity(value) | Λαμβάνει ή ορίζει τη συνέχεια που χρησιμοποιείται στην TCB spline |

 **Result:**



---


### getBias{#getBias}

| Όνομα | Περιγραφή |
| --- | --- |
| getBias() | Λαμβάνει ή ορίζει την προκατάληψη που χρησιμοποιείται στην TCB spline |

 **Result:**



---


### setBias{#setBias}

| Όνομα | Περιγραφή |
| --- | --- |
| setBias(value) | Λαμβάνει ή ορίζει την προκατάληψη που χρησιμοποιείται στην TCB spline |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| getIndependentTangent() | Λαμβάνει ή ορίζει ότι οι out και next in εφαπτόμενες είναι ανεξάρτητες. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| setIndependentTangent(value) | Λαμβάνει ή ορίζει ότι οι out και next in εφαπτόμενες είναι ανεξάρτητες. |

 **Result:**



---


### getFlat{#getFlat}

| Όνομα | Περιγραφή |
| --- | --- |
| getFlat() | Λαμβάνει ή ορίζει αν το πλαίσιο κλειδιού είναι επίπεδο. Το πλαίσιο κλειδιού πρέπει να είναι επίπεδο εάν το επόμενο ή το προηγούμενο πλαίσιο κλειδιού έχει την ίδια τιμή. Ένα επίπεδο πλαίσιο κλειδιού έχει επίπεδες εφαπτόμενες και σταθερή παρεμβολή. |

 **Result:**



---


### setFlat{#setFlat}

| Όνομα | Περιγραφή |
| --- | --- |
| setFlat(value) | Λαμβάνει ή ορίζει αν το πλαίσιο κλειδιού είναι επίπεδο. Το πλαίσιο κλειδιού πρέπει να είναι επίπεδο εάν το επόμενο ή το προηγούμενο πλαίσιο κλειδιού έχει την ίδια τιμή. Ένα επίπεδο πλαίσιο κλειδιού έχει επίπεδες εφαπτόμενες και σταθερή παρεμβολή. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| getTimeIndependentTangent() | Λαμβάνει ή ορίζει ότι η tangent είναι ανεξάρτητη από το χρόνο. |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Όνομα | Περιγραφή |
| --- | --- |
| setTimeIndependentTangent(value) | Λαμβάνει ή ορίζει ότι η tangent είναι ανεξάρτητη από το χρόνο. |

 **Result:**



---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Λαμβάνει την αναπαράσταση συμβολοσειράς του πλαισίου κλειδιού. |

 **Result:**
String


---



