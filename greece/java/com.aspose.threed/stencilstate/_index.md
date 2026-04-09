---
title: StencilState
second_title: Aspose.3D for Java API Reference
description: Καταστάσεις stencil ανά πρόσωπο.
type: docs
weight: 175
url: /el/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Καταστάσεις stencil ανά πρόσωπο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με ένα καθορισμένο αντικείμενο. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Λαμβάνει τη συνάρτηση σύγκρισης που χρησιμοποιείται στη δοκιμή στένσιλ |
| [getDepthFailAction()](#getDepthFailAction--) | Λαμβάνει τη δράση στένσιλ όταν η δοκιμή στένσιλ περνά αλλά η δοκιμή βάθους αποτυγχάνει. |
| [getFailAction()](#getFailAction--) | Λαμβάνει τη δράση στένσιλ όταν η δοκιμή στένσιλ αποτυγχάνει. |
| [getPassAction()](#getPassAction--) | Λαμβάνει τη δράση στένσιλ όταν τόσο η δοκιμή στένσιλ όσο και η δοκιμή βάθους περνούν. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την περίπτωση. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Ορίζει τη συνάρτηση σύγκρισης που χρησιμοποιείται στη δοκιμή στένσιλ |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Ορίζει τη δράση στένσιλ όταν η δοκιμή στένσιλ περνά αλλά η δοκιμή βάθους αποτυγχάνει. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Ορίζει τη δράση στένσιλ όταν η δοκιμή στένσιλ αποτυγχάνει. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Ορίζει τη δράση στένσιλ όταν τόσο η δοκιμή στένσιλ όσο και η δοκιμή βάθους περνούν. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με ένα καθορισμένο αντικείμενο.

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
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


Λαμβάνει τη συνάρτηση σύγκρισης που χρησιμοποιείται στη δοκιμή στένσιλ

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Λαμβάνει τη δράση στένσιλ όταν η δοκιμή στένσιλ περνά αλλά η δοκιμή βάθους αποτυγχάνει.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Λαμβάνει τη δράση στένσιλ όταν η δοκιμή στένσιλ αποτυγχάνει.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Λαμβάνει τη δράση στένσιλ όταν τόσο η δοκιμή στένσιλ όσο και η δοκιμή βάθους περνούν.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την περίπτωση.

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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


Ορίζει τη συνάρτηση σύγκρισης που χρησιμοποιείται στη δοκιμή στένσιλ

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Νέα τιμή |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Ορίζει τη δράση στένσιλ όταν η δοκιμή στένσιλ περνά αλλά η δοκιμή βάθους αποτυγχάνει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Νέα τιμή |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Ορίζει τη δράση στένσιλ όταν η δοκιμή στένσιλ αποτυγχάνει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Νέα τιμή |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Ορίζει τη δράση στένσιλ όταν τόσο η δοκιμή στένσιλ όσο και η δοκιμή βάθους περνούν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Νέα τιμή |

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

