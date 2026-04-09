---
title: NurbsDirection
second_title: Aspose.3D for Java API Reference
description: Ένα 3D  έχει δύο κατευθύνσεις, η  και η  η  ορίζει δεδομένα για κάθε κατεύθυνση.
type: docs
weight: 113
url: /el/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

Ένα 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) έχει δύο κατευθύνσεις, το [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) και το [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), το [NurbsDirection](../../com.aspose.threed/nurbsdirection) ορίζει δεδομένα για κάθε κατεύθυνση. Μια κατεύθυνση είναι στην πραγματικότητα μια καμπύλη NURBS, που σημαίνει ότι ορίζεται επίσης από το [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), ένα [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors), και ένα σύνολο βαρυμενών σημείων ελέγχου (ορίζονται στο [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Δημιουργήστε ένα νέο στιγμιότυπο του [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των σημείων ελέγχου στην τρέχουσα κατεύθυνση. |
| [getDegree()](#getDegree--) | Λαμβάνει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1 |
| [getDivisions()](#getDivisions--) | Λαμβάνει τον αριθμό των διαιρέσεων μεταξύ γειτονικών σημείων ελέγχου στην τρέχουσα κατεύθυνση. |
| [getKnotVectors()](#getKnotVectors--) | Λαμβάνει το διάνυσμα κόμβων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Λαμβάνει την πολλαπλότητα. |
| [getOrder()](#getOrder--) | Λαμβάνει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης. |
| [getType()](#getType--) | Λαμβάνει τον τύπο της τρέχουσας κατεύθυνσης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Ορίζει τον αριθμό των σημείων ελέγχου στην τρέχουσα κατεύθυνση. |
| [setDegree(int value)](#setDegree-int-) | Ορίζει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1. |
| [setDivisions(int value)](#setDivisions-int-) | Ορίζει τον αριθμό των διαιρέσεων μεταξύ γειτονικών σημείων ελέγχου στην τρέχουσα κατεύθυνση. |
| [setOrder(int value)](#setOrder-int-) | Ορίζει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Ορίζει τον τύπο της τρέχουσας κατεύθυνσης. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Δημιουργήστε ένα νέο στιγμιότυπο του [NurbsDirection](../../com.aspose.threed/nurbsdirection)

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
### getCount() {#getCount--}
```
public int getCount()
```


Λαμβάνει τον αριθμό των σημείων ελέγχου στην τρέχουσα κατεύθυνση.

**Returns:**
int - ο αριθμός των σημείων ελέγχου στην τρέχουσα κατεύθυνση.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Λαμβάνει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1

**Returns:**
int - ο βαθμός μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Λαμβάνει τον αριθμό των διαιρέσεων μεταξύ γειτονικών σημείων ελέγχου στην τρέχουσα κατεύθυνση.

**Returns:**
int - ο αριθμός των διαιρέσεων μεταξύ γειτονικών σημείων ελέγχου στην τρέχουσα κατεύθυνση.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Λαμβάνει το διάνυσμα κόμβων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS.

**Returns:**
java.util.List<java.lang.Double> - το διάνυσμα κόμβων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Λαμβάνει την πολλαπλότητα.

**Returns:**
java.util.List<java.lang.Integer> - η πολλαπλότητα.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Λαμβάνει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης.

**Returns:**
int - η τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης.
### getType() {#getType--}
```
public NurbsType getType()
```


Λαμβάνει τον τύπο της τρέχουσας κατεύθυνσης.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
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




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Ορίζει τον αριθμό των σημείων ελέγχου στην τρέχουσα κατεύθυνση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Ορίζει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Order - 1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Ορίζει τον αριθμό των διαιρέσεων μεταξύ γειτονικών σημείων ελέγχου στην τρέχουσα κατεύθυνση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Ορίζει την τάξη μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Ορίζει τον τύπο της τρέχουσας κατεύθυνσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Νέα τιμή |

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

