---
title: FVector3
second_title: Aspose.3D for Java API Reference
description: Διανυσμα float με τρία στοιχεία.
type: docs
weight: 60
url: /el/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

Διανυσμα float με τρία στοιχεία.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Αρχικοποιεί μια νέα παρουσία του [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Αρχικοποιεί μια νέα παρουσία του [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Αρχικοποιεί μια νέα παρουσία του [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [x](#x) | Το στοιχείο x. |
| [y](#y) | Το στοιχείο y. |
| [z](#z) | Το στοιχείο y. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Operator overloading |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Συγκεκριμένος τελεστής μετατροπής για μετατροπή του FVector3 σε Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Γινόμενο διανυσματικό δύο διανυσμάτων. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | Το διανύσμα κλίμακας μονάδας με όλα τα συστατικά ίσα με 1 |
| [getZero()](#getZero--) | Το μηδενικό διανύσμα. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Υπερφόρτωση τελεστή |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Operator overloading |
| [normalize()](#normalize--) | Κανονικοποιεί αυτήν την instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Operator overloading |
| [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Αρχικοποιεί μια νέα παρουσία του [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | X component of the vector |
| y | float | Y component of the vector |
| z | float | Συστατικό Z του διανύσματος |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Αρχικοποιεί μια νέα παρουσία του [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 σε τύπο double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Αρχικοποιεί μια νέα παρουσία του [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 σε τύπο double |

### FVector3() {#FVector3--}
```
public FVector3()
```


### x {#x}
```
public float x
```


Το στοιχείο x.

### y {#y}
```
public float y
```


Το στοιχείο y.

### z {#z}
```
public float z
```


Το στοιχείο y.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Operator overloading

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | First vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Second vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Clone current instance

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Συγκεκριμένος τελεστής μετατροπής για μετατροπή του FVector3 σε Vector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 σε τύπο float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Γινόμενο διανυσματικό δύο διανυσμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Τιμή δεξιάς πλευράς. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


Το διανύσμα κλίμακας μονάδας με όλα τα συστατικά ίσα με 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


Το μηδενικό διανύσμα.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* Υπερφόρτωση τελεστή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | First vector |
| b | float | Second vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Operator overloading

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Διάνυσμα εισόδου |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Κανονικοποιεί αυτήν την instance.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- Operator overloading

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | First vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Second vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String - Αναπαράσταση κειμένου αυτού του διανύσματος.
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

