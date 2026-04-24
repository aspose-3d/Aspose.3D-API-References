---
title: EndPoint
second_title: Aspose.3D for Java API Reference
description: Το σημείο τέλους για την περικοπή της καμπύλης μπορεί να είναι μια τιμή παραμέτρου ή ένα καρτεσιανό σημείο.
type: docs
weight: 51
url: /el/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Το τελικό σημείο για περικοπή της καμπύλης, μπορεί να είναι μια τιμή παραμέτρου ή ένα καρτεσιανό σημείο.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Δομήστε ένα [EndPoint](../../com.aspose.threed/endpoint) από ένα καρτεσιανό σημείο. |
| [EndPoint(double v)](#EndPoint-double-) | Δομήστε ένα [EndPoint](../../com.aspose.threed/endpoint) από μια πραγματική παράμετρο. |
| [EndPoint()](#EndPoint--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Δημιουργήστε ένα σημείο τέλους με μέτρηση σε μοίρες. |
| [fromRadian(double degree)](#fromRadian-double-) | Δημιουργήστε ένα σημείο τέλους με μέτρηση σε ακτίνια. |
| [getAsPoint()](#getAsPoint--) | Λαμβάνει το σημείο τέλους ως καρτεσιανό σημείο, ή ρίχνει μια εξαίρεση. |
| [getAsValue()](#getAsValue--) | Λαμβάνει το σημείο τέλους ως πραγματική παράμετρο, ή ρίχνει μια εξαίρεση. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Είναι το σημείο τέλους καρτεσιανό σημείο; |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναπαράσταση συμβολοσειράς του τρέχοντος σημείου τέλους. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Δομήστε ένα [EndPoint](../../com.aspose.threed/endpoint) από ένα καρτεσιανό σημείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Σημείο για κατασκευή |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Δομήστε ένα [EndPoint](../../com.aspose.threed/endpoint) από μια πραγματική παράμετρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | double | Η πραγματική αριθμητική παράμετρος για την κατασκευή ενός σημείου τέλους |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Clone current instance

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Δημιουργήστε ένα σημείο τέλους με μέτρηση σε μοίρες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μοίρες | double | Η τιμή σε μοίρες |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Δημιουργήστε ένα σημείο τέλους με μέτρηση σε ακτίνια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μοίρες | double | Η τιμή σε ακτίνια |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Λαμβάνει το σημείο τέλους ως καρτεσιανό σημείο, ή ρίχνει μια εξαίρεση.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Λαμβάνει το σημείο τέλους ως πραγματική παράμετρο, ή ρίχνει μια εξαίρεση.

**Returns:**
double - το σημείο τέλους ως πραγματική παράμετρο, ή ρίχνει μια εξαίρεση.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isCartesianPoint() {#isCartesianPoint--}
```
public boolean isCartesianPoint()
```


Είναι το σημείο τέλους καρτεσιανό σημείο;

**Returns:**
boolean - Είναι το σημείο τέλους καρτεσιανό σημείο;
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


Επιστρέφει μια αναπαράσταση συμβολοσειράς του τρέχοντος σημείου τέλους.

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

