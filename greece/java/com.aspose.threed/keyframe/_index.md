---
title: KeyFrame
second_title: Aspose.3D for Java API Reference
description: Ένα key frame ορίζεται κυρίως από χρόνο και τιμή· για ορισμένους τύπους παρεμβολής, τα tangent/tension/bias/continuity χρησιμοποιούνται επίσης κατά τον υπολογισμό της τελικής δειγματοληπτικής τιμής.
type: docs
weight: 89
url: /el/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Ένα key frame ορίζεται κυρίως από χρόνο και τιμή· για ορισμένους τύπους παρεμβολής, τα tangent/tension/bias/continuity χρησιμοποιούνται επίσης κατά τον υπολογισμό της τελικής δειγματοληπτικής τιμής. Οι δειγματοληπτικές τιμές σε θέση χρόνου που δεν είναι key-frame παρεμβάλλονται από key-frames μεταξύ του προηγούμενου και του επόμενου key-frame. Η τιμή πριν/μετά το πρώτο/τελευταίο key-frame υπολογίζεται από την κλάση [Extrapolation](../../com.aspose.threed/extrapolation).
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Δημιουργήστε ένα νέο key frame στην καθορισμένη καμπύλη |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Επιστρέφει το bias που χρησιμοποιείται στην TCB spline |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Επιστρέφει το continuity που χρησιμοποιείται στην TCB spline |
| [getFlat()](#getFlat--) | Λαμβάνει ή ορίζει αν το key frame είναι επίπεδο. |
| [getIndependentTangent()](#getIndependentTangent--) | Επιστρέφει εάν τα out και next in tangents είναι ανεξάρτητα. |
| [getInterpolation()](#getInterpolation--) | Επιστρέφει τον τύπο παρεμβολής του key, το list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η δειγματοληπτική τιμή. |
| [getNextInTangent()](#getNextInTangent--) | Επιστρέφει το επόμενο in (αριστερό) tangent σε αυτό το key frame. |
| [getNextInWeight()](#getNextInWeight--) | Επιστρέφει το επόμενο in (αριστερό) weight σε αυτό το key frame. |
| [getOutTangent()](#getOutTangent--) | Επιστρέφει το out (δεξιό) tangent σε αυτό το key frame. |
| [getOutWeight()](#getOutWeight--) | Επιστρέφει το out (δεξιό) weight σε αυτό το key frame. |
| [getStepMode()](#getStepMode--) | Επιστρέφει τη λειτουργία βήματος του key. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Επιστρέφει τη λειτουργία βάρους tangent του key. |
| [getTension()](#getTension--) | Επιστρέφει το tension που χρησιμοποιείται στην TCB spline |
| [getTime()](#getTime--) | Επιστρέφει τη θέση χρόνου του key frame list.data[index], μετρημένη σε δευτερόλεπτα. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Επιστρέφει ότι το tangent είναι ανεξάρτητο από το χρόνο |
| [getValue()](#getValue--) | Επιστρέφει την τιμή του key-frame. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Ορίζει το bias που χρησιμοποιείται στην TCB spline |
| [setContinuity(float value)](#setContinuity-float-) | Ορίζει το continuity που χρησιμοποιείται στην TCB spline |
| [setFlat(boolean value)](#setFlat-boolean-) | Λαμβάνει ή ορίζει αν το key frame είναι επίπεδο. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Ορίζει ότι οι εξωτερικές και οι επόμενες εσωτερικές εφαπτόμενες είναι ανεξάρτητες. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Ορίζει τον τύπο παρεμβολής του κλειδιού, το list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η δειγματοληπτική τιμή. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Ορίζει την επόμενη εσωτερική (αριστερή) εφαπτόμενη σε αυτό το πλαίσιο κλειδιού. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Ορίζει το επόμενο εσωτερικό (αριστερό) βάρος σε αυτό το πλαίσιο κλειδιού. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Ορίζει την εξωτερική (δεξιά) εφαπτόμενη σε αυτό το πλαίσιο κλειδιού. |
| [setOutWeight(float value)](#setOutWeight-float-) | Ορίζει το εξωτερικό (δεξί) βάρος σε αυτό το πλαίσιο κλειδιού. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Ορίζει τη λειτουργία βήματος του κλειδιού. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Ορίζει τη λειτουργία βάρους εφαπτομένης του κλειδιού. |
| [setTension(float value)](#setTension-float-) | Ορίζει την ένταση που χρησιμοποιείται στην καμπύλη TCB. |
| [setTime(double value)](#setTime-double-) | Ορίζει τη χρονική θέση του πλαισίου κλειδιού list.data[index], μετρημένη σε δευτερόλεπτα. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Ορίζει ότι η εφαπτόμενη είναι ανεξάρτητη από το χρόνο. |
| [setValue(float value)](#setValue-float-) | Ορίζει την τιμή του πλαισίου κλειδιού. |
| [toString()](#toString--) | Λαμβάνει την αναπαράσταση συμβολοσειράς του πλαισίου κλειδιού. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Δημιουργήστε ένα νέο key frame στην καθορισμένη καμπύλη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Η καμπύλη στην οποία θα δημιουργηθεί το πλαίσιο κλειδιού. |
| χρόνος | double | Η χρονική θέση του πλαισίου κλειδιού. |

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
### getBias() {#getBias--}
```
public float getBias()
```


Επιστρέφει το bias που χρησιμοποιείται στην TCB spline

**Returns:**
float - η προκατάληψη που χρησιμοποιείται στην καμπύλη TCB.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContinuity() {#getContinuity--}
```
public float getContinuity()
```


Επιστρέφει το continuity που χρησιμοποιείται στην TCB spline

**Returns:**
float - η συνέχεια που χρησιμοποιείται στην καμπύλη TCB.
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Λάβετε ή ορίστε εάν το πλαίσιο κλειδιού είναι επίπεδο. Το πλαίσιο κλειδιού πρέπει να είναι επίπεδο εάν το επόμενο ή το προηγούμενο πλαίσιο κλειδιού έχει την ίδια τιμή. Ένα επίπεδο πλαίσιο κλειδιού έχει επίπεδες εφαπτόμενες και σταθερή παρεμβολή.

**Returns:**
boolean - Λάβετε ή ορίστε εάν το πλαίσιο κλειδιού είναι επίπεδο. Το πλαίσιο κλειδιού πρέπει να είναι επίπεδο εάν το επόμενο ή το προηγούμενο πλαίσιο κλειδιού έχει την ίδια τιμή. Ένα επίπεδο πλαίσιο κλειδιού έχει επίπεδες εφαπτόμενες και σταθερή παρεμβολή.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Επιστρέφει εάν τα out και next in tangents είναι ανεξάρτητα.

**Returns:**
boolean - οι εξωτερικές και οι επόμενες εσωτερικές εφαπτόμενες είναι ανεξάρτητες.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Επιστρέφει τον τύπο παρεμβολής του key, το list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η δειγματοληπτική τιμή.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Επιστρέφει το επόμενο in (αριστερό) tangent σε αυτό το key frame.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Επιστρέφει το επόμενο in (αριστερό) weight σε αυτό το key frame.

**Returns:**
float - το επόμενο εσωτερικό (αριστερό) βάρος σε αυτό το πλαίσιο κλειδιού.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Επιστρέφει το out (δεξιό) tangent σε αυτό το key frame.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Επιστρέφει το out (δεξιό) weight σε αυτό το key frame.

**Returns:**
float - το εξωτερικό (δεξί) βάρος σε αυτό το πλαίσιο κλειδιού.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Λαμβάνει τη λειτουργία βήματος του κλειδιού. Εάν ο τύπος παρεμβολής είναι [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), το list.data[index] αποφασίζει ποια τιμή του πλαισίου κλειδιού θα χρησιμοποιηθεί κατά την παρεμβολή. Ένα [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) σημαίνει ότι θα χρησιμοποιηθεί η τιμή του αριστερού πλαισίου κλειδιού. Ένα [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) σημαίνει ότι θα χρησιμοποιηθεί η τιμή του επόμενου δεξιού πλαισίου κλειδιού.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Λαμβάνει τη λειτουργία βάρους εφαπτομένης του κλειδιού. Η εξωτερική εφαπτόμενη ή η επόμενη εσωτερική εφαπτόμενη μπορεί να προσαρμοστεί επιλέγοντας το σωστό [WeightedMode](../../com.aspose.threed/weightedmode).

**Returns:**
int - η λειτουργία βάρους εφαπτομένης του κλειδιού. Η εξωτερική εφαπτόμενη ή η επόμενη εσωτερική εφαπτόμενη μπορεί να προσαρμοστεί επιλέγοντας το σωστό [WeightedMode](../../com.aspose.threed/weightedmode).
### getTension() {#getTension--}
```
public float getTension()
```


Επιστρέφει το tension που χρησιμοποιείται στην TCB spline

**Returns:**
float - τάση που χρησιμοποιείται σε TCB spline
### getTime() {#getTime--}
```
public double getTime()
```


Επιστρέφει τη θέση χρόνου του key frame list.data[index], μετρημένη σε δευτερόλεπτα.

**Returns:**
double - η χρονική θέση του πλαισίου-κλειδιού list.data[index], μετρημένη σε δευτερόλεπτα.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Επιστρέφει ότι το tangent είναι ανεξάρτητο από το χρόνο

**Returns:**
boolean - η εφαπτομένη είναι ανεξάρτητη από το χρόνο
### getValue() {#getValue--}
```
public float getValue()
```


Επιστρέφει την τιμή του key-frame.

**Returns:**
float - η τιμή του πλαισίου-κλειδιού.
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




### setBias(float value) {#setBias-float-}
```
public void setBias(float value)
```


Ορίζει το bias που χρησιμοποιείται στην TCB spline

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Ορίζει το continuity που χρησιμοποιείται στην TCB spline

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Λάβετε ή ορίστε εάν το πλαίσιο κλειδιού είναι επίπεδο. Το πλαίσιο κλειδιού πρέπει να είναι επίπεδο εάν το επόμενο ή το προηγούμενο πλαίσιο κλειδιού έχει την ίδια τιμή. Ένα επίπεδο πλαίσιο κλειδιού έχει επίπεδες εφαπτόμενες και σταθερή παρεμβολή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Ορίζει ότι οι εξωτερικές και οι επόμενες εσωτερικές εφαπτόμενες είναι ανεξάρτητες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Ορίζει τον τύπο παρεμβολής του κλειδιού, το list.data[index] ορίζει τον αλγόριθμο με τον οποίο υπολογίζεται η δειγματοληπτική τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Νέα τιμή |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Ορίζει την επόμενη εσωτερική (αριστερή) εφαπτόμενη σε αυτό το πλαίσιο κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Ορίζει το επόμενο εσωτερικό (αριστερό) βάρος σε αυτό το πλαίσιο κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Ορίζει την εξωτερική (δεξιά) εφαπτόμενη σε αυτό το πλαίσιο κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Ορίζει το εξωτερικό (δεξί) βάρος σε αυτό το πλαίσιο κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Ορίζει τη λειτουργία βήματος του κλειδιού. Εάν ο τύπος παρεμβολής είναι [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] αποφασίζει ποια τιμή πλαισίου-κλειδιού θα χρησιμοποιηθεί κατά την παρεμβολή. Ένα [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) σημαίνει ότι η τιμή του αριστερού πλαισίου-κλειδιού θα χρησιμοποιηθεί. Ένα [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) σημαίνει ότι η τιμή του επόμενου δεξιού πλαισίου-κλειδιού θα χρησιμοποιηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Νέα τιμή |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Ορίζει τη λειτουργία βάρους εφαπτομένης του κλειδιού. Η εξωτερική εφαπτομένη ή η επόμενη εσωτερική εφαπτομένη μπορεί να προσαρμοστεί επιλέγοντας τη σωστή [WeightedMode](../../com.aspose.threed/weightedmode)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Ορίζει την ένταση που χρησιμοποιείται στην καμπύλη TCB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Ορίζει τη χρονική θέση του πλαισίου κλειδιού list.data[index], μετρημένη σε δευτερόλεπτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Ορίζει ότι η εφαπτόμενη είναι ανεξάρτητη από το χρόνο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Ορίζει την τιμή του πλαισίου κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Νέα τιμή |

### toString() {#toString--}
```
public String toString()
```


Λαμβάνει την αναπαράσταση συμβολοσειράς του πλαισίου κλειδιού.

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

